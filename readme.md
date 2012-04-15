# emojⓔⓔz - Icons for Twitter, Facebook, Instagram, Tumblr, and other social networks

This project was created for a guest lecture about mobile web applications for the CIS 350 Infrastructure Technologies course at [UofL](http://business.louisville.edu/) College of Business.

1. Start with [HTML5 Mobile Boilerplate](http://html5boilerplate.com/mobile).
  * Like starting a new presentation with a template.
  * A solid baseline for mobile web apps.
  * The comments explain best practices.
  * Thank you to [all the](https://github.com/h5bp/mobile-boilerplate/contributors) [contributors](https://github.com/h5bp/mobile-boilerplate/graphs/impact).
2. Use the button CSS from [Bootstrap](http://twitter.github.com/bootstrap/) for the icon buttons.
  * Bootstrap is an excellent collection of user HTML5 user interface components.
  * The CSS is built using the [LESS](http://lesscss.org/) dynamic stylesheet language and it's [organized well](https://github.com/twitter/bootstrap/blob/master/less/buttons.less).
  * Thank you to [all the](https://github.com/twitter/bootstrap/contributors) [contributors](https://github.com/twitter/bootstrap/graphs/impact).
3. Add a `textarea` to the top of the screen to receive the icons when pressed.
4. Added JavaScript to insert icons into the `textarea`.
  * "[JavaScript: The Good Parts](http://www.amazon.com/JavaScript-Good-Parts-Douglas-Crockford/dp/0596517742)" is a great book to start learning JavaScript.
  * Also read "[Eloquent JavaScript](http://eloquentjavascript.net/)"
  * And the [MDN documentation](https://developer.mozilla.org/en/JavaScript)
  * And learn [jQuery](http://jquery.com). The Tuts+ "[30 Days to Learn jQuery](http://tutsplus.com/course/30-days-to-learn-jquery/)" video series is great.
5. Add iOS homescreen icons and startup images
  * "[Everything you always wanted to know about touch icons](http://mathiasbynens.be/notes/touch-icons)"
  * Use the startup image to make it look like part of your UI has loaded.
6. Add a [bookmark bubble](http://code.google.com/p/mobile-bookmark-bubble/) to notify the user that the site is an installable web app.

## TODO
1. Send clipboard to social networks using APIs or URI schemes.
  * [iPhone URL Schemes](http://wiki.akosma.com/IPhone_URL_Schemes)
  * [URL Scheme Index](http://handleopenurl.com/scheme/tweetbot)
  * [Wikipedia URI Scheme](http://en.wikipedia.org/wiki/URI_scheme)

    #facebook {
      display:inline-block;
      top:90px; right:2px;
      position:fixed;
    }

    #twitter {
     display:inline-block;
      top:90px; right:32px;
      position:fixed; 
    }

    <a id="facebook" href="fb://publish/?text=✳✴➺➼➝➟"><img src="http://www.cord.edu/images/template/facebook_icon.png" border="0" /></a>
    <a id="twitter" href="tweetbot:///post?text=✳✴➺➼➝➟"><img src="http://www.cord.edu/images/template/twitter_icon.png" border="0" /></a>

2. Don't show the keyboard, [select all the text automatically](http://www.thecssninja.com/demo/clipboard/) when the `textarea` is tapped.
3. 

## References
1. [HTML5 Cross Browser Polyfills](https://github.com/Modernizr/Modernizr/wiki/HTML5-Cross-Browser-Polyfills)
2. [Glyphboard](http://mrgan.com/gb/)
3. [Emojinator](http://www.apple.com/webapps/utilities/emojinator.html)
4. [Twitter Symbols](http://twsym.com/)
5. [iPhone Emoji](http://barrow.io/posts/iphone-emoji/)