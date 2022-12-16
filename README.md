# Refactoring Mockup Accessibility
![project landing page](/assets/images/mockup-page-screenshot.png)

## Description
This project was created to practice refactoring code to ensure that it meets accessibility standards. It's important to ensure that websites are accessible so that everyone, including people with disabilities, are able to access the information. 

To meet accessibility standards, I ensured that code meets the following standards:

### Use of semantic elements
![original html code](/assets/images/semantic-original.png)

The original text here did not follow accessibility standards because the non-sematic tags make it difficult for a screen reader to understand what the purpose and importance of each div element is. 

![modified html code](/assets/images/semantic-modified.png)

Converting the non-semantic elements to semantic elements makes this webpage much easier for a screen reader to read. The header element very clearly states that this section of code will reside in the header section of the webpage. The nav element indicates that the item included in this section are navigational links.

### Ensuring that elements follow a logical structure
![original html code](/assets/images/logical-structure-original.png)

In this original code, it's difficult for a screen reader to understand why the div elements are nested within each other and how each div element relates to one another. 

![modified html code](/assets/images/logical-structure-modified.png)

The aside element clearly indicates that the code contained within it is a part of a sidebar. Additionally, the footer elements shows that this code is located at the bottom of the page. 

### Applying alt attributes to images
```
 <img src="./assets/images/search-engine-optimization.jpg" class="float-left" />
 ```

```
 <img src="./assets/images/search-engine-optimization.jpg" class="float-left" alt="SEO diagram on a notebook"/>
```

### Crafting a concise, descriptive title




## Resources
|Resource Type| Link |
|:------|:-----|
|Accessibility| https://blog.hubspot.com/website/html-accessibility|
|Semantic Elements|https://www.w3schools.com/html/html5_semantic_elements.asp|
|Test|https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax|

## Credits
Link to deployed project: https://megellman.github.io/refactoring-mockup-accessibility/

## License
MIT License

Copyright (c) [2022] [MeganEllman]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
