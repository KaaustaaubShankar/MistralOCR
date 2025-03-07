# Financial Metrics Extraction and Piotroski F-Score Calculation with MistralOCR

This project automates financial data extraction from PDFs, processes it with OCR (using Mistral OCR), and calculates key financial ratios and the Piotroski F-score.

## Prerequisites
- **Libraries:** MistralAI, LangChain, OpenAI
- **API Keys:** Set your Mistral and OpenAI API keys in Google Colab.

## Data Preparation
1. **Upload PDFs**: Upload `kering2024.pdf` and `kering2023.pdf` to Colab.
2. **OCR Processing**: Uses Mistral’s OCR service to extract text from PDFs.

## Financial Metrics Extraction
1. **Prompt Engineering**: Uses LangChain to build a prompt for OpenAI to extract financial metrics (e.g., revenue, COGS).
2. **LLM Processing**: Extracts structured financial data from OCR text using GPT models.

## Piotroski F-Score Calculation
1. **Ratio Calculations**: Computes profitability, leverage, liquidity, and efficiency ratios.
2. **F-Score**: If both years' data is available, calculates the Piotroski F-score.

## Output
- Structured output with extracted financial metrics, ratios, and Piotroski F-score.

## Usage
1. Upload PDFs to Google Colab.
2. Set API keys.
3. Run the notebook to extract and analyze financial data.

**Note:** This project leverages Mistral OCR for extracting text from financial PDFs.
