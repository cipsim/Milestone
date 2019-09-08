# Acid Reign's website

Stream One Project: User Centric Frontend Development - Code Institute

This is the website of the british metal band Acid Reign. 

The website gives a general overview of the band sponsoring the new album and single in the homepage, as well as the possibility to access directly to their music on spotify in the music section. 

For whom might be interested in the latest updates on the band, there is a "News section". 

It is possible to see what are the planned gigs and buy tickets trough the "tour" section. 

Whoever might be interested in buying tshirts and albums will be able to do so in the "merch" section.


## Demo
A live demo can be found [here](https://cipsim.github.io/Milestone/).
 
## UX
 
My goal in the design was to promote the band and its music on the site, while basing the design on the upcoming album's illustrations.

- Being new to the band, I want to have a general overview, so that I learn more and listen to their music.
- As a fan of the band, I want to pre-order the new album, so that I can listen to it as soon as possible and I want to know where the band will be touring and buy tickets
- 
- ## Technologies
- [HTML](https://whatwg.org)
    - The project uses **HTML** to insert text links and images.
 - [CSS](https://www.w3.org/Style/CSS/)
    - The project uses **CSS** to style the page content.
- [BOOTSTRAP](https://getbootstrap.com)
    - The project uses **Bootstrap** to simplify styling and responsiveness.
- [FONT AWESOME](https://fontawesome.com)
    - The project uses **Font Awesome** to easily insert icons.

## Features
This site uses filters in order to make the background of the "tour" section and the covers of the albums in the "music" section black and white. It also uses the "fade" effect from the Hover.css library.

### Features Left to Implement
In the future, I would like to add a biography section, telling the story of the band while adding pictures and videos.


## Testing

Every page of website has been tested manually multiple times in order to ensure responsiveness, functionality and compability.

In the index section the first article briefly explains who are Acid Reign showing a picture of the band. Immediatly after there is a chance to pre-order the new album with a direct link to the label website and a link to the spotify page of the last single.

The music section shows the albums, their names, and their year of release. Hovering on the albums, the covers will go from black and white to color. Clicking on a cover, will directly bring the user to the spotify page of the album.

In the news section it is possible to see the announcement of the new tour and being redirected to the "tour" section, or listen to the latest metal podcast.

In the tour section the user will see a list of tourdates and will be able to be redirected to the ticket-selling websites for every date.

The merch section will allow the user to buy tshirts, albums and bundles. At the moment the images are not linked to any external website.

*All the links will open in a new tab except for the button in the news section that will redirect to the tour section of the website*

## Deployment

The website has been deployed using AWS Cloud 9 and it has been regularilly pushed on GitHub

To run locally, you can clone this repository directly into the editor of your choice by pasting `git clone https://github.com/cipsim/Milestone.git` into your terminal. To cut ties with this GitHub repository, type `git remote rm origin` into the terminal.


## Credits

### Content
- All the texts have been copied from the facebook webpage of the band [Acid Reign Facebook](https://www.facebook.com/acid.reign.thrash)

### Media
- The photos used in this site were obtained from the band's social pages.

### Acknowledgements

- I received inspiration for this project from Alice Cooper's website [Alice Cooper](https://alicecooper.com) in making the tour and the music section (please see comments in the code)
- To implement filters on the images used in the website I retrieved the instructions from [Stack Overflow](https://stackoverflow.com/questions/16340159/greyscale-background-css-images) and [CodeBlockQ](http://www.codeblocq.com/2016/08/Turn-an-image-to-Black-and-White-on-hover-with-CSS/)
