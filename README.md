# DeepSeek Resume Extractor (DeepSeek OCR + AGNO Agent)

A Colab-ready pipeline that runs DeepSeek OCR on a T4 GPU to extract text from resumes, then feeds the OCR output to an AGNO-based AI agent to extract structured resume fields such as:
- Name
- E-mail
- Skills
- Education (GPA, 12th and 10th percentage/GPA)
- Experience

## Quick links
- DeepSeek-OCR Huggingface - https://huggingface.co/deepseek-ai/DeepSeek-OCR
- Generate Gemini API Key - https://ai.google.dev/gemini-api/docs/api-key
- Agno Documentation - https://docs.agno.com/examples/models/gemini/basic

## Getting started (Colab)
1. Open the Colab notebook .
2. Select Runtime > Change runtime type > GPU > NVIDIA T4.
3. Run the setup cell to install dependencies and download model weights.
4. Upload a resume PDF or image, or mount from Google Drive.
5. Run the OCR cell to generate raw text output.
6. Run the AGNO agent cell to parse structured fields from the OCR output.

