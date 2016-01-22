# Syllabus


This course is a 12 step program for asking and answering scientific questions using data science practices.
We will cover the fundamentals of doing data science research, explaining "best practices" for each step, that collectively comprise the upward spiral of science.  These steps include: 

1. asking an interesting question,
  2. significance
  3. feasibility
  4. innovation
2. determining the degree to which the answer is known, 
  3. background 
3. assessing the degree to which (or probability) existing data is sufficient to obtain a satisfactory answer, 
4. exploring the data set, 
  5. how many feaures? what kind?
  6. how many samples? are they supposedly "independent?
  7. how many NaNs/Infs?
  8. what is the distribution of each feature?
  9. are the magnitudes given explicitly relavant, or are they some transformation of the property of interest? do we know the nature of that transformation?
  9. what does a "typical" subject look like?
  10. are any features correlated?
  11. are there any outlier subjects?
  12. do any subjects cluster?
5. cleaning up the dataset, 
  6. formatting to be more convenient
  7. removing outliers/features/subjects that we don't want
6. formalizing a statistical inquiry, 
   7. is our inquiry a statistical test or a parameter estimation one (almost always both) 
7. positing a statistical model which we hope will yield satisfactory answers, 
  8. restricting the model to a regime of interest, both for the null and alternative hypotheses 
8. devising a test to assess the answer, 
  7. stating a hypothesis test, with a null and alternative distribution
  8. choosing a test statistic
  9. providing a mechanism for computing the null distribution of the test statistic
  10. demonstrating via simulation/theory that p-value is small when it should be, and not small when it shouldn't be
9. building an estimator to assess the model, 
10. checking the model, 
11. reporting the results, 
12. suggesting the next experiment to perform or question to answer to further enhance the model.

Note that this course will largely be project based; each student will be expected to complete each of the above steps on some real data of interest to the student.  Lectures will be minimal, giving introductory explanations one day, hopefully only part of the time.  The rest of the time, I expect we will work independently or in small groups to complete the weekly portion of the overall project.  

No courses are formally required, though students will need to write numerical code (in R, Python, or Julia), and make reports using something like LaTeX, knitr, or Jupyter notebooks.  All code and reports will be *open*, that means using *open access data* and *open source code*.

Please come ready to do science! If you don't have questions that you want answered, you can work in small groups, but each student will need to write the code and reports on their own.  There will be no "homeworks".

- *Textbook*: https://leanpub.com/artofdatascience 
- *TA*: [Greg Kiar](gkiar07@gmail.com)
- *Grading*: Each week each group will be responsible for handing in an updated report.  Grade will be: A assuming it comes in on time, B if it comes in late, C if it never comes in.  Total grade will be an average over all weeks.
- *Pweweqs*: I assume you are comfortable with all the content in https://www.coursera.org/specializations/jhu-data-science
