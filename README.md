# jquery.toast.basic

A basic toast plugin.

## Required Files

    <link rel="stylesheet" type="text/css" href="../src/jquery.basic.toast.css" />
    <script type="text/javascript" src="http://code.jquery.com/jquery-1.11.2.min.js"></script>
    <script type="text/javascript" src="../src/jquery.basic.toast.js"></script>

## Usage

    $.Toast(message, options);

Example:

    $.Toast('Hello world.');
    $.Toast('Error world.', {'duration': 1000, 'class': 'alert'});

## Options

Options include toast duration, stickiness, and toast type.

* **width** - Determines width of toast. (default: self-adaption)
* **duration** - Milliseconds duration for toast display. (default: 5000)
* **class** - Determines css class: blank, 'alert', 'info', 'success'. (default is blank, add your own class if you want to customise)
* **position** - Positionning toast top / bottom. (default is bottom)
* **align** - Align toast left / center / right. (default is right)
* **zindex** - Z-Index value for the toast container. (default is 999999)
