# Epstein Flight Logs
This is the data from the flight logs of Jeffrey Epstein's private jet, The Lolita Express. The purpose of this project is to organize the data into readable formats.

#### Table of Contents
- [Objective](#objective)
- [Data Structure](#data-structure)
- [How to Contribute](#how-to-contribute)
  - [Create an Issue](#1-create-an-issue)
  - [Do the Workd](#2-do-the-work)
  - [Submit a Pull Request](#3-submit-a-pull-request)
- [Help Needed](#help-needed)
- [Official Sources](#official-sources)
- [Unofficial Sources](#unofficial-sources)

## Objective
So much of the data about current events is hidden within the text of ephemeral articles. Often times, these data exist only as poorly scanned documents in unreadable formats, only to become broken links. The first step to understanding the truth of a story is organize the facts. This is a task that takes a team. I can think of no better collaborative system than GIT. Let's liberate the truth from the shackles of obscurity together.

## Project Details
We want to make this information easy to consume for humans and computers. The important information this data must communicate is:

- when the flights took place,
- where flights went, and
- who was on them.

The data structure should reflect this. Yes, we want to include as much data as possible, but not at the expense of the overal focus. With that said, the data structure is not set in stone. If there's a better way to structure this to communicate the information, create and issue and we can discuss it.

## How to Contribute

### 1. Create an Issue
Create an issue for the task you're going to complete. This way we can track what data is being entered so we don't do work that's already been done.

**Example Issue:** `Enter flight data between from dates between [YYYY/MM/DD] - [YYYY/MM/DD] referenced in pages [00]-[00] of [document_name]`

### 2. Do the Work
Check and doublecheck the data you enter to make sure it's correct. Don't convert passenger initials to names unless you're absolutely sure the initials reference that particular name.

### 3. Submit a Pull Request
- Reference your issue in the pull request.
- Include an image or PDF of the data you've transcribed so that it can be cross-checked. *(only reference sources in the offical sources list)*
- Include a link to the document that the changes were pulled from so that the source can be verified.
- Keep it manageable. Nobody likes 3000 line code reviews. If you're adding lots of data, split it up into multiple pull requests.

## Guidelines

### Only work on your issues
We don't want to double up work, so **only work on the issues you created or issues assigned to you**. It will be assumed that you are going to complete the issue you created.

### Don't let issues linger
Don't let your issues linger. If you create an issue that sits for more than two week without a pull request submission, the issue will be deleted so that someone else can complete that task. We don't want to drag this project out for 3 years waiting on someone to enter 5 flights.

### Reporting bugs
If you discover an issue with the data, but do not want to fix it, prepend your issue with `But Report:`

**Example Issue**: `Bug Report: Jeffrey Epstein spelled wrong on line 212 of json/flight-log`

## Help Needed

### Aviation Experts
Aviation experts, please help to organize this data correctly. It's not completely clear what everything in the flight logs means to someone who's never filled one out. For example, the Airplane column.

### Investigators
If you have additional sources of flight manifest data or passenger information, contact [epsteinflightlogs@protonmail.com](mailto:epsteinflightlogs@protonmail.com).

## Official Sources
The following are the publicly available flight records and their sources. Please only reference sources in this this list when creating issues. If you have discovered a new source, create an issue to add that source to the list. Only sources from trusted entities such as news companies and government websites.

### O-Source 01
Original document published by Gawker in 2015.

**Link:** [Epstein Flight Manifests](https://www.dropbox.com/s/ugplsdawnkvkfcv/GAWKER-epstein-flight-manifests.pdf?dl=0)  
**Filesize:** 9.6 MB  
**Source:** [Flight Logs Put Clinton, Dershowitz on Pedophile Billionaire’s Sex Jet](https://gawker.com/flight-logs-put-clinton-dershowitz-on-pedophile-billio-1681039971)

### O-Source 02
Recently unsealed document reported on by CNBC.

**Link:** [Epstein Court Documents](https://www.dropbox.com/s/4mlcoqri6t8m0nn/CNBC-epstein-court-docs.pdf?dl=0)  
**Filezie:** 178 MB  
**Source:** [Court releases documents about Jeffrey Epstein, accused in sex traffic case, and his alleged procurer Ghislaine Maxwell](https://www.cnbc.com/2019/08/09/documents-released-about-jeffrey-epstein-and-ghislaine-maxwell.html)

## Unofficial Sources
Unofficial sources may be helpful, but should not be the primary source of information data. If a more reputable prodiver of the source is found, an unofficial source can graduate to an official source. 

### U-Source 01
This may be useful for reading the information in o-source 01. It's essentially the same thing, just typed out in readable text.

**Link:** [Epstein Flight Logs](https://www.dropbox.com/s/0911d48rotdi2fl/RADAR-epstein-flight-logs.pdf?dl=0)  
**Filesize:** 673 KB  
**Source:** [Something To Hide? Jeffrey Epstein Orgy Plane Sex Logs ‘Sanitized’ To Protect Pals Like Clinton, Attorneys Claim](https://radaronline.com/exclusives/2015/01/royal-sex-scandal-prince-andrew-pedophile-flight-logs/)
