---
layout: docs
type: [review]
title: Test Review and Approval Process
---

## Test Review Policy

In order to encourage a high level of quality in the W3C test
suites, test contributions must be reviewed by a peer.

Reviewers may be:

- Spec editors
- The test coordinator for that spec
- An implementor
- Anyone with the ability to read and understand the spec along
with an understanding of the [format][format] and [style][style] guidelines 

**The reviewer can be a colleague of the contributor as long as the**
**proceedings are public.**

**A reviewer cannot review his/her own tests and changes.**

*To assist with test reviews, a [review checklist][review-checklist]*
*is available.*

## Test Review and Approval Process on Github

The preferred method for reviewing tests is on Github. The general 
workflow for test reviews and approval follows the GitHub
contribution model and is summarized here: 

* To initiate a review, make a Pull Request to the main 
```web-platform-tests/master``` or ```csswg-test/master``` on 
GitHub. This will notify all subscribers of the PR, including 
the test coordinator and test reviewers.
* Reviewers should review the test code and reply accordingly in 
Github. If no issues are found, the reviewer should state that so 
there is a trail a review was done. 
* After all of the review issues are addressed, the PR will be 
merged into the repository. The merge may be done by the spec's Test 
Facilitator or someone that is overseeing the test repository.
* The merged tests are considered Approved.

[format]: ./test-format-guidelines.html
[style]: ./test-style-guidelines.html
[review-checklist]: ./review-checklist.html
