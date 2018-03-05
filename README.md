# restaf-apiexplorer

An useful application to explore SAS REST APIs. This is also a great example of using restaf
to build a medium-sized application.

Please review the source code to see how restaf is used to achieve
the desired goal with minimal coding.


## Install
```
git clone https://<this github>/restaf-apiexplorer.git
cd restaf-apiexplorer
npm install

example:
git clone https://github.com/sassoftware/restaf-apiexplorer.git
cd restaf-apiexplorer
npm install
```

## Configure the app
### Server setup
To run this application you need to do the following:

1. Ask your system administrator to enable CORS using the SAS Environment Manager.

2. Ask your system administrator to give you a clientid and clientSecret appropriate
for implicit flow with no callback.

### Creating env file
Copy the apiexplorer.env file to some location.
Edit apiexplorer.env file and follow the instructions in the file.
Key values to set:

1. VIYA_SERVER
2. CLIENTID
3. CLIENTSECRET



## Running the application
```
npm start <env file>

ex: let us say you saved the myenv file one level above the project directory
npm start ../myenv.file
```

Now visit the site indicated in the console and follow the instructions.



