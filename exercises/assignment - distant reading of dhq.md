# Assignment: Distant reading of a DH journal

## Rationale
In planning this class, I assume you're interested in the DSAM certificate as a way of pursuing interesting questions in your own varied fields of study – and not, necessarily, of becoming a Digital Humanist (TM), i.e. of deeply grounding yourself in the history of DH as a field of study per se.

Even so, I feel that historically one role of DSAM 3000, in its "seminar" designation, is to at least expose you to that field, so that you're not reinventing the wheel of digital methodologies or ignorant of critiques raised by digital studies.

As a compromise, in this assignment we will collectively work to apply a DH method to DH content: we will "distant read" the corpus of a Digital Humanities journal. In so doing, you'll be practicing several relevant skills:

* collaborating on a medium-scale project that requires working asynchronously in parallel with others
* building a textual study corpus that includes structured metadata
<!-- * transforming text using simple regular expressions in a plain-text editor -->
<!-- * checking on the project of in-development analytical tools using GitHub -->
<!-- * using documentation to run programs at the command line -->
* interpreting the outputs of textual concordancing, topic modeling, and related distant reading tools


## Step 1: Choose a target captaset

Because we are dependent on the number of people who are able to contribute to a distant reading project, and because the ease of capturing data in a context-sensitive way will vary, we always have to be flexible in terms of the scope of what we're scanning.

For the purposes of this project, in this class, I imagine that a few years of a single journal will be both small enough to complete and large enough to be worthwhile – in other words, we'll still save time doing the distant reading as compared to just normally reading the text of every article we include.

With that goal in mind, let's look at [Digital Humanities Quarterly](http://digitalhumanities.org:8081/dhq/) from 2019-2022, encompassing 16 issues (in four volumes) from 13.1 through 16.4.

## Step 2: Set up for collaboration

We'll use a Google Spreadsheet to both keep track of who's contributing what elements of our captaset and to house the capta themselves.

[Link to spreadsheet goes here]

<!-- IMPORTANT REALIZATION: distant-reader wants a directory of files -- including pdf files, at that -- not a spreadsheet of them, but it does allow you to add a spreadsheet of (fairly limited) metadata: file, author, title, date. See https://reader-toolbox.readthedocs.io/en/latest/commands.html#build for more specs.

THEREFORE we may want to save files to a shared folder, and write the filename in the spreadsheet, along with maybe the abstract, but leave the rest of the text out. ALTERNATIVELY we may want to just straight-up *skip* Distant Reader for this collaborative project (and update the goals above, accordingly), and instead pass URLs to Voyant to distant-read that way. We'd probably still want to build up some metadata of our own using the spreadsheet, which we can look at in OpenRefine while we're waiting for Voyant to do its thing.

After all, with distant-reader "the build process can take less than a minute to more than hour to complete." We can always look at it, should there be interest, using some of the sample datasets.
-->


### 2a. Clarifying methods and meanings
Notice that the spreadsheet has two tabs, or sheets: one will house the data, and the other will house a _data dictionary_, explaining what each of the columns (or _fields_) in the data represents.

### 2b. Sharing responsibility
One of those fields is `transcribed_by`. That means you! Go ahead and add your name in that column for two issues of your choice. This will help minimize duplication of labor while also spreading the workload.

### 2c. Procedural notes
First, I've set up the spreadsheet with only one row per issue, but each issue will actually contain multiple articles. **Before you enter information about a new article, first copy the row and insert a new one with the same shared journal, volume, issue, and transcribed_by values.** You may end up with one extra row at the end of your chosen issue; please delete the extra at that point.

In general, when you are setting up a spreadsheet like this in the future, you should think about what will stay the same across multiple rows (allowing you to group the data), and what will uniquely identify one and only one row.
