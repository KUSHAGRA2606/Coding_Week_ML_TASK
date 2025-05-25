# Coding_Week_ML_TASK
This repository describes the task of coding week in machine learning module made by-kushagra singhal,Roll number-240102056

For "The Campus Pulse Initiative" (Task 1)
Project Overview
This notebook analyses anonymized student survey data from IIT Guwahati to identify factors influencing romantic relationships and student wellness. The project progresses through five levels of analysis: variable identification, data cleaning, exploratory insights, predictive modelling, and model interpretation.
Notebook Structure
•	Level 1: Variable Identification
•	EDA with histograms, correlation heatmaps, and box plots
•	Feature hypothesis testing for Feature_1/2/3
•	Finding what actually Feature 1,2,3 represent.
•	Level 2: Data Integrity Audit
•	Filling the missing Data with appropriate measure like mean, median case to case.
•	Imputation strategies per feature type
•	Level 3: Exploratory Insights
•	Asked 7 investigative questions with visualizations
•	Analysed each investigative questions carefully and shown their relationship using various types of plots like heat map, bar plot, histogram etc varying from case to case.
•	Comparative analysis of academic vs social behaviours
•	Level 4: Predictive Modelling
•	Experimented between the Two main models -Logistic regression and Random Forest classifier Moder to identify how involved in Romantic Relationship column be best related, compared both the models. So, for particular Case logistic regression yielded better result as compared to Random Forest, so used it as compared to Random Forest.
•	Performance metrics (Accuracy, F1, Recall value)
•	Level 5: Model Interpretation
•	SHAP waterfall/bee swarm plots
•	Decision boundary visualizations
•	Bonus Level
•	Classifier identification from decision boundaries
Software Versions
•	Python 3.11.6
•	Pandas 2.1.3, Matplotlib 3.8.0
•	Scikit-learn 1.3.2, SHAP 0.44.0
Requirements
text
pandas
numpy
matplotlib
seaborn
scikit-learn
Shap

 For "The Rise of the Weather Mind" (Task 2, Project Sky Link)
________________________________________
Project Overview
This notebook implements "WeatherMind," a modular, agentic AI system built with LangGraph, integrating a Large Language Model (LLM) and multiple tool-augmented reasoning agents. The Project evolves through four levels, from a basic chatbot to a collaborative, multi-agent architecture.
Structure and Flow (Heading-wise)
•	Introduction & Setup
•	Installation of dependencies: langgraph, langchain, langchain-google-genai, google-generative Ai (GEMINI-1.5-Flash as LLM model)
•	Environment variable configuration for API keys
•	Level 1: Core Activation
•	Construction of a LangGraph node called chatbot, powered by Gemini (or any open-source LLM)
•	Integration of a calculator tool supporting BODMAS
•	Visualization of the LangGraph as an image (AI's "neural skeleton")
•	Level 2: Senses of the World
•	Addition of two tools:
•	Weather Extractor Tool: Fetches real-time weather via API, parsing location from queries
•	Fashion Recommender Tool: Uses LLM to surface trending fashion for a given city/country
•	Demonstrations of both tools
•	Level 3: Judgement and Memory
•	Introduction of intent-based routing logic: classifies user queries and dispatches to the correct tool (calculator, weather, fashion, or general LLM)
•	Implementation of conversational memory: stores and utilizes prior dialogue context for more coherent, context-aware responses
•	Level 4: The Architect’s Trial – Multi-Agent Evolution
•	Definition of multiple agents (Researcher, Analyst, Decision-Maker, General Worker), each with a distinct role and toolset
•	Expansion of toolset (e.g., news tool, calendar tool)
•	Custom routing logic between agents, ensuring smooth collaboration and graceful failure handling
•	Visualization of the multi-agent LangGraph
•	Testing & Demonstrations
•	Tested and thought of various models and tools which can I use like calendar tool, news tool .
•	Tested how to implement calculator function.
•	Example queries to showcase tool selection, agent routing, and memory
•	Output inspection for each level
•	Conclusion
Software Versions
•	Python: 3.12.7
•	NumPy: 1.26.4 
•	Lang graph, langchain, langchain-google-genai: latest as of May 2025
Requirements
text
Lang graph
langchain
langchain-google-genai
google-generative Ai (GEMINI -1.5-Flash)

THANK YOU
