### Week 5

**Main Division** of data science questions
1. *Descriptive* Analysis
  - to describe or summarize a set of data
  - measures of central tendency
  - measures of variability
  - aimed at summarizing your sample – not for generalizing the results of the analysis to a larger population or trying to make conclusions
2. *Exploratory* Analysis
  - examine or explore the data and find relationships that weren’t previously known
  - “Correlation does not imply causation”
  - allow you to formulate hypotheses and drive the design of future studies and data collection
3. *Inferential* Analysis
  - to use a relatively small sample (subset) of data to infer or say something about the population at large
  - to extrapolate and generalize that information to a larger group
  - give a measure of your uncertainty about your estimate
4. *Predictive* Analysis
  - to use current data to make predictions about future data
  - dependent on measuring the right variables
5. *Causal* Analysis
  - to see what happens to one variable when we manipulate another variable - looking at the cause and effect of a relationship
  - fairly complicated to do with observed data alone
  -  be questions as to whether it is correlation driving your conclusions or that the assumptions underlying your analysis are valid
  - considered the gold standard in data analysis, and is seen frequently in scientific studies where scientists are trying to identify the cause of a phenomenon, but often getting appropriate data for doing a causal analysis is a challenge
  - data is usually analysed in aggregate and observed relationships are usually average effects
6. *Mechanistic* Analysis
  - not nearly as commonly used as the previous analyses
  - to understand the exact changes in variables that lead to exact changes in other variables
  - exceedingly hard to use to infer much, except in simple situations or in those that are nicely modeled by deterministic equations

**Big Data**
1. **Volume**
2. **Velocity**
3. **Variety**

**Structured And Unstructured Data**
1. Structured data is what you traditionally might think of data; long tables, spreadsheets, or databases with columns and rows of information that you can sum or average or analyse however you like within those confines.
2. unstructured data being collected from all of our digital interactions: emails, Facebook and other social media interactions, text messages, shopping habits, smartphones (and their GPS tracking), websites you visit, how long you are on that website and what you look at, CCTV cameras and other video sources, etc.
  - examples include text files and documents, websites and applications, sensor data, image files, audio files, video files, email data, and social media data

**Challenges for big data analysis**
1. Big in size
2. Constantly changing or updating
3. Overwhelming variety
4. Messy
- however, it can identify hidden correlations

**Experiment Design**
1. *Dependent Variable*
2. *Independent Variable*
3. *Hypothesis*
4. *Confounder*: An extraneous variable that may affect the relationship between the dependent and independent variables.
  - In our example, since age affects foot size and literacy is affected by age, if we see any relationship between shoe size and literacy, the relationship may actually be due to age – age is “confounding” our experimental design!
  - we can fix the confounder variable by having it as constant
5. *Control Group*
  - have a group of experimental subjects that are not *manipulated*
  - E.g.: *control* group does not receive any treatment, *treatment* group receive treatment from the experiment to study the effect of treatment on disease
6. *Blinded Group*
  - *placebo effect* where only stated to be there is treatment received but the treatment is not given appropriately
7. This “balancing” of confounders is often achieved by randomization
8. *Replication/Repetition*
9. *p-value*
  - this is a value that tells you the probability that the results of your experiment were observed by chance
  - when your p-value is less than 0.05 (in other words, there is a 5 percent chance that the differences you saw were observed by chance), a result is considered significant.
