# FileShare

File sharing web app with links and password protection.
 <br>
 <br>
 The app features the following functionality:
<ul>
 <li>File upload</li>
 <li>File sharing protection with password (optional)</li>
 <li>Allowing other people to download the file by sharing the custom link generated from the app</li>
</ul>

# Dependencies:

<ul>
 <li>Npm</li>
 <li>MongoDB</li>
</ul>

# Installation & Usage

 # 1. Npm modules installation
    1. After downloading, initiate "npm install" command inside the main folder.
    2. Next, you have to execute "npm audit fix"/"npm audit fix --force".
    3. After this, execute "npm fund" and you are done with this part.

 # 2. Ensuring Back-end functionality
    1. Create an empty folder called "uploads" in the main directory.
    2. Now open the file .env and fill the mongoDB database connection string with your own mongo string (online cluster or localhost).
    3. Set a desired port number for the PORT variable as well.

 # 3. Running the project
    1. Finally, you will have to run "npm start" or click the start.bat in order to execute the project.

 # 4. Usage
    1. Click the upload file field, choose a file and click OK. If the file is successfully attached, the field will turn green.
    2. In the "Title" field, the name of the file will be visible, so you can make sure it is the right file.
    3. In the "Password" field, you can assign a password to the file, so it can be protected from unauthorized downloads. (optional)
    4. If everything is ready you can click the "Upload file" button and when the file is successfully uploaded you will receive a link on the same page which can be used to share the file with other users and allow them to download it.
