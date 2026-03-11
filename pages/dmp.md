--- 
title: Data Management Plan
layout: page
permalink: /dmp.html 
---



# Wills’ Cigarettes - Late 1800s and Early 1900s  
## With WWI Wartime Propaganda  
## Data Management Plan

---

## Project Description

This project is collecting and managing a 40+ item CollectionBuilder website while using skills learned in UO’s LIB350M class. This data collection includes detailed descriptions of the images portrayed on the cigarette cards along with summarized descriptions.

CollectionBuilder is a website creation template using GitHub for digital collection projects. The subjects in the collection are organized so that users can quickly browse and navigate through the collection.

---

## Roles and Responsibilities

- **Andrew J. Sajor** – CollectionBuilder coding and metadata input  
- **Lucy Doran** – Image uploading and CollectionBuilder writing  

---

## Anticipated Data

This dataset is a collection of artwork pictured on cigarette boxes from **1850–1959**. The images were accessed through the **New York Public Library Digital Collections**. The project source code is built using **CSS and YAML-based templates**.

| Item | Description | File Type | Size (MB) | # of Items | License | Sources |
|-----|-------------|-----------|-----------|------------|---------|---------|
| Downloaded images from museum and public collections | Artwork and cigarette cards | jpg | 2148 KB | 30 | Creative Commons Zero (Public Domain) | World War I Museum, NYPL, Australian Sports Museum, WW1 Museum |

This project uses **CollectionBuilder**, a static website framework built with **Jekyll** and hosted through **GitHub Pages**. Images and metadata are uploaded into the CollectionBuilder repository and organized using **CSV metadata files**.

The website runs using standard web technologies including:

- HTML  
- CSS  
- JavaScript  

The repository is stored on GitHub, allowing **version control and public access** to the project files. Users can access the collection through a **web browser without installing specialized software**.

---

## Documentation and Metadata

Documentation for this project includes the **metadata spreadsheet used in CollectionBuilder**, which serves as the project’s **data dictionary**.

The spreadsheet records key metadata fields including:

- Object ID  
- Filename  
- Title  
- Creator  
- Source information  

Additional documentation is included in the **GitHub repository README**, which describes the project structure and how the collection is organized.

---

## Storage and Backup

The metadata and collection images are stored on **Andrew’s personal device** with a **cloud backup on Google Drive**. These cloud backups are shared with **Lucy**.

The repository will also be saved as a **ZIP file** in the same cloud backup and will remain available through **GitHub’s repository hosting**.

---

## Data Sharing

The project data is shared publicly through the **CollectionBuilder website hosted on GitHub Pages**.

The images originate from publicly accessible digital collections including:

- New York Public Library Digital Collections  
- Museum archives  

These sources allow reuse under **Public Domain or Creative Commons licenses**.

The GitHub repository also provides access to the **metadata and project files** for anyone interested in reusing or studying the dataset.

---

## Period of Data Retention

The project will be maintained for the **duration of the course and grading period**.

After the course concludes:

- The project files will remain available through the **GitHub repository**.
- Active maintenance may stop.

Because the images come from **publicly available digital collections**, the data can be **recreated or downloaded again in the future if needed**.

---

## Licensing and Ethical Issues

The images used in this project are sourced from institutions that provide digital materials under **Public Domain or Creative Commons licenses**, allowing them to be reused for **educational purposes**.

Proper attribution is included in the **metadata for each image**.

The project does **not include sensitive or private information**, and all materials come from **publicly available historical archives**.

---

# Appendix: Data Dictionary

| Field | Definition | Example |
|------|------------|---------|
| objectid | Unique identifier assigned to each item in the collection | ccoll01 |
| filename | Name of the image file stored in the repository | `.jpeg` |
| title | Title or name of the cigarette card image | A Description of the Submarines used in the War |
| creator | Artist or organization responsible for the image | W.D. & H.O. Wills |
| source | Institution where the digital image was obtained | New York Public Library |
| date | Approximate date the image or card was created | 1895 |
| rights | Usage rights or license associated with the image | Public Domain |
| description | Description of the card or transcription of the back of the card | Artwork of the Louvain Town Hall |
| orientation | Orientation of the card | Vertical |




