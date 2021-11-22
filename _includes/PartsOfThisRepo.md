# This is how this repository is broken down.

### Folders
- _includes
    Anything in this folder can be pulled into your index page. 
- assets
    Generally anything that isn't pages that you want to include in your code- Image etc. This includes css
    - css
        This is where your css files go. CSS is what tells the website how to colour and shape your page. So you can change the look and feel of your webpage. I've included some in [here that we can look at](https://github.com/amandamiotto/Portfolio/blob/main/assets/css/sidebar_resume.css#L12) .
        One thing to note is I've pulled in the variable `{{ site.colour1 }}` by using the double { brackets. This reads it from the _config.yml file we'll discuss next)
