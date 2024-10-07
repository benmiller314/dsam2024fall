
# Week 7: Artificial Intelligence and Large Language Models
<span class="date">October 7, 2024</span>

<section class="prereqs">
    <details><summary><strong>Texts to have read / watched</strong></summary>
        <ul class="spaced">
            <li>"Computer Scientist Explains Machine Learning in 5 Levels of Difficulty." _WIRED_, YouTube, 18 Aug 2021. <a href="https://www.youtube.com/watch?v=5q87K1WaoFI">https://www.youtube.com/watch?v=5q87K1WaoFI</a>.</li>
            <li>Newhauser, Mary. “What Is Generative AI? A Comprehensive Guide for Everyone.” GPTech, 26 June 2023, <a href="https://www.gptechblog.com/what-is-generative-ai-comprehensive-guide-beginners">https://www.gptechblog.com/</a>.</li>
            <li>Crawford, Kate, and Trevor Paglen. “Excavating AI: The Politics of Training Sets for Machine Learning.” 19 Sep 2019, <a href="https://excavating.ai">https://excavating.ai</a>.</li>
            <li>Onuoha, Mimi and Mother Cyborg (Diana Nucera). “A People’s Guide To Tech: Artificial Intelligence.” Allied Media Projects, Aug 2018, <a href="https://alliedmedia.org/resources/peoples-guide-to-ai">https://alliedmedia.org/resources/peoples-guide-to-ai</a>.</li>
            <li>Shane, Janelle. “An Exercise in Frustration.” AI Weirdness, 21 May 2024, <a href="https://www.aiweirdness.com/an-exercise-in-frustration/">https://www.aiweirdness.com/an-exercise-in-frustration/</a>.</li>
            <li>Shane, Janelle. “When Algorithms Surprise Us.” AI Weirdness, 13 Apr 2018, <a href="https://www.aiweirdness.com/when-algorithms-surprise-us-18-04-13/">https://www.aiweirdness.com/when-algorithms-surprise-us-18-04-13/</a>.</li>
        </ul>
    </details>
    <details><summary><strong>Writing to have done</strong></summary>
        <ul>
            <li>Post to the <a href="{{site.repo_url}}/discussions">discussion forum</a> in response to the readings</li>
        </ul>
    </details>
</section>


## Plan for the day:

* [First half](#first-half): Let's discuss!
    - Warm-up writing
    - Terms, tensions, takeaways, confusions, questions, connections
    - Grok writing (around 10:30)
* Break (10 min)
* [Second half](#second-half): Let's practice!
    - Announcements / what's coming up
    - Options
        * Studio time
        * People's choice options: the story so far, Q&A
        * Language models at a first approximation: building a Markov chain
    - EXT / Studio time
        * Reflective writing
        * Set goals
        * Work toward them
        * Exit note
* [Homework for next time](#hw)

<a id="first-half"></a>
## First half: Discussion

### Warm-up writing

Like last week, not knowing as I write this what you've been thinking about, I'd like you to start by calling to mind the readings for this week. What stands out to you as a particularly important **take-away**, something memorable or surprising? What stands out as an **unresolved** point of tension or confusion?

Depending on your own practices, you may want to make lists or freewrite, or even draw a picture or diagram. Either way, I want to spend 5 minutes on this composing-to-center. I won't collect it, but I will ask for volunteers to share.


### Let's talk!

If we get to grok-writing by around 10:15, that should give us about equal time to dig into ideas now and then to dig into process in the second half.

And as usual, it would be great if we could take some collaborative notes at [bit.ly/dsam{{site.course.slugterm}}-notes](https://bit.ly/dsam{{site.course.slugterm}}-notes).

<details><summary>Some possible passages for consideration / moments to revisit, if needed</summary>
<ol class="spaced">
    <li><details><summary>The visibility paradox from another angle</summary>
        <blockquote>On one hand, removing these problematic datasets from the internet may seem like a victory. The most obvious privacy and ethical violations are addressed by making them no longer accessible. However, taking them offline doesn’t stop their work in the world: these training sets have been downloaded countless times, and have made their way into many production AI systems and academic papers. By erasing them completely, not only is a significant part of the history of AI lost, but researchers are unable to see how the assumptions, labels, and classificatory approaches have been replicated in new systems, or trace the provenance of skews and biases exhibited in working systems. (Crawford and Paglen)</blockquote>
        <p></p>
        </details>
    </li>
    <li><details><summary>Data <em>about</em> vs. data that <em>serves</em></summary>
        <blockquote>
            <p>Undocumented people, immigrants, and people of color in lower-income spaces also tend to be over-surveilled. In other words, they’re more likely to have data and information collected about them with- out their consent, or they’re forced to give it up to get access to basic needs. For example, if you qualify for food stamps in the US, you know that you had to share a lot of information about yourself with the local government, whereas your wealthier neighbor likely hasn’t been forced to in the same way.</p>
            <p>This overcollection of data <em>about</em> some people and undercollection of data that <em>serves</em> those people results in a cycle of data violence that is passed on to these algorithms. (Onuoha and Mother Cyborg, 63–4)</p>
        </blockquote>
        </details>
    </li>
    <li><details><summary>When the frustration is part of the point</summary>
        <blockquote>
            <p>If you were able to come up with a social algorithm that can determine who is interesting and fun in an equitable way... amazing! <strong>We suspect that you may have stopped at some point and questioned the activity.</strong> Maybe you thought that there was no good way of telling how fun or interesting someone is. Or maybe you considered that ideas of “fun” and “interesting” are contextual, and might be different for different people. Maybe you just designed an algorithm that would make it so you could attend the party!</p>
            <p>This activity is meant to show just how complex humans are and how attributes like “interesting” and “fun” are relative to whoever is designing the algorithm. (Onuoha and Mother Cyborg 41, emphasis added)</p>
        </blockquote>
        <p>What did you think of the writing exercises / thought experiments in the "People's Guide to Tech"? Did anyone try them out?</p>
        </details>
    </li>
    <li><details><summary>The revision question</summary>
        <p>In "An Exercise in Frustration," Janelle Shane documents the difficulty she had in getting the image generator DALL-E3 (via ChatGPT4) to revise according to her instructions. Given what you've read/seen about how these models are trained, do you think a model with a text-based output would have the same difficulty with revising? Why or why not? Would it be frustrating in the same way? Why or why not?</p>
        </details>
    </li>
</ol>
</details> <!-- end of discussion prompts -->

### Grok writing

<div class="alert alert-success">
    <p>Spend some time putting marks on a page to help you think through, and consolidate for yourself, what we discussed today. What do you want to remember? What are you left wondering?</p>
</div>

After a few minutes, I'll ask everyone to share one thing, to which we'll all say, simply, "thank you."

<a href="week-03#an-explanation" class="smaller" title="We skipped this explanation in week 3, but it's there if you're curious">Why this terminology?</a>


## Break (10 minutes)
Assuming we left off at 10:30, let's aim to start up again at 10:40 or so. That should beat the elevator rush for 11am classes.


<a id="second-half"></a>
## Second half: Let's practice

We have a few options here. It might help you choose to remind you where we're going in the next couple of weeks:

* There's **no in-class meeting next week**: it's Pitt's "fall break" on Monday and Tuesday.
    - I won't have office hours on Monday, but I will this Thursday and next, and you can also email me to set up an alternative time if that doesn't work for you.
* When we get back, it's already time for our second presentation cycle!
    - If you didn't get to present and discuss your project in class last time, you will this time around.
    - Even so, everyone should record a five-minute video (give or take), and everyone will write and receive two written peer reviews.
* Shortly thereafter, we'll start hitting our "People's Choice" weeks. To give me a little time to prepare assignments in response to your interests, part of your homework *this* week will be to take a survey of some options I've brainstormed.

<div class="alert alert-info">
So for today's second half, you could:

<ol>
    <li>Work on your own projects in a <a href="#studio">co-working studio</a>.</li>
    <li>Review the <a href="#choices">choices</a> in the survey and discuss or propose new topics (or readings) I may be missing.</li>
    <li>Stay focused on machine learning and AI by doing a shared exercise I found to help us grok how generative models work by building a very simple one: an analog <a href="#markov">Markov chain</a>.</li>
</ol>
</div>

We could potentially combine 2 and 1, but 3 would probably use the full time.

Thoughts? Inclinations?


<a id="studio"></a>
### Option 1: Studio. We begin with reflective writing

Each time you head into a studio session, I'll ask you to **begin by thinking in private writing and then set some public goals for the day**. For today, you might begin with these questions:

1. What is exciting about your project right now? What keeps you returning to it?
2. When you look back at the notes in your Mindful Practice Journal, what had you been planning to do next? Of those things, what piece or chunk might you reasonably complete in the class time we have left?
3. In processing the feedback from the last iteration, was there anything you wanted to do alongside a classmate?

<div class="alert alert-success">When you have a sense of what you'd like to achieve by the end of class or by next week, please write them into the shared google doc: <a href="https://bit.ly/dsam{{site.course.slugterm}}-notes">bit.ly/dsam{{site.course.slugterm}}-notes</a>. This helps with accountability – and helps me find where I can be most helpful during the studio time.</div>

Then get started on those goals, and call me over as needed!

<div class="alert alert-info"> Don't forget to save and commit (if you're using git/GitHub) and to log this time in your Mindful Practice Journal.</div>

#### Exit note
When the end of the class is approaching, **please head back into the <a href="https://bit.ly/dsam{{site.course.slugterm}}-notes">shared notes doc</a>** and respond to your own note from earlier:
* How far did you get?
* What are your new priorities for the coming week?

<a id="choices"></a>
### Option 2: Preview the survey

I've put together a [survey of possible seminar topics](https://forms.gle/y5d2pCbQoyfdA3ag9) – currently twelve potential weeks' worth of reading/activity sets, grouped roughly into clusters on programming and markup; data and metadata; the digital in the world; and digital academia.

<div class="alert alert-success">In groups of two or three, read through the list together and talk out the pros and cons of each item. You can look up the potential sources I've included, if you want, or ask me any questions that come up!</div>

NB: There's no need to reach consensus within your group; I mainly want groups to avoid the awkward silence – or, alternatively, the awkward slow train of trying to talk about twelve things *all* together.

Likewise, I'm not expecting anyone to finalize your vote today, but I do hope to have your scores by the end of the week so I can compile them and bring them back for a whole-group discussion.

EXT: When your group is finished, use the remaining time for [studio](#studio).

<a id="markov"></a>
### Option 3: Building a(n analog) Markov chain

When we say that an AI model "learns" to predict future texts from past texts, what do we mean? In this exercise, we'll construct a rough approximation of the process by building generative algorithms from short phrases with recurring bits of language.

Credit for this exercise goes to [Gabriel Egan](https://wac.colostate.edu/repository/collections/textgened/ai-literacy/understanding-markov-chains/), who in turn draws on Douglas Hofstadter's _Gödel, Escher, Bach_.

#### Part 1: algorithm as a flow chart for producing text

First we have to know what we're trying to make. Come with me to [a little slide deck on Recursive Transition Networks](https://docs.google.com/presentation/d/1vosRqj2kAJIqbExYkqxh80yE6x1p4if13w3wWTwRSPE/edit?usp=sharing).

a. The flow
b. Assign probabilities (now it's a Markov chain)
c. Enact the randomness
d. Have some fun with it
e. A recursive network (but note that it "bottoms out")
f. More generators! [verbs](https://perchance.org/verb), [prepositions](https://perchance.org/preposition), [etc](https://perchance.org/useful-generators)

#### Part 2: algorithm for *producing* a flow chart from text

For this exercise, you'll need two pieces of paper – or one slide (as in PowerPoint) and one table (as in Excel). If you're using paper, the first should be held in landscape (horizontal) orientation; the second can be either landscape or portrait (vertical).

Choosing one of the short phrases below, proceed through the following steps. (NB: These are modified only slightly from Egan's; my insertions are underlined and deletions are struck through.)

Options for texts:
* "It was the best of times, it was the worst of times" (Dickens)
* "Beauty is truth, truth beauty,—that is all
Ye know on earth, and all ye need to know" (Keats)
* "Every cat is an animal, but not every animal is a cat" (Onuoha and Mother Cyborg 43)
* "all examples of deep learning are examples of machine learning, even though not all machine learning is deep learning" (Onuoha and Mother Cyborg 50)


<blockquote>
    <ol class="spaced">
        <li>Draw a ["Start"] box on the left side of your  <ins>first</ins> piece of paper <ins>(or slide)</ins> and to the right of it draw a box containing the first word of the text. Draw an arrow linking "[Start]" to the first word of the text. Think of that first word as the "Current word" and underline it in the text to keep track of where you are.</li>
        <li>If the underlined "Current word" is the last word in the text and it already has an arrow to a "[Stop]" box, stop the assignment. If the underlined "Current word" is the last word in the text and it does not already have an arrow to a "[Stop]" box, draw a "[Stop]" box to the right of the box for "Current word" and link the "Current word" box to the [Stop] box with an arrow and then stop this assignment.</li>
        <li>If the underlined "Current word" is not the last word in the text, count how many times "Current word" appears in the text (including the underlined occurrence) and write that number down underneath a forward-slash division sign, as in "/3" if "Current word" appears in the text three times.</li>
        <li>On <del>a spare</del><ins>your second</ins> piece of paper<ins> (or spreadsheet)</ins>, make a "Comes next" list for "Current word" as follows. For each occurrence of "Current word" in the text, including the underlined one, write down the single word that immediately follows it. Beside each of these words that "Comes next" write how many times it "Comes next" after the "Current word" in the text and follow that count with the divisor from Step (3). Thus, if "Current word" appears in the text three times there must be three words that follow "Current word", but they are not necessarily three different words. If "Current word" is followed by the word "the" two times and is followed by the word "on" one time, write down "the 2/3" and "on 1/3" in the "Comes next" list. If one of the occurrences of "Current word" in the text is the last word in the text, add the item "[Stop]" to the "Comes next" list and add its fraction (which will be 1 over the number of occurrences of "Current word" in the text).</li>
        <li>Returning to your Markov Chain, draw a box to the right of the "Current word" box for each of the words (or the "[Stop]" token) in the "Comes next" list you made in Step (4) that you don't already have a box for, then put the word (or the "[Stop]" token) from the "Comes next" list inside the box and draw an arrow from the "Current word" box to each of these new boxes. If one of the words (or the "[Stop]" token) in the "Comes next" list made in Step (4) already has a box drawn in a previous step, don't draw a new box but instead draw the arrow from the "Current word" box to the existing box. Beside each arrow put the associated "weight" from the "Comes next" list made in Step (4). Thus, if "Current word" is followed by the word "the" two times and is followed by the word "on" one time, write beside the arrow from the "Current word" box to the "the" box the fraction "2/3" and write beside the arrow from the "Current word" box to the "on" box the fraction "1/3".</li>
        <li>Cross "Current word" off from the text. The next word in the text is your new "Current word", so underline it. You must already have a box for this new "Current word" since you just drew it in Step (5) or in a previous iteration of that step.</li>
        <li>Go to Step 2.</li>
    </ol>
</blockquote>

EXT: Waiting for others to finish? Try a second one!
EXT: Done two already? Read ahead in the lesson plan (or into the EXT readings for today)

#### Part 3: share and reflect

How did it go? Do you have any new insights or questions to pose about how computers might crawl text and assign probabilities to the features they find there?

In reality, it's quite a bit more convoluted than this: rather than map literal words directly, for example, they build classes, or groups, of recurring word-types and assign weights both to the groups and to the terms within them. And then they build groups of groups, and so on. (And that's not even mentioning the fact that [they don't really know what words are](https://www.youtube.com/watch?v=uSinkCeUg9U).)

But if you can imagine this process being sped up to the point where electrons, rather than eyes, are moving back and forth over the text, you won't be too far off from getting the idea. If you want further details, check out the relevant EXT sources from this week, especially Cheung.




<a id="hw"></a>
## Homework for Next Time

<div class="alert alert-danger">
No class meeting next Monday: it's "fall break." I'll hold <a href="../office">office hours</a> today, on both Thursdays, and by appointment.
</div>

* **Before you forget**, and ideally by the end of this week, please [respond to the survey on the People's Choice topics](https://forms.gle/y5d2pCbQoyfdA3ag9). I'll compile everyone's rankings and we can finalize after the break.

* When we get back for week 9 (October 21), there are no new shared readings to discuss. Instead, **pour that extra time into your project's _developing public-facing deliverable_ and a second _five-minute pre-recorded presentation_.**

* At this point in the iterative cycle, you should be able to _look back through your journal_ to answer the following:

    * What sources / objects are you working with? (i.e. briefly remind or update us)
    * What have you done with or to those sources?
    * What have you learned in the process so far?
    * What are your next steps?


* Post links to both your deliverable (in whatever form) and your presentation file (or the video itself, if GitHub lets you) on the [Discussion forum]({{site.repo_url}}/discussions/).

* Continue logging your time in a [Mindful Practice Journal](../projects#mindful-practice-journal) and (if you're using GitHub) in commit messages.

I won't require you to come to office hours, but you are certainly welcome to [sign up](../office) if you'd like! Or email me if that's easiest.
