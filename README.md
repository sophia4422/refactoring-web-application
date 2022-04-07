## refactoring-web-application

For this client, I was asked to refactor the html and css for clients 'Horiseons' web application.

## What is refactoring?

Software can fail when the code becomes too complex and cluttered. Refactoring can improve the code design, this makes it easier to understand, easier to modify and easier to spot bugs.

Refactoring is not only useful for yourself but also for others who may use the code. Refactored code also helps to make coding quicker, as you can spend more time adding features and improvements, rather than sifting through code trying to understand what as been written and where errors may be.

## My refactoring 'To do List'

After reading the client's brief and looking through the provided code, I outlined a list of things to refactor with the main aim of making the webpage more accessible. Below is my 'To do List' and an explanation of what I did to achieve these tasks.

- **Ensure all images have alt text captions.**
  Alt text is essential to make the webpage accessible for visually impaired users, as this means images can be read by screen-readers. Alt text is hidden and the only time it will be visible is if an image fails to load on a users screen. Alt text is useful in improving a web page's SEO.

  Good alt text should be descriptive and specific. Describe the image with clear, useful keywords - but not too many keywords as to incur a penalty from Google. The captions should be less than 125 characters, straight to the point and lack spelling errors.

- **Use semantic elements.**
  Semantic elements help improve accessibility of a webpage. Replacing a lot of code wrapped up in < divs > and replacing them with semantic elements not only makes the code more readable to a developer but also makes the webpage more accessible for those using screen-readers.

- **Include comments.**
  Including comments in the html helps to identify what areas of the webpage the html refers to. Comments in the css makes it clear which parts of the website are being manipulated by the css.

- **Logical order to headings (h1 to h6).**
  Previously, the webpage had a h1 header and the remaining headers were set to h3. Changing the h3 headers to h2 helps the webpage to load more logically and boosts SEO.

- **Document title (head element) is descriptive.**
  Writing a compelling title and description is an excellent way to improve SEO. The title is what shows at the top of the webpage and the description is shown in internet search results. I have tried to keep the description concise and containing the main keywords that describe Horiseons.

- **The 'search engine optimization' navigation link is broken.**
  This was missing a simple id tag (id = search-engine-optimization). When 'Search Engine Optimization' is clicked in the navigation bar, the user is automatically taken to its corresponding section on the webpage.

- **There are lots of duplicate class names in css. Replace this in the html with generic names.**
  I have replaced duplicate classes with one concise class. This makes things more simple in the html and css by preventing errors and making future changes easier, as you will only need to change one class rather than multiple ones.
  
 
## Before and After Screenshots

**Changing < divs > to Semantic Elements**
  
  This screenshot shows a small snipped of just a few of the many < div > classes that were in the code before any edits. This can be called a 'div soup'. 
  ![divsoup](https://user-images.githubusercontent.com/101473841/162231706-49f28be7-cd5e-41c5-ba22-6d08985b9693.png)
  
  This screenshot shows the html after I have removed the multiple < div > classes and replaced with semantic elements, such as < article > and < aside >.
  
  ![divsoupafter](https://user-images.githubusercontent.com/101473841/162232972-b0ba4721-ea74-4f4a-9d88-b51810293980.png)
  
 **Combining multiple css classes into one with a generic name**
 
 This screenshot shows the multiple class selectors in the html. A lot of these classes had the same styling and formatting elements. 
 ![multipleclasses](https://user-images.githubusercontent.com/101473841/162234507-5bbcc92d-145b-4b48-9546-5d1082293b75.png)
