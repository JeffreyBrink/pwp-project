# pwp-project

This project is to create a one page functioning website.

## Milestone 1

### Feedback on content

It seems that you want to find a job doing both front end development and graphic design, but it's not explicitly stated in your document. Your persona does a good job of explaining Ralph's pain point. I am left having to assume that you intend to help fill Ralph's need for a front end developer/designer.

I know it's tempting at this point to keep your target market and audience broad to catch the maximum number of job opportunities. Unfortunately this method will not get Ralph's attention. 

If you truly want to get a front end developer/designer job, focus your audience and goal upon satisfying an audience that has the same needs as Ralph. 

### Feedback on code

The .idea directory should not have made it onto github. Forgetting to create the .gitignore file before cloning your project from github on future projects can have much greater consistences.
Update: Thank you for deleting your project and recreating it in a new repository.

Your directory structure is perfect.

There are three HTML problems:
1. The <img> tag on line 56 is missing the alt attribute.
2. There are two obsolete css attributes. https://validator.w3.org/nu/?doc=https%3A%2F%2Fbootcamp-coders.cnm.edu%2F~jbrink1%2Fpwp-project%2Fpublic_html%2Fdocumentation%2Fmilestone-1.php
3. CSS should be in a separate file and pulled into the HTML document in the <head>.
 
I commend you for making the effort to add styling and an image to your page. In the future, put your css in a separate file and check your page for errors using the tool in the above link.

Overall you did a great job. Keep up the good work!

### Grade
Tier III https://bootcamp-coders.cnm.edu/projects/personal/rubric/

## Milestone 2a 

### Feedback 
HTML, CSS and directory structure is perfect. I cannot say the same about your wireframes. I had a very hard time deciphering what exactly you wanted to accomplish. The mobile and desktop views did not match and the content strategy did not provide any clarity. This is a big indicator that you might also not know what you  want to accomplish. Wireframes are considered deliverables (something that is given to a client/employer) and it is important that they match what the end product will look like. I highly recommend that you spend more time fleshing out what exactly you want to accomplish before you begin development. 

## Recommendations
For your image gallery I recommend that you use [fancybox3](https://fancyapps.com/fancybox/3/). Fancybox3 will make displaying the images you want to display in a professional clean way (you may have to change the layout of your image gallery if you use fancybox). I  recommend you do not have a thumbnail scroll since they are not very mobile friendly. What you laid out in the desktop wireframes will require a few media queries specifically with the logo graphic in the contact me section. Are you going to have the same content for the about me section, if not you will also have to write media quires for that as well  

## Grade Tier II
