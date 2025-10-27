# AI-Powered Presentation Generator

This project is a chat application built with React and Vite that allows a user to generate PowerPoint presentations using AI.

**Deployed Link:** [ADD YOUR DEPLOYED LINK HERE ONCE STEP 4 IS DONE]

---

### ⭐️ IMPORTANT NOTE: AI Integration Status

The live integration with the Google Gemini AI is built and ready, but is currently **pending a 24-hour quota activation** by Google Cloud.

To demonstrate the full, end-to-end functionality of the application, the chat has been temporarily connected to a **mocked JSON response**.

**To test:**
1.  Type any prompt into the chat.
2.  The app will simulate the AI response.
3.  The "Download Presentation" button will become active.
4.  Clicking the button will use `pptxgenjs` to generate a real `.pptx` file based on the mock data.

This successfully demonstrates the complete application workflow, from UI interaction to final file generation.

---

### Tech Stack

* **Frontend:** React (with Vite)
* **PowerPoint Generation:** `pptxgenjs`
* **AI (Pending):** Google Gemini (`gemini-2.5-pro-preview-05-06`)

### How to Run Locally

1.  Clone the repository:
    ```bash
    git clone [YOUR_REPOSITORY_URL_HERE]
    ```
2.  Navigate to the project directory:
    ```bash
    cd ai-ppt-chat
    ```
3.  Install dependencies:
    ```bash
    npm install
    ```
4.  Run the development server:
    ```bash
    npm run dev
    ```