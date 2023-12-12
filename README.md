![image](https://github.com/dynamomanal/student-portfolio/assets/133088089/b49db1f1-3458-43b1-bd3c-dc70c9062049)
![image](https://github.com/dynamomanal/student-portfolio/assets/133088089/4f3a4392-0dcf-4525-bac0-5b734ca4ceaa)

To start a lite server in Node.js, you can use the lite-server package. Here are the steps to install and use it:

Install Node.js: Node.js manages npm libraries and dependencies to support some browsers when loading particular pages. It also serves the run-time environment on the localhost (local machine). Node.js can be downloaded from their official website. Install the downloaded setup by following the instructions in the installation wizard. After installation, the Node version can be checked using the following command. node -v
nitialize a new Node project: Navigate to the folder or application where the lite-server has to be used. In that folder, use npm to initialize a project. The parameters can be specified as asked by the prompt. This will create a package.json file containing information about the project.

Install and configure lite-server: In the same folder, install lite-server using the below npm command. This will automatically download the lite-server package and make it ready to be configured.

npm install lite-server --save-dev

The newly added files can be seen in the folder. In the package.json file that is created, change the starting file to the one we created earlier (or any file according to your application). The following lines have to be also added under the scripts section in the package.json. This will specify the server to start whenever the start command is run.

JSON
AI-generated code. Review and use carefully. More info on FAQ.

"start": "npm run lite",
"lite" : "lite-server",
Start the server: The server can now be started using the start command. The details of the server would be displayed if the server started successfully. It also shows the local and external access URLs that can be used to access the server.
npm start

After the starting of the server, the default browser will automatically start a new tab at localhost:3000 which means the server was successfully installed and started. The server can be closed by pressing Ctrl + C in the command prompt running the server.
