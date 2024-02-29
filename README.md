## README

Repository for Transdiagnostic Addiction Laboratory lab management files, manuals, etc.

Work in progress.

### Updating this document

This document was created using a Quarto book in R Studio, in combination with GitHub. To update this document, you must first access the [GitHub Repository](https://github.com/transdiagnostic-addiction-laboratory/TALab) and have Igor or the lab manager add you as a collaborator on the repository. From there, you should be able to clone the repository to your computer and begin working.

Before you begin making changes, you should first review the GitHub section in the lab manual document and understand how to commit changes, make push/pull requests, and what these terms mean.

Once you're ready to make changes, simply open the R project and modify any documents you would like. If you are removing sections, you can simply delete the .qmd files associated with those sections. To add sections, you can create a new Quarto document (.qmd file) and add content there. Note that if you add or remove documents, or would like to reorganize chapters, those changes must also be reflected in the \_quarto.yml file.

Once you are satisfied with your changes, commit and push your changes and then type:

``` {#git-publish .terminal-code style="color: green"}
quarto publish gh-pages
```

This should push your updates to `gh-pages` branch of the repository, and update the lab manual document.
