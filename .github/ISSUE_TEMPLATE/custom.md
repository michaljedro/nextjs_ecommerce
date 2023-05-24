---
name: Custom issue template
about: Describe this issue template's purpose here.
title: ''
labels: ''
assignees: ''

---

# Code of Good Code Review

1. I have read and understood the task.
2. I have read the description of this PR.
3. I tested the changes implemented in this PR.
4. I have read and understood the code added or modified in this PR.
5. I am fully convinced that I would like to use such an application with the change implemented in this PR.

If I'm unsure about any of the points above - let me know by commenting on Code Review.

---

# Description

<!-- What have the changes achieved?
 -->

A screen has been added between Home and Quiz asking the user about the criterion they want to follow when making decisions. There are 3 suggested options to choose from and the "Other" option, which, when selected, shows a text field to be completed by the user.


Validation works in the form:
- select any option before clicking Next;
- if the "Other" option has been selected, the user must enter min. 10 characters.

### Link to issue

<!-- Link to the issue on GitHub
 -->

[Description](url)

### a list of changes

- [ ] the Criterion screen with the form has been added
- [ ] 
- [ ] 

<!-- Optional fields
 -->

# Screenshot

<img width="512"  />
