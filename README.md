# Introduction-to-Data-Science

|   Field             |   type         |   NULL        |   Key         |
|:------------------- |:--------------:|:-------------:|  ------------:|
| guest_no            | varchar(50)    | NO            |               |
| guest_name          | varchar(20)    | NO            |               |
| guest_address       | decimal(5,0)   | NO            |PRI            |



|   guest_no             |   guest_name         |   guest_address        |
|:------------------- |:--------------:|-------------:| 
|10001|	John Kay|	56 High St, London
|10002|	Mike Ritchie|	18 Tain St, London
|10003|	Mary Tregear|	5 Tarbot Rd, Aberdeen
|10004|	Joe Keogh	|2 Fergus Dr, Aberdeen
|10005|	Carol Farrel|	6 Achray St, Glasgow
|10006|	Tina Murphy	|63 Well St, Glasgow
|10007|	Tony Shaw	|12 Park Pl, Glasgow
|10008|	knight Darren|	13 , Berlin
|10010|	krishna	|Kukatpally hyderabad


|   Field             |   type         |   NULL        |   Key         |
|:------------------- |:--------------:|:-------------:|  ------------:|
|hotel_id	            |varchar(10)	   |NO	           |PRI	           |
|hotel_name	          |varchar(20)	   |NO		         |               |
|city	                |varchar(20)	   |NO		         |               |

|   Field             |   type         |   NULL        |   Key         |
|:------------------- |:--------------:|:-------------:|  ------------:|
|room_id	|decimal(5,0)|	YES|	MUL|
|hotel_id	|varchar(10)	|YES|	MUL|
|room_type	|varchar(10)|	YES	|
|price	|int(11)	|YES	|

|   Field             |   type         |   NULL        |   Key         |
|:------------------- |:--------------:|:-------------:|  ------------:|
|hotel_id	|varchar(10)	|NO	|PRI|
|guest_no	|decimal(5,0)|	NO|	PRI|
|date_from	|date	|NO|	PRI|
|date_to|	date|	NO|	
|room_id	|decimal(5,0)	|NO	|MUL|

|   hotel_id             |   hotel_name         |   city        |
|:------------------- |:--------------:|-------------:| 
|ch01|	Omni Shoreham|	London|
|ch02|	Phoenix Park|	London|
|dc01|	Latham	|Berlin|
|dc02|	lemon	|Berlin|
|fb01|	Grosvenor|	London|
|fb02|	Watergate|	Paris|
|hy01	|Taj	|Hyderabad|


|   room_id             |   hotel_id         |   room_type        |   price         |
|:------------------- |:--------------:|:-------------:|  ------------:|
|501	|fb01	|single	|500|
|601	|fb01	|double	|1000|
|701	|fb01	|family	|1500|
|1001|	fb02	|single|	300|
|1101|	fb02	|double|	600|
|1001|	ch01	|single|	400|
|1101|	ch01	|family|	800|
|701	|ch02	|single	|250|
|801	|ch02	|double	|500|
|901	|dc01	|single	|600|
|1001|	dc01	|double|	1200|
|1101|	dc01	|family|	2400|
|1001|	dc02	|single|	900|
|1101|	dc02	|double|	1800|
|701	|dc02	|family	|2600|
|1001|	hy01	|single|	200|
|1101|	hy01	|double|	400|
|701	|hy01	|family	|800|
