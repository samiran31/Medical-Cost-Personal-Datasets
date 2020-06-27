In this kernel, extensive EDA has been performed to understand the relation between each features with the changes. i:e if with increase in age, does the charges increase, if a person is smoker does he have to pay more for insurance  etc. After that I have converted this numerical feature into categorical one. For example age is categorized as young,adult, Senior Adult and BMI as underweight,healthy ,overweight and obese. 

Learning:- IF possible convert your numerical feature to categorical one, it gives better result when included in model also gives more sense when interpreted.

Once feature Engineering is Done I have used various models LR,GBR,DTR,SVR,RFR,KNN to predict the outcome and GBR gave a better result of 93%.

DESCRIPTION:
# Medical-Cost-Personal-Datasets
Insurance Forecast for a person given his age,bmi, smoking status etc

Context
Machine Learning with R by Brett Lantz is a book that provides an introduction to machine learning using R. As far as I can tell, Packt Publishing does not make its datasets available online unless you buy the book and create a user account which can be a problem if you are checking the book out from the library or borrowing the book from a friend. All of these datasets are in the public domain but simply needed some cleaning up and recoding to match the format in the book.

Content
Columns

age: age of primary beneficiary

sex: insurance contractor gender, female, male

bmi: Body mass index, providing an understanding of body, weights that are relatively high or low relative to height,
objective index of body weight (kg / m ^ 2) using the ratio of height to weight, ideally 18.5 to 24.9

children: Number of children covered by health insurance / Number of dependents

smoker: Smoking

region: the beneficiary's residential area in the US, northeast, southeast, southwest, northwest.

charges: Individual medical costs billed by health insurance
