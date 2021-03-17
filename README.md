# Coal Tipple Operations

### Background Information
The Aspen-Boulder Coal Company runs a loading facility consisting of a large coal tipple. When the coal trains arrive, they are loaded from the tipple. The standard coal train takes 3 hours to load, and the tipple’s capacity is 1.5 standard trainloads of coal. Each day, the railroad sends three standard trains to the loading facility, and they arrive at any time between 5 A.M. and 8 P.M. local time. Each of the trains has three engines. If a train arrives and sits idle while waiting to be loaded, the railroad charges a special fee, called a demurrage. The fee is \$5,000 per engine per hour. In addition, a high-capacity train arrives once a week every Thursday between 11 A.M. and 1 P.M. This special train has five engines and holds twice as much coal as a standard train. An empty tipple can be loaded directly from the mine to its capacity in six hours by a single loading crew. This crew (and its associate equipment) costs \$9,000 per hour. A second crew can be called out to increase the loading rate by conducting an additional tipple-loading operation at the cost of \$12,000 per hour. Because of safety requirements, during tipple loading, no trains can be loaded. Whenever train loading is interrupted to load the tipple, demurrage charges are in effect.  

### Problem
The management of the Coal Company has asked you to determine the 
expected annual costs of this tipple’s loading operations.  

__Your analysis should include the following considerations:__  
- How often should the second crew be called out?  
- What are the expected monthly demurrage costs?  
- If the standard trains could be scheduled to arrive at precise times, 
- what daily schedule would
- minimize loading costs?  
- Would a third tipple-loading crew at \$12,000 per hour 
- reduce annual operations?  
- Can this tipple support a fourth standard train every day?  

### File Explanation
Files Included:
- Scripts:
	- create_schedule.ipynb - File used to create the randomized arrival schedule (schedule.csv)
	-compute_costs.ipynb - File used to run simulation and compute costs
- Data:
	- schedule.csv - Randomized train arrival schedule
	- output.csv - schedule.csv appended with columns and values for Demurrage, Crew Cost, Total Cost, and Max Crew # for each record
	- monthly_demurrage.csv - demurrage calculated for each calendar month (factoring in the variance in length) with the average computed and included as the projected value.
	- annual_costs.csv - total annual costs aggregated over the entire data set (roughly 27 "years") with the average computed and included as the projected value.
