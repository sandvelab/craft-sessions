 **Note:** This website is under development.
 
# Sandve Lab Craft Sessions

Craft Sessions with links to relevant resources by the Sandve Lab, UiO.

## Contributing

### Updating the existing content

All the content is written in the restructured text (rst) format and compiled with Sphinx (for documentation, see https://www.sphinx-doc.org/en/master/).
To edit any of the existing pages, pull the content from the master branch, find the page under the source folder in this repository and edit the rst file. Check that 
you have the latest content from the master again and commit and push the changes to the master branch. This push will trigger a GitHub action which will run Sphinx 
in the background based on the content in the source folder, and create the HTML pages and store them in the docs folder. The changes 
in the newly updated docs folder will be automatically visible at https://sandvelab.github.io/craft_sessions/ in a few minutes.

### Adding new content

#### Where to add the content

At the website at https://sandvelab.github.io/craft_sessions/ in the left sidebar the content is divided into sections based on the audience level: 

- Postdoctoral Researchers, 
- PhD Candidates,
- Master's Students,
- All.

New topics can be added under the existing subsections.

#### How to add the content

To add a new page, add a new rst file in the chosen directory under the source folder, add the content, and add the page path without the extension 
to one of the sidebars by explicitly listing it at the page one level up in the hierarchy. 

From this, Sphinx will generate a sidebar with these three items that will have the text the same as the main title on the corresponding pages.

Images and other static files are located under source/_static/ and should be included using the relative path from the target page. 
