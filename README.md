# Pokemon SV Mini Web Scrapping Project

### Introduction
This project will focus on web scrapping 421 entries of Pokemon. The data will be retrieved from a website that holds a table that contains all of the information we need. 

### Importing the libraries 
![image](https://user-images.githubusercontent.com/115194266/227655084-aa926d8b-1eee-4ba9-b5b8-734a2a7c01de.png)

### Setting the url. Requesting access to the website. By using '/tr', we are telling the HTML parser to look for table rows in the HTML code.
![image](https://user-images.githubusercontent.com/115194266/227655220-006a3503-00d2-40da-8002-084cc58b05e0.png)

### Let's check to see if the table was accessed correctly. We can see if we have the correct amount of columns by checking the length. There should be 12 total.
![image](https://user-images.githubusercontent.com/115194266/227655424-3dcabeba-68ab-4882-a558-4a7f40489123.png)

![image](https://user-images.githubusercontent.com/115194266/227655481-94db4fca-2bba-425f-b130-6854cecc79f4.png)

### We have the correct number of columns. We can use a for loop to see if the column names are correct.
![image](https://user-images.githubusercontent.com/115194266/227655556-c64ebff8-4a89-4742-bf6a-2dd89900b032.png)

### Making sure that the data is the correct row size. Converting the data type. Appending the data into an empty list.
![image](https://user-images.githubusercontent.com/115194266/227658170-98b475d0-3e11-4f63-b0ed-515c4dcad148.png)

### Putting the data into a pandas dataframe.
![image](https://user-images.githubusercontent.com/115194266/227660435-450ce775-9624-4948-a098-662ee4fbe75f.png)

### Exporting the dataframe to a csv.
![image](https://user-images.githubusercontent.com/115194266/227660475-b0388e31-da42-4f74-a0c8-948dbbef3b7d.png)

