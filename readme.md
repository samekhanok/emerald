## Facebook introduces emoticons instead of "dislikes"

Facebook will finally fulfill the promise and expand the functions of the like button. Now it will be added as many as seven emoticons expressing a variety of emotions from the published post.

 Earlier, Mark Zuckerberg reported on the development of a button expressing the “dislike” of the post. Users are waiting for its appearance almost from the day the social network was founded. However, instead of it, “reactions” will appear (Reactions) - that is the name of the developed function. The news highlighted the resource Engadget.com, citing employees of the company as a source of information.

The usual "like" with it does not go anywhere. By clicking on the button, network users will be able to mark their favorite entry as before. Or choose a smiley to express your reaction to the content of the tape.

# [FACEBOOK EMOJIS](https://wowemojis.com/facebook-emojis//) 

Engadget also posted a screenshot of emoticons. The images convey the following emotions: love, laughter, smile, surprise, sadness and anger. Residents of Spain and Ireland are luckier than others - they will be able to try out the "reaction" today - October 9th. The function will spread to other regions a bit later. There will also be involved the audience of the service for business communications Pages. Advertising services, however, will continue to consider the function as a "like".

Opportunities to put Dislike to the post social network users have been waiting for more than one year. The creator of Facebook in this confirmed that the company is working on a similar function and its appearance should be expected in the near future.

Mark Zuckerberg also noted in his speech in December last year that the currently available functionality does not allow responding adequately to the content of the recording. It looks unnatural when you mark a post you like, and it talks about a social or cultural problem, loss and loss. The audience can express their emotions and show a real reaction thanks to a new feature. The developers have tried to display the full range of emotions in Reactions.

From the statement of Zuckerberg, then it was concluded about the introduction of the long-awaited users "dislayka". However, the creator of the network has more than once stated that he will not introduce a button that allows him to directly “dislike” posts. He also identified several reasons why he wants to do this.

First of all, it would make Facebook similar to a number of online forums, the principle of which is based on the UGC model of online media. Putting “Like / Dislike” marks in such a system would reduce or increase the rating.

The second reason Zuckerberg called the reluctance to distribute the negative. It is more than enough in social networks, and more importantly - to prevent its appearance, and not to create tools for expressing discontent.

And the third reason is that it is not profitable for advertising. Not many companies would agree that posts with their products are subject to active “minus” by users.

Even after all this, Facebook users have not lost hope of the appearance of the “Dislink” button. The community of fans of this button currently has about 3.2 million participants. When there was an opportunity to sign the petition, it was supported by almost 1, 5 million people.

Resource Fast Company is a different opinion from the creator of Facebook. The button would allow to mark negative events, expressing solidarity with this mark. And companies that would serve as a criterion for evaluating their advertising campaign. And most importantly - with its help it would be possible to mark truly annoying posts.


### Support or Contact

Having trouble with Pages?[contact support]# [WOW EMOJIS](https://wowemojis.com//) and we’ll help you sort it out.


![Emerald](/img/Emerald01.png "Emerald")

## Setup & usage
Emerald may be installed by simply downloading the .zip folder from the [repository on Github](https://github.com/KingFelix/emerald/archive/master.zip).

After extracting the content from the folder into the selected directory, you can type ``jekyll serve`` from the terminal, than open your browser to ``0.0.0.0:4000/emerald/`` and you will find it there.

Additionally it is possible to fork the repository and use Github Pages as hosting. By following this way it will be enough to change the ``baseurl`` value into the ``_config.yml`` file, with the directory name of your project (for example /blog) or simply with a "/" (slash) if you want install Emerald in the root.

### Options
Starting from the 1.1.0 version, you can customize Emerald thanks to a few options. Now it is possible to set a custom header tag by setting the related option in the ``_config.yml`` file to "true". Then insert your custom code into the ``header-custom.html`` file.
In the same way, you can customize the footer of the navigation menu, by setting to "true" the related option and put your code into the ``nav-footer-custom.html`` file.
Moreover it is now possible to select a reverse option that allows to move the navigation menu to the left side, by setting it to "true".

### Colors
The basic colors are set into the ``base.scss`` file:
- $main-color: used for the menu, title, link and footer
- $background-color: used for background and links in the navigation menu
- $text-color: used for text and title in posts and pages 

To customize the colors, just set the values in HEX, RGB (or RGBa) or any other format accepted by CSS.

### Navigation menu
Starting from the 1.1.0 version, the links inside the navigation menu are autogenerated from pages having the layout set to ``page``.
You can set custom links, by putting in the ``<a>`` tag into the ``link.html`` file.

### Branch
Emerald has two branch: 
- ``master``: is for developing pourpose.
- ``gh-pages``: is only for demo site.  

### Baseurl
Emerald was thought to be used mainly with Github, in particular into [project site](https://pages.github.com/). For this reason several tags have been included ``{{ site.baseurl }}`` to refer to the "/emerald/" directory.
You can change the "baseurl" value into the ``config.yml`` file, to match your directory (for example "/blog/") or the root of your project. In that case you must set the "baseurl" value to "/".

### Typography
To maintain the vertical rhythm, it has been applied a **Typographic scale** as a modular scale, with a baseline set to 24px. To maintain this rhythm you need to insert elements like image, video or other contents with a 24px (or multiple) height as refer.

Last but not least: the [Jekyll documentation](http://jekyllrb.com) is the best starting point! 

## Author

### Jacopo Rabolini

- Web site: [www.jacoporabolini.com](http://www.jacoporabolini.com)
- Google+: [+JacopoRabolini](https://plus.google.com/u/0/+JacopoRabolini/posts)

## License
Emerald is released under [MIT License](license.md).
