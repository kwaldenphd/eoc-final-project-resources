# Final Project: Assignment Prompt (Elements of Computing II)

<a href="http://creativecommons.org/licenses/by-nc/4.0/" rel="license"><img style="border-width: 0;" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" alt="Creative Commons License" /></a>
This tutorial was written by <a href="https://github.com/kwaldenphd">Katherine Walden</a> is licensed under a <a href="http://creativecommons.org/licenses/by-nc/4.0/" rel="license">Creative Commons Attribution-NonCommercial 4.0 International License</a>.

# Table of Contents

- [Assignment Prompt](#assignment-prompt)
- [Assignment Steps](#assignment-steps)
- [CSE Guide to the Honor Code](#cse-guide-to-the-honor-code)
- [Identify a Data Source](#identify-a-data-source)
- [Build a Data Model](#build-a-data-model)
- [Status Update](#status-update)
- [Shareout](#shareout)
- [Rubric](#rubric)

# Assignment Prompt

The final project for this course involves an open-ended data communication project built using Python. There is no one specific form this project must take. One of my goals for the final project is for you to have an opportunity to delve into and explore in greater depth an aspect of the course that interests you, while also having the opportunity to further develop skills you would like to hone. 

Successful final projects will include two main components:
- a well-documented, working Python program written in Jupyter Notebooks
- a written reflection (minimum 300 words) that documents how you approached the final project/what you wanted to accomplish via the final project, resources consulted, how you handled challenges you encountered, key takeaways, etc.
  * That reflection can come at the end of the Jupyter Notebook or be embedded throughout the Jupyter Notebook, if you want to approach authoring the notebook as a type of tutorial or "report".

Other components you could develop as part of the final project:
- Blog post with data analysis/visualization
- Research paper with data analysis/visualization
- Presentation that features slide deck with data analysis/visualization
- Infographics
- Research poster
- Interactive digital project (embedded plotly visualizations or Dash app)

The instructor will generally be open to final project ideas with a strong rationale and feasibility plan.

The wide range of possible project directions makes it hard to have a single overarching criteria in terms of project length/scope. So we’ll approach this in terms of the number of hours you should expect to spend working on the final project. 

Expect to spend at least 30 hours working on the final project. That includes brainstorming, meeting with instructor/TAs, in-class work time, etc. If you’re working on a project that is not going to take that much time, think about how to add complexity or take on another smaller scale project.

Contact the instructor with questions.

# Assignment Steps

We will move toward the final project in stages:
- [Identify a data source](#identify-a-data-source)
- [Build a data model](#build-a-data-model)
- Develop data visualizations
  * *NOTE: This work takes place during a series of labs on data visualization in Python with `matplotlib`, `seaborn`, `pandas`, and `plotly`*
- [Project status update](#status-update)
- [Project shareout](#shareout)
- All final project materials need to be submitted to the instructor by the date specified in the syllabus/on Canvas.

# CSE Guide to the Honor Code

[Click here](https://github.com/kwaldenphd/eoc-final-project-resources/blob/main/honor-code.md) to visit the "CSE Guide to the Honor Code" page that includes more details on how Notre Dame's Honor Code applies to your work in this project.

# Identify a Data Source

*NOTE: This assignment takes place around week #3 in the semester after a series of labs on JSON and CSV data structures and web APIs in Python.*

[Link to make a copy of a Google Doc template for this assignment](https://docs.google.com/document/d/1u3Xw4UnCDQHmNCZmz1Wd2Aykz4-05kIUa1ayyqzlcPc/copy)

Things to address in this post:
- Data source
  * Be as specific as possible, and include a URL/link to the data source you're thinking about working with.
  * If you're torn between different options (or are wanting to use data from multiple sources), provide details for both (and the current state of your thinking about what you might want to work with)
- Data context
  * What you're able to tell from the documentation about the background for data you're interested in working with
  * Who was involved in collecting it (people, organization, lab, etc)
  * Why it was collected
- Data content
  * Again, what you're able to tell from the documentation about information included in the data
  * Types of information, specific fields/data points, etc.
- Next steps
  * What you're interested in doing with this data, or what working with this data might enable you to do
  * Later in the semester, we'll talk in more concrete detail about ways to analyze/visualize structured data.
  * For now, think about the kinds of questions you're interested in asking of this data (comparison, contrast, relationships, change over time, etc) and how this data source might let you ask/answer those questions.
  * And the questions you're interested in asking of this data don't necessarily have to be framed as questions- at this point it's fine to be thinking more abstractly/conceptually about what aspects of this data interest you (and how/why)

Length guidelines:
- Written text (at least 300 words in length)
- Complete sentences are helpful, but bullet points or fragmented notes that address discrete components of the prompt are fine.

# Build a Data Model

*NOTE: This assignment takes place around week #7 in the semester after a series of labs on relational database systems and SQL.*

Templates:
- [Google Doc](https://docs.google.com/document/d/1TcSbSBSAojPUzkPGuUz2hAPOZpbywevZqGvOwAo70G4/copy)
- [Jupyter Notebook](https://colab.research.google.com/drive/1eStnEiSC6oTtCCixG0eTeqfJ67vYaMcC?usp=sharing)

## Data Format/Structure

- Format for the data source(s) you’re working with (API, CSV, JSON, etc)
- What it would look like to bring this data into Python, and any challenges/difficulties you anticipate
  * Data structure issues
  * Figuring out an API call
  * Data format issues
  * Bringing together multiple datasets
  * Needing to georeference location data (add latitude and longitude data)
  * Web scraping

- I encourage folks to start building out a Python program for this step
  * Get as far as you can bringing this data into Python (loading files, writing/storing an API call, etc)
  * If you have targeted questions about the Python workflow, code screenshots and/or Jupyter Notebook would be helpful

## Data Content

- Update and continue adding to your original notes on discrete types of data/information/measurements.
- We can start to think about this data in terms of the data types we’ve been working with in relational databases (string, float, integer), with an eye toward how that shapes what we’re able to do with this data in Python
  * Summary statistics, calculations, aggregations, etc.

## Data Model

- Spend some time building out an entity relationship diagram (ERD) for the data source(s) you’re planning to work with.
  * Remember an ERD is a conceptual model of information contained in a database- for the purposes of the final project, we’re thinking about the questions you are interested in asking of this data and a conceptual model of a data structure that would allow you to explore these questions

- We’re also going to get started on building out a relational schema (RS) diagram for the data source(s) you’re planning to work with.
  * Remember an RS is a logical model or representation of how data is organized or structured in a relational database. 
  * NOTE: You are not required to build or use a relational database for the final project. If you’re working with a single table, then just build out an RS diagram for that table.

- Additional Resources:
  * [Introduction to Relational Databases Lab](https://github.com/kwaldenphd/data-models) (has more details on ER diagrams and relational schema diagrams)
  * [Lucidchart, "The components and features of an ER diagram"](https://www.lucidchart.com/pages/er-diagrams#section_3)
  * [StackExchange, "ER vs database schema diagrams"](https://dba.stackexchange.com/questions/119380/er-vs-database-schema-diagrams)

- Tools:
  * Free generic drawing tools:
    * [Google Drawings](https://docs.google.com/drawings) *Google Drive tool*
    * [Microsoft Paint](https://www.microsoft.com/en-us/p/paint-3d/9nblggh5fv99) *Windows users*
    * [MacOS Paintbrush](https://paintbrush.sourceforge.io/) *Mac users*
  * Free online database-specific tools:
    * [ERDPlus](https://erdplus.com/)
    * [LucidChart](https://www.lucidchart.com/pages/?anonId=0.1c8414ae17e41a83751)
    * [Visual Paradigm Online](https://online.visual-paradigm.com/diagrams/solutions/free-erd-tool/)

## Next Steps

- Later in the semester, we'll talk in more concrete detail about ways to analyze/visualize structured data.

- For now, update and continue adding to your notes about the kinds of questions you're interested in asking of this data (comparison, contrast, relationships, change over time, etc) and how this data source might let you ask/answer those questions.

- Specific things to address/consider:
  * The degree to which the ERD you built for this data supports the work you want to do or the questions you want to ask
  * If there are gaps, what other types of data or data sources would you need to bring in conversation with the data you have now?
  * The degree to which the ERD and RS you built for this data supports the work you want to do or the questions you want to ask
  * Here we’re thinking about the current data structure/organization in the table and the degree to which that maps onto how you are wanting to interact with the data
  * If there are gaps, what are some of the changes or modifications that might need to happen with the data

## Length Guidelines and Required Components

- Written text (at least 200 words in length)
- Entity relationship diagram (ERD) and relational schema (RS) diagram
- Complete sentences are helpful, but bullet points or fragmented notes that address discrete components of the prompt are fine.
- Insert any needed ERDs or relational schema as images in the Google Doc or Jupyter Notebook

# Status Update

*NOTE: The status update typically is due 10 days before the assignment deadline and prior to the last week of class (when presentations/shareouts take place).*

Final project status update (due by the end of week specified on Canvas/the syllabus). 

Status update constitutes some kind of substantive project update communicated with the instructor. Addresses what you’re working on, how things are going in relation to the project plan, problems/questions/challenges you’re facing.

This update can come in via email, Slack, Canvas, or an appointment or office hours conversation.

# Shareout

*NOTE: Shareouts take place over two days (2 class meetings) during the last full week of classes.*

You have multiple options for a two minute lightning talk:
- Live presentation
- Pre-recorded video that’s screened during class time

The instructor will post slide deck links on Canvas in the weeks leading up to the shareouts. Add data, analysis, code, visualization, text, etc. to the slide with your name.
- One slide per person
- Two minute cutoff
- Q&A will happen in the #final-project Slack channel

Pre-recorded video resources:
- [Using Zoom to record a video presentation](https://otl.du.edu/knowledgebase/using-zoom-to-record-a-video-presentation/)
- [Using Panopto to record a video presentation](https://techdocs.blogs.brynmawr.edu/13504)
  * NOTE: These are not ND-specific resources, so folks will need to modify login urls, etc. 
    * [ND Zoom login](https://notredame.zoom.us/)
    * [ND Panopto login](https://panopto.nd.edu)

Google Slides Resources:
- [Add a video](https://support.google.com/docs/answer/97447?hl=en&co=GENIE.Platform%3DDesktop)
- [Add audio](https://www.howtogeek.com/757376/how-to-add-audio-to-google-slides/)
- [Add images](https://support.google.com/docs/answer/97447?hl=en&co=GENIE.Platform%3DDesktop)
- [Link a chart or table](https://support.google.com/docs/answer/7009814?hl=en&ref_topic=1361463)

# Rubric

[Click here](https://docs.google.com/document/d/1m5FqzQv9N6tELGBskXZgRqbNPu2zz1C8iTaf0w4r9qw/edit?usp=sharing) to access the final project rubric via Google Drive (ND users only).

[Click here](https://github.com/kwaldenphd/eoc-final-project-resources/blob/main/rubric.md) for a plain-text version of the final project rubric

# Return to Home

[Click here](https://github.com/kwaldenphd/eoc-final-project-resources) to return to the landing page for this repository.
