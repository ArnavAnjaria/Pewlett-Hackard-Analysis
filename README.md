# Pewlett-Hackard-Analysis

## Overview

As Pewlett-Hackard is beginning to see many employees retire, the company would like to be prepared to see what positions will need to be filled. Bobby, is asking for assistance in checking, from their databases who is retiring. We are going to use SQL queries to do the analysis for Bobby.

## Results
- The first deliverable shows us the breakdown of the titles of the employees that are going to be retiring. This will give the team a good idea of what positions need to be filled soon.
- Knowing these numbers beforehand will allow the company to decide if they want to fill from within or look to hire people and provide training before the wave of retirees hits. 
- This leads into the mentorship program that P-H is working on, allowing them to specify overall areas where mentorship may be more useful compared to other areas
- They would also be able to see which current employees would be a good fit for the mentorship program based on the mentorship_eligibility.csv file that has been produced.

## Analysis

- There will be 72458 positions that need to be filled as the Silver Tsunami makes an impact
    - Query used: SELECT COUNT(*)FROM unique_titles;
- There are 1549 eligible employees who will be able to mentor the next generation of the P-H workforce
    - Query used: SELECT COUNT(*)FROM mentorship_eligibilty;