## Getting Started

- Install the version of Node JS for your OS https://nodejs.org/en/download
- From a terminal run the following commands to check if the installation was successful:
  - `$ node -v`
  - `$ npm -v`
  - Set PATH environment variable to path/to/bin/node and path/to/bin/npm if the above commands failed to return the version number.
- In the terminal install dependencies using the command:
    `$ npm install`
- In the terminal run the local server using the command:
  - `node form-server.js`
- Open "form.html" in a browser. Enter username and password and click "Submit".

## Questions for you to answer
1. What is the purpose of the _action_ attribute in the _form_ tag?  <-- a way to describe the url to click to when the form is submited 
2. What is the purpose of the _method_ attribute in the _form_ tag? <- a a way to desctibe the type of action that is completed when submitted 
3. What is the purpose of the _name_ attribute in the _input_ tag? <-- it gives us a label that we can reference in code to retreive the user input 
4. What is the purpose of the _type_ attrbute in the _input_ tag? <-- defines the type of input wanted, e.g text vs. multiple choice 
5. What is the purpose of the _label_ tag? <-- gives users a hint about what input is espexted 
6. What is the purpose of the _required_ attribute? <-- says this feild must be given an input before submission 

