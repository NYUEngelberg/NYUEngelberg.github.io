![Glam3d Hero Image](https://github.com/NYUEngelberg/NYUEngelberg.github.io/blob/master/images/glam3D_header_image_v1_2.jpg "Glam3D hero image")

# NYUEngelberg.github.io
As of April 12, 2023, this repo is now an archive repo.  The current repo for glam3d.org is [https://github.com/NYUEngelberg/glam3d](https://github.com/NYUEngelberg/glam3d).  The change is the result of a migration from github pages to cloudflare pages for hosting.

This repo contains the website files for [Glam3D.org](https://glam3d.org/).  

Glam3D.org brings together best practices for conceiving, designing, and executing 3D Open Access programs at GLAM institutions. It is an evolving resource and we encourage you to email us at engelberg.center@nyu.edu if you have suggestions for improvements, additions, or corrections.  We also welcome suggestions in the form of pull requests or issues in this repo.

Glam3D.org is a project of the [Engelberg Center on Innovation Law & Policy](https://www.law.nyu.edu/centers/engelberg) at NYU Law. It was originally created in 2020 by Sketchfab Cultural Heritage Lead [Thomas Flynn](https://twitter.com/nebulousflynn), Engelberg Center Fellow [Neal Stimler](https://www.law.nyu.edu/centers/engelberg/team/stimler), and Engelberg Center Executive Director [Michael Weinberg](https://www.law.nyu.edu/centers/engelberg/team/weinberg), in consultation with a wide variety of 3D digitization and Open Access experts from around the world. Glam3D.org could not exist without the generous and valuable feedback from this community.

There is a [Conifer Archive](https://conifer.rhizome.org/) of this site from October 6, 2020.  It is available both on the [Conifer site](https://conifer.rhizome.org/EngelbergCenter/glam3dorg) and the [Internet Archive](https://archive.org/details/g3d_20201007).  The .warc file is not part of this repo because it exceeds GitHub's 100MB file size limit.

The site content is licensed under a [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/legalcode) license. The site itself is based on the [Jekyll Technical Documentation Theme](https://idratherbewriting.com/documentation-theme-jekyll/) by [Tom Johnson](https://idratherbewriting.com/aboutme/), modified by [Lauren Slowik](https://www.laurenslowik.com/).  It is licensed under an MIT license (except for the nav bar, which is licensed under a BSD license) and built with the Jekyll framework.

The nav bar itself is also hard coded instead of dynamically updated.  In order to update the nav bar, edit the file in `_data/sidebars/glam3d_sidebar.yml` directly.

The footnotes use [bigfootjs](http://www.bigfootjs.com/) to display properly.  If you would like to add a footnote, you will need to insert a new marker and update the text.  These steps are necessary because bigfoot uses the footnote numbers to match markers to text.  We try to keep the footnote text in the order it appears in the main text, which results in the reference numbers appearing out of sequence.  This can be strange when described in the abstract, so hopefully these steps will make it more clear.  We cannot guarantee that increased clarity will make it less strange.

1. Look at the bottom of the appropriate page.  If there is not a note (see below), use the next sequential number for your footnote and add an HTML comment with the next number.

2. If there is a note, like:
```HTML
<!-- Next fn is 64 -->
```
use that number as your new footnote number and increase the number in the note by one

3. Go to the place in the next you would like to add your footnote and add `[^64]`, where '64' is the number you decided to use based on steps 1 and 2.

4. In the footnote section, place your footnote in the appropriate order as reflected by the main text.  For example, if the paragraph before your new footnote has footnote #60 and the paragraph after your new footnote has footnote #61, place your footnote text between them in the footnote section.

5. Match your footnote format to the other footnotes.

6. bigfootjs can have problems rendering the text of really long URLs on mobile.  The best solution we have to address this is to add spaces in the text portion of the reference. For example:

`[https://www.heritagefund.org.uk/ stories/advice-understanding- our-licence-requirement](https://www.heritagefund.org.uk/stories/advice-understanding-our-licence-requirement)`

Note that there are spaces in the [] version of the URL.  A space every 30 characters or so usually does the trick. Adding the spaces after slashes or dashes makes it less obvious (and annoying) to readers.

That's it. So simple!
