# Bass Militia Website

![](https://github.com/samlaubscher/bass-militia-website/blob/master/assets/images/landing-page/Landing-page-preview-screenshot.png?raw=true)

A website built for the Bass Militia Collective, created to serve as a promotional showcase and contact directive for their music events team, as well as their freshly launched record label.

## UX [Use this section to provide insight into your UX process, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.]

Bass Militia is a Bristol based collective that focuses on creating and promoting electronic dance music - namely the harder and darker side of mutant bass, drum and bass, and 4x4 bass oriented styles. They have been heavily involved in the local events industry for the past year in Bristol, having organised and successfully ran some of the best nights for this style of music in years.

The owner of the brand approached me and asked if I could build them a simple but effective website to serve some of their requirements and streamline their marketing. The initial request was to have a page that easily displayed contact information and all posters of the previous events organised by the brand, allowing them to easily present their back catalogue of work as well as a means of contact for anybody interested. I suggested they should also include event imagery to deliver an instant insight on the general attendance and successful appearance of these past events.

I was told that in the past two months, the further expansion of the brand has led to the formation of a record label with the aim to push the music that has come to be expected when attending the events. When speaking with the client, we spoke about the fact they only planned to promote and display their full music catalogue on Soundcloud - a free music streaming website - and whilst this site does serve its purpose extremely well, it is not the best option for those wanting to uniquely display announcements and release information. It was also discussed how Facebook limits promotion of posts, and that when customers look on a businesses Facebook page, they don't gain a very good grasp of the company whereas a website allows you to immediately be faced with the information in a unique style.


So the basis of this project was to provide the client with a platform to document and showcase their content. I explained that I could create a front end site that would serve the following purposes for different user types:

- As somebody that has heard of Bass Militia, I want to look at the previous events organised by the brand so that I can see if its something I would be interested in.

- As a promoter looking to potentially collaborate, I want to look at what the brand has done in the past and then have the ability to contact them.

- As an existing fan of Bass Militia or as somebody that has previously attended one of their events, I want to be able to look on their website and see any upcoming events, this way I can see the dates of them and see what acts will be playing.

- As a DJ, I want to look up the music catalogue offered by the record label so that I can efficiently see what has been released and what is forthcoming.

- As a producer, I want to be able to see what has been previously released and have the ability to contact them, this way I can see if my own music will fit the style and if it would be something they are interested in.

I originally presented the wireframe found here _________ as a rough idea, and the client was happy with my layout and general colour scheme. I did advise the layout may vary in places as I find what works and fits. 


## Features

As I was developing the website, the brand continued to create more media through their events and releases - meaning there became sufficient content to dedicate individual pages to each section of the website.
 
- Landing page
- Events page
- Record Label page
- Merchandise page
- Contact page

### Existing Features
- Navbar - A Navbar is used across the site allowing users to easily navigate through the website regardless of the page they are on. The use of a collapsable dropdown menu is used on mobile view to save space.
- Social Media Links - The navbar also includes social media links across the website, these are relocated to the footer on mobile devices.
- The [Landing page](https://samlaubscher.github.io/bass-militia-website/index.html) - allows users to easily and clearly navigate to either a specific page of the website they desire via the navbar, or to one of the external website links via the footer icons.
- Event images - The top of the [Events page](https://samlaubscher.github.io/bass-militia-website/events.html) allows users to see photos taken taken at the events, achieved with the use of a photo carousel.
- Catalogue of pase events - The [Events page](https://samlaubscher.github.io/bass-militia-website/events.html) also allows users to clearly see all of the previous events hosted, achieved by displaying each of the posters in a chronologically ordered grid layout.
- [Label page](https://samlaubscher.github.io/bass-militia-website/record_label.html) announcements - Users can clearly see any public news and announcements relating to the label at the top of the Record Label page via the 'Announcements' section.
- Back catalogue of releases - On the [Record Label page](https://samlaubscher.github.io/bass-militia-website/record_label.html) Users can easily view the chronological order of releases and premieres on the label by viewing the 'Digital Album Releases' and 'Premieres' sections on the record label page.
- Direct file uploads / submissions - Artists are able to upload their demo submissions for the record label directly through the website by visiting the [Record Label page](https://samlaubscher.github.io/bass-militia-website/record_label.html) and filling in the contact form in the 'Submissions' section at the bottom.
- View and purchase merchandise - Via the [Merchandise page](https://samlaubscher.github.io/bass-militia-website/merchandise.html) Users are able to view the available merchandise and easily purchase using the linked PayPal 'Buy Now' buttons which display sizes and are actively linked to the correct corresponding payment account.
- Crew members [contact](https://samlaubscher.github.io/bass-militia-website/contact.html) directory - Users are able to easily view members involved in the team as well as their contact details. Users can click on these details to compose direct emails to the respectful recipients.
- Submission and enquiry sections - Users are able to see the correct avenue of contact in regards to track submissions, event enquiries or general enquiries etc by viewing the [Contact page](https://samlaubscher.github.io/bass-militia-website/contact.html) and locating the section relating to their needs.
- Direct contact forms - Via the [Contact page](https://samlaubscher.github.io/bass-militia-website/contact.html) any type of user is able to directly contact the brand via the website itself by filling in the contact form and allocating the correct reason for the enquiry.

### Features Left to Implement
- I would like to include the back end processes to allow the contact form submissions to be received by the server and for file submissions to be uploaded and downloaded.
- I would like to embed social media widgets at some point to allow for Facebook and Soundcloud updates to be delivered live to the website for example.


## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- [JQuery](https://jquery.com)
    - The project uses **JQuery** to simplify DOM manipulation.


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