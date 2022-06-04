# Find-Git-Acc
* Problem Statement: A web portal to find the profiles of Github accounts and information about their repositories.

* Project Description : The Core idea behind this project is to provide young coding enthusiasts a platform to find the profiles of a github user and information about their repositories and their projects so that it'll be more convenient for coders to get to know about helpful accounts and repos. Using this platform the user will be able to get to know about the repositories that are there on github, there will be some information regarding their education , their  whereabouts. 


* Technology Stack :
1. HTML & CSS,JavaScript
2. Microsoft Azure services

* Azure technology used :
1. Storage Accounts (Containers) :

*  An Azure storage account contains all of your Azure Storage data objects, including blobs, file shares, queues, tables, and disks. 

* The storage account provides a unique namespace for your Azure Storage data that's accessible from anywhere in the world over HTTP or HTTPS. 

* Data in your storage account is durable and highly available, secure, and massively scalable.


2. Storage accounts static website :

* You can serve static content (HTML, CSS, JavaScript, and image files) directly from a storage container named $web.

* Azure Storage static website hosting is a great option in cases where you don't require a web server to render content.

## 

* API's Used : 
Total 3 API' are used {fetchData.js}
1. To fetch the default data.
2. To get user input.
3. To fill the data.

* step by step process to deploy a website :- 

Step 1: Login to your azure portal and create a storage account first.
![Screenshot (87)](https://user-images.githubusercontent.com/97949958/172020207-e3d7b7ba-5cdb-4b25-9f8c-01196a583ca9.png)


Step 2: After Creating a storage account, on that same page select static Website in data management section in resources in the column on left side. After selecting the another page will appear which will be asking you to create a website. By clicking on the enable option on that page your website will be generated automatically and will be served from the container $web. Give the index document and error document name and save the changes made.

![Screenshot (91)](https://user-images.githubusercontent.com/97949958/172021447-7f4f6738-7480-48de-9ea1-52cd6511f0ee.png)

Step 3: Now go to the storage, open the containers and upload the website code files and images.

![Screenshot (92)](https://user-images.githubusercontent.com/97949958/172021621-437b52e3-03b3-490e-a256-abfbd79e4045.png)

![Screenshot (93)](https://user-images.githubusercontent.com/97949958/172021644-bf4b51b1-d76c-465f-8cb8-44cb60a319a2.png)

Step 4 : Once done with all of this copy the link that was generated earlier and paste it in browser . 
                  
         
         --------------------------YOUR WEBSITE WILL BE READY TO WORK-------------------------------    

Project demo website URL :  https://frtprojectstorage.z13.web.core.windows.net/

Demo video link : https://youtu.be/ZsKZPmECzxU
 
After Images :

![Screenshot (94)](https://user-images.githubusercontent.com/97949958/172022602-3e470720-5455-45c2-83e6-205bfdeec1dc.png)

![Screenshot (95)](https://user-images.githubusercontent.com/97949958/172022604-d09537dd-495f-4442-811f-5ca92cf3d232.png)
