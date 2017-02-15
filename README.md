# Menagerie of testing

Different breeds of automated testing, for comparative purposes.

Forks, requests and PRs welcome. Please reuse under creative commons (see footer.)

## Scope

Test correctness at the following sizes:

### Unit

Smallest: test code corresponds closest to testable code; other layers injected or mocked.

### Integration

Medium: testable code involves more than one layer or unit; comined behaviour tested.

### System

Largest: entire application invoked for each test.

## Assertion

Confirm testable code works successfully, by defining success as:

### Behavioural

Human-like progressing from one part of the test to another, checking elements of a journey in turn.

### Functional

Procedural checking of elements of functionality, each independently from the next.

## Reason

Write the test in order to satisfy the following business requirement(s):

### Regression

Prevent a bug from arising during future development.

### Acceptance

Confirm the current state of development works as required.

### Performance

Determine the capability of the testable code to withstand heavy traffic.

### Smoke

Determine the point at which the testable code is overwhelmed by traffic.

-----------

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons Licence: Attribution-ShareAlike 4.0 International" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/80x15.png" /></a>
