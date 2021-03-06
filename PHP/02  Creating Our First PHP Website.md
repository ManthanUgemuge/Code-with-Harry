## Creating our first PHP site
Let’s start creating our first Php website and gain some confidence. Before writing the code, it is important to understand few things about some of the files and folder structure created by XAMPP. When XAMPP is installed it creates a folder named XAMPP(By default in the C:// directory).

Inside the Xampp folder, there is a folder named htdocs which is something we will work with very frequently. This folder is home to all the websites we create using Xampp on our PC. A website is created by creating a folder inside the htdocs directory. htdocs contains several directories which contains main directories from all our websites. Here, "main directory" is the directory where all the files of a website are present. You will learn more and get used to working with multiple websites with XAMPP very soon in the course.

## Creating Multiple sites with XAMPP
A new folder is required for every new website we want to develop in Php. Let me explain with an example***

Suppose we want to start the development of a PHP website named Harry. In order to do this, we will have to follow the steps below:

1. Create a folder named harry inside htdocs folder.
2. Inside the 'Harry' folder, open Visual Studio Code by right-clicking on the blank screen > Open VS code here. Else, you can also open VS code and open the 'Harry' folder by clicking on File>Open Folder.
3. Index is the main page of the website which is opened first when we access the "Harry" folder. So, create a new file named index within VS code with extension .php (index.php). Write some code inside the index.php file and save it.
4. In your browser’s address bar, type localhost/harry. It will open the index file and show the output of the code written within “index.php” of the project "harry".
5. Try to practice by writing some code in another file with a different name. To access the page other than index, you have to type its name with an extension, such as localhost/harry/page.php.
6. You can also create a folder and move some PHP files to that folder. For instance,  you can create a folder called folderName and move a file called fileName.php to that folder. You will have to access the files by visiting localhost/harry/folderName/fileName.php after you do so. We will do things similar to this very frequently throughout the course.
