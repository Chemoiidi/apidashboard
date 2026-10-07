# SMP Command Centre Dashboard

A weekly performance dashboard for the Self-Made Protocol (SMP) fitness program. The project processes simulated API response data to analyze member performance, weekly activity, and SMP skill enrollment using core Python and JSON.

## What It Does

* Processes simulated member data
* Tracks steps, sleep, fasting protocol, and cold-shower participation
* Identifies members who reach the 10,000-step goal
* Calculates average member steps
* Analyzes weekly step performance
* Identifies the best-performing day
* Tracks enrollment across SMP skills
* Identifies the most popular skill
* Generates a formatted dashboard
* Exports key metrics as JSON

## Usage

```bash
python dashboard.py
```

The dashboard displays member performance, weekly step activity, skill enrollment, and a JSON summary of the results.

## Sample Output

```text
====================================================
 SMP COMMAND CENTRE DASHBOARD | Week 2024-W47
====================================================

 SECTION 1: MEMBER PERFORMANCE
 Total members:              6
 Hit 10,000 step goal:       3/6
 Average steps:              9,500
 Cold showers today:         5/6
 Goal hitters: Sandra Weru, Grace Achieng, Kevin Mwangi

 SECTION 2: WEEKLY STEPS
 Mon    54,200 ##########
 Tue    62,000 ############
 Wed    58,400 ###########
 Thu    71,000 ##############
 Fri    49,600 #########
 Sat    68,000 ##############
 Sun    65,200 #############

 Best day: Thu (71,000 total steps)
 Week avg: 61,200 steps/day

 SECTION 3: ACTIVE SMP SKILLS
 copywriting     15 enrolled
 tiling          12 enrolled
 phone repair    10 enrolled
 welding          8 enrolled
 beekeeping       6 enrolled

 Most popular: copywriting (15 enrolled)
```

## Stack

Python, JSON, Lists, Dictionaries, List Comprehensions, `sum()`, `max()`, `sorted()`, `zip()`, Lambda Functions, and String Formatting.
