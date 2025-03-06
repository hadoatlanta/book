+++
title = "Introduction"
type = "home"
+++
The theme is using [hugo-relearn-theme](https://mcshelby.github.io/hugo-theme-relearn/index.html).

There 3 type of pages:
- [Create a Home Page](#create-a-home-page)
- [Create a Chapter Page](#create-a-chapter-page)
- [Create a Content Pages](#create-a-content-pages)

## Create a Home Page

````
hugo new --kind home _index.md
````

## Create a Chapter Page

````
hugo new --kind chapter log/_index.md
````

## Create a Content Pages

````
hugo new log/first-day/_index.md
hugo new log/second-day/index.md
hugo new log/third-day.md
````