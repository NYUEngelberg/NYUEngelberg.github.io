---
title: 6.  Digitize
summary:
sidebar: glam3D_sidebar
permalink: digitize.html

---

##    6.1 3D Scanning

This section will provide you with best practices for 3D digitization. It will not suggest a single workflow because there is no universal workflow for capturing cultural resources in 3D. Most resources are unique in size, shape, material, handling guidelines, accessibility, and portability. Most GLAM organizations and digitization projects are unique in their staffing, funding, goals, and audiences.

Additionally, and despite a huge amount of 3D data being produced by GLAM organizations,[^54] there are surprisingly few projects that share common standards and best practices.[^55]

Instead of searching for a single 3D digitization solution, it is more practical to explore existing guidelines for 3D digitization and consider their relevance to your project goals. It should then be possible to embed decision-making breakpoints and opportunities to capture paradata snapshots within your digitization project planning. Some points to consider are shared in this section.



###        6.1.1 Do Your Research
Spending time to research existing workflows, case studies, and advice will save you time in the long run. Read academic papers but also visit or subscribe to specialized blogs and forums, and follow experts and amateurs alike on social media. Piece together a knowledge base that is suitable to your goals before you begin and make a note of resources you feel will be valuable to revisit later. Don’t be afraid to reach out to colleagues, manufacturers, and software developers directly for specific advice—it can save you hours of searching and maybe even some money too.

Below are a few online communities you may wish to consider joining, as well as a general reading list:

**Community Groups**

[IIIF 3D Community Group](https://iiif.io/community/groups/3d/)

[Community Standards for 3D Preservation (CS3DP)](https://groups.google.com/forum/#!forum/community-standards-for-3d-data-preservation-cs3dp)

[Europeana 3D Task Force](https://pro.europeana.eu/project/3d-content-in-europeana)

[LIB3DVR](https://lib.vt.edu/research-learning/lib3dvr.html)

[CLIR 3D/VR](http://vrpreservation.oucreate.com/Colloquium/)
[3D Scanning Users Facebook Group](https://www.facebook.com/groups/3dsug/)

[Open Heritage 3D](https://openheritage3d.org/)

[Share3D](https://share3d.eu/)

**Reading Material**

[Advice on 3D from National Swedish Heritage Board](https://www.raa.se/in-english/outreach-and-exhibitions)

[British Art Studies Issue 6: Disciplining the Digital](http://britishartstudies.ac.uk/issues/issue-index/issue-6/virtual-reproduction)

[Cultural Heritage Spotlights on the Sketchfab Blog](https://sketchfab.com/blogs/community/category/community-story/cultural-heritage)

[European Commission Expert Group Report: Basic Principles and Tips for 3D Digitisation of Cultural Heritage](https://ec.europa.eu/digital-single-market/en/news/basic-principles-and-tips-3d-digitisation-cultural-heritage)

[Europeana 3D Task Force Report](https://pro.europeana.eu/files/Europeana_Professional/Europeana_Network/Europeana_Network_Task_Forces/Final_reports/3D-TF-final%20report.pdf)

[The London Charter](http://www.londoncharter.org/)

[ReACH Dialogue](https://www.vam.ac.uk/research/projects/reach-reproduction-of-art-and-cultural-heritage) - [Copy Culture: Sharing in the Age of Digital Reproduction PDF](https://vanda-production-assets.s3.amazonaws.com/2018/06/15/11/42/57/e8582248-8878-486e-8a28-ebb8bf74ace8/Copy%20Culture.pdf)

[Sketchfab Cultural Heritage Users Survey Results 2019](https://tinyurl.com/skfbchsurveyresults)







###        6.1.2 Capture the Best Result You Can And Work Transparently

No matter how well resourced and organized, your 3D digitization project will likely be limited in some way. The equipment and time available to you will largely dictate the resolution and fidelity of your 3D output. Be transparent about those limitations to your users. Publishing lower-resolution and even incomplete 3D scans is fine as long as you also make it clear to audiences what it is they are viewing and how it was made.

###   6.1.3 Document Your Process As Thoroughly As Possible

Following on from the previous point, and to re-assert the importance of meta- and paradata, record the details of your digitization and post-production process as much as possible. From the moment you begin your work, make note of the equipment you are using, decisions you are making, and the circumstances of the capture environment. Continue to document decisions made during processing and post-production and aim to publish this information at the same time as the 3D models.

###   6.1.4 Plan For Mistakes And Technical Issues

Things don’t always go according to plan, but you can prepare your workflow to cope with this. Give yourself more time than you need to conduct digitization. Plan extra and backup digitization sessions. If you are new to a 3D digitization process, budget time to make tests and get familiar with your tools. Unless your work is highly specialized, you will no doubt find an answer online to any unexpected roadblocks you experience.


### 6.1.5 Archive Input Data And Project Files As Well As Output 3D Data

In an ideal world, all the data that is captured and produced during digitization would be available and archived in a way that accords with best practices. While this can quickly run to terabytes of data, making input data and project files available means other people can verify and build on your work. It will also allow you to go back to make additional uses of your scanning efforts as new technology develops. Long-term data storage and security should be considered during your project planning.

Cultural sector collections management, digital asset management, and digital preservation providers need to develop further capabilities to catalogue, process, present, store, transform, and deploy 3D data and models. Most of these systems are currently oriented toward 2D digital images, accompanying metadata, and—increasingly—video. Many of the technological advances and communities of practice for 3D began in industries outside the cultural realm, such as gaming, manufacturing, and multimedia production. Time-based media and software preservation systems are being used with increasing adoption as more of cultural and content production is digital-first. Institutions should work with the industry systems providers to test and build capacity for 3D data and models, along with working in collaboration with professional communities of practice. Common and core functionalities include the aforementioned internal systems requirements, along with external functionalities such as browser-based display and download from collections online; deployment and distribution to third-party databases or applications through batch processes or automated APIs; and export and migration to future platforms.



##  6.2 Data Structures

###        6.2.1 Metadata and Paradata

Metadata related to 3D models of cultural resources includes information about the 3D file(s) and information regarding the cultural resource itself. The paradata explains how a 3D model was generated and details decisions that were made during this process. Meta- and paradata make a given 3D model more valuable and re-usable: If audiences better know what they are viewing or downloading, they are better able to understand it and incorporate it into their own plans.

It is not currently possible to reliably embed extended meta- and paradata within most 3D file formats. While some file formats like X3D offer the option to write additional information into the 3D file itself, the format is not widely supported in other 3D software or platforms—and when a file is converted to another format, the data is often lost. This makes X3D an interesting candidate for archival data but not so valid as a format for dissemination through an Open Access program.

A simple approach to connecting metadata to a 3D model is to publish it separately from the model and/or provide links to it. This might take the form of one or all of the following:

*   A text file within the downloadable 3D data archive
*   A link on the same page as the 3D model
*   Machine-readable tags (where supported)
*   An online database that is accessible via API or a web interface

Whatever form you decide on, do not be overly concerned with the idea of your 3D data existing separately from its detailed metadata. End users of your 3D data will inevitably edit, separate, or remove metadata when it is not deemed relevant to their re-use of your 3D models.

What is important is to make a “best effort” at the point of initial interaction, to provide as much context to your 3D model as possible. A nice example of this approach is the presentation of the 3D model [The Grandfather of Europe by AD&D 4D](https://sketchfab.com/3d-models/the-grandfather-of-europe-granada-spain-decf3d333d9d4345a35ac5d524d71e1f) on Sketchfab:

*   The 3D model is present with a descriptive title, including the cultural resources location.
*   A summary description is presented alongside in both English and Spanish.
*   The description includes a Digital Object Identifier (DOI)[^56] badge from zenodo.com that links a persistent online record pertaining to the digital file, as well as downloadable data packages.
*   The model is categorized correctly in the Sketchfab system.
*   The model is presented with extensive descriptive, machine-readable tags.
*   There are extensive informative annotations on the model itself.

What constitutes a complete metadata set and best practice for associating it with a 3D model is not a settled matter, and several organizations are working toward building consensus.[^57] What metadata you capture and publish will largely depend on what is already available (e.g., an existing cultural resource object record) and what you have the opportunity and capacity to record during your 3D creation workflow. There is no clear right or wrong regarding metadata; rather, there are gradations of light to heavy, sparse to complete, and this should be made clear wherever the metadata is published. A bare minimum might be a description of what the cultural resource represented by the 3D model is, a technical description of the 3D file, and a description of the workflow by which it was captured or created.

Among the mature 3D digitization initiatives for cultural heritage, the [Smithsonian 3D Metadata Model](https://dpo.si.edu/blog/smithsonian-3d-metadata-model) offers one of the most complete attempts at defining a metadata scheme for cultural heritage 3D, based on extensive experience digitizing resources from multiple collections.

###     6.2.2 Data Files

The input and project files that you offer under Open Access will vary depending on your capture, processing, and post-production methods. The output and derivative 3D files will also vary depending on your project goals.

By way of example, let’s consider a 3D model generated using a photogrammetry pipeline:

**Input Files**

Digital images.

**Project Files**

Photogrammetry software project file.
3D editor software project file (if the workflow included a post-production stage).

**Output and Derivative 3D Files**

The following list is not exhaustive and, depending on your project goals, there may be other 3D file formats that suit your needs. It is recommended that you check which file formats your destination 3D viewer supports, as well as what download formats are most usable by your primary audience(s).

You do not need to choose only one output file format. Publishing the same 3D model in a variety of formats increases the chance of uptake by certain communities. Suggested file formats for you to create are listed below with a summary of their use cases.

**X3D**

As one of the only 3D [ISO/IEC internationally ratified standard](https://www.web3d.org/standards/number/19775-1) formats, X3D is a good choice for archival use, but for wider dissemination, other formats should be considered.

**OBJ**

An open source file format that is widely supported in common 3D editing software. It is usually associated with a separate material (.MTL) file and separate texture map file(s) (.JPG, .PNG).

**FBX**

A proprietary file format often used in film, animation, and interactive game production that supports embedded textures and animations.

**STL**

A file format specific to 3D printing. It does not support vertex or UV color mapping.

**GLTF, USDZ**

Two newer open 3D interchange formats that support embedded animations, color mapping, and material options. Support for both formats is growing across 3D editing tools for film, animation and interactive game production, as well as AR and VR tools. Android devices that support ARCore are able to display GLTF in a native [AR Scene Viewer](https://developers.google.com/ar/develop/java/scene-viewer), and likewise iOS devices can natively display USDZ in [AR Quicklook](https://developer.apple.com/augmented-reality/quick-look/).

Duplicating or exporting a 3D model in multiple formats will of course take more time and significantly increase data storage requirements. This effect is compounded if 3D models at multiple resolutions for each file format are required. One approach to mitigate such issues might be to produce and maintain high-resolution “master” projects and 3D models files, only creating derivatives as and when they are required, it being even better if this process can be automated.

###     6.2.3 Data Packages

By deliberately choosing a combination of 3D file formats, data resolutions, and linked meta- and paradata, it is possible to build “data packages” aimed at specific audiences. As part of digitization project planning, it is likely a good exercise to define target data packages and budgeting post-production resources to their preparation. If you are not sure of the best data package for your audience, it will behoove you to reach out to that audience before beginning digitization.

Three example data packages follow:

**Researchers**

*   Input data
*   Project files
*   High-resolution archival 3D data, X3D file, high -resolution texture maps (16384x16384 pixels)
*   Extensive meta- and paradata

**Students**

*   Optimized derivative 3D data, STL and OBJ files, medium-resolution texture maps (4096x4096 pixels)
*   Curriculum-related meta- and paradata

**AR and VR Developers**

*   Highly optimized derivative 3D data—e.g., GLTF, USDZ, low-resolution texture maps (1024x1024 pixels)
*   Basic metadata

## 6.3 Data Storage

### 6.3.1 Data Size

3D digitization can quickly create large numbers of files with an equally large storage requirement. A simple project can quickly exceed several gigabytes (GB), and a complex one can grow to terabytes (TB). Multiple smaller projects will also soon grow to require considerable total amounts of data storage.

Data planning at the beginning of a project is essential to help protect the time spent digitizing in 3D, especially if repeat access to the physical cultural object is not possible. Caring for archived data after a project has finished is also essential.

It can be difficult to accurately predict the amount of storage that you may require. A large photogrammetry project can quickly double or triple in size just through necessary steps such as saving multiple versions of a project through the stages of creating the 3D model, cleaning it, and creating various derivative files such as a high resolution uncleaned model, a high resolution cleaned version, and lower resolution files for distribution.

### 6.3.2 External Drives for Capture and Work-in-Progress

It is often a good idea to purchase or repurpose a new external hard drive for a photogrammetry project. Connected to a PC or Mac via USB3 these provide fast access to data and it is easy to keep an eye on how much storage a project is using.

A 4 terabyte hard drive can be a good starting place with plenty of room for raw photographs and their derivatives, photogrammetry project files, and exported files. Aim for a USB-powered drive to avoid the need for an external power supply (which could develop a fault and be difficult to replace and therefore create difficulty in accessing the data in the future).   You should budget for two identical drives - one for the ‘live’ project and one for a running backup to protect your data if the primary drive fails.

Always label a drive on the enclosure to allow easy identification. Labels can become detached through time, so make sure your labels are firmly attached to the drives (or write directly on the drives themselves).

Once a project is complete you should ensure that the two drives, where possible (e.g. if full, and if budget allows) are stored safely.

One drive may need to be on-hand for ongoing data access. The other drive should be stored carefully in a dry, low-magnetic environment. If you are in a museum, this could be in your institution’s archives where paper records are stored. You may wish to talk to relevant members of your team to ensure that the location is documented in an appropriate way.

### 6.3.3 Directory Structure

A clear, easily understood directory structure is essential to making use of your data. A complex 3D project can quickly create many files and become difficult to navigate. Always think about future access to the project and files by someone other than yourself. Will they be able to work out what files they need?

An example structure for a photogrammetry project could be (directory names)

- Project name
    - Photographs
        - RAW
        - JPEG
    - 3D
        - Photogrammetry
        - Exports
            - High res uncleaned
            - High res cleaned
            - Low res cleaned
            - Working
    - Archive

### 6.3.4 Files, Meta, and Paradata

As computers become faster and photogrammetry methods improve, you may be able to re-process your raw data to produce better results in the future. IIt is good practice to ensure that you use ASCII formats where possible.  Even though these formats are not as easy to use for day-to-day processing, archiving your data in them will increase the likelihood that your files will be accessible when you need them. ASCII formats store 3D information and colors in plain text in the form of 3D coordinates (x,y,z,r,g,b).  A mesh or point cloud can be saved in the ASCII PLY format from most 3D software. Store this in your “Archive” directory.

Use plain text (TXT) files to hold metadata describing the project directory structure and explain the contents, formats used, and paradata such as camera type, lens, and any notes about the conditions when the scan took place. Any other decisions about colour correction, sharpening, and other processing should be made here.

There is no standard way of doing this, so be mindful that this should be easily understood in the future. Read the [GLAM 3D guidance for metadata and paradata](/digitize.html#621-metadata-and-paradata).

### 6.3.5 Backup and Cloud Storage

While USB external drives backups can be helpful, they can and do fail. If you do not have a backup, then you will have lost everything. This could be especially devastating if you cannot re-scan the subject because it has been destroyed, degraded, or lengthy travel was originally involved in accessing it.

**Good: a second USB drive**

A second USB drive is the easiest backup solution. Plenty of software is available that allows for drives to be backed up automatically or manually in a number of ways.

This could be as simple as scheduling a time to regularly copy the contents of the drive to spare drive. It could be installing an app that does this for you. If backing up is a manual process, try to set reminders and keep a log of what was backed up and when.

**Better: use the cloud**

Cloud storage allows the creation of an off-site backup without requiring any other infrastructure. There are plenty of apps that allow external drives to be backed up to the cloud using, for example, [Amazon Glacier](https://aws.amazon.com/glacier/), [Dropbox](https://www.dropbox.com/), [Backblaze](https://www.backblaze.com/). Sometimes these apps are included with a USB drive.

Cloud storage must be paid for (and continue to be paid for) so consider these costs when planning. A fast internet connection, particularly the upstream speed, will also be needed to complete an initial backup of large 3D datasets in a timely manner. How fast will depend on how long you can wait for a cloud transfer to take, but generally a minimum of 10Mbps upload speed will be needed.

*If you stop paying for cloud storage - sometimes even accidentally - your backup will disappear. Consider using cloud storage in combination with two drives.*

**Best: backup your drive to a server which has drive redundancy & cloud backup**

Depending upon your resources you may be able to work with your organisation’s IT team to help you backup your project drive to a local server that you maintain, which can in turn be backed up in another way (e.g. [magnetic tape](https://en.wikipedia.org/wiki/Tape_drive), or to the cloud).

Network Attached Storage (NAS) drives can be used as a local backup server. These small units are connected to networks where they appear as another drive, and often provide software for automatic backup processes. These devices can also be easier to administer than full servers.  Some NAS drives, such as those by Synology, have dedicated backup protocols built into the device, so that versions of files can be preserved if you need to roll-back an unwanted change or accidental deletion.

NAS drives are often set up with redundant drives using a technology called [RAID](https://en.wikipedia.org/wiki/RAID). For example, a NAS drive with two HDD bays could be installed with two 4TB drives. It could be configured to provide 4TB storage, with 4TB of redundancy. All data saved to the 4TB drive would be instantly copied. If one of the drives were to fail, the data is safe on the other drive. While this protection against hard drive failure can be important, remember that RAID is in itself not a backup solution. Delete a file from one drive and it will be deleted on the other.

If one drive fails then the faulty drive may be removed and a fresh one installed. The data would be automatically re-duplicated providing once again, two ‘live’ copies. Complex RAID configurations can be designed with multiple drive redundancy.

NAS drives often contain cloud backup software so that off-site backups happen automatically.

### 6.3.6 Confirm Backup Routines and Data Integrity

As with all automatic methods, schedule time to check that these backups are actually occurring. This could be by manually checking your second drive or by examining the logs on your server/NAS drive.

Always check the integrity of a backup by opening backed up files from time to time.

### 6.3.7 Dissemination as a Form of Preservation

In general, the more copies of a dataset, or parts of a dataset, that exist, the better. This means that one single location is not being relied upon for 3D assets to continue to be available.

Consider making data available on multiple platforms. In addition to internal storage, make a copy available on your institution’s website.  Upload copies to other platforms as well.  The [Internet Archive](https://archive.org/) can store 3D files.  [Sketchfab](https://sketchfab.com/) will display them.  Data, metadata, and paradata about files can be stored on [GitHub](https://github.com).  Reduced - still high - quality models can be submitted to [Wikimedia Commons](https://commons.wikimedia.org/wiki/Main_Page).  None of these platforms is necessarily the best platform to store your data.  The key is to distribute it widely, thus decreasing the likelihood that a single failure will erase the data entirely.  

### 6.3.8 Digital Archives

Your country may have a dedicated digital archive service. For example, in the UK, the [Archaeology Data Service](https://archaeologydataservice.ac.uk) (ADS) can be contacted to discuss permanent backups of data related to archaeological projects in the country. Data lodged with the ADS is constantly monitored, moved to fresh disks, checked for integrity and so on, as part of an active data archive strategy. Data can also be made accessible through their web portal to enable Open Access.

3D data can be costly to archive, so if archiving in this way is important to your project, have a conversation with a digital archivist right at the beginning of a project where possible.





<br>
<br>
**NEXT SECTION [Disseminate](/disseminate.html)**

***

<!-- Footnotes themselves at the bottom. -->
## Notes

[^54]:
     _See e.g._, Thomas Flynn, _Over 100,000 Cultural Heritage 3D Models on Sketchfab_, Sketchfab (October 2, 2019), [https://sketchfab.com/blogs/ community/over-100000-cultural-heritage- 3d-models-on-sketchfab/](https://sketchfab.com/blogs/community/over-100000-cultural-heritage-3d-models-on-sketchfab/)

[^55]:
     _Cultural Heritage User Survey 2019_, Sketchfab (August 2019), [https://docs.google.com/ presentation/d/1avExQtbfl6vDCFyo5VgSyBy638BjdDTAIhw79ClHT5A/ edit#slide=id.g5e4c799188_0_573](https://docs.google.com/presentation/d/1avExQtbfl6vDCFyo5VgSyBy638BjdDTAIhw79ClHT5A/edit#slide=id.g5e4c799188_0_573) (demonstrating that a majority of institutions surveyed use no formal quality assurance methods or standards for their 3D production work).

[^56]:

     _What is a DOI and How Do I Use them in Citations?_, University of Illinois Library, [https://library.uic.edu/help/ article/1966/what-is-a-doi-and-how-do-i- use-them-in-citations](https://library.uic.edu/help/article/1966/what-is-a-doi-and-how-do-i-use-them-in-citations), last accessed April 16, 2020.

[^57]:
     _See CS3DP Community Standards for 3D Data Preservation_ [https://osf.io/ewt2h/wiki/home, last accessed April 16, 2020](https://osf.io/ewt2h/wiki/home); _see also_
    _IIIF 3D Community Group_, IIIF, [https://iiif.io/community/groups/3d, last accessed April 16, 2020](https://iiif.io/community/groups/3d); _see also_ _3D Content in Europeana_, Europeana 3D Task Force (January 28, 2019), [https://pro.europeana.eu/project/3d-content-in-europeana](https://pro.europeana.eu/project/3d-content-in-europeana)
