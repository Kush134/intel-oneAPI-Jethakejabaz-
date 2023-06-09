# intel-oneAPI

#### **Team Name** - Jethakejabaz
#### **Problem Statement** - Open Innovation in Education 
#### **Team Leader Email** - sachinmishra4585@gmail.com 
#### **Medium Blog** - [Codie: AI-Powered Chatbot Revolutionising Software Interview Preparation]('https://kushsah42.medium.com/codie-ai-powered-chatbot-revolutionising-software-interview-preparation-8284217565a7') 

## A Brief of the Prototype:
  *(This section must include UML Diagrams and prototype description)*

  
  `Codie`
    
An AI powered chatbot that is intended to help you with your Software Interview Preparation and doubts related to coding problems. Codie runs on the GPT-3 integrating with Intel One Api model, and is programmed specifically for Open Innovation in Education use case. 
  
  
  `Architecture Diagram`
  
  ![Screenshot_1](https://github.com/Kush134/intel-oneAPI-Jethakejabaz-/assets/37140352/f3ee9dfd-a5ba-4d39-81bf-eb951f341156)
  
  
  ![Screenshot_2](https://github.com/Kush134/intel-oneAPI-Jethakejabaz-/assets/37140352/bccf37d5-5dcc-4a45-afaf-51677b659d54)



![Screenshot_3](https://github.com/Kush134/intel-oneAPI-Jethakejabaz-/assets/37140352/91224c90-179f-4c7c-8a36-9d5856bef64e)



![Screenshot_4](https://github.com/Kush134/intel-oneAPI-Jethakejabaz-/assets/37140352/af2aa710-650f-459f-a40b-30374962b3b3)


  
## Tech Stack: 
   *(List Down all technologies used to Build the prototype **Clearly mentioning Intel® AI Analytics Toolkits, it's libraries and the SYCL/DCP++ Libraries used** )*
   
   * **Intel Math Kernel Library (MKL) to optimize numerical computations.**

* **Intel Distribution for Python or the Intel Data Analytics Acceleration Library (DAAL)** to perform data analytics tasks on the output of the GPT-3 API. These libraries provide optimized functions for data manipulation, statistics, and machine learning that can speed up processing.


   
   ![Screenshot_5](https://github.com/Kush134/intel-oneAPI-Jethakejabaz-/assets/37140352/d5e88507-9972-4837-89e8-31e48fcbad6d)

   
## Step-by-Step Code Execution Instructions:
  *(This Section must contain set of instructions required to clone and run the prototype, so that it can be tested and deeply analysed)*
   
   
### How to Install the extension

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

### Supported Platforms
Currently, Codie supports questions from the following platforms
- Leetcode
- AlgoExpert
- Hackerrank
- Geeksforgeeks
- Interviewbit

**Additionally, Codie doesn't not work during live tests or contests, and we don't condone or encourage cheating.**
 
  
## What We Learned:
   
✅ In our exhilarating hackathon experience, our team embarked on a mission to create Codie, an AI-powered chatbot for software interview preparation, using Intel OneAPI. Throughout this journey, we gained valuable insights and knowledge that expanded our understanding of AI development and its practical applications.

✅ First and foremost, we discovered the immense potential of Intel OneAPI. By harnessing its capabilities, we were able to optimize Codie's performance and tap into Intel's hardware prowess, unleashing its full power. OneAPI's unified programming model and extensive library support allowed us to maximize computational efficiency and deliver an exceptional user experience.

✅ We also learned the importance of seamless integration. By designing Codie as a Chrome extension, we eliminated the hassle of switching between tabs, providing users with convenient and uninterrupted access to Codie's wealth of knowledge. This integration not only enhanced user experience but also highlighted the value of creating solutions that seamlessly integrate with existing workflows.

✅ Lastly, we prioritized ethical considerations throughout the development process. We made sure that Codie did not operate during live tests or contests, discouraging any form of cheating and promoting integrity in the interview preparation process.

✅ Overall, our journey in creating Codie using Intel OneAPI was a tremendous learning experience. We gained valuable insights into the power of hardware acceleration, seamless integration, natural language processing, and ethical AI development. These lessons have not only enriched our understanding of AI technologies but also empowered us to create innovative solutions that make a positive impact in the field of software interview preparation.