# KFreund-Final-Project

Problem: Can a model be created to predict adoptions of shelter animals?

Data: The data set was collected from data.world. The orginal dataset was produced by the Austin Animal Shelter. This data was chosen because it included detailed information about individual intakes as opposed to summary data reported by most shelters.

ETL: Data was loaded in jupyter notebook and a Pandas dataframe was created. Null values and redundant columns were removed. Data was limited to just cat and dog entries due to the researcher's interest in adoption outcomes.

Data Analysis: Summary statistics were evaluated for intakes, outcomes, and feline/canine adoptions. Visualizations were created using Tableau.

ML Model: Otcomes were simplified to "Adoption" and "Not Adopted." Data was numerically encoded using Pandas. A random forest model was made using Scikit-learn and a grid search was performed to establish optimal parameters. The final product had an accuracy of approximately 72%, which given the use case, was deemed useful although not extremely accurate.

Additional details were then added to the webpage including external links.