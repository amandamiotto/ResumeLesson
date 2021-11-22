
# Create your open CV

### Intro

We're going to use Github Pages to create a webpage so you can host your resume online.

First, make yourself a github account. If you use your edu.au account, you get free private repositories.
**Anything you put in a public repository or github pages is open to the world.**

Your website will always be called https://[YOUR USER NAME HERE].github.io/[REPOSITORY NAME]/  For example, my resume is at https://amandamiotto.github.io/Portfolio/.

This will show you your index page, or if you don't have an index page, your readme page. If you want to go to other pages, you add the name of the page at the end of the url. For example, this page, titled "HowIMadeThis" can be found at https://amandamiotto.github.io/Portfolio/HowIMadeThis . 

Hint: if you add the extension at the end of the url, you'll get the raw (unformatted) page instead (aka https://amandamiotto.github.io/Portfolio/HowIMadeThis**.md** )


### Github pages and how they work:

Github has integrated [Jekyll themes](https://github.com/topics/jekyll-theme) into its system to 'render' (aka make it work like a webpage). It has css to style it, and you can either pick from the predefined styles or use github themes.

You can either use HTML or something special called Markdown to style it. You may have seen Markdown before from systems like R Studio- Github has its own version but it is very very similar. You can find Github Markdown here [https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

Github will assume files that end in html should render in HTML, and pages that end in .md should be rendered with Github Markdown.


## Using this template to make your own


There's lots (and lots and lots) of much prettier templates on Github - you can search Github resume templates and see many that you can clone and alter for yourself. Hopefully this workshop helps you understand how the Github pages fit together.

Let's look at a [breakdown of this repostory](PartsOfThisRepo.md)

## If you were going to create a Github page yourself

Create a new repository.
Settings -> Pages -> Turn on Github pages
Leave it set as main->/root for the moment. When you start making more complex pages, you may want to turn this to a branch

## Parts of Github Pages

### Variables

You can either have 'Variables' as a global variable or a local variable. This means that if a variable is global, it is available for use on every page in your repository (repo). If a variable is local, it is defined and only available in that single page. Your global variables can be found in your _config.yml file on your repository . Jekyll has some more information here on [predefined and definable variables](https://jekyllrb.com/docs/front-matter/) . You can also check out this [Carpentry (beta - draft) lesson here](https://carpentries-incubator.github.io/jekyll-pages-novice/starting-jekyll/index.html).

### Themes

Github has premade themes that you can use as a basis here: Settings -> Pages -> Themes. 

### Include other pages into your main page

This can differ depending on what type of page you are using. If you have a Markdown page as your main Index page, you can include a html page using this:
    ~~~
    {% include sidebar.html %}
    ~~~







