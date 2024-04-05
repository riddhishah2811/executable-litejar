# Understanding
This project helps you how we can make our lite jar executable in spring boot.

## Non-executable Lite-Jar Output
<img width="601" alt="Screenshot 2024-04-06 at 1 40 24 AM" src="https://github.com/riddhishah2811/executable-litejar/assets/59967480/48f8e04a-85a9-48c9-9f48-1d46b3b849b7">

As we see, non-executable jar file doesn't have a main-class or starter-class information. It also doesn't contain the lib/ or dependencies because of that it's size is small compare to the Fat-Jar. If we want to make it executable then we can do this by changing the plugins and defining out main-class means entry point of the application in spring boot.
In this project I have done this and made a non-executable jar as a executable jar file. We can also do the same for War files.

## Executable Lite-Jar Output
<img width="601" alt="Screenshot 2024-04-06 at 1 47 26 AM" src="https://github.com/riddhishah2811/executable-litejar/assets/59967480/8f654099-e5ec-44fa-a806-906a8cfe9912">


