Hi Everyone,

I hope this email finds you well. Your Homework 1 has been updated and the rubric has been attached. If you have any questions or concerns, please do not hesitate to reach out to me via email or during my office hours.

I would like to offer a few tips to improve the quality of your reports in the future:

1. **Read the prompt carefully.**
   - **Answer the question.** Please make sure that you are answering the exact question asked in the prompt. This means that you should explain why you made certain decisions, or provide explanations when asked to do so. For example, when Q3 asks you "*Which trim yields a larger optimal value of K? Why do you think this is?*", please don't ignore it. 
   - **Explain when necessary.** Your graphs alone may not provide enough information to the reader. You should also describe the steps and models you used, the purpose behind each step, and the results obtained. 
2. **Be concise.**
   - **Include only necessary graphs.** Consider the purpose of each graph you include in your report. If it does not answer the question or contribute to the answer, it should not be included. For example, please do not include a separate plot of the fitted model for every K in Q3 if not necessary.
   - **Maximize the information included in each graph.** If you can convey all the information needed in a single graph, it is better to do so. For example, if you have a line plot and a bar plot that has the same x-axis, cast them into one graph. 
   - **Ensure that the graph is readable and easy to understand.** Usually, graphs with > 6 colored and intertwined lines / > 6 colored and overlapped dots on the same vertical line are hardly readable.
   - **Hide redundant code and messages.** We do not need to see warnings or messages to understand the report, so it is best to hide these elements. Next time, any homework submitted with these elements left visible will result in a penalty. Please refer to [this website](https://bookdown.org/yihui/rmarkdown-cookbook/hide-one.html) if you do not know how to do so.
   - **Let someone else review your report.** Before you submit your report, have someone else read it to ensure that it is clear and concise. If they have difficulty understanding it, consider revising it based on their suggestions.
3. **Use cross validation.**
   - This is a technical suggestion. To prevent overfitting and ensure a stable result, make sure to use cross validation when fitting your model.

Best regards,

Rui



**Rubrics:**

Submission - 30 pts

- A single .md or .pdf file with the entire writeup, including all figures and prose. 
- A .Rmd file with the raw code used to produce the writeup.
- Submitted on time.

Question 1 - 25 pts

- 15 pts for the the figure(s), 10 pts for a clear annotation/explanation. 
- the better figures show more than one explanatory variable. If you had only one “basic” figure
  (histogram/boxplot/bar plot/scatter plot/line graph) showing one explanatory variable (e.g. average delay by day of week), your maximum score was 10 points for the figure and 5 for the caption. This data set was quite rich and we gave you plenty of tools for exploring richer relationships (e.g. delay vs day of week AND airline).
  • all figures should have clear axis labels and titles.

Question 2 - 20 pts

- 5 pts for part A and B, 5 pts for part C - graph, and 5 pts for part C - explanation

- Part A: 183 cm

- Part B: Rowing Women’s Coxed Fours

- Part C: any explanation that makes sense

  ![image-20230208211835404](C:\Users\ruizu\AppData\Roaming\Typora\typora-user-images\image-20230208211835404.png)

Question 3:

- 5 pts for each graph, 5 pts for answering the last question
- 2 pts penalty if there aren't enough Ks
- using cross validation would be great, but not using it result in no penalty this time

