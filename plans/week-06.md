
# Week 6: What is code? Why does it matter?
<span class="date">September 30, 2023</span>

<section class="prereqs">
    <details><summary><strong>Texts to have read / watched</strong></summary>
    <ul class="spaced">
        <li>Ford, Paul. <em>What Is Code? If You Don’t Know, You Need to Read This</em>, Bloomberg.com, <a href="http://www.bloomberg.com/graphics/2015-paul-ford-what-is-code/">http://www.bloomberg.com/graphics/2015-paul-ford-what-is-code/</a>.
            <ul>
                <li>Section 1: "The Man in the Taupe Blazer."</li>
                <li><a href="https://www.bloomberg.com/graphics/2015-paul-ford-what-is-code/#and-now-for-something-beautiful">Section 6.5</a>: "And Now for Something Beautiful"</li>
            </ul>
        </li>
        <li>Vee, Annette. “Introduction: Computer Programming as Literacy.” <em>Coding Literacy</em>, MIT Press, 2017, pp. 1–42, <a href="https://doi.org/10.7551/mitpress/10655.003.0003">https://doi.org/10.7551/mitpress/10655.003.0003</a>. <a href="https://direct-mit-edu.pitt.idm.oclc.org/books/monograph/3543/Coding-LiteracyHow-Computer-Programming-Is">(Pitt library link)</a>.</li>
        <li>Montfort, Nick. "Appendix A: Why Program?" <em>Exploratory Programming for the Arts and Humanities</em>, 2nd ed., The MIT Press, 2021, pp. 319–330, <a href="https://mitpress.ublish.com/ebook/epah2e-preview/12629/319">https://mitpress.ublish.com/ebook/epah2e-preview/12629/319</a>.</li>
        <li>Miller, Benjamin. “Chapter 17: The Pleasurable Difficulty of Programming.” <em>Methods and Methodologies for Research in Digital Writing and Rhetoric: Centering Positionality in Computers and Writing Scholarship</em>, Volume 2, edited by Victor Del Hierro and Crystal VanKooten, The WAC Clearinghouse; University Press of Colorado, 2022, pp. 159–83. <a href="https://doi.org/10.37514/PRA-B.2022.1664.2.17">https://doi.org/10.37514/PRA-B.2022.1664.2.17</a>. (<a href="https://wac.colostate.edu/docs/books/positionality/chapter17.pdf">Direct link to chapter PDF</a>.)</li>
        <li>EXT for eager readers:
            <ul>
                <li>Montfort, Nick, Patsy Baudoin, John Bell, Ian Bogost, Jeremy Douglass, Mark C Marino, Michael Mateas, Casey Reas, Mark Sample, and Noah Vawter. “10: Introduction.” _10 PRINT CHR$(205.5+RND(1)); : GOTO 10_, The MIT Press, 2012, pp. 1–17. direct.mit.edu, <a href="https://doi.org/10.7551/mitpress/9040.001.0001">https://doi.org/10.7551/mitpress/9040.001.0001</a>.
                </li>
            </ul>
        </li>
    </ul>
    </details>
</section>

## Plan for the day:

* [First half](#first-half): Let's discuss!
    - Warm-up writing
    - Tensions, takeaways, confusions, questions
    - Grok writing (around 10:15)
* Break (10 min)
* [Second half](#second-half): Let's practice!
* [Homework for next time](#hw): About those presentations

<a id="first-half"></a>
## First half: Tensions, takeaways, confusions, questions

### Warm-up writing
I'd like you to start by calling to mind the readings for this week. What stands out to you as a particularly important **take-away**, something memorable or surprising? What stands out as an **unresolved** point of tension or confusion?

Depending on your own practices, you may want to make lists or freewrite, or even draw a picture or diagram. Either way, I want to spend 5 minutes on this composing-to-center. I won't collect it, but I will ask for volunteers to share.


### Let's talk!

If we get to grok-writing by around 10:15, that should give us about equal time to play with the concepts now and to play with the methods in the second half.

Let's take notes at [bit.ly/dsam{{site.course.slugterm}}-notes](https://bit.ly/dsam{{site.course.slugterm}}-notes).






### Grok writing

<div class="alert alert-success">
    <p>Spend some time putting marks on a page to help you think through, and consolidate for yourself, what we discussed today. What do you want to remember? What are you left wondering?</p>
</div>

After a few minutes, I'll ask everyone to share one thing, to which the only response will be "thank you."

<a href="week-03#an-explanation" class="smaller" title="We skipped this explanation in week 3, but it's there if you're curious">Why this terminology?</a>

## Break (10 minutes)
Assuming we left off at 10:30, let's aim to start up again at 10:40 or so. That should beat the elevator rush for 11am classes.



<a id="second-half"></a>
## Second half: Let's practice!

### Orienting to code
As a preamble/reminder, it's not that I'm asking you to learn to code because it's impossible to do good work in digital studies, or using digital methods, without programming. Rather, I am asking you to *engage with code* because code underlies all digital methods, and it will help you think about code's affordances to get more familiar with how it works.

Today we'll work a little bit with Python, and a little bit with JavaScript, but that's not because these are somehow the best languages – though they are fairly common in DH and in web authoring, respectively. **What I *most* want you to take away aren't the specifics of any one programming language, but rather the patterns that cross languages: things like variables, functions, loops, and conditionals.**



### Defining terms

Let's have a look at [some interactive examples](https://mybinder.org/v2/gh/benmiller314/dsam-montfort/HEAD?labpath=intro-to-coding.ipynb):

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/benmiller314/dsam-montfort/HEAD?labpath=intro-to-coding.ipynb)

NB: If you're bored with the basics, you can skip ahead to the next section.

### Modifying a Program

The Montfort reading for homework was an appendix to his book _Exploratory Programming for the Arts and Humanities_ (2nd edition). Today I'd like you to try an exercise from his chapter 3: ["Modifying a Program"](https://mitpress.ublish.com/ebook/epah2e-preview/12629/31). Specifically, we'll be looking at some JavaScript poetry generators embedded within HTML pages. You do not need any prior programming experience; you do, however, need a plain-text editor like [Pulsar](https://pulsar-edit.dev/) or [VS Code](https://code.visualstudio.com/).

<div class="alert alert-info">
Note Montfort's use of <em>exploratory</em> in his title. The heart of what he means by this is the question, "What happens when I...?"
</div>

The basic idea is that you can learn some programming fundamentals by messing around with existing scripts. Sometimes, changing a piece of code will break something; that can often help you see what assumptions are built into the function or conditional logic of the program.

Other times, changing a piece of code will preserve the functionality, but change the output. This often means you're changing the content of a variable, but not its type – you're likely still working within the basic framework the original programmer built.

<div class="alert alert-info">Note the parallels to "sources, processed and presented": only when you mess with the processing bits does the behavior fundamentally change.</div>


#### Part 1: Find the code

_NB: The numbered instructions below are only slightly modified from Montfort's, which begin on page 33. My variations will appear in bold._

1. Go to **[nickm.com/memslam/a_house_of_dust.html](https://nickm.com/memslam/a_house_of_dust.html), where Montfort has recreated a 1967 script by Alison Knowles and James Tenney. Watch for a minute to see how the page works.**

2. **Right-click to select** Page Source or View Source so that you see the HTML (which includes the JavaScript). In Firefox, this can be done with Ctrl-U (or on the Mac, ⌘-Option-U), or you can locate the option in the menu, sometimes under Tools > Web Developer. All browsers have a similar option.

3. Select all, usually done with Ctrl-A (or on the Mac, ⌘-A).

4. Copy, usually done with Ctrl-C (or on the Mac, ⌘-C).

5. Open your text editor. Paste all of the HTML into the text editor with Ctrl-V (Mac: ⌘-V).

6. Save that file to your computer. (For bonus points, you can first fork and clone my [dsam-montfort repository](https://github.com/benmiller314/dsam-montfort/), and save into that folder.) **Give the file a name like _'house-of-%name%.html'_, replacing '%name%' with your first name.** Note that there should be **no spaces, no apostrophes, and no percent symbols** in the filename.
<details><summary>NB: If your operating system is configured to conceal file extensions like <code>.html</code> from you, this is a great time to turn that off.</summary><p>File extensions can tell you a lot about how they're supposed to work, with what software, e.g. the <code>.py</code> that indicates a Python file, <code>.csv</code> for LO-FI spreadsheet files, vs. <code>.xlsx</code> for Excel workbooks, etc. <ul><li>If you use Mac OS X, the option to show file extensions can be reached by clicking on the desktop to activate the Finder and then selecting Finder > Preferences > Advanced.</li><li>On Windows, open the File Explorer and look at the View tab.</li><li>All the GNU/Linux distributions I know about show the extensions by default.</li></ul></p></details>

<ol start="7"><li>Find the file in your computer's system (e.g. Finder on Mac, or Explorer on Windows), and double-click to open it. If it has the <code>.html</code> extension, it should appear in your default web browser – but instead of having an <code>http://</code> address, it'll be under something like <code>file:///</code>. <ul><li>Why? Because you're not transferring data across the internet, so you don't need to use a HyperText Transfer Protocol.</li></ul></li></ol>


#### Part 2: Change the code

We're now up to Montfort's [section 3.3](https://mitpress.ublish.com/ebook/epah2e-preview/12629/34).

1. Head back into your text editor and look for the words in all caps: 'SAND', 'DUST', etc.

2. Change them and save the file. You don't need your lists to be as long as the ones there, but make sure you've got at least a few variations that you'll recognize as your own.

3. Go back to your browser and refresh the page.

<div class="alert alert-info">
<p>Pause to discuss. What happens?</p>

<p>What lets you know what you can change and keep the program intact, and what would break the program if you changed it?</p>
</div>

<ol start="4"><li>If you're happy with this changed version of your generator, this is where (if you set up the repository) you could <strong>commit the change</strong>, using a meaningful commit message (beyond "updated file"). And if you're not sure how to do that, please ask. :¬)</li></ol>


#### Part 3 / EXT: Explore the possibilities

We're now up to Montfort's [Free Project 3-1](https://mitpress.ublish.com/ebook/epah2e-preview/12629/36), copied below.

Montfort writes:
<blockquote>
<strong>Do this project three (3) times, using two (2) different Web pages as your starting point.</strong> Start with a particular combinatory textual toy in HTML with JavaScript—a simple one, although your selection doesn’t have to be one of the six listed previously.
</blockquote>

By "the six listed previously," Montfort means one of the following sites, and for now I strongly recommend sticking to these. (You can always try something else at home.)

* [nickm.com/poems/perverbs.html](https://nickm.com/poems/perverbs.html)
* [nickm.com/poems/upstart.html](https://nickm.com/poems/upstart.html)
* [nickm.com/poems/lede.html](nickm.com/poems/lede.html)
* [nickm.com/memslam/love_letters.html](https://nickm.com/memslam/love_letters.html)
* [nickm.com/memslam/stochastic_texts.html](https://nickm.com/memslam/stochastic_texts.html)
* [nickm.com/memslam/a_house_of_dust.html](https://nickm.com/memslam/a_house_of_dust.html) (but we've already done this one)

<blockquote><p>Modify the program so that its output is somehow substantially different. It could contradict the original system, for instance, or the tone could be completely different, or the system could produce unrelated output. Beyond replacing some text with other text, <em>see if you can make changes to the way the system functions.</em> For instance, if your system generates sentences, can you change the syntax of the sentences it outputs—adding adjectives or moving parts of speech around—rather than just changing the lexicon? <strong>For this exercise, restrict your work to the JavaScript code (in the <code>&lt;script&gt;</code> element) rather than modifying the HTML.</strong> Modifying HTML can be fun and rewarding too, but our focus is on programming, not on structured documents or their appearance.</p> <p>(Montfort 36-37, emphasis added)</p>
</blockquote>

<div class="alert alert-success">
<p>See how many changes you can make while time allows – and have fun with it! Each time you reach a moment of satisfaction, go ahead and commit the change, using a meaningful commit message (i.e. beyond just "updated file").</p>

<p>NB: Make a new file for each new <em>source page</em>, giving it a unique name... but then <strong>keep the same filename for your revisions within that file</strong>, so your changes will show up as diffs.</p>

<p>If you find you've broken something, you can Edit > Undo within the text editor; or you can go back and copy from an old commit; or you can go all the way back and copy from the original source again. This is a safe space for experimentation and exploration. :¬)</p>
</div>

### Share and enjoy!

I'd love to see some of your poem-generators in action! To make your examples more visible, if you've cloned [my original repo](https://github.com/benmiller314/dsam-montfort/), please **push your changes** to the cloud. From there, we'll be able to view them [online](network).



<a id="hw"></a>
## Homework for next time

As always, continue working on your project – now with a little more feedback – and take notes in your [Mindful Practice Journal](projects.md).

I'll also ask you to [add your thoughts to the discussion forum]({{site.repo_url}}/discussions) after reading.

In preparation for <a title="required reading: 71 page-equivalents; EXT reading adds 55 for a total of 126">week 7, on artificial intelligence and machine learning</a>, please **watch / read**:

* "Computer Scientist Explains Machine Learning in 5 Levels of Difficulty." WIRED, YouTube, 18 Aug 2021. <a href="https://www.youtube.com/watch?v=5q87K1WaoFI">https://www.youtube.com/watch?v=5q87K1WaoFI</a>.
* Newhauser, Mary. “What Is Generative AI? A Comprehensive Guide for Everyone.” GPTech, 26 June 2023, <a href="https://www.gptechblog.com/what-is-generative-ai-comprehensive-guide-beginners">https://www.gptechblog.com/</a>
* Crawford, Kate, and Trevor Paglen. “Excavating AI: The Politics of Training Sets for Machine Learning.” 19 Sep 2019, <a href="https://excavating.ai">https://excavating.ai</a>.
* Onuoha, Mimi and Mother Cyborg (Diana Nucera). “A People’s Guide To Tech: Artificial Intelligence.” Allied Media Projects, Aug 2018, <a href="https://alliedmedia.org/resources/peoples-guide-to-ai">https://alliedmedia.org/resources/peoples-guide-to-ai</a>.
* Shane, Janelle. “An Exercise in Frustration.” AI Weirdness, 21 May 2024, <a href="https://www.aiweirdness.com/an-exercise-in-frustration/">https://www.aiweirdness.com/an-exercise-in-frustration/</a>.
* Shane, Janelle. “When Algorithms Surprise Us.” AI Weirdness, 13 Apr 2018, <a href="https://www.aiweirdness.com/when-algorithms-surprise-us-18-04-13/">https://www.aiweirdness.com/when-algorithms-surprise-us-18-04-13/</a>.

* EXT: eager learners can read / watch the following:
    - Alammar, Jay. "ChatGPT Has Never Seen a SINGLE Word (Despite Reading Most of The Internet). Meet LLM Tokenizers." YouTube, 26 Jul 2023. <a href="https://www.youtube.com/watch?v=uSinkCeUg9U">https://www.youtube.com/watch?v=uSinkCeUg9U</a>.
    - Karpathy, Andrej. "State of GPT \| BRK216HFS." Microsoft Build 2023. YouTube, 25 May 2023. <a href="https://www.youtube.com/watch?v=bZQun8Y4L2A">https://www.youtube.com/watch?v=bZQun8Y4L2A</a>.
        * NB: at 42 minutes, this is long; the first 20 minutes go into some more detail on how large language models are trained and built up, and is perhaps the more DSAM-level portion; the second half is advice on how to work with models, e.g. through prompt engineering, and what may be coming next.
    - Kozyrkov, Cassie. "Introduction to ML and AI - MFML Part 1." posted to YouTube 3 Oct 2021, but filmed in 2018. <a href="https://www.youtube.com/watch?v=lYWt-aCnE2U">https://www.youtube.com/watch?v=lYWt-aCnE2U</a>.
        * NB: another long video, and part of an even longer series. I recommend the following sections:
        * <a href="https://www.youtube.com/watch?v=lYWt-aCnE2U&t=973s">from 16:13</a> to 34:45: The process of building a regression model and why that matters.
        * <a href="https://www.youtube.com/watch?v=lYWt-aCnE2U">from 39:42</a> to 45:37: Why did AI start booming in the late 2010s?
        * <a href="https://www.youtube.com/watch?v=lYWt-aCnE2U&t=3264s">from 54:28</a> to 1:07:05: When can you trust machine learning?
    - Cheung, Diana. “Demystifying Generative AI: Introducing the Underlying Technologies & Models of Generative AI.” Codesmith.io/Blog, Aug 30, 2023, <a href="https://www.codesmith.io/blog/demystifying-generative-ai-introducing-the-underlying-technologies-models-of-generative-ai">https://www.codesmith.io/blog/demystifying-generative-ai-introducing-the-underlying-technologies-models-of-generative-ai</a>.
