# This is how this repository is broken down.

### Folders
- _includes
  Anything in this folder can be pulled into your index page. 
- assets
    Generally anything that isn't pages that you want to include in your code- Image etc. This includes css
    - css
    This is where your css files go. CSS is what tells the website how to colour and shape your page. So you can change the look and feel of your webpage. I've included some in [here that we can look at](https://github.com/amandamiotto/Portfolio/blob/main/assets/css/sidebar_resume.css#L12) .
        One thing to note is I've pulled in the variable { { site.colour1 } } by using the double { brackets. This reads it from the _config.yml file we'll discuss next)


### Files

- HowIMadeThis.md
- LICENSE  
    (Talk to your IP person at your university for help on this. I've picked an open licence, you can find some info here [https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository#choosing-the-right-license](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository#choosing-the-right-license)
- README.md  
    This is the first page that'll come up at the base of https://github.com/amandamiotto/Portfolio
- _config.yml
    This contains all the variables used in the rest of the repository.
- index.md
    This contains the code to make the main content of the repository. Everything should link from here out.


**The two files we'll work with today are _config.yml and index.md** 

We can also add a new photo later by either uploading your own profile photo here: https://github.com/[Your name here]/Portfolio/tree/main/assets with the name "ProfilePhoto.JPG" OR uploading your photo into assets and including the name here: [https://github.com/amandamiotto/Portfolio/blob/main/_includes/sidebar.html#L7](https://github.com/amandamiotto/Portfolio/blob/main/_includes/sidebar.html#L7)


