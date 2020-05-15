# The Speaker-conditional Chain model

In this work, we raise a common strategy named 
Speaker-Conditional Chain Model (SCCM) to process complex speech recordings. 

Our model first infers the identities of variable numbers of speakers from the observation based on a sequence-to-sequence model. Then, it takes the information from the inferred speakers as conditions to extract their speech sources. With the predicted speaker information from whole observation, our model is helpful to solve the problem of conventional speech separation and speaker extraction for multi-round long recordings.


## Basic Introduction Demo 

Please see the introduction Video with this link:
https://drive.google.com/open?id=1B4K4BhqAwxWkZP_LY98epjZ9asqIxkaU

To use the Cayman theme:

1. Add the following to your site's `_config.yml`:

    ```yml
    theme: jekyll-theme-cayman
    ```

2. Optionally, if you'd like to preview your site on your computer, add the following to your site's `Gemfile`:

    ```ruby
    gem "github-pages", group: :jekyll_plugins
    ```


