Install Option 1
---------------------------------------------------------------------------------------------------------------------------------
To install the font, copy the `@font-face` rule and paste it into a CSS file or in the HTML document (inbetween a set of `style`
      tags). Example on how to apply it are below it.

    <style>
    @font-face {
    	font-family: "Steamwreck";
    	src: url("https://cdn.rawgit.com/heyitguyfixit/font/ae1cae1c/Steamwreck/Steamwreck.otf") format("opentype"); /* .otf */
    	unicode-range: U+?????;
    }
    @font-face {
    	font-family: "Steamwreck Bold";
    	src: url("https://cdn.rawgit.com/heyitguyfixit/font/ae1cae1c/Steamwreck/Steamwreck%20Bold.otf") format("opentype"); /* .otf */
    	unicode-range: U+?????;
    }
    @font-face {
    	font-family: "Steamwreck Bold Italic";
    	src: url("https://cdn.rawgit.com/heyitguyfixit/font/ae1cae1c/Steamwreck/Steamwreck%20BoldItalic.otf") format("opentype"); /* .otf */
    	unicode-range: U+?????;
    }
    @font-face {
    	font-family: "Steamwreck Italic";
    	src: url("https://cdn.rawgit.com/heyitguyfixit/font/ae1cae1c/Steamwreck/Steamwreck%20Italic.otf") format("opentype"); /* .otf */
    	unicode-range: U+?????;
    }

    p .example1 { 
          font-family: "Steamwreck";
    }
    </style>

    <p class="example1">Hello world!</p>


Install Option 2
---------------------------------------------------------------------------------------------------------------------------------
To install the font, copy the @import rule and paste it into a CSS file or in the HTML document (inbetween a set of style
tags). Example on how to apply it are below it.

      <style>
      @import url("https://cdn.rawgit.com/heyitguyfixit/font/master/Steamwreck/Steamwreck.css");

      p .example2 { 
            font-family: "Steamwreck";
      }
      </style>
      <p class="example2">Hello world!</p>
