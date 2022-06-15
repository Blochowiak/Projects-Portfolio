# Projects Portfolio
I have three projects included in this portfolio. They are listed in order of complexity, and the relevant documents are in the files section of this repository.
1.	A cost-benefit analysis with Monte Carlo simulations to optimize XYZ café’s lunch rush
2.	Integer programming optimizing a freight airline's daily flight patterns
3.	Crane population dynamical system with decay rate and carrying capacity

Each project is explained below, with references to the attached files created for the respective projects.

# 1. XYZ Cafe Lunch Rush Optimization Model
XYZ café serves breakfast and lunch foods alongside coffee, tea, and specialty beverages. The café employs a single cashier alongside
a barista for preparing specialty drinks (each at $16 per hour). Between the cashier and barista queues, congestion can become an issue. This leads
to balking and lost revenue. The café wanted to investigate business optimization through decreasing queue lengths and balking to maximize profits.

The objectives of this project were twofold. The first was to create a model that replicated the activities of a normal day given the data provided – three
weeks of incoming business, Monday through Friday between 10:30 am and 1 pm. This model is necessary to simulate an average lunch rush with novel data
generated by random variables. Secondly, a cost-benefit analysis was performed on this model alongside two potential modifications to the current employment strategy. These are:
  * Adding a second cashier – “Second Cashier” model.
  * The barista works as a second cashier when not making drinks – “Floating Barista” model.
Both of these models would cost about $1,000 for a new Point of Sale system. However, there would likely be additional costs (training, construction disruptions, and so on).

All replicated variables were within one standard deviation from the original data (see the Technical Report for more). The cost-benefit analysis showed that adding a second cashier hurt profitability of XYZ Cafe while the Floating Barista model significantly improved the number of customers served and profitability.

### Tasks
1. Replicate a lunch rush of business based upon three weeks of prior data.
2. Modify the replication model to include an extra cashier.
3. Modify the replication model to allow for a floating barista who can act as a second cashier when not creating specialty drinks.
4. Perform a cost-benefit analysis on the three models to discern which is best. 

### Methods and Tools Used
* Descriptive Statistics
  - Performed in Excel, from mean/median/mode to correlations between continuous and dichotomous variables. (Files available upon request).
* Random variables
  - Simulated new data with random variables.
* Distributions
  - Exponential and uniform distributions were utilized to simulate new data.
* C# Programming
  - 15,000 simulations of each model were run using C#. (Executables available upon request).

## Skills
* Technical writing
* Technical presentation
* Excel, Word, PowerPoint

## What I Learned or Improved
* Interpersonal communication
* Time management
* Meeting management
* Task scheduling
* Project management
* Excel efficiency

___
# 2. Integer Program Optimizing Freight Flight Patterns
A freight company must make eleven flights every among five cities. There are four pilots; two in Des Moines, two in Green Bay. They cannot fly more than 10 hours and must return to their base city at the end of every day. Given flight lengths, wages, and flying limitations, how can this freight airline minimize the cost of making these eleven flights daily?
It was discovered that three flight patterns made daily would minimize the costs. Only one pilot would fly out of Green Bay, two out of Des Moines. This freed up one pilot in Green Bay to potentially fulfill other contracts.

### Tasks
1. Outline all parameters.
2. Create a binary coefficient matrix in Excel.
3. Create decision variables for an objective function based upon the cost of flight patterns.
4. Use Microsoft Solver to minimize the objective function.

### Methods and Tools Used
*  Integer Programming
    - Binary decision variables with a coefficient scalar of flight costs
*  Excel's Solver tool to minimize costs

## Skills
* Integer programming
* Excel
* Technical writing

## What I Learned or Improved
* Excel, expecially Solver
* Technical writing efficiency
* Project management
* Excel efficiency

___
# 3. Crane Population Dynamical System
Among the wildlife at a state park, a population of 100 cranes has been decreasing by 3.24 percent annually. In order to keep the crane population
from dissolving, along with maintaining the revenue from visitors who enjoy the crane sightings, it is paramount that the park manager grow and release
approximately eight chicks per year – the limit their resources will allow. Additionally, the carrying capacity of the park is 200 cranes. Two questions were investigated:
1. How quickly can a population of 200 cranes be reached?
2. What will it take for such a population to be maintained?

### Tasks
1. Create a recursive formula to calculate each successive year's crane population
2. Discover years until carrying capacity is reached
3. Modify model to maintain balance of approximately 200 cranes

### Methods and Tools Used
* Affine system
  - The recursive formula for this discrete system was affine
* Excel (files available upon demand)
  - All recursion and analysis were done in Excel

## Skills
* Technical writing
* Excel, Word

## What I Learned or Improved
* Excel efficiency
* Affine dynamical systems
* Technical writing efficiency
