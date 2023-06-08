# intel-oneAPI

#### Team Name - Jethakejabaz
#### Problem Statement - Open Innovation in Education 
#### Team Leader Email - sachinmishra4585@gmail.com

## A Brief of the Prototype:
  This section must include UML Daigrms and prototype description
  
  
  `Architecture Diagram`
  
  ![Screenshot_1](https://github.com/Kush134/intel-oneAPI-Jethakejabaz-/assets/37140352/f3ee9dfd-a5ba-4d39-81bf-eb951f341156)
  
  
  ![Screenshot_2](https://github.com/Kush134/intel-oneAPI-Jethakejabaz-/assets/37140352/bccf37d5-5dcc-4a45-afaf-51677b659d54)



![Screenshot_3](https://github.com/Kush134/intel-oneAPI-Jethakejabaz-/assets/37140352/91224c90-179f-4c7c-8a36-9d5856bef64e)



![Screenshot_4](https://github.com/Kush134/intel-oneAPI-Jethakejabaz-/assets/37140352/af2aa710-650f-459f-a40b-30374962b3b3)


  
## Tech Stack: 
   List Down all technologies used to Build the prototype **Clearly mentioning Intel® AI Analytics Toolkits, it's libraries and the SYCL/DCP++ Libraries used**
   
   **Intel Math Kernel Library (MKL) to optimize numerical computations.**

**Intel Distribution for Python or the Intel Data Analytics Acceleration Library (DAAL)** to perform data analytics tasks on the output of the GPT-3 API. These libraries provide optimized functions for data manipulation, statistics, and machine learning that can speed up processing.


   
   ![Screenshot_5](https://github.com/Kush134/intel-oneAPI-Jethakejabaz-/assets/37140352/d5e88507-9972-4837-89e8-31e48fcbad6d)

   
## Step-by-Step Code Execution Instructions:
  This Section must contain set of instructions required to clone and run the prototype, so that it can be tested and deeply analysed
  
  `Codie`
  An AI powered chatbot that is intended to help you with your Software Interview Preparation and doubts related to coding problems. Codie runs on the GPT-3 integrating with Intel One Api model, and is programmed specifically for Open Innovation in Education use case. 
   
   
##How to Install the extension

0. Download the build/ folder from [here](https://drive.google.com/drive/folders/1Rgn7SwjAYUYvbV8vGjwRazjggD3C0TEE?usp=share_link) and skip to step 4  And i have also added the build folder in this repo itself you can use that also. 

OR    

1. Clone/Download this repo  

2. At the root folder, create a .env file with the following content
```
REACT_APP_GPT_API = <OpenAI_API_KEY>
```
Since keys can't be uploaded on public repos, you will have to create your own API key from [OpenAI](https://platform.openai.com/account/api-keys).

3. Run the following commands
```
npm install
npm run build
```

4. Go to chrome://extensions  
 
5. Enable "Developer mode"

6. In the Developer options, click on "Load unpacked"  

7. Select the build/ folder from the repo

## Supported Platforms
Currently, Codie supports questions from the following platforms
- Leetcode
- AlgoExpert
- Hackerrank
- Geeksforgeeks
- Interviewbit

**Additionally, Codie doesn't not work during live tests or contests, and we don't condone or encourage cheating.**
 
  
## What I Learned:
   Write about the biggest learning you had while developing the prototype
