This project aims to help you get started building your own personal portfolio page from scratch. 

# What is a Personal Portfolio Page?
A resume is a great way to get an overview of a potential employee's skills. However, a much more dynamic and deep way to introduce yourself, especially if you are a web developer, is with a personalized page that is both an example of your web development skills and a deeper picture of who you are as a person and a developer than a resume can be.

Landing interviews, especially for those having graduated from a coding boot camp with no real industry experience and without a 4-year Computer Science degree, a hand-crafted portfolio can mean the difference between getting a phone call for a tech screen and being skipped over.

A portfolio page should be custom to your interests and be an example of the kind of code that you'd prefer to be writing professionally. More of a front-end dev? Focus heavily on CSS and styling. More of a back-end dev? Write more JavaScript and give some examples of what you're capable of. Want a job using React or Angular? Use the framework in your portfolio and show how clean your code is and how well you know the framework.

# Getting Started
The files in this project are intentionally small. They are the very basics of a skeleton that you can use to create your own portfolio page. 

Here's how to do it

1. Fork the Repo. Or clone it locally, rename it, and upload it all. Cultiv8 claims zero copyright on this project, so use it however you'd like.
2. Update the HTML to reflect yourself. 
    - Fill in the "About" section. Be as long-winded or as short as you usually are
	- Add URLs for your GitHub profile and LinkedIn account (and make sure they work)
	- Add some new sections that you think will be useful or that you want to share (some ideas: "Personal Interests", "Technologies", "Work History"...)
	- Add some basic styling: a color scheme
3. Come back to the page for a few hours at a time and pick some topics from the "List of Potential Updates" section below.

# Hosting Your Portfolio
GitHub will host your portfolio for free. [GitHub Pages](http://github.com/pages) allows the creation of a full HTML/CSS/JavaScript page per user and per project hosted on GitHub. With this, you are able to create a site hosted at http://<your_github_username>.github.io.


# Update Your Portfolio and Make it Your Own 
Now that you have a very basic portfolio, make it your own by exploring different tools and techniques and incorporating the ones you think are most useful into your own profile. 

Make sure that you understand how each of the additions works. I highly recommend that if you decide to use a library that you fully code review that library and understand how it works. These can be great discussion points in an interview.

Be careful not to add too many features just for the sake of adding features. These are just some ideas. Using them all would likely result in an unweildy, busy, mess of a page. Pick and choose according to your tastes and be careful not to overdo it. Often, simpler is better.

We plan to include links of the following types for each of the suggested features below:
1. Links to recommended articles or blog posts that explain the feature and how it works from a developer's perspective
2. Links to frameworks and libraries that implement the feature.
3. Good examples of how the feature has been put to use on other pages. 

*Until there are links for each suggested feature, we have faith that you can perform a web search to learn more about each suggestion. If you find any good links that you'd like to have included here, please post them on the Cultiv8 Slack team instance.*

## List of Required Updates
This group of items should be done for every portfolio. They should not be considered optional.

### Navigation
Add a &lt;nav&gt; block to your page to help visitors navigate to the different sections of your page.

### Favicon
The icon in your browser tab next to the page title gets there by declaring the web page's "favicon". There's one created for the template, but it is intentionally horrible so that you are further incentivized to create your own.

### Adaptive/Responsive Layout
While you are almost certainly developing your portfolio page while using a computer with a desktop-sized monitor, most browsing these days is done on mobile devices. Certainly, any development team looking at your profile will resize their browser windown to verify that you have paid attention to what happens when your page is resized or viewed on a mobile device. 

The techniques used in "Adaptive" and "Responsive" pages are technically slightly different, but most developers call the entire set of techniques "Responsive Web Design". If you're going to be a front-end developer, understanding the differences and which techniques go with which moniker would be useful knowledge to have.

## List of Optional Updates
### Frameworks
Consider adding Bootstrap, React, Angular, or other front-end frameworks. Most sites on the web use one or more frameworks. Overall, we would recommend hand-coding all of your site yourself if you are a web developer. However, there is a strong argument that in the "real world" you'll seldom be asked or even want to reinvent the wheel. You'll need to make your own decision. If you do decide to add a framework, make sure you understand all of the functionality you take advantage of from the framework and can talk about it in an interview.

### SVG Images
PNGs are "raster" images, which store their contents as a matrix of pixels. This can be problematic on high resolution displays. Vector-based images can fix this problem and allow scaling of images to any size with crisp edges by defining the image as a series of mathematical functions. SVG is an XML-based format that allows for this. (*Note: SVGs are not good for photographic images; use JPGs for those.*) Investigate SVGs and incorporate some into your design: maybe as project icons.

#### SVG Animations and CSS with SVG
Because SVGs are XML, you can target pieces of them with CSS and animate them. 

### Icon Fonts
While your portfolio likely doesn't have enough icons on it to require an Icon Font, knowing how to create and use icon fonts is a great skill to master.

### Menus
If your portfolio grows, you may want a menu 

### Auto-Scrolling
If you present your portfolio as a single page, your menu links may simply scroll the page to the corresponding anchor. Consider doing this with scrolling animations.

### Auto-Hiding Content
Instead of a single page that scrolls, you could implement the functionality as a carousel or a single-page app where the content of a menu item appears or expands as the current page disappears or collapses. You could mix both by having your profile be a single page that hosts a list of projects in an accordion control. Have fun with it!

### CSS Animations and Transitions
CSS Animations are pretty cool, and most browsers are able to take advantage of GPUs to render most CSS animations, which makes them much less processor-intensive than they would be using JavaScript to alter them. 

Note that overdoing animations can result in a page that is very busy and not very pleasing. Usually small, subtle uses are best.

Like CSS Animations, CSS Transitions can be overdone. But subtly updating items over a short amount of time time in response to a click or hover can add a classy touch.

### Parallax Scrolling
Parallax scrolling offers a subtle and classy effect to many pages. 

### Tooltips
Tooltips are blocks of text that appear on click to give more context or some aside content (hint: the HTML5 &lt;aside&gt; tag is your friend here). There's probably not a lot of reason to use Tooltips on a portfolio page, but if you have any aside content, they can be a fun addition.

### Header/Footer
The basic portfolio template has no header or footer. Feel free to add your own. Decide whether they should scroll with the page or be fixed in place.


### Get Inspired!
Check out https://codepen.io/ for a ton of great ideas. **DO NOT** copy any of them directly to your page. Review them thoroughly to understand how they work then reimplement them yourself to ensure that you understand it deeply. Also, it's always a nice thing to provide links to your inspiration in a comment in your code or on the public-facing HTML itself. 