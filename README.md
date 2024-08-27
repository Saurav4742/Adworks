# adworks-gwoc


Team Name :Fantastic 4
Project: Adworks

Tech Stack: MERN

	Database:MongoDB Atlas Cloud Server
	Backend: Express and Node.js
	Frontend: React.js
	other middlewares: 
		Multer for file handling
		Redux for state management in frontend
    
   Team Members:
    Jainesh Machhi
    Krunal Javiya
    Parth Sharma
    Saurav patel
    
  How to get Started 
  1) clone the repo or download the source code
  2) For the backend:
      run the following commands
        cd adworks-backend/
        npm i
      
      Now create a new file ".env" and add the following lines of code
         
          CONNECTION_URL=<MongoDBURL>
          PORT=<Port>
          
      replace <MongoDBURL> with the database link eg "mongodb+srv://xxxxxxx:xxxxxxxx@cluster0.itedlkj.mongodb.net/adworkDB?retryWrites=true&w=majority"
	
      replace <Port> with a port number to run th server on eg : 9000
     
      Time to Roll!!!
	
    		node server.js 
	
      If consoles "DB connected Successfully" all things went correctly.
  3) for the frontend:
      run the commands
	
          cd adworks-frontend/
          npm i
	
      Now create another .env file in this folder
      Add the following lines of code
	
          REACT_APP_SERVER_URL=<your server url>
          
     replace <your server url> with the actual server url eg: "http://localhost:9000"
	
      	   npm start 
	
