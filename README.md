# BYU-I ME Portfolio Template
## Building a Quarto Portfolo

A template for a portfolio developed with Quarto and hosted on GitHub.

This is all configured so you only need to edit the source files in Quarto (.qmd). The website is generated and hosted automatically by GitHub.
If you need help installing the VS Code Quarto extension and the Quarto CLI, please see the [Quarto Installation](https://byuistats.github.io/DS250-Course/Setup/quarto_setup.html) page.

### Walkthrough
```{=html}
<iframe id="kaltura_player" src="https://cdnapisec.kaltura.com/p/1157612/sp/115761200/embedIframeJs/uiconf_id/41338032/partner_id/1157612?iframeembed=true&playerId=kaltura_player&entry_id=1_m4ka8cia&flashvars[localizationCode]=en&amp;flashvars[sideBarContainer.plugin]=true&amp;flashvars[sideBarContainer.position]=left&amp;flashvars[sideBarContainer.clickToClose]=true&amp;flashvars[chapters.plugin]=true&amp;flashvars[chapters.layout]=vertical&amp;flashvars[chapters.thumbnailRotator]=false&amp;flashvars[streamSelector.plugin]=true&amp;flashvars[EmbedPlayer.SpinnerTarget]=videoHolder&amp;flashvars[dualScreen.plugin]=true&amp;flashvars[Kaltura.addCrossoriginToIframe]=true&amp;&wid=1_jv5tibva" width="608" height="402" allowfullscreen webkitallowfullscreen mozAllowFullScreen allow="autoplay *; fullscreen *; encrypted-media *" sandbox="allow-downloads allow-forms allow-same-origin allow-scripts allow-top-navigation allow-pointer-lock allow-popups allow-modals allow-orientation-lock allow-popups-to-escape-sandbox allow-presentation allow-top-navigation-by-user-activation" frameborder="0" title="W06 - DS Portfolio"></iframe>
```

### Using this template
1. __Git a ME Portfolio in GitHub (main page)__
    a. __Use the Portfolio Template on your GitHub root directory__
        * __Navigate to the [BYUI ME Portfolio](https://github.com/chaz-clark/ME-Portfolio) repo in GitHub.__
        * __Click the Green Button `Use this template` and select `Create a new repository`__  
        * __IMPORTANT: Click `include all branches` checkbox, this will include the `gh-pages` branch__  
        * __Select yourself as the `Owner`__  
        * __Name the repository as `username.github.io` where the username is your username on GitHub (Note: If the `username` part of the repository doesn’t exactly match your username, it won’t work, so make sure to get it right.)__
        * __Click the Green Button `Create repository`__  

    a.  __Clone the repository to your computer__
        * __Click the `<> Code` menu__
        * __Click the Green Button `<> Code` and select `Open with GitHub Desktop`__  
        * __Click the Button `Open in Visual Studio Code`__  


    a.  __Update the `_quarto.yml` file__
        * __Change the `title` to your name__
        * __Change the `repo-url` to your code repository url__
        * __Change the page-footer `left:` to your name__
        * __Change the page footer `href:` to your LinkedIn profile link__
        * __Scroll to the bottom and change the theme `light:` and/or `dark:` to another theme (optional)__  


    a.  __Push the changes to GitHub via GitHub Desktop__
        * __Make sure your current repo in the top left is `username.github.io`__  
        * __Type a commit message and click the Blue Button `Commit to main`__  
        * __Click the Blue Button `Push origin`__    


    a.  __Confirm the GitHub Actions are working__
        * __Navigate to the repo in GitHub and click on the  `Actions` tab__  
        * __Confirm the `Update _quarto.yml` is working by the yellow circle turning to a green check circle (Note: this can take 3-5min)__  