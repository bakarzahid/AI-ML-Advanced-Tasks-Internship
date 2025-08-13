# News Topic Classifier Using BERT

## Objective
Fine-tune a transformer model (e.g., BERT) to classify news headlines into topic categories.

## Dataset
AG News Dataset (Available on Hugging Face Datasets)

## Instructions
- Tokenize and preprocess the dataset
- Fine-tune the `bert-base-uncased` model using Hugging Face Transformers
- Evaluate the model using accuracy and F1-score
- Deploy the model using Streamlit or Gradio for live interaction

## Skills Gained
- NLP using Transformers
- Transfer learning & fine-tuning
- Evaluation metrics for text classification
- Lightweight model deployment

## Project Structure
- `train.py` - Script to fine-tune and evaluate the model
- `app.py` - Streamlit or Gradio app for live interaction
- `requirements.txt` - Project dependencies
- `README.md` - Project documentation

## Usage
1. Clone the repository
2. Install dependencies
3. Run the training script to fine-tune the model
4. Launch the web app for live testing
