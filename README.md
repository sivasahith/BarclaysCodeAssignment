# BarclaysCodeAssignment
Read values from json object and render values on graph

This code will help to read the JSON object from git repository url and displayed as Piechart. 

Step1 : Open Piechart.html in any browser.

Step2 : App will read the JSON object and display information on Piechart

Step3: PieChartController is restful service which will work on any application server. I write the simple restfulserverice on my local server and It reads any external url as a JSON format.

Step4: As Eventbase,  i call my restFul url(http://localhost:8080/BarClaysServer/rest/pieChartData) in index.html. Ajax Jquery will help to send request to server as Asynchronously. When ever any changes trigered on Server and PieChart data will also update.  

