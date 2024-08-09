
# Week 3: Programming as literacy, as exploration
<span class="date">September 11, 2023</span>


## Plan for the day:

* [First half](#first-half): Being / becoming programmers
    - brought to you by Montfort ch 3    
* Break (10 min)
* [Second half](#second-half): Share and discuss!
* HW for next time (~10 min)

<a id="first-half"></a>
## First half: Being / becoming programmers

### Review
- a repo is a folder
- a fork is a copy you control
- a clone brings the folder from the **clo**ud to the **ne**ar
- to sync local changes to the web,

For today's exercise, I've created a repository with instructions in the README. This also has the benefit of linking them together, so it'll be easy later for us all to see what the others have been up to.

<div class="alert alert-success"><strong>Head on over to <a href="https://github.com/benmiller314/dsam-montfort-03">github.com/benmiller314/dsam-montfort-03</a></strong>, where we'll follow the instructions through these parts:

<ol><li>Find the code</li>
<li>Change the code</li>
<li>Explore the possibilities</li>
<li>Share it back</li></ol>
</div>

That should take us pretty much through the first half of class.

<div class="alert alert-info">NB: For your own projects, <em>should you choose to</em> (it's encouraged but not required), <strong>you can easily create a new repo with GH Desktop by using File > New Repository</strong> and giving it a location. This will make a new folder on your own computer; later, you'll have the option to Publish it to GitHub.
<details><summary>You can also use github.com or the command line.</summary>
<ul><li>From github.com, go to your user page (the default when you log in) and click on the green New button. To work on the repo locally, you'll want to clone it.</li>
<li>From the command line, navigate to a folder you want to start tracking and run <code>git init</code>. You'll have to run <code>git add remote {url}</code> (replacing <code>{url}</code> with a github.com address before you can <code>git push</code>.)</li>
</ul>
</details>
</div>


<!--
Takeaways:
* some code controls processing, some is just source material to process
* we can tell the difference between source material and processing instructions, even in an unfamiliar programming language
    - and it's not just the all-caps (though I started with that because I thought it would be easier)
-->

## Break (10 min)
Assuming we left off at 10:30, let's aim to start up again at 10:40 or so. That should beat the elevator rush for 11am classes.

<a id="second-half"></a>
## Second half: Let's talk about it!

- What did you notice? What do you wonder?
- Where does it add to what you'd read/viewed, and vice versa?

Let's take notes at [bit.ly/dsam2023fall-notes](https://bit.ly/dsam2023fall-notes)

<details><summary>As needed, some passages/questions from the forum</summary>
    <details><summary>On project scope</summary>
        <blockquote>
            <p>The three main things you can learn from a free project are how to do something using your programming skills that is <em>tractable</em>, <em>computational</em>, and <em>interesting</em>. A project has to be tractable—that is, manageable, something you can handle—or it won’t be possible for you to accomplish it. Most of the free projects have some basic structure to them but allow latitude in how they are done.</p>
            <p>This discussion will hopefully make even more sense after you have learned the fun- damentals a good bit using Methods 1, 2, and 3. But to be concrete about the tractable, computational, and interesting at this point, I’ll imagine a final project (or “very free project”) for a semester-long class, one that is not constrained and builds on everything learned throughout the semester.</p>
            <p>For such a project, you may want to develop a networked multimedia system that can converse about art history as well as an expert human can. Nice idea, but this is not a tractable project. Just making a website with some images of visual art and some writing about visual art could be a fine project for a different context, but it isn’t a computational project that uses your growing ability as a programmer. Figuring out some simple statistics of different photographs, represented as JPEG files, may be both tractable and computational, but because it isn’t very likely to offer insights, it doesn’t seem very interesting. It is a challenge to find a free project that meets all three of these criteria. If you do develop a project that interests you, is computational, and can be accomplished, you not only will be developing as a programmer; you’ll also be learning about how programming and computation is meaningful to you.</p>
            <p class="bq_cite">Montfort 20–21 (section 1.10)</p>
        </blockquote>
        <p><a href="https://github.com/benmiller314/dsam2023fall/issues/4#issuecomment-1712310041">Sidra asks</a>: How do we reconcile Montfort's (dis)approval with a project like Rachel Deblinger's "<a href="https://memoriesmotifs.com/">Memories/Motifs</a>"?</p>
    </details><!--/ On project scope -->
    <details><summary>On audience</summary>
        <p><a href="https://github.com/benmiller314/dsam2023fall/issues/4#issuecomment-1712558505">Khushboo noted</a> that "one of the questions that looms large while reading both the texts is that of the intended reader." In composition theory, we have a key concept that (in the words of Andrea Lunsford and Lisa Ede) audience is not only <em>addressed</em> but also <em>invoked</em>; in other words, writers can try to imagine up an ideal audience member and shape their texts so as to invite readers to come closer to that ideal.</p>
        <p>So I guess I'd pose the question to you all in this way: Did you find yourself inside the primary "audience addressed" of either or both of these texts? If not, how inviting were they to you as a secondary reader, i.e. how well were you able to see yourself as part of an "audience invoked"?</p>
        <p>Here are some first-page passages to ground the discussion:</p>
        <blockquote><p>You are an educated, successful person capable of abstract thought. A VP doing an SVP’s job. Your office, appointed with decent furniture and a healthy amount of natural light filtered through vertical blinds, is commensurate with nearly two decades of service to the craft of management.</p>
        <p>[...]</p>
        <p>For your entire working memory, some Internet thing has come along every two years and suddenly hundreds of thousands of dollars (inevitably millions) must be poured into amorphous projects with variable deadlines. Content management projects, customer relationship management integration projects, mobile apps, paperless office things, global enterprise resource planning initiatives—no matter how tightly you clutch the purse strings, software finds a way to pry open your fingers.</p>
        <p class="bq_cite">Ford section 1</p>
        </blockquote>
        <blockquote><p>This book is mainly addressed to people without a programming background— particularly to both individual, self-directed learners and to graduate students in the arts and humanities. I developed this book in part for use in university courses, as a textbook. I also put a lot of effort into developing a book that will be useful outside a standard classroom and course. I provide suggestions for teaching this book, and for learning from it in a class, in appendix B, “Contexts for Learning,” which also includes some suggestions for self-directed students.</p>
        <p>To some, <em>programming</em> is associated with expertise, professional status, and esoteric technical difficulty. I don’t think the term <em>programming</em> needs to be intimidating, any more than the terms <em>writing</em> or <em>sketching</em> do. These are simply the conventional words for different activities—creative activities that are also methods for inquiry.
        </p>
        <p class="bq_cite">Montfort 1 (section 1.1)</p>
        </blockquote>
        <p>I imagine this may also bring in <a href="https://github.com/benmiller314/dsam2023fall/issues/4#issuecomment-1712620347">Chloe's comments</a> about business-writing conventions and the mystification of digital tools: "what kind of tools we think of like levers and pulleys and which ones we think of like magic."</p>
    </details><!--/ On audience -->
    <details><summary>On exploration vs. exploitation</summary>
        <p><a href="https://github.com/benmiller314/dsam2023fall/issues/4#issuecomment-1712920772">Alex points us</a> toward this distinction of Montfort's, noting that trying to apply his grocery store metaphor to learning code is frustrating. Here's one representative paragraph:</p>
        <blockquote>
            <p>In organizational behavior, machine learning, and grocery shopping, it is desirable to balance exploration with exploitation. We can imagine a shopper who does nothing but explore—who tries new foods at random but never returns to enjoy a particularly pleasing food again. What is being learned from such exploration? <strong>As described, nothing at all is being learned. Not just very little, but nothing: each random selection is completely independent of the previous ones.</strong> One day’s grocery basket could be improved by remembering some of the best items found so far and selecting those while also continuing to look for new food. Most grocery-seeking individuals balance exploration and exploitation in some way, just as successful companies try to profit from existing, stable lines of business while they also try out new opportunities that might pay off significantly. A robot finding its way around a changing or partially known environment should exploit some known ways to get from place to place while also devoting some time to exploration, in the hopes that it can find more efficient routes. </p>
            <p class="bq_cite">Montfort 5–6, boldface Ben's</p>
        </blockquote>
        <p>How do we understand the terms of this metaphor? What is Montfort after with it, do you think? Can we come up with a better metaphorical framework for expressing that intervention?</p>
    </details><!--/ On exploration vs. exploitation -->
    <details><summary>On labor and its (in)visibility</summary>
        <p>Back in the previous week's discussion, <a href="https://github.com/benmiller314/dsam2023fall/issues/3#issuecomment-1703078145">Khushboo raises the question of labor</a>: "how does one perceive it?" I hear that as both "how do we even know it's happening?" and as "how do we feel about it?", i.e. do we see it as a good thing, a sign of access? or as a burden? (Khushboo, is that a fair sayback?) Despite all the efforts that go into even developing systems of practice, let alone enacting them, ensuring recognition is never simple or guaranteed.</p>
        <p>Khushboo, like <a href="https://github.com/benmiller314/dsam2023fall/issues/3#issuecomment-1700095619">Sidra in the previous post</a>, grounds this line of questioning in Risam and Gil's discussion of "Tense Origins." Here's an excerpt:</p>
        <blockquote>
            <p>The second tension is a relatively newer one between metaphorical computer literacy — the ability to use GUIs, an act in which most people with computational devices engage through their ordinary interactions online — and symbolic computational literacy, or the ability to “code,” which remains the purview of a rare few, especially in the humanities. Much has been made of the debate over whether one must code to be a digital humanist<span class="ftnref">[10]</span> [Cecire 2011] [Sample 2011] [Posner 2012]. The two of us have, at earlier moments in our careers, understood firsthand how many who wish to undertake digital humanities scholarship are simply looking for easy access to out-of-the-box software and platforms with GUIs for project development.</p>
            <p>The history of digital humanities is marked by many laudable efforts to create tools with GUIs that allow scholars to create digital scholarship in the humanities without having to develop much symbolic computational literacy. However, these tools are inextricably linked to the dominance of English as a lingua franca for programming and markup languages, with downstream implications for those working with languages other than English — namely the emphasis on Anglophone scholarship in digital humanities and the comparative underdevelopment of multilingual digital humanities, particularly languages in scripts other than Latin and those read from right to left [Fiormonte 2015] [Risam 2018a] [Wrisley 2019]. In addition, we have increasingly come to understand that GUIs hide the systems that drive that production, and by extension, the labor to maintain and sustain them. For example, platforms like WordPress that rely on a database require labor to keep abreast of updates and patches, deprecated dependencies like plugins, and their vulnerability to security breaches — and to fix the issues that inevitably arise. Such invisible labor is so successfully obscured that even the most veteran practitioners struggle with its implications after decades of work in the field [Drucker 2021] [Yelton 2021]. Technologies associated with Minimal Computing™ like Jekyll offer some relief from labor issues by avoiding reliance on a database, though not without inevitable tradeoffs — among them, the learning curve for use.</p>
            <p class="bq_cite">Risam and Gil, paragraphs 14-15</p>
            </blockquote>
            <p>I don't expect there's a way to entirely unravel the tensions here. But do you see ways forward? Or new ways of articulating the tensions or questions, in light of the reading and practice with code and/or DH projects/tools/methods/studies you've engaged in since?</p>
    </details><!--/ On labor and its (in)visibility -->
</details><!-- end of "if needed" section -->

### Grok writing

<div class="alert alert-success">
    <p>Spend some time putting marks on a page to help you think through, and consolidate for yourself, what we discussed today. What do you want to remember? What are you left wondering?</p>
</div>

After a few minutes, I'll ask everyone to share one thing, to which the only response will be "thank you."

#### An explanation

The phrase "to grok" comes from Robert Heinlein's science fiction novel _Stranger in a Strange Land_ (first printing, Putnam 1961). Leaving aside the weird gender-relations of the novel for the moment, the novel spends a lot of time harping on how hard it is to translate the word "grok" from Martian to English, though it's sometimes rendered as "drink" or especially "drink in." But in general (albeit nerdy) use &mdash; and certainly as I will use it from time to time in this course &mdash; to grok [something] means "to understand [something] fully," in the sense that (a) you no longer need to think consciously about how [something] works, and (b) you could make modifications if the need arose.

<details>
    <summary>More detail and some fun quotes</summary>
    <p>Here's an example of the original usage:</p>
    <blockquote>
        <p>The Martian Race had encountered the people of the fifth planet, grokked them completely, and had taken action; asteroid ruins were all that remained, save that the Martians continued to cherish and praise the people they had destroyed. This new work of art was one of many attempts to grok the whole beautiful experience in all its complexity in one opus. But before it could be judged it was necessary to grok how to judge it. (Heinlein 93)</p>
    </blockquote>
    <p>Wikipedia's <a href="https://en.wikipedia.org/w/index.php?title=Grok&amp;oldid=695270451#In_computer_programmer_culture">current page on "Grok"</a> features this definition, which matches my experience of the term's usage:</p>
    <blockquote>
        <p>The <a href="https://en.wikipedia.org/wiki/Jargon_File">Jargon File</a>, which describes itself as a "Hacker's Dictionary" and has been published under that name three times, puts grok in a programming context:</p>
        <blockquote>
            <p>When you claim to "grok" some knowledge or technique, you are asserting that you have not merely learned it in a detached instrumental way but that it has become part of you, part of your identity. For example, to say that you "know" <a href="http://www.catb.org/jargon/html/L/LISP.html">Lisp</a> is simply to assert that you can code in it if necessary &mdash; but to say you "grok" LISP is to claim that you have deeply entered the world-view and spirit of the language, with the implication that it has transformed your view of programming. Contrast <a href="http://www.catb.org/jargon/html/Z/zen.html">zen</a>, which is a similar supernatural understanding experienced as a single brief flash.</p>
        </blockquote>
    </blockquote>
</details> <!--/ fun quotes -->

**Grok-<em>writing</em>**, as I will use the term, means _using writing to internalize a discussion_: to drink it in and set it down and make what had been only air and vibrations &ndash; ephemeral sound &ndash; into something you can return to, perhaps repeatedly. In other words, please save your grok-writing somewhere you'll be able to find it again.

Procedurally, I also like to draw on the Canadian tradition of "inkshedding," whereby we all write privately in a public space, knowing that **we will be expected to share _something_ from what we just wrote**. I won't collect it, and we won't discuss it. Instead, we'll go around and each read some excerpt (how long is up to each of us) and then say, simply, "Thank you."

Today's grok-writing and -sharing starts off already a bit disrupted by this explanation, but as the weeks go on I hope we'll be able to transition more smoothly from the writing to the talking to the sharing... into the break, where the ideas we share can linger and buzz and mix.

#### Sharing
Don't forget to say "Thank you!"

## Homework

### Long-term / ongoing
Remember to put in at least 2 hours (more is fine, too) toward your independent project, logging how you spend that time in a [Mindful Practice Journal](../projects#mindful-practice-journal).


### For next time

Building on today's work with code, for next time I've chosen some readings from "critical code studies" as well as a smidge from literacy studies treatments of programming. Our colleague Annette Vee is one of the foremost scholars on this topic, and for a fuller treatment I highly recommend her book _Coding Literacy_. But in the interest of keeping the workload manageable, I'm assigning here instead a kind of abridged version: a magazine article that _quotes_ Annette.

<div class="alert alert-info">
<p>As usual, I'd love you to share some brief thoughts in writing before we come together again. I can open up a space on the Issue Queue, as I did for the first two weeks – or, if you want, I believe I can now activate the official GH Discussion Forum that wasn't working the first time around.</p>
<p><strong>Quick show of hands:</strong> Who wants to try the other thing to compare the affordances? Who would rather stick to what we've already used?</p>
</div>

UPDATE: after some demonstration, and a second vote, we decided to test out _Discussions_. It's basically like Issues, but with threads and a somewhat softer-looking index page. I've updated all the links that weren't to particular existing posts!


By Friday, please **read** and post a short response to the following:

* Montfort, Nick, Patsy Baudoin, John Bell, Ian Bogost, Jeremy Douglass, Mark C Marino, Michael Mateas, Casey Reas, Mark Sample, and Noah Vawter. “10: Introduction.” _10 PRINT CHR$(205.5+RND(1)); : GOTO 10_, The MIT Press, 2012, pp. 1–17. direct.mit.edu, <a href="https://doi.org/10.7551/mitpress/9040.001.0001">https://doi.org/10.7551/mitpress/9040.001.0001</a>.
* Whalen, Zach. “Any Means Necessary to Refuse Erasure by Algorithm: Lillian-Yvonne Bertram’s Travesty Generator.” _Digital Humanities Quarterly_, vol. 017, no. 2, July 2023, <a href="http://digitalhumanities.org:8081/dhq/vol/17/2/000707/000707.html">http://digitalhumanities.org:8081/dhq/vol/17/2/000707/000707.html</a>.
* Benjamin, Ruha. "Preface" and “Introduction: The New Jim Code.” _Race after Technology: Abolitionist Tools for the New Jim Code_, Polity, 2019, pp. 16–101, but you can stop at p. 78 if you're running short on time. [Available on Overdrive](https://pitt.primo.exlibrisgroup.com/permalink/01PITT_INST/e8h8hp/alma9999863389206236).
* Raja, Tasneem. “Is Coding the New Literacy?” _Mother Jones_, 16 June 2014, <a href="https://www.motherjones.com/media/2014/06/computer-science-programming-code-diversity-sexism-education/">https://www.motherjones.com/media/2014/06/computer-science-programming-code-diversity-sexism-education/</a>.
    - EXT for eager readers: Vee, Annette. “Introduction: Computer Programming as Literacy.” _Coding Literacy_, MIT Press, 2017. pitt.primo.exlibrisgroup.com, <a href="https://doi.org/10.7551/mitpress/10655.003.0003">https://doi.org/10.7551/mitpress/10655.003.0003</a>.
