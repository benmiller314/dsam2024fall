
# Week 12: Data Visualization and Analysis
<span class="date">November 11, 2024</span>

<section class="prereqs">
    <details><summary><strong>Texts to have read / watched</strong></summary>
        <ul>
            <li>Cairo, Alberto. <em>The Truthful Art: Data, Charts, and Maps for Communication</em>, New Riders, 2016
              <ul>
                <li>“3: The Truth Continuum.” <a href="https://learning.oreilly.com/library/view/the-truthful-art/9780133440492/ch03.html">https://learning.oreilly.com/library/view/the-truthful-art/9780133440492/ch03.html</a>.</li>
                <li>“5: Basic Principles of Visualization.” <a href="https://learning.oreilly.com/library/view/the-truthful-art/9780133440492/ch05.html">https://learning.oreilly.com/library/view/the-truthful-art/9780133440492/ch05.html</a>.</li>
              </ul>
            </li>
            <li>D’Ignazio, Catherine, and Lauren F. Klein. “Chapter Six: The Numbers Don’t Speak for Themselves.” <em>Data Feminism</em>, MIT Press, 2020, pp. 149–72. mitpressonpubpub.mitpress.mit.edu, <a href="https://ebookcentral.proquest.com/lib/pitt-ebooks/detail.action?docID=6120950">https://ebookcentral.proquest.com/lib/pitt-ebooks/detail.action?docID=6120950</a>.</li>
            <li>Datawrapper Academy&nbsp;–&nbsp;the documentation center for one of my go-to tools for visually presenting data once I know what I want it to say.
              <ul>
                <li>“Our Explanatory Approach to Visualizing Data.” 31 Aug. 2020, <a href="https://academy.datawrapper.de/article/279-our-explanatory-approach">https://academy.datawrapper.de/article/279-our-explanatory-approach</a>.</li>
                <li>“How to Create Your First Datawrapper Chart.” 24 Oct. 2023, <a href="https://academy.datawrapper.de/article/245-how-to-create-your-first-datawrapper-chart">https://academy.datawrapper.de/article/245-how-to-create-your-first-datawrapper-chart</a>.</li>
                <li>“How to Prepare Your Data for Datawrapper in Excel or Google Sheets.” 13 June 2022, <a href="https://academy.datawrapper.de/article/240-how-to-prepare-your-data-for-datawrapper-in-excel-or-google-sheets">https://academy.datawrapper.de/article/240-how-to-prepare-your-data-for-datawrapper-in-excel-or-google-sheets</a>.</li>
                <li>“How to Create a Dot Plot.” 24 June 2020, <a href="https://academy.datawrapper.de/article/122-how-to-create-a-dot-plot">https://academy.datawrapper.de/article/122-how-to-create-a-dot-plot</a>.</li>
                <li>“How to Create a Locator Map.” 11 June 2021, <a href="https://academy.datawrapper.de/article/161-how-to-create-a-locator-map">https://academy.datawrapper.de/article/161-how-to-create-a-locator-map</a>.</li>
                <li>“What to Consider When Creating Pie Charts.” 4 Jan. 2021, <a href="https://academy.datawrapper.de/article/127-what-to-consider-when-creating-a-pie-chart">https://academy.datawrapper.de/article/127-what-to-consider-when-creating-a-pie-chart</a>.</li>
              </ul>
            </li>
        </ul>
    </details>
    <details><summary><strong>Writing to turn in</strong></summary>
        <ul>
            <li>a <a href="{{site.repo_url}}/discussions/9">discussion forum</a> post in response to the readings</li>
        </ul>
    </details>
</section>

## Plan for the day:

* [First half](#first-half): Let's discuss!
    - Discussion
        * Variable types and how knowing them can help
        * Questions, comments, connections about models, principles, and perspectives
        * EXT: Why charts and tables, not just numbers and text?
    - Grok writing (around 10:15)
    - Sharing (around 10:25)
* Break (10 minutes, around 10:35)
* [Second half](#second-half): Let's practice!
    - Writing to center (5 min)
    - Options!
        * OpenRefine
        * Datawrapper
        * General studio time
    - EXT: Studio
* [Homework for next time](#hw): 3rd project iteration (and...?)


## First half: Let's discuss! {#first-half}

I want to start with some discussion topics I had on the agenda for last week but didn't quite get to.

### Variable types vary

Not all data is numerical. Some (quite a bit, actually) is **categorical**:
* Discrete possible values, rather than infinite
* Usually, textual labels
* Often (but not always) mutually exclusive, distinct values – i.e. if an observation is in one category, it's not in another

Categorical variables may be **nominal** or **ordinal**:
* *Nominal* categories are essentially lists of independent *names*; they can be easily re-sorted or grouped in a variety of ways. Examples include neighborhoods, 311 request codes, or tree types.
* *Ordinal* categories have a meaningful *order*, and should be presented in that order. You wouldn't scramble days of the week or put "strongly agree" next to "strongly disagree" without passing through "neither agree nor disagree" first.
    - Important side note: you also can't take an average of a Likert scale, because the numbers 1–5 aren't really quantitative values; they're categorical (albeit ordinal) values. Ten people strongly agreeing and another ten strongly disagreeing doesn't 'average' to neutrality.

<div class="alert alert-info">
    <p><strong>Categorical variables are fundamentally <em>ways to filter or group your data.</em></strong></p>
    <p>You can <strong>filter to one value</strong> within a category (especially a nominal category) as a way of making an otherwise overwhelming dataset manageable: e.g. to look at just pothole requests, or just garbage collection, rather than all of the hundreds of types of requests in the 311 database.</p>
    <p>You can <strong>group by a category that contains multiple values</strong> to see how other variables change when aggregated within these groups: e.g. to see how tree counts vary by neighborhood, you first summarize the tree counts for each neighborhood value.</p>
    <p>By combining those approaches, you can zoom in on the questions that really matter &ndash; and the answers you're able to communicate.</p>
</div>


### Models, Principles, and Perspectives

Now on to this week's readings, on [mental models (and bugs)](https://learning.oreilly.com/library/view/the-truthful-art/9780133440492/ch03.html) and how they relate to [core visualization principles](https://learning.oreilly.com/library/view/the-truthful-art/9780133440492/ch05.html); on the [non-neutrality of graphs and numbers](https://ebookcentral.proquest.com/lib/pitt-ebooks/detail.action?docID=6120950) (and figure titles); and on [how various graph types emphasize particular relationships](https://academy.datawrapper.de/).


What's coming up for you? Questions, comments, confusions, connections? Skim your notes and <a href="https://github.com/benmiller314/dsam2024fall/discussions/9">discussion posts</a> and remind yourself what's in there.

Let's discuss! We can take notes at [bit.ly/dsam{{site.course.slugterm}}-notes](https://bit.ly/dsam{{site.course.slugterm}}-notes). If we get to grok-writing by around 10:15, that should give us enough time to share and break and still get some practice in.

Some keywords from the reading, should we need starting points:
* big dick data
* zombie data
* raw data
* data setting
* the truth continuum
* relative variable
* patternicity bug
* storytelling bug
* confirmation bug

<!--
<details><summary>And also some passages</summary>

    <details><summary>From Cairo 3, quoting Raj Kamal</summary>
    <blockquote>
        <p>We humans love exciting stories. We see a single event and we transform it into a general rule. We stereotype and generalize [...] It happens to me, to you, to all of us. Being aware of this mental bug is paramount for visualization designers, but we're generally oblivious to it, with dire consequences. In January 2014, infographics designer <strong>Raj Kamal</strong> wrote an article in which he explained his creative process:</p>
        <blockquote>
            <p>It’s the “message” that decides the presentation. The numbers, visual, or text or a combination of these are to only support the way of putting the message across. This also changes the way one conceptualizes a graphic. The thought starts with the message and then gets into putting other related information together to support it instead of starting with the data and thinking of what to make of it (...) The advantage of taking this route is also that you are not just restricted by topics or numbers or just presenting “news.” You can go a step further and air your “views,” too, to make a point.</p>
        </blockquote>
        <p>Proceeding this way is a recipe for disaster, but it is one that is too common in the news industry. A managing editor comes up with a headline—“We’re going to show how raising the minimum wage increases unemployment”—and then asks her reporters to just look for data to support it. It is the flaw, I believe, behind Wired’s story about the death of Web browsers, discussed before.</p>
        <p>Storytelling can be a potent tool for communicating effectively, but it is dangerous if it blinds us toward evidence that should compel us to tweak or discard our models.</p>
        </blockquote>
    </details>
</details>
-->


### EXT: Why charts and tables, not just numbers and text?

Let's talk about [Anscombe's quartet](https://en.wikipedia.org/wiki/Anscombe%27s_quartet)

One takeaway: data's shapes not only help readers get quickly to the overall story we want to tell, they also help <em>us</em> figure out what that story might be.


### Grok writing

<div class="alert alert-success">
    Spend some time putting marks on a page to help you think through, and consolidate for yourself, what we discussed today. What do you want to remember? What are you left wondering?
</div>

After a few minutes, I'll ask everyone to share one thing, to which the only response will be "thank you."



## Break (10 minutes)
I'm guessing we'll hit the break at around 10:35 or so. Try to be back for a 10:45 start, so we have a full hour to get hands-on.

## Second half: Let's practice! {#second-half}

### Writing to center

<div class="alert alert-success">
    <p>Let's begin with a little reflective writing. I won't collect this, but keep it somewhere you'll be able to find it later.</p>

    <ul>
        <li>Think about your DSAM project. What's exciting about it? What keeps you coming back to it?</li>
        <li>Given the ways you've processed your source material, what <em>categories</em> are you working with? Do you have a sense yet of how evenly they divide your data? (If not, OpenRefine might help you figure it out.) Is there one category you'd like to zoom in on, or several you want to compare across?</li>
        <li>Given the ways you've divided your source material, what <em>correlations</em> do you predict you'll find? That is, what aspects of your sources do you think will grow or shrink in the same (or opposite) directions? Try to put it in a sentence, e.g. <em>Where I see more X, I expect to see more Y.</em></li>
    </ul>
</div>

### Options for studio

You have some options for hands-on time, depending on what you're working with and where you are in the process. Remember that the goal is to have some _claims_ to make and post in video form by this Friday!


1. We didn't finish with **OpenRefine** last week; if you have data that needs alignment or refinement, that might be a good place to begin.
    - This is an especially useful tool whenever you have multiple values that you want to split apart or combine.
    - With split values within a column, you can also facet, cluster, and edit to get more consistent tagging and more accurate counts within categories.
    - NB: when faceting, you can click on the choice count to show tab-separated values that you can copy and paste to Excel, Datawrapper, etc.

2. You might want to work through some **Datawrapper** tutorials, starting with their data. Some suggestions below!
    - NB: If you haven't already, I strongly advise practicing new tools with their sample data before you dive into your own. They provide data they know will go smoothly, so you can make a chart and modify it in under 10 minutes, and get a feel for how the tool works and what options it gives you. Setting up your own data could easily take 2 or 3 times longer, depending on how (dis)similar it is to their expected defaults.

3. You might forgo datavis today, despite the topic of the week, and just have **general studio time** to work on your own project – whatever step you're up to – in a dedicated co-working environment. You can also call me over with questions, especially if you're not able to make it to office hours.


#### Datavis starting points: tasks and tutorials

> <em>Principle:</em> "Think about the task or tasks you want to enable, [... and] <strong>plot what you need to plot</strong>. (Cairo ch 5)

Suppose you wanted to...

<details><summary>Rank nominal categories</summary>
    <p><strong>Description:</strong> find the top (or bottom) <em>N</em> categories by values (or counts) along one shared axis of comparison</p>
    <p><strong>Tool:</strong> <a href="https://academy.datawrapper.de/category/74-bar-charts">bar charts</a> / <a href="https://academy.datawrapper.de/category/75-column-charts">column charts</a></p>
    <p><strong>Color strategy:</strong> use spot color to highlight one or two particular values of interest, and let the rest be a neutral gray; rainbows aren't helpful.</p>
    <p><strong>Tip:&nbsp;</strong>Use horizontal bars when it makes the labels easier to read.</p>
    <p>&nbsp;</p>
    <p><iframe id="datawrapper-chart-fZyMZ" style="width: 0; min-width: 100% !important; border: none;" title="Squirrel Hill may have the most trees in Pittsburgh (by far), but Oakland's not too shabby" src="https://datawrapper.dwcdn.net/fZyMZ/2/" height="389" aria-label="Bar Chart" data-external="1"></iframe></p>
    <p>&nbsp;</p>
</details>
<details><summary>Consider changes in rank</summary>
    <p><strong>Description:</strong> When you want to see how the <em>order</em> of one variable changes in relation to a change in categorical value (subgroup) or time.</p>

    <p><strong>Tools:</strong> <a href="https://stephanieevergreen.com/slopegraph/">slope graph</a>, <a href="https://blog.datawrapper.de/favorite-popular-chart-types/">bump chart</a></p>

    <p><strong>Color strategy:</strong> use spot color to highlight one or two particular lines of interest, and let the rest be a neutral gray. With only two points to compare (slope graph), you could also choose a uniform color for all values that ascend (or those that descend).</p>

    <figure>
        <iframe title="Datawrapper Chart Type Ranking | 2013 - 2020" aria-label="Interactive line chart" id="datawrapper-chart-PMTIu" src="https://datawrapper.dwcdn.net/PMTIu/2/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="818" data-external="1"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"]){var e=document.querySelectorAll("iframe");for(var t in a.data["datawrapper-height"])for(var r=0;r<e.length;r++)if(e[r].contentWindow===a.source){var i=a.data["datawrapper-height"][t]+"px";e[r].style.height=i}}}))}();</script>
        <figcaption>You can make a bump chart using a line graph. This one uses dates for the x-axis, but you could also use categories – ideally, though, they'll have a sensible or consistent order.</figcaption>
    </figure>
</details>
<details><summary>Compare proportions</summary>
    <p><strong>Description:</strong> compare selections where exact numbers matter less than ratios, or within an ordered range of values (e.g. from "strongly agree" through "strongly disagree")</p>
    <p><strong>Tool:</strong> <a href="https://academy.datawrapper.de/article/17-how-to-create-a-stacked-bar-chart">stacked bar chart</a></p>
    <p><strong>Color strategy:</strong> To show variation within a single line, it often makes sense to use one or two hues (e.g. blue or orange) and vary the saturation or lightness of that basic color; that usually means it'll still be distinguishable in black and white, but check.</p>
    <figure>
        <a href="https://app.datawrapper.de/chart/YAoqp/visualize"><img src="https://canvas.pitt.edu/courses/217600/files/13999725/preview" alt="Stacked bar chart of ten categories of &amp;quot;successful individuals,&amp;quot; showing rates of no college, some college, or elite college attendance. Very few have no college." data-api-endpoint="https://canvas.pitt.edu/api/v1/courses/217600/files/13999725" data-api-returntype="File" /></a>
        <figcaption>The page linked above has been removed, but here's <a class="inline_disabled" href="https://theconversation.com/the-myth-of-the-college-dropout-75760" target="_blank" rel="noopener">the figure in context</a>: see the tell-tale signs this was created in Datawrapper?</figcaption>
    </figure>
    <p><strong>Color strategy:</strong> If you have a Likert-like scale with two extremes and a neutral, use a light gray or beige in the middle and the most saturated/dark variations of your two hues for the extremes.</p>
        <figure>
            <iframe title="Trust high for reporting on migrant crisis, low for reporting on Ukraine conflict " aria-label="Stacked Bars" id="datawrapper-chart-y7EwR" src="https://datawrapper.dwcdn.net/y7EwR/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="365" data-external="1"></iframe>
            <script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"]){var e=document.querySelectorAll("iframe");for(var t in a.data["datawrapper-height"])for(var r=0;r<e.length;r++)if(e[r].contentWindow===a.source){var i=a.data["datawrapper-height"][t]+"px";e[r].style.height=i}}}))}();</script>
            <figcaption>One of datawrapper's <a href="https://academy.datawrapper.de/article/151-examples-of-datawrapper-stacked-bar-charts">examples of stacked bars</a>, this one using a diverging color scale to match the diverging scale from high to low trust</figcaption>
        </figure>
</details>
<details><summary>Chart differences in value</summary>
    <p><strong>Description:</strong> When you want to see how the relationship between two or three values changes across categories</p>
    <p><strong>Tools:</strong> <a href="https://academy.datawrapper.de/category/112-dot-charts">dot, range, and arrow plots</a>; with only two categories, <a href="https://stephanieevergreen.com/slopegraph/">slope graph</a>.)</p>
    <p><strong>Color strategy:</strong> If the subcategories are nominal, aim for a <a href="https://chartio.com/learn/charts/how-to-choose-colors-data-visualization/#qualitative-palette">qualitative color palette</a>, like <a href="https://waldyrious.net/viridis-palette-generator/">viridis</a>, that varies both the hue and the brightness/saturation; this will give your readers the best hope of distinguishing between categories. Even so, try to keep the number of categories at five or fewer.</p>
    <p><a href="https://app.datawrapper.de/chart/yIDhg/visualize#refine"><img src="https://canvas.pitt.edu/courses/217600/files/14002550/preview" alt="Range plot: average earnings of Americans by highest degree. The higher the degree, the higher the pay gap between women and men: with a doctorate degree, men earn $151k to women's $91k." data-api-endpoint="https://canvas.pitt.edu/api/v1/courses/217600/files/14002550" data-api-returntype="File" /></a></p>
</details>
<details><summary>Show geographical variation</summary>
    <p><strong>Description:</strong> When you suspect (or know) that a particular variable you're tracking is related to where you measure it.</p>
    <p><strong>Tool:</strong> <a href="https://academy.datawrapper.de/category/278-symbol-maps">symbol maps</a> for discrete points, <a href="https://academy.datawrapper.de/article/134-what-to-consider-when-creating-choropleth-maps">choropleth maps</a> for area-based aggregate summaries</p>
    <p><strong>Color strategy:</strong> In a symbol map, color can encode a category while size encodes a quantitative value; use a categorical color scheme and keep the number of categories small (usually 5 or below). In a choropleth map, the same logic as in stacked bar graphs applies: if you're showing one continuous variable, use a single hue and vary the luminosity; if you're showing a divergent scale (e.g. agree/disagree, increase/decrease), use a divergent scale with a neutral gray or tan for the values in the middle.</p>
    <figure>
        <iframe title="Polling stations in NYC (2018)" aria-label="Map" id="datawrapper-chart-USufF" src="https://datawrapper.dwcdn.net/USufF/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="687" data-external="1"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"]){var e=document.querySelectorAll("iframe");for(var t in a.data["datawrapper-height"])for(var r=0;r<e.length;r++)if(e[r].contentWindow===a.source){var i=a.data["datawrapper-height"][t]+"px";e[r].style.height=i}}}))}();</script>
        <figcaption>One of Datawrapper's <a href="https://academy.datawrapper.de/article/262-examples-of-datawrapper-symbol-maps">examples of symbol maps</a>, this one using a categorical color scale.</figcaption>
    </figure>
    <figure>
        <iframe title="Average Family Sizein New York City Neighbourhoods" aria-label="Map" id="datawrapper-chart-EndwC" src="https://datawrapper.dwcdn.net/EndwC/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="689" data-external="1"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"]){var e=document.querySelectorAll("iframe");for(var t in a.data["datawrapper-height"])for(var r=0;r<e.length;r++)if(e[r].contentWindow===a.source){var i=a.data["datawrapper-height"][t]+"px";e[r].style.height=i}}}))}();</script>
        <figcaption>One of Datawrapper's <a href="https://academy.datawrapper.de/article/149-examples-of-datawrapper-choropleth-maps">examples of choropleth maps</a>, this one using a sequential color scale for the areas of interest – and grayscale for areas with no data being reported.</figcaption>
    </figure>
</details>
<details><summary>Understand the distribution of frequencies</summary>
    <p><strong>Description:</strong> When you have a lot of values and you want to see not only the average or the most frequent, but how commonly they cluster around the average or diverge from it.</p>
    <p><strong>Tool:</strong> <a href="https://www.displayr.com/how-to-make-a-histogram-in-excel/">histograms</a></p>
    <p><strong>Color strategy:</strong> Generally speaking, keep it all one color: what you want to compare is the tops of the bars. However, you may find that you want to <a href="https://blog.datawrapper.de/interpolation-for-color-scales-and-maps/">correlate the histogram to another visualization, like a choropleth map</a>, in which case you might want a one- or two-color scale that shows increasing intensity to highlight map regions.</p>
    <figure>
        <img alt="black and white histogram of unemployment rate by number of counties, with a strip plot below" src="https://lh3.googleusercontent.com/ksMwjRN_Yx4sGMBXFx8qQKV2l5F4psld5UoSq0oWGYu6RmBZnveyueNffqZpDUHsxHry6RnlINGFXp8aJMiLtp7fONrA2wF4mo5Tpwe_Ee8-JK0njglwtAtfAVJsgJGFqml0-pnR47CKZMPtCg"/>
        <img alt="histogram with quantile interpolation and a correspondingly colored choropleth map of the united states" src="https://lh3.googleusercontent.com/7enlkQ3iO1ez3kA4Dowx7GpWQcWPC5mJsEkcUiYTIt-asnATp_q5Bjskr0rPdjp50UM3qVMzqHhMeQ9ubJvnZt9_uDw4B2LGIf87uBiZKAOqEQU2mdR69i7dfIkYShl9ULHez6PPWYS83CmcFw"/>
    <figcaption>Two figures from "<a href="https://blog.datawrapper.de/interpolation-for-color-scales-and-maps/">How to choose an interpolation for your color scale</a>" by Lisa Charlotte Muth for the Datawrapper blog, July 25, 2022.</figcaption></figure>
</details>


### EXT: Studio

Feeling good on all the above? Use the remaining time to work on your project.




## Homework for next time {#hw}

* As always, continue working on your project, and take notes in your [Mindful Practice Journal](projects.md).

* <strong>By this Friday, Nov 15</strong>, [**pre-record** a 5-minute presentation](projects#presentations-and-peer-review) on your independent project, so we can watch before class. For this iteration, you should be able to *look back through your journal* to answer the following:

    - What questions are you pursuing by processing your sources / objects? (Remind us or update us)
    - **NEW:** What answers do you have so far, however tentative?
    - What are your next steps to deepen your questions and answers?
    - What have you learned in the process?

* Post your video to the [discussion forum]({{site.repo_url}}/discussions); in the same post, **include a link** to your developing public-facing project, even if it's the same link as last time.
    - <div class="alert alert-warning">What does a "public-facing project" entail? As we discussed last week, by the end of the term you should have at least a <strong>landing page</strong> introducing your project to new viewers, even if that landing page is just a README file or tab within a worksheet.</div>

* **Watch all your classmates' videos before class.** This should allow us to dive right into sayback and feedback during next week's class.

* Optionally, schedule a meeting with Ben in [office hours](office) for early feedback as you build your presentation and public-facing site.
