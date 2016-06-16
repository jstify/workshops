twemoji sandbox
---
 
Tested out twemoji, Twitter's npm package for converting emoji strings
into Twitter emoji.
 
The `parse()` method takes a string and converts it to HTML, with `<img>`
tags for all the emoji images.

  - Tried with sigle twemoji : returns img tags with url
  - Tried with simple text : returns simple text if it is not match with any emoji
  - Tried with multiple twemoji : returns multiple img tags
  - Tried with combination of emoji and simple text : returns the html with comibination of img for selected emoji and simple text