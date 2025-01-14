# Support Agent Chatbot for CDP

Welcome to the **Support Agent Chatbot for CDP** project! This chatbot is designed to assist users with "how-to" questions related to four popular Customer Data Platforms (CDPs): Segment, mParticle, Lytics, and Zeotap. It extracts relevant information directly from their official documentation, providing accurate and helpful responses.

## **Project Overview**

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

## **Languages and Tools Used**

- **React** (Frontend)
- **Vite** (Build Tool)
- **TypeScript** (Type Safety)
- **Lucide-react** (Icons and Components)

---

## **How It Works**

1. **User Interaction**: Users can type their "how-to" questions into the chatbot interface.
2. **Processing**: The chatbot interprets the query and identifies the relevant platform (Segment, mParticle, Lytics, or Zeotap).
3. **Information Retrieval**: It fetches the corresponding section of the official documentation and extracts the required steps or guidance.
4. **Response**: The chatbot displays the extracted information in a user-friendly format.

---

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

