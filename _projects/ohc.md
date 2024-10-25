---
layout: page
title: Tapering Antidepressants
description: Understanding how people tapering antidepressants use online help communities to find and provide support.
img: assets/img/ohc.jpeg
importance: 3
category: work
---
This is the first part of a research project with advisors [Alexandra Papoutsaki](https://cs.pomona.edu/~apapoutsaki/) (Pomona College) and [Daniel Epstein](https://depstein.net/) (University of California, Irvine) on tapering antidepressants. This part focuses on an online health community assisting people with discontinuing psychiatric medications.

This work resulted in a paper published at CSCW2021. Read the full paper [here](https://dl.acm.org/doi/abs/10.1145/3479564). Watch the presentation [here](https://www.youtube.com/watch?v=e-nOYW7felM).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <h3>About the Project</h3>
        <h5>Background</h5>
        <p>Every year, nearly 1 in 5 adults in the United States experience a diagnosable mental illness (e.g., depression, anxiety, bipolar disorder). Medical professionals often prescribe psychiatric drugs to help manage mental illnesses, with 1 in 6 U.S. adults filling one or more prescriptions annually. While long-term treatment with psychiatric drugs may be necessary in certain cases, treatment discontinuation is often clinically advisable. For example, some patients experience significant side effects that may negatively affect their daily life (e.g., dizziness, indigestion, loss of libido, etc.). Unfortunately, upon treatment discontinuation, as many as a quarter of people experience side effects of withdrawal, with symptoms that can be severe and last for several weeks, months, or even years. Additionally, patients report that providers often fail to disclose the potential risk of withdrawal symptoms and do not provide adequate support for their safe discontinuation. As a result, a number of people experiencing difficulties discontinuing their medication seek support in online health communities (OHCs).</p>
    </div>
    <div class="col-sm mt-3 mt-md-0 align-self-center">
        <h4 align="center">What I Did:</h4>
        <ul>
            <li>Conducted a <b><i>literature review</i></b> on online health communities, psychiatric drugs, and sensemaking.</li>
            <li>Open-coded and <b><i>thematically analyzed</i></b> thousands of posts from the online health community <i>Surviving Antidepressants.</i></li>
            <li><b><i>Sketched screens</i></b> for a mobile app that would assist patients with tapering their medications (some of which you can see in the gallery).</li>
            <li><b><i>Wrote a Python script</i></b> to extract publically available data from the forum (i.e., member rank, date of publication, etc.).</li>
        </ul>
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <h5>The Inspiration</h5>
        It all started with an article published in The New Yorker called ["The Challenge of Going Off Psychiatric Drugs."](https://www.newyorker.com/magazine/2019/04/08/the-challenge-of-going-off-psychiatric-drugs) In this piece, Rachel Aviv describes in detail the struggles of Laura Delano to get off of the medications she was prescribed by her providers. While Laura is an individual case, the article mentions a couple of online forums where people experiencing similar issues come together to seek advice and emotional support, as they embark on their individual journeys of discontinuing psychiatric drugs. One of these communities is Surviving Antidepressants, which we started looking into further, as it was one of the largest and longest-running forums on the topic.
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/laurany.jpg" title="Picture of Laura Delano" class="img-fluid rounded z-depth-1" %}
    </div>
</div>


<h5>Exploration and Analysis</h5>
Our team began exploring the forum in the summer of 2020, keeping an eye for recurring themes or concerns shared by forum members. In this initial stage, we ended up reading around 1,000 posts across more than 40 threads. Once we had a better idea of what the general recurring themes are, we started collecting and coding posts from one of the most popular sub-forums. We decided to focus on and gather data from threads that were started between 2017 and 2020. We made the decision to exclude any posts that engaged with the coronavirus pandemic.

We analyzed posts from 25 threads to inform our [codebook](https://depstein.net/assets/docs/cscw21b_supplemental.xlsx). We then analyzed 148 threads, which resulted in a dataset of 8,713 posts in total. We met on a weekly basis to discuss any emerging new themes or any questions we might have.

<h5>Findings</h5>
People came to the forum predominantly to seek informational support around planning new or adjusting ongoing tapers and occasionally with managing persistent post-withdrawal disorders.

We found that the core members of the forum generally operated in habitual mode, meaning that they had a shared understanding of what psychiatric drug withdrawal and tapering are. They leveraged well-defined community-built protocols, especially when it came to providing informational support to other members. The informational support provided by the forum was initially inspired by research literature, but over the year was adjusted through collective sensemaking. We also observed that certain veteran members "specialized" in the kind of advice they provide, as different members had more experience with different types of drugs. Interestingly, members also provided advice on how to navigate the medical system in order to receive the medication at the dosages that the forum, not the medical provider, recommends.

While it was mostly staff and veteran members who gave newcomers advice, all members provided emotional support.

Finally, we also observed that a lot of the forum's members expressed disappointment with and distrust towards their providers and the medical community as a whole.

<h5>Why it Matters</h5> 
Our observations of <i>Surviving Antidepressants</i> reveal that the perceived gaps in care left by the medical system can create opportunities for OHCs to develop their own support mechanisms and act as independent or even sole sources of informational support. This may be dangerous and detrimental to individuals' health, as they receive advice from people who are not trained professionals and information that is not necessarily obtained through clinical trials.


<h5>Now What?</h5>
Following these discoveries, we saw two opportunities for technological intervention:
<ul>
<li>building a platform to assist patients with discontinuing their medication by helping them track their progress;</li>
<li>building a platform to help providers create taper schedules for their patients.</li>
</ul>

While we started by sketching out potential screens for the patient platform, we decided to focus on the latter for our next step.

This work resulted in a paper published at CSCW2021. Read the full paper [*here*](https://dl.acm.org/doi/abs/10.1145/3479564).


<h3 align="center">Meet the Team</h3>

<div class="container">
    <div class="row justify-content-sm-center">
        <div class="col-sm-2 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/prof_pic.jpg" title="Georgia Kenderova" class="img-fluid rounded z-depth-1" %}
        </div>
        <div class="col-sm-2 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/alexpap.jpg" title="Alexandra Papoutsaki" class="img-fluid rounded z-depth-1" %}
        </div>
        <div class="col-sm-2 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/daniel.jpg" title="Daniel Epstein" class="img-fluid rounded z-depth-1" %}
        </div>
    </div>
    <div class="row justify-content-sm-center">
        <div class="col-sm-2 mt-3 mt-md-0">
            <div class="caption">Georgia Kenderova</div>
        </div>
        <div class="col-sm-2 mt-3 mt-md-0">
            <div class="caption"><a href="https://apapoutsaki.sites.pomona.edu/" target="_blank">Alexandra Papoutsaki</a></div>
        </div>
        <div class="col-sm-2 mt-3 mt-md-0">
            <div class="caption"><a href="https://depstein.net/" target="_blank">Daniel Epstein</a></div>
        </div>
    </div>
    <div class="row justify-content-sm-center">
        <div class="col-sm-2 mt-3 mt-md-0">
            <div class="caption"><a href="https://samuelso.net/" target="_blank">Samuel So</a></div>
        </div>
        <div class="col-sm-2 mt-3 mt-md-0">
            <div class="caption"><a href="https://faculty.uci.edu/profile/?facultyId=7037" target="_blank">Bryan Shapiro</a></div>
        </div>
    </div>
</div>
            

