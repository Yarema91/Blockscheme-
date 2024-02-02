<!-- Add custom styles for Mermaid Gantt chart -->
<style>
  .grid .tick {
    stroke: lightgrey;
    opacity: 0.3;
    shape-rendering: crispEdges;
  }

  .grid path {
    stroke-width: 0;
  }

  #tag {
    color: white;
    background: #fa283d;
    width: 150px;
    position: absolute;
    display: none;
    padding: 3px 6px;
    margin-left: -80px;
    font-size: 11px;
  }

  #tag:before {
    border: solid transparent;
    content: ' ';
    height: 0;
    left: 50%;
    margin-left: -5px;
    position: absolute;
    width: 0;
    border-width: 10px;
    border-bottom-color: #fa283d;
    top: -20px;
  }

  .taskText {
    fill: white;
    text-anchor: middle;
  }

  .taskTextOutsideRight {
    fill: black;
    text-anchor: start;
  }

  .taskTextOutsideLeft {
    fill: black;
    text-anchor: end;
  }
</style>

<!-- Mermaid Gantt chart code -->
### 2  ![Online flowchart](https://mermaid.live/edit#pako:eNp1Uktr4zAQ_iuDzikkTjYtvnXb7uMQKC20FHxRrbF3wJKMNM4SSv97R1IckkODD2H06XtpPlTrDapa9doxNw6AiQeEZw6asT_AbWAIGMmgazGdG5n_8sFqhjf5pVHElsk72GlHHcZMA3CPHTkE_ofQ-oAwBnItjQNG0M5A7_UQwXcZkFSeZpW6WlbV1XIl3wJWG1Po4C6R7PUwYazhHLJeHiE7ijH5iCweLTq-xG3_F9gLZVTnQ9bW5wnnG-tz5jnfH28x2WQv5cig0N2GoF2P4AcjGdFSlIQ1HIm2mejmKP3XdUFHDlPLk6QxuMfBj8kqxNGf_G5K9B8X6nfe2slRe5J-xXeIxFi05E5VrlVZ7Ofg-55cX18cVpt8-LAXyfIO6cFIap1LXS0LsHT6W9rmU98lTLEFj1KasGQ7s4gArsVBSfutcbVQFmWDyMjifaRJo-QlLDaqlr8GOz0N3KjGfQpUT-yfD65VtfSGCzWNaQXvSfdB23mIhuRVdmWX80p_fgG_9uSm)


```mermaid
---
displayMode: compact
---
gantt
  title Strategy for Art Residence Development
   %% This is a comment
  dateFormat YYYY
  section 1 Manifest
    Define the core principles and goals of the Art Residence: done, 2022-01-01, 14d
     Core values: done, 2022-01-01, 30d
    Mission statement: done, 2022-01-01, 6w
    Vision for the art residence: done, 2022-03-01, 30d
  section 2 Home Restoration
    Arrange old premises :  2022-06-01, 8w
    Infrastructure development spot: 2022-04-01, 15d
  section 3 Communication
    Web site:  site, 2024-02-01, 12w
    Blogging: crit, active, 2024-02-01, 24w
    Events and festivals: 2022-10-01, 2d
    Guests: milestone,2022-06-01, 5d
    Presentation: 2024-06-07, 1w
   section 4 Administration Liaison and Funding
     Building Team: team, 2024-01-01,2w
     PubOrg: 2024
     Grants and tender: after team, 2y
     Shop: after site, 2w
     Donation: 2024-02
```
