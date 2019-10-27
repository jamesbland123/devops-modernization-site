# AWS DevOps Modernization Workshops

### Install Hugo
The templating system uses Hugo. Do the following to install and run Hugo.

```
macOS: `brew install hugo`

Windows: `choco install hugo -confirm`
```

> For more information about installing and using Hugo, visit https://gohugo.io/getting-started/installing/ 

#### Runing Hugo
From within the root of the repo
``` 
$ hugo server
```
Using a browser go to http://localhost:1313 to view the site.  Hugo is dynamic, so as you edit the content the page in the browser will change.  Allowing you to view in real-time what the content will look like.

### To Add a New Partner

1. Create a markdown document at content/{section}/{company_name}.md.  {section} is the area that the solution falls under and {company_name} is the company name of the partners.  Its best to copy another document in the section and edit.
2. Place a logo of the company in themes/learn/assets.  The logo needs to be a .png that is 160x wide or larger.  The template system will scale down logos larger than 160x wide.  

### Publishing updates

Publishing will happen automatically once the changes are accepted into the git master branch.

