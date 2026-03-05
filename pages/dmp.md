--- 
title: Data Management Plan
layout: page
permalink: /dmp.html 
---



## Data Management Plan

### Project Description

*This project is collecting and managing a 30+ item CollectionBuilder website while using skills learned in UO’s LIB350M class. This project will have detailed descriptions of the images portrayed on the cigarette cards and it will include a summarization of the descriptions. We have organized the subjects so that any user on the website can quickly traverse through our vast collection.*

### Roles and Responsibilities

*List project partners and explain how data management responsibilities were coordinated across partners.*

* Andrew J. Sajor - CollectionBuilder coding and Metadata input
* Lucy Doran - Image uploading and CollectionBuilder writing

### Anticipated Data

*This data is a collection of art pictured on cigarette boxes from 1850-1959. It was accessed through the New York Public Library’s Digital Collections.*


| Item Description | File Type | Size (in MB) | \# of Items | License(s) | Sources |
| ---- | ---- | ---- | ---- | ---- | ---- |
| Downloaded images from both museum and public collections | jpg |  | 30  | Creative Commons Zero - Public Domain | World War I Museum, NYPL, Australian Sports Museum |
|  |  |  |  |  |  |

*This project uses CollectionBuilder, a static website framework built with Jekyll and hosted through GitHub Pages. Images and metadata are uploaded into the CollectionBuilder repository and organized using CSV metadata files. The website runs using standard web technologies including HTML, CSS, and JavaScript. The repository is stored on GitHub, allowing version control and public access to the project files. Users can access the collection through a web browser without installing any specialized software.*

**Documentation and Metadata**

*Documentation for this project includes the metadata spreadsheet used in CollectionBuilder, which serves as the project’s data dictionary. The spreadsheet records key metadata fields such as object ID, filename, title, creator, and source information. Additional documentation is included in the project’s GitHub repository README, which describes the project structure and how the collection is organized.*

**Storage and Backup**

*The metadata and collection images are both stored on Andrew’s personal device with a cloud backup on Google Drive. These cloud backups are shared with Lucy. The repository is going to be saved in a zip file located in this same cloud backup and will be available with GitHub’s lifespan.*

**Data Sharing**

*The project data is shared publicly through the CollectionBuilder website hosted on GitHub Pages. The images originate from publicly accessible digital collections, including the New York Public Library Digital Collections and museum archives, which allow reuse under public domain or Creative Commons licenses. The repository on GitHub also provides access to the metadata and project files for anyone who wishes to reuse or study the dataset.*

**Period of Data Retention**

*The project will be maintained for the duration of the course and grading period. After the course concludes, the project files will remain available through the GitHub repository, though active maintenance may stop. Because the images come from publicly available digital collections, the data can be recreated or downloaded again if needed in the future.*

**Licensing and Ethical Issues**

*The images used in this project are sourced from institutions that provide digital materials under Public Domain or Creative Commons licenses, allowing them to be reused for educational purposes. Proper attribution is included in the metadata for each image. The project does not include sensitive or private information, and all materials come from publicly available historical archives.* 

**Appendix: Data Dictionary**

* *Your data dictionary is a the key to your metadata.*  
* *You do not need to alter the standard definitions of fields required by CollectionBuilder, **but example values should come from your collection**..*

| field | definition | example |
| ---------- | ---------------------- | ------------- |
| objectid | the unique identifier for each object  | ccoll01 |
| filename | ccoll01  | .jpeg |
| title | the title of the object |  |
| creator | initials of the creator of the object |  |
