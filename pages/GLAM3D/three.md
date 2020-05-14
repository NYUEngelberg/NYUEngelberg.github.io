---
title: 3.  What is a 3D Model?
summary: some words for a summary
sidebar: glam3D_sidebar
permalink: three.html

---

##    [3.1. Introduction to 3D Models](#introduction_to_3d_models)

In the simplest terms, a 3D model is just another kind of image: a way to show something to another person who is geographically or temporally removed from the original, physical cultural resource.

When compared with other media—images or video, for example—3D models are unique in one regard: their interactivity. A 3D model that you can interact with on a viewing device by rotating, zooming, and translating is said to be real-time 3D, as opposed to an image or a video of a 3D model, which is said to be pre-rendered. 3D models can also become physical 3D objects that can be touched, held, and examined without harming the originals.

3D models can have advantages over 2D images. A single image will show one view of a resource, cropped and zoomed a single way. An orthographic set will show more views (front, back, left, right, top, bottom) again at single crop and zoom levels. In contrast, a 3D model can be viewed from an infinite number of angles, a similar amount or zoom levels, and infinite cropped views. This is not to say that 3D is a superior approach to imaging in every context, but it does afford viewers new ways to look at a given resource.

Some common use cases for 3D models include:

*   Interactive display—e.g., on a screen, touchscreen, projection, hologram, or head-mounted display
*   Analysis and measurement—e.g., distance, volume
*   Creating physical replicas
*   Documenting physical changes in a cultural resource over time

3D models themselves should not be confused with the experiences that are built using them. Virtual and augmented reality, digital interactive games, animations, or film use 3D models much the same way that 2D images are involved in the production of a book, by drawing on a library of discrete files to build something bigger.[^28]

Probably the most common type of 3D model is a surface model, a digital description of the outward contours and appearance of a physical shape or form. A surface model is built of faces, and, similarly to the pixel dimensions of a 2D image, the resolution of a 3D model can be described for the most part in terms of the number of faces (the facecount) used to represent a cultural resource. Surface models are a common output from photogrammetry, structured light, and x-ray CT workflows.


![Herakles wireframe head](images/herakles_full.png "Herakles wireframe head")


###### 3D surface model of Marble head of Herakles from The Metropolitan Museum of Art with the face edges (the wireframe) highlighted. This model was created using a photogrammetry workflow.

As the name suggests, this surface model has no concept or record of a cultural resource’s internal structure—it is akin to a papier-mâché model in the real world: empty on the inside. By way of example, a 3D surface model of a wooden statue holds no record of the wood’s internal grain.



![Herakles wireframe head bisected](images/herakles_half.png "Herakles wireframe head bisected")


###### The same 3D surface model of Marble head of Herakles bisected, showing that it is hollow inside. The inward faces have been colored blue and a light and shadow added for easier recognition of this feature.

Another common type of 3D model is the point cloud. Instead of representing a physical shape with faces, we can also describe it using a number points or dots arranged in 3D space.



![Herakles Pointcloud](images/herakles_pointcloud.png "Herakles Pointcloud")


###### The same cultural resource represented by 3D as a point cloud.


Both surface model and point cloud files can also include color data that is either captured as part of the 3D digitization process or authored as part of data post processing or during a 3D modeling workflow.

A more in-depth look at the anatomy of 3D files can be found in the “Anatomy of a 3D Model” section in the Appendix.



###        [3.1.1. Creating 3D Models](#creating_3d_models)

This section includes some general guidance regarding commonly used 3D creation techniques. A more in-depth analysis of each technique can be found in the Appendix section “Common 3D Capture and 3D Creation Techniques and Software.”

Broadly speaking, creating a 3D model of a cultural resource will entail either a 3D digitization or 3D modeling workflow. The former uses a chain of equipment and software to capture a cultural resource’s likeness in 3D; the latter typically involves a 3D artist or designer building a 3D reconstruction or illustration of the same.

The general goal of a digitization process is to capture a cultural resource as accurately as possible. 3D modeling can also illustrate that which does not exist anymore, exists only in a digital space, or is entirely hypothetical—a group of outputs collectively referred to as _born-digital content_.

While this paper would be remiss in not mentioning both digitization and modeling workflows, it should be noted that due to the generally more complicated rights involved in commissioning an artist to create a new 3D work, the advice given throughout this publication is most applicable to digitization projects.

By way of a simple example showing comparative outputs of digitization and 3D modeling workflows, consider the two representations of a Roman villa below as typical outputs of the two processes.



<p id="gdcalert4" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/Lock-Text3.png). Store image on your image server and adjust path/filename if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert5">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/Lock-Text3.png "image_tooltip")
An example of a 3D output from a digitization workflow: Photogrammetric model of [villa room by Cotswold Archaeology](https://sketchfab.com/models/880e8668f49d4dbdb367def61fb4c41a).



<p id="gdcalert5" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/Lock-Text4.png). Store image on your image server and adjust path/filename if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert6">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/Lock-Text4.png "image_tooltip")
A similar subject (an ancient Roman villa) as created via a 3D modeling workflow: Reconstruction—[Roman room in Londinium by Mieke Roth](https://sketchfab.com/models/627c75ee13334940ba42c51e87272714) for The British Museum.

Both methods of 3D production require a certain amount of practice to yield effective results (if you are undertaking the 3D production yourself), or commercial companies can be hired to do the work for you. The advice in this white paper is based on the assertion that building in-house capacity for 3D production is the better long-term strategy. Doing so will better enable the effective inclusion of 3D in every relevant aspect of your organization’s work, future proofing its capacity for media production. The proven maturity of audiences and use cases for 3D models makes setting up and staffing a 3D digitization program now as equally useful as investing in a 2D photography program.

Deciding which 3D creation technique to use will largely depend on the goals you have set, available budgets, staffing, and staff skills. Below is a quick summary of common options, starting with the most inexpensive and easy-to-use techniques.



1. Illustrative 3D Modeling
2. Photogrammetry
3. Structured Light Scanning
4. LiDAR/Laser Scanning
5. X-Ray Computed Tomography

3D modeling is the most inexpensive and accessible option for producing 3D models, due to [high-quality open source software options](https://www.blender.org) and a minimum of equipment requirements. However, 3D modeling is an artistic and technical discipline that requires significant training and experience to master—while you can set yourself up for 3D modeling quickly and easily, it is unlikely to yield especially useful results straight away. 3D modeling does, however, offer extensive opportunities to create 3D content based on existing 2D digital collections.[^29]

Photogrammetry, the technique of calculating a 3D model by taking pictures of a subject from lots of different angles, is the most available form of 3D digitization available today. You or your organization likely already possess the capture technology (a smartphone or dedicated photography equipment, such as a DSLR or compact camera). and with relatively little effort, [free software](https://github.com/alicevision/meshroom) can produce high-quality 3D outputs.

The current expense and training requirements push the remaining methods of 3D digitization listed beyond the reach of anyone wanting to experiment with 3D production before making a significant investment of time and money. This is especially true for smaller organizations with limited funding.

While the unique nature of an organization’s collections demands unique approaches to 3D digitization, some existing projects indicate broadly effective approaches to 3D digitization.

* [Malopolska’s Virtual Museums](https://sketchfab.com/blogs/community/digitizing-art-and-history-from-40-malopolska-museums/), Poland


    A project consisting of a regional digitization studio servicing some 40 museums, using a combination of photogrammetry and structured light digitization techniques. This project approaches 3D digitization with clearly defined digitization, publication, and interpretation stages, which is reflected in equally important digitization, post-production, and editorial staff roles.


* [Museum of British Colonialism](https://www.museumofbritishcolonialism.org/), UK/Kenya


    An entirely volunteer-led organization founded to creatively communicate a more truthful account of British colonialism. As an online first space, MBC uses digital tools, including 3D reconstructions based on archival photography and oral interviews, to “engage audiences in a more interactive way and present information that would otherwise be inaccessible.”[^30]


    [National Natural History Museum of Santiago](http://mnhn.gob.cl/sitio/), Chile


    Motivated by the results of an experimental photogrammetry-based digitization project, the museum has undertaken a large-scale program of 3D digitization for public display.[^31]


    In order to create highly detailed 3D models, including versions that accurately document the shape and colors of the original objects, every artifact is digitized twice by using structured light scanning and photogrammetry.


    [Scottish Maritime Museum](https://www.scottishmaritimemuseum.org/), Scotland


    This museum has defined two core audiences for their digitization work: in-house staff who monitor the condition of the objects in the museum’s care and more casual online viewers looking to discover the stories about the objects and learn about their past. This project’s standard workflow involves capturing accurate data via LiDAR scanner and combines this with photogrammetry data sets of the same cultural resource to patch any missing geometry data and add high-quality color data.[^32]


    [Konzerthaus Berlin](https://www.konzerthaus.de/en/), Germany


    An EU-funded project designed especially to reach younger, more socially disadvantaged people with little access to culture, focusing 3D outputs optimized for online and augmented reality viewing. This organization employed a commercial architecture firm to 3D model several venues and buildings, combining these 3D models with color data from extensive architectural photography.[^33]

There are many more approaches[^34] worth reading about as you plan your own 3D production project. Through such an investigation, it becomes clear (judged on their 3D output and audience reception) that hybrid approaches to 3D production are generally the most successful.

If we assume the most effective 3D outputs are those that both accurately document a cultural resource’s shape (geometry data) and appearance (color data), we likely require a workflow that involves calibrated spatial capture (structured light, LiDAR) with calibrated color capture (photogrammetry).

When possible, capturing the highest-resolution and most accurate 3D data will afford the broadest possible range of use cases for the original data set as well as derivative 3D assets based on it.

While this paper exists because the authors believe a considered approach to 3D digitization is the most prudent course of action, some readers may wish to jump right in and attempt a “minimum viable 3D digitization workflow.” If you simply wish to start exploring the process of capturing and publishing 3D models of cultural resources right now, the Quick Start 3D Digitization Guide in the Appendix is for you.



###     [3.1.2. 3D Digitization Data Output Categories](#3d_digitization_data_output_categories)

The production of a single 3D model can entail a large number and variety of digital files, all of which may be offered under Open Access for specific audiences. A broad overview of digital file categories follows.



####            [3.1.2.1. Input Data](#input_data)

Input data is the raw data captured at the initial digitization stage. For example, in a photogrammetry workflow, input data comprises digital images; in a laser scanning workflow, this would be the files output from the laser scanning hardware.



####            [3.1.2.2. Project Files](#project_files)

Most 3D production workflows entail some processing or cleaning of raw data inputs. Edited data will most likely be stored in a proprietary format designed to be opened by a single, specific piece of software.



####            [3.1.2.3. Archival 3D Data](#archival_3d_data)

Archival 3D data are the highest quality and fidelity output files from a given digitization scenario, intended to be accessible and readable in perpetuity. This data is likely of most use to expert audiences, including internal personnel responsible for collection management. Recommended archival 3D file formats for cultural heritage projects include X3D, U3D, PLY, DAE, OBJ, and STL.[^35]



####            [3.1.2.4. Derivative 3D Data](#derivative_3d_data)

Derivative 3D data are 3D models derived from the archival 3D data, most likely simplified in some way and converted to other 3D file formats to facilitate quick and easy access and re-use as part of an Open Access offering for wider audiences.



####            [3.1.2.5. Metadata and Paradata](#metadata_and_paradata)

For all of the previous types of data, it is useful to provide additional context to what the 3D data is (metadata) and how it was captured or created and processed (paradata).

Recording and exposing detailed technical information that describes how a cultural resource was captured or created in 3D allows relevant end users more opportunity to verify the value and practical uses for a given 3D data set.

A few 3D file formats allow for additional text data to be embedded within the file itself. However, the varied software and platform support for metadata embedded in a 3D file combined with the ease with which a 3D file can be edited make this a somewhat unreliable method.

A more common and robust way to save or supply metadata is as an external text file, web page or database entry that can be provided alongside a 3D model at the moment of end user interaction with the 3D data. Refer to Section 6.2 on Data Structures for further information.

If it is technically possible and practical to both embed metadata and paradata in a 3D file and provide links to permanent external records, this increases the chances of contextual information about a 3D model remaining linked to it as it is downloaded, re-used, and remixed.

For further guidance regarding what kinds of metadata and paradata to collect and how to do so, explore the work of Cultural Heritage Imaging and their [Digital Lab Notebook](http://culturalheritageimaging.org/Technologies/Digital_Lab_Notebook/), the [Europeana 3D Task Force Report](https://pro.europeana.eu/files/Europeana_Professional/Europeana_Network/Europeana_Network_Task_Forces/Final_reports/3D-TF-final%20report.pdf), and the [Smithsonian 3D Metadata Model](https://dpo.si.edu/blog/smithsonian-3d-metadata-model).

<!-- Footnotes themselves at the bottom. -->
## Notes

[^28]:
     _See e.g._, Alban Denoyel, _3D is the Backbone of Any Immersive Strategy_, Sketchfab Customer Stories (March 26, 2019), [https://sketchfab.com/blogs/enterprise/news/3d-strategy/3d-immersive-technology](https://sketchfab.com/blogs/enterprise/news/3d-strategy/3d-immersive-technology)

[^29]:
     _See_ Thomas Flynn, _Collections: 2D to 3D_, Sketchfab,  [https://sketchfab.com/nebulousflynn/collections/2d-to-3d](https://sketchfab.com/nebulousflynn/collections/2d-to-3d), last accessed April 16, 2020.

[^30]:
     Museum of British Colonialism, _Emergency: An Exhibition on the Mau Mau Conflict and British Colonial Rule in 1950s Kenya_, 1, 13,  [https://static1.squarespace.com/static/591175bf1b10e32648746640/t/5e273aa7de776a57d97e2588/1579629236853/Emergency+Exhibition+Guide-compressed.pdf](https://static1.squarespace.com/static/591175bf1b10e32648746640/t/5e273aa7de776a57d97e2588/1579629236853/Emergency+Exhibition+Guide-compressed.pdf)

[^31]:
     Franscisco Garrido, _Chilean Heritage in 3D: A New Life for the Collections of the MNHN_, Sketchfab (November 21, 2018), [https://sketchfab.com/blogs/community/chilean-heritage-in-3d-a-new-life-for-the-collections-of-the-mnhn/](https://sketchfab.com/blogs/community/chilean-heritage-in-3d-a-new-life-for-the-collections-of-the-mnhn/)

[^32]:
     Marta Pilarska, _Scanning the Horizon: 3D Collections of the Scottish Maritime Museum_, Sketchfab (February 5, 2020), [https://sketchfab.com/blogs/community/scanning-the-horizon-3d-collections-of-the-scottish-maritime-museum/](https://sketchfab.com/blogs/community/scanning-the-horizon-3d-collections-of-the-scottish-maritime-museum/)

[^33]:
     Annette Thoma, _Konzerthaus Berlin: Cultural Participation Through Digitisation_, Sketchfab (September 20, 2018), [https://sketchfab.com/blogs/community/konzerthaus-berlin-cultural-participation-through-digitisation/](https://sketchfab.com/blogs/community/konzerthaus-berlin-cultural-participation-through-digitisation/)

[^34]:
     _See, e.g._, _Cultural Heritage_, Sketchfab, [https://sketchfab.com/blogs/community/category/community-story/cultural-heritage/](https://sketchfab.com/blogs/community/category/community-story/cultural-heritage/), last accessed April 16, 2020.

[^35]:
     _See_ _3D und Virtual Reality_, IANUS (November 22, 2016), [https://www.ianus-fdz.de/it-empfehlungen/3d](https://www.ianus-fdz.de/it-empfehlungen/3d); _see also_ Anas Alaoui M’Darhri et al., _Share - Publish - Store - Preserve. Methodologies, Tools and Challenges for 3D Use in Social Sciences and Humanities_, PARTHENOS (February 2019), [https://hal.archives-ouvertes.fr/hal-02155055/document](https://hal.archives-ouvertes.fr/hal-02155055/document); _see also_ _Guides to Good Practice_, Archeology Data Service, [https://guides.archaeologydataservice.ac.uk/g2gp/3d_3-2](https://guides.archaeologydataservice.ac.uk/g2gp/3d_3-2), last accessed April 16, 2020.