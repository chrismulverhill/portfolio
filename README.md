This page contains all the files you need to set up your own E-Portfolio using Quarto & GitHub. To use these files, 'fork' this repository. Using your Github Desktop app, you can then 'fetch the origin' - aka pull these files onto your computer, and make edits. First, open the "\_quarto.yml" file and change the output directory to your local repository folder. Next, personalize your page by opening the Quarto (qmd) files in R-Studio and adding your content. Once you are finished adding content, make sure you commit all of your edits to your GitHub repository. If you want to add any pages, simply create a new quarto document, and index it in the "\_quarto.yml" following the provided formatting.

Before we begin, make sure you have Github desktop installed on your device, that you are logged in to your github account in the desktop app, and that you have R-Studio installed on your device.

1.  Navigate to the sample repository using the link above.

2.  Now ‘fork’ the repository - this will create a copy of all of the files on your github account. You can make changes to this ‘forked’ repository without affecting the original or getting things mixed up with your peers. Make sure you provide a descriptive name for the forked repo.

3.  Open up your Github Desktop app and navigate to ‘File \> Clone Repository’. This will show you all of the repositories that are available to be cloned based on your github account. Find the forked repo and clone it to a local path. You will get a pop-up that asks you how you plan to use this fork - **make sure you select the ‘for my own purposes’ option**.

4.  In the Github Desktop app, click on the ‘Show in Explorer’ button - this will navigate to the folder on your computer where all the repo files are stored. This folder is where you will make changes to your E-Portfolio files.

5.  Open up an R-Studio session and click on ‘File \> Open File’. Navigate to your explorer folder with all of the repo files, and open the “\_quarto.yml” file. This file controls the indexing of your E-Portfolio. At the top, you will notice there is a file path for your output directory - change this to the folder containing your cloned repository and save the file.

6.  Next, open up the ‘index.qmd’ file. Edit the file with your own profile picture (if you’d like), contact information, and introduction blurb. When you are finished editing the page, save the .qmd file and hit ‘render’. This will give you a preview of what the page will look like in your E-Portfolio. Repeat this step for the ‘resume.qmd’ file.

7.  In your Github Desktop, you will now notice that there are local changes to the repository files based on your edits. You can push these edits to your github by clicking ‘commit to main’.

In order to customize your E-Portfolio, we encourage you to review the following resources:

-   [Quarto HTML Basics](https://quarto.org/docs/output-formats/html-basics.html)

-   [Quarto HTML Options](https://quarto.org/docs/reference/formats/html.html)

-   [Quarto Theming](https://quarto.org/docs/output-formats/html-themes.html)

Once you are satisfied with the content of your E-Portfolio, it is time to publish your website. Before you do so, make sure you have committed all local changes from your desktop. Once you are ready:

1.  Open your github account in your web browser, and navigate to your E-Portfolio repository.

2.  In the top bar, select ‘Settings’ and navigate to ‘Pages’ under the ‘Code and automation’ column.

3.  Under ‘Build and deployment’ \> ‘Branch’, select the ‘Main’ branch, and click save.

4.  Your website is now being built. This will take a few minutes, so be patient and refresh the page after \~ 2-5 minutes. Once complete, a url for your website will now be available to you.

[Here](https://ubc-mgem-fcor599.github.io/E-Portfolio/) is an example of the website created by the template provided.
