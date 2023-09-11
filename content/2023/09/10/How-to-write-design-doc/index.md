---
title: "How to write design doc"
date: 2023-09-10T23:13:14+08:00
updated: 2023-09-10T23:13:14+08:00
taxonomies:
  tags: ['Tech']
extra:
  source: 
  hostname:
  author: leonahq
  original_title:
---
## Overview

Main Things to get accross:
**current stage**
	 We have XXX issue and we don't do anything about fixing/preveninting it
	 This documents describe how we imporve the data quality

--------------------
## Background

Goals of the background:
- Should provide enough context such as the "goals" makse sense to the reader:
	- We should use the background to define the probem that our goal is trying to address
	- E.g if we mention that we ight want to create a shared lib for computing, we should mention in badground that all of premium compuation logic is in multople place, duplicate code and error-prone
	- The background provied general context and domain knowledge about the problem so that they are understand the rest of the document



Discuss pior history, and talk(brief) about the current process.
Tool for reder to get previous content to understood my solution.
Context could be:
- Why is the problem important
- Different things that might be mentioned in proposed solution
>Goal should be drived from the background

for example- Background:
> In 2020, we created the policy premium validated job...> 
--------------------
BELBOW is where we start to talk about the issue with the current stage that describe above

> The current issue are:
>- a
>- b
>- c...

----------------
## Goals
Should be the END RESULT （不要有action item), should <-> support you proposed solution
>X: Implemenet an validation that apply to only off-ex IVL ...
  O: No persist premium data defects for applicable LoBs(off-ex IVL and off-ex SG)

This explain why we would even consider adding a person service validation
PRD goals can be different from eng goals(different audience)

------------------------
## Resource
List *EVERY* single external resource/document referenced
- e.g link to PRD, link to old TD on ...
- Link. to BQ
- bullet per source
--------------------
## Proposed solution

