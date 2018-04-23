# The Playground
This is a distributed learning community around decentralized systems funding 6-week
long learning adventures. We're exploring the future of learning organizations.

<!-- markdown-toc start - Don't edit this section. Run M-x markdown-toc-refresh-toc -->
**Table of Contents**

- [The Playground](#the-playground)
    - [Motivation and Vision](#motivation-and-vision)
- [How does it work](#how-does-it-work)
    - [1. Propose an Adventure](#1-propose-an-adventure)
        - [A Goal](#a-goal)
        - [Structures](#structures)
        - [Community](#community)
        - [Artifacts and Outcomes](#artifacts-and-outcomes)
    - [2. Reviewing and funding](#2-reviewing-and-funding)
        - [Criteria](#criteria)
        - [Outcomes and Decision Making](#outcomes-and-decision-making)
    - [3. Funding and Adventuring](#3-funding-and-adventuring)
- [Change and Governance](#change-and-governance)
    - [PlIPS](#plips)
- [Appendix](#appendix)
    - [Roles](#roles)
        - [Reviewers](#reviewers)
        - [Dictator](#dictator)
        - [Funders](#funders)

<!-- markdown-toc end -->

## Motivation and Vision
Today's learning institutions are floundering. They divide ideas and people into
arbitrary silos, creating barriers against collaboration in the pursuit of
knowledge.

With the tools and systems available today there is the possibility for
radically new learning systems.

**This is a community to explore this future**

The focus is on decentralized systems. They are driving a revolution in 
digital infrastructure and provide powerful tools.

The playground challenges you to envision your ideal learning environment, build
it, and connect it to others, building piece by piece a community focused on
empowering _learning_ above all.

----------

# How does it work
The Playground funds adventures. Each learner on an adventure defines it's
subject and structure, what they're learning and how. Funds are distributed to
learners over a 6 week period to enable experimentation, creation, and novelty.

Each adventure is defined by a document in [/adventures](/adventures).

## Step 1. Propose an Adventure
Anyone can propose an adventure by opening a PR adding an adventure
document.

Adventures can be anything. Individual explorations of a niche subject, original
research, study groups, or any other scenario you can imagine for learning about
decentralized systems. For a proposal you need to decide how best to describe
_your_ adventure.

There are some general elements that your proposal should cover. They're
what others will judge, connect to, and build on.

### A Goal
What do you want to learn? Every adventure is a journey towards knowledge. To
coordinate around your adventure the playground community needs to understand
what it is you're going to learn.

### Structures
_How_ are you going to learn? What are the systems and processes that will best
create knowledge for you? What are the resources they will connect to? These can
be rigid or open-ended, but should be clearly defined.

### Community
An adventure does not exist in isolation. It should build upon, connect
to, support, and involve other adventures and the broader community. Who are you
working with, who are the people who will support you?

### Artifacts and Outcomes
Finally, adventures result in artifacts. This can be anything from
software created, to a log of your experiences. They should be
openly-licensed and accessible to all.

-------------------

If you're looking for some inspiration for your proposal check out some
[ideas](https://gitlab.com/fathom/playground/issues?label_name%5B%5D=idea),
[other
proposals](https://gitlab.com/fathom/playground/issues?label_name%5B%5D=proposal)
or [funded adventures](/adventures)

## Step 2. Reviewing and funding
Once you create a proposal, it's public. Others can comment on it, copy it, or
suggest changes. You can mark your proposal as WIP if you would like for
it to be public but not yet reviewed.

When you're ready your PR will be assigned a reviewer. Anyone can become
a reviewer by opening a [nomination issue](https://gitlab.com/fathom/playground/issues/new?issuable_template=reviewer).
Each reviewer operates for a fixed term, and new reviewers are added via
majority consensus. You can see the current reviewers
[here](#reviewers).

Reviewing is an interactive process; reviewers can ask questions or
provide suggestions and feedback. 

### Criteria
Adventures are judged on:

- How well defined they are
- How they engage with existing adventures and the broader community
- Whether they create knowledge, or support the creation of knowledge

These crtieria extend to all aspects of an adventure: subject,
structure, community, and artifacts.

### Outcomes and Decision Making
A reviewer can either close a proposal, if they think it's not valuable
to fund, or they can escalate it.

Once escalated all reviewers read the proposal. A proposal can then be
passed 2 ways: 

1. Majority consensus from all reviewers
2. A reviewer can unanimously pass a proposal with a wildcard (each
reviewer begins their term with 2)

## Step 3. Funding and Adventuring
Once an adventure is accepted a smart-contract is instantiated in order
to distribute funds to the learner.

The smart contract will allow them to withdraw funds at a fixed rate. It
will also allow the [Dictator](#dictator) to freeze the
funds indefintiely. These are the only two options.

This will **only** be used if the participant stops actively working
towards their adventure.

# Change and Governance
The playground, this community and the systems that support it, is
intended to grow and change, and so needs a governance model.

## PlIPS
The main mechanism for change in the Playground are PlIPs, Playground
Improvement Proposals. Anyone can create one by opening an
[issue](https://gitlab.com/fathom/playground/issues/new?issuable_template=PlIP).

After discussion a PlIP should result in an MR which can change any
part of the Playground, including this document. 

PlIPs can only be merged in by the [Dictator](#dictator).

# Appendix

## Roles
### Reviewers
| Name          | Term Start | Wildcards |
|---------------|------------|-----------|
| Jared Pereira | 2018/04/06 | 2         |
|               |            |           |

### Dictator

| Name          | Start      | Finish     |
|---------------|------------|------------|
| Jared Pereira | 2018/04/05 | 2018/08/01 |


### Funders
| Funder | Date       | Amount |
|--------|------------|--------|
| Test   | 2018-04-06 | $1000  |
|        |            |        |
