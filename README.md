# ATS Resume Expert

Welcome to the **ATS Resume Expert**, a powerful AI-based tool that helps you evaluate your resume against a job description and suggests areas for improvement. This app utilizes Google's Gemini AI models to analyze your resume and provide insights on how to make it more aligned with specific job requirements.

## 🌐 Live Demo

Check out the deployed version of the app here: [ATS Resume Expert](https://resume-tracking-system-gemini.streamlit.app/)

## Features

- **Tell me About the resume:** Get a detailed evaluation of your resume by a simulated HR professional.
- **How can I improve my Skills:** Receive suggestions on which skills to improve or acquire to better match the job description.
- **Percentage match:** Get a percentage score of how well your resume aligns with the job description, along with missing keywords and final recommendations.

## How It Works

1. **Upload your resume** in PDF format.
2. **Provide a job description** by typing or pasting it in the input box.
3. Select one of the following options:
   - **Tell me About the resume:** Get a detailed analysis of how well your resume aligns with the job description.
   - **How can I improve my Skills:** Get suggestions on skills you should develop or improve based on the job description.
   - **Percentage match:** Receive a match percentage based on your resume and job description, along with missing keywords and recommendations.

## Technologies Used

- **Streamlit**: Used for the frontend of the application.
- **Google Gemini AI**: Used for generating responses and content.
- **PDF2Image**: Converts PDF to images for further processing.
- **PIL (Pillow)**: For image processing.
- **Base64**: Encodes the image into a base64 string to be passed to the AI model.

## Getting Started

### Prerequisites

Make sure you have Python installed. You can install the required dependencies using `pip`:

```bash
pip install streamlit google-generativeai pdf2image pillow python-dotenv
```
