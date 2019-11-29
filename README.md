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
|  |--+ head.html # includes inline css using scssify
|  |--+ header.html
|  |--+ navigation.html
|  |--+ sidebar.html
|  |--+ social.html
|  |--+ vk.scss # parent stylesheet, imports all .scss partials from _sass using |@imports
|  |--+ navigation.html
|  |--+ sidebar.html
|  |--+ social.html
|-- _layouts\
|  |--+ compress.html
|  |--+ default.html
|  |--+ post.html
|-- _posts\
|-- _sass\
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
