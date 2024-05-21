**Overview**

This microservice will allow a user to download an image. My plan is to implement this as a way to save all of the information displayed on the user's screen, whlie avoiding the user having to ensure that all of the content is visible in a single screenshot. The microservice is designed to be linked directly to a button or link on a webpage, which will tell the microservice specifically what image to download.

**How to Request Data**

This is currently designed to be run locally. Run the program locally by downloading all of the zip file, extracting its contents, and opening the file in VS Code or a similar program. Once there, run the following commands:
```
cd server
```
```
npm i
```
```
node index
```

Once there, check localhost:3000 to see the download button. Click on the download button to download the image specified in the code.


**Example request**

[example]

**How to Receive Data**

The file specified will be downloaded to the device being used to view the program after the button is pressed.

**UML Sequence Diagram**

[diagram]
