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

# 3- Create Azure OpenAI Service and Deplpoy ChatGPT35 Turbo
1. Sign in to the Azure portal https://portal.azure.com
2. Search for Azure OpenAI and click Create
3. Fill the required information and click create
   ![image](https://github.com/zakishahin83/CognitiveSearch/assets/137057041/93fc8d72-6e20-4c95-b99d-4ae89de037f8)
4. Once create, open the resource and navigate to Azure OpenAI Studio
    ![image](https://github.com/zakishahin83/CognitiveSearch/assets/137057041/6a1238fa-c7ff-43b3-86a0-3e22a7ce2d37)
5. On the left Navigation, click on Models and then choose gpt-35-turbo, and then click Deploy
![image](https://github.com/zakishahin83/CognitiveSearch/assets/137057041/b7cf9f1c-9c2a-4302-82a8-a93fd88a1efe)
6. Once deployed successfully, On the left navigation and under Playground, click on Chat Tab.
7. Click on Add Your Data (Preview) and then click on Add a Data Source
8. From Select Data Source, choose Azure Blob Storage
   ![image](https://github.com/zakishahin83/CognitiveSearch/assets/137057041/b76f6cfc-6583-482c-bb8b-de0162b5483d)
9. Choose the storage account that we created in the previous lab, and then choose the container
10. Choose the Cognitive Search you have created in the previous lab.
     ![image](https://github.com/zakishahin83/CognitiveSearch/assets/137057041/d2ad2a7b-af5e-4b2f-ae82-88c66cfc21d3)
11. Click Save and Close.
12. It will take around 5 mins to proceed the the content.
13. Make sure the Limit responses to your data content is checked
14. Click "Deploy To" (top right) to Deploy the solution into a web app in Azure 
![image](https://github.com/zakishahin83/CognitiveSearch/assets/137057041/da0553a4-0a8e-44c2-a858-bd5288d4f749)
15. Fill the required parameters for the web app and click create
![image](https://github.com/zakishahin83/CognitiveSearch/assets/137057041/6ff72e0e-fd29-498e-81a0-f217e54eba09)
16. Note: It will take some time to get the authentication deployed.
17. Test the module based on the sample data.




