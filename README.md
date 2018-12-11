# ROISSC Mayo Branch - Milestone Project-1

This is a website for the Mayo branch of the Republic of Ireland Soccer Supporters Club (ROISSC). The website acts as a portal for current members or other interested parties to check the how the Irish football team are currently doing in their quest to qualify for the European Championships in 2020.

The next venue and date for the next meeting of the supporters club will always be displayed on the homepage. While a travel page will offer advice on the various locations that the Ireland team will be tarvelling to play in. The photo gallery page shows some photos taken by members on previous trips.
 
## UX

Wireframes

[Wireframe 1 - Home & Travel pages](assets/images/wireframe1.jpg)

[Wireframe 2 - Standings & Gallery pages](assets/images/wireframe2.jpg)

This website is for current and prospective members of the ROISSC - Mayo Branch. People would vist this site when looking for information on when the next meeting of the supporters club is on, this information will always be displayed on the home page.  For anyone looking for travel information on cities that Ireland will be playing in they could visit the Travel page for this information.

If a member whishes to send in photos that they have taken from a previous trip they can do so throught the form in the photo gallery page.

For anyone who wishes to join the supporters club there is a button in the navbar on each page for them to apply through a form.

## Features

Navbar - The navbar has a link to each page along with our club logo. There is also a button that opens a modal for new members to sign up thorugh a form.

Travel page - Displays the stadium capacity  and estimated ticket allocation for each away game, this is vital information for people as they might not get tickets for games with a smaller allocation. Information on flights and hotels for each city are shown here also.

Standings - The standings paage uses tables to display the fixtures, results and the current table for Ireland qualifying group. These don't contain too much information yet as the games don't start until March 2019.

Photos - The photo gallery page displays photos grouped by various trips that we have went on as a gorup. There is a form at the bottom for members to send in some new photos.


 
### Existing Features
- Join the Club - By filling out the joining form in the navbar prospective members can apply to join the club
- Upload Photos - A user can submit photos from previous trips by dilling out and uploading photos to the form on the photos page.
- Next meeting - This is the most useful information to current members, so I have placed this on the homepage so they can find out when the next metting is on and where it will be held.



### Features Left to Implement
- Dedicated members area to apply for tickets
- Previous results

## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- [Bootstrap 4](https://getbootstrap.com/)
    -  **Bootstrap 4.1.3** was used to help with the grid layout, navbar and footer. I also used a Bootstrap Javascript file for the navbar and modal.

- [Jquery](https://jquery.com)
    -  **JQuery** was used to complement Bootstrap to allow the navbar to collapse and also for the modal.

- [Font Awesome](https://fontawesome.com/)
    -  **Font Awesome 5.5.0** was used for various icons on the Navbar and also on each page heading.

- [Flag Icon](http://flag-icon-css.lip.is/)
    -  **Flag Icon** was used to improve the display of each country on most pages.

## Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

I have tested all the main features of this project as follows:

1. Join:
    1. Click on the join button to bring up the modal
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.


## Credits

### Content
- The text for section Y was copied from the [Wikipedia article Z](https://en.wikipedia.org/wiki/Z)

### Media
- The photos used in this site were obtained from ...

### Acknowledgements

- I received inspiration for this project from X
