# Workspace-Mental-Health-Clustering
In this repository, I execute K-means and a combination of K-means and LLM and compare the results.
# Dataset
This dataset is from a 2014 survey that measures attitudes towards mental health and the frequency of mental health disorders in the tech workplace. You are also encouraged to analyze data from the ongoing 2016 survey found here.

Content
This dataset contains the following data:

Timestamp

Age

Gender

Country

state: If you live in the United States, which state or territory do you live in?

self_employed: Are you self-employed?

family_history: Do you have a family history of mental illness?

treatment: Have you sought treatment for a mental health condition?

work_interfere: If you have a mental health condition, do you feel that it interferes with your work?

no_employees: How many employees does your company or organization have?

remote_work: Do you work remotely (outside of an office) at least 50% of the time?

tech_company: Is your employer primarily a tech company/organization?

benefits: Does your employer provide mental health benefits?

care_options: Do you know the options for mental health care your employer provides?

wellness_program: Has your employer ever discussed mental health as part of an employee wellness program?

seek_help: Does your employer provide resources to learn more about mental health issues and how to seek help?

anonymity: Is your anonymity protected if you choose to take advantage of mental health or substance abuse treatment resources?

leave: How easy is it for you to take medical leave for a mental health condition?

mental_health_consequence: Do you think that discussing a mental health issue with your employer would have negative consequences?

phys_health_consequence: Do you think that discussing a physical health issue with your employer would have negative consequences?

coworkers: Would you be willing to discuss a mental health issue with your coworkers?

supervisor: Would you be willing to discuss a mental health issue with your direct supervisor(s)?

mental_health_interview: Would you bring up a mental health issue with a potential employer in an interview?
phys_health_interview: Would you bring up a physical health issue with a potential employer in an interview?

mental_vs_physical: Do you feel that your employer takes mental health as seriously as physical health?

obs_consequence: Have you heard of or observed negative consequences for coworkers with mental health conditions in your workplace?

comments: Any additional notes or comments

However, I removed some variables from this dataset due to their high null values or because of their little use. These variables include timestamps, comments, state, and country.

You can download this dataset from https://www.kaggle.com/code/aditimulye/mental-health-at-workplace/input

# Final Results
![kmeans](https://github.com/alinadikhorasgani/Workspace-Mental-Health-Clustering/assets/90984806/7c261620-ebef-4354-9538-9070ba5717a6)
![KMeans-LLM](https://github.com/alinadikhorasgani/Workspace-Mental-Health-Clustering/assets/90984806/dd800e9f-3153-4bd4-bbd3-a72bcd3ae7a7)

The provided code implements a clustering analysis using K-means and a combination of K-means with LLM (Large Language Model) to compare the results. The goal of this analysis is to identify distinct groups or clusters within a dataset.
By employing a Large Language Model (LLM) as a preprocessing step before applying K-means clustering, we observed significant enhancements in the quality and interpretability of our results. The utilization of the LLM acted as a powerful data transformation tool, enabling us to extract more meaningful and context-rich information from the textual data. As a result, our subsequent K-means clustering yielded outcomes that were not only more distinct but also easier to interpret. The LLM's ability to capture intricate patterns, nuances, and semantics in the data improved the overall performance and clarity of our analysis, making it a valuable addition to our data processing pipeline.

# References

https://towardsdatascience.com/mastering-customer-segmentation-with-llm-3d9008235f41





