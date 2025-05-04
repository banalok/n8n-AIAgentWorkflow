# n8n-AIAgentWorkflow
An automated workflow that scrapes laptop prices from Amazon and Target, processes the data, and provides intelligent analysis via natural language conversation.

## Project Structure

'''
n8n-AIAgentWorkflow/
├── README.md
├── workflows/
│   └── n8n-workflow.json
├── video-demo/
│   ├── workflow-diagram.png
├── sample-data/
│   ├── sample-data-link.txt
└── license
'''

## Features

- **Automated Web Scraping**: Uses Apify actors to collect real-time laptop data
- **Data Processing Pipeline**: Standardizes and structures data from multiple sources
- **AI-Powered Analysis**: Uses LLM (OpenAI API) to answer questions and generate insights
- **Multi-Source Comparison**: Compares prices across Amazon and Target
- **Conversational Interface**: Chat-based interaction for data queries

## 🛠️ Technology Stack

- **n8n**: Workflow automation platform
- **Apify**: Web scraping infrastructure
- **OpenAI**: Natural language processing for data analysis
- **Google Sheets API**: Data storage and retrieval
- **JavaScript**: Custom data processing logic

## Demo
![Quick Demo](video-demo/video-demo.gif)
