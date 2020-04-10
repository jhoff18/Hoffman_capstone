# 2020 Capstone Assignment:

## Statistically Design an Experiment

tl;dr

* This is the last one
* Turn this by the due date. 
* Write it in an R markdown and submit knitted html
* You can collaborate in so far as giving and receiving feedback from colleagues.
* 5 pts per item!
* For a rubric on how to write this, see Chapter 10 in JABSTB. Follow that multi-step format!!!

Code chunk example:
```
# this is code
a <- fitdecay1(x, y, half$data, 1, 0, 100, weigh=F)
if (isAwesome){
  return true
}
```
## Instructions

1. Provide a brief background and significance about a specific research problem that interests you. It could be project you’re involved with now, or a rotation project, or something you’d like to work on. The reader will need to understand enough background to make sense of the experiment you propose below. Keep it brief. In one short paragraph.

2. Briefly state something that is unknown about this system that can be discovered through, and leads to, an experiment.  For example, "It is not known whether....."

3. Make an “if” “then” prediction that is related to item #2. It should be of the general form, “if X is true, then Y should happen”.

4. What dependent variable will be observed to test this prediction in item #3? What predictor variable will be used to manipulate the system experimentally? Define the inherent properties of these variables (eg, are they sorted, ordered or measured).

5. Write a statistical hypothesis.  There should be a null and alternate. These should be explicitly consistent with the prediction in item #3 and the response variable in #4. In other words, make sure the statistical hypotheses that you write here serves as a test of the prediction made in item #3.

6. What is the statistical test you would use to test the hypothesis in item #5? Briefly defend what makes this appropriate for the hypothesis and the experimental variables. If there are alternatives, why is this approach chosen instead? Points will not be awarded if the justification involves something like "because everybody does it this way".

7. List the procedures and decision rules you have for executing and interpreting the experiment. These procedures range from selection of experimental units, to randomization to primary endpoint to threshold decisions. Define (and defend) what you believe will be the independent replicate.

8. Produce a graph of a simulation for the expected results. Create a dataMaker-like function in R to create and plot the data. Label and scale any axis. The graph should illustrate the magnitude of the expected response, or the level of response that you expect to see and would be minimally scientifically relevant. Be sure to illustrate any variation that is expected.

9. Write and perform a Monte Carlo analysis to calculate a sample size necessary to test the hypothesis. This Monte Carlo must test the primary endpoint.

10. Write up in RMarkdown. Code chunks to illustrate specific points are welcome other than for the Monte Carlo code. Knit and submit and html document by the due data.
