# W1HW-Refactor Horiseon Site
21st December 2021

**Assignment:** 

An increasingly important consideration for businesses, web **accessibility** ensures that people with disabilities can access a website using assistive technologies like video captions, screen readers, and braille keyboards. Accessibility is good for business for one thing, accessible sites rank higher in search engines like Google. It also helps companies avoid litigation, which might arise if people with disabilities can't access a website.

Check that all links are functioning correctly. You can also increase the efficiency of the CSS by consolidating the selectors and properties, organizing them to follow the semantic structure of the HTML elements, and including comments before each element or section of the page._
_________________________________________________________________________________________________________________________________________________________________________________

Reviewing and Refactoring someone else's code is a good way to test what you have learned in the sessions and also provides an opportunity to learn by looking at how another developer's code or to see how they approached solutions to meet the stipulated requirements of the web site.  

The refactored code has addressed a number of accessibility issues with the site.  By inspecting the web page and paying attention to the accessibility scores was a key factor that prompted reconsideration of the elements on the page.  

The code has been enhanced as follows:

* Included a title for the website <title>Horiseon</title>

* To improve the overall accessibility score of the various elements added:
  - Added 'alt' element to images to assist users using non visual browsers
  - Added 'aria-labelledby to links 
  - Adjusted the colour of the benefits section:
  - Replaced DIV with HTML semantic tags
  - Headers are sequential
  - Consolidated CSS using semantic tags 
  - Renamed Repository
  
    From: ![image](https://user-images.githubusercontent.com/94102473/144243917-0a4eddca-4dc8-4f68-9aee-df64ac59409d.png)

      To: ![image](https://user-images.githubusercontent.com/94102473/144243990-43aacbcc-1bc6-46d8-bd59-c687d82adae9.png)

* Fixed non working link for the Search Engine Optimisation by adding the ID class

* Used Header and Footer HTML Semantic instead of Header and footer class 

* Added the Nav HTML semantic 
* Replaced DIV with HTML semantic tags (article and aside)
* Headers are sequential
* Consolidated CSS using the newly created semantic tags 
* Renamed the GIT Repository
