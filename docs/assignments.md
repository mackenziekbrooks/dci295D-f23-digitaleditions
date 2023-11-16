## Reading/Writing/Thinking Responses

Each week you'll write a 300-500 word post in response to a prompt. Prompts will invite you to dig deeper into readings, discussion topics, or your own experiences. These posts aren't meant to be busy work, rather they're a chance for you to practice thinking critically and analyzing information. They help me know what you're thinking and *how* you're thinking. Plus, I know that talking a lot in class isn't for everyone. Think of these posts as an extension of your participation. You don't have to know all the answers, just be thoughtful in your questions! 

**General specifications:**

* Turn in your post on Canvas. 
* Due Thursdays by noon (12pm). Posts will be in response to the readings and discussion we have on Tuesdays. 
* 300-500 words.
* Free from grammatical errors, typos. 
* Credit and link out to sources when appropriate. I won't require that you use a certain citation style, but you should be in the habit of crediting sources and using in-text links. If you feel better about using a formal citation style, go for it! 

## Coding Activity Log

Each week (usually Thursday) we’ll learn a new technology or coding skill together in class. The activity log will document the ways you practice and build that skill on your own. Logs will be submitted in Canvas and later on GitHub. These skills will help you complete the final project, but they'll also serve you well in future encounters with the internet and can go on your resume.

**Specifications:**

* Turn in on Canvas. Some assignments might be uploaded to GitHub, so check the individual assignment.
* Activities might include writing code AND some writing about your process. Think: show your work in math.


## Digital Edition Project

Our big project for this course is the creation of a website for publishing digital editions of documents held by Leyburn Library's Special Collections and Archives. This is exciting! You are helping make these documents available to the wider world when they otherwise would stay inaccessible or hard to find. Not only that, part of your job is to add valuable scholarly commentary to the texts so they are updated with the latest research and understanding. 

Specifically, we'll be encoding articles from the Proceedings of the Rockbridge Historical Society. Each student will select one article after an exploration and proposal process. You'll be responsible for encoding that article in TEI XML. You will research the subject of the article and write annotations that add context and images or point to updated research or other resources in Special Collections and Archives. 

To accomplish this, we'll break the project down into a number of parts. Each of these components will count in the Digital Edition Project category for our [Specs Grading System](grading.md). 

### Proposal

Time to figure out which article you'd like to work on for your project. There are many topics to choose from! You should select something that is of interest to you - maybe it's the location, the people involved, or the content it's covering. Shorter articles will not necessarily be easier. You should browse the Proceedings in print or [online](https://wlu.app.box.com/folder/223091696832) and use the [Table of Contents spreadsheet](https://wlu.app.box.com/file/1289009716733) (data entry by Margaret Alexander) or the index. Be sure to completely read your article before you make your selection. Don't worry about the tech part of this project, we're still learning those skills. Focus on the content of the article and the questions that it raises.

**Specs:**

* Due October 19th at noon. 
* Turn in on Canvas. 
* 400-500 words.
* Free from grammatical errors, typos. Include links/citations as necessary.
* Address the following: 
	* Why this article? What struck you? What was your process of elimination like? What is going to be interesting/challenging/unique about this article?
	* Using our document analysis skills, what do you notice? What features will need to be marked up? 
	* Do some cursory Googling or library research. Can you find more about the place/people/events described? Are there related articles in the Proceedings already? Include a list of 5 or more sources that will be your initial starting place when conducting research. 
	* Provide some initial comments on potential comments/annotations. What's confusing to you? What needs more explanation? Is there language that needs to be updated? 

### Annotated Bibliography

This project is going to require some deep research. Heads-up! Some of your sources may not be available on the internet, but only in Special Collections or in the stacks. This assignment is designed to get you digging for sources and reflecting on their use in your project. Rely on our research workshop day for places to conduct this research. It may be that some of the sources in your annotated bibliography are the ones in your article. But you may also want to find other sources to verify the statements in the article. 

You should plan to use:

* the [Library Catalog](https://library.wlu.edu/)
* [ArchivesSpace](https://archivesspace.wlu.edu/)
* [Digital Repository](https://dspace.wlu.edu/)
* [Google Scholar](http://scholar.google.com/)
* Some of our [databases](https://libguides.wlu.edu/az/databases)
* The internet/Wikipedia 

**Specs:**

* Due October 31 at noon.
* Turn in on Canvas.
* Include 8-10 sources. 4+ must be *primary sources* and 4+ should be *secondary sources*. 
* Each source should be formatted in an established citation style (probably Chicago?). Use [Zotero](http://library.wlu.edu/zotero) if it helps! 
* Under each source should be a 2 sentence annotation. In the first sentence, summarize the source. In the second sentence, say something about why this source is useful for your project. 


### teiHeader Markup

An essential piece of your project is completing the `<teiHeader` part of your digital edition. This section of the XML contains all the *metadata* (my favorite!) about your article - including information about you, the encoder! You'll want to follow the [TEI guidelines](https://tei-c.org/release/doc/tei-p5-doc/en/html/HD.html) so that there is some consistency across articles and everything displays correctly. We'll work together in class to come up with our project's way of entering data. 

**Specs:**

* Due November 7 at noon.
* Turn in link on Canvas.
* Your XML should be well formed, properly nested and structured. The teiHeader insists on a specific order for fields, so you should follow the examples. 
* You must fill out the following sections according to our project guidelines:
	* `teiHeader`
	* `titleStmt`
	* `respStmt`
	* `editionStmt`
	* `publicationStmt`
	* `notesStmt`
	* `sourceDesc`
	* `encodingDesc`
	* `revisionDesc`

### TEI Body Markup

This is the core part of your digital edition! Time to markup the body of the text. This section of the XML contains all the actual text from your article as it appears on the page. While you can copy the text from the `.pdf` or `.txt` files, you should be diligent about checking for OCR errors. While each article will have its unique requirements, the markup should still conform to the TEI guidelines and any decisions we make in class. 

**Specs:**

* Due November 14 at noon.
* Upload to GitHub, turn in link on Canvas.
* Your markup should address:
	* [Paragraphs](https://tei-c.org/release/doc/tei-p5-doc/en/html/CO.html#COPA) and any other [text divisions](https://tei-c.org/release/doc/tei-p5-doc/en/html/DS.html#DSDIV), sections, headings, etc.
	* [Highlighting and quotation](https://tei-c.org/release/doc/tei-p5-doc/en/html/CO.html#COHQ)
	* [Simple editorial changes](https://tei-c.org/release/doc/tei-p5-doc/en/html/CO.html#COED)
	* [Notes](https://tei-c.org/release/doc/tei-p5-doc/en/html/CO.html#CONO) while your editorial notes are not due yet, some of you may have to incorporate original notes from the authors.
	* [Names, Dates, People, and Places](https://tei-c.org/release/doc/tei-p5-doc/en/html/ND.html)


### Annotations 

The annotations of your digital edition is what sets it apart as a scholarly project. They are the point where you, the scholar and encoder, can chime with your own observations, updates, expertise, links, etc. They leverage the hypertext potential of the internet - a kicking off point for research rabbit holes. You should plan to craft 8-10 quality annotations that expand on aspects of your chosen article. 

Potential annotations could be:

* links to relevant collections in [ArchivesSpace](https://www.archivesspace.wlu.edu/)
* links to digital images of documents references, likely from [DSpace](https://dspace.wlu.edu/) or other newspaper databases or digital libraries
* explanation of comment/references made by the author. You were new to this article just a few weeks ago! What did you have to look up? 
* more biographical information about individuals, including links to obituaries or Find a Grave. 
* update to information that is dated! These articles are 10+ years old, some up to 50! What has happened since then? 
* Questions or gaps in information. You can indicate that some piece of information is not accessible. 
* Links to other publications by RHS, W&L, or other local organizations. 
* FYI you can make any of your tags a link by including the ref attribute. Example: `<persName ref="http://www.google.com">`

**Specs:**

* List of potential annotations due November 30 at noon. You should identify at least 10 different types of things that could become annotations. 
* Final annotations due December 7 at noon.
* Upload to GitHub, turn in link on Canvas.
* 8-10 annotations. 
* Annotations can and should vary in length. At least two should be multiple sentences in length.
* Annotations can and should vary in content. They could link out to other sources or media. 

### Reflection 

No project is complete without time taken to reflect on its successes and lessons learned. Talk about your feelings! What have you learned about digital editions and DCI more broadly? What have you learned about yourself and the way you learn new things?

**Specs:**

* Due December 15 at noon.
* Submit as a document in Canvas.
* 500-1000 words.
* Address the following. Your answers should be about the course as a whole, not just your digital edition.	
	* What have you learned? Which of these things is most important to you? What did you learn about the material that you didn't expect? What did you learn about yourself?
    * How can you apply the tech and research skills you learned in this course to future courses or non-academic endeavors?
    * What has been challenging? Why?
    * Revisit the objectives for this course. Did we address those objectives?
    * If you could do it all again, what would you do differently?
    

 



