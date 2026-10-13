# Data profiling before integration

**DAT 325 Project Two | Academic coursework | Private review draft**

An academic review of data from an acquired-firm scenario, intended to identify quality problems before integration. The report documents Python and pandas profiling and proposes source-verified corrections.

[Read the one-page PDF](case-study.pdf)

## Completed analysis documented

Reviewed Age, Marital_Status, Days_Employed and Citizen_Desc for missing values, invalid categories and unusual numeric values. The report names pandas missing-value and descriptive-statistics methods as part of the profiling approach.

## Reported findings

- Age: a missing value, a negative value of -39 and an extreme value of 139.
- Marital_Status: four missing values and the invalid category Female.
- Days_Employed: a missing value, a negative value of -514 and an extreme value of 52,246.
- Citizen_Desc: a missing value and the invalid category Male.

## Correction decisions

Verify affected entries against reliable source records. Correct only values that can be confirmed, document unresolved records, and investigate extreme values before deciding whether to change or remove them. The report does not support automatic deletion or guessed replacement values.

## Proposed transformations

Split Employee_Name into separate first-name and last-name fields, trim extra spaces, and standardize DOB to the destination date format before a future merge. These transformations were specified, not demonstrated as completed.

## Scope and evidence

The evidence is the written profiling report. No notebook, Python script, input dataset, execution log or validated output was available to reproduce the results. The report does not establish a completed cleanup or successful merge. No personal employee records are included here.

## Skills demonstrated

Data profiling; anomaly assessment; validation planning; transformation mapping.

## Source and attribution

Olga Solodovnikova, Project Two Executive Summary Report, DAT 325, Southern New Hampshire University, October 2, 2026. The report cites pandas DataFrame.isnull and DataFrame.describe documentation.

This is a new portfolio adaptation of the coursework, not the original assignment submission. See the [source register](../../SOURCES.md). Raw course data and assignment templates are not redistributed.

## Before sharing publicly

Locate the original notebook or script and permitted data. A future reproducible version should include environment details, validation rules and evidence of any corrections actually performed.

[Back to portfolio](../../README.md)
