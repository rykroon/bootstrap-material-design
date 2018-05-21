# bootstrap-material-design
Custom Bootstrap 4 theme with a hint of Material Design.

Create your own Color scheme by adjusting the following code in scss/custom.scss

//Custom Color Scheme
$primary-light:		$blue-300;
$primary:       	$blue-500;
$primary-dark:		$blue-700;
$secondary:     	$teal-A700;

//Add Primary Dark and Primary Light themes
$theme-colors: (
  "primary-dark": 		$primary-dark,
  "primary-light": 		$primary-light,	 
);

I have manually added all of the colors from "https://material.io/design/color/the-color-system.html#tools-for-picking-colors"

See the part labeled "2014 Material Design color palettes"

Just choose the colors and assign them to $primary, $primary-light, $primary-dark, and $secondary

then run "sass scss/custom.scss scss/custom_bootstrap.css"


