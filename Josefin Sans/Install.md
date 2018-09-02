Install Option 1
---------------------------------------------------------------------------------------------------------------------------------
To install the font, copy the `@font-face` rule and paste it into a CSS file or in the HTML document (inbetween a set of `style`
      tags). Example on how to apply it are below it.

    <style>
    @font-face {
    	font-family: "Josefin Sans";
    	src: url("https://cdn.rawgit.com/heyitguyfixit/font/c31f413d/Josefin%20Sans/JosefinSans-Regular.ttf") format("opentype"); /* .ttf */
    	unicode-range: U+?????;
    }
    @font-face {
    	font-family: "Josefin Sans Bold";
    	src: url("https://cdn.rawgit.com/heyitguyfixit/font/c31f413d/Josefin%20Sans/JosefinSans-Bold.ttf") format("opentype"); /* .ttf */
    	unicode-range: U+?????;
    }
    @font-face {
    	font-family: "Josefin Sans Bold Italic";
    	src: url("https://cdn.rawgit.com/heyitguyfixit/font/c31f413d/Josefin%20Sans/JosefinSans-BoldItalic.ttf") format("opentype"); /* .ttf */
    	unicode-range: U+?????;
    }
    @font-face {
    	font-family: "Josefin Sans Italic";
    	src: url("https://cdn.rawgit.com/heyitguyfixit/font/c31f413d/Josefin%20Sans/JosefinSans-Italic.ttf") format("opentype"); /* .ttf */
    	unicode-range: U+?????;
    }
    @font-face {
    	font-family: "Josefin Sans Light";
    	src: url("https://cdn.rawgit.com/heyitguyfixit/font/c31f413d/Josefin%20Sans/JosefinSans-Light.ttf") format("opentype"); /* .ttf */
    	unicode-range: U+?????;
    }
    @font-face {
    	font-family: "Josefin Sans Light Italic";
    	src: url("https://cdn.rawgit.com/heyitguyfixit/font/c31f413d/Josefin%20Sans/JosefinSans-LightItalic.ttf") format("opentype"); /* .ttf */
    	unicode-range: U+?????;
    }
    @font-face {
    	font-family: "Josefin Sans Regular";
    	src: url("https://cdn.rawgit.com/heyitguyfixit/font/c31f413d/Josefin%20Sans/JosefinSans-Regular.ttf") format("opentype"); /* .ttf */
    	unicode-range: U+?????;
    }
    @font-face {
    	font-family: "Josefin Sans Semi-Bold";
    	src: url("https://cdn.rawgit.com/heyitguyfixit/font/c31f413d/Josefin%20Sans/JosefinSans-SemiBold.ttf") format("opentype"); /* .ttf */
    	unicode-range: U+?????;
    }
    @font-face {
    	font-family: "Josefin Sans Semi-Bold Italic";
    	src: url("https://cdn.rawgit.com/heyitguyfixit/font/c31f413d/Josefin%20Sans/JosefinSans-SemiBoldItalic.ttf") format("opentype"); /* .ttf */
    	unicode-range: U+?????;
    }
    @font-face {
    	font-family: "Josefin Sans Thin";
    	src: url("https://cdn.rawgit.com/heyitguyfixit/font/c31f413d/Josefin%20Sans/JosefinSans-Thin.ttf") format("opentype"); /* .ttf */
    	unicode-range: U+?????;
    }
    @font-face {
    	font-family: "Josefin Sans Thin Italic";
    	src: url("https://cdn.rawgit.com/heyitguyfixit/font/c31f413d/Josefin%20Sans/JosefinSans-ThinItalic.ttf") format("opentype"); /* .ttf */
    	unicode-range: U+?????;
    }

    p .example1 { 
          font-family: "Josefin Sans";
    }
    </style>

    <p class="example1">Hello world!</p>


Install Option 2
---------------------------------------------------------------------------------------------------------------------------------
To install the font, copy the @import rule and paste it into a CSS file or in the HTML document (inbetween a set of style
tags). Example on how to apply it are below it.

      <style>
      @import url("https://cdn.rawgit.com/heyitguyfixit/font/master/Josefin%20Sans/Josefin_Sans.css");

      p .example2 { 
            font-family: "Josefin Sans";
      }
      </style>
      <p class="example2">Hello world!</p>
