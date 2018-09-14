# Angular-Getting Started
Materials for the ["Angular: Getting Started"](http://bit.ly/Angular-GettingStarted) course on Pluralsight.

`APM-Start`: The starter files set up for use in VSCode, WebStorm, or other editors. **Use this to code along with the course**. (Updated for <i>Angular version 6 or higher</i>)

`APM-Final`: The completed files. Use this to see the completed solution from the course. (Updated for <i>Angular version 6 or higher</i>)

# Screenshots

### Homepage
![Home Page](/screenshots/desktopview.PNG)

### Responsive View
![Product Page](/screenshots/responsiveView.PNG)


See the `README.md` file under each folder for details on installing and running the application.

NOTE: The installation was tested using node v8.10.0 and npm 6.0.1.

NOTE: If you chose to use Stackblitz, note that it currently does not support reading json files from a folder defined in the angular.json file. Rather, you need to copy the products folder from the api folder to the assets folder. Then modify the productUrl to look in the assets folder: private productUrl = 'assets/products/products.json';

Note also that Stackblitz does not seem to recognize the Font Awesome icons. So you will instead see portions of squares.
