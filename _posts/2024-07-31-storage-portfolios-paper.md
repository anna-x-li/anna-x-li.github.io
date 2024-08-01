---
layout: post
title: Recently published storage portfolios paper
date: 2024-07-31
description: 
tags: Updates Research Publications
thumbnail: assets/img/publication_preview/li_influence_2024.png
images:
  slider: true
toc:
  beginning: true
---

<style>
  /* Add padding after headings */
  h3 {
    margin-bottom: 20px; /* Adjust the value as needed */
  }

  h4 {
    margin-bottom: 15px; /* Adjust the value as needed */
  }

  .swiper-caption {
    text-align: center;
    margin-top: 10px;
    font-size: 14px;
    color: #333;
    margin-bottom: 40px; /* Adjust this value to ensure it doesn’t overlap with pagination dots */
  }

  /* Adjust the position of pagination dots */
  .swiper-pagination-bullets {
    bottom: 20px; /* Adjust this value to move the pagination dots down */
  }
</style>

### Links to Paper and Research Brief

I’m thrilled to share my first first-author paper, titled ["The Influence of Regional Geophysical Resource Variability on the Value of Single- and Multistorage Technology Portfolios"](https://pubs.acs.org/doi/10.1021/acs.est.3c10188), published in ACS Environmental Science & Technology!

In this paper, we explore **the value of single- and multi-storage portfolios** in electricity systems reliant on solar and wind energy.

For a concise 2-page summary, see our [Research Brief](https://img1.wsimg.com/blobby/go/650b2a67-8ba1-496b-beab-042f6700f73b/StoragePortfolios_ResearchBrief_16July2024.pdf).

---

### Key Findings

<ol style="padding-left: 2; margin-top: 20px;">
    <li style="margin-bottom: 10px;"><strong>Long-duration storage may also fulfill short-term power needs</strong>, as long-duration storage already requires substantial discharge power-capacity to meet long-term power needs, such as large demand spikes during weather events.</li>
    <li style="margin-bottom: 10px;">Among all storage portfolios we analyzed for systems with abundant solar and wind energy, systems deploying <strong>underground hydrogen storage</strong> or <strong>metal-air batteries</strong> had the lowest total system costs, due to being the most cost-effective long-duration energy storage technology. This is because they had the lowest energy-capacity costs out of all storage technologies modeled (~2 $/kWh energy-capacity cost for hydrogen, and 20 $/kWh total cost and 100-h duration for metal-air batteries).</li>
</ol>

---

### Methodology

#### Modeling of Different Storage Technologies
<div class="row mt-4">
    <div class="col-sm-7">

        We modeled various low-carbon energy storage technologies currently available on the market:

        <ul style="list-style-type: none; padding-left: 2; margin-top: 20px;">
            <li style="margin-bottom: 10px;"> - 🔋 Lithium-ion batteries</li>
            <li style="margin-bottom: 10px;"> - 🧪 Redox flow batteries</li>
            <li style="margin-bottom: 10px;"> - 💦 Pumped hydro storage</li>
            <li style="margin-bottom: 10px;"> - 🏗️ Gravity energy storage</li>
            <li style="margin-bottom: 10px;"> - 🔥 Thermal energy storage</li>
            <li style="margin-bottom: 10px;"> - 💨 Compressed air energy storage</li>
            <li style="margin-bottom: 10px;"> - 🤘 Metal-air batteries</li>
            <li style="margin-bottom: 10px;"> - ⚗️ Underground hydrogen energy storage</li>
        </ul>

        In our model, we select base-case costs and round-trip efficiencies from the middle range of estimates from other techno-economic analyses.

    </div>
    <div class="col-sm-5">
        {% include figure.liquid loading="eager" path="assets/img/storage_portfolios_paper_post/Figure 1.jpeg" class="img-fluid rounded z-depth-1" zoomable=true%}

        <div class="caption">
            Ranges of total installed energy- and power-capacity costs of different low-carbon energy storage technologies on the market
        </div>
    </div>
</div>

#### Modeling of Different Geographic Regions

<div class="row mt-4">
    <div class="col-sm-7">
        <swiper-container keyboard="true" navigation="true" pagination="true" pagination-clickable="true" pagination-dynamic-bullets="true" rewind="true">
        <swiper-slide>
            {% include figure.liquid loading="eager" path="assets/img/storage_portfolios_paper_post/Figure 3 CONUS.jpeg" class="img-fluid rounded z-depth-1" zoomable=true%}
            <div class="swiper-caption">System costs for combinations of storage technologies in CONUS</div>
        </swiper-slide>
        <swiper-slide>
            {% include figure.liquid loading="eager" path="assets/img/storage_portfolios_paper_post/Figure 3 CAISO.jpeg" class="img-fluid rounded z-depth-1" zoomable=true%}
            <div class="swiper-caption">System costs for combinations of storage technologies in CAISO </div>
        </swiper-slide>
        <swiper-slide>
            {% include figure.liquid loading="eager" path="assets/img/storage_portfolios_paper_post/Figure 3 ERCOT.jpeg" class="img-fluid rounded z-depth-1" zoomable=true%}
            <div class="swiper-caption">System costs for combinations of storage technologies in ERCOT</div>
        </swiper-slide>
        <swiper-slide>
            {% include figure.liquid loading="eager" path="assets/img/storage_portfolios_paper_post/Figure 3 ISO-NE.jpeg" class="img-fluid rounded z-depth-1" zoomable=true%}
            <div class="swiper-caption">System costs for combinations of storage technologies in ISO-NE</div>
        </swiper-slide>
        <swiper-slide>
            {% include figure.liquid loading="eager" path="assets/img/storage_portfolios_paper_post/Figure 3 MISO.jpeg" class="img-fluid rounded z-depth-1" zoomable=true%}
            <div class="swiper-caption">System costs for combinations of storage technologies in MISO</div>
        </swiper-slide>
        </swiper-container>
    </div>
    <div class="col-sm-5">
        <p>We then simulated the deployment of different combinations of storage technologies in solar- and wind-based electricity systems, representing several geographically diverse regions:</p>

        <ol start="1" style="padding-left: 2; margin-top: 20px;">
            <li style="margin-bottom: 10px;"> The Continental U.S. (<strong>CONUS</strong>)</li>
            <li style="margin-bottom: 10px;"> California Independent System Operator (<strong>CAISO</strong>)</li>
            <li style="margin-bottom: 10px;"> Electric Reliability Council of Texas (<strong>ERCOT</strong>)</li>
            <li style="margin-bottom: 10px;"> ISO New England (<strong>ISO-NE</strong>)</li>
            <li style="margin-bottom: 10px;"> Midcontinent Independent System Operator (<strong>MISO</strong>)</li>
        </ol>
    </div>
</div>

---

### Acknowledgements

I couldn’t have done this without my collaborators from the [Climate Energy Lab](https://climateenergylab.org/) at the Carnegie Institution for Science, especially my co-first authors ([Edgar Virgüez](https://sites.duke.edu/edgarvirguez/) and [Jackie Dowling](https://jadowling.com/)). I started this project during my junior year at Caltech with Jackie, who was my graduate student mentor at the time. I’ve learned and grown so much as a researcher throughout the process, and I want to give an extra special thanks to Jackie for giving me the hands-on and supportive mentorship that I needed to get started in the macro-scale energy modeling world. I also want to thank Edgar Virgüez, Ph.D. for putting in countless hours to push this paper through submission and reviews to the finish line.

I also want to thank my other co-authors, [Alicia Wongel](https://www.linkedin.com/in/alicia-wongel/), [Dominic Covelli](https://www.linkedin.com/in/dominic-covelli-1b7b03168/), [Tyler Ruggles](https://thruggles.com/), and [Natasha Reich](https://www.linkedin.com/in/natasha-reich-521b01200/), for their huge contributions towards this study, especially during the review process. Additionally, I owe a special thanks to my advisors [Ken Caldeira](https://www.breakthroughenergy.org/our-team/ken-caldeira/) from Carnegie Science and Nate Lewis from Caltech for providing the environment that greatly contributed to my development as a researcher.