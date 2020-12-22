
# Security software users by income groups testing analysis

-   Author: Zhanyi Su (Yiki)

## About

In this project, I am interested in finding whether there is a
difference between the ratio of security software users by different
income groups.

The data set that I chose is from the Statistics Canada called “Internet
security software use, by household income, age group and level of
education,” which can be found
[here](https://open.canada.ca/data/en/dataset/6e45b085-1fbf-4ba4-881b-f4eebbb3764e).
This data set consists of the responses from the 2018 Canadian Internet
Use Survey (CIUS), which aims to collect information regarding the use
of digital technologies and the online behaviors for Canadians who are
over age 15 (2018 Canadian Internet Use Survey 2012). This data set has
400 observations with 18 attributes. Each observations represents a
survey response with information regarding the year of the security
software usage status (2010 or 2012), the geographical location of the
respondent, whether security software is used (free versions or paid
versions), income level of the respondents and etc.

## Usage

The replication of this project can be done by installing the following
dependencies and running the following command from the root directory
of this project to unzip the data:

Using `R`:

`Rscript script/download_data.R --url="https://www150.statcan.gc.ca/n1/tbl/csv/22100010-eng.zip" --out_path="data"`

The data file will be saved in a folder called `data`.

## Dependencies

-   R version 3.6.1 and R packages:

    -   docopt==0.7.1

# References

<div id="refs" class="references csl-bib-body hanging-indent">

<div id="ref-data" class="csl-entry">

2018 Canadian Internet Use Survey. 2012. “Statistics Canada.”
<https://open.canada.ca/data/en/dataset/6e45b085-1fbf-4ba4-881b-f4eebbb3764e>.

</div>

</div>
