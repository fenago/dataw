# Data Wrangling, Data Mining & Data Science

This will serve as the entry level book for an undergraduate data wrangling class and data mining class. This is going to be an academic textbook with plenty of hands-on activities. I prefer that this is very practical and pragmatic. It's going to be for undergraduate readers to learn how to wrangle data and do data mining. And we'll have Python as the core language.  # Practical Python for Data Analysis
## Complete Table of Contents

---

# PART 1: DATA WRANGLING

---

## Chapter 1: Foundations of Python Data Analysis

### Understanding the Data Analysis Landscape
- The critical need for high-quality and accurate data in analytics
- Defining data analysis and visualization
- The data analysis lifecycle: Acquire, Clean, Transform, Analyze, Visualize
- Career applications and industry relevance

### Tools and Languages for Data Wrangling
- Overview of data wrangling tools and languages
- Why Python is ideal for data wrangling
- The Python data science ecosystem
- Overview of Pandas for structured data
- Overview of Seaborn for statistical visualization
- Setting up your analysis environment

### Core Python Constructs for Analysts
- Importing modules and libraries
- Method calling and chaining techniques
- Working with slices for data extraction

### Debugging and Error Resolution
- Identifying and fixing syntax errors
- Troubleshooting runtime errors
- Best practices for error prevention

### Chapter 1 Review
- Discussion Questions
- Multiple Choice Questions
- True/False Questions
- Fill in the Blank Questions
- Case Study: Analyzing a Business Problem
- Guided Programming Exercises
- Independent Programming Challenges

---

## Chapter 2: Python Data Structures and File Management

### Built-in Data Collection Types
- Lists: Creation, manipulation, and operations
- Tuples: Immutable sequences for data integrity
- Sets: Unique collections and set operations
- Dictionaries: Key-value data structures
- Choosing the right data structure for your task

### Advanced Data Structures
- Understanding stacks: LIFO operations
- Understanding queues: FIFO operations
- When to use stacks vs. queues

### List Comprehensions and Efficient Processing
- List comprehensions for efficient data processing
- Nested comprehensions
- Conditional comprehensions

### File Input and Output Operations
- Opening files in different modes
- Reading file contents
- Writing data to files
- Closing files and resource management
- Context managers for safe file handling

### Chapter 2 Review
- Discussion Questions
- Multiple Choice Questions
- True/False Questions
- Fill in the Blank Questions
- Case Study: Processing Log Files
- Guided Programming Exercises
- Independent Programming Challenges

---

## Chapter 3: Essential Python Packages for Analytics

### NumPy for Numerical Computing
- Creating arrays with NumPy
- Array attributes and properties
- Mathematical operations on arrays
- Array indexing and slicing
- Broadcasting and vectorized operations

### Introduction to Pandas
- Creating Series objects
- Creating DataFrames
- Series vs. DataFrame: When to use each

### DataFrame Fundamentals
- Core attributes: values, index, columns, shape
- Performing basic column operations
- Performing basic row operations
- Displaying and exploring data

### Statistical Analysis with Pandas
- Applying statistical measures: min, max, median
- Descriptive statistics with describe()
- Aggregation functions

### Introduction to Matplotlib
- Creating basic charts
- Line plots and scatter plots
- Bar charts and histograms
- Customizing plot appearance

### Chapter 3 Review
- Discussion Questions
- Multiple Choice Questions
- True/False Questions
- Fill in the Blank Questions
- Case Study: Sales Data Analysis
- Guided Programming Exercises
- Independent Programming Challenges

---

## Chapter 4: Mastering DataFrames with Pandas

### Creating and Persisting DataFrames
- Building DataFrames from files
- Constructing DataFrames programmatically
- Saving DataFrames with pickle serialization
- Loading persisted DataFrames

### Exploring and Profiling Data
- Profiling with info(), nunique(), and describe()
- Understanding data types and memory usage
- Extracting subsets for specific business questions

### Selecting and Filtering Data
- Column access with dot notation
- Bracket notation for flexible selection
- Conditional filtering with query()
- Position-based selection with iloc[]
- Label-based selection with loc[]
- Combining techniques for complex selections

### Sorting, Filtering, Indexing, and Grouping
- Sorting rows by single and multiple columns
- Advanced filtering techniques
- Index management: Setting and resetting
- Grouping data for analysis

### Computing and Transforming Values
- Statistical methods for numeric analysis
- Arithmetic operations on columns
- Value replacement strategies
- Data transformation patterns

### Chapter 4 Review
- Discussion Questions
- Multiple Choice Questions
- True/False Questions
- Fill in the Blank Questions
- Case Study: Customer Data Exploration
- Guided Programming Exercises
- Independent Programming Challenges

---

## Chapter 5: Data Acquisition Strategies

### File-Based Data Import
- Reading CSV files with Pandas
- Importing Excel workbooks
- Pre-downloading files for local processing

### Working with Compressed Archives
- Extracting zip file contents
- Accessing nested archive structures

### Database Connectivity
- Establishing database connections
- Writing SQL queries for data extraction
- Loading query results into DataFrames

### Statistical Software Formats
- Understanding Stata file metadata
- Selective column importing
- Working with survey and research data

### Hierarchical Data Formats
- Navigating JSON structure
- Drilling into nested JSON levels
- Converting JSON to dictionaries
- Constructing DataFrames from complex JSON

### Chapter 5 Review
- Discussion Questions
- Multiple Choice Questions
- True/False Questions
- Fill in the Blank Questions
- Case Study: Multi-Source Data Integration
- Guided Programming Exercises
- Independent Programming Challenges

---

## Chapter 6: Data Quality and Cleaning

### Diagnosing Data Issues
- Profiling with info() for structural problems
- Discovering unique values and distributions
- Using value_counts() for frequency analysis
- Identifying data types in each column

### Handling Missing Data
- Detecting missing values
- Strategies: Deletion, imputation, flagging
- Implementing missing value solutions

### Managing Duplicate Records
- Finding duplicate values
- Strategies for handling duplicates
- Eliminating duplicate records

### Detecting and Treating Outliers
- Outlier detection techniques
- Assessment strategies: Keep, transform, or remove
- Implementing outlier treatments

### Streamlining Datasets
- Removing irrelevant rows
- Dropping unnecessary columns
- Standardizing column naming conventions

### Data Type Conversion
- Fixing datetime parsing issues
- Correcting numeric type mismatches
- Converting data types when necessary
- Validating and replacing invalid entries

### Applying Functions to Data
- Applying functions to entire rows
- Applying functions to entire columns
- Lambda functions for quick transformations

### Chapter 6 Review
- Discussion Questions
- Multiple Choice Questions
- True/False Questions
- Fill in the Blank Questions
- Case Study: Cleaning a Messy Dataset
- Guided Programming Exercises
- Independent Programming Challenges

---

## Chapter 7: Data Transformation and Combining Datasets

### Deriving New Columns
- Creating datetime-based features
- Generating string-derived columns
- Computing numeric transformations
- Building summary and aggregate columns

### Advanced Function Application
- Using built-in functions
- Creating custom transformation functions
- Lambda expressions for inline operations

### Index-Based Restructuring
- Setting meaningful indexes
- Unstacking data with hierarchical indexes
- Resetting indexes for flat structures

### Combining Multiple DataFrames
- Concatenating datasets vertically
- Joining datasets horizontally with join()
- Flexible merging with merge()
- Understanding join types: Inner, outer, left, right

### Pivot Tables and Data Manipulation
- Creating pivot tables with Pandas
- Reshaping data for analysis
- Additional transformation tasks

### Avoiding Common Pitfalls
- Understanding SettingWithCopyWarning
- Proper assignment patterns
- Using .copy() effectively

### Chapter 7 Review
- Discussion Questions
- Multiple Choice Questions
- True/False Questions
- Fill in the Blank Questions
- Case Study: Feature Engineering Pipeline
- Guided Programming Exercises
- Independent Programming Challenges

---

## Chapter 8: Visual Storytelling and Analytical Visualization

### Principles of Data Visualization
- Choosing the right visualization
- Understanding wide vs. long data formats
- How data structure affects plot output

### Creating Core Plot Types with Pandas
- Line plots for trends over time
- Area plots for cumulative visualization
- Scatter plots for relationship analysis
- Bar plots for categorical comparison
- Histograms for distribution analysis
- Box plots for statistical summaries

### Statistical Visualization with Seaborn
- Relational plots: Line and scatter
- Categorical plots: Bar and box
- Distribution plots: Histogram, KDE, ECDF

### Customizing Plot Appearance
- Adding titles and axis labels
- Configuring grid lines and ticks
- Setting axis boundaries and limits
- Color palette selection

### Multi-Panel Visualizations
- Creating subplot layouts
- Working with FacetGrid
- Adding super titles and coordinating aesthetics

### Exporting and Sharing Visualizations
- Saving plots to various formats
- Resolution and sizing options

### Chapter 8 Review
- Discussion Questions
- Multiple Choice Questions
- True/False Questions
- Fill in the Blank Questions
- Case Study: Executive Dashboard Creation
- Guided Programming Exercises
- Independent Programming Challenges

---

# PART 2: DATA MINING

---

## Chapter 9: Introduction to Data Mining and Predictive Analytics

### Foundations of Data Mining
- What is data mining?
- Extracting insights from organizational data warehouses
- Uncovering hidden patterns and relationships
- Supervised vs. unsupervised techniques

### The Data Mining Process
- Preparing the analysis services database
- Understanding data sources and data views
- Creating intermediate data mining solutions
- The CRISP-DM methodology

### Building Your First Mining Structure
- Targeted mailing as a use case
- Building a targeted mailing structure
- Adding and processing models
- Exploring targeted mailing models

### Model Testing and Validation
- Testing model accuracy
- Cross-validation techniques
- Interpreting model results

### Creating and Working with Predictions
- Generating predictions from models
- Evaluating prediction quality
- Deploying predictions for business use

### Chapter 9 Review
- Discussion Questions
- Multiple Choice Questions
- True/False Questions
- Fill in the Blank Questions
- Case Study: Direct Marketing Campaign
- Guided Programming Exercises
- Independent Programming Challenges

---

## Chapter 10: Customer Analytics - RFM and Lifetime Value

### Understanding Customer Value
- Why customer analytics matters
- Segmentation strategies
- From transactions to insights

### Recency, Frequency, Monetary (RFM) Analysis
- The RFM framework explained
- Calculating Recency scores
- Calculating Frequency scores
- Calculating Monetary scores
- Combining RFM into customer segments
- Interpreting RFM segments for action

### Customer Lifetime Value (CLV)
- What is customer lifetime value?
- Historical CLV calculation
- Predictive CLV models
- Components: Acquisition cost, retention rate, margin

### Building CLV Models
- Simple CLV formulas
- Cohort-based CLV analysis
- Probabilistic models (BG/NBD overview)
- Applying CLV to business decisions

### Customer Segmentation Strategies
- Combining RFM with CLV
- Creating actionable customer tiers
- Targeting strategies by segment

### Chapter 10 Review
- Discussion Questions
- Multiple Choice Questions
- True/False Questions
- Fill in the Blank Questions
- Case Study: E-Commerce Customer Segmentation
- Guided Programming Exercises
- Independent Programming Challenges

---

## Chapter 11: Monte Carlo Simulation and Risk Analysis

### Introduction to Simulation
- What is Monte Carlo simulation?
- When to use simulation vs. analytical methods
- Random number generation in Python

### Building Monte Carlo Models
- Defining input distributions
- Running simulations with iterations
- Collecting and storing results
- Convergence and sample size considerations

### Probability Distributions for Business
- Normal distribution applications
- Uniform distributions
- Triangular distributions for estimates
- Custom distributions from historical data

### Risk Analysis Applications
- Project cost estimation
- Sales forecasting under uncertainty
- Investment portfolio analysis
- Break-even analysis with uncertainty

### Interpreting Simulation Results
- Analyzing output distributions
- Confidence intervals and percentiles
- Sensitivity analysis
- Tornado diagrams and variable importance

### Chapter 11 Review
- Discussion Questions
- Multiple Choice Questions
- True/False Questions
- Fill in the Blank Questions
- Case Study: New Product Launch Risk Assessment
- Guided Programming Exercises
- Independent Programming Challenges

---

## Chapter 12: Time Series Forecasting

### Foundations of Time Series Analysis
- What is time series data?
- Components: Trend, seasonality, cycles, noise
- Stationarity and why it matters

### Preparing Time Series Data
- Adding data source views for forecasting
- Specifying requirements for time series models
- Handling missing timestamps
- Resampling and frequency conversion

### Building Forecasting Models
- Creating forecasting structures
- Modifying and customizing forecasting models
- Processing and training the model
- Exploring forecasting model outputs

### Time Series Prediction Techniques
- Moving averages and smoothing
- Exponential smoothing methods
- Creating time series predictions
- Advanced time series predictions

### Working with Forecast Data
- Updating data in time series predictions
- Replacing data in time series predictions
- Comparing predictions across models
- Choosing the proper forecasting model

### Evaluating Forecast Accuracy
- Mean Absolute Error (MAE)
- Root Mean Square Error (RMSE)
- Mean Absolute Percentage Error (MAPE)
- Forecast confidence intervals

### Chapter 12 Review
- Discussion Questions
- Multiple Choice Questions
- True/False Questions
- Fill in the Blank Questions
- Case Study: Retail Demand Forecasting
- Guided Programming Exercises
- Independent Programming Challenges

---

## Chapter 13: Market Basket Analysis and Association Rules

### Understanding Association Analysis
- What is market basket analysis?
- Real-world applications
- Support, confidence, and lift explained

### Preparing Data for Market Basket Analysis
- Adding data source views with nested tables
- Transaction data formats
- Handling product hierarchies

### Building Association Models
- Creating market basket structures
- Modifying market basket models
- Processing the market basket model
- Filtering nested tables in mining models

### Exploring Market Basket Results
- Exploring the market basket models
- Interpreting association rules
- Identifying strong vs. weak rules
- Visualizing item relationships

### Predicting Associations
- Generating product recommendations
- Cross-selling and up-selling strategies
- Implementing recommendations in business

### Advanced Association Techniques
- Multi-level association rules
- Sequential patterns in purchases
- Time-aware association analysis

### Chapter 13 Review
- Discussion Questions
- Multiple Choice Questions
- True/False Questions
- Fill in the Blank Questions
- Case Study: Grocery Store Product Placement
- Guided Programming Exercises
- Independent Programming Challenges

---

## Chapter 14: Sequence Clustering and Pattern Mining

### Introduction to Sequence Analysis
- What is sequence clustering?
- Applications in customer journey analysis
- Sequence vs. traditional clustering

### Building Sequence Clustering Models
- Creating sequence clustering mining model structures
- Preparing sequential data
- Processing the sequence clustering model

### Exploring Sequence Patterns
- Exploring the sequence clustering model
- Identifying common sequences
- Understanding cluster characteristics
- Visualizing sequence flows

### Advanced Sequence Modeling
- Creating related sequence clustering models
- Comparing sequence models
- Handling variable-length sequences

### Generating Sequence Predictions
- Predicting next steps in a sequence
- Probability of sequence completion
- Applying predictions to customer journeys

### Chapter 14 Review
- Discussion Questions
- Multiple Choice Questions
- True/False Questions
- Fill in the Blank Questions
- Case Study: Website Clickstream Analysis
- Guided Programming Exercises
- Independent Programming Challenges

---

## Chapter 15: Introduction to Machine Learning with Logistic Regression

### Machine Learning Fundamentals
- What is machine learning?
- Supervised vs. unsupervised learning
- Classification vs. regression problems
- The machine learning workflow

### Logistic Regression Concepts
- From linear to logistic regression
- The sigmoid function
- Probability and classification
- Binary vs. multiclass classification

### Building Logistic Regression Models
- Adding data source views for modeling
- Feature selection and preparation
- Creating the logistic regression model
- Training and fitting the model

### Practical Application: Call Center Analysis
- Adding a data source view for call center data
- Building a call center prediction model
- Adding logistic regression to existing structures
- Interpreting coefficients and odds ratios

### Model Evaluation and Predictions
- Confusion matrix analysis
- Accuracy, precision, recall, F1-score
- ROC curves and AUC
- Creating predictions for business decisions

### Chapter 15 Review
- Discussion Questions
- Multiple Choice Questions
- True/False Questions
- Fill in the Blank Questions
- Case Study: Customer Churn Prediction
- Guided Programming Exercises
- Independent Programming Challenges

---

## Chapter 16: Neural Networks and Advanced Predictive Models

### Introduction to Neural Networks
- What are neural networks?
- Biological inspiration and artificial neurons
- Network architecture: Layers and connections
- When to use neural networks

### Building Neural Network Models
- Creating neural network structures
- Configuring hidden layers and neurons
- Activation functions explained
- Training neural networks

### Practical Application: Call Center Neural Networks
- Adding a data source view for call center data
- Creating a neural network structure and model
- Exploring the call center neural network model
- Comparing neural networks to logistic regression

### Creating Predictions with Neural Networks
- Generating predictions from neural models
- Interpreting neural network outputs
- Confidence scores and probability estimates

### Querying Mining Models
- Introduction to DMX (Data Mining Extensions)
- Using MDX for mining model queries
- Using DAX for mining model queries
- Creating and querying models programmatically

### Choosing the Right Model
- Comparing model performance
- Trade-offs: Interpretability vs. accuracy
- Model selection guidelines
- Ensemble approaches overview

### Chapter 16 Review
- Discussion Questions
- Multiple Choice Questions
- True/False Questions
- Fill in the Blank Questions
- Case Study: Multi-Model Comparison for Fraud Detection
- Guided Programming Exercises
- Independent Programming Challenges

---

# Integrating AI-Assisted Analysis and Vibe Coding

### The Future of Data Analysis
- How AI is transforming analytical workflows
- The role of natural language in coding
- When to leverage AI assistance

### Vibe Coding for Data Wrangling
- Using conversational prompts to clean data
- AI-assisted data transformation
- Generating data quality reports with prompts

### Vibe Coding for Data Mining
- Building predictive models through natural language
- Iterating on model parameters conversationally
- AI-assisted feature engineering
- Generating model evaluation reports

### Best Practices for AI-Augmented Analysis
- Writing effective prompts for data tasks
- Validating AI-generated code
- Combining human intuition with AI efficiency
- Ethical considerations in AI-assisted analysis

### Hands-On Vibe Coding Exercises
- Guided AI-Assisted Projects
- Independent AI-Augmented Challenges

---

**Author:** Professor Carlos Marquez and Dr. Ernesto Lee

## Chapters

1. Foundations of Python Data Analysis
2. Python Data Structures and File Management

## Building Locally

```bash
# Install MyST
npm install -g mystmd

# Start development server
myst start

# Build for production
myst build --html
```

---

Built with [LiquidBooks](https://liquidbooks.tech) - Create beautiful, interactive eBooks with AI.
