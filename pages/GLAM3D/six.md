---
title: 6.  Digitize
summary: some words for a summary
sidebar: glam3D_sidebar
permalink: six.html

---

##    [6.1. 3D Scanning](#3d_scanning)

This section will provide you with best practices for 3D digitization. It will not suggest a single workflow because there is no universal workflow for capturing cultural resources in 3D. Most resources are unique in size, shape, material, handling guidelines, accessibility, and portability. Most GLAM organizations and digitization projects are unique in their staffing, funding, goals, and audiences.

Additionally, and despite a huge amount of 3D data being produced by GLAM organizations,[^54] there are surprisingly few projects that share common standards and best practices.[^55]

Instead of searching for a single 3D digitization solution, it is more practical to explore existing guidelines for 3D digitization and consider their relevance to your project goals. It should then be possible to embed decision-making breakpoints and opportunities to capture paradata snapshots within your digitization project planning. Some points to consider are shared in this section.



###        [6.1.1. Do Your Research](#do_your_research)
Spending time to research existing workflows, case studies, and advice will save you time in the long run. Read academic papers but also visit or subscribe to specialized blogs and forums, and follow experts and amateurs alike on social media. Piece together a knowledge base that is suitable to your goals before you begin and make a note of resources you feel will be valuable to revisit later. Don’t be afraid to reach out to colleagues, manufacturers, and software developers directly for specific advice—it can save you hours of searching and maybe even some money too.

Below are a few online communities you may wish to consider joining, as well as a general reading list:

**Community Groups**

[IIIF 3D Community Group](https://iiif.io/community/groups/3d/)

[Community Standards for 3D Preservation (CS3DP)](https://groups.google.com/forum/#!forum/community-standards-for-3d-data-preservation-cs3dp)

[Europeana 3D Task Force](https://pro.europeana.eu/project/3d-content-in-europeana)

[LIB3DVR](https://lib.vt.edu/research-learning/lib3dvr.html)

[CLIR 3D/VR](http://vrpreservation.oucreate.com/Colloquium/) \
[3D Scanning Users Facebook Group](https://www.facebook.com/groups/3dsug/)

[Open Heritage 3D](https://openheritage3d.org/)

[Share3D](https://share3d.eu/)

**Reading Material**

[Cultural Heritage Spotlights on the Sketchfab Blog](https://sketchfab.com/blogs/community/category/community-story/cultural-heritage)

[Sketchfab Cultural Heritage Users Survey Results 2019](https://tinyurl.com/skfbchsurveyresults)

[Europeana 3D Task Force Report](https://pro.europeana.eu/files/Europeana_Professional/Europeana_Network/Europeana_Network_Task_Forces/Final_reports/3D-TF-final%20report.pdf)

[British Art Studies Issue 6: Disciplining the Digital](http://britishartstudies.ac.uk/issues/issue-index/issue-6/virtual-reproduction)

[ReACH Dialogue](https://www.vam.ac.uk/research/projects/reach-reproduction-of-art-and-cultural-heritage) - [Copy Culture: Sharing in the Age of Digital Reproduction PDF](https://vanda-production-assets.s3.amazonaws.com/2018/06/15/11/42/57/e8582248-8878-486e-8a28-ebb8bf74ace8/Copy%20Culture.pdf)

[Advice on 3D from National Swedish Heritage Board](https://www.raa.se/in-english/outreach-and-exhibitions)

[The London Charter](http://www.londoncharter.org/)



###        [6.1.2. Capture the Best Result You Can And Work Transparently](#capture_the_best_result_you_can_and_work_transparently)

No matter how well resourced and organized, your 3D digitization project will likely be limited in some way. The equipment and time available to you will largely dictate the resolution and fidelity of your 3D output. Be transparent about those limitations to your users. Publishing lower-resolution and even incomplete 3D scans is fine as long as you also make it clear to audiences what it is they are viewing and how it was made.

###   [6.1.3. Document Your Process As Thoroughly As Possible](#document_your_process_as_thoroughly_as_possible)

Following on from the previous point, and to re-assert the importance of meta- and paradata, record the details of your digitization and post-production process as much as possible. From the moment you begin your work, make note of the equipment you are using, decisions you are making, and the circumstances of the capture environment. Continue to document decisions made during processing and post-production and aim to publish this information at the same time as the 3D models.

###   [6.1.4. Plan For Mistakes And Technical Issues](#plan_for_mistakes_and_technical_issues)

Things don’t always go according to plan, but you can prepare your workflow to cope with this. Give yourself more time than you need to conduct digitization. Plan extra and backup digitization sessions. If you are new to a 3D digitization process, budget time to make tests and get familiar with your tools. Unless your work is highly specialized, you will no doubt find an answer online to any unexpected roadblocks you experience.


### [6.1.5. Archive Input Data And Project Files As Well As Output 3D Data](#archive_input_data_and_project_files_as_well_as_output_3D_data)

In an ideal world, all the data that is captured and produced during digitization would be available and archived in a way that accords with best practices. While this can quickly run to terabytes of data, making input data and project files available means other people can verify and build on your work. It will also allow you to go back to make additional uses of your scanning efforts as new technology develops. Long-term data storage and security should be considered during your project planning.

Cultural sector collections management, digital asset management, and digital preservation providers need to develop further capabilities to catalogue, process, present, store, transform, and deploy 3D data and models. Most of these systems are currently oriented toward 2D digital images, accompanying metadata, and—increasingly—video. Many of the technological advances and communities of practice for 3D began in industries outside the cultural realm, such as gaming, manufacturing, and multimedia production. Time-based media and software preservation systems are being used with increasing adoption as more of cultural and content production is digital-first. Institutions should work with the industry systems providers to test and build capacity for 3D data and models, along with working in collaboration with professional communities of practice. Common and core functionalities include the aforementioned internal systems requirements, along with external functionalities such as browser-based display and download from collections online; deployment and distribution to third-party databases or applications through batch processes or automated APIs; and export and migration to future platforms.



##  [6.2. Data Structures](#data_structures)

###        [6.2.1. Metadata and Paradata](#metadata_and_paradata)

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

###     [6.2.2. Data Files](#data_files)

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

###     [6.2.3. Data Packages](#data_packages)

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

<!-- Footnotes themselves at the bottom. -->
## Notes

[^54]:
     _See e.g._, Thomas Flynn, _Over 100,000 Cultural Heritage 3D Models on Sketchfab_, Sketchfab (October 2, 2019), [https://sketchfab.com/blogs/community/over-100000-cultural-heritage-3d-models-on-sketchfab/](https://sketchfab.com/blogs/community/over-100000-cultural-heritage-3d-models-on-sketchfab/)

[^55]:
     _Cultural Heritage User Survey 2019_, Sketchfab (August 2019), [https://docs.google.com/presentation/d/1avExQtbfl6vDCFyo5VgSyBy638BjdDTAIhw79ClHT5A/edit#slide=id.g5e4c799188_0_573](https://docs.google.com/presentation/d/1avExQtbfl6vDCFyo5VgSyBy638BjdDTAIhw79ClHT5A/edit#slide=id.g5e4c799188_0_573) (demonstrating that a majority of institutions surveyed use no formal quality assurance methods or standards for their 3D production work).

[^56]:

     _What is a DOI and How Do I Use them in Citations?_, University of Illinois Library, [https://library.uic.edu/help/article/1966/what-is-a-doi-and-how-do-i-use-them-in-citations](https://library.uic.edu/help/article/1966/what-is-a-doi-and-how-do-i-use-them-in-citations), last accessed April 16, 2020.

[^57]:
     _See CS3DP Community Standards for 3D Data Preservation_ [https://osf.io/ewt2h/wiki/home, last accessed April 16, 2020](https://osf.io/ewt2h/wiki/home); _see also_
    _IIIF 3D Community Group_, IIIF, [https://iiif.io/community/groups/3d, last accessed April 16, 2020](https://iiif.io/community/groups/3d); _see also_ _3D Content in Europeana_, Europeana 3D Task Force (January 28, 2019), [https://pro.europeana.eu/project/3d-content-in-europeana](https://pro.europeana.eu/project/3d-content-in-europeana)
