# Data Donation Workshop 24.03 - 26.03.2025 @ IfKW, LMU Munich

These are the data and materials for the workshop "Collecting and Analyzing WhatsApp Data Donations".
It consists of both a presentation and some hands-on-sessions to code along.

The workshop builds both on the WhatsR R-package ([https://github.com/gesiscss/WhatsR](https://github.com/gesiscss/WhatsR)) and the ChatDashboard R-shiny webapp ([https://github.com/gesiscss/ChatDashboard](https://github.com/gesiscss/ChatDashboard)) for data donations.

**Goal:**
Semi-ineractive Walk-through of the process for **preprocessing**, **collecting**, and **analyzing** donated WhatsApp Chat Log data.

## Schedule

| Time             | Block                                                                    |
|------------------|--------------------------------------------------------------------------|
| 09:00 - 09:15    | Presentation: Overview of WhatsApp Chat Log Data                         |
| 09:15 - 09:45    | **Code along:** Exporting & Parsing WhatsApp Chat Log Data               |
| 09:45 - 09:55    | Presentation: Anonymization & Consent Checking                           |
| 09:55 - 10:10    | **Code along:** Anonymization & Consent Checking                         |
| 10:10 - 10:20    | Presentation: ChatDashboard for Data Donation Studies                    |
| 10:20 - 10:45    | **Code along:** Installing and adapting ChatDashboard                    |
| 10:45 - 11:00    | Discussion, Q&A                                                          |

<br><br>

## Whatsapp Chat Logs

To fully participate in the workshop, participants need WhatsApp chat logs to analyze. these can be obtained in different ways:

### Export your own chat log

We recommend to export the chat files using the `without media` option and by sending it to a private Email address.

#### Android

![](./Images/DataExport_Guide_Android.png)

<br>

#### iOS

![](./Images/WhatsApp_DataExport_iOS.png)

<br><br>

### Create a dummy chat log file

Participants can also use the WhatsR package to create a dummy chat log file themselves

```
# loading library
library(WhatsR)

# checking documentation
??create_chatlog

# creating a dummy chat log
create_chatlog()

```

### Use the Example Chat logs provided in this repo

This repository contains multiple pre-generated example chat log files that can be used as well. Participants can find them in the `data` folder.
