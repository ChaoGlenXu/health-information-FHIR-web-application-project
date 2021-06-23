# health-information-FHIR-web-application-project

## The documentation will be organized in 4 parts:
##    1. what is the web application used for
##    2. how does this web application look like
##    3. how you can test out my web application on your computer
##    4. how I implemented this project
            - the order of implementation
            - the Javascript code that I implemented to properly construct the query


## 1. what is the web application used for: 

  what is the web application used for: 
  This project goal was to implement a simple web application that can fetch samples of patients from the FHIR server (https://hapi.fhir.org/resource?serverId=home_r4&pretty=false&_summary=&resource=Patient) and then display the basic statistics(nubmer of patients and average age of patients) and a simple table to list all the default retreived patients datas
 
 I completed this web application project on June 20th, So the project goal was achieved.
 
##    2. how does this web application look like:

  Below is how it look like if you open this project on Google Chrome browser

![Screen Shot 2021-06-21 at 6 53 37 AM](https://user-images.githubusercontent.com/59375616/122751166-68625b80-d25d-11eb-889a-852f6e4259b1.png)

![Screen Shot 2021-06-21 at 6 54 08 AM](https://user-images.githubusercontent.com/59375616/122751228-7adc9500-d25d-11eb-85ad-d9c1ded9070f.png)


##    3. how you can test out my web application on your computer:

if you click the Button (New Tab for latest Data) after 15 minutes or just refresh the page, you call see the statistics and the data in the table will change

By clicking this button, you can open up a new tab to fetch the latest data of patients from the HAPI FHIR server:

![Screen Shot 2021-06-21 at 3 57 48 AM](https://user-images.githubusercontent.com/59375616/122727260-d9494980-d244-11eb-9f80-470b428f08e4.png)

Note that the data could look different when you click the button or refresh the web application at different time. The screenshot below is the data retrieved after around 30 minutes:

![Screen Shot 2021-06-21 at 5 30 21 AM](https://user-images.githubusercontent.com/59375616/122740255-cab55f00-d251-11eb-9be1-43387f31363b.png)

if you want to use this web application or test out this web application: 
- Firstly, you can download this zip file and unzip this file.
- Secondly, you can just open the file with HTML extension. 
     
###    Note that my HTML code, CSS code, and Javascript code are all in this HTML file since this is a small project. 
      
##    4. how I implemented this project:

Now I will explain how I implemented this project:
      I fist implemented some of the HTML code, then I added the style by coded the CSS code.
      Then I implemented the code to query the HAPI FHIR server by using the code below:
![Screen Shot 2021-06-21 at 5 42 07 AM](https://user-images.githubusercontent.com/59375616/122741896-6c897b80-d253-11eb-864c-17ca057ac437.png)

      If you see this snippet code above, I used the fetch() function to receive the data.
      
      The line console.log(data) can let you see the data on the console :

![Screen Shot 2021-06-21 at 5 47 37 AM](https://user-images.githubusercontent.com/59375616/122742675-30a2e600-d254-11eb-89ff-a07ea81d0b66.png)

![Screen Shot 2021-06-21 at 5 48 51 AM](https://user-images.githubusercontent.com/59375616/122742836-5def9400-d254-11eb-8fe1-be99fa608290.png)

      Yeah, so that's the end of my documentation for this project. 
      
      If you have more question about this project, feel free to contact me through email. 
      
      My email address is : chaoglen.xu@mail.utoronto.ca
      
      Thank you for your time!

