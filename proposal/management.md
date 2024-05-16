# Project management plan

## The People
#### Joe
**Strengths:**
- Strong software background, completing a course on Software Systems Development from Queens’ University Belfast.
- Previous experience developing neural networks.
- Real world experience in Project Management within major construction projects.
- E-Bike enthusiast. Worked with DIY battery packs and familiar with cell chemistry.
- Relevant IIA Modules:
	- 3A5 Thermodynamics and Power Generation. Includes cell chemistry and exergetic analysis.
	- 3F8 and 3G3 - covering inference techniques. 
	- 3E6 Organisational Behaviour: Group Dynamics theories. Relevant when working in teams.
	- Hybrid Energy ExA: Analysing round-trip efficiency of Li-ion cells.
**Weaknesses:**
- Only took one information engineering module and zero electrical for IIA.
- Limited knowledge of Nyquist stability techniques. Relevant for EIS.
- Dropped Chemistry for Software at A-Level
#### Amy
**Strengths:**
- Relevant IIA Modules:
	- 3F1, 3F3, 3F8 and 3M1, providing a background in:
		- Information engineering including systems and control, data analysis, inference, statistical signal processing: LSE, MLE, MAP, Bayesian regression, classification, clustering, EM, AR models and HMMs
		- Mathematical methods including stochastic processes, and constrained and unconstrained optimisation
- 3C1 and 3A5 covering:
	- Materials, including understanding of diffusion, compounds and ions
	- Thermodynamics and power generation, including fuel cells and energy storage
- Chemistry A Level, including electrochemistry
- Projects in python skills, including a project on logistic regression, PCA analysis and a project analysing a large financial data set using pandas
**Weaknesses:**
- No IIA electronics or electrical engineering, so equivalent circuit modelling is a weakness, along with control and systems engineering
## Required Resources
Cell cycling is an expensive, and time-consuming process. Open-source datasets exist, in addition to the data provided by LiFETIME. It is not feasible for us to collect new data in the time available. No costs will be incurred and no parts are required.
## Timeline
- Wednesday 15th: 1st Meeting with LiFETIME
- Thursday 16th: **(Deliverable)** Proposal Presentation
- Present initial research.
- Monday 20th: 2nd meeting with LiFETIME.
- Thursday 23rd: Interim Presentation.
	- **Deliverables**
		- Presentation
	- **Deadlines**
		- Data model choice (EIS vs. ICA)
		- Dataset choice (NASA, Oxford, LiFETIME)
		- Model choice (Using equivalent circuit, statistical regression or deep learning)
- Monday 27th: 
	- **Deliverables**
		- Present and evaluate a functioning model.
		- Create model visualisations.
	- Enact contingency plan if deliverables incomplete.
- Tuesday 4th: **(Deliverable)** Final Presentation.
- Thursday 6th: **(Deliverable)** Documentation Completion


## Risk Assessment
There are no additional risks for this project, given that all of our work is software and research. The standard risks of everyday office work apply,  with stress due to poor planning and time management being the significant risk. The assessment below is derived from HSE guidelines for work.

| Hazard                         | Possible effects/harm                                         | Risk Rating | Detail mitigations                                                                                                  | Revised risk rating H, M, L |
| ------------------------------ | ------------------------------------------------------------- | ----------- | ------------------------------------------------------------------------------------------------------------------- | --------------------------- |
| Eye Strain                     | Headaches, discomfort, blurry vision.                         | L           | Regular breaks. Spread project schedule to reduce the need for long periods of sustained work.                      | L                           |
| Stress                         | Reduced ability to concentrate, sleep. Cardiovascular issues. | L           | Regular discussion of project schedule. Planned contingencies allowing for a reduction in scope during the project. | L                           |
| Repetitive Strain Injury (RSI) | Short and long-term musculoskeletal pain.                     | M           | Regular breaks, maintain proper workstation ergonomics.                                                             | L                           |
###### Risk Rating Guidance:
| High:<br>- Fatality to one or more individuals however infrequent.<br>- Frequent major injuries to few individuals.<br>- Likelihood of long-term muscular-skeletal problems affecting a significant number of individuals. | Immediate action required.                                                  |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------- |
| Medium:<br>- Infrequent major injuries to one/few individuals.<br>- Likelihood of long-term muscular skeletal problems affecting some individuals.                                                                         | Requires attention as soon as possible.                                     |
| Low:<br>- Minor injury occurring infrequently to few individuals.                                                                                                                                                          | Not a priority, may need attention if not as low as reasonably practicable. |
## Contingency plans
There is a chance that we could fail to deliver a functional model in time. The process may be more complicated than we expect, perhaps due to the data being less useful than we are hoping, taking longer to clean or giving us insufficient insight into the characteristics of battery degradation. 
Alternatively, we may find the project proceeds more slowly than expected due to our inexperience in this field. Whilst we are mitigating this risk through our project management plan and a thorough literature review, this process is slow and we're likely to underestimate the time required (planning fallacy).

In event that we fail to meet this deliverable by the 27th, there are many options available that would allow us to provide something of value to the startup.
First, if the quantity or quality of data is an issue, we can use open source data instead of the given data. Similarly, if progress is slow on developing our model, we could replicate an existing study rather than trying to do something new. 
Alternatively, we could provide some level of analysis of the data they’ve recorded, creating a visualisation of the data, processing it for ICA and cleaning it up for EIS, so that the team has a better understanding of how useful their data is and what it contains (eg if we can spot any degradation patterns or key features), and they can implement further steps more quickly. 
We could review available data sets and give recommendations on what is currently available for future research to utilise, especially as this will be very important for LiFETIME as they look to test their product. 
Finally, it is crucial that we ensure all of our research is well documented so that even if we can’t deliver a functional model, we still have collated research that is useful and valuable to the startup. 
