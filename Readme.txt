An example of how to do a basic web service that serves json.

This includes only one test service test_service.php.
This service has one parameter limit.  This limits the number of records being returned.

Example of running it in the web browser:
test_service.php?limit=100000
test_service.php?limit=1
test_service.php?limit=10

Data returned is json in format:

[
	{
	"ProductID":"1",
	"ProductName":"Chai",
	"SupplierID":"1",
	"CategoryID":"1",
	"QuantityPerUnit":"10 boxes x 20 bags",
	"UnitPrice":"18",
	"UnitsInStock":"39",
	"UnitsOnOrder":"0",
	"ReorderLevel":"10",
	"Discontinued":"0",
	"DiscontinuedDate":null
	},
	{
	"ProductID":"2",
	"ProductName":"Chang",
	"SupplierID":"1",
	"CategoryID":"1",
	"QuantityPerUnit":"24 - 12 oz bottles",
	"UnitPrice":"19",
	"UnitsInStock":"17",
	"UnitsOnOrder":"40",
	"ReorderLevel":"25",
	"Discontinued":"0",
	"DiscontinuedDate":null
	}
]	
