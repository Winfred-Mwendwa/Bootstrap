# Bootstrap
Bootstrap is a responsive css framework
Bootstrap will figure out how wide your screen is and respond by resizing your HTML elements - hence the name responsive design.
With responsive design, there is no need to design a mobile version of your website. It will look good on devices with screens of any width.
You can add Bootstrap to any app by adding the following code to the top of your HTML:
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous"/>

~Make images mobile responsive by adding the img-rresponsive class.
~Center text by adding the text-center class.
~Create a Bootstrap button by adding the btn and btn-default classes to the button element.
~Make Bootstrap buttons block elements by adding btn-block class;cover entire horizontal width of page, following elements are added on the next line
~The btn-primary class is the main color you'll use in your app. It is useful for highlighting actions you want your user to take.
~Bootstrap comes with several pre-defined colors for buttons. The btn-info class is used to call attention to optional actions that the user can take.
~The btn-danger class is the button color you'll use to notify users that the button performs a destructive action.

~Bootstrap uses a responsive 12-column grid system, which makes it easy to put elements into rows and specify each element's relative width. 
~Most of Bootstrap's classes can be applied to a div element.
~Bootstrap has different column width attributes that it uses depending on how wide the user's screen is.
~Take for example Bootstrap's col-md-* class. Here, md means medium, and * is a number specifying how many columns wide the element should be.

~Nest the elements you want to put in a row within a single <div class="row"> element.
~Nest each individual element in a <div class="col-xs-*"> element (xs-extra small screen) or md for medium screen size such as a laptop
~Also applies to form elements

~You can use Bootstrap's col-xs-* classes on form elements, too! 
~This way, our radio buttons?check boxes will be evenly spread out across the page, regardless of how wide the screen resolution is.

~All textual <input>, <textarea>, and <select> elements with the class .form-control have a width of 100%.
