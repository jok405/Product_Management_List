# Angular-Getting Started
Documentation is available using Angular 6 and Angular CLI online.

# Screenshots

### Homepage
![Home Page](/screenshots/desktopview.PNG)

### Responsive View
![Product Page](/screenshots/responsiveView.PNG)


See the `README.md` file under each folder for details on installing and running the application.

NOTE: The installation was tested using node v8.10.0 and npm 6.0.1.

NOTE: If you chose to use Stackblitz, note that it currently does not support reading json files from a folder defined in the angular.json file. Rather, you need to copy the products folder from the api folder to the assets folder. Then modify the productUrl to look in the assets folder: private productUrl = 'assets/products/products.json';

Note also that Stackblitz does not seem to recognize the Font Awesome icons. So you will instead see portions of squares.
