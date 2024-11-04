
# Week 10: Exploration, Slicing, Cleaning
<span class="date">November 4, 2024</span>

<section class="prereqs">
    <details><summary><strong>Texts to have read / watched</strong></summary>
        <ul>
          <li>Gradek, Bob, and Liz Monk. “Dataset Summaries: Pivot Tables.” vimeo, 2022. <a href="https://vimeo.com/703773939">https://vimeo.com/703773939</a>.</li>
          <li>van Hooland, Seth, Ruben Verborgh, and Max De Wilde. “Cleaning Data with OpenRefine.” <em>Programming Historian</em>, Aug. 2013. <a href="https://programminghistorian.org/en/lessons/cleaning-data-with-openrefine">https://programminghistorian.org/en/lessons/cleaning-data-with-openrefine</a>.</li>
          <li>Cairo, Alberto. “6: Exploring Data with Simple Charts.” The Truthful Art: Data, Charts, and Maps for Communication, New Riders, 2016. learning.oreilly.com, <a href="https://learning.oreilly.com/library/view/the-truthful-art/9780133440492/ch06.html">https://learning.oreilly.com/library/view/the-truthful-art/9780133440492/ch06.html</a>.</li>
          <li>D’Ignazio, Catherine, and Lauren F. Klein. “5: Unicorns, Janitors, Ninjas, Wizards, and Rock Stars.” <em>Data Feminism</em>, MIT Press, 2020, pp. 125–48. <a href="https://ebookcentral.proquest.com/lib/pitt-ebooks/reader.action?docID=6120950&amp;ppg=138">https://ebookcentral.proquest.com/lib/pitt-ebooks/reader.action?docID=6120950&amp;ppg=138</a>.</li>
        </ul>
    </details>
    <details><summary><strong>Writing to turn in</strong></summary>
        <ul>
            <li>a <a href="{{site.repo_url}}/discussions/8">discussion forum</a> post in response to the readings</li>
            <li>Download <a href="https://openrefine.org/">OpenRefine</a>.</li>
        </ul>
    </details>
</section>

## Plan for the day:

* [First half](#first-half): Let's practice!
    - Pivot Tables and Trees (~20 min)
    - Mass editing with OpenRefine (~20 min)
    - EXT: Studio
* Break (10 minutes, around 10:20)
* [Second half](#second-half): Let's discuss!
    - Discussion: Questions, comments, connections
    - Grok writing (around 11:25)
    - Sharing (around 11:35)

* [Homework for next time](#hw): Data visualization


## First half: Let's practice! {#first-half}

I have a confession to make: I deliberately withheld some context. That video was created as part of a seminar on Information Ecosystems, and is meant to be just part one of an [activity series structured as Watch -> Do -> Explore](https://infoeco.hcommons.org/infoecocookbook/cookbook-modules/pivot-tables/).

**In a minute, I'm going to ask you work in groups of two or three on the "Do" activity**, which will have you applying the lessons of the video to a new dataset (this time, it's City of Pittsburgh Trees). Let's start off all together until we've found the instructions and the data from WPRDC, because it's changed slightly and might be easier to miss than the instructions expect. Then I'll set you loose to practice.




### Counting trees with pivot tables

Got the instructions? Got the data? Okay, go ahead and get started. Make sure at least one person in your group has access to a full spreadsheet program (either Excel or Google Sheets should work here), i.e. not just a tablet.

EXT: Go on to your choice of the "Explore" activities.

After about 15 minutes, let's talk through these questions:

1. Which Pittsburgh neighborhood has the most trees in general? Why do you think this is? What has the least?

2. Did all the groups get the same answer about where a squirrel could find the most food-bearing trees? Did you expect us to? Why or why not? What does that tell us about working with data in general?


### Mass editing with OpenRefine

Time for some OpenRefine, another data exploration and processing tool I'd asked you to install for today.

<div class="alert alert-info"><p>NB: This software is safe, even though it doesn't come from the Mac Store. Instead of double-clicking, right-click the OpenRefine app and choose Open. On Windows, you may be able to click More Info and then Install anyway.</p><p>Windows users, you also have to Extract All rather than trying to load from the compressed folder. You'll know it's working if you see “127.0.0.1” or “localhost” in the address bar.</p></div>

Did anyone work through the exercises in [the tutorial](https://programminghistorian.org/en/lessons/cleaning-data-with-openrefine)?

Any challenges?


Did anyone notice that the URL structure in that dataset has changed? Let's see if we can fix it.


Questions:

1. _After processing_, do your source materials look something like the Powerhouse Museum dataset? Like the trees dataset? Or like something else? Do you see a use for the tools we've practiced today?

2. How might you use facets to explore or better understand data, not just clean it? How do facets interact with filters?


### EXT: Studio

Finished with all the above? Use the remaining time to work on your project.


### Time check

* If it's already _after 10:15_, let's take a break here to allow for discussion.
* If it's _before 10:00_, choose one of the following:
    1. Apply these lessons to your own processed source material
    2. Back in groups, do one of the "Explore" activities (PGH 311 requests or dog licenses) – ideally using OpenRefine at least once.
*  And if it's _between 10 and 10:15_, let's make sure you know how to get data *out*.


<!-- <div class="alert alert-info">
    <p>A key takeaway: <strong>Categorical variables are fundamentally</strong> <em><strong>ways to slice or subset your data.</strong></em></p>
    <p>You can <strong>filter to one value</strong> within a category as a way of making an otherwise overwhelming dataset manageable: e.g. to look at just pothole requests, or just garbage collection, rather than all of the hundreds of types of requests in the 311 database.</p>
    <p>You can <strong>group across multiple values</strong> within a category to see how other variables change when summarized within these groups: e.g. to see how tree counts vary by neighborhood, you first aggregate the tree counts for each neighborhood value.</p>
    <p>By combining those approaches, you can zoom in on the questions that really matter &ndash; and the answers you're able to communicate.</p>
</div> -->

## Break (10 minutes)
I'm guessing we'll hit the break at around 10:20 or so. Try to be back for a 10:30 start, so we have a full hour to get into the readings.

## Second half: Discussion {#second-half}

What's coming up for you? Questions, comments, confusions, connections? Skim your notes and remind yourself what's in there.

<details><summary>Starting points, if we need them</summary>
    <ul>
        <li>Yi had asked about D'Ignazio and Klein's idea of <em>reflexivity</em> – "disclosing your project's methods, your decisions, and [...] your own positionalities" (D'Ignazio and Klein 136) – and whether it can replace "traditional scientific objectivity" ... or whether valuing such transparency is in conflict with valuing privacy.</li>
        <li>Brenda found Cairo's chapter on data exploration eye-opening, especially in offering a set of humanistic rationales for data-science operations using something like R or Python. She connects this with questions of pedagogy, especially outside of the academy.</li>
        <li>Nick floated a number of observations that to my mind felt question-adjacent, or question-implying: e.g. a pedagogical / media question: does a video that "somebody had an incredible amount of fun making" help alleviate technophobias around tools like Excel or massive data portals like NYC Open Data? e.g. Who decides what data to include in a massive portal, and why did squirrels make the cut? etc.</li>
    </ul>
</details>

Let's discuss! We can take notes at [bit.ly/dsam{{site.course.slugterm}}-notes](https://bit.ly/dsam{{site.course.slugterm}}-notes).


If we get to grok-writing by around 11:25, that should give us enough time to share and still introduce the new homework.


### Grok writing

<div class="alert alert-success">
    Spend some time putting marks on a page to help you think through, and consolidate for yourself, what we discussed today. What do you want to remember? What are you left wondering?
</div>

After a few minutes, I'll ask everyone to share one thing, to which the only response will be "thank you."





## Homework for next time {#hw}

As always, continue working on your project, and take notes in your [Mindful Practice Journal](projects.md).

I'll also ask you to **[add your thoughts to the discussion forum]({{site.repo_url}}/discussions) after reading**.

In preparation for <a title="required reading: 69 page-equivalents; EXT reading adds 22 for a total of 91">week 12, on visualizing data</a>, please read:

* Cairo, Alberto. _The Truthful Art: Data, Charts, and Maps for Communication_, New Riders, 2016
    - “3: The Truth Continuum.” [https://learning.oreilly.com/library/view/the-truthful-art/9780133440492/ch03.html](https://learning.oreilly.com/library/view/the-truthful-art/9780133440492/ch03.html).
    - “5: Basic Principles of Visualization.” [https://learning.oreilly.com/library/view/the-truthful-art/9780133440492/ch05.html](https://learning.oreilly.com/library/view/the-truthful-art/9780133440492/ch05.html).
* D’Ignazio, Catherine, and Lauren F. Klein. “Chapter Six: The Numbers Don’t Speak for Themselves.” _Data Feminism_, MIT Press, 2020, pp. 149–72. mitpressonpubpub.mitpress.mit.edu, [https://ebookcentral.proquest.com/lib/pitt-ebooks/detail.action?docID=6120950](https://ebookcentral.proquest.com/lib/pitt-ebooks/detail.action?docID=6120950).
* _selections from_ [Datawrapper Academy](https://academy.datawrapper.de/): the documentation center for [Datawrapper](https://datawrapper.de), one of my go-to tools for visually presenting data once I know what I want it to say. The following list of starting points may look like a lot, but each article is quite short – and the first and third are especially important, as well as relevant beyond that specific tool.
    - "Our Explanatory Approach to Visualizing Data." 31 Aug. 2020, [https://academy.datawrapper.de/article/279-our-explanatory-approach](https://academy.datawrapper.de/article/279-our-explanatory-approach).
    - "How to Create Your First Datawrapper Chart." 24 Oct. 2023, [https://academy.datawrapper.de/article/245-how-to-create-your-first-datawrapper-chart](https://academy.datawrapper.de/article/245-how-to-create-your-first-datawrapper-chart).
    - "How to Prepare Your Data for Datawrapper in Excel or Google Sheets." 13 June 2022, [https://academy.datawrapper.de/article/240-how-to-prepare-your-data-for-datawrapper-in-excel-or-google-sheets](https://academy.datawrapper.de/article/240-how-to-prepare-your-data-for-datawrapper-in-excel-or-google-sheets).
    - "How to Create a Dot Plot." 24 June 2020, [https://academy.datawrapper.de/article/122-how-to-create-a-dot-plot](https://academy.datawrapper.de/article/122-how-to-create-a-dot-plot).
    - "How to Create a Locator Map." 11 June 2021, [https://academy.datawrapper.de/article/161-how-to-create-a-locator-map](https://academy.datawrapper.de/article/161-how-to-create-a-locator-map).
    - "What to Consider When Creating Pie Charts." 4 Jan. 2021, [https://academy.datawrapper.de/article/127-what-to-consider-when-creating-a-pie-chart](https://academy.datawrapper.de/article/127-what-to-consider-when-creating-a-pie-chart).


* EXTs for eager readers
    - Drucker, Johanna. “Humanities Approaches to Graphical Display.” _Digital Humanities Quarterly_, vol. 005, no. 1, Mar. 2011, [https://digitalhumanities.org/dhq/vol/5/1/000091/000091.html](https://digitalhumanities.org/dhq/vol/5/1/000091/000091.html).
        * Famous-in-field for proposing "capta" rather than "data" as the term we ought to use, since information is usually more taken than given, this is also a meditation on what graphs' usual conventions get wrong – or, at least, tend to oversimplify.
    - Few, Stephen. _Show Me the Numbers: Designing Tables and Graphs to Enlighten_. Second edition, Analytics Press, 2012.
        * A bit of a tome, this beautiful hardcover-only book is a practical deep dive into how to design data representations for _rapid communication of core ideas_. It's written with a business audience in mind, but very relevant for academics. If you want to know the normative framework that D'Ignazio and Klein (and especially Drucker) are seeking to expand beyond, this is one of the best books I've read to explain it. My attempted scans didn't come out, or I'd be assigning some chapters this week.
    - You might also read around more in [Datawrapper Academy](https://academy.datawrapper.de/), especialy if something strikes your eye.
