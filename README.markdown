# TowerOfHanoiJS #
JavaScript code to create Tower of Hanoi game.

Version: 0.1

This code itself is not a jQuery plugin, but this code needs jQuery and jQuery UI
to run. Make sure jQuery and jQuery UI are loaded first before create 
the Game instance.

## Documentation ##
First, you need block container for your game instance in your html document.
jQuery and jQuery UI must be loaded before this script. The following example
is the simple way to put it altogether:

    <html>
    <body>
      <div id="game-container"></div>
      <script src="js/jquery-1.7.1.min.js"></script>
      <script src="js/jquery-ui.min.js"></script>
      <script src="js/TowerOfHanoi.min.js?v=0.1"></script>
    </body>
    </html>

Create Tower of Hanoi game instance by calling Game constructor:

    jQuery(function() {
      game = new Game();
    });

Creating Game object without any options passed to constructor will create pegs
with droppable behavior and discs with draggable behavior. You need to declare
your own rule for the game, example_02.html gives you the basic overview for
the rule of the game.

## Examples ##
There are three working examples, with commented code as guide, to give you
a brief view on how this code can be used in several ways. All examples are
provided in root directory of this repository.

### example_01.html ###
Live demo of this example: http://tower-of-hanoi.appspot.com/example_01.html

### example_02.html ###
Live demo of this example: http://tower-of-hanoi.appspot.com/example_02.html

### example_03.html ###
Live demo of this example: http://tower-of-hanoi.appspot.com/example_03.html

## jQuery and jQuery UI versions ##
This code has been tested with jQuery 1.7.1 and jQuery UI 1.8.16 (both versions
included in js directory). You may help me by testing the code with other
jQuery and jQuery UI versions.

## Supported Browsers ##
Chrome 16, Firefox 4. You may help me by testing the code with other browsers.

## License ##
Copyright (c) 2012 Akeda Bagus <admin@gedex.web.id>
Licensed under MIT (http://www.opensource.org/licenses/mit-license.php) license.
