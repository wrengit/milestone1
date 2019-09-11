# ruhstik. - A wedding planning service
Stream One Project: User-Centric Frontend Development - Code Institute

A website to act as an initial information portal for prospective clients interested in a wedding planning service. Designed to act as a 'hook' to showcase the ethos of the company, whilst not overloading the user with too much information.

# Demo
A link to the project hosted on GitHub Pages can be found [here](https://wrengit.github.io/milestone1/)

## UX
The site is designed to focus on couples looking for a wedding planning service that stands out from the traditional planning services. The ethos of the business is 'customer first', working closely with clients to deliver an event to remember. The service is pitched at young, design conscious couples that will likely be viewing the site initially on a mobile device.

The colour palate was kept subtle, with minimal 'clutter' and clear, readable text.

The user is guided through the single scrolling page, to arrive at a contact form at the bottom. This aligns with the strategy of the site in active as an initial hook, and allows the user to submit contact information with out feeling like they have to commit. The business can follow up with a personalised email to sell the service.

Links to the business' social media pages (demo links forward to the main social media home page) are prominently displayed at the top of the page (desktop view) and in the drop down navbar (mobile view). This allows users to view more specific information in a suitable format (Instagram for images of previous events, Facebook to see 'blog' or text posts etc.), whilst maintaining their attention.

Users can see what the business is about, read testimonials from previous clients, and read about example events that the business has previously organised. This gives a good feel for what they can expect from working with the business. Social media links, a contact form, a physical location and phone number, and a contact email cover all methods of communicating should the user wish to proceed.

Links to wireframes

## Features
### Existing Features
The target audience will likely be initially viewing the site on a mobile device. The parallax images found on the desktop site will not render on a mobile browser, so the images are changed to sticky. This gives the site an improve look over fixed images on a mobile browser. The parallax images are left to the desktop site only.

### Features Left to Implement
Suggestions on the mobile site to visit the desktop site, with more information available better suited for the larger screen size. An in-site gallery, based on the portfolio modal pop-ups would keep the site neat whilst providing a better user experience.

Currently the contact form requires that suitable user data is entered into the fields before allowing a 'submit' click. This should be followed by a modal giving feedback that the form has been correctly filled, sent, and that the business will be in contact soon. Presently, applying a modal bypasses the form validation. Research suggests that this is achievable with JavaScript.

## Technologies Used
* HTML
* CSS
* Bootstrap
* JavaScript
* favicon.io
* FontAwesome
* Google Fonts
* PopperJS
* Jquery

## Services Used
* Tinypng - image compression
* Unsplash - imaage repository
* hover.css - css hover styling


## Testing
The site was tested across multiple browsers (Chrome, Firefox, Brave, Edge), and on multiple virtual screen sizes via Chrome dev tools. The hosted site was tested physically with a Huawei P20 pro. Compatibility was good across all screen sizes.
Testing on ipad and ipad pro (dev tools) in horizontal mode showed minor layout and sizing issues that could not be remedied without affecting desktop view. It is assumed that the majority of users will be viewing on either a vertical mobile or tablet view, or desktop. The site has been optimised for these arrangements.

During testing it was found that mobile browsers cannot render ```background-attachment: fixed```. Initially this was changed to ```background-attachment: scroll``` for mobile view, but this impacted the visual appeal of the mobile experience too much. The images were changed to ```position: sticky``` on mobile only, giving a more pleasing mobile experience, leaving the parallax scrolling effect on desktop.

## Cloning & Deployment

### Cloning
The site can be cloned to a local repository by the following steps (GitHub guide link [here](https://help.github.com/en/articles/cloning-a-repository):

* Under the repository name, click Clone or download.

* In the Clone with HTTPs section, click the clipboard icon to copy the clone URL for the repository.

* Open the terminal on your local machine

* Change the current working directory to the location where you want the cloned directory to be made.

* Type ```git clone```, and then paste the URL you previously copied.

```$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY```

* Press Enter. Your local clone will be created.

```$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
> Cloning into `Spoon-Knife`...
> remote: Counting objects: 10, done.
> remote: Compressing objects: 100% (8/8), done.
> remove: Total 10 (delta 1), reused 10 (delta 1)
> Unpacking objects: 100% (10/10), done.```

### Deployment
The site is deployed on GitHub pages, directly from the master branch. The site will update with all further commits on the master branch. A cloned site can be deployed on GitHub via the following steps:

* Go to the setting menu on the GitHub repository

* Scroll down to find the 'GitHub Pages' subtitle and change the source to 'master branch'

* A link will appear beneath the 'GitHub Pages' subtitle with your hosted site.

## Credits

### Content
All content was written by me. Client names, testimonials and example portfolio events are all fictional, and not based on any real world examples or people.

### Media
All images are from [Unsplash](http://unsplash.com), a royalty free, free to use image repository. A sepia filter was added to the polaroid images to enhance the appearance. Photographer credits for the images are below.

* Photo by [sept commercial](https://unsplash.com/@septdoigt)
* Photo by [Marisa Morton](https://unsplash.com/@poemacollective)
* Photo by [Eliza Szablinska](https://unsplash.com/@liz_szablinska)
* Photo by [Stanley Dai](https://unsplash.com/@stanleydai)
* Photo by [NeONBRAND](https://unsplash.com/@neonbrand)
* Photo by [Hannah Cook](https://unsplash.com/@hanleigh)
* Photo by [Carly Rae Hobbins](https://unsplash.com/@carlyrae)
* Photo by [Ben Rosett](https://unsplash.com/@spiritvisionstudios)
* Photo by [Banter Snaps](https://unsplash.com/@bantersnaps)

### Acknowledgements
The JavaScript to collapse the mobile navbar upon a link being clicked was provided by Eventyret_mentor from the Code Institute Slack channel.

Parallax background image was learnt from https://www.w3schools.com/howto/howto_css_parallax.asp
