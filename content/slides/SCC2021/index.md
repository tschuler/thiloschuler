---
authors: []
categories: []
date: "2019-02-05T00:00:00Z"
slides:
  highlight_style: dracula
  theme: white
summary: Optimising community service use with ePRO-based screening during routine Radiation Oncology care
tags: []
title: Slides
---

<link rel="stylesheet" href="reveal_custom.css">

## Patients ↔ Services  = ❤️

_Optimising community service use with ePRO-based screening during routine Radiation Oncology care_

--

[Virtual Poster]() by [NSCC]() & [Canteen]() Collaboration  

Sydney Cancer Conference 2021


---

## Background

<style>
.smaller-font{
  font-size:smaller;
  text-align:left;
}

.left-align-text{
  text-align:left;
}

.container{
    display: flex;
    
}
.col{
    flex: 1;
}
.spacer-top{
  margin-top:1em;
}

.spacer-bottom{
  margin-bottom:1em;
}

</style>

<div class="container smaller-font">

<div class="col" data-markdown>
- Community services in cancer care
  - important 👍, but
  - underutilised 😞

</div>

<div class="col r-stack">
<ul>  
<li class="fragment pointy">TODO: Underutil REF (screenshot of article title) </li>  
<li class="fragment pointy">TODO Low RNSH/NSLHD referral rates vs potential referees (?pie charts) </li>  
</ul>  
</div>

</div>

<div class="fragment smaller-font spacer-top">

- Time constraints (not a core service)
- Tradiational referrer campaigns ➡️ unsustainable effect
- Insufficient knowledge ➡️ unconvincing recommendation
 
<div> 

---

## Aim & Methods

<div class="left-align-text">

Systematic and sustainable referral to Quitline and Canteen (Implementation Science):

</div>

<div class="smaller-font"> 

- Screening via routine new patient **ePRO survey**
- **Co-designed** information and referral approach
- Key role: **Patient Care Radiation Therapist (PCRT)**

</div>

---

## Results (1/3)

<div class="container smaller-font spacer-bottom">

<div class="col" data-markdown>
- **6 months ePRO screening**
  - Aug 2020 - Jan 2021
  - 366 patients 
  - 88% response rate
- **Quitline referral**
  - 24 (6.6%) smokers
  - 9 (38%) accepted referral
  - **Over 100% increase** of NSLHD rates in 2018

</div>

<div class="col">
<ul>  
<li class="fragment pointy">TODO: proportion response (?pie chart) </li>  
<li class="fragment pointy">TODO bargraphs smokers vs accepters for ePRO at NSCC vs corresponding 2018 at NSLHD </li>  
</ul>  
</div>

</div>

---

## Results (2/3)

<div class="container smaller-font">

<div class="col" data-markdown>
- **Canteen referral**
  - 85 (23%) of cancer patients had children aged 0-25yrs
  - 18 (21% of eligible) accepted referral
  - Annualised **350% increase** vs 2018.

</div>

<div class="col">

<ul>  
<li class="fragment pointy">TODO bargraphs cancer patients with eligible kids vs referal acceptance at NSCC vs corresponding 2018 numbers </li>  
</ul>  
 
</div> 

</div>

---

## Results (3/3)

<div class="container smaller-font">

<div class="col" data-markdown>
- **Clinical staff survey**
  - Response rate 34 of 77 (44%)
  - 100% ➡️ overall patient benefit
  - 97% ➡️ emotional and/or professoional comfort for clinicians

</div>

<div class="col">

<ul>  
<li class="fragment pointy">TODO: proportion of survey response (?pie chart) </li>  
</ul> 
 
</div> 

</div>


---

## Conclusion & Future

<div class="smaller-font">

Succesful routine care translation with benefits for patients and clinicians:
- Systematic ePRO-based screening
- Co-design strategy
- Plans to apply this model more broadly (other services incl internal pathways)

</div>

---

## Fragments

Make content appear incrementally

```
{{%/* fragment */%}} One {{%/* /fragment */%}}
{{%/* fragment */%}} **Two** {{%/* /fragment */%}}
{{%/* fragment */%}} Three {{%/* /fragment */%}}
```

Press `Space` to play!

{{% fragment %}} One {{% /fragment %}}
{{% fragment %}} **Two** {{% /fragment %}}
{{% fragment %}} Three {{% /fragment %}}

---

A fragment can accept two optional parameters:

- `class`: use a custom style (requires definition in custom CSS)
- `weight`: sets the order in which a fragment appears

---

## Speaker Notes

Add speaker notes to your presentation

```markdown
{{%/* speaker_note */%}}
- Only the speaker can read these notes
- Press `S` key to view
{{%/* /speaker_note */%}}
```

Press the `S` key to view the speaker notes!

{{< speaker_note >}}
- Only the speaker can read these notes
- Press `S` key to view
{{< /speaker_note >}}

---

## Themes

- black: Black background, white text, blue links (default)
- white: White background, black text, blue links
- league: Gray background, white text, blue links
- beige: Beige background, dark text, brown links
- sky: Blue background, thin dark text, blue links

---

- night: Black background, thick white text, orange links
- serif: Cappuccino background, gray text, brown links
- simple: White background, black text, blue links
- solarized: Cream-colored background, dark green text, blue links

---

{{< slide background-image="/media/boards.jpg" >}}

## Custom Slide

Customize the slide style and background

```markdown
{{</* slide background-image="/media/boards.jpg" */>}}
{{</* slide background-color="#0000FF" */>}}
{{</* slide class="my-style" */>}}
```

---

## Custom CSS Example

Let's make headers navy colored.

Create `assets/css/reveal_custom.css` with:

```css
.reveal section h1,
.reveal section h2,
.reveal section h3 {
  color: navy;
}
```

---

# Questions?

[Ask](https://github.com/wowchemy/wowchemy-hugo-modules/discussions)

[Documentation](https://wowchemy.com/docs/managing-content/#create-slides)