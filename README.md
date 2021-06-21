# health-information-FHIR-web-application-project

## The documentation will be organized as 3 parts:
##   1. what it does and how it look
##   2. how you can test it out on your computer
##   3. how I implemented this project
      - the order of implementation
      - the Javascript code that I implemented to properly construct the query


## 1. what it does and how it look:


  This project goal was to implement a simple web application that can fetch samples of patients from the FHIR server (https://hapi.fhir.org/resource?serverId=home_r4&pretty=false&_summary=&resource=Patient) and then display the basic statistics(nubmer of patients and average age of patients) and a simple table to list all the default retreived patients datas
  
  Below is how it look like if you open this project on Google Chrome browser

![Screen Shot 2021-06-21 at 3 33 25 AM](https://user-images.githubusercontent.com/59375616/122723888-70ac9d80-d241-11eb-968a-5e3f1a042cd4.png)

![Screen Shot 2021-06-21 at 3 56 06 AM](https://user-images.githubusercontent.com/59375616/122727041-9be4bc00-d244-11eb-8f3b-34ab8427338a.png)

if you click the Buttom (New Tab for latest Data) after 15 minutes or just refresh the page, you call see the statistics and the data in the table will change

By clicking this buttom, you can open up a new tab to fetch the latest data of patients from the HAPI FHIR server:

![Screen Shot 2021-06-21 at 3 57 48 AM](https://user-images.githubusercontent.com/59375616/122727260-d9494980-d244-11eb-9f80-470b428f08e4.png)
