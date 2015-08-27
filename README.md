#PrettyPress - An Octopress 2.0 theme

* ###Introduction


    This is a Material Designed Theme for Octopress 2 based on Bootstrap 3 and Material Design Guidelines by Google.
    ###[Demo](https://sonalkeshav.me)
    
* ###How to Install
    ```bash
    cd octopress
    git clone https://github.com/sonal-keshav/Material-Design-Octopress2.git
    rake install ['Material-Design-Octopress2']
    #If you are using ZSH, the above line would be changed to the following: rake install\[Material-Design-Octopress2\]
    rake generate
    ```

* ###How to configure
    Please have a look at the `Rakefile` & `_config.yml` files included in the theme.
    If you already have a theme installed, modify your config files. However, if you are starting fresh, I'd recommend you directly use the included files.
    
    ```bash
    cd octopress
    mv Rakefile Rakefile.bak
    cp .themes/Material-Design-Octopress2/Rakefile ./
    cp .themes/Material-Design-Octopress2/_config.yml ./
    ```
    
    You would also need to provide favicons. Have a look at `source/_includes/custom/head.html` to see the files necessary. All favicons would need to be stored in `/favicons/`
    
* ###Credits
    * [Octostrap3](https://github.com/kAworu/octostrap3)
    * [Bootstrap-Material-Design](https://github.com/FezVrasta/bootstrap-material-design)

* ###Pull requests are welcome!

* ###Future Release Features:
    * [ ] URL shortner integration with services like bit.ly
    * [x] ~~Add support for live tiles on Windows~~

* ###Bugs:
    * [ ] New page generation with `Rakefile` will result in an error (the new page will be generated but won't have all the necessary defaults)

* ###PRAISE DUARTE!!!
    ![Matias Duarte](https://i.imgur.com/OvnZeTr.jpg)
