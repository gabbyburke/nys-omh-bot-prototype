OMH Chatbot Prototype: Deployment Instructions
1. Clone this repository to your local machine
2. Zip the full file (right click --> zip)
3. Navigate to Conversational Agents (https://conversational-agents.cloud.google.com/)
4. Select the correct project. Click "Create agent," then "Build your own."
5. Create an appropriate name, location, and time zone. Select "Playbook" as the conversation start.
6. Next to your new agent's name, click the 3 dots on the right hand side of the screen. Click "Restore."
7. Upload a local file. Find the .zip you created earlier. **Critical** Select "Use default settings" - this will let us bypass changes we will need to make to the agent (e.g., creating a new data store) and get the agent up and running more quickly.
8. Click "Restore." After a few moments, the agent will populate and you can start editing.

# OMH Chatbot Prototype

This repository contains the exported agent files for the Office of Mental Health Chatbot Prototype, built on Google's Conversational Agents platform (formerly Dialogflow CX).

This guide provides the necessary steps to restore this agent into your own Google Cloud project.

## 🚀 Deployment Instructions

Follow these steps carefully to deploy the agent from this repository.

1.  **Clone the Repository**
    Clone this repository to your local machine using the following command:
    ```bash
    git clone [https://github.com/gabbyburke/omh-bot-prototype.git](https://github.com/gabbyburke/omh-bot-prototype.git)
    ```

2.  **Compress the Files**
    Navigate to the cloned folder on your computer. Compress the entire `omh-bot-prototype` folder into a single `.zip` file. (e.g., right-click the folder and select "Compress" or "Send to > Compressed (zipped) folder").

3.  **Navigate to Conversational AI Console**
    Open the [Google Cloud Conversational AI Console](https://conversational-agents.cloud.google.com/) in your web browser.

4.  **Create a New Agent**
    * Ensure you have selected the correct Google Cloud project from the top bar.
    * Click **+ Create new agent**.
    * Select the **Build your own** option.

5.  **Configure Initial Agent Settings**
    * **Name:** Give your agent an appropriate name (e.g., "OMH-Chatbot").
    * **Location & Time Zone:** Select your desired region and time zone.
    * **Conversation Start:** Select **Playbook** from the dropdown menu.
    * Click **Save**.

6.  **Initiate Restore Process**
    Once the agent is created, you will be on the agent list screen. Find your new agent, click the **three-dot menu (⋮)** on the far right, and select **Restore**.

7.  **Upload and Configure Restore**
    * In the "Restore agent" window, select the **Upload** option.
    * Click **"select file"** and choose the `.zip` file you created in Step 2.

    > **⚠️ Critical Note**
    >
    > On the final restore options screen, you must select **"Use default settings."** This is crucial for bypassing initial configuration failures (related to components like Data Stores that don't exist in your new project). This allows you to configure these settings manually after the agent has been successfully restored.

8.  **Finalize the Restore**
    Click the final **Restore** button. After a few moments, the agent's flows, playbooks, and intents will populate the console, and you can begin editing and configuring it for your project.

---
*Last updated: July 17, 2025*
