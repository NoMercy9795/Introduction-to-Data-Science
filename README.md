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
