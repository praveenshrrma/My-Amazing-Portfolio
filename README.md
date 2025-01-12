## 🌍 Live Hosted App

[![Horizon Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20Now-brightgreen?style=for-the-badge)](https://praveensharrma.netlify.app)  
*(Right-click the link and select "Open link in new tab")*

---

## 📚 Introduction
This interactive and visually engaging website highlights a diverse range of projects I have built, including e-commerce platforms, AI-powered SaaS applications, real estate management systems, and more.
Built with modern technologies like React, Tailwind CSS, GSAP, and Lenis, this portfolio is not just a collection of past work but a reflection of my passion for creating seamless, user-friendly web applications. Smooth animations, responsive layouts, and a smooth scroll experience come together to demonstrate both my technical skills and my ability to craft intuitive, visually appealing user experiences.

- 💡 **Key Features**: Bank account linking, real-time transaction tracking, fund transfers, and more.

---

## ⚙️ Tech Used

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)  
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)  
![Appwrite](https://img.shields.io/badge/Appwrite-ff6600?style=for-the-badge&logo=appwrite&logoColor=white)  
![Plaid](https://img.shields.io/badge/Plaid-007b5e?style=for-the-badge&logo=plaid&logoColor=white)  
![Dwolla](https://img.shields.io/badge/Dwolla-00bfae?style=for-the-badge&logo=dwolla&logoColor=white)  
![React Hook Form](https://img.shields.io/badge/React%20Hook%20Form-EC4A2A?style=for-the-badge&logo=react&logoColor=white)  
![Zod](https://img.shields.io/badge/Zod-2c3e50?style=for-the-badge&logo=typescript&logoColor=white)  
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white)  
![Chart.js](https://img.shields.io/badge/Chart.js-F5B400?style=for-the-badge&logo=chart.js&logoColor=white)  
![ShadCN](https://img.shields.io/badge/ShadCN-1D4ED8?style=for-the-badge&logo=react&logoColor=white)

---

## 🔋 Features
👉 **Authentication**: Ultra-secure **SSR authentication** with proper validations and authorization.  

👉 **Connect Banks**: Integration with **Plaid** to securely link multiple bank accounts.  

👉 **Home Page**: Provides a comprehensive overview, including the total balance across all linked accounts, recent transactions, and expenditure breakdown by category.  

👉 **My Banks**: Displays all connected bank accounts, their balances, and transaction details.  

👉 **Transaction History**: Allows easy pagination and filtering for viewing transactions by account or category.  

👉 **Real-Time Updates**: Automatically reflects changes across the platform when new bank accounts are added or transactions are made.  

👉 **Funds Transfer**: Allows users to transfer funds to other accounts via **Dwolla**, with recipient bank IDs and necessary fields.  

👉 **Responsiveness**: Fully responsive design, ensuring a consistent experience on mobile, tablet, and desktop.

---

## ⚙️ Planned Optimizations
- **Improve Speed**: I would focus on making the app load faster by using **Static Site Generation (SSG)** for important pages. This would help pages load quicker and improve search engine rankings.
  
- **Optimize API Calls**: I would work on reducing the time it takes to get data from services like Plaid and Dwolla by adding a caching system. This would make the app feel faster and more responsive.

- **Real-Time Updates**: To make updates smoother when a user connects new bank accounts or makes a transaction, I would explore **WebSockets**. This would allow the app to instantly show new data without needing to reload the page.

- **Better User Interface**: I would add features like **dark mode** to make the app more customizable for users. I would also focus on improving accessibility, making sure the app works well for users with disabilities.

- **Optimize Data Handling**: For large amounts of transaction data, I would implement **pagination** to break the data into smaller chunks, making it easier to navigate.

---

## 📚 Lessons Learned
- **Security**: Handling sensitive financial data requires implementing secure API calls and strict data validation (e.g., OAuth with Plaid).
  
- **Complex Integrations**: Integrating multiple third-party services (Plaid, Dwolla) requires careful API management and adherence to rate limits.
  
- **Real-Time Functionality**: Managing real-time data across multiple users and banks required careful design of state management and WebSocket connections.
