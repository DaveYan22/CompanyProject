# CompanyProject

Dataset features:
 • company_id- Unique ID of the company.
 • industry_id- Industry ID the company is operating in.
 • topic_id- ID of the interest topic. Could be a general-business concept (e.g., sales analytics), a
 specific product (e.g., Adobe Photoshop), or a specific company (e.g., Salesforce, Apple).
 • category_id- ID of the category the topic belongs to.
 • week-Weeknumberonwhichtheinterest has been calculated.
 • interest_level- a single normalized score from 0 to 100, reflecting how much each company has
 researched the topic online this week. A score of 100 signifies high interest, while 0 indicates no
 interest at all

Task-1
1. Basic exploratory analysis of the dataset
2. Proposed scoring method
3. Suggestions on how to assess "the volatility of the scores". Please, design a metric to show how good is the solution comparing to the baseline (original scores)


Task-2
Wrap up your algorithm in to one or several .𝑝𝑦 scriptswithauxiliaryfiles(ifnecessary). 
Themain script should be customizable, taking the following parameters:– path_to_input_file- path to the input .CSV file– path_to_output_file- path where to save the processed .CSV file
 • Write an appropriate Dockerfile that results in the execution of the script.
 • Write a READMEexplaining the steps:– Howtobuildanimage given the Dockerfile– Howtoexecuteanimagetoprocessafilegivenitsinputandoutputpaths. Forexample, how
 to process folder_one/input.csv and folder_two/input.csv, using the same image but different
 "docker run ..." commands.– Note: There might be many ways how to do so, feel free to pick any.

 Task-3
1.Whichtopics are the most/least explored per company-industry?
2.Arethere any groups of keywords that are explored together?
