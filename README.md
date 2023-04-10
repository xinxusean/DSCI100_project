# Please use/make edits to ProjectReport.ipynb NOT ProjectProposal.ipynb
# Please use git pull before modifying any file in Jupyter Notebook!
# Please see the following link for how to use git pull https://datasciencebook.ca/Getting-started-with-version-control.html#pulling-changes-from-a-remote-repository

https://ubc.zoom.us/j/69584216044?pwd=c3ZOajBSS0lyS0RvQ1h3MlhuMHpxQT09
695 8421 6044 passcode 501204
Apr 10, 2023 02:00 PM Vancouver

*Project Info Notes:* https://docs.google.com/document/d/16KH3VHFBkNK44VXUcl2z_SKX3jJ644Mw-Ivczh8frhc/edit?usp=sharing

*Group Contract:* https://docs.google.com/document/d/1If7IfTIdSsfvsYHG8RFmIZaK1DL3zR_YH14zobUIOq8/edit?usp=sharing

*Energy efficiency*:   https://archive.ics.uci.edu/ml/datasets/Energy+efficiency (regression) - we choose this
1. planning on working with surface area, overall height, and glazing area predictors
1. predicting heating load due to that being more important in vancouver 

**PROJECT REPORT TODO**
 - Dataset Dictionary (TA feedback) - Sean
 - Update Method to explain what we are doing - Mattias
 - Comparison of K-NN vs Linear Regression - Jiawei
 - visualize the data analysis (ADA)
 - Summary of Findings - Ada/Mattias
 - Is This What We Expected - (MATTIAS)
 - Future Questions (if it needs to be updated) - Sean
 - Make sure to add quotes from sources somewhere - Sean
 - The lovely panic about word count
 - Add figure numbers (at the end) add the labels and legends to all the tables and diagrams - Jiawei
 
 **QUESTIONS TO ASK TA**
 - Ask about potentially different predictors for knn vs linear regression
 - Ask about how we split up our code blocks
 - Ask about best k being 1
 - Ask which values of k we should be testing, we are currently jumping by 1s from 1 to 100. Do we need to justify this?
 - Set seed to different values changes what the best k is
 - ask how to do this with more than 1 predictor variable (both knn and linear regression)
 - Summary of findings: (only summarize for Linear regresion or also summarize for K-NN as well), likely both
 - also we might also need to describe (in words, i.e. not code) what we are doing
 - do we need the coeffecients block? (it's dupliated from the above)
 
 Title
Introduction:
provide some relevant background information on the topic so that someone unfamiliar with it will be prepared to understand the rest of your report
clearly state the question you tried to answer with your project
identify and describe the dataset that was used to answer the question
Methods & Results:
describe in written English the methods you used to perform your analysis from beginning to end that narrates the code the does the analysis.
your report should include code which:
loads data from the original source on the web 
wrangles and cleans the data from it's original (downloaded) format to the format necessary for the planned analysis
performs a summary of the data set that is relevant for exploratory data analysis related to the planned analysis 
creates a visualization of the dataset that is relevant for exploratory data analysis related to the planned analysis

- the part above is already done (from project proposal), though we should add a label the table and figures with a number and a legend
- also we might also need to describe (in words, i.e. not code) what we are doing

- other tasks:
   - performing the data anlaysis (both knn and linear regression) (ADA) SEAN? DONE
   - visualize the data analysis (ADA) - 
   - summarize what you found
   - discuss whether this is what you expected to find? (MATTIAS)
   - discuss what impact could such findings have? (SEAN) - there are currently tools that help architects design energy effecient buildings, our findings and the dataset we used could help them refine and evaluate their tools. http://designadvisor.mit.edu/design/papers/urban_glicksman_simbuild_2006.pdf
   - discuss what future questions could this lead to? (DONE?)
   - At least 2 citations of literature relevant to the project (format is your choice, just be consistent across the references). (SEAN) https://docs.google.com/document/d/1eoOzmqIawpVto1p7KN6TKj_YG9I7e_B-KnJK7tCzbtw/edit?usp=sharing (highlighted ones are the ones I plan to use)
   - add the labels and legends to all the tables and diagrams

