# Activity: Statistics of Gene Expression

## Instructions 

- Each student will submit the activity individually to Canvas, but students are encouraged to help one another complete the work
- Complete the **Statistics of Gene Expression** Activity found in the DataComputing eBook
    - make sure you carefully follow the instructions and mirror the code in the activity as you work 
    - **every task in the activity should have narrative text describing your observations; most steps also require code chunks and corresponding output.**
    - you should make at least 3 commits in GitHub as you complete the activity
- submit the completed R Notebook to Canvas before deadline



## Grading

Assignment is worth a total of 15 points.

- [5 points] Follow along with the activity in the book and reproduce the following figures as they appear in the book  
      - Figure 18.1: A bar chart comparing TOP3A expression in the different tissue types.  
      - Figure 18.2: TOP3A expression in the individual cells.  
      - Figure 18.3: TOP3A Bar chart with individual cells overlaid  
      - Figure 18.4: TOP3A Dynamite plot (bar chart with error bars)  
      - Figure 18.5: "Better than Dynamite" (TOP3A expression in the individual cells with overlaid confidence intervals by tissue type)  
- [1 point] Figure 18.1 Critique 
- [2 point] Your turn: Pick your own probe and make a figure like that of Figure 18.5.
- [2 points] recreate Figure 18.6 showing 30 Probes with largest r-squared for expression level explained by tissue type
- [2 points] **Your Turn** Choose one probe with high R-squared.  Plot expression versus tissue type (like Figure 18.5)
- [2 points] recreate Figure 18.7 (overlaid density plots) 
- [1 points] recreate Figure 18.8 (comparison of highest R^2 from actual data and the Null)
- [1 point] Push changes to GitHub


## Tips

#### Warning 

In the "Probing for a Probe" section, you're introduced to the `dplyr::do( )` function... this step is "slow" (i.e. takes a long time). Your code will actually fit a regression model to each of more than 32,000 probes and then store the R-squared for each one of them.  In fact, if you understand what it's doing, it happens *incredibly fast*... but it still takes a long time (i.e., a couple minutes depending on your available computational resources).


#### Hints

- For the critique of Figure 18.1, make sure to address what about the data is not being displayed in Figure 18.1. 
- AFTER you have written your critique of Figure 18.1, among the "several suggestions for improving the graphic", #3 and #4 will be most handy  
- You'll need to combine elements of previous plots in order to produce Figure 18.5
- When you reproduce Figure 18.5 for a new Probe in the **Your Turn** portion, you shouldn't start from scratch.  Find code earlier in the assignment that you can copy, paste, and modify to investigate the Probe of interest.


#### More information about....

- ... Gene Expression: <https://en.wikipedia.org/wiki/Gene_expression>
- ... $R^2$: <https://en.wikipedia.org/wiki/Coefficient_of_determination>
- ... False Discovery Rates: <https://en.wikipedia.org/wiki/False_discovery_rate>
- ... Approaches to simulating null hypothesis: <https://bookdown.org/ajsage/statistics_for_data_science_notes/simulation-based-hypothesis-tests.html> 
  - Side note: this is what my current research is about. If you're interested, I can tell you all about it! 
