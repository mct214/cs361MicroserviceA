**Overview**

This microservice will allow a user to download an image. My plan is to implement this as a way to save all of the information displayed on the user's screen, whlie avoiding the user having to ensure that all of the content is visible in a single screenshot. The microservice is designed to be linked directly to a button or link on a webpage, which will tell the microservice specifically what image to download.

**How to Request Data**

This is currently designed to be run locally. Run the program locally by downloading all of the zip file, extracting its contents, and opening the file in VS Code or a similar program. Once there, run the following commands in a terminal:
```
cd server
```
```
npm i
```
```
node index
```

Once there, drag 'index.html' into a browser window to see the download button. Click on the download button to download the image specified in the code.


**Example request**

As an example, the following is how a user could download an image using this microservice.

In the terminal:
```
cd server
```
```
npm i
```
```
node index
```
User drags index.html into browser window and selects "Download an image of Bulbasaur".

A person could implement this microservice into their code by ensuring that node.js is properly installed (including the node_modules folder and the proper package json files) and pasting the 'index.js' file into their code. So long as the html request is properly formatted, they should be able to route to an image of any name using the microservice.

**How to Receive Data**

The file specified will be downloaded to the device being used to view the program after the button is pressed.

**UML Sequence Diagram**

![image](https://github.com/mct214/cs361MicroserviceA/assets/122847004/dd172c3a-4cd8-4dd8-adac-8e0b8946297c)

