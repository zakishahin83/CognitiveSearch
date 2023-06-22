# 1- Create Cognitive Search

Steps to create Azure Cognitive Search Service:

1. Sign in to the Azure portal https://portal.azure.com.
2. Click the plus sign ("Create Resource") in the top-left corner.
3. Use the search bar to find "Azure Cognitive Search" or navigate to the resource through Web > Azure Cognitive Search.
4. Choose a subscription
5. Create a new or choose an existing resource group (location: westeurope)
![image](https://github.com/zakishahin83/CognitiveSearch/assets/137057041/75face86-f693-49d9-b9aa-3d2b0faa8b25)

Click Next (Keep default settings)
![image](https://github.com/zakishahin83/CognitiveSearch/assets/137057041/42dacbd6-a1ad-4152-a816-41ab30cbc486)

Click Next (Keep default settings)
![image](https://github.com/zakishahin83/CognitiveSearch/assets/137057041/347abb59-a9de-4052-afa6-818b06620b2c)

Click Next (Keep default settings)
Click Create

# 2- Create Storage Account to Host Data and add Sample Data

Steps to create a Storage Account to Host Data:
1. Create a storage account as the screenshot below and keep default settings:
![image](https://github.com/zakishahin83/CognitiveSearch/assets/137057041/de9d810b-cebe-4673-bc94-c2a1ff940359)

2. Create a container and upload sample data found here: https://github.com/zakishahin83/CognitiveSearch/tree/main/Sample%20Data
![image](https://github.com/zakishahin83/CognitiveSearch/assets/137057041/f006d976-6d1b-4ff9-90c7-cd0ec66aeb32)

# 3- Create a Search Index
1. Go in the portal to the 'Search Service' that you created earlier.
2. Click Import Data, and fill as below:
![image](https://github.com/zakishahin83/CognitiveSearch/assets/137057041/6f8e0004-69e4-41a3-99cd-1ba467b58d1f)
3. Click on Choose Existing Connection, and choose the container you have created in step 2
![image](https://github.com/zakishahin83/CognitiveSearch/assets/137057041/cfe3ffed-9385-48d7-b8f0-37687f42e1e5)
4. Click on Add Cognitive Skills (Optional)
5. Expand attach cognitive service, and click Create New Cogntive Services Resource **(In a new Tab)**
![image](https://github.com/zakishahin83/CognitiveSearch/assets/137057041/fe56f007-9172-49b3-be7d-b0356e800ba9)
**Note: The Cognitive Service and Search Service should be in the same region**
6. Choose the cognitive service you have created:
![image](https://github.com/zakishahin83/CognitiveSearch/assets/137057041/5fd46a42-5f3f-49b5-a68a-bc0cfc663dec)
7. Expand Add enrichments, and
 - Check 'Enable OCR'
 - Check 'Text Cognitive Skills'
 - Check 'Image Cognitive Skills'
![image](https://github.com/zakishahin83/CognitiveSearch/assets/137057041/d30c6406-44aa-46f8-817a-83a7ff62b22e)
8. Click on Customize Target Index; Note the following:
   In this view, you define how and what data you want to save in your index. An index exists out of json documents that all have the same structure.
   Notice that for every field you have following options:
   - Retrievable:
     Search API will be able to retrieve this field
   - Filterable:
     Search API will be able to filter on this field
   - Sortable:
     Search API will can sort on this field
   - Facetable:
     Search API can generate facets on this field
   - Searchable:
     Search API can search through this field
   - Analyzer:
     What kind of analyser can be used to search through your field. If you want to understand the differences between them.
   - Sugester:
     Enable this if you want to give your search input box an autosuggest functionality. This will not improve your search results, but only the usability of the frontend that you build. 
9. Check the following boxes as the screenshot below and schoose the language for the analyzer, as per the screenshot below:
![image](https://github.com/zakishahin83/CognitiveSearch/assets/137057041/5ebfdfd8-84c9-49cd-9ac6-a87957dbf763)
10. Click on Validate
![image](https://github.com/zakishahin83/CognitiveSearch/assets/137057041/c6a348f0-4fc0-47a4-a51d-631b17948c4b)



