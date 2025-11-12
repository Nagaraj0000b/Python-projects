# Python Projects Collection

A comprehensive collection of Python projects covering machine learning, AI chatbots, agents, and data analysis. This repository demonstrates various concepts in artificial intelligence, machine learning, and data science using Python.

## 📚 Projects Overview

### 1. **Linear Regression** (`LinearRegrssion/`)
A fundamental machine learning project demonstrating linear regression for salary prediction.

- **Goal:** Predict salary based on years of experience
- **Techniques:** Simple linear regression, data visualization, model evaluation
- **Key Files:**
  - `LinearRegresion.py`: Main implementation
  - `data.csv`: Training dataset
- **Libraries:** scikit-learn, pandas, numpy, matplotlib

### 2. **Diabetes Onset Predictor** (`Diabetes Onset Predictor/`)
A machine learning model to predict diabetes onset using patient health metrics.

- **Goal:** Predict diabetes occurrence based on health indicators
- **Features:** Pregnancies, Glucose, Blood Pressure, BMI, Age, etc.
- **Key Files:**
  - `Predictor.py`: Prediction model implementation
  - `diabetes.csv`: Patient health dataset
- **Libraries:** scikit-learn, pandas, numpy, matplotlib

### 3. **AI Chatbot** (`AiChatbot/`)
Multiple chatbot implementations ranging from rule-based to advanced AI-powered versions.

- **simpleModel1.py**: Basic rule-based chatbot with pattern matching
- **Version2.py**: Enhanced chatbot version
- **NewsScrapingAgent.py**: AI agent for news scraping and analysis
- **Libraries:** LangChain, Google Generative AI, web scraping tools

### 4. **AI Agents** (`Agents/`)
Advanced AI agent implementations using LangGraph and Google's Gemini AI.

- **Agent1.py**: Basic conversational AI agent using LangGraph
- **Agent2.py**: Enhanced agent with extended capabilities
- **Agent3.py**: Advanced agent implementation
- **DrafterAgent.py**: Specialized agent for drafting tasks
- **Libraries:** LangChain, LangGraph, Google Generative AI

### 5. **LanGraph** (`LanGraph/`)
Jupyter notebooks exploring graph-based machine learning and AI workflows.

- **Notebooks:** Multiple assignments and examples (Assignment1, Assignment2, Graph3-5, HelloWorldGraph, MultipleGraphInputs)
- **Focus:** Graph-based AI architectures and state management
- **Libraries:** LangGraph, LangChain

## 🚀 Getting Started

### Prerequisites
- Python 3.7 or higher
- pip (Python package manager)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Nagaraj0000b/Python-projects.git
cd Python-projects
```

2. Install required dependencies:
```bash
pip install pandas numpy matplotlib scikit-learn langchain langgraph langchain-google-genai python-dotenv
```

3. For AI agent projects, create a `.env` file in the `Agents/` directory with your API keys:
```
GOOGLE_API_KEY=your_api_key_here
```

## 📖 Usage

### Running Linear Regression:
```bash
cd LinearRegrssion
python LinearRegresion.py
```

### Running Diabetes Predictor:
```bash
cd "Diabetes Onset Predictor"
python Predictor.py
```

### Running AI Chatbot:
```bash
cd AiChatbot
python simpleModel1.py
```

### Running AI Agents:
```bash
cd Agents
python Agent1.py
```

### Exploring LanGraph Notebooks:
```bash
cd LanGraph
jupyter notebook
```

## 🛠️ Technologies Used

- **Python 3.x**: Core programming language
- **scikit-learn**: Machine learning models and evaluation
- **pandas**: Data manipulation and analysis
- **numpy**: Numerical computations
- **matplotlib**: Data visualization
- **LangChain & LangGraph**: AI agent frameworks
- **Google Generative AI (Gemini)**: Advanced language models
- **Jupyter Notebook**: Interactive development environment

## 📊 Key Concepts Covered

- **Machine Learning:**
  - Linear Regression
  - Model training and evaluation
  - Feature engineering
  - Prediction accuracy metrics

- **Artificial Intelligence:**
  - Conversational AI agents
  - Rule-based chatbots
  - LLM-powered agents
  - State management in AI systems

- **Data Science:**
  - Data preprocessing
  - Exploratory data analysis
  - Visualization techniques
  - Statistical analysis

## 🎯 Project Structure

```
Python-projects/
├── LinearRegrssion/          # Salary prediction using linear regression
├── Diabetes Onset Predictor/ # Healthcare ML prediction
├── AiChatbot/                # Various chatbot implementations
├── Agents/                   # Advanced AI agents
├── LanGraph/                 # Graph-based AI notebooks
└── Readme.md                 # This file
```

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

## 📝 License

This project is open source and available for educational purposes.

## 👤 Author

**Nagaraj0000b**
- GitHub: [@Nagaraj0000b](https://github.com/Nagaraj0000b)

---

*This repository is a collection of learning projects demonstrating various Python programming, machine learning, and AI concepts. Each project is self-contained and can be run independently.*
