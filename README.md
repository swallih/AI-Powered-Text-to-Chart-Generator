# AI-Powered Text-to-Chart Generator

An AI-driven application that converts natural language and voice inputs into interactive data visualizations.

## Overview
This project allows users to describe data insights in plain English and automatically generates appropriate charts and dashboards. It is designed to simplify data visualization for non-technical users.

## Key Features
- Natural language and voice-based input for chart generation
- AI-powered text understanding using a fine-tuned T5 transformer model
- Automatic chart type selection and data mapping
- Fuzzy column matching using RapidFuzz
- Interactive and dynamic visualizations with Plotly
- Multi-chart dashboards with global filtering
- Streamlit-based user interface

## Tech Stack
- Python
- Streamlit
- Pandas
- PyTorch
- T5 Transformer Model
- Plotly
- RapidFuzz

## Project Workflow
1. User provides text or voice input describing the desired chart
2. The T5 model processes the input and extracts chart intent
3. Data is cleaned and matched using fuzzy logic
4. Charts are generated dynamically and displayed in an interactive dashboard

## Use Cases
- Automated data visualization
- Business reporting dashboards
- Data analysis for non-technical users

## Future Improvements
- Support for additional chart types
- Model performance optimization
- User-defined styling and export options
