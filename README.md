# Jekyll-Boilerplate

The purpose of this boilerplate is to jumpstart Jekyll website development by having the basic directory structure and configuration items enabled. This boilerplate adhere's to **Nu HTML Checker** and implements various schema.org's schemas all across the website. Below is the folder structure that used for the website.

## Directory structure:

```
.
|-- _data\
|  |--+ navigation.yml
|  |--+ social.yml
|-- _includes\
|  |--+ articles.html
|  |--+ catalogue.html
|  |--+ footer.html
|  |--+ head.html *(includes inline css using scssify)*
|  |--+ header.html
|  |--+ kumbhar-vivek.scss *(parent stylesheet, imports .scss files from _sass folder using @imports)*
|  |--+ navigation.html
|  |--+ sidebar.html
|  |--+ social.html
|-- _layouts\
|  |--+ compress.html
|  |--+ default.html
|  |--+ post.html
|-- _posts\
|-- _sass\
|  |-- components\
|  |-- mixins\
|  |--+ _<file_name>.scss
|-- assets\
|  |-- fonts\
|  |-- images\
|-- pages\
|  |--+ about-me.html
|  |--+ catalogue.html
|  |--+ index.html
|--+ _config.yml
|--+ docker-compose.yml

```
