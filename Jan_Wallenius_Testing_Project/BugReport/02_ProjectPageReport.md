
## Summary (Summarize the bug encountered concisely)

    On the new project creation page https://gitlab.com/projects/new, there is a typo in the heading of the upper left selection box.

## Steps to reproduce     

   When the user goes to the new project creation page by selecting 'New project' from the 'Projects' list, the error appears immediately after the selection.

## What is the current bug behavior?

    Midmost word in the heading of the upper left selection box is showing as 'black'.

## What is the expected correct behavior?

    Midmost word in the heading of the upper left selection box is supposed to show as 'blank'.
     
## Relevant logs and/or screenshots

[comment]:![](https://i.imgur.com/GchRTmC.png)

![Image info](../Image/Bug_Project_create_blank.png)

## Possible fixes

    The HTML code and/or script of the project creation page must be corrected.

## Whom do you report/ Assign To/ Tags

    /label ~bug ~reproduced ~needs-investigation /cc @project-manager /assign @qa-tester

## Priority

    Severity of the bug is major because it confuses user and can be perceived as an website spoofing attempt.
