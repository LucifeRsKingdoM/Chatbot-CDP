# Support Agent Chatbot for CDP

Welcome to the **Support Agent Chatbot for CDP** project! This chatbot is designed to assist users with "how-to" questions related to four popular Customer Data Platforms (CDPs): Segment, mParticle, Lytics, and Zeotap. It extracts relevant information directly from their official documentation, providing accurate and helpful responses.

## **Project Overview**

![Screenshot 2025-03-03 200922](https://github.com/user-attachments/assets/7e6a12b8-ad3a-43cb-95ab-de1142688d4c), ![Screenshot 2025-03-03 200922](https://github.com/user-attachments/assets/a6e5dd4e-ead9-4b59-ac48-5916ca0665f0), ![Screenshot 2025-03-03 201003](https://github.com/user-attachments/assets/cc94b5c7-ec3f-4145-bfd4-34af60a51d24)


### **Objective**

To build an intelligent chatbot that:

- Answers "how-to" questions related to Segment, mParticle, Lytics, and Zeotap.
- Extracts relevant information from the official documentation of these CDPs.
- Provides accurate guidance to users on various tasks and features.

### **Features**

1. **Answer "How-to" Questions**
   - Example: "How do I set up a new source in Segment?"
2. **Extract Information from Documentation**
   - Fetches relevant instructions directly from the provided documentation.
3. **Handle Variations in Questions**
   - Robust handling of differently phrased or irrelevant questions.

#### **Bonus Features**

- **Cross-CDP Comparisons**
  - Example: "How does Segment's audience creation process compare to Lytics'?"
- **Advanced "How-to" Questions**
  - Handles platform-specific, complex use cases and configurations.

---

## **Logos**

### **Platforms Supported**

| Platform      | 
| ------------- | 
| **Segment**   |      
| **mParticle** |      
| **Lytics**    |      
| **Zeotap**    |   

---

## 🛠️ Technologies Used  

### **Frontend (Client) 🎨**  
✅ **React.js** ⚛️  
✅ **Tailwind CSS** 🎨 (for beautiful UI)  
✅ **Framer Motion** ✨ (for smooth animations)  
✅ **Axios** 🔄 (for API calls)  
✅ **React Toastify** 🍞 (for notifications)  

### **Backend (Server) 🖥️**  
✅ **Node.js & Express.js** 🚀  
✅ **MySQL** 🛢️ (as the database instead of MongoDB)  
✅ **Sequelize ORM** 🗄️ (for database interactions)  
✅ **bcrypt.js** 🔐 (for password hashing)  
✅ **jsonwebtoken (JWT)** 🛡️ (for authentication)  
✅ **CORS & dotenv** 🌐 (for security & environment variables)  

### **Other Tools 🛠️**  
✅ **Concurrently** 🏃‍♂️ (to run frontend & backend in one command)  

## **How It Works**

1. **User Interaction**: Users can type their "how-to" questions into the chatbot interface.
2. **Processing**: The chatbot interprets the query and identifies the relevant platform (Segment, mParticle, Lytics, or Zeotap).
3. **Information Retrieval**: It fetches the corresponding section of the official documentation and extracts the required steps or guidance.
4. **Response**: The chatbot displays the extracted information in a user-friendly forma

## **How to Run**

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn package manager

### Steps

1. Clone the repository:
   ```bash
   [git clone https://github.com/LucifeRsKingdoM/Chatbot-CDP.git
   cd cdp-chatbot]
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
   or
   ```bash
   yarn install
   ```
3. Start the development server:
   ```bash
   npm run dev
   node server.js
   ```
   or
   ```bash
   yarn dev
   ```
4. Open your browser and visit:
   ```
   http://localhost:9000
   ```

---

## **Live Preview**

Check out the live version of the project [here](https://chatbot-cdp-slj7.vercel.app/).

---

## **Sample Preview**

Below is a preview of the chatbot interface:

![Screenshot 2025-01-14 193249](https://github.com/user-attachments/assets/9e252139-0f96-4d12-8ad3-66a2857ab9c3)

![Screenshot 2025-01-14 193305](https://github.com/user-attachments/assets/f1da1e78-e8c9-4d6f-ab64-e609ac568a24)

![Screenshot 2025-01-14 190309](https://github.com/user-attachments/assets/695e2ddb-d2be-46a8-a300-32733bdbdc5e)

---

## **Directory Structure**

```
cdp-chatbot/
├── src/
│   ├── components/
│   │   ├── ChatMessage.tsx
│   ├── App.tsx 
│   ├── data/
│   │   └── cdpData.ts
├── vite.config.ts
├── package.json
├── README.md
```

---

## **Future Enhancements**

- Add more CDPs and extend support.
- Implement machine learning for better question understanding.
- Enhance UI with more customization options.

---

## **License**

This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT).

---

Feel free to explore, contribute, and provide feedback! 🚀

