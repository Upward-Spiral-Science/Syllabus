# Potentially Useful Info 

- *Textbook*: https://leanpub.com/artofdatascience 
- *TA*: [Greg Kiar](mailto:gkiar07@gmail.com)
- *Grading*: Each week each group will be responsible for handing in an updated report.  Grade will be: A assuming it comes in on time (and I/TA can reproduce it, as necessary), B if it comes in late (and we can reproduce it), C if it never comes in (or we can't reproduce it).  Total grade will be an average over all weeks.
- *Pweweqs*: I assume you are comfortable with all the content in https://www.coursera.org/specializations/jhu-data-science
- *Class Schedule*: Tues & Thurs, 3-4:15pm
- *Location*: Gilman 132
- *Organization*: Tuesdays will be lectures, thursdays will be in class group work
- *Teamwork*: This is a *team project* based course, so pick teams, 3 people is the ideal team size for this class, ihmo
- *Assignments*: Each week assignments will be due each Monday NLT 4:00AM Eastern.  Due means pushed to your group's repo.
- [*Peer Evaluations*](http://goo.gl/forms/eEXctcr067): Each week along with assignments you will be submitting a peer evaluation. The peer evaluations are also due each Monday NLT 4:00AM Eastern. These evaluations enable us to scale group grades based on individual participation. Also, if you fail to submit the evaluations your grade will be affected. The evaluation form can be found in the link at the start of this bullet.
- *Github*: Each team should have a *public* github repo containing everything.  In the case of private data, we can discuss various options.
- *Background*: Comfortable coding in R/Python/Julia, github, Jupyter notebooks or MATLAB publish
- *Video lectures*: Most *technical* content that will be required is available in these lectures: https://www.coursera.org/specializations/jhu-data-science, in general, i'll expect familiarity with that material
- *Projects*: A list of recommended [projects](projects.md) for the course

# Class Schedule

- 01/28: 
  - Welcome
  - Overview
  - List of Projects
  - Pick Teams
  - Reading Assignment: Ch1 & Ch2 of ADS

# Outline

This course is a 12 step program for asking and answering scientific questions using data science practices.
We will cover the fundamentals of doing data science research, explaining "best practices" for each step, that collectively comprise the upward spiral of science.  These steps include: 

1. asking an interesting question,
  2. significance
  3. feasibility
  4. innovation
2. background 
  1. determining the degree to which the answer is known, 
  2. assessing the degree to which (or probability) existing data is sufficient to obtain a satisfactory answer, 
  3. what tools currently exist that we could use to find the answer (go deep and old skool)
3. Basic Math Stats: statistical models 
2. **experimental design**
  1. which data would yield the most clear answer to the question?
  2. what is the the minimal sample size needed to obtain sufficient "confidence"
  3. what is the least expensive way of obtaining such a dataset (eg, maybe one exists already?)
  4. how do we know if the should trust our answers?
4. **"exploratory" data analysis**
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
5. **"confirmatory" data analysis**
  6. formalizing a statistical inquiry, 
    7. a hypothesis test?
    8. a parameter estimate?
    9. a prediction (which is secretly a parameter estimate)? 
  7. positing a statistical model which we hope will yield satisfactory answers (perhaps one for null & one for alternative), 
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

