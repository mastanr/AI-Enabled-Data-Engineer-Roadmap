# Full Roadmap

## Phase 0 - Setup

### Learn
- Install Python
- Install VS Code
- Install Git
- Create GitHub repo
- Learn virtual environments
- Install Jupyter Notebook

### Practice
- Create a simple Python file
- Create a notebook
- Push first commit to GitHub

---

## Phase 1 - Python for Data Engineering and AI

### Topics
- Variables and data types
- Lists, tuples, sets, dictionaries
- If conditions
- Loops
- Functions
- File handling
- Error handling
- pandas basics
- NumPy basics

### Practical Examples
- Read a CSV file
- Clean null values
- Filter records
- Group data by category
- Export clean data to CSV

### Connect to Data Engineering
- Python is used in Databricks notebooks
- pandas helps understand tabular data
- dictionaries help with JSON data
- loops help process files dynamically

---

## Phase 2 - SQL and Data Engineering Foundation

### Topics
- SELECT, WHERE, GROUP BY
- INNER JOIN / LEFT JOIN
- CTEs
- Window functions
- Stored procedures
- Incremental load
- Watermark logic
- Data quality checks
- Medallion architecture

### Practical Examples
- Build staging table
- Deduplicate records
- Create silver table
- Create gold aggregation table
- Build data quality validation query

---

## Phase 3 - Math and Statistics for AI

### Discrete Math Topics
- Boolean logic
- Truth tables
- Sets
- Relations
- Functions
- Graph basics

### Statistics Topics
- Mean, median, mode
- Variance and standard deviation
- Probability
- Distributions
- Correlation
- Hypothesis testing basics

### Practical Connection
- Boolean logic = SQL WHERE conditions
- Sets = SQL joins and matching
- Functions = transformations
- Probability = ML prediction thinking
- Variance = model and data spread

---

## Phase 4 - Machine Learning Basics

### Topics
- What is ML?
- Supervised learning
- Unsupervised learning
- Regression
- Classification
- Train/test split
- Overfitting and underfitting
- Model evaluation
- Confusion matrix
- Precision and recall
- Feature engineering

### Tools
- pandas
- NumPy
- scikit-learn
- matplotlib

### Practice Projects
- Predict house price
- Classify customer churn
- Predict delivery delay
- Detect abnormal transaction amount

---

## Phase 5 - Azure Databricks and MLflow

### Topics
- Databricks notebooks
- Spark DataFrames
- Delta Lake
- Feature engineering with Spark
- MLflow experiment tracking
- Model registry basics
- Batch inference
- Model output tables

### Data Engineer View
A Data Engineer does not always build complex ML models, but must know how to prepare, run, monitor, and operationalize ML workflows.

---

## Phase 6 - GenAI and RAG

### Topics
- LLM basics
- Prompt engineering
- Embeddings
- Vector search
- Chunking
- Retrieval-Augmented Generation
- RAG evaluation
- Guardrails
- Responsible AI

### Simple RAG Flow

```text
Documents
→ Chunk text
→ Create embeddings
→ Store in vector DB
→ User asks question
→ Retrieve relevant chunks
→ LLM generates answer
```

---

## Phase 7 - Agentic AI

### Topics
- What is an AI agent?
- Tools and actions
- Memory
- Planning
- Tool calling
- Workflow orchestration
- Observability
- Evaluation

### Simple Agent Flow

```text
User request
→ Agent understands intent
→ Agent chooses tool
→ Agent runs SQL / API / Python
→ Agent summarizes result
→ Agent logs output
```

---

## Phase 8 - Portfolio Projects

Build projects that combine data engineering and AI.

Recommended projects are documented in the `projects/` folder.

---

## Phase 9 - Interview Preparation

### Prepare Stories
- Data pipeline architecture
- Incremental load design
- Databricks performance tuning
- Data quality framework
- RAG architecture
- AI agent architecture
- Production monitoring

### Use STAR Format
- Situation
- Task
- Action
- Result

