<!-- This Heuristic Evaluation Workbook replicates the one proposed by the 
Nielsen Norman Group available at: https://media.nngroup.com/media/articles/attachments/Heuristic_Evaluation_Workbook_-_Nielsen_Norman_Group.pdf
-->

**Evaluator**: [Rúben Gomes]
**Date**: [24-2-2024]
**Product**: [Meetup]


Severity Scale adopted: [[severity_scale_heuristic_evaluation]]
Summary of each usability heuristic: [here](https://media.nngroup.com/media/articles/attachments/Heuristic_Summary1-compressed.pdf)

# 1 Visibility of System Status
>	The design should always keep users informed about what is going on, through appropriate feedback within a reasonable amount of time. 
>	- Does the design clearly communicate its state?
>	- Is feedback presented quickly after user actions?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Upon creating an account, a internal server error is shown. | 3            | Show more options on how to proceed. Could be considered a turn-off for the user (since it's the first experience of the user). | 
<!-- | Another thing   | 4            |                | -->

# 2 Match Between System and The Real World
>	The design should speak the users' language. Use words, phrases, and concepts familiar to the user, rather than internal jargon. Follow real-world conventions, making information appear in a natural and logical order. 
>	- Will user be familiar with the terminology used in the design? 
>	- Do the design’s controls follow real-world conventions?

<!-- | **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Something wrong | 3            |                |
| Another thing   | 4            |                | -->

The UI is fairly simple and user-friendly, maybe even _too much_ simple.

# 3 User Control and Freedom
>	Users often perform actions by mistake. They need a clearly marked "emergency exit" to leave the unwanted action without having to go through an extended process. 
>	- Does the design allow users to go back a step in the process? 
>	- Are exit links easily discoverable? 
>	- Can users easily cancel an action? 
>	- Is Undo and Redo supported?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Email notifications on by default | 2            | Ask the user if they want them enabled or not. Can be quite annoying receiving multiple emails a day. |
| No undo button on bio creation. | 2            | Add it somehwere below the text field (not everyone knows Ctrl + Z!). Can be frustrating creating a bio and accidentally deleting it. |

# 4 Consistency and Standards
>	Users should not have to wonder whether different words, situations, or actions mean the same thing. Follow platform and industry conventions. 
>	- Does the design follow industry conventions? 
>	- Are visual treatments used consistently throughout the design?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Home button may be somewhat "hidden" to inexperienced users | 0            | It is a industry standard having the logo as the home button, but some people might not know it. Make it stand out more! |
| No back button   | 2            | Since the home button is quite hidden, the user might have to rely on browser-specific tools (go forward/backwards) Maybe place one on the top right. |
| "Not going" option very hidden | 2 | To unmark an event as "Not Going", the user has to really look for the option of not going. Why would a "Share" button be more valuable than a "Not Going" button? Switch them! |

# 5 Error Prevention
>	Good error messages are important, but the best designs carefully prevent problems from occurring in the first place. Either eliminate error-prone conditions, or check for them and present users with a confirmation option before they commit to the action. 
>	- Does the design prevent slips by using helpful constraints? 
>	- Does the design warn users before they perform risky actions?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Error upon account creation | 3            | This error could be fixed with a more intuitive error message (i.e. refresh the page, go to home). With this being the first page upon creating the account, it might constrain users and make them lose interest right away. |
| No prompt on logging out. | 2            | A user could log out accidentally (since all colors are the same on the dropdown menu), which can cause frustration on the user, since they have to re-login. |
| No confirmation on attending to a activity | 2 | A user could simply missclick the "Attend" button without ever knowing, causing a false-positive on the organizer's end (may expect more people, may be occupying a free slot...). |
| Can't find any groups | 2 | By default, finding groups is locked to a 25 mile radius. Even after removing the distance restriction, I couldn't find any groups. Makes the app feel "dead" and with no purpose. |

# 6 Recognition Rather than Recall
>	Minimize the user's memory load by making elements, actions, and options visible. The user should not have to remember information from one part of the interface to another. Information required to use the design (e.g. field labels or menu items) should be visible or easily retrievable when needed. 
>	- Does the design keep important information visible, so that users do not have to memorize it? 
>	- Does the design offer help in-context?

The UI features a calendar, which helps with keeping track of upcoming events.

<!-- | **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Something wrong | 3            |                |
| Another thing   | 4            |                | -->
# 7 Flexibility and Efficiency of Use
>	Shortcuts — hidden from novice users — may speed up the interaction for the expert user such that the design can cater to both inexperienced and experienced users. Allow users to tailor frequent actions. 
>	- Does the design provide accelerators like keyboard shortcuts and touch gestures? 
>	- Is content and funtionality personalized or customized for individual users?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| No keyboard shoutcuts | 2            | The app could use some keybaord shortcuts (like M for Messages, C for Connections...) |
<!-- | Another thing   | 4            |                | -->
# 8 Aesthetic and Minimalist Design
>	Interfaces should not contain information that is irrelevant or rarely needed. Every extra unit of information in an interface competes with the relevant units of information and diminishes their relative visibility. 
>	- Is the visual design and content focused on the essentials? 
>	- Have all distracting, unnescessary elements been removed?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Too many "Premium" ads | 2            | Just on the home page, 3 ads can be seen for a premium upgrade. Does there really have to be that many? |
<!-- | Another thing   | 4            |                | -->
# 9 Help Users Recognize, Diagnose, and Recover from Errors
>	Error messages should be expressed in plain language (no error codes), precisely indicate the problem, and constructively suggest a solution. 
>	- Does the design use traditional error message visuals, like bold, red text? 
>	- Does the design offer a solution that solves the error immediately?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| No solution provided for errors | 2            | The errors that occur within the app give little to no info. Tell the user what to do! |
<!-- | Another thing   | 4            |                | -->

# 10 Help and Documentation
>	It’s best if the system doesn’t need any additional explanation. However, it may be necessary to provide documentation to help users understand how to complete their tasks. 
>	- Is help documentation easy to search? 
>	- Is help provided in context right at the moment when the user requires it?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Help at the bottom of the page | 1            | Can be quite hard to spot if the user is not paying attention. |
<!-- | Another thing   | 4            |                | -->
