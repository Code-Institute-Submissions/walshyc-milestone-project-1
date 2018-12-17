# ROISSC Mayo Branch - Milestone Project-1

This is a website for the Mayo branch of the Republic of Ireland Soccer Supporters Club (ROISSC). The website acts as a portal for current members or other interested parties to check the how the Irish football team are currently doing in their quest to qualify for the European Championships in 2020.

The next venue and date for the next meeting of the supporter’s club will always be displayed on the homepage. While a travel page will offer advice on the various locations that the Ireland team will be travelling to play in. The photo gallery page shows some photos taken by members on previous trips.
 
## UX

#### Wireframes

[Wireframe 1 - Home & Travel pages](assets/images/wireframe1.jpg)

[Wireframe 2 - Standings & Gallery pages](assets/images/wireframe2.jpg)

#### About The Site

This website is for current and prospective members of the ROISSC - Mayo Branch. People would visit this site when looking for information on when the next meeting of the supporter’s club is on, this information will always be displayed on the home page.  For anyone looking for travel information on cities that Ireland will be playing in they could visit the Travel page for this information.

If a member wishes to send in photos that they have taken from a previous trip they can do so through the form in the photo gallery page.

For anyone who wishes to join the supporters club there is a button in the navbar on each page for them to apply through a form.

## Features

Navbar - The navbar has a link to each page along with our club logo. There is also a button that opens a modal for new members to sign up through a form.

Travel page - Displays the stadium capacity and estimated ticket allocation for each away game, this is vital information for people as they might not get tickets for games with a smaller allocation. Information on flights and hotels for each city are shown here also.

Standings - The standings page uses tables to display the fixtures, results and the current table for Ireland qualifying group. These don't contain too much information yet as the games don't start until March 2019.

Photos - The photo gallery page displays photos grouped by various trips that we have went on as a group. There is a form at the bottom for members to send in some new photos.


 
### Existing Features
- Join the Club - By filling out the joining form in the navbar prospective members can apply to join the club
- Upload Photos - A user can submit photos from previous trips by filling out and uploading photos to the form on the photos page.
- Next meeting - This is the most useful information to current members, so I have placed this on the homepage so they can find out when the next meeting is on and where it will be held.



### Features Left to Implement
- Dedicated members area to apply for tickets for away games.
- A dedicated history page that will display the previous results of the Irish football team going back over the years.

## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- [Bootstrap 4](https://getbootstrap.com/)
    -  **Bootstrap 4.1.3** was used to help with the grid layout, navbar and footer. I also used a Bootstrap JavaScript file for the navbar and modal.

- [jQuery](https://jquery.com)
    -  **jQuery** was used to complement Bootstrap to allow the navbar to collapse and also for the modal.

- [Font Awesome](https://fontawesome.com/)
    -  **Font Awesome 5.5.0** was used for various icons on the Navbar and also on each page heading.

- [Flag Icon](http://flag-icon-css.lip.is/)
    -  **Flag Icon** was used to improve the display of each country on most pages.

## Testing

#### Validation

I ran each HTML file through a HTMl validator on [HTML Validator](https://validator.w3.org). This showed up some issues with stray i tags around some of the Social Media icons in the footer. The validator also showed up the fact that I had px after the height and width in the attribute of some of my images that I hadn't realised wasn't required.

I used [CSS Validator](https://jigsaw.w3.org/css-validator) to validate my CSS file style.css, this proved to be all correct.

#### Usability

1. Join:
    1. Click on the join button to bring up the modal.
    2. Tried to submit the form with each field empty separately and it wouldn't allow me to.
    3. Submitted the form with all the form fields correct and I was redirected to the thanks.html page as expected.

2. Upload Photos:
    1. Filled out the two text fields in the form
    2. Tested adding multiple files to be uploaded
    3. Submitted the form with all the form fields correct and I was redirected to the thanks.html page as expected.

3. All the links point to where they should do

4. All the page titles are correct.


I have used the Google Chrome Dev Tools to ensure that each page appears correctly at the most common screen sizes from large desktop to tablet to smartphone.

I loaded each page on the following browsers:
- Google Chrome (Windows & Android)
- Firefox
- Safari (iOS)

All pages worked as expected on the above browsers at the Large, Medium, Small and Extra Small viewpoints where applicable.

#### Speed Test

I used [GTMetrix](https://gtmetrix.com) to test the load speed on each page. After initially testing each page, it was clear that the photos in the gallery page were too large and slowing down the load speed. I resized them and it greatly improved the load speed of this page.

The homepage had a load speed of 1.1 seconds and a total page size of 1.55mb. After reducing the images on the gallery page, I got the page size down for roughly 4mb to 1.6mb, which I am happy with.


## Deployment

I have hosted this project on GitHub pages and regularly committed to the GitHib repository for this project.

I created the Github repository called milestone-project-1 in my [GitHub Page](https://github.com/walshyc).

The link to the homepage of the project is [here](https://walshyc.github.io/milestone-project-1/index.html).


### Content
- I used content from Wikipedia to get information on each stadium such as capacity and year opened. 
- I researched the travel information myself using airline & hotel websites.

### Media
The photos used on the gallery page were all sourced from members of the supporter’s club, these were used with their permission. The stadium images were retrieved from [Stadium Guide](http://www.stadiumguide.com/).

