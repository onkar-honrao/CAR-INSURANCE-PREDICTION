# CAR-INSURANCE-PREDICTION

### ABOUT THE DATASET
This is a dataset from a bank in the United States. Besides usual services, this bank also provides carinsurance services. The bank organizes regular campaigns to attract new clients.The bank has potential customers data, and bank’s employees call them for advertising available car insurance options. We are provided with general information about clients (age, job, etc.) as well as more specific information about the current insurance sell campaign (communication, last contact day) and previous campaigns(attributes like previous attempts, outcome).

### CLIENT
STAR Bank is our Client, located in United States they operate in almost all states and they try to convert already existing insurance customers from a different agency to STAR by their marketing campaigns mostly Cold Call

### PROBLEM(S) TO SOLVE
The client wants to know the most important factor which determines cold call success so that they can work on it and further improve their business using the cold call data.The problem I am trying to solve involves creating predictive models and choosing the best model among them using model validation techniques to gain more insights about the key factors which contributes to cold call success and provide recommendations to improve cold call success as well. Further the model implementation can improve their business and help them on concentarting on the key areas to their success.

Lets look at the features of the dataset and understand what each attribute/feature is about.The table below shows a brief description of the dataset and whether the variables are continuous, categorical or binary.

### Feature Description
- Id :- Unique ID number. Predictions file should contain this feature. “1” … “5000”
- Age:- Age of the client
- Job:- Job of the client. "admin.", "blue-collar", etc.
- Marital:- Marital status of the client "divorced", "married", "single"
- Education:- Education level of the client "primary", "secondary", etc.
- Default:- Has credit in default? "yes" - 1,"no" - 0
- Balance:- Average yearly balance, in USD
- HHInsurance:- Is household insured "yes" - 1,"no" - 0
- CarLoan:- Has the client a car loan "yes" - 1,"no" - 0
- Communication:- Contact communication type "cellular", "telephone", “NA”
- LastContactMonth:- Month of the last contact "jan", "feb", etc.
- LastContactDay:- Day of the last contact
- CallStart:- Start time of the last call (HH:MM:SS) 12:43:15
- CallEnd:- End time of the last call (HH:MM:SS) 12:43:15
- NoOfContacts:- Number of contacts performed uring this campaign for this client
- DaysPassed:- Number of days that passed by after the client was last contacted from a previous campaign (numeric; -1 means client was not previously contacted)
- PrevAttempts:- Number of contacts performed before this campaign and for this client
- Outcome:- Outcome of the previous marketing campaign "failure", "other", "success", “NA”
- CarInsurance:- Has the client subscribed a CarInsurance? "yes" - 1,"no" - 0
