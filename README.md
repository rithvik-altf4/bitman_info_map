# BITMAN Info Map (ADM Focus)

This project scrapes course information from BCIT’s public website and turns it into a structured dataset.

For this assignment, I narrowed the scope to:
- **BITMAN Common Year 1 courses**
- **Analytics & Data Management (ADM) option courses**

The goal is to take unstructured web content (HTML) and convert it into clean, usable data for building a “course map” later (ex: prerequisites + course planning).

---

## What I built

I created a Jupyter notebook that:
1. pulls course codes and outline links from the two BCIT program pages  
2. visits each course page on BCIT
3. extracts course name + prerequisite text (when available)
4. saves the results as a CSV file

---

## Data sources

BCIT Program pages:
- https://www.bcit.ca/programs/business-information-technology-management-diploma-full-time-6235dipma/
- https://www.bcit.ca/programs/business-information-technology-management-analytics-data-management-option-diploma-full-time-623cdipma/

Full source list is in **CITATIONS.md**.


