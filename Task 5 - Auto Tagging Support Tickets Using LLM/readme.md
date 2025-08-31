# Auto Tagging Support Tickets Using LLM

## Overview

This project demonstrates an automated system for tagging customer support tickets into predefined categories using a Large Language Model (LLM). The system leverages zero-shot and few-shot learning techniques to classify free-text support tickets without requiring extensive labeled data or fine-tuning.

## Features

- Zero-shot classification: Classify tickets into categories without any task-specific training.
- Few-shot learning: Improve classification accuracy by providing a few labeled examples in prompts.
- Top-k tag prediction: Outputs the top 3 most probable tags for each ticket.
- Interactive demo: Easily test the model with new ticket texts.
- Lightweight deployment: Uses Hugging Face Transformers and can be deployed with Streamlit or Gradio.

## Dataset

- The system is trained and evaluated on a Free-text Support Ticket Dataset.
- Synthetic and real-world datasets can be used.
- Example dataset includes categories such as billing, login issues, bug reports, feature requests, account closure, payment failures, and performance issues.

## Installation

- Clone the repository.
- Create and activate a virtual environment.
- Install dependencies from requirements.txt.

## Usage

- Run the classification script to tag tickets in batch.
- Launch the interactive demo using Streamlit or Gradio for live testing.

## Code Structure

- Scripts for classification, model utilities, demo app, and sample datasets.
- Requirements file for dependencies.

## Model Details

- Uses Hugging Face’s facebook/bart-large-mnli model for zero-shot classification.
- Supports multi-label classification.
- Can be fine-tuned on custom datasets.

## Evaluation

- Metrics include accuracy, macro F1-score, and top-3 accuracy.
- Supports evaluation on labeled test datasets.

## Contributing

- Contributions and improvements are welcome via issues and pull requests.

## License

- Licensed under the MIT License.

## References

- Hugging Face Transformers
- Zero-shot classification with BART
- Streamlit
- Gradio
