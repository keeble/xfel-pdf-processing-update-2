---
marp: true
theme: rose-pine
size: 16:9
backgroundImage: url('../assets/dls_blue.png')
style: |
  h1 {
    font-size: 4rem;
  }
  h2 {
     font-size: 2.2rem; 
  }
  h3 {
    font-size: 1.8rem;
  }
  p {
    font-size: 1.5rem;
    font-weight: 200;
    }
  li {
    font-size: 1.5rem;
    font-weight: 200;
    color: var(--text);
  }
---
# <!--fit-->uf-TS/PDF Software Meeting 2
![bg opacity](../assets/gradient.jpeg)
Dean Keeble
20th July, 2023

---
## Agenda
1. Welcome
2. Review of previous meeting
3. Update from Dean
4. Discussion of sample database options
5. Pre-visit computer access
6. November experiment logistics
7. AOB

---
## Review of Previous Meeting - Actions
1. Collect a blank data collection into our pre-visit session so that we can familiarise ourselves with the offline file formats (Karen + HED team)
2. :white_check_mark: Finalise the design of the detector geometry and distribute the drawings when available (Karen + HED team)
3. :white_check_mark: Build a multigeometry in pyfai to simulate data according to the finalised drawings (Phil)
---
4. :pause_button: Define the dependencies required in a python environment for it to be useable within EXtra-metro (Thomas, Luca?)
5. :pause_button: Confirm an environment can be built which contains both pyFAI and PDFgetX3 and the deps specified above (Dean)
6. :white_check_mark: Confirm the impact that "gaps" have on PDFgetX3: what value should they take? can they be masked? what impact should we expect? (Dean)
---
7. :white_check_mark: Is it possible to do a better job mitigating the characteristic features seen close to gaps with data which are not azimuthally symmetric? (Dean)
8. :white_check_mark: It was mentioned that DAMNIT runs on SQLite, meaning we can't write from EXtra-metro processing but we can read. Draw out a data schematic for the various collections we'll use (Dean)
9. Convert these schematics to toy/psuedo context files (Dean)
---

## Update from Dean
overall schematics and context files
gaps
databases
gap mitigation

---

## PDFGetX3 and detector gaps
![width:400](../assets/pdfgetx3.png) ![width:400](../assets/pdfgetx3_zoom.png) 

The exact detector geometry is yet to be finalised, but processing should be prepared for incomplete data

---
- Some simple linear fitting gives the best match to the original data
- For certain applications filling a high-Q gap may not be necessary
![bg right w:700](../assets/fitted.png)




---

## Discussion on database options

---
## Pre-visit computer access

---
## November experiment logistics

---
## Any Other Business


