# Week 6 - Design & Visual Rhetoric
*Do you distrust a website that looks old or poorly designed or sketchy? What does good design mean and why does it make us trust the information more? We'll learn some basic design principles for use on our websites, data visualizations, and digital essays.*


### Read for Tuesday: 
* [What Screens Want](https://frankchimero.com/blog/2013/what-screens-want/) - Chimero
* [The Interface as Discourse](https://journals.sagepub.com/doi/full/10.1177/1461444814520873) - Mel Stanfill, New Media & Society


## Tuesday, October 18, 2022
* icebreaker
* Activity 6.1 - 5 min paper. How do you relate to visual design? Think about the websites/apps you visit most. Setting aside the content, why do you return? Are the websites easy/hard to use? What makes them that way? Is there a style of website you prefer and why? What makes you trust a website?
* Reading discussion - let's unpack what's going on in these articles using the W&L website as an example. 
* Activity 6.2 - Your turn! Each table will be assigned a category of website (sports, shopping, etc). In the Boxnote in our class folder, address the following:
	* Where are the levels of abstraction? What activities/labor/problems/humans are there, represented by this website? (Chimero)
	* Where is the flux? What is changing on this website? Where is the interaction? (Chimero)
	* What are the functional affordances of the site? What can the site do? 
	* What are the cognitive affordances of the site? How do you know what it can do?
	* What are the sensory affordances of the site? What do you see/feel/hear?
	* Take a look at the site in the [Wayback Machine](http://web.archive.org/) or the [Web Design Museum](https://www.webdesignmuseum.org/timeline). How has the site changed over the years? Have the affordances changed? 
* Activity 6.3 - Let's do a little work on your website. Pairing up with someone at your table, look at each other's course website. What's working? What's not? What are the functional/cognitive/sensory affordances? Identify a short list of things to change. 
* Activity 6.4 - Code meet WordPess. Beyond the options provided to you in WordPress, how can you change your website using the HTML/CSS we learned earlier in class? 
	* In the admin screen for your WordPress site, navigate to Appearance > Customize. 
	* Check out all these settings and see what you might want to change! Your content shouuld be safe. 
	* Visit the `Additional CSS` screen. Remember our CSS from a few weeks ago? Write some here to change the style of your site. 
	* You might need to use the Inspect tool in your browser to figure out how to target the HTML element or CSS class you're trying to change. For example, I'm always annoyed at seeing the "Powered by WordPress" line on my site. By inspecting the page, I can see that that piece of text is in a `<div class="powered-by">` So I can write the following to hide it:
			`
		.powered-by {
			display:none;
		}
		` 




### Read for Thursday:
* [On Rational, Scientific, Objective Viewpoints from Mythical, Imaginary, Impossible Standpoints](https://data-feminism.mitpress.mit.edu/pub/5evfe9yd/release/5) - Data Feminism 
* [When the Designer Shows Up in the Design](https://www.propublica.org/article/when-the-designer-shows-up-in-the-design) - ProPublica
* [Design Ethos](https://yournamehere.scholarslab.org/design-ethos/) - Your Name Here Project
* [Accessible Design for Data Visualizations](https://www.youtube.com/watch?v=PfrtZeYmKkk) - Rachel Starry 


## Thursday, October 20, 2022
* icebreaker 
* preview future weeks
* readings discussion
* Activity 6.5 - Let's go back to your blog post #4 and reconsider your chosen data visualization. Is it well-designed? Is it accessible? 
* Activity 6.6 - Time to make our own data visualizations. We'll start with paper - what do you want to visualize? Setting aside the counting and the tech, what will your visualization look like? Let's start with the Coeducation report. [Here's a compiled version](https://wlu.app.box.com/file/1033106280115). 
    * Working in Excel, let's make a couple basic charts. 
    * First, we need to make a **PivotTable**. This creates a version of the data that be more easily summarized for the charts. 
        * Select all the columns in your spreadsheet.
        * Go to `Insert` then select `PivotTable`. 
        * Complete the wizard. You'll want to `add to new worksheet`. 
    * Let's make a basic bar graph that shows the breakdown of support for coeducation. 
        * First, add the `PivotChart` box to your sheet. It's in the middle of the Insert menu.
        * In the pane on the right called `PivotChart Fields`, select `opinion`. You should a count of all the opinions in a single bar. Sure okay, but not quite what we want. 
        * Drag the `opinion` field to the `Axis (Categories)` window. Now we see each category broken out on the X axis. Ta da! 
        * Can you figure out how to make this a pie chart? 
    * What about a stacked bar graph that shows both the opinion and who they wrote to? Try it first before reading the instructions.
        * Select the stacked column chart type. 
        * Add `opinion` to the `Values` box.
        * Add `opinion` to the `Axis (Categories)` box.
        * Add `addressee of letter` to the `Legend (Series)` box. 


## Week 6 Assignments - Due Tuesday at 12pm

### Blog post #6 - Website Genealogy

Let's practice applying *discursive interface analysis* to a website of your choosing. It doesn't have to be related to your project, but it would be helpful if it was! Address the following: 

* What are the functional affordances of the site? What can the site do? 
* What are the cognitive affordances of the site? How do you know what it can do?
* What are the sensory affordances of the site? What do you see/feel/hear?
* How do these affordances produce norms? What are the norms? 
* Look at the site in the [Wayback Machine](http://web.archive.org/) or the [Web Design Museum](https://www.webdesignmuseum.org/timeline). How has the site changed over the years? Have the affordances changed? Jump back as far as you can. 

**Specs:** 

* Create a WordPress post, turn in the link on Canvas.
* 300-500 words.
* Include 3-5 screenshots of the website from its current iteration and past versions. 
* Free from grammatical errors, typos.
* Credit and link out to sources when appropriate. I won't require that you use a certain citation style, but you should be in the habit of crediting sources and using in-text links. If you feel better about using a formal citation style, go for it!

### Activity log #6 

Continue practicing your data visualization skills. For this activity log, you can continue working with the Coeducation report OR the Oak Grove cemetery data OR both! The goal here is not to produce the perfect visualization, rather it's to work through and learn from the process. How do you take an idea and make it real? How do you learn a new piece of software? The [Data Viz Catalog](https://datavizcatalogue.com/) can be helpful in getting started. 

Create 2 new and different visualizations using Excel or Google Sheets. 

Create 1 visualization with a new data viz platform, such as [Raw Graphs](https://www.rawgraphs.io/), [Observable](https://observablehq.com/), [Flourish](https://flourish.studio/) or [Tableau Public](https://public.tableau.com/app/discover). 


**Specs:** 

* Create a WordPress post, turn in the link on Canvas.
* Embed or link to 3 data visualizations - 2 from Excel/Google Sheets and 1 from a new platform.
* Include captions and titles for your visualizations. 
* Within the possiblities of the software, make your visualizations as accessible as possible.
* Write 150-300 words on your experience crafting these visualizations. What was hard? What was easy? Are your visualizations accessible (give an example)? How would you improve your visualizations if you had more time? What help resources did you use along with the way? How might you *visceralize* your visualizations (have them emoke emotion over neutral information). 



