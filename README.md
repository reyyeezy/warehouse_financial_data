# Warehouse Financial Data

In this excel file, we have data from a warehouse company. Data contains product sales information.
We've analyzed the dataset, using pivot tables to solve the following tasks, given by our manager.

### How many states do we distribute to in this dataset?
Solution: Using the analyze data function, we can ask the preceding question, and Excel's AI. Giving us<ins>50 States</ins>


### Manager asks for sales break down by region
Solution: We utilize pivot table to organize the sales but region. By placing Sales field in values twice, we can adjust on column to be a percentage, to easily see that west region is the highest contributor here.
 

### What is the most popular price range for us?
Solution: When creating a pivot table including price per unit as rows and sum of units sold as values, we get a long table. We can use the group function to group prices together.


### Can you create a visual for preceding table?
Solution: we use PivotChart Analyze insert chart function to create this


### Can we filter by certain dates?
Solution: Utilizing the insert timeline function we get a dynamic filter window

### Can we add a filter by region?
Solution: By adding a slicer for the region, we create another filter by region window.


### Manger says he would like to send these reports to each of the regional managers
Solution: Under PivotTable Analyze, under the options button on the far left, we can select “Show repot filter pages”, this creates new sheets from the filter separately so we can send each regional manager their respective data. 

### Find the top 5 states by region.
Solution: Create a pivot table with State under rows, Sum of Sales under values, and region under filter. We then right click on any state to filter by top 10, then changing it to top 5. Lastly, we right click the sales since it is not in descending order, sort by largest to smallest. 
