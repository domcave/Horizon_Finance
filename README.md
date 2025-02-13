# Horizon_Finance
Personal financial insights and guidance for those at different stages of life

## About the Project 

### PNC Challenge at the SheInnovates Hackathon 2025
Design an **innovative** and **customer focused** solution that onsiders the **specific financials needs** and **goals of customers** at **different stages or life events**.

### Inspiration  
We were inspired by the need for accessible and personalized financial guidance. Many people struggle with planning for major life events—whether it's buying a home, getting married, or preparing for retirement—because financial advice can be generic and disconnected from their real financial situation. We wanted to build a tool that integrates directly with a user's bank data to provide tailored recommendations based on their actual financial habits.  

### What We Learned  
Throughout this project, we gained valuable experience working with financial data, API integrations, and full-stack development. Specifically, we:  
- Learned how to securely connect and retrieve user bank data using the **Plaid API**.  
- Built a **Flask** backend that serves as a bridge between the frontend and third-party APIs, including **Plaid** and **OpenAI**.  
- Worked with **PostgreSQL** to store and manage both user account and financial data.  
- Developed a **React** frontend to display financial insights in an intuitive and user-friendly way.  
- Strengthened our debugging and problem-solving skills, especially in handling API requests and responses.  

### How We Built It  
Our project consists of three main components:  

- **Frontend:** Built with **React**, this provides an interactive dashboard where users can view financial insights and request guidance.  
- **Backend API:** A custom **Flask** API that handles requests from the frontend, interacts with **Plaid** to fetch financial data, processes user queries using **OpenAI**, and stores structured data in **PostgreSQL**.  
- **APIs & Data Sources:**  
  - **Plaid API**: Fetches users' financial transactions and account balances.  
  - **OpenAI API**: Generates personalized financial recommendations based on user data.  
  - **PostgreSQL**: Stores user preferences and processed financial insights.  

### Challenges We Faced  
One of the biggest challenges was working with multiple APIs and ensuring smooth communication between them. Specifically:  
- **Plaid API Integration:** Retrieving, formatting, and interpreting transaction data correctly was complex, especially handling different bank data formats.  
- **Custom API Development:** We had to create our own API to interface between the frontend, Plaid, and OpenAI. Debugging this was particularly difficult due to authentication issues, API rate limits, and handling real-time requests.  
- **Backend Debugging:** Since we were dealing with multiple external APIs, tracking down errors required extensive logging and testing.  

Despite these challenges, we successfully built a working prototype that provides real-time, data-driven financial guidance to users at different life stages. We’re excited about the potential of this project and how it can help people take control of their financial future. 🚀

## Using Horizon Finance
**We have deployed Horizon Finance!!!**
Use this link to see [Horizon Finance](http://horizonfinancelb-1989960674.us-east-1.elb.amazonaws.com/)

### Local Hosting Instructions
While you can technically setup the backend and frontend in any order, it is highly recommended to setup the backend first. The frontend/client interfaces with the backend extensively, so setting up the backend first is best-practice.
#### Step 1
Go to the [Horizon Finance Backend Repo](https://github.com/domcave/Horizon_Finance_backend.git) and follow the setup instructions.

#### Step 2 
Go to the [Horizon Finance Frontend Repo](https://github.com/domcave/Horizon_Finance_frontend.git) and follow the setup instructions.

#### Step 3
Open your http://localhost:3000 in a browser and get started using Horizon Finance!

## Backend
Link to [Horizon Finance Backend Repo](https://github.com/domcave/Horizon_Finance_backend.git)

Tools Used:
- Python
- Flask
- Plaid API
- OpenAI API
- PostgreSQL

## Frontend
Link to [Horizon Finance Frontend Repo](https://github.com/domcave/Horizon_Finance_frontend.git)

Tools Used:
- JavaScript
- React
- HTML
- CSS
- npm

