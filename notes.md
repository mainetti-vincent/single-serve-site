## November 16, 2017 Notes
### General Info 
* general practice is to mix different typfaces. one serif and one sans-serif often work well together.
* Web-safe fonts are often better used for body copy text while custon fonts are more commonly used for headings and decorative text. 
* It would be good practice to use 2-3(max) weight of a non websafe font on a single page. 


### On Web Fonts 
* if possible pull fonts form Google Fonts, but download the font rather than relying on google to support the font. This removes the need for a third party
* Choose a font that has more than one weight
* Keep the chosen fonts within a "raw" folder inside the project folder (the ttf & woff)
* Be Aware of the **lisences** that are included in these fonts
* WOF (web open font)convert all fonts to this type for use on the web. fontquirrel.com font generator
* Create a "fonts" folder within the project folder and place the woff files inside 
* Fontsquirrel should create a css file that can be opened and copy/pasted into the prject css. **Don't Forget** re-route the the folder paths src: url('**../fonts/muli/** muli-extralight-webfont.woff2') 
* Preload fonts should **not** go beyond 2 fonts wihtout good reason, and is best used on the headings

### ont Display Proporties
* font-disply: swap (prevents a timeout on font load
* font-display: fallback (displays while browser loads correct font, best used in body copy) 

### Rsources
* 0. google fonts
https://fonts.google.com

* 0. font squirrel
https://www.fontsquirrel.com

* 1. web font generator
https://www.fontsquirrel.com/tools/webfont-generator

* 2. Font weight values
http:/cssreference.io/typography/#font-weight

* 3. Font Display Properties
https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face/font-display

* 4. Preload
https://www.zachleat.com/web/preload/
https://www.zachleat.com/web/preload/

* 5. Web font comparison tool 
http:/webfont-test.com
