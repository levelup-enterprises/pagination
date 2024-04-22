PAGINATION

 Ver: 2.1.0
 Author: Tommy Wheeler
 
 Adds pagination for a set of data

 USES
 There are 2 ways to use pagination

 1) Render a default table with data
 	- Requires a wrapper element to be assigned to this.tableWrapper
 	- Requires this.table.columns to render data *

 2) Use pagination to handle data rendering
 	- Requires a wrapper element to be assigned to this.wrapper
 	- Requires a function to be bound to this.renderMethod
 		+ Additional parameters may be passed to this.renderMethod through this.params as an array [] *

 
 INITIALIZATION
 Passing an object on initialization is possible if you wish
 	- If using pagination to render a default table this will build the table immediately
 	
 If you do not wish to build the table on the pagination object's creation
 	- Assign a wrapper element to this.tableWrapper
 	- Call this.buildTable passing a table object (this.table) as a param
 		+ Make sure to set column objects to render correctly
