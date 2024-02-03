- A methodology:
	- A system of methods
	- A guidline for decision-making during the scientific process
	- Data science methodology guides data scienctists in solving complex problems with data

<img width="644" alt="Screenshot 2024-02-01 at 4 19 13 PM" src="https://github.com/DuongNg2911/IBM-Data-Science/assets/127082369/7c713688-2c0a-45d8-a516-d996aa45d0f7">

- DS methodology consists of 10 stages and here are the questions to ask at each stage:
	- Business understanding -> analytic approach (define the issue and solution):
 		- What is the problem that you are trying to solve?
	 	- How can you use data to answer the business question?
  - Data requirements -> Data collection -> Data understanding -> Data preparation (get organized around the data)
		- What data do you need to answer the question?
    - Where is the data sourced from, and how will you receive the data?
    - Does the data you collected represent the problem to be solved?
    - What additional work is required to manipulate and work with the data
  - Modeling -> Evaluation -> Deployment -> Feedback (Validate your approach and the final design of the data)
  	- When you apply data visualizations, do you see answers that address the business problem?
   	- Does the data model answer the initial business question or must you adjust the data?
    - Can you put the model into practice?
    - Can you get constructive feedback from the data and the stakeholder to answer the business question?

- First step: Business understanding ( Identifies the data sources and variables required to address the business problem )
  - Understand the goal
  - Identifying the objectives that support the goal

- Second step: Analytic approach
	- Pick analytic appraoach based on the question type
   	- If the question is to determine the probabilities of an action: use a predictive model
   	- If the question is to show relationships: use a descriptive model
   	- If the question requires a yes/no answer: use a classification model
  
- Third step: Data Requirements
	- The chosen analytic approach determines the data requirements. Specifically, the analytic methods to be used require certain data content, formats and representations, guided by domain knowledge.
	- Identify the necessary data content, formats, and sources for initial data collection
 
- Fourth step: Data collection
	- When collecting data it is alright to defer (delay) decisions about unavailable data and attempt to accquire it at a later stage
	- Using Data visualization and decriptive statistics to get initial insights about the data.
 	- This step involves collaborating with DBAs and programmer to extract and merge data from various sources

- Fifth stage: Data understanding
	- Descriptive statistics:
 		- Univariate statistics on each variable, such as mean, median, minimum, maximum, and standard deviation
   		- Pairwise correlations were used, to see how closely certain variables were related, and which ones, if any, were very highly correlated, meaning that they would be essentially redundant, thus making only one relevant for modeling. 
		-  Histograms are a good way to understand how values or a variable are distributed, and which sorts of data preparation may be needed to make the variable more useful in a model.
	- The data understanding phase aims to determine if the collected data represents the problem to be solved.

- Sixth stage: Data preparation (Taking about 70-90% of the project)
	- Cleansing data
   		- Remove invalid, missing or duplicate
  		- Formatting 
   	- Transformation data
   	- Using domain knowledge (feature engineering):
   	  	- Feature engineering is the process of using domain knowledge of the data to create feature that makes the machine learning algorithms work.
   	-  Automation can reduce data preparation time by up to 50 percent. Automation allows data scientists to spend more time focusing on model creation.

- Seventh stage: Modeling
	- Focuses on developing models that are either descriptive or predictive.
	- An example of a descriptive model might examine things like: if a person did this, then they're likely to prefer that. A predictive model tries to yield yes/no, or stop/go type outcomes. These models are based on the analytic approach that was taken, either statistically driven or machine learning driven.
	- Descriptive models use data aggregation and data mining to uncover patterns in past or current events. A familiar example of descriptive modeling is business reporting in the form of graphs, charts, and dashboards. While descriptive models can be very complex, they are usually close to 100% accurate.
	- Predictive models analyze historical data and use AI algorithms to uncover trends, make smart extrapolations, and identify likely outcomes.

- Eighth stage: Evaluation
	- Model evaluation helps determine if the model effectively addresses the problem and provides accurate results.
  	- Model Evaluation involves two main phrases:
  	  	- Diagnostic measures: used to ensure the model is working as intended
  	  	- Statistical significance: This type of evaluation can be applied to the model to ensure that the data is being properly handled and interpreted within the model.
  	- ROC curve (Diagnostic tool for classification model evaluation):
  	  	- Optimal model at maximum separation between the point and the red line.
<img width="628" alt="Screenshot 2024-02-03 at 1 34 08 PM" src="https://github.com/DuongNg2911/IBM-Data-Science/assets/127082369/8cf2d6cf-5f89-4360-a45e-e5088ff87ac0">

- Ninth stage: Deployment
- Tenth stage: Feedback

<img width="1372" alt="Screenshot 2024-02-03 at 3 12 33 PM" src="https://github.com/DuongNg2911/IBM-Data-Science/assets/127082369/6a12233c-37db-47b1-9ea2-e01714ca0f9e">

- Note: Each stage of this methodology is highly iterative
- CRISP-DM (Cross-industry standard process for data mining)
	- A structured approach to guide data-driven decision-making
 	- Data mining life cycle
 <img width="413" alt="Screenshot 2024-02-03 at 3 34 54 PM" src="https://github.com/DuongNg2911/IBM-Data-Science/assets/127082369/3d949b24-8206-4efb-ba9b-3270728a09e6">

 	- Data mining:
  		- Reveals patterns and structure between data
      		- Provides knowledge and insights that address the stated business problems and goals
