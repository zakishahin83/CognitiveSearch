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
6. 





