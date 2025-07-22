# AI E-commerce Agent

## Overview
The AI E-commerce Agent is a Python-based application designed to answer e-commerce-related questions by converting natural language queries into SQL, executing them on a SQLite database, and returning human-readable responses. It includes bonus features like interactive Plotly charts and streamed responses with a typing effect, fulfilling all requirements of the "Build an AI Agent to Answer E-commerce Data Questions" project. The agent handles both predefined and unseen questions efficiently, with secure API key management.

### Features
- **Natural Language to SQL**: Uses Google’s Gemini 1.5 Flash API to convert questions into SQL queries.
- **Database Integration**: Queries a SQLite database with tables: `ad_sales`, `total_sales`, `eligibility`.
- **Human-Readable Responses**: Formats raw SQL results into clear answers.
- **Visualization**: Generates interactive bar charts for queries like total sales and highest CPC.
- **Streaming Responses**: Delivers responses with a live typing effect via Server-Sent Events (SSE).
- **Secure Configuration**: Stores the Gemini API key in a `.env` file, excluded from version control.

### Dataset
The project uses three CSV files:
- `Product_Level_Ad_Sales.csv`: `date`, `item_id`, `ad_sales`, `impressions`, `ad_spend`, `clicks`, `units_sold`
- `Product_Level_Total_Sales.csv`: `item_id`, `total_sales`
- `Product_Level_Eligibility.csv`: `eligibility_datetime_utc`, `item_id`, `eligibility`, `message`

## Prerequisites
- Python 3.8 or higher
- Git
- A web browser (e.g., Chrome, Edge) for viewing charts and streaming responses
- Postman for testing API endpoints
- Google Gemini API key (free tier) from [Google AI Studio](https://aistudio.google.com/app/apikey)

## Setup Instructions
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/sprpranav/ai-ecommerce-agent
   cd ai-ecommerce-agent
