Install Option 1
---------------------------------------------------------------------------------------------------------------------------------
To install the font, copy the `@font-face` rule and paste it into a CSS file or in the HTML document (inbetween a set of `style`
      tags). Example on how to apply it are below it.

    <style>
    @font-face {
    	font-family: "SteamWreck";
    	src: url("https://cdn.rawgit.com/heyitguyfixit/font/c31f413d/SteamWreck/SteamWreck%20Regular.ttf") format("opentype"); /* .ttf */
    	unicode-range: U+?????;
    }
    @font-face {
    	font-family: "SteamWreck Bold";
    	src: url("https://cdn.rawgit.com/heyitguyfixit/font/c31f413d/SteamWreck/SteamWreck%20Bold.ttf") format("opentype"); /* .ttf */
    	unicode-range: U+?????;
    }
    @font-face {
    	font-family: "SteamWreck Bold Italic";
    	src: url("https://cdn.rawgit.com/heyitguyfixit/font/c31f413d/SteamWreck/SteamWreck%20BoldItalic.ttf") format("opentype"); /* .ttf */
    	unicode-range: U+?????;
    }
    @font-face {
    	font-family: "SteamWreck Italic";
    	src: url("https://cdn.rawgit.com/heyitguyfixit/font/c31f413d/SteamWreck/SteamWreck%20Italic.ttf") format("opentype"); /* .ttf */
    	unicode-range: U+?????;
    }

    p .example1 { 
          font-family: "SteamWreck";
    }
    </style>

    <p class="example1">Hello world!</p>


Install Option 2
---------------------------------------------------------------------------------------------------------------------------------
To install the font, copy the @import rule and paste it into a CSS file or in the HTML document (inbetween a set of style
tags). Example on how to apply it are below it.

      <style>
      @import url("https://cdn.rawgit.com/heyitguyfixit/font/master/SteamWreck/SteamWreck.css");

      p .example2 { 
            font-family: "SteamWreck";
      }
      </style>
      <p class="example2">Hello world!</p>
