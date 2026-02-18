---
marp: true
theme: default_theme
paginate: true
html: true
header: " "
footer: " "
math: katex
---

<!-- _class: title -->
<h1></h1>
<h2></h2>

---

# About me

<div class="body">
<div style="display: flex; gap: 1.5rem;">

<div style="flex: 2;">

<img src="figures/Miguel.jpg" style="flex: 1; width: auto; height: 50%; object-fit: contain;"/>

</div>

<div style="flex: 2; font-size: 1.2em; margin-top: -3rem">

- [Miguel Ureña Pliego](https://miguelurenapliego.github.io/) 

- MEng Civil Engineering at UPM (Spain)

- Visiting Student @ City Science (September 25 to March 2026)

- No drivers licence 
(but licence to build roads)

- I like cats 

</div>

</div>
</div>

---

# Cities are important

<div class="body">
<div style="display: flex; gap: 1.5rem;">

<div style="flex: 2;">
  <img src="figures/urban_growth.png" style="height: 580px;; width: 100%; object-fit: strech;" />
</div>

<div style="flex: 1; font-size: 1.2em;">

- Urban population growth 

- Asia exploded

- Africa? 

</div>

</div>
</div>

---

# Cities are important

<div class="body">
<div style="display: flex; gap: 1.5rem;">
<div style="flex: 2;">
<iframe
  src="html/france.html"
  style="width: 100%; height: 580px; border: w;">
</iframe>
</div>
<div style="flex: 1; font-size: 1.2em;">

- Cities always had power and identity 

- A world of cities beyond nation states...

</div>

</div>
</div>

---

# The city science network

<div class="body">
<div style="display: flex; gap: 1.5rem;">

<div style="flex: 2;">
      <img src="figures/city_science_net.png" style="height: 580px; width: auto; object-fit: strech;" />
</div>

<div style="flex: 1; font-size: 1.2em;">

- MIT Media Lab City Science

- 10 city science labs 

- Close relationship with local administration

- North/south America, Europe and Asia 

</div>

</div>
</div>

---

# What is accessibility?

<div class="body">
<div style="display: flex; gap: 1.5rem;">

<div style="flex: 1.5;">
<iframe
  src="html/cambridge_pt_access.html"
  style="width: 100%; height: 580px; border: w;">
</iframe>
</div>

<div style="flex: 1; font-size: 1.2em; margin-top: -20px">

- Good KPI for coverage 

- Points of Interest (PoIs) + Distance / Time

- Very related to the 15-min-city

- Access if you don't drive?

- Work with [Naroa Coretti](https://www.media.mit.edu/people/naroa/overview/)

</div>

</div>
</div>

---
# But not every PoI is equally attractive...

<div class="body">
<div style="display: flex; align-items: center; gap: 2rem;">

<!-- Left box -->
<div style="
  flex: 2;
  border: 2px solid #555;
  border-radius: 10px;
  padding: 1rem;
  font-size: 1.1em;
">

- Transit stop: 
**Subway vs bus**

- Groceries:
**Large chain vs small shop**

</div>

<!-- Arrow -->
<div style="flex: 0.5; font-size: 10em; text-align: center;">
→
</div>

<!-- Right formula -->
<div style="flex: 2; font-size: 1.5em; text-align: center; margin-top:1.5rem">

$$
\text{Accessibility} = \text{PoI quality}
\times \text{Distance}
$$

</div>

</div>
</div>

---

# Motivation

<div class="body">
<div style="flex: 1; display: flex; justify-content: center; align-items: center; font-size: 1.5em; text-align: center; margin-top: -80px">

  <iframe
    src="html/eldiario/index.html"
    style="width: 100%; height: 580px; border: w;">
  </iframe>

  <!-- <img src="figures/eldiario.jpg" style="height: 600px; width: auto; object-fit: strech;" /> -->
</div>

</div>

---

# Accessibility to public transport

<div style="display: flex; gap: 2rem; height: 100%; align-items: center;">

<!-- Left text -->
<div style="flex: 1.1; font-size: 1.2em; display: flex; flex-direction: column; justify-content: center;">

</div>

<!-- Right formula -->
<div style="flex: 2; display: flex; justify-content: center; align-items: center; font-size: 1.5em; text-align: center;">

$$
\text{Accessibility} = \text{PoI quality}
\times \text{Distance}
$$
</div>

</div>

---

# The city science accessibility contest

<div style="flex: 1; display: flex; justify-content: center; align-items: center; font-size: 1.5em; text-align: center;">

| <img src="figures/san_francisco.jpg" width="300" height="180" style="object-fit: cover;"> | <img src="figures/hamburg.jpeg" width="300" height="180" style="object-fit: cover;"> | <img src="figures/donostia.jpg" width="300" height="180" style="object-fit: cover;"> |
|:---------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|:---------------------------------------------------------------------------------------:|
| <img src="figures/toronto.jpg" width="300" height="180" style="object-fit: cover;">      | <img src="figures/boston.jpg" width="300" height="180" style="object-fit: cover;">     | <img src="figures/guadalajara.jpg" width="300" height="180" style="object-fit: cover;"> |
</div>

---

# Accessibility to public transport

<div style="display: flex; gap: 2rem; height: 100%; align-items: center;">

<!-- Left text -->
<div style="flex: 1.1; font-size: 1.2em; display: flex; flex-direction: column; justify-content: center;">

- PoIs - Stops

</div>

<!-- Right formula -->
<div style="flex: 2; display: flex; justify-content: center; align-items: center; font-size: 1.5em; text-align: center;">

$$
\text{Accessibility} = 
  \overbrace{
      \text{PoI quality}
  }^{\text{Public Transport quality}}
\times \text{Distance}
$$
</div>

</div>


---

# Accessibility to public transport

<div style="display: flex; gap: 2rem; height: 100%; align-items: center;">

<!-- Left text -->
<div style="flex: 1.1; font-size: 1.2em; display: flex; flex-direction: column; justify-content: center;">

- PoIs - Stops

- Stop quality

</div>

<!-- Right formula -->
<div style="flex: 2; display: flex; justify-content: center; align-items: center; font-size: 1.5em; text-align: center;">

$$
\text{Accessibility} = 
  \overbrace{
      \text{headway} \cdot 
      \text{speed}\cdot 
      \text{mode}
  }^{\text{Public Transport quality}}
\times \text{Distance}
$$
</div>

</div>

---

# Accessibility to public transport

<div style="display: flex; gap: 2rem; height: 100%; align-items: center;">

<!-- Left text -->
<div style="flex: 1.1; font-size: 1.2em; display: flex; flex-direction: column; justify-content: center;">

- PoIs - Stops

- Stop quality

- Normalization $[0,1]$
</div>

<!-- Right formula -->
<div style="flex: 2; display: flex; justify-content: center; align-items: center; font-size: 1.5em; text-align: center;">

$$
\underbrace{\text{Accessibility}}_{[0, 1]} = 
    \overbrace{
        \underbrace{\text{headway}}_{[0, 1]} \cdot 
        \underbrace{\text{speed}}_{[0, 1]} \cdot 
        \underbrace{\text{mode}}_{[0, 1]}
    }^{\text{public transport quality}}
\times \underbrace{\text{distance}}_{[0, 1]}
$$
</div>

</div>

---

# Quality functions

<div style="display: flex; gap: 2rem; align-items: center; height: 430px">

  <!-- Left column: formulas -->
  <div style="flex: 1; font-size: 1.3em; display: flex; flex-direction: column; justify-content: center; gap: 1rem;">
    
  $$\text{Distance} \to [0,1]$$
    
  Exponential decay function - Elasticity:
    
  $$e = \frac{\%\text{ change in Demand } (\approx \text{ Quality})}{\%\text{ change in Distance}}$$

  </div>

  <!-- Right column: iframe graph -->
  <div style="flex: 2; overflow: hidden; height: 170%;  text-align: center; margin-top: 50px">
    <iframe 
      src="html/elasticity_graph.html"
      style="
        width: 100%;
        height: 100%;
        border: w;
      ">
    </iframe>
  </div>

</div>

---

# Accessibility to public transport

<div style="display: flex; gap: 2rem; height: 100%; align-items: center;">

  <!-- Left column: bullets with arrow -->
  <div style="flex: 1.1; font-size: 1.2em; display: flex; flex-direction: column; justify-content: center; gap: 0.5rem; position: relative;">

  <!-- First two bullets -->
  <div>

  - PoIs - Stops<br>
  - Stop quality

  <!-- Vertical arrow -->
  <div style="position: relative; height: 2em; display: flex; justify-content: center; align-items: center;">
    <div style="border-left: 2px solid black; height: 100%;"></div>
    <div style="position: absolute; top: 50%; left: 50%; transform: translate(-100%, -50%); font-size: 5em;">↓</div>
  </div>
  </div>

  <!-- Last bullet -->
  <div>

  - Timetables

  </div>

  </div>

  <!-- Right column: accessibility formula -->
  <div style="flex: 2; display: flex; justify-content: center; align-items: center; font-size: 1.5em; text-align: center;">

  $$
  \text{Accessibility} =
  \overbrace{
    \color{red}{\fbox{$\text{headway} \;\cdot\; \text{speed} \;\cdot\; \text{mode}$}}
  }^{\text{Public Transport quality}}
  \times \text{Distance}
  $$

  </div>

</div>


---

# Public transport timetables: GTFS

<div class="body" style="display: flex; flex-direction: row; gap: 2rem; height: 450px; align-items: center; margin-top: -50px; margin-bottom: -10px">

  <!-- LEft column -->
  <div style="flex: 1; display: flex; flex-direction: column;">

  ## Global standard

  - [**Mobility Database API**](https://mobilitydatabase.org) 

  - [**Transitland API**](https://www.transit.land)

  - Local agencies (mandatory in the EU)

  </div>

  <!-- Right column -->
  <div style="flex: 1; display: flex; flex-direction: column;">
    <!-- Image wrapper: flex-grow to take most of the space -->
    <div style="flex: 1.3; display: flex; justify-content: center; align-items: center; width: 100%; margin-top: 30px; margin-bottom: 30px">
      <img src="figures/google_maps.jpg" style="height: 100%; width: auto; object-fit: strech;" />
    </div>
    <!-- Text at bottom -->
    <div style="margin-top: auto; text-align: center;margin-bottom: 0px; font-size: 1.1em;">We all use it</div>
  </div>

</div>

---

# Not that easy...

<div class="body" style="display: flex; flex-direction: row; gap: 2rem; height: 450px; align-items: center; margin-top: -50px; margin-bottom: -10px">

  <!-- LEft column -->
  <div style="flex: 1; display: flex; flex-direction: column; font-size: 1.2em; gap: 1rem;">

  <!-- First step -->
  <div style="display: flex; flex-direction: column; align-items: flex-start;">
  <div style="display: flex; align-items: center;font-size: 2em">
    ✅ GTFS → stop location
  </div>

  <br>
  <br>
  <br>

  </div>

  <!-- Second step -->
  <div style="display: flex; flex-direction: column; align-items: flex-start;">

  <div style="display: flex; align-items: center;font-size: 2em">
    ☹️ GTFS → headway, speed, mode
  </div>


  
  </div>

  </div>

  <!-- Right column -->
  <div style="flex: 1; display: flex; flex-direction: column;">
    <!-- Image wrapper: flex-grow to take most of the space -->
    <div style="flex: 1.3; display: flex; justify-content: center; align-items: center; width: 100%; margin-top: 30px; margin-bottom: 30px">
      <img src="figures/gtfs_file_structure.jpg" style="height: 100%; width: auto; object-fit: strech;" />
    </div>
    <!-- Text at bottom -->
    <div style="margin-top: auto; text-align: center;margin-bottom: 0px; font-size: 1.1em;">GTFS file structure</div>
  </div>

</div>


---

# Stop quality

<div style="display: flex; justify-content: center; align-items: center; height: 80vh;">

$$
\text{Accessibility} =
\overbrace{
  \color{red}{\fbox{$\text{headway}$}} \color{white}{\;\cdot\; \text{speed} \;\cdot\; \text{mode}
}}^{\text{Public Transport quality}}
\times \text{Distance}
$$

</div>


---

# Headway

<!-- Row with two images side by side -->
<div style="display: flex; flex-direction: row; gap: 2rem; align-items: stretch; height: 500px; margin-bottom: -3rem">

  <!-- Left image -->
  <div style="flex: 1; display: flex; justify-content: center; align-items: center;margin-top: -3rem; margin-bottom: -3rem;">
    <img src="figures/example_PT_net.jpg" style="height: 100%; object-fit: contain;">
  </div>

  <!-- Right image -->
  <div style="flex: 1; display: flex; justify-content: center; align-items: center;margin-top: -3rem; margin-bottom: -3rem;">

  Contribution of multiple routes?

  </div>

</div>

---

# Headway

<!-- Row with two images side by side -->
<div style="display: flex; flex-direction: row; gap: 2rem; align-items: stretch; height: 500px;margin-bottom:-3rem">

  <!-- Left image -->
  <div style="flex: 1; display: flex; justify-content: center; align-items: center;margin-top: -3rem; margin-bottom: -3rem;">
    <img src="figures/example_PT_net_2.jpg" style="height: 100%; object-fit: contain;">
  </div>

  <!-- Right image -->
  <div style="flex: 1; display: flex; justify-content: center; align-items: center;margin-top: -3rem; margin-bottom: -3rem;">

  Harmonic mean
  $\text{HM} = 1/\left[\text{mean}\left(\frac{1}{\text{headway}_i}\right)\right]$

  </div>

</div>

---

# Headway: Trips and routes

<!-- Row with two images side by side -->
<div style="display: flex; flex-direction: row; gap: 2rem; align-items: stretch; height: 400px;">

  <!-- Left image -->
  <div style="flex: 1; display: flex; justify-content: center; align-items: center;margin-top: -3rem; margin-bottom: -3rem;">
    <img src="figures/branches.jpg" style="height: 100%; object-fit: contain;">
  </div>

  <!-- Right image -->
  <div style="flex: 1; display: flex; justify-content: center; align-items: center;margin-top: -3rem; margin-bottom: -3rem;">
    <img src="figures/routes.jpg" style="height: 100%; object-fit: contain;">
  </div>

</div>

<!-- Subtitle below both images -->
<div style="text-align: center; font-size: 2em; margin-top: 0rem; margin-bottom: 0rem;">
  The problem with the 'route' concept. Better use trips.
</div>


---

# Headway

<div style="display: flex; width: 100%; align-items: flex-start;">

  <!-- Left column: Text with top gap -->
  <div style="flex: 1; font-size: 1.5em; margin-top: 0rem; padding-right: 2rem;">
    <p><strong>Elasticity:</strong></p>
    <p>Theoretical value: <br>
    0.5 (Mohring's Law)</p>
    <p>Empirical:<br>
    &lt; 30 min: e = 0.3 to 0.5<br>
    &gt; 60 min: e = 0.6 to 1</p>
  </div>

  <!-- Right column: Image aligned to top -->
  <div style="flex: 1.5; display: flex; flex-direction: column; align-items: center; margin-top: 0rem;">
  <iframe
    src="html/cambridge_pt_headway.html"
    style="width: 100%; height: 500px; border: w;margin-top: -6rem;">
  </iframe>
  </div>

</div>


---

# Stop quality

<div style="display: flex; justify-content: center; align-items: center; height: 80vh;">

$$
\text{Accessibility} =
\overbrace{
  \text{headway} \;\cdot\; \color{red}{\fbox{\text{speed}}} \color{white}{\;\cdot\; \text{mode}
}}^{\text{Public Transport quality}}
\times \text{Distance}
$$

</div>

---

# Speed

<div class="body">

<div style="display: flex; align-items: flex-start; gap: 2rem;">

<!-- Left side: bullet points -->
<div style="flex: 1; font-size: 1.1em;">

- Per trip and stop  

- Measured ±15 minutes around each stop

- Elasticity: $e = 0.1 - 0.4$ (smaller than headway)

</div>

<!-- Right side: map -->
<div style="flex: 1.7; text-align: center;">
<img src="figures/speed.jpg" style="height: 100%; object-fit: contain;">
</div>

</div>
</div>


---

# Speed

<div class="body">

<div style="display: flex; align-items: flex-start; gap: 2rem;">

<!-- Left side: bullet points -->
<div style="flex: 1; font-size: 1.1em;">

- Per trip and stop  

- Measured ±15 minutes around each stop

- Elasticity: $e = 0.1 - 0.4$ (smaller than headway)
</div>

<!-- Right side: map -->
<div style="flex: 1.7; text-align: center;">
<iframe
  src="html/cambridge_pt_speed.html"
  style="width: 100%; height: 500px; border: w;margin-top: -6rem;">
</iframe>
</div>

</div>
</div>

---

# Stop quality

<div style="display: flex; justify-content: center; align-items: center; height: 80vh;">

$$
\text{Accessibility} =
\overbrace{
  \text{headway} \;\cdot\; \text{speed} \;\cdot\; \color{red}{\fbox{\text{mode}}}
}^{\text{Public Transport quality}}
\times \text{Distance}
$$

</div>

---

# Mode

<div class="body">
<div style="display: flex; align-items: flex-start; gap: 2rem;">

<!-- Left side -->
<div style="flex: 1; font-size: 1.1em;">

### Values
- **Bus**: $0.5 - 0.9$
- **LRT/BRT (tram)**: $0.75 - 0.95$
- **Subway/Train (rail)**: $1$

User comfort and capacity   

`route_type` column in GTFS

No specific ID for BRT services
</div>

<!-- Right side -->
<div style="flex: 1.4; font-size: 1.1em;">
<iframe
  src="html/cambridge_pt_mode.html"
  style="width: 100%; height: 500px; border: w;margin-top: -6rem;">
</iframe>
</div>
</div>

---

# Accessibility

<div style="display: flex; justify-content: center; align-items: center; height: 80vh;">

$$
\text{Accessibility} =
\overbrace{
  \text{headway} \;\cdot\; \text{speed} \;\cdot\; \text{mode}
}^{\text{Public Transport quality}}
\times \color{red}{\fbox{\text{Distance}}}
$$

</div>

---

# Distance/Time: Isochrones

<div class="body">

<div style="display: flex; align-items: flex-start; gap: 2rem;">

<!-- Left side: bullet points -->
<div style="flex: 1; font-size: 1.1em; margin-top: -1rem;">

- The area reachable in **X minutes** 
with a specific transport **mode**
(public transport, walk, bike, car, etc.)

- Transport system graph 

- For accessibility to public transport: 
walk isochrones

- Elasticity: $e = 0.1 - 0.4$ 
(smaller than headway)
</div>

<!-- Right side: figure -->
<div style="flex: 1; text-align: center; margin-top: -1rem">

![Isochrone](figures/isochrones.jpg)

</div>

</div>
</div>

---

# A bit of graph theory

<div class="body">

<div style="display: flex; align-items: flex-start; gap: 2rem;">

<!-- Left side: bullet points -->
<div style="flex: 1; font-size: 1.1em;">

- Transport system graph 
(source: OpenStreetMap streets)  

- Geo-multi-source **Dijkstra**
adds exact nodes at breakpoints

- Discrete distances 

- Discrete stop qualities 

</div>

<!-- Right side: figure -->
<div style="flex: 1; text-align: center; margin-top: -1rem">

![Isochrone](figures/graph.jpg)

</div>

</div>
</div>

---
# Discretization




<div class="body">

  1. Choose discrete accessibility grades

  <div style="display: flex; gap: 0.3rem; margin-bottom: 1rem;">

  <div style="flex:1; background-color:#ff6666; color:white; text-align:center; padding:0.5rem;">0</div>
  <div style="flex:1; background-color:#ff9999; color:black; text-align:center; padding:0.5rem;">0.1</div>
  <div style="flex:1; background-color:#ffcc66; color:black; text-align:center; padding:0.5rem;">0.2</div>
  <div style="flex:1; background-color:#ffff66; color:black; text-align:center; padding:0.5rem;">0.3</div>
  <div style="flex:1; background-color:#ccff66; color:black; text-align:center; padding:0.5rem;">0.4</div>
  <div style="flex:1; background-color:#99ff66; color:black; text-align:center; padding:0.5rem;">0.5</div>
  <div style="flex:1; background-color:#66ff66; color:black; text-align:center; padding:0.5rem;">0.6</div>
  <div style="flex:1; background-color:#33ff66; color:black; text-align:center; padding:0.5rem;">0.7</div>
  <div style="flex:1; background-color:#00cc66; color:white; text-align:center; padding:0.5rem;">0.8</div>

  <!-- added -->
  <div style="flex:1; background-color:#00aa55; color:white; text-align:center; padding:0.5rem;">0.9</div>

  <div style="flex:1; background-color:#009933; color:white; text-align:center; padding:0.5rem;">1</div>

</div>


2. Stop quality and distance are discretized automatically 
</div>

---
# An example result

<div class="body">
<iframe
  src="html/cambridge_pt_access.html"
  style="width: 100%; height: 700px; border: w; margin-top: -8rem">
</iframe>
</div>

---
# Population/Census

<div class="body">
<div style="display: flex; align-items: flex-start; gap: 2rem;">

<!-- Left side: map -->
<div style="flex: 2.5; text-align: center;">

<iframe
  src="html/cambridge_pt_population.html"
  style="width: 100%; height: 400px; border: w;">
</iframe>
</div>

<!-- Right side: bullet points -->
<div style="flex: 1; font-size: 1.1em;">

- Global source: [WorldPop](https://www.worldpop.org)  

- Census data: Individual countries
</div>

</div>
</div>

---
# This idea is flexible!

<div class="body">
<div style="display: flex; align-items: flex-start; gap: 2rem;">

<!-- Left side: bullet points -->
<div style="flex: 1; font-size: 1.1em; margin-top: 10rem;">

- Park quality by its **area**

</div>

<!-- Right side: map -->
<div style="flex: 4; text-align: center; margin-top: 0rem;">
<iframe
  src="html/cambridge_park_access.html"
  style="width: 100%; height: 430px; border: w;">
</iframe>
</div>

</div>
</div>


---

# Introducing perception

<div class="body">

<div style="display: flex; align-items: flex-start; gap: 2rem;">

<!-- Left side: bullet points -->
<div style="flex: 1; font-size: 1.1em;">

- Work with [Leticia Izquierdo](https://www.media.mit.edu/people/leticiai/projects/) 

- Pairwise comparisons

- Image vision model

- Small sample size

- Different profiles

- Perceived distances

</div>

<!-- Right side: map -->
<div style="flex: 1.7; text-align: center;">
<img src="figures/place_pulse.jpg" style="height: 400px; object-fit: contain;">
</div>

</div>
</div>

---

# Introducing perception

<div class="body">

<div style="display: flex; align-items: flex-start; gap: 2rem;">

<!-- Left side: bullet points -->
<div style="flex: 1; font-size: 1.1em;">

- Work with [Leticia Izquierdo](https://www.media.mit.edu/people/leticiai/projects/) 

- Pairwise comparisons

- Image vision model

- Small sample size

- Different profiles

- Perceived distances

</div>

<!-- Right side: map -->
<div style="flex: 1.7; text-align: center;">
<img src="figures/streetscore.jpg" style="height: 400px; object-fit: contain;">
</div>

</div>
</div>


---

# Connecting with DUSP

<div class="body">

<div style="display: flex; align-items: flex-start; gap: 2rem;">

<!-- Left side: bullet points -->
<div style="flex: 1; font-size: 1.1em;">

- Coffee and transit

  - Speaker next Wendesday
</div>

<!-- Right side: map -->
<div style="flex: 1.7; text-align: center;">
  <iframe
    src="html/coffee_and_transit/index.html"
    style="width: 100%; height: 450px; border: w;">
  </iframe>

<!-- <img src="figures/coffee_and_transit.jpg" style="height: 100%; object-fit: contain;"> -->
</div>
</div>
</div>


---

# Connecting with DUSP

<div class="body">

<div style="display: flex; align-items: flex-start; gap: 2rem;">

<!-- Left side: bullet points -->
<div style="flex: 1; font-size: 1.1em;">


- City Science San Francisco: 

  - Affordable housing 

  - Erik Huntley: Who owns Massachusetts?

</div>

<!-- Right side: map -->
<div style="flex: 1.7; text-align: center;">
<iframe
  src="https://who-owns-mass.org/"
  style="width: 100%; height: 450px; border: w;">
</iframe>
</div>
</div>
</div>

---
# Results

---

<div class="body">
<iframe
  src="html/boston.html"
  style="width: 100%; height: 850px; border: w; margin-top: -8rem">
</iframe>
</div>

---

<div class="body">
<iframe
  src="html/san_francisco.html"
  style="width: 100%; height: 850px; border: w; margin-top: -8rem">
</iframe>
</div>


---

<div class="body">
<iframe
  src="html/toronto_res_7.html"
  style="width: 100%; height: 850px; border: w; margin-top: -8rem">
</iframe>
</div>

---

<div class="body">
<iframe
  src="html/guadalajara.html"
  style="width: 100%; height: 850px; border: w; margin-top: -8rem">
</iframe>
</div>

---

<div class="body">
<iframe
  src="html/gipuzkoa.html"
  style="width: 100%; height: 850px; border: w; margin-top: -8rem">
</iframe>
</div>

---

<div class="body">
<iframe
  src="html/hamburg_res_7.html"
  style="width: 100%; height: 850px; border: w; margin-top: -8rem">
</iframe>
</div>

---

<div class="body">
<iframe
  src="html/new_city_with_stops.html"
  style="width: 100%; height: 850px; border: w; margin-top: -8rem">
</iframe>
</div>

---

<div class="body">
<iframe
  src="html/new_city.html"
  style="width: 100%; height: 850px; border: w; margin-top: -8rem">
</iframe>
</div>


---

# Equity 

<div style="display: flex; width: 100%; align-items: flex-start;">

  <!-- Left column: Text with top gap -->
  <div style="flex: 1; font-size: 1.5em; margin-top: 0rem; padding-right: 2rem;">

  - Population density

  - Home ownership 

  - Car ownership

  - Race

  - Income

  </div>

  <!-- Right column: Image aligned to top -->
  <div style="flex: 1; display: flex; flex-direction: column; align-items: center; margin-top: -7.5rem;">
    <img src="figures/boston_equity.png" style="width: 100%; max-height: 550px; object-fit: contain;">
  </div>

</div>

---

# Equity 

<div style="display: flex; width: 100%; align-items: flex-start;">

  <!-- Left column: Text with top gap -->
  <div style="flex: 1; font-size: 1.5em; margin-top: 0rem; padding-right: 2rem;">

  - Population density

  - Home ownership 

  - Car ownership

  - Race

  - Income

  </div>

  <!-- Right column: Image aligned to top -->
  <div style="flex: 1; display: flex; flex-direction: column; align-items: center; margin-top: -7.5rem;">
    <img src="figures/sf_equity.png" style="width: 100%; max-height: 550px; object-fit: contain;">
  </div>

</div>

---

# Equity 

<div style="display: flex; width: 100%; align-items: flex-start;">

  <!-- Left column: Text with top gap -->
  <div style="flex: 1; font-size: 1.5em; margin-top: 0rem; padding-right: 2rem;">

  - Population density

  - Home ownership 

  - Car ownership

  - Race

  - Income

  </div>

  <!-- Right column: Image aligned to top -->
  <div style="flex: 1; display: flex; flex-direction: column; align-items: center; margin-top: -7.5rem;">
    <img src="figures/new_city_equity.png" style="width: 100%; max-height: 550px; object-fit: contain;">
  </div>

</div>

--- 

# Ranking: Bottom

<div style="display: flex; width: 100%; align-items: flex-start;">
  <div style="flex: 1; font-size: 1.5em; margin-top: 0rem; padding-right: 2rem;">

  <img src="figures/results_city_core_worst.png" style="width: 100%; max-height: 400px; object-fit: contain;">

  </div>
  <div style="flex: 1; font-size: 1.5em; margin-top: 0rem; padding-right: 2rem;">

  <img src="figures/results_urban_areas_worst.png" style="width: 100%; max-height: 400px; object-fit: contain;">

  </div>
</div>

--- 

# Ranking: Top

<div style="display: flex; width: 100%; align-items: flex-start;">
  <div style="flex: 1; font-size: 1.5em; margin-top: 0rem; padding-right: 2rem;">

  <img src="figures/results_city_core.png" style="width: 100%; max-height: 400px; object-fit: contain;">

  </div>
  <div style="flex: 1; font-size: 1.5em; margin-top: 0rem; padding-right: 2rem;">

  <img src="figures/results_urban_areas.png" style="width: 100%; max-height: 400px; object-fit: contain;">

  </div>
</div>

--- 

# Python packages

<div style="display: flex; gap: 5rem; align-items: flex-start;">

<!-- Left column -->
<div style="flex: 1; font-size: 1.1em;">

<h2>
<a href="https://github.com/CityScope/pyGTFSHandler" style="text-decoration: none;">
  PyGTFSHandler
</a>
</h2>

<ul style="margin-top: 0.5rem;">
  <li>
    <a href="https://github.com/CityScope/pyGTFSHandler/blob/main/examples/example.ipynb"
       style="text-decoration: none;">
      Tutorial
    </a>
    <span style="display: block; font-size: 0.75em; line-height: 1.15; margin: 0;">
      Download GTFS and compute speed and headway
    </span>
  </li>
</ul>

</div>

<!-- Right column -->
<div style="flex: 1; font-size: 1.05em;">

<h2>
<a href="https://github.com/CityScope/UrbanAccessAnalyzer" style="text-decoration: none;">
  UrbanAccessAnalyzer
</a>
</h2>

<ul style="margin-top: 0.5rem;">
  <li>
    <a href="https://github.com/CityScope/UrbanAccessAnalyzer/blob/main/examples/rural_schools.ipynb"
       style="text-decoration: none;">
      Schools
    </a>
    <span style="display: block; font-size: 0.75em; line-height: 1.15; margin: 0;">
      Basic example and download of PoIs from OpenStreetMap
    </span>
  </li>
  <br>
  <li>
    <a href="https://github.com/CityScope/UrbanAccessAnalyzer/blob/main/examples/green_spaces.ipynb"
       style="text-decoration: none;">
      Parks
    </a>
    <span style="display: block; font-size: 0.75em; line-height: 1.15; margin: 0;">
      Simple tutorial introducing PoI quality
    </span>
  </li>
  <br>
  <li>
    <a href="https://github.com/CityScope/UrbanAccessAnalyzer/blob/main/examples/worldwide_public_transport.ipynb"
       style="text-decoration: none;">
      Public Transport
    </a>
    <span style="display: block; font-size: 0.75em; line-height: 1.15; margin: 0;">
      Complete example of our accessibility to public transport indicator including isochrone computation and GTFS processing
    </span>
  </li>
</ul>

</div>

</div>

---

# A good relationship with data?

<div class="body">

<div style="display: flex; align-items: flex-start; gap: 2rem;">

<!-- Left side: bullet points -->
<div style="flex: 1; font-size: 1.1em;">

- What data gets collected? 

- Decision informed data

</div>

<!-- Right side: map -->
<div style="flex: 2; text-align: center;">
<img src="figures/madrid_vs_barcelona.jpg" style="height: 100%; object-fit: contain;">
</div>

</div>
</div>

---

# A good relationship with data?

<div class="body">

<div style="display: flex; align-items: flex-start; gap: 2rem;">

<!-- Left side: bullet points -->
<div style="flex: 1; font-size: 1.1em;">

- What data gets collected? 

- Decision informed data

- What data should exist?

</div>

<!-- Right side: map -->
<div style="flex: 2; text-align: center;">
  <iframe
    src="html/bbc/index.html"
    style="width: 100%; height: 450px; border: w;">
  </iframe>
<!-- <img src="figures/egipt.jpg" style="height: 100%; object-fit: contain;"> -->
</div>

</div>
</div>

---

# A good relationship with data?

<div class="body">

<div style="display: flex; align-items: flex-start; gap: 2rem;">

<!-- Left side: bullet points -->
<div style="flex: 1; font-size: 1.1em;">

- Data governance and monopolization

  - Google [dominates](https://www.justinobeirne.com/how-many-people-use-google-maps-compared-to-apple-maps)

  - [OpenStreetMap](https://www.openstreetmap.org/about)


</div>

<!-- Right side: map -->
<div style="flex: 1.7; text-align: center;">
<img src="figures/google_maps_users.jpg" style="height: 100%; object-fit: contain;">
</div>

</div>
</div>

---

# A good relationship with data?

<div class="body">

<div style="display: flex; align-items: flex-start; gap: 2rem;">

<!-- Left side: bullet points -->
<div style="flex: 1; font-size: 1.1em;">

- Who is looking? 

- Data science is not objetive!


</div>

<!-- Right side: map -->
<div style="flex: 1.7; text-align: center;">
<img src="figures/data.jpg" style="height: 400px; object-fit: contain;">
</div>

</div>
</div>

---

# Look up!

<div class="body">

<div style="display: flex; align-items: flex-start; gap: 2rem;">

<!-- Left side: bullet points -->
<div style="flex: 1; font-size: 1.1em;">

- Poverty does not just exist

- A system makes it happen

- Who profits? 

</div>

<!-- Right side: map -->
<div style="flex: 2; text-align: center;">
<img src="figures/wealth_inequality_EU_US.jpg" style="height: 100%; object-fit: contain;">
</div>

</div>
</div>

---

# How does the world change?

<div class="body" style="height: 100%; display: flex; justify-content: center; align-items: center; margin-top:20px">

  <!-- Image centered -->
  <div>
    <img src="figures/javito.jpg" style="height: 600px; object-fit: contain;">
  </div>

</div>

---

# How does the world change?

<div class="body" style="height: 100%; display: flex; justify-content: center; align-items: center; margin-top:20px">

  <!-- Image centered -->
  <div>
    <img src="figures/stonewall.jpg" style="height: 600px; object-fit: contain;">
  </div>

</div>

---
<div class="body" style="height: 100%; display: flex; justify-content: center; align-items: center; margin-top:90px">

  <!-- Image centered -->
  <div>
    <img src="figures/sdg_goals.jpg" style="height: 600px; object-fit: contain;">
  </div>

</div>

--- 

<div class="body" style="height: 100%; display: flex; justify-content: center; align-items: center; margin-top:20px">

# Data as a pressure mechanism?
</div>

---
<!-- _class: last -->
# Questions?
## Thank you!

<div style="flex: 1; font-size: 1.05em; margin-top:-5rem">

Miguel Ureña Pliego
Contact: miguelup@mit.edu
miguel.urena.pliego@gmail.com

Github: [MiguelUrenaPliego](https://github.com/MiguelUrenaPliego)
LinkedIn: [miguel-urena-pliego](www.linkedin.com/in/miguel-urena-pliego)

</div>