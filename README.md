# Excel Feedback Analyzer

This repository contains a Streamlit application that analyzes customer feedback stored in Excel or CSV files. It uses IBM’s AI language model to label feedback entries with sentiment, generate summaries, and provide sentiment counts.

## Features

- Upload Excel (`.xlsx`) or CSV files containing customer feedback  
- Preview the uploaded dataset in the app  
- Automatically extract and process feedback text  
- AI-powered sentiment labeling (Positive/Negative) for the first 50 rows [this number can be configured based on tokens available to compute]
- Generates a concise summary of overall feedback themes  
- Displays total counts of Positive and Negative sentiments  

## Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/excel-feedback-analyzer.git
cd excel-feedback-analyzer
pip install -r requirements.txt
