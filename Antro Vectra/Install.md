Install Option 1
---------------------------------------------------------------------------------------------------------------------------------
To install the font, copy the `@font-face` rule and paste it into a CSS file or in the HTML document (inbetween a set of `style`
      tags). Example on how to apply it are below it.

    <style>
    @font-face {
          font-family: "Antro Vectra";
          src: url(https://cdn.rawgit.com/heyitguyfixit/font/c7565819/Antro%20Vectra/Antro_Vectra.otf) format("opentype"); /* .otf */
          unicode-range: U+?????;
          font-style: normal;
          font-weight: 400;
    }

    p .example1 { 
          font-family: "Antro Vectra";
    }
    </style>

<p class="example1">Hello world!</p>


Install Option 2
---------------------------------------------------------------------------------------------------------------------------------
To install the font, copy the @import rule and paste it into a CSS file or in the HTML document (inbetween a set of style
tags). Example on how to apply it are below it.

      <style>
      @import url("https://cdn.rawgit.com/heyitguyfixit/font/master/Antro%20Vectra/Antro_Vectra.css")

      p .example2 { 
            font-family: "Antro Vectra";
      }
      </style>
      <p class="example2">Hello world!</p>
