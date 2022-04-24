---
title: Gulli Bot
permalink: /
hideTitle: true
layout: layouts/base.njk
eleventyNavigation:
  key: Home
  order: 1
---

<style>
    .hero {
        width: 100%;
    }

    @media (min-width: 500px) {
        .hero {
            float: right;
            width: 50%;
        }
    }

    .btn {
        display: inline-block;
        font-weight: 400;
        line-height: 1.5;
        color: #212529;
        text-align: center;
        text-decoration: none;
        vertical-align: middle;
        cursor: pointer;
        -webkit-user-select: none;
        -moz-user-select: none;
        user-select: none;
        background-color: transparent;
        border: 1px solid transparent;
        padding: .375rem .75rem;
        font-size: 1rem;
        border-radius: .5rem;
        transition: color .15s ease-in-out, background-color .15s ease-in-out, border-color .15s ease-in-out, box-shadow .15s ease-in-out;
    }

    a.btn.btn-primary {
        color: #fff;
        background-color: #b758ff;
        border-color: #b758ff;
    }

    @font-face {
    font-family: "Nothing You Could Do";
    src: url(/site/img/NothingYouCouldDo-Regular.ttf) format("truetype");
    }

    .pain-point{
        color: red;
        fill:red;
        font-family: "Nothing You Could Do", sans-serif ;
        margin: 0;
    }
</style>

<h1 class="pain-point" style="transform: rotate(-5deg);" >
How could they even think that? 
<svg version="1.1" viewBox="0 20 613 55" xmlns="http://www.w3.org/2000/svg" style="max-height:50px;">
<path d="m227 46c-4 0.8-7 2-11 3-1 0.3-2 2-2 3l0.02 0.05c-20 0.3-40 0.9-60 2-29 1-58 3-87 6-28 3-36 3-61 8-0.7 0.1-2 0.1-3 0.3-0.7 0.2-1 0.5-1 0.9-0.4 0.4-0.6 0.9-0.7 1-0.1 0.6-0.07 1 0.4 2 1 2 4 3 6 2 2-0.4 5-2 7-2 37-3 74-6 111-8 57-4 113-6 170-7 59 0.5 119 3 178 6 39 2 77 6 116 9-0.03 0.2-0.03 0.3-0.03 0.5 0.08 1 1 2 3 2 1-0.09 14-0.4 16-1 1-0.3 2-1 2-1 0.5-1 0.5-2-0.5-3-0.2-0.2-0.6-0.5-1-0.7-0.6-0.2-2-0.4-5-0.6-43-3-86-7-130-10-19-1-39-2-58-3 26-0.3 53-0.7 79-1 1-0.02 2-0.2 2-0.2 1-0.6 2-2 2-2-7e-3 -0.2-0.2-2-2-2-1-0.2-10-0.5-14-0.6-17-0.9-16-0.8-33-2-37-2-74-3-112-4-15-0.4-30-0.6-45-0.9 43-4 87-4 128-4 22-0.2 43-0.3 65-0.06 10 0.1 19 0.4 29 0.6 3 0.05 6 0.2 9 0.2 0.4 8e-3 5 0.05 6 0.03 2-0.04 2-2 2-2 0.08-0.3 0.4-3-2-3-36-5-73-4-109-5-63-2-127-1-190 0.8-28 0.9-56 3-84 4-14 0.9-28 2-42 4-1 0.2-5 0.4-6 0.7-0.8 0.1-1 0.3-2 0.5-1 0.6-1 2-1 2-0.01 0.5 0.09 2 2 3 33 7 69 3 102 2 8-0.07 17-0.1 25-0.1zm28 0.04c-10 2-20 3-29 5 24-0.3 48-0.4 72-0.2 39-0.8 79-1 118-2-25-0.9-51-2-76-2-28-0.7-56-1-84-1zm136-13c-53-0.8-106-0.3-159 1-28 0.9-56 3-84 4-11 0.7-22 1-33 3 28 3 58-0.06 86-0.3 18-0.2 35-0.2 53-0.1 45-7 91-8 137-8z" clip-rule="evenodd" fill-rule="evenodd"/>
</svg>
</h1>
<h2 class="pain-point" style="padding-left:12%">and how can I change their mind...</h2>
<img src="/site/img/gullibot.png" class="hero">
<H2>Hello, I'm Gulli Bot!</h2>
<p>
    I listen to you and gather the best reasons for and against contentious issues, weighing them based only on what
    you tell me.
</p>
<p>
    My process is transparent: You can see exactly how I decide what I believe and you can change my
    mind publicly.
 </p>
<p>
    I strive to capture all sides of an issue, including yours.
</p>

<p><b>Your Reasons. Our Analysis. Better Decisions.</b></p>
<div id="dynamic-content"></div>
<h2>Explore:</h2>
<a href="/covid-vaccine/" class="btn btn-primary">Should you take a COVID-19 vaccine?</a>
<div style="clear:both;"></div>
<script>
    if (new Date().getTime() <= new Date("2022-04-02T00:00:00").getTime()){
        document.getElementById("dynamic-content").innerHTML = `<h2>What should we discuss this week?</h2>
<iframe style="width: 95%; max-width:500px; height: 80vh;border:none" src="https://app.sli.do/event/nPhPD54cj1gstCNhbfpa8U"></iframe>`
    }
</script>
