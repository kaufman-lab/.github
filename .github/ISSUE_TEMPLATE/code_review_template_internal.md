---
name: Internal Code Review Issue
about: Use this template when requesting a Code Review for Internal Code
title: "[DATE]: Code Review"
---

## Package Review

*Please check off boxes as applicable, and elaborate in comments below. Both author and reviewer may edit this form.* 

See the EAC Developer's Guide section on code review [here](https://kaufman-lab.github.io/eac-devguide/code-review.html).

#### Justifications
- [ ] **Privacy** Reviewer and author has agreed that this tool should not be published as open source 
- [ ] **Languages other than R** (if applicable) The author and reviewer agree that there is a compelling case to write this code in a language other than R. 

#### Documentation

The package includes all the following forms of documentation:

- [ ] **A statement of need** clearly stating problems the software is designed to solve and its target audience in README
- [ ] **Installation/Setup instructions:** for the development version of package and any non-standard dependencies in README
- [ ] **Vignette(s)** demonstrating major functionality (for simpler packages, package usage can be demonstrated in the README)
- [ ] **Function Documentation:** for all exported functions AND important internal functions
- [ ] **Examples** for all exported functions
- [ ] **Attribution** including author(s) and reviewer(s) 

#### Functionality

- [ ] **Installation:** Installation succeeds as documented.
- [ ] **Functionality:** Any functional claims of the software been confirmed.
- [ ] **Performance:** Any performance claims of the software been confirmed.
- [ ] **Automated tests:** Unit tests cover essential functions of the package (the author and reviewer may agree this can be waived for simple tools). 
   and a reasonable range of inputs and conditions. All tests pass on the machine on which the package is to be used.  
- [ ] **Portability:** To the extent possible, the code does not contain absolute paths or depend on its location on our server. 
- [ ] **Security:** No secrets (passwords, sensitive information, etc.) are tracked in the Github repo.

### Review Comments
