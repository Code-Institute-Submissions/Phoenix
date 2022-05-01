# Phoenix Park

Phoenix park is a site to help people discover the wonders of this magical urban park found only a stones throw from Dublin City Centre, Ireland. The site will target visitors to the city as well as those resident in the city who wish to avail of this amazing amenity. Users will find information about attractions and events on the site.

![image](https://user-images.githubusercontent.com/101147217/166140608-ed367264-6835-456c-acfa-08d87dc46b4b.png)

## Features 

- __Navigation Bar__

  - Featured on firt pages, the full responsive navigation bar includes links to the About, Attractions and Sign Up page. The attractions page list Home and Sign up. The About page feature Home and Sign up links.
  - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button. 

![image](https://user-images.githubusercontent.com/101147217/166141641-dec4668f-536e-41b1-bb01-8c4ef180a4d4.png)

- __The landing page image__

  - The landing page includes a main section that has a photograph which uses opacity property and underneath that separated with two images using text overlay to allow the user to see different attractions available in the park. 
  - Animation is added on all photographs to offer an intitutive feel to the site

![Landing Page](https://user-images.githubusercontent.com/101147217/166141789-562b6342-073c-448d-b559-480d70dbc00c.png)

- __cell-images section__

  - The cell-images section will allow the user to see the attractions of the Park. 
  - The user has the option of signing up to the site to engage with activities. This should help the user to actively participate on any events as well bring others . 

![cell-images](https://user-images.githubusercontent.com/101147217/166142812-a0660520-7047-43b8-93bc-388a272492ae.png)

- __Attractions__

  - The attractions page will provide the user with supporting images to see what the Dublin Zoo look like. 
  - This section is valuable to the user as it will boost their interest to visit the Zoo. 

![Zoo](https://user-images.githubusercontent.com/101147217/166142977-e3060e44-36ed-4d40-a0ef-ccf3a7dcd080.png)

- __The Sign Up Page__

  - This page will allow the user to get signed up to Phoenix Park to explore any current events and other attractions available within the Park boundary. The user will be asked to submit their full name and email address. 

## Testing 

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your project’s features and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.


### Validator Testing 

During testing I found a number of errors:
1) Stray start tag footer
2) Element div not allowed as child of element ul
3) End tag li seen, but there were open elements
4) Unclosed element a.
5) End tag a violates nesting rules
6) Section lacks heading. Consider using h2-h6 elements to add identifying headings to all sections

- HTML
  - No errors were returned when passing through the official [W3C validator] (https://validator.w3.org/nu/?doc=https%3A%2F%2F8000-arpreacher-phoenix-586umj49vbf.ws-eu43.gitpod.io%2Findex.html) (https://8000-arpreacher-phoenix-586umj49vbf.ws-eu43.gitpod.io/attractions.html) (https://8000-arpreacher-phoenix-586umj49vbf.ws-eu43.gitpod.io/about.html)
  
  ![W3C](https://user-images.githubusercontent.com/101147217/166147946-547eef14-013f-44b8-be37-904b90497c6a.png)

- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2F8000-arpreacher-phoenix-586umj49vbf.ws-eu43.gitpod.io%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

  ![CSS](https://user-images.githubusercontent.com/101147217/166147518-a59327ee-5758-45ac-b0cb-4a31052316b8.png)

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - 
- Gitpod platform was used for coding as it allows to launch the development environment without taking any stress locally,  the code was then pushed to Github 
- I used the grid property to design the pages as it offers the flexibility to place photographs based on the column and row values, thereby it offers more control on the      elements placed in a particular layout.


## Credits 

### Content 

- The text for the About page was taken from https://phoenixpark.ie/
- Instructions on how to implement side bar navigation on the Sign Up page was taken from (https://www.youtube.com/watch?v=Fx_NpAPM-iU)
- The icons used in all pages were taken from [Font Awesome](https://fontawesome.com/)
- The code for sign up and attractions page were referred from the Love Running project
- The overlay effects were inspired from https://www.w3schools.com/howto/howto_css_image_overlay_title.asp

### Media

- The photos used on the home and sign up page are from This https://www.lonelyplanet.com/ Open Source site
- The images used for the attractions page were taken from this https://www.dublinzoo.ie/news/ctas/image/  https://www.lonelyplanet.com/ open source site