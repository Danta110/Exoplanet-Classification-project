This project uses machine learning to classify Kepler Objects of Interest (KOIs) as either confirmed exoplanets or false positives. 
Because space telescopes collect massive amounts of data, checking every signal manually is time-consuming. 
This project shows how ML can help automate that process and support astronomers in making faster, data-driven decisions.
The dataset contains important stellar and observational features such as brightness, surface gravity, stellar radius, and quality flags.
The data is first cleaned and preprocessed, and the target labels are converted into numerical form.
To ensure fair evaluation, the data is split into training and testing sets using stratified sampling, which keeps the class distribution balanced.
Different models, including Logistic Regression and Random Forest, are trained and evaluated using metrics like accuracy, confusion matrix, and classification report.
The goal is not only to predict correctly, but also to understand which features help distinguish real exoplanets from false detections.
