# HumanTrace

HumanTrace is an AI-text detection application designed to analyze
admissions essays and identify text that is likely to be AI-generated.

## Project Structure

### Backend

The backend contains the Flask API, model prediction pipeline,
dataset and model-related code.

Repository:
https://github.com/Harkirankaur06/humantrace-backend

### Frontend

The frontend contains the Next.js application and user interface.

Repository:
https://github.com/Harkirankaur06/humantrace-frontend

### Trained Model

Fine-tuned DistilBERT model:

https://huggingface.co/harkirankaur/humantrace-distilbert

## Architecture

```text
User
  ↓
Next.js Frontend
  ↓
Flask API
  ↓
Fine-tuned DistilBERT
  ↓
Human / AI Prediction
  ↓
Result displayed in UI