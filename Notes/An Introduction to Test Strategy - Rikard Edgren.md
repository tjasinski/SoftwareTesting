# An Introduction to Test Strategy - Rikard Edgren

1. [Testing Mission](#test-mission)  
  The reason for testing  

2. [Context Analisys](#context-analisys)  
  Finding out what's important.

3. [Test Strategy](#test-strategy)  
  What to test, and how.

## Testing Mission

If you don't know what value testing brings, it is very difficult to do good testing.

Definition:  
*Testing mission is the answer to **Why do we test ?***

The mission is also given by **people**.

### Why do we test ?

- To find important problems
- To assess quality
- Because we have to
  
All three may be interested in the same things:

- Bugs
- Enhancements
- Performance
- Reliability
- Usability
- Security
- Standards
- Regulations
- Benefits
- ???

If you have a vague mission, like  
*test the product* - **use 'so' trick.**
  
    *test the product*  
    *so we can find important problems*  
    *so we can take well-informed decissions*  
    *so ...*
    *so ...*

Find out what's important:

- Talk to stakeholders
- Investigate relevant information sources:
  - Specifications
  - Quality objectives
  - Fears
  - Technologies
  - Bussines knowladge
  - Real customers
  - ..., see [37 Sources for Test Ideas](https://testingideas.wordpress.com/2015/09/08/37-source-for-test-ideas-from-the-test-eye/)

Recognize important problems

- by ivestigating examples:
  - Patches
  - Complaints
  - Bad reviews
  - Embarassments
  - Bugs

- by guidelines:
  - Quality objectives
  - Error catalogue
  - Checklists
  - Requirements
  - Case studies

## Contex Analisys

(Based on James Bach's HTSM)

How should the project environment effect the testing ?

- Other's testing
- Developer/Tester interaction
- Test environment
- Planning and deliverables

What should be tested ?

- Create models (James Bach's SFDIPOT)

Which quality characteristics matter ?

## Test Strategy

The strategy drives the testing, in order to reach the testing mission.

Definition:  
*Test strategy consists of guidelines and ideas that describe **what** should be tested, and **how**.*

It' more than test plan or test process.

It's written to communicate to (at least) two audiences:

- Stakeholders
- Testers

Test Strategy need details to be really useful.

Every situation requires a unique test strategy.

A good test strategy is specific, justified and realistic.

It is better to test preety well in many ways, than perfect in one or two (*Lessons Learned in Software Testing*)

### Aspects of test strategies

- What is important?
- Goals
- Test techniques
- Test ideas
- Information resources
- Oracles
- Models
- Quality objectives
- How testers think
- Trade-offs

Test strategy should be anchored in:

- Situation (context)
- Management (information needed)
- Testers (know what and why)

... should be adjustable - thing are always change.

Test strategy (on non verbal level) should also contain a bit of:

- risk judgment
- test design
- communication

***Testing is never better than the communication of the results.***

### The results of developing an anchored test strategy

- You have learned a lot
- You have many ideas about what to test, and how
- You have a starting point for reporting
- You have stakeholders agreeing what are you up to
