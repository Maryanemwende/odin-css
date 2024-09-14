This folder contains exercises exploring the different methods of adding CSS to html files. These methods include External CSS, Internal CSS and Inline method of styling. 
<br>
***External Method***
Involves creating a separate file for the CSS and linking it inside of an HTML’s opening and closing <head> tags with a void <link> element. Add a void <link> element inside of the opening and closing <head> tags of the HTML file. The href attribute is the location of the CSS file, either an absolute URL or, a URL relative to the location of the HTML file. The rel attribute is required, and it specifies the relationship between the HTML file and the linked file.
<hr>
***Internal Method***
Internal CSS (or embedded CSS) involves adding the CSS within the HTML file itself instead of creating a completely separate file. With the internal method, you place all the rules inside of a pair of opening and closing <style></style> tags, which are then placed inside of the opening and closing <head> tags of your HTML file. Since the styles are being placed directly inside of the <head> tags, you no longer need a <link> element that the external method requires.
<hr>
***Inline Method***
Makes it possible to add styles directly to HTML elements. You have the style= attribute, with its value within the pair of quotation marks being the declarations. 