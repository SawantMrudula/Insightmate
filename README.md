# Insightmate
DataViz – AI-Powered Visualization and Analysis Tool An intelligent web-based data analysis platform that processes structured and unstructured files (CSV, PDF, DOCX, PPTX) to generate automated visualizations, AI-driven insights, correlation analysis, and interactive dashboards using Streamlit, Python, LangChain, and Gemini AI.

DataViz – AI-Powered Data Visualization & Analysis Platform
📌 Overview

DataViz is an intelligent web-based analytics platform designed to simplify data exploration and visualization for both structured and unstructured datasets. The application supports multiple file formats including CSV, PDF, DOCX, and PPTX, automatically extracts tabular data, generates interactive visualizations, and provides AI-powered insights using Large Language Models (LLMs).

Built with Streamlit, Python, LangChain, and Google Gemini AI, the platform enables users to upload datasets, perform exploratory data analysis, visualize trends, generate correlation insights, and interact with data through natural language queries.

🚀 Features
📂 Multi-Format File Support

The system can process and analyze:

CSV files
PDF documents containing tables
DOCX files with tabular content
PPTX presentations containing tables
📊 Automated Data Visualization

Automatically generates visualizations for uploaded datasets, including:

Histograms
Bar Charts
Scatter Plots
Line Charts
Pie Charts
Box Plots
Violin Plots
Correlation Heatmaps
Pair Plots
🤖 AI-Powered Insights

Integrated with Google Gemini AI via LangChain to provide:

Natural language explanations of graphs
Correlation analysis summaries
Dataset question answering
Automated trend interpretation
Context-aware responses
🧠 Intelligent Data Querying

Users can ask questions about uploaded datasets in natural language such as:

“What is the average sales value?”
“Which category has the highest frequency?”
“What trends are visible in the dataset?”

The AI model analyzes the dataset preview and generates human-readable responses.

🧹 Automated Data Cleaning

The platform automatically detects and handles:

Missing values
Null entries
Inconsistent categorical values

Techniques used:

Mean imputation for numerical data
Mode imputation for categorical data
📈 Interactive Dashboard

Provides a dynamic dashboard with:

Dataset preview
Statistical summaries
Distribution analysis
Downloadable visualizations
AI-generated descriptions
💾 Downloadable Outputs

Users can download generated plots and visualizations directly as PNG files.

🛠️ Tech Stack
Frontend
Streamlit
Backend
Python
Data Processing Libraries
Pandas
NumPy
Visualization Libraries
Matplotlib
Seaborn
AI & NLP
LangChain
Google Gemini AI
Hugging Face Transformers
File Processing
pdfplumber
python-docx
python-pptx
PyPDF2
Utilities
dotenv
tenacity
⚙️ System Workflow
User uploads dataset/document.
System identifies file format.
Data extraction module processes content.
Dataset preview and statistical summary are generated.
Visualizations are created automatically.
AI generates explanations and insights.
User interacts with dataset through natural language queries.
Results and plots can be downloaded.
🧪 Supported Visualizations
Visualization Type	Purpose
Histogram	Distribution analysis
Bar Plot	Category frequency analysis
Scatter Plot	Relationship analysis
Line Plot	Trend visualization
Pie Chart	Proportion analysis
Box Plot	Outlier detection
Violin Plot	Distribution comparison
Heatmap	Correlation analysis
Pair Plot	Multi-variable analysis
📁 Project Structure
DataViz/
│
├── app.py
├── requirements.txt
├── .env
├── README.md
│
├── data/
│   ├── sample.csv
│   ├── sample.pdf
│   ├── sample.docx
│   └── sample.pptx
│
├── assets/
│   └── screenshots/
│
└── outputs/
    └── generated_plots/
🔐 Environment Variables

Create a .env file and add:

GOOGLE_API_KEY=your_google_api_key
LANGCHAIN_API_KEY=your_langchain_api_key
▶️ Installation & Setup
1️⃣ Clone Repository
git clone https://github.com/yourusername/DataViz.git
cd DataViz
2️⃣ Install Dependencies
pip install -r requirements.txt
3️⃣ Run Application
streamlit run app.py
💡 Use Cases
Business Intelligence
Academic Research
Data Exploration
Report Analysis
Automated Dashboarding
AI-assisted Analytics
Cybersecurity Log Analysis
Document-based Data Extraction
📚 Future Enhancements
Real-time collaborative dashboards
Cloud deployment
Database connectivity
Advanced predictive analytics
OCR support for scanned PDFs
Voice-based querying
Multi-language support
Export to PDF reports
👩‍💻 Author

Mrudula Sushil Sawant
B.Tech Computer Engineering (Honours in Cyber Security & Forensics)

📄 License

This project is developed for academic, research, and educational purposes.
