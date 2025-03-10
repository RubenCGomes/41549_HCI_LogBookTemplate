[Back to main Logbook Page](../hci_logbook.md)

---
# B. Stage 1 - Context Definition


# B.1. Competitor Identification
>	The competitor analysis will entail an identification of all competitors, with brief descriptions and a collection of the look and feel of their solutions, e.g., with screenshots, etc. It will also include a detailed analysis of the competitor deemed the best or more representative. It ends with a summary of the main findings including an HCI SWOT analysis



## B.1a. Competitors


|  Competitor  | Description                             | Information repository              |
| ----------------- | ------------------------------------------- | ----------------------------------- |
|  [Meetup]    | [Platform to form groups and publish activities]        | [[Competitor Analysis AmazonShoes]] |
| [Eventbrite] | [Platform to browse, create and promote local events] |                                     |



## B.1b. Detailed Competitor Analysis
>	Choose the most notable competitor and do a more thorough analysis of their interactive solution

Most notable competitor: **Meetup**.

### - Heuristic Evaluation

#### Method
<!-- [ Describe the method used for the heuristic evaluation: procedure, number of experts, heuristics, severity scale considered, how was consensus done.] -->

The procedure for the HE was fairly straight forward. Each expert would create an account and navigate the website like the average user would.

2 experts were taken into account for this evaluation.

The severity scale used is present [here](heuristic_evaluations/severity_scale_heuristic_evaluation.md).

After each expert finished their HE, all the points were brought onto the table, and the most similar/common points were kept in mind into the consensus.


#### Individual Evaluations
<!-- For the individual heuristic evaluations by each member of the group, you can use the templates below, grouping problems by heuristic OR each evaluator can have a table listing all the detected problems with the number of the violated heuristics on the second column. Whichever your choice, you should have a list of problems, the severity, and a recommendation to mitigate it -->



- [113435_heuristic_evaluation_workbook](heuristic_evaluations/113435_heuristic_evaluation_workbook.md)

- [113446_heuristic_evaluation_workbook](heuristic_evaluations/113446_heuristic_evaluation_workbook.md)

<!-- - [expert3_heuristic_evaluation_workbook](heuristic_evaluations/expert3_heuristic_evaluation_workbook.md) -->


#### Consensus

>	After the individual analysis by each expert, all results should be gathered in a consensus table. If an expert has not found any of the problems found by other experts, they should analyse it, at this point, and give it a severity.

|     Issue       |   Expert 1   | Expert 2 | Recommendations |
| --------------- | ------------ | -------- | --------------- | 
| No Undo button on event signing | 2 | 2 | Switch the Share button with Undo |
| No back button on pages | 2 | 2 | Add a button to go to the previous page |
| Attending to a event has no confirmation | 2 | 2 | Show a prompt for the person to confirm |
| Error messages are not clear | 2 | 3 | Give more info to the user on how to act after the error. |


---
### - Cognitive Walkthrough

#### Method
<!-- [Briefly described  the method you used for the Cognitive Walkthrough analysis. ] -->

It was used a streamlined method for the Cognitive Walkthrough, as this was the one recommended in the lectures, and is perfectly applicable in this scenario. Simple and effective.

#### Task Selection and Task Analysis

<!-- [Which tasks did you select and why. What are the subtasks entailed for each ] -->

The tasks selected for the Cognitive Walkthrough were the ones that the average user would do upon signing up and using the website, defined below.


| Task                  | Subtasks                               |
| --------------------- | -------------------------------------- |
|  **1. Join a group**  | Sign on/login on the website |
|                       | Scroll down a bit to find the "Find more groups" button |
|                       | Select a relevant group |
|                       | Click "Join this group" |


| Task                     | Subtasks                                |
| ------------------------ | --------------------------------------- |
| **2. Attend to a event** | Sign on/login on the website |
|                          | Browse the page (or search) to find a interesting event |
|                          | Click on a event of interest |
|                          | Click on "attend" |



#### Results

Task: [Join a group]

| Step # | Task/Action to Perform | Will User Know What to do at this step? (Yes/No) | Notes | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No) | Suggestions for Improvement |     |
| ------ | ---------------------- | ------------------------------------------------ | ----- | ----------------------------------------------------------------------------------------- | ----- | ------------------------------ | --------------------------- | --- |
| 1      | [Sign on/login on the website]   | [Yes] | | [Yes] | | [Yes] | [N/A]| |
| 2      | [Scroll down a bit to find the "Find more groups" button]   | [No] | | [Yes] | | [Yes] | [On a medium/small monitor, the user has to scroll a fair amount to find it]| |
| 3      | [Select a relevant group]   | [Yes] | | [Yes] | | [Yes] | [N/A]| |
| 4      | [Click "Join this group"]   | [Yes] | | [Yes] | | [Yes] | [N/A]| |


Task: [Attend to a event]

| Step # | Task/Action to Perform | Will User Know What to do at this step? (Yes/No) | Notes | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No) | Suggestions for Improvement |     |
| ------ | ---------------------- | ------------------------------------------------ | ----- | ----------------------------------------------------------------------------------------- | ----- | ------------------------------ | --------------------------- | --- |
| 1      | [Sign on/login on the website]   | [Yes] | | [Yes] | | [Yes] | [N/A]| |
| 1      | [Browse the page (or search) to find a interesting event]   | [Yes] | | [Yes] | | [Yes] | [N/A]| |
| 1      | [Click on a event of interest]   | [Yes] | | [Yes] | | [Yes] | [N/A]| |
| 1      | [Click on "attend"]   | [Yes] | | [Yes] | | [Yes] | [N/A]| |

## B.1c. Overall Analysis

<!-- [Here, you should summarize the main findings for the competitor panorama, listing key points that are valuable to inform the design of your solution, and also make an HCI SWOT analysis for the main competitor, taking into consideration what you learned from the heuristic evaluatio, cognitive walkthrough, online reviews, user feedback, etc.] -->

Meetup uses a very simple UI, which ends up being one of its weaknesses. Too much simplicity leads to very few options, where the user can feel lost at times, and not know where to go, forced to use the "Back" feature of the browser or go to the main page, having to renavigate all over again.

The website is also prone to having a few errors in its flow that don't tell much to the user (i.e. upon creating an account, getting an error right away).

It does of course have its strengths, like being able to search for events and groups the user can join, or an oncoming event the user may want to attend to.

Down below is the HCI SWOT analysis of the competitor, which summarizes the evaluation.

| SWOT Element | HCI Focus | Example in UI/UX |
| ------------ | --------- | ---------------- |
| **Strenghts** | It tries to simplify the interface to make it not too crowded with information. Does have a calendar to keep track of future events. | The main page is a prime example of this. |
| **Weaknesses** | Suffers from too much simplification, which can make a user feel lost at times (no back button, can't directly undo "Going to event"). | While in another page (i.e. Messages page), the user doesn't know how to go back. |
| **Opportunities** | The app focuses too much on their "Premium" element, where a free user can feel very pointless while using the app, which could scare a potential customer away. | On the main page, the constant "Premium" upgrade buttons. |
| **Threats** | If a aspiring company would "bet their chips" on this area seriously and did it right, this application would surely lose a fair amount of clientele | [N/A] |
---

# B.2. Users
>	For the users, there are two goals: 1) understand the current status of users in the domain you are addressing. How do they manage, what are the main tasks they do, if they use some tool for the purpose, what are current challenges, what might be improved, what might be new features, ...


## B.2a. Method
<!-- [What approach was followed to talk with users; what kind of users were considered. What was the goal of the interviews? What were the questions considered?] -->

The main goal of the interviews were to get a general idea of what features a potential user would like to see in a application on this area, what difficulties they have on finding other people.

We considered users that would likely use our app, or that could give us a general idea on what could be introduced or expanded upon.

## B.2b. Results

>	This section tracks all informal user interviews, summarizing key insights and linking to detailed notes for each session. 

### Interview List 
| Date       | Participant / Role | Key Insights                                                    | Link to Notes                |
| ---------- | ------------------ | --------------------------------------------------------------- | ---------------------------- |
| 25-02-2025 | Simão / Student      | Plays football during weekends, would like to find people to "fill holes". | [📄 Notes](interviews/interview-simao.md) |     |
| 25-02-2025 | Tiago / Student      | Practices cyclcing, wouldn't mind cycling with others. | [📄 Notes](interviews/interview-tiago.md) |
| 25-02-2025 | UA Student / Student      | Goes to the gym with a friend, doesn't have interest in introducing more people. | [📄 Notes](interviews/interviewB.md) |
| 25-02-2025 | UA Student / Student      | Plays occasionally basketball. Has trouble finding people to play with. | [📄 Notes](interviews/interviewIS.md) |

### Common Themes & Patterns 

- **Recurring Problems:** 
	- Friends have busy schedules/can't reach a consensus.
	- Friends may not have interests in the same sports (or none at all).
- **Frequently Used Tools:** 
	- Texting apps.
	- In person.
- **Desired Features / Solutions:** 
	- Be able to have a pace/skill level, in order for everyone to have a good experience.
	- See activities on a map, and notify nearby interested people.
- --- 



---
[Back to main Logbook Page](../hci_logbook.md)

---
