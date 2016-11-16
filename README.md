# Semantic HTML Portfolio

Welcome to the Semantic HTML Portfolio Project! For this project, we'll be converting a portfolio created using basic HTML tags (`div`, `span`, etc) to use HTML 5's more semantic tags.

Please follow the instructions below to complete the project. Be sure to run tests to make sure your tests are passing before submitting your code.

## Getting Started

To get started with this project, head over to the [Semantic HTML Portfolio](#) project on Code School, and begin!

To get setup locally, run the following commands:

```
npm install
npm start
```

## Tasks

Complete the following tasks to complete this project.

### Convert the Header

The element with a class of "header" isn't using the most semantic HTML tag it could be using. Switch it to use an element that most accurately wraps the header content for a page.

### Semantic Navigation

Our `.nav` element in the header of the page isn't using the most semantic HTML tags it could be using. `ul` is the correct one for this list of navigation items, but we should wrap this element with a more semantic element to indicate it is a navigation. Go ahead and add this.

### Create Sections

Each of the main content areas of our portfolio could be switched from using `div` tags to something that more accurately describes them as sections of our page. Update the `.tagline`, `.skills` and `.contact` sections to use a more semantic HTML tag.

### Main Content

Our 3 main sections make up the focus of our page. Wrap these three sections (tagline, skills and contact) in an HTML element that gives it the correct focus.

### Footer

Lastly, the element with a class of `footer` isn't the most semantic use of that area either. Luckily HTML 5 has a much better element we can use for footers. Update this element to use the semantically correct tag.

### What's Up Next

Now that your site is working, the next step would be to deploy it to production!

Putting this site up on GitHub pages is a bit different than some other projects because the code is all in the /src directory. There’s a nifty way to push this directory to a GitHub branch, which allows you to use GitHub pages with it! Try running this Git command for this project:

```unix
git subtree push --prefix src origin gh-pages

```
This is the correct result:

```unix
git push using:  origin gh-pages
Counting objects: 24, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (24/24), done.
Writing objects: 100% (24/24), 48.18 KiB | 0 bytes/s, done.
Total 24 (delta 7), reused 0 (delta 0)
remote: Resolving deltas: 100% (7/7), done.
To https://github.com/zamudpoe/SemanticHTMLPortfolioProject.git
 * [new branch]      350100aa32c81f0821f2faf3d12a6b8e28c89e16 -> gh-pages
 ```




This will push the src folder up to GitHub on the gh-pages branch. After that, you should be able to open up http://username.github.io/SemanticHTMLPortfolioProject , where ```username``` is your GitHub username.

I give to you my portfolio : [SemanticHTMLPortfolioProject]




[SemanticHTMLPortfolioProject]:(http://zamudpoe.github.io/SemanticHTMLPortfolioProject)
