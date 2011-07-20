## Push It - pure CSS push buttons

## Check out what these pushovers look like: Demo

![screenshot](http://dl.dropbox.com/u/349285/Screen%20shot%202011-07-19%20at%2010.22.10%20PM.png)

## How to use

Just download the file and open the button.css file in the css folder or download the repo directly
    
    git clone git@github.com:adrianrodriguez/push_it.git
  
In the folder you will also see a button.sass file if you're using compass/sass. This is something I use all the time and makes for easy color scheming of your buttons.

All you need to do is pick a color of yours and then adjust the lightness/darkness of it. For Ex:
  
    .button
      @include background-image(linear-gradient(top center, #0192f7, darken(#0192f7, 15%)))
      // border needs to match the background color of the bevel
      border: solid 1px darken(#0192f7, 20%) 
    
...and for the bevel area
  
    .button_underneath
      background: darken(#0192f7, 20%)
    
..of course adjust to your liking, but it's as simple as that.

I wish I had a place to host small splash site: cssbutton.html, but right now I don't so I can't share the cool looking splash page.

This is my first github project, so bear with me. I am totally open to questions, suggestions, comments, advice, praise, etc...

Thanks for checking this out!