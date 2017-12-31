1. Create a file called `<font name>/Install.md`. Copy the below text to use a template. Replace `<font name>` with the name of the font.
<pre>
Install Option 1
---------------------------------------------------------------------------------------------------------------------------------
To install the font, copy the `@font-face` rule and paste it into a CSS file or in the HTML document (inbetween a set of `style`
      tags). Example on how to apply it are below it.

    <style>
    @font-face {
          font-family: "<font name>";
          src: url(<font url>); /* .eot */
          src: url(<font url>) format("truetype"), /* .ttf */
                url(<font url>) format("woff"), /* .woff */
                url(<font url>) format("svg"); /* .svg */
          unicode-range: U+?????;
          font-style: normal;
          font-weight: 400;
    }

    p .example1 { 
          font-family: "<font name>";
    }
    </style>
    <p class="example1">Hello world!</p>
Install Option 2
-----------------------------------------------------------_---------------------------------------------------------------------
To install the font, copy the `@import` rule and paste it into a CSS file or in the HTML document (inbetween a set of `style`
      tags). Example on how to apply it are below it.

    <style>
    @import url("<css url>")

    p .example2 { 
          font-family: "<font name>";
    }
    </style>
    <p class="example2">Hello world!</p>
</pre>
2. Upload the font files to the new folder.
3. Go to the following link and get the raw link to each of the font files:
  http://rawgit.com/

4. Replace the `<font url>` with the URL's mentioned in step 3 in the `Install.md` file.
5. Create a CSS file named `<font name>.css` in the font's folder. Copy the CSS rule `@font-family` into it. Then create a link to it with Raw Git.
6. Replace the `<css url>` with the CSS file's raw URL from step 5.
