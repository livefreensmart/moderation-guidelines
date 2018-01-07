# Moderating Analysis Contributions

*"Data analysis, also known as analysis of data or data analytics,
is a process of inspecting, cleansing, transforming, and modeling
data with the goal of discovering useful information, suggesting
conclusions, and supporting decision-making."*
Source: ["Data Analysis" on Wikipedia](https://en.wikipedia.org/wiki/Data_analysis)

## What counts as an analysis contribution?

* Make sure contributions actually match the above definition
* Pure data visualization is not analysis. If you can plot it
with a single line of SQL in Excel, it's most likely not analysis.
* No daily reports.
* No reports on single Steem accounts or small account groups unless it
is "of relevance for Steem"
* Weekly reports are tolerated, but must contain a wide set of common
data. There should be a correlation of the data with (all) previous
weeks and there should be analysis/conclusions involed.

## General checks

* Steem blockchain analysis contributions should use the repository
"steemit/steem", not "steemit/condenser" and not a custom repo with
the analysis/query scripts.
* Utopian/Utopian-Bot analysis contributions should use the repository
"utopian/api.utopian.io", not the frontend repo "utopian/utopian.io"
* Make sure the contribution contains information or scripts how 
the data was gathered. The full database query or a github repo 
with all required scripts to repeat the analysis is best, but a
description of the logical steps can be suffient in many cases as well.

## Quality checks

* are the graphs sane? Is there actually information contained, or is the 
relevant message hidden due to wrong axis scales, time ranges, meaningless
pie charts, ...
* check for axis labels, legends, units
* are the analysis conclusions drawn by the author actually backed with data?
