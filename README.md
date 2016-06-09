# egen-be-challenge
egen-be-challenge
Alert Module sapmle urls
============================================
read all 					--  http://localhost:8081/alert
read all in a time range	--  http://localhost:8081/alert/query?from=1465447429505&to=1465447515325


Metrics module sample urls
============================================
read all(GET) 				-- http://localhost:8080/weight
read all in a time range	-- http://localhost:8080/weight/query?from=1465447429505&to=1465447515325
create metric (POST)    	-- http://localhost:8080/weight

Git Repositories
=============================================
https://github.com/skarun3/EgenAlerts.git
https://github.com/skarun3/EgenMetrics.git

General Comments
=============================================
There are two projects EgenAlerts and EgenMetrics
Please read the comments in the property files in each module.
Application.java is the starting file in both modules.
