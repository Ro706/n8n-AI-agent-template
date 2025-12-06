# 📄 PDF Summarization Workflow (n8n)

This n8n workflow automates the process of summarizing PDF documents using AI. It allows users to submit a form with a PDF file, extracts the content, processes it through an AI model, and returns a concise summary in a downloadable format.

## 🚀 Workflow Overview

The workflow consists of the following nodes:

1. **On Form Submission**  
   Triggers the workflow when a user submits the PDF summarization form.

2. **Extract from File**  
   Retrieves the uploaded PDF file and prepares it for processing.

3. **AI Agent**  
   Uses an AI model (Google Gemini Chat Model) to generate a summary of the extracted content.

4. **Edit Fields**  
   Allows manual review or editing of the AI-generated summary before final output.

5. **Convert to File**  
   Converts the final summary into a downloadable text file.

## 🛠️ Requirements

- n8n v2.0 or later
- Access to Google Gemini or compatible AI model
- Form integration for PDF upload
- Proper permissions to read/write files

## 📥 Input

- PDF file uploaded via form
- Optional metadata (e.g., title, description)

## 📤 Output

- AI-generated summary in `.txt` format
- Optionally editable before final conversion

## 🧠 Use Cases

- Quickly summarize lengthy reports or research papers
- Extract key insights from contracts or legal documents
- Generate digestible content from technical PDFs

## 📌 Notes

- Ensure the AI model is properly authenticated and configured.
- Large PDFs may require additional memory or timeout adjustments.
- Manual editing step is optional but recommended for accuracy.

## 🧪 Example

Submit a PDF via the form → AI summarizes → You review/edit → Download summary.

---

