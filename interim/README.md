# Interim report
To be read alongside slides - see in folder **Interim**

### How our objective have changed
- When we last spoke, our objectives were to decide between EIS and ICA and create a model based on which ever method we chose
- Since our last presentation, we've explored the data, creating visualisations and performing preliminary analysis
- Following three meetings with the LiFETIME team, our direction is now looking towards fitting an equivalent circuit model to the provided EIS data for one battery, and determining how well this fits for other battery types
- This decision was based on the fact EIS is quicker
- LiFETIME hasn't pursued this at all so far, and since we still haven't got access to the LiFETIME GitHub, it made sense to do this rather than work on something they already have code for 

Our new objectives are:
- Clean, process and visualise the EIS data 
This is following our feedback on our contingency plan from last time. We've already completed this, as you'll see.
- Take an EIS route, finding an ECM and fitting it
- Investigate the trade-off between applicability and accuracy
- Reporting the feasibility of this approach


### Work done so far 

EIS
- EIS is performed in a very short period of time, just a few minutes, within charging cycles that ran over several days
- This meant the data recorded was almost all zeros, with huge files containing only very small amounts of data 
- I cleaned the data to remove the zeros, and plotted the EIS spectrum, Nyquist diagrams, for all the battery types
- We only had 4 cycles, so I generated synthetically a full data set with an EIS for every cycle using interpolation
- Discuss how the last cycle in August does not match the first cycle in January, and how the synthetic data helped to show this.

ECM
- See plots

### Demonstrate feasibility
- From current ECM progress we can see that it should be feasible to achieve fitting of parameters in the remaining time frame
- Even if we find out it's not feasible to have a single ECM for the different battery types, it's still useful

### Issues faced
- We didn’t get access to LiFETIME’s GitHub until last Friday despite our pestering, which was a shame but it didn’t stop us making progress in other areas
- Difficulty with data, unclear labelling and naming conventions and general lack of documentation of the data slowed us down. It’s not entirely cleared up yet, we still are waiting for some clarification as Nicolas is checking details for us.
- The LiFETIME team are pretty busy, and they all have different areas of expertise so when we’ve met with one or two members they weren’t always able to answer every question we had

### Personal and technical development (what have you learnt and how have you learned it?) Amy
- I started from effectively square zero with my electrical knowledge, so something that’s really helped me is YouTube videos explaining key concepts, so I was able to get more out of the papers
- Aside from reading, I learnt the basics of fitting and ECM to EIS data by watching an online webinar and following that up with learning about different software options there were, also through video tutorials
- I’ve been doing the communications and coordination for meetings with with LiFETIME, always nice to brush up on administrative and time management skills
- I’ve presented my work on calls which has helped me improve my confidence, especially because the subject area is completely out of my comfort zone so it’s not been an easy exercise presenting to people that know a lot more than you
- Had some issues using codespace on GitHub, so I watched some tutorials and found a solution that worked. 
- Developed my Python skills, learnt brand new packages, such as python impedance for the ECM fitting

### Update the project development time-line and present a plan for completion
Our next steps are:
1. Clean, process and visualise the EIS data (DONE)
1. Document the data
1. Choose an ECM, using literature and our EIS data, building on current progress
1. Get a better picture of how each ECM component links to a physical aspect of the cell
1. Fit the parameters of the ECM for a single SOC, cycle number and battery type
1. Investigate whether the ECM is valid for the other battery types
1. Investigate how the ECM parameters change with SOC and cycle number


