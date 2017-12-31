Install Option 1
---------------------------------------------------------------------------------------------------------------------------------
To install the font, copy the `@font-face` rule and paste it into a CSS file or in the HTML document (inbetween a set of `style`
      tags). Example on how to apply it are below it.

    <style>
    @font-face {
          font-family: "Moon Flower";
          src: url(https://cdn.rawgit.com/heyitguyfixit/font/506b65d9/Moon%20Flower/Moon_Flower.eot);
          src: url(https://cdn.rawgit.com/heyitguyfixit/font/506b65d9/Moon%20Flower/Moon_Flower.ttf) format("truetype"),
                url(https://cdn.rawgit.com/heyitguyfixit/font/506b65d9/Moon%20Flower/Moon_Flower.woff) format("woff"),
                url(https://cdn.rawgit.com/heyitguyfixit/font/506b65d9/Moon%20Flower/Moon_Flower.svg) format("svg");
          unicode-range: U+?????;
          font-style: normal;
          font-weight: 400;
    }

    p .example1 { 
          font-family: "Moon Flower";
    }
    </style>
    <p class="example1">Hello world!</p>

---------------------------------------------------------------------------------------------------------------------------------
Install Option 2
---------------------------------------------------------------------------------------------------------------------------------
To install the font, copy the `@import` rule and paste it into a CSS file or in the HTML document (inbetween a set of `style`
      tags). Example on how to apply it are below it.

    <style>
    @import url("https://cdn.rawgit.com/heyitguyfixit/font/master/Moon%20Flower/Moon_Flower.css")

    p .example2 { 
          font-family: "Moon Flower";
    }
    </style>
    <p class="example2">Hello world!</p>
