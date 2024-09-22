
# Week 4: Data: By whom? For what?
<span class="date">September 16, 2024</span>

<section class="prereqs">
    <details><summary><strong>Texts to have read / watched</strong></summary>
        <ul>
            <li>D’Ignazio, Catherine, and Lauren F. Klein. <em>Data Feminism</em>, MIT Press, 2020. ProQuest Ebook Central, <a href="http://ebookcentral.proquest.com/lib/pitt-ebooks/detail.action?docID=6120950">http://ebookcentral.proquest.com/lib/pitt-ebooks/detail.action?docID=6120950</a>.<ul>
                <li>“Introduction: Why Data Science Needs Feminism.” pp. 1–19.</li>
                <li>"4. 'What Gets Counted Counts.' " pp. 97-124.</li>
                </ul>
            </li>
            <li>Onuoha, Mimi. On Missing Data Sets. 2016. 16 July 2024. GitHub, <a href="https://github.com/MimiOnuoha/missing-datasets">https://github.com/MimiOnuoha/missing-datasets</a>.</li>
            <li>Schöch, Christof. “Big? Smart? Clean? Messy? Data in the Humanities.” <em>Journal of Digital Humanities</em>, Nov. 2013, <a href="https://journalofdigitalhumanities.org/2-3/big-smart-clean-messy-data-in-the-humanities/">https://journalofdigitalhumanities.org/2-3/big-smart-clean-messy-data-in-the-humanities/</a>.</li>
            <li>Ghorayshi, Azeen. “No One Knows How Many L.G.B.T.Q. Americans Die by Suicide.” <em>The New York Times</em>, 1 June 2023. NYTimes.com, <a href="https://www.nytimes.com/2023/06/01/health/lgbtq-suicide-data.html">https://www.nytimes.com/2023/06/01/health/lgbtq-suicide-data.html</a>.</li>
            <li>Brown, AmyJo. “Building Your Own Data Set: A Journalist’s Approach.” <em>What Are Digital Humanities?</em>, 11 Nov. 2022, <a href="https://cmu-lib.github.io/dhlg/project-videos/brown/">https://cmu-lib.github.io/dhlg/project-videos/brown/</a>.</li>
        </ul>
    </details>
    <details><summary><strong>Writing to turn in</strong></summary>
        <ul><li>a brief post to the <a href="{{site.repo_url}}/discussions/3">discussion forum</a></li></ul>
    </details>
</section>

## Plan for the day:

* [First half](#first-half): Let's discuss!
    - Warm-up writing: terms, tensions, takeaways
    - Questions, confusions, connections
    - Grok writing (around 10:20)
    - Sharing (around 10:30)
* [Second half](#second-half): Let's practice!
    - Loop writing: from sources to data?
    - Using/planning data structures
    - Your turn!
    - HW preview: What's in a presentation?


* [Homework for next time](#hw):
    - Present your project's first iteration


<figure>
    <img alt="data: is or are? depends on the underlying construct." src="http://www.phdcomics.com/comics/archive/phd080715s.gif">
    <div class="sr-only">Transcript of comic, which has four panels. Panel 1: Person A asks, "Do you write 'the data is...' or 'the data are...'? Is it singular or plural?" Panel 2: Person B responds, "That is a deep philosophical question, actually." Panel 3: Person B continues: "It depends on whether you consider data to be facts (plural) or information (which is singular). It's a fascinating grammatical conundrum." On a whiteboard, Person B has drawn a grid of 1s and 0s under "INFORMATION" and "is," and a series of bullet points under "FACTS" and "are," with "DATA" in the middle surrounded by question marks. Panel 4: Speaker A, holding up a Cartesian plot with a single x on it, asks, "What if I only have one data point?" Speaker B responds with a sarcastic expression: "Then you have bigger problems than grammar."</div>
    <figcaption>"<a href="https://phdcomics.com/comics/archive.php?comicid=1816">A Grammatical Conundrum</a>," comic 1816 from <a href="phdcomics.com">Piled Higher and Deeper</a> (PhD Comics) by Jorge Cham.</figcaption>
</figure>


<a id="first-half"></a>
## First half: Discussion

### Warm-up writing
I'd like you to start by calling to mind the following terms from this week's readings and video, which I've chosen among the many possible because I think they'll help us think *across* texts and contexts in a useful way:

- systematic
- tractable
- hierarchical
- visible
- actionable


<div class="alert alert-success">What does putting together the sources' different uses of these terms help you notice? What does it lead you to wonder? Where might we go from there?</div>

Take a few minutes to gather thoughts in writing, then we'll talk about it.

### Let's discuss!

If we get to grok-writing by around 10:15, that should give us about equal time to play with the concepts now and then to play with the methods in the second half.

And maybe we can take some collaborative notes at [bit.ly/dsam{{site.course.slugterm}}-notes](https://bit.ly/dsam{{site.course.slugterm}}-notes)?

Some possible moments to revisit, as needed:

<details><summary>You can't capture it all</summary>
    <p>AmyJo Brown:</p>
    <figure><iframe width="560" height="315" src="https://www.youtube.com/embed/5fUKTPAvYDM?si=XPD9jjMZamXCXwic&amp;clip=UgkxdxOVnNXP-CxCGXiUlFcpghrmy08VzwOH&amp;clipt=ELT2EBjY5BI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></figure><!--Get familiar with the kinds of things you *can* record from your objects, then pose some questions you hope to answer by doing so – and use those questions to limit what kinds of data you track and clean.-->
</details>
<details><summary>"the <em>paradox of exposure:</em>"</summary>
    <p>From Catherine D'Ignazio and Lauren Klein: "the double bind that places those who stand to significantly gain from being counted in the most danger from that same counting (or classifying) act" (<em>Data Feminism</em> 105).</p>
    <p>Or again: "[B]eing represented also means being made visible, and being made visible to the matrix of domination–which continuously develops laws, practices, and cultural norms to police the gender binary–poses significant risks to the health and safety of minoritized groups" (110).</p>
    <!-- refer to a forum post if you can! <ul><li></li></ul> -->
</details>

<details><summary>Data for good?</summary>
    <p>cf. D'Ignazio and Klein's discussion of the Colored Conventions Project, pp. 118-119. Perhaps especially pertinent: "Acts of counting and classification, especially as they relate to minoritized groups, must always balance harms and benefits. When data are collected about real people and their lives, risks ranging from exposure to violence are always present. But when deliberately considered, and when consent is obtained, counting can contribute to efforts to increase valuable and desired visibility."</p>
</details>

In addition, from the forums:
* Is it possible to fully "de-bias" data? (Jiating)
* What's the relationship between data and information? Which is prior? (Cate)
* What forms of protection can be found through data exclusion? (Nick)
* At what point does public information-gathering become intrusive and stalky? (Brenda)


### Grok writing

<div class="alert alert-success">
    <p>Spend some time putting marks on a page to help you think through, and consolidate for yourself, what we discussed today. What do you want to remember? What are you left wondering?</p>
</div>

After a few minutes, **I'll ask everyone to share one thing**, to which we'll all say, simply, "thank you."

<a href="week-01#an-explanation" class="smaller" title="We skipped this explanation in week 1, but it's there if you're curious">Why this terminology?</a>


## Break (10 minutes)
Assuming we left off at 10:40, let's aim to start up again at 10:50 or so. That should beat most of the rush for 11am classes.


<a id="second-half"></a>
## Second half: Let's practice!

### Loop writing: from sources to questions (to data?)

_Loop writing_ is a practice in composition/rhetoric that asks you to think on the page, responding to a series of questions – each of which may generate a range of responses, and many of which build from or zoom in on one of those prior responses. It's a generative technique for deepening your ideas.

While you can for sure do this on your own, in class I'd like to guide you through the questions, so we stay more or less together. But because we know we don't always write or think at the same rate, sometimes you may find yourself still working on a previous question when I've moved on – or you may find yourself feeling finished, waiting for me to catch up. If that happens, please be patient with yourself and with me. If I'm ahead, ask yourself: "What's the heart of this?" If you're waiting, ask yourself: "What am I forgetting?"

Ready?

<div class="alert alert-success">Take out something you can write with: a clean document, pen and paper, whatever feels good. <strong>This can be private writing until you want to share.</strong></div>

Let's go!

1. Start with a quick mental inventory. You can make just a quick list for yourself: _What's on my mind today?_ What am I trying to remember to do? To find? What's in the way of my focus?

    ...

    (Once you have that list, you can set it aside, knowing it's there to come back to when class is over.)


2. Begin again, in a clean space. Think about your project for DSAM, the one we talked about in office hours.

    What are the _source materials you want to work with?_ Again, make a quick list for now, not delving into any one thing; you can always come back and expand it as needed.

    ...

3. Of these source materials, which do you already have? Which do you still hope to find? Do you anticipate that any might be impossible to find? Are there any you might have to create?

    ...

4. Choosing one item from your list of materials – ideally one you already have access to – consider what it might mean to represent that material _as data_.
    * What features of this source material might be systematically measured, documented, or compared?
    * What might you be able to see, do, or ask if you had such documentation?
    * What might it hide or impede?

    ...

    * Roughly how many instances of this kind of source would be in your dataset?

    ...

5. Zoom in now on one of the features, one field of comparison (or contrast) across the sources you're working with.
    * _How many possible values_ could each source have in this regard? e.g.:
        - if it's a name or title, perhaps it would be unique and one-to-one;
        - if it's a year of birth or publication, there might be a span of years you're constraining your search to;
        - if it's coauthors, perhaps there could be one or several per source, but always a whole number;
        - if it's a qualitative category, perhaps there would be one (or more?) tag from a limited list.
        - etc.
    ...

6. Set that aside for now and close your eyes. What's the heart of the draw, for you, to this potential dataset? _What core questions do you have about it?_ When you feel yourself answering, open your eyes and write them down.

    ...

7. You may have one question, or several. _Which of these do you think a data-centered approach could help with?_ (It may well be none, but let's not presume.)


### Using/planning data structures

There are several kinds of data structures, as Schöch mentioned:

- rectangular (or linear)
- hierarchical
- relational

I'm hoping some volunteers will be able to share an example from their loop writing that will help us illustrate at least the first two of these, so we can see how we might plan out our data gathering spaces for ease of analysis later on. (If no one volunteers, I'll just go meta, and use "project presentations" as our example.)

- **Rectangular** (csv): Rows and columns, intersecting at cells. Often, it helps to gather information such that each row is one object or observation, and each column is a field or feature; this works especially well when there's a one-to-one relationship between features and values. In rectangular data, every row has the same number of columns, though some cells may be blank.
- **Hierarchical** (json): Key:value pairs (usually), but allowed to be nested, such that some "values" are themselves keys with additional values within them. Allows for varied numbers of "children."
- **Relational** (database): Multiple tables (usually), such that values in one table can be listed in another, and each table can have its own fields. Allows for complex search and join operations.




## EXT: Project studio

If we've gotten through the examples with time to spare, go ahead and work on your own project! Don't forget to document how you use the time in your Mindful Practice Journal, and take care to document any decisions you make about how to classify or modify something you'll use as data!



<a id="hw"></a>
## Homework for next time:

No new reading! Instead, prepare a 5-minute presentation on your semester-long DSAM project. At this stage in your iterative process, you should be able to answer the following questions:

* What sources / objects are you working with?
* What questions do you have about them, or that you hope they can help you address?
* What are your long-term goals in pursuing this research?
* What are your next steps?

NB: Five minutes is not a lot of time to answer all those questions, but it is enough time if your responses are focused. To help you practice until you achieve this goal, and to preserve an archive we can revisit, I'm asking you to **record your presentation before class and post it to the [discussion forum]({{site.repo_url}}/discussions)**. You'll then have the option of either playing the video next class (which guarantees the same timing) or re-presenting live, treating the video as a rehearsal (which spares you from hearing your own voice on a recording). Your choice, while classtime lasts!

In addition, you should have put some materials into some kind of repository, file, or folder where you can **begin building a public-facing "deliverable" version of your project**, however nascent it is for now. (NB: This repository can be, but does not need to be, a GitHub repo. Other good options include Google Sheets; blogs or other websites, whether built with content management systems or GitHub Pages or OpenFuego; or file folders shared using OneDrive.) **Link to this public-facing project in your forum post.**

There are many tools you can use to capture both your voice and your screen, including Zoom and Panopto, as well as many sources of advice on how to do this well. (You can also view the [example videos from last year](../sample-projects) for inspiration.)

Please do search before you ask for help, because it's a vital skill you'll need as a digital scholar! But if you need me, you know [where to find me](../office). :)
