
#  Formula 1 Analytics Dashboard (Power BI)

##  Overview

This project is an interactive **Power BI dashboard** built to analyze historical Formula 1 data across drivers, constructors, races, and circuits.

It is designed to:

* Provide a **high-level executive summary**
* Enable **deep dive analysis into driver and race performance**
* Surface **trends, competitiveness, and reliability insights**
* Present data in a **clean, business-focused format**

The dashboard uses historical F1 data (1950–2017) and transforms it into actionable insights through Power BI modeling and DAX measures.

---

##  Dashboard Preview

### Executive Overview  
![Executive Overview](Screenshot%202026-03-20%20112505.png)

### Race Results Dashboard  
![Race Results](Screenshot%202026-03-20%20112524.png)

---

##  Executive Overview 

This page acts as a **landing page for stakeholders**, summarizing the entire dataset.

### Key KPIs

* **Seasons Covered (69)** → Shows dataset time span
* **Total Races (997)** → Scale of competition
* **Total Drivers (842)** → Depth of participation
* **Total Constructors (208)** → Team diversity

### Highlights

* **Winningest Driver: Michael Schumacher**
* **Winningest Constructor: Ferrari**

 Purpose:

* Gives a **quick snapshot of the sport’s scale and history**
* Helps non-technical users immediately understand the dataset
* Acts as a **navigation hub** to deeper analysis pages

### Navigation Buttons

* Race Results
* Driver Analysis
* Constructor Analysis
* Lap Analysis

These allow users to move between different analytical views, making the dashboard feel like a full application rather than a static report.

---

##  Race Results Dashboard

This page focuses on **race-level insights, competitiveness, and performance trends**.

---

###  Top KPI Cards

#### 1. Race Competitiveness (7.11)

* Measures how competitive races are (e.g., overtakes, field spread)
* Includes **YoY growth (+3.2)**
   Insight: Racing has become more competitive over time

#### 2. Pole Conversion (42%)

* % of pole positions converted into wins
* Includes:

  * Avg winner starting position (P2.7)
     Insight: Starting first does **not guarantee victory**

#### 3. Unique Winners (107)

* Total number of different race winners
* Includes:

  * Field balance
  * Top driver dominance share
     Insight: Indicates parity vs dominance eras

#### 4. Race Reliability (74.73%)

* Measures how often drivers finish races
* Includes:

  * DNF trends
  * Risk levels by circuits
     Insight: Reliability has improved but varies by track

---

###  Grand Prix Map

* Displays all race locations globally
* Helps identify:

  * Geographic distribution of races
  * Expansion of F1 over time

 Insight: Shows how F1 evolved from Europe-centric to global

---

### 🏁 P1 by Driver (Bar Chart)

* Top drivers ranked by total wins
* Example:

  * Michael Schumacher
  * Lewis Hamilton
  * Alain Prost

 Insight: Quickly highlights **all-time greats**

---

###  Wins by Constructor (Line Chart)

* Tracks constructor wins over time
* Multiple teams displayed simultaneously

 Insight:

* Shows **eras of dominance** (Ferrari, McLaren, etc.)
* Reveals how competition shifts across decades

---

###  Circuit Table

Columns:

* Grand Prix Count
* Avg Positions Gained
* Avg Fastest Lap Speed

 Insight:

* Identifies:

  * Tracks where overtaking is easier
  * Faster vs slower circuits
  * Strategic race environments

---

###  Overtaking Over Time (Line Chart)

* Tracks overtaking trends across years

 Insight:

* Helps analyze:

  * Rule changes impact
  * Aerodynamics evolution
  * Era-specific racing styles

---

###  Filters Panel

* Year
* Constructor
* Driver
* Status

 Purpose:

* Enables **interactive slicing of data**
* Lets users explore:

  * Specific drivers
  * Specific eras
  * Team performance

---

##  Skills Demonstrated

This project showcases:

### Data & Analytics

* Data modeling in Power BI
* DAX measures (KPIs, YoY, rates, aggregations)
* Handling historical datasets

### Visualization

* KPI cards with contextual insights
* Time series analysis
* Geographic mapping
* Comparative analysis

### Product Thinking

* Executive vs analytical views
* User-friendly navigation
* Business storytelling through data

---

##  Future Improvements

* Add **driver comparison tool**
* Include **lap-level analysis**
* Integrate **real-time or recent season data**
* Enhance **predictive insights (ML / forecasting)**

---

##  Why I Built This

This project was created to:

* Strengthen my **data analytics and visualization skills**
* Practice building **end-to-end dashboards**
* Translate raw data into **clear, actionable insights**

---


* Help you write a **Driver Analysis README section** (even stronger for GitHub)
* Or help you **add 2–3 advanced visuals** that make this look *senior-level* (like win probability, dominance index, etc.)
