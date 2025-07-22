# AI E-commerce Agent

## Overview
The AI E-commerce Agent is a Python-based application designed to answer e-commerce-related questions by converting natural language queries into SQL, executing them on a SQLite database, and returning human-readable responses. It includes bonus features like interactive Plotly charts and streamed responses with a typing effect, fulfilling all requirements of the "Build an AI Agent to Answer E-commerce Data Questions" project. The agent handles both predefined and unseen questions efficiently, with secure API key management.


### Dataset
[Dataset Link](https://drive.google.com/drive/folders/1B5jUZ4SdN277sFnrNduAQHO3x9DSjA_W?usp=sharing)

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

## Sample Output Screenshots
<img width="1033" height="615" alt="image" src="https://github.com/user-attachments/assets/6cab38e7-fc07-4584-9ac8-2ef1d960f013" />
<img width="1035" height="524" alt="image" src="https://github.com/user-attachments/assets/16288dc3-fde5-44a2-abee-fbe39bbc57f3" />
<img width="1054" height="529" alt="image" src="https://github.com/user-attachments/assets/636c2500-7001-46b4-be8b-c08b3dad397c" />
<img width="1058" height="563" alt="image" src="https://github.com/user-attachments/assets/eb9d3af5-f633-4333-ae1b-11747007d20b" />


## Setup Instructions
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/sprpranav/ai-ecommerce-agent
   cd ai-ecommerce-agent
