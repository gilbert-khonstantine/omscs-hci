# CS6750 · Human–Computer Interaction — Open-Book Exam Companion

Complete lecture notes (Units 1–3, Lessons 1.1 – 3.5) with per-lesson summaries, key-point breakdowns, clickable cross-links and a keyword index. Source: David Joyner, CS6750 Summer 2017 lecture book, as supplied in 13 Markdown files. Full lecture text is reproduced verbatim in Part B; nothing has been shortened or omitted.

<a id="howto"></a>

## How to use this guide

This document is built from the 14 lecture-note files you supplied (13 unique lessons; the two “2.4 Human Abilities” files were identical, so that lesson appears once). It has three parts:

**Part A — Lesson Summaries & Key Points.** One block per lesson: what the lesson is about, every key point, and all of the lecture's numbered lists (every “5 Tips”, Norman's Seven Questions, the 15 design principles, the ISO principles, the IRB steps, brainstorming rules, etc.) broken out as numbered items so you can quote them point by point. Each block ends with a keyword box and a two-column jump list to every section of the full text.

**Part B — Full Lecture Text.** The complete, unabridged text of every lesson, in course order, with every section heading bookmarked. Nothing has been summarised away here, so if a question hinges on an exact example or sentence, this is where to find it.

**Part C — Keyword Index.** Alphabetical list of terms, people, books, papers, examples and lists, each pointing to the exact lesson and section with a clickable link.

**Navigation.** Blue underlined text is a clickable link. The PDF sidebar (bookmarks / outline) lists every lesson and section. In Part B the “»” symbol marks a change of speaker in a video transcript, exactly as in the source files.

**Exam tip.** Start from the Index (Part C) for a term, or from the Part A summary for a concept; both link straight into the verbatim text in Part B. Where the lecturer uses his own names for things (e.g. the “15 principles”, “processor / predictor / participant”), those names are used here too.

<a id="toc"></a>

## Table of Contents

- [Part A — Lesson Summaries & Key Points](#partA)
  - [Summary — 1.1 Introduction to HCI](#A-L1-1)
  - [Summary — 1.2 Introduction to CS6750](#A-L1-2)
  - [Summary — 1.3 Exploring HCI](#A-L1-3)
  - [Summary — 2.1 Introduction to Principles](#A-L2-1)
  - [Summary — 2.2 Feedback Cycles](#A-L2-2)
  - [Summary — 2.3 Direct Manipulation](#A-L2-3)
  - [Summary — 2.4 Human Abilities](#A-L2-4)
  - [Summary — 2.5 Design Principles and Heuristics](#A-L2-5)
  - [Summary — 3.1 Introduction to Methods](#A-L3-1)
  - [Summary — 3.2 Ethics and Human Research](#A-L3-2)
  - [Summary — 3.3 Needfinding and Requirements Gathering](#A-L3-3)
  - [Summary — 3.4 Design Alternatives](#A-L3-4)
  - [Summary — 3.5 Prototyping](#A-L3-5)
- [Part B — Full Lecture Text](#partB)
  - [1.1 Introduction to HCI](#L1-1)
    - [Humans](#L1-1-humans)
    - [Computers](#L1-1-computers)
    - [Interaction](#L1-1-interaction)
    - [Quiz: Reflections: Interacting & Interfaces](#L1-1-quiz-reflections-interacting-interfaces)
    - [The HCI Space](#L1-1-the-hci-space)
    - [HCI in the Big Picture](#L1-1-hci-in-the-big-picture)
    - [HCI vs Human Factors](#L1-1-hci-vs-human-factors)
    - [HCI vs User Interface Design](#L1-1-hci-vs-user-interface-design)
    - [HCI vs User Experience Design](#L1-1-hci-vs-user-experience-design)
    - [HCI vs Psychology](#L1-1-hci-vs-psychology)
    - [HCI: Research and Design](#L1-1-hci-research-and-design)
    - [Welcome to HCI!](#L1-1-welcome-to-hci)
  - [1.2 Introduction to CS6750](#L1-2)
    - [Introduction to CS6750](#L1-2-introduction-to-cs6750)
    - [Learning Goals](#L1-2-learning-goals)
    - [Learning Outcomes: To Design](#L1-2-learning-outcomes-to-design)
    - [Learning Outcomes: Effectiveness](#L1-2-learning-outcomes-effectiveness)
    - [Learning Outcomes: Between Humans and Computers](#L1-2-learning-outcomes-between-humans-and-computers)
    - [Learning Strategies: Video Material](#L1-2-learning-strategies-video-material)
    - [Learning Strategies: Georgia Tech](#L1-2-learning-strategies-georgia-tech)
    - [Learning Assessments](#L1-2-learning-assessments)
    - [Course Structure](#L1-2-course-structure)
    - [5 Tips Doing Well in CS6750](#L1-2-5-tips-doing-well-in-cs6750)
    - [Conclusion](#L1-2-conclusion)
  - [1.3 Exploring HCI](#L1-3)
    - [Introduction to Exploring HCI](#L1-3-introduction-to-exploring-hci)
    - [Technology: Virtual Reality](#L1-3-technology-virtual-reality)
    - [Technology: Augmented Reality](#L1-3-technology-augmented-reality)
    - [Technology: UbiComp and Wearables](#L1-3-technology-ubicomp-and-wearables)
    - [Technology: Robotics](#L1-3-technology-robotics)
    - [Technology: Mobile](#L1-3-technology-mobile)
    - [Idea: Context-Sensitive Comp](#L1-3-idea-context-sensitive-comp)
    - [Idea: Gesture-Based Interaction](#L1-3-idea-gesture-based-interaction)
    - [Idea: Pen- and Touch-Based Interaction](#L1-3-idea-pen-and-touch-based-interaction)
    - [Idea: Information Visualization](#L1-3-idea-information-visualization)
    - [Idea: CSCW](#L1-3-idea-cscw)
    - [Idea: Social Computing](#L1-3-idea-social-computing)
    - [Domain: Special Needs](#L1-3-domain-special-needs)
    - [Domain: Education](#L1-3-domain-education)
    - [Domain: Healthcare](#L1-3-domain-healthcare)
    - [Domain Security](#L1-3-domain-security)
    - [Domain: Games](#L1-3-domain-games)
    - [Reflections: Exploring HCI](#L1-3-reflections-exploring-hci)
    - [Conclusion to Exploring HCI](#L1-3-conclusion-to-exploring-hci)
  - [2.1 Introduction to Principles](#L2-1)
    - [Introduction to Design Principles](#L2-1-introduction-to-design-principles)
    - [Interfaces: Between Users and Tasks](#L2-1-interfaces-between-users-and-tasks)
    - [Quiz: Identifying a Task](#L2-1-quiz-identifying-a-task)
    - [5 Tips: Identifying a Task](#L2-1-5-tips-identifying-a-task)
    - [Usefulness and Usability](#L2-1-usefulness-and-usability)
    - [Exploring HCI: HCI Principles](#L2-1-exploring-hci-hci-principles)
    - [Views of the User: Processor](#L2-1-views-of-the-user-processor)
    - [Views of the User: Predictor](#L2-1-views-of-the-user-predictor)
    - [Views of the User: Participant](#L2-1-views-of-the-user-participant)
    - [Good Design, Bad Design](#L2-1-good-design-bad-design)
    - [Quiz: Reflections: Views of the User](#L2-1-quiz-reflections-views-of-the-user)
    - [User Experience, Sans Design](#L2-1-user-experience-sans-design)
    - [Quiz: Design Challenge: Morgan on the Street](#L2-1-quiz-design-challenge-morgan-on-the-street)
    - [Conclusion to Intro to Design](#L2-1-conclusion-to-intro-to-design)
  - [2.2 Feedback Cycles](#L2-2)
    - [Introduction to Feedback Cycles](#L2-2-introduction-to-feedback-cycles)
    - [Feedback Cycles are Fundamental](#L2-2-feedback-cycles-are-fundamental)
    - [Gulf of Execution](#L2-2-gulf-of-execution)
    - [Gulf of Execution Example](#L2-2-gulf-of-execution-example)
    - [5 Tips: Gulfs of Execution](#L2-2-5-tips-gulfs-of-execution)
    - [Gulf of Evaluation](#L2-2-gulf-of-evaluation)
    - [Gulf of Evaluation Example](#L2-2-gulf-of-evaluation-example)
    - [5 Tips: Gulfs of Evaluation](#L2-2-5-tips-gulfs-of-evaluation)
    - [Good Design, Bad Design: Feedback Cycles](#L2-2-good-design-bad-design-feedback-cycles)
    - [Quiz: Reflections: Feedback Cycles](#L2-2-quiz-reflections-feedback-cycles)
    - [Quiz: Feedback Cycles in David's Car 1](#L2-2-quiz-feedback-cycles-in-david-s-car-1)
    - [Quiz: Feedback Cycles in David's Car 2](#L2-2-quiz-feedback-cycles-in-david-s-car-2)
    - [Quiz: Feedback Cycles in David's Car 3](#L2-2-quiz-feedback-cycles-in-david-s-car-3)
    - [Seven Questions for Bridging Gulfs](#L2-2-seven-questions-for-bridging-gulfs)
    - [Exploring HCI: Feedback Cycles](#L2-2-exploring-hci-feedback-cycles)
    - [Quiz: Design Challenge: Credit Card Readers 1](#L2-2-quiz-design-challenge-credit-card-readers-1)
    - [Quiz: Design Challenge: Credit Card Readers 2](#L2-2-quiz-design-challenge-credit-card-readers-2)
    - [Quiz: Design Challenge: Credit Card Readers 3](#L2-2-quiz-design-challenge-credit-card-readers-3)
    - [Conclusion to Feedback Cycles](#L2-2-conclusion-to-feedback-cycles)
  - [2.3 Direct Manipulation](#L2-3)
    - [Introduction to Direct Manipulation and Invisible Interfaces](#L2-3-introduction-to-direct-manipulation-and-invisible-interfaces)
    - [Direct Manipulation: The Desktop Metaphor](#L2-3-direct-manipulation-the-desktop-metaphor)
    - [Direct Manipulation: The Desktop Metaphor](#L2-3-direct-manipulation-the-desktop-metaphor-2)
    - [Paper Spotlight: "Direct Manipulation Interfaces"](#L2-3-paper-spotlight-direct-manipulation-interfaces)
    - [Exploring HCI: Direct Manipulation](#L2-3-exploring-hci-direct-manipulation)
    - [Quiz: Reflections: Direct Manipulation](#L2-3-quiz-reflections-direct-manipulation)
    - [Babies and Direct Manipulation](#L2-3-babies-and-direct-manipulation)
    - [Quiz: Exercise: Direct Manipulation](#L2-3-quiz-exercise-direct-manipulation)
    - [Making Indirect Manipulation](#L2-3-making-indirect-manipulation)
    - [Exploring HCI: Direct Manipulation](#L2-3-exploring-hci-direct-manipulation-2)
    - [Invisible Interfaces](#L2-3-invisible-interfaces)
    - [Good Design, Bad Design In](#L2-3-good-design-bad-design-in)
    - [Invisibility by Learning](#L2-3-invisibility-by-learning)
    - [Invisibility by Design](#L2-3-invisibility-by-design)
    - [5 Tips: Invisible Interfaces](#L2-3-5-tips-invisible-interfaces)
    - [Quiz: Reflections: Invisibility by Design](#L2-3-quiz-reflections-invisibility-by-design)
    - [Quiz: Design Challenge: The](#L2-3-quiz-design-challenge-the)
    - [Conclusion to Direct Manipulation](#L2-3-conclusion-to-direct-manipulation)
  - [2.4 Human Abilities](#L2-4)
    - [Introduction to Human Abilities](#L2-4-introduction-to-human-abilities)
    - [Information Processing](#L2-4-information-processing)
    - [Sensation and Perception: Visual](#L2-4-sensation-and-perception-visual)
    - [Sensation and Perception: Auditory](#L2-4-sensation-and-perception-auditory)
    - [Sensation and Perception: Haptic](#L2-4-sensation-and-perception-haptic)
    - [Quiz: Design Challenge: Message Alerts](#L2-4-quiz-design-challenge-message-alerts)
    - [Quiz: Memory: Perceptual Store](#L2-4-quiz-memory-perceptual-store)
    - [Quiz: Memory: Short Term and Chunking](#L2-4-quiz-memory-short-term-and-chunking)
    - [Quiz: Memory: Short Term and Recognition](#L2-4-quiz-memory-short-term-and-recognition)
    - [Memory: Short Term Takeaways](#L2-4-memory-short-term-takeaways)
    - [Memory: Long Term Memory](#L2-4-memory-long-term-memory)
    - [Cognition: Learning](#L2-4-cognition-learning)
    - [Cognition: Cognitive Load](#L2-4-cognition-cognitive-load)
    - [Quiz: Reflections: Cognitive Load](#L2-4-quiz-reflections-cognitive-load)
    - [5 Tips: Reducing Cognitive Load](#L2-4-5-tips-reducing-cognitive-load)
    - [Motor System](#L2-4-motor-system)
    - [Exploring HCI: Human Abilities](#L2-4-exploring-hci-human-abilities)
    - [Conclusion to Human Abilities](#L2-4-conclusion-to-human-abilities)
  - [2.5 Design Principles and Heuristics](#L2-5)
    - [Introduction to Design Principles](#L2-5-introduction-to-design-principles)
    - [The Sets](#L2-5-the-sets)
    - [Discoverability](#L2-5-discoverability)
    - [Quiz: Design Challenge: Discovering Gestures](#L2-5-quiz-design-challenge-discovering-gestures)
    - [Simplicity](#L2-5-simplicity)
    - [Affordances](#L2-5-affordances)
    - [Mapping](#L2-5-mapping)
    - [Quiz: Design Challenge: Mapping and Switches](#L2-5-quiz-design-challenge-mapping-and-switches)
    - [Perceptability](#L2-5-perceptability)
    - [Consistency](#L2-5-consistency)
    - [Consistency: The Curious Case of Ctrl+Y](#L2-5-consistency-the-curious-case-of-ctrl-y)
    - [Flexibility](#L2-5-flexibility)
    - [Equity](#L2-5-equity)
    - [Ease and Comfort](#L2-5-ease-and-comfort)
    - [Structure](#L2-5-structure)
    - [Constraints](#L2-5-constraints)
    - [Norman's Four Types of Constraints](#L2-5-norman-s-four-types-of-constraints)
    - [Quiz: Reflections: Constraints](#L2-5-quiz-reflections-constraints)
    - [Tolerance](#L2-5-tolerance)
    - [Feedback](#L2-5-feedback)
    - [Documentation](#L2-5-documentation)
    - [Exploring HCI: Design Principles and Heuristics](#L2-5-exploring-hci-design-principles-and-heuristics)
    - [Other Sets of Principles](#L2-5-other-sets-of-principles)
    - [Conclusion to Design Princip](#L2-5-conclusion-to-design-princip)
  - [3.1 Introduction to Methods](#L3-1)
    - [Introduction to Research Methods](#L3-1-introduction-to-research-methods)
    - [User-Centered Design](#L3-1-user-centered-design)
    - [Principles of User-Centered Design](#L3-1-principles-of-user-centered-design)
    - [Stakeholders](#L3-1-stakeholders)
    - [Quiz: Reflections: HCI Methods](#L3-1-quiz-reflections-hci-methods)
    - [The Design Life Cycle](#L3-1-the-design-life-cycle)
    - [Methods for the Design Life Cycle](#L3-1-methods-for-the-design-life-cycle)
    - [Design Life Cycles meets Feedback Cycles](#L3-1-design-life-cycles-meets-feedback-cycles)
    - [Qualitative vs. Quantitative Data](#L3-1-qualitative-vs-quantitative-data)
    - [Quiz: Exercise: Quantitative vs Qualitative](#L3-1-quiz-exercise-quantitative-vs-qualitative)
    - [Design Challenge: Recording MOOCS](#L3-1-design-challenge-recording-moocs)
    - [Exploring HCI: HCI Methods](#L3-1-exploring-hci-hci-methods)
    - [Conclusion to Introduction to Methods](#L3-1-conclusion-to-introduction-to-methods)
  - [3.2 Ethics and Human Research](#L3-2)
    - [Introduction to Research Ethics](#L3-2-introduction-to-research-ethics)
    - [Origin of Institutional Review Board](#L3-2-origin-of-institutional-review-board)
    - [The Value of Research Ethics](#L3-2-the-value-of-research-ethics)
    - [Getting Started: CITI Training](#L3-2-getting-started-citi-training)
    - [Getting Started: IRB](#L3-2-getting-started-irb)
    - [IRB Protocols: Basics](#L3-2-irb-protocols-basics)
    - [IRB Protocols: Human Subject Interaction](#L3-2-irb-protocols-human-subject-interaction)
    - [IRB Protocols: Consent Procedures](#L3-2-irb-protocols-consent-procedures)
    - [IRB Protocols: Wrapping Up](#L3-2-irb-protocols-wrapping-up)
    - [Research Ethics and Industry](#L3-2-research-ethics-and-industry)
    - [Quiz: Exercise: Research Ethics and Industry](#L3-2-quiz-exercise-research-ethics-and-industry)
    - [Paper Spotlight: "Evolving the IRB: Building Robust Review for Industry Research"](#L3-2-paper-spotlight-evolving-the-irb-building-robust-review-for-industry-research)
    - [Conclusion to Research Ethics](#L3-2-conclusion-to-research-ethics)
  - [3.3 Needfinding and Requirements Gathering](#L3-3)
    - [Introduction to Needfinding](#L3-3-introduction-to-needfinding)
    - [Data Inventory](#L3-3-data-inventory)
    - [The Problem Space](#L3-3-the-problem-space)
    - [User Types](#L3-3-user-types)
    - [5 Tips: Avoiding Bias in Needfinding](#L3-3-5-tips-avoiding-bias-in-needfinding)
    - [Naturalistic Observation](#L3-3-naturalistic-observation)
    - [5 Tips: Naturalistic Observation](#L3-3-5-tips-naturalistic-observation)
    - [Participant Observation](#L3-3-participant-observation)
    - [Hacks and Workarounds](#L3-3-hacks-and-workarounds)
    - [Errors](#L3-3-errors)
    - [Apprenticeship and Ethnography](#L3-3-apprenticeship-and-ethnography)
    - [Interviews with Focus Groups](#L3-3-interviews-with-focus-groups)
    - [5 Tips: Interviews](#L3-3-5-tips-interviews)
    - [Quiz: Exercise: interviews](#L3-3-quiz-exercise-interviews)
    - [Think-Aloud](#L3-3-think-aloud)
    - [Surveys](#L3-3-surveys)
    - [5 Tips: Surveys](#L3-3-5-tips-surveys)
    - [Quiz: Exercise: Surveys](#L3-3-quiz-exercise-surveys)
    - [Other Data Gathering Methods](#L3-3-other-data-gathering-methods)
    - [Quiz: Exercise: Needfinding Pros and Cons](#L3-3-quiz-exercise-needfinding-pros-and-cons)
    - [Quiz: Design Challenge: Needfinding for Book Reading](#L3-3-quiz-design-challenge-needfinding-for-book-reading)
    - [Iterative Needfinding](#L3-3-iterative-needfinding)
    - [Revisiting the Inventory](#L3-3-revisiting-the-inventory)
    - [Representing the Need](#L3-3-representing-the-need)
    - [Defining the Requirements](#L3-3-defining-the-requirements)
    - [Exploring HCI: Needfinding](#L3-3-exploring-hci-needfinding)
    - [Conclusion](#L3-3-conclusion)
  - [3.4 Design Alternatives](#L3-4)
    - [Introduction to Design Alternatives](#L3-4-introduction-to-design-alternatives)
    - [The Second Biggest Mistake](#L3-4-the-second-biggest-mistake)
    - [The Design Space](#L3-4-the-design-space)
    - [Individual Brainstorming 1](#L3-4-individual-brainstorming-1)
    - [Individual Brainstorming 2](#L3-4-individual-brainstorming-2)
    - [5 Tips: Individual Brainstorming](#L3-4-5-tips-individual-brainstorming)
    - [Challenges in Group Brainstorming](#L3-4-challenges-in-group-brainstorming)
    - [Rules for Group Brainstorming](#L3-4-rules-for-group-brainstorming)
    - [5 Tips: Group Brainstorming](#L3-4-5-tips-group-brainstorming)
    - [Fleshing Out Ideas](#L3-4-fleshing-out-ideas)
    - [Personas](#L3-4-personas)
    - [User Profiles](#L3-4-user-profiles)
    - [Timeline](#L3-4-timeline)
    - [Scenarios and Storyboards](#L3-4-scenarios-and-storyboards)
    - [User Modeling](#L3-4-user-modeling)
    - [Quiz: Exercise: Design Alternatives](#L3-4-quiz-exercise-design-alternatives)
    - [Exploring Ideas](#L3-4-exploring-ideas)
    - [Exploring HCI: Design Alternatives](#L3-4-exploring-hci-design-alternatives)
    - [Conclusion to Design Alternatives](#L3-4-conclusion-to-design-alternatives)
  - [3.5 Prototyping](#L3-5)
    - [Introduction to Prototyping](#L3-5-introduction-to-prototyping)
    - [Basics of Prototyping](#L3-5-basics-of-prototyping)
    - [Tradeoffs of Prototyping](#L3-5-tradeoffs-of-prototyping)
    - [5 Tips: Prototyping](#L3-5-5-tips-prototyping)
    - [Verbal Prototypes](#L3-5-verbal-prototypes)
    - [Paper Prototyping](#L3-5-paper-prototyping)
    - [Wizard of Oz](#L3-5-wizard-of-oz)
    - [Wireframing](#L3-5-wireframing)
    - [Physical Prototypes](#L3-5-physical-prototypes)
    - [Quiz: Exercise: Prototyping Pros and Cons](#L3-5-quiz-exercise-prototyping-pros-and-cons)
    - [Design Life Cycle Revisited](#L3-5-design-life-cycle-revisited)
    - [Multi-Level Prototyping](#L3-5-multi-level-prototyping)
    - [Exploring HCI: Prototyping](#L3-5-exploring-hci-prototyping)
    - [Conclusion to Prototyping](#L3-5-conclusion-to-prototyping)
- [Part C — Keyword Index](#partC)

---

<a id="partA"></a>

# Part A — Lesson Summaries & Key Points

One block per lesson: what the lesson is about → every key point, with the lecture's numbered lists broken out as numbered items → keywords → links to the full lecture text in Part B.

| Lesson | About | Full text |
|---|---|---|
| [1.1 Introduction to HCI](#A-L1-1) | Defines HCI as humans + computers + interaction, argues the goal is an interface that disappears so the user focuses on the task, and positions HCI relative to human factors, UI design, UX design and psychology. | [Full text](#L1-1) |
| [1.2 Introduction to CS6750](#A-L1-2) | Overview of the course: three learning goals, the single learning outcome (design effective interactions between humans and computers) unpacked word by word, learning strategies, assessments, structure and five tips for doing well. | [Full text](#L1-2) |
| [1.3 Exploring HCI](#A-L1-3) | A tour of HCI application areas grouped into Technologies (VR, AR, UbiComp & wearables, robotics, mobile), Ideas (context-sensitive computing, gesture, pen/touch, information visualisation, CSCW, social computing) and Domains (special needs, education, healthcare, security, games). | [Full text](#L1-3) |
| [2.1 Introduction to Principles](#A-L2-1) | Sets up the principles unit: interfaces mediate between users and tasks (focus on the task, not the interface), usefulness vs usability, three views of the user (processor, predictor, participant) and user experience at individual, group and societal levels. | [Full text](#L2-1) |
| [2.2 Feedback Cycles](#A-L2-2) | Feedback cycles as the most fundamental HCI concept: the Gulf of Execution (how do I know what I can do?), the Gulf of Evaluation (how do I know what happened?), tips for bridging each, Norman's Seven Questions, and worked examples (microwave, thermostat, David's car, credit-card readers). | [Full text](#L2-2) |
| [2.3 Direct Manipulation](#A-L2-3) | Two applications of good feedback cycles: direct manipulation (feel like you're directly controlling the object of the task — distance + direct engagement, per Hutchins, Hollan & Norman 1985) and invisible interfaces (invisible by learning vs invisible by design). | [Full text](#L2-3) |
| [2.4 Human Abilities](#A-L2-4) | Crash course in the psychology of the human as input–processing–output system: visual/auditory/haptic perception, three kinds of memory (perceptual store, short-term, long-term), learning (procedural vs declarative), cognitive load and the motor system. | [Full text](#L2-4) |
| [2.5 Design Principles and Heuristics](#A-L2-5) | Merges four famous sets of design guidelines — Norman's six principles, Nielsen's ten heuristics, Constantine & Lockwood's six principles, and the seven Principles of Universal Design — into Joyner's 15 principles: discoverability, simplicity, affordances, mapping, perceptibility, consistency, flexibility, equity, ease, comfort, structure, constraints, tolerance, feedback, documentation. | [Full text](#L2-5) |
| [3.1 Introduction to Methods](#A-L3-1) | Opens the methods unit: user-centered design and its six ISO principles, primary/secondary/tertiary stakeholders, the four-phase design life cycle (needfinding → design alternatives → prototyping → evaluation), its relationship to feedback cycles, and qualitative vs quantitative data. | [Full text](#L3-1) |
| [3.2 Ethics and Human Research](#A-L3-2) | Research ethics for human-subjects work: the history behind Institutional Review Boards (Milgram, Tuskegee, Stanford prison, National Research Act 1974, Belmont Report), why ethics also improves data quality, the Georgia Tech CITI/IRB protocol process step by step, and ethics in industry (Facebook emotional-contagion study, Jackman & Kanerva). | [Full text](#L3-2) |
| [3.3 Needfinding and Requirements Gathering](#A-L3-3) | First stage of the design life cycle: the data inventory (seven questions), problem space and user types, five biases to avoid, needfinding methods from low to high intervention (naturalistic observation, participant observation, hacks & workarounds, errors, apprenticeship/ethnography, interviews & focus groups, think-aloud, surveys, existing interfaces/reviews/logs), then representing the need and defining requirements. | [Full text](#L3-3) |
| [3.4 Design Alternatives](#A-L3-4) | Second stage of the design life cycle: generate lots of ideas (individual brainstorming first, then group brainstorming with rules), then flesh them out and narrow to 3–4 alternatives using personas, user profiles, timelines, scenarios/storyboards and user modeling. | [Full text](#L3-4) |
| [3.5 Prototyping](#A-L3-5) | Third stage of the design life cycle: build things to put in front of users, from low to high fidelity — concepts (representation, fidelity, evaluation, scope), tradeoffs, five tips, and methods (verbal, paper/card, Wizard of Oz, wireframes, physical), plus how prototyping fits the iterative cycle at multiple levels. | [Full text](#L3-5) |

<a id="A-L1-1"></a>

## Summary — Lesson 1.1 Introduction to HCI

**Full lecture text:** [1.1 Introduction to HCI](#L1-1) · **Lecture book pages:** pp. 1–24

**In one sentence:** Defines HCI as humans + computers + interaction, argues the goal is an interface that disappears so the user focuses on the task, and positions HCI relative to human factors, UI design, UX design and psychology.

### Key points

- [Humans](#L1-1-humans) — Morgan is the running example of a human. Humans bring:
  - Senses: seeing, hearing, feeling (smelling and tasting exist but are dealt with less).
  - More than senses: memories, experiences, skills, knowledge.
  - HCI must consider every element of the human, from perception to their long history with technology.
- [Computers](#L1-1-computers) — a “computer” is not just a desktop: phones, watches, cars, etc. Augmented-reality games like Pokémon Go (released days before recording) turn effectively the entire world into an instance of HCI.
- [Interaction](#L1-1-interaction) — two ways to view it:
  - Obvious view: human interacts with computer, computer responds; back and forth.
  - More interesting view: the human interacts with the **task** *through* the computer; the computer mediates. Or: human and computer together interact with the task.
  - Goal: make the interface as **invisible** as possible so the user spends as little time as possible thinking about the interface and as much as possible on the task. Realistically interfaces stay somewhat visible.
- [Quiz: Reflections: Interacting & Interfaces](#L1-1-quiz-reflections-interacting-interfaces) — Invisible example: video games (player feels inside the game world; intuitive controls like forward = move forward, plus learning over time). Visible example: two remote controls (TV + cable box) for what feels like one task (watching TV) — you think about which remote, not the task.
- [The HCI Space](#L1-1-the-hci-space) — HCI is ubiquitous, which is exciting but dangerous:
  - Because we all interact with computers we think we are HCI experts. We may be experts at *using* computers, not at *designing* interactions for other people (like athletes/scientists who can't necessarily teach others).
  - Red dot vs black circle diagram: what you know (red dot) grows after studying HCI, but your perception of what there is to know (black circle) grows even more — you may leave the class *less* confident than when you started. “You're taking the first step into a larger world.”
- [HCI in the Big Picture](#L1-1-hci-in-the-big-picture) — Many schools offer whole HCI degrees. Hierarchy used in this course: HCI is a subset of **human factors engineering**; sub-disciplines within HCI include UI design and UX design (Joyner's arrangement — some would put UI under UX, or UX level with HCI). Sub-fields use many of the same principles, applied to narrower domains, sometimes with their own extra principles/methods.
- [HCI vs Human Factors](#L1-1-hci-vs-human-factors):
  - Human factors = designing interactions between people and products, systems or devices — including non-computing parts (electric-car example: HCI cares about dashboard data visualisation and radio control; human factors also cares about steering-wheel height, mirror size, seat position — the entire environment).
  - Many HCI principles come from human factors applied narrowly to computerised systems.
  - The gap is shrinking as computers become ubiquitous: 20 years ago a car wasn't HCI; 10 years ago a wristwatch was industrial design; now showerheads and fridges are computerised. Tesla Model S console is a giant computer. “Cars have become computers on wheels. Watches have become computers on wristbands. Car keys have become computers on keychains.”
- [HCI vs User Interface Design](#L1-1-hci-vs-user-interface-design):
  - For many years HCI was largely UI design: earliest innovations were the light pen and the first mouse — focus squarely on the screen.
  - UI design produced principles for screens: grids (borrowed from magazine/print industries) to guide the eye; laws governing how hard it is to select things on screen (e.g. Mac menus always at top vs PC menus grouped with each window); techniques for adapting to screen sizes; rapid prototyping with pen-and-paper or wireframes.
  - UI design became its own well-defined field; many HCI concepts originated there. HCI goes beyond interaction with a single screen — general methods that apply to any interface.
- [HCI vs User Experience Design](#L1-1-hci-vs-user-experience-design):
  - Ask a dozen people, get a dozen answers. Course definition: HCI is about **understanding** interactions between humans and computers; UX design is about **dictating** them.
  - To design UX well you must understand the user, so Joyner treats UX design as a subfield of HCI.
  - Relationship is deeply symbiotic: understanding informs designs; evaluating designs informs understanding (good design = evidence understanding is correct; failed design = maybe understanding flawed). Similar to **design-based research** (covered later). Related to feedback cycles — the user acts/evaluates; we design/evaluate.
- [HCI vs Psychology](#L1-1-hci-vs-psychology):
  - Human factors engineering is in many ways the merger of engineering and psychology (plus design and cognitive science). In HCI the engineering side is software engineering; the psychology connection remains and is symbiotic.
  - At Georgia Tech the HCI class is cross-listed as Computer Science and Psychology.
  - Example: in 1992 psychologists at Apple studied how people organise the rapid flow of information in workspaces; observed people form **piles** of related material (an informal filing system); designed an interface that mimicked piles; then used the results to reflect on how people manage workspaces — better understanding of users' thinking AND a useful interface.
- [HCI: Research and Design](#L1-1-hci-research-and-design) — what HCI is:
  - Research: researching the user, understanding needs, evaluating interactions with prototypes.
  - Design: the prototyping phase, using known principles such as **distributed cognition**, good **mental models**, **universal design** (all covered later).
  - Not isolated: results of user research inform designs; results of designs inform ongoing research. This cycle is “the heart of what HCI is” and appears wherever humans use computers for tasks: desk and screen, smartphone/smartwatch, touch/gesture, VR/AR.
- [Welcome to HCI!](#L1-1-welcome-to-hci) — Course will cover: fundamental design principles; user research (for new interfaces or exploring cognition); the relationship between research and design; applications across domains (AR to healthcare). The course itself is meant to be an example of HCI.

**Keywords to search for:** Morgan · invisible interface · task vs interface · two remote controls · red dot / black circle · human factors engineering · UI design · UX design · light pen · grids · Mac vs PC menus · design-based research · psychology cross-listed · Apple 1992 piles · research informs design · distributed cognition · mental models · universal design · Pokémon Go · Tesla Model S

**Jump to a section of the full text:** [Humans](#L1-1-humans) · [Computers](#L1-1-computers) · [Interaction](#L1-1-interaction) · [Quiz: Reflections: Interacting & Interfaces](#L1-1-quiz-reflections-interacting-interfaces) · [The HCI Space](#L1-1-the-hci-space) · [HCI in the Big Picture](#L1-1-hci-in-the-big-picture) · [HCI vs Human Factors](#L1-1-hci-vs-human-factors) · [HCI vs User Interface Design](#L1-1-hci-vs-user-interface-design) · [HCI vs User Experience Design](#L1-1-hci-vs-user-experience-design) · [HCI vs Psychology](#L1-1-hci-vs-psychology) · [HCI: Research and Design](#L1-1-hci-research-and-design) · [Welcome to HCI!](#L1-1-welcome-to-hci)

---

<a id="A-L1-2"></a>

## Summary — Lesson 1.2 Introduction to CS6750

**Full lecture text:** [1.2 Introduction to CS6750](#L1-2) · **Lecture book pages:** pp. 25–45

**In one sentence:** Overview of the course: three learning goals, the single learning outcome (design effective interactions between humans and computers) unpacked word by word, learning strategies, assessments, structure and five tips for doing well.

### Key points

- [Introduction to CS6750](#L1-2-introduction-to-cs6750) — High-level overview of the class; assessments apply only to Georgia Tech students and change semester to semester, so follow the materials for your own semester.
- [Learning Goals](#L1-2-learning-goals) — a learning goal = something we want you to **understand**. Three goals:
  1. Understand common HCI **principles** — the tried-and-true rules for designing good interactions.
  2. Understand the **design life cycle** — how interfaces go from conception to prototypes to evaluation, especially the role of **iteration**.
  3. Understand the expanse of the HCI field and current **applications** (healthcare, virtual reality, emerging techniques like sonification).
- [Learning Outcomes: To Design](#L1-2-learning-outcomes-to-design) — a learning outcome = something we want you to be able to **do**. The one outcome: **design effective interactions between humans and computers**. “Design” takes two forms:
  - Design as an **activity**: applying known principles to a new problem (e.g. giving users the right feedback at the right time).
  - Design as a **process**: gather information → develop design alternatives → evaluate with users → revise.
  - Thermostat example: both apply (feedback/error tolerance principles AND creating ideas, user feedback, revision). Applying known principles alone doesn't guarantee a good design; ignoring decades of experience is also wrong. These two sides are the vast majority of the course: principles from human factors/HCI research, and methods (gathering requirements, developing designs, evaluating).
- [Learning Outcomes: Effectiveness](#L1-2-learning-outcomes-effectiveness) — effectiveness is defined by the **goal**:
  - Usual goal: **usability** (user creates the outcome they want as easily as possible).
  - Alternative goal: **research** (e.g. deliberately make thermostats harder to read to study what makes people think it works).
  - Alternative goal: **change the activity** (e.g. reduce a home's carbon footprint: show comparison to neighbours' usage, let users set energy goals, or make the thermostat physically harder to turn).
  - Course assumes usability unless stated otherwise.
- [Learning Outcomes: Between Humans and Computers](#L1-2-learning-outcomes-between-humans-and-computers) — Emphasis on **interactions**, not “interfaces”: we design tasks and how people accomplish goals. Thermostat: goal is not “design a thermostat” but “design the way a person controls the temperature in their home” — that shift leads to **Nest** (learns from the user and controls temperature automatically) rather than just an easier-to-read wall device.
- [Learning Strategies: Video Material](#L1-2-learning-strategies-video-material) — strategies used in the videos:
  - Learning by **example** (running examples recur throughout).
  - Learning by **doing** (design exercises — not required, can't be verified, but do them).
  - Learning by **reflection** (reflect on your own everyday encounters).
  - Danger: “you are not your own user” — focusing on your own experiences gives a false sense of expertise; strategies will push you out of your comfort zone.
- [Learning Strategies: Georgia Tech](#L1-2-learning-strategies-georgia-tech) — additional strategies in the full course:
  - Leveraging the student community: **peer learning**, **collaborative learning**, **learning by teaching**, **communities of practice** — you play student, teacher and partner.
  - **Project-based learning**: form a team early, pick a provided problem or your own, explore principles and methods through it; could become a real product or research project.
- [Learning Assessments](#L1-2-learning-assessments) — assessments evaluate whether you can do/understand the outcome/goals:
  - Primary assessments = design effective interactions between humans and computers.
  - Start small (recommend improvements to existing interfaces; small design challenges) → scope up to a bigger challenge: investigate individually, then merge into teams to prototype and evaluate a full solution.
  - Evaluated not just on the final design but on the **process** by which it was generated.
- [Course Structure](#L1-2-course-structure) — Lessons are as independent as possible (you can skip around) but the planned order: core **design principles** → **research methodologies** / iterative design life cycle → peek at the HCI community at large. (Design informs research, research informs design.)
- [5 Tips Doing Well in CS6750](#L1-2-5-tips-doing-well-in-cs6750):
  1. **Look over the assignments early** — some take an hour, others need advance coordination (talking to users, developing prototypes, testing with real people); at least read all the descriptions.
  2. **Start the assignments early** — you use interfaces every day, so starting early lets everyday inspiration make writing far easier than inventing something on the spot.
  3. **Participate** — interact with classmates, post on and read the forums; that knowledge is as valuable as the videos.
  4. **Select an application area to explore** — next lesson previews areas; pick one and mentally revisit it throughout the course.
  5. **Leave behind what you know** (or at least try) — being good at using computers doesn't make you good at designing experiences; HCI is about gaining a grounded understanding of user needs, not assuming them; be cautious about designing narrowly from your own experience.
- [Conclusion](#L1-2-conclusion) — Video material covers three areas: **principles**, **methods**, **applications**. Applications are previewed next, then revisited after principles and methods.

**Keywords to search for:** learning goal vs learning outcome · design as activity · design as process · effectiveness = goal · usability / research / change the activity · carbon footprint thermostat · Nest · interactions not interfaces · learning by example / doing / reflection · you are not your own user · peer learning · project-based learning · evaluated on process · 5 tips · principles / methods / applications

**Jump to a section of the full text:** [Introduction to CS6750](#L1-2-introduction-to-cs6750) · [Learning Goals](#L1-2-learning-goals) · [Learning Outcomes: To Design](#L1-2-learning-outcomes-to-design) · [Learning Outcomes: Effectiveness](#L1-2-learning-outcomes-effectiveness) · [Learning Outcomes: Between Humans and Computers](#L1-2-learning-outcomes-between-humans-and-computers) · [Learning Strategies: Video Material](#L1-2-learning-strategies-video-material) · [Learning Strategies: Georgia Tech](#L1-2-learning-strategies-georgia-tech) · [Learning Assessments](#L1-2-learning-assessments) · [Course Structure](#L1-2-course-structure) · [5 Tips Doing Well in CS6750](#L1-2-5-tips-doing-well-in-cs6750) · [Conclusion](#L1-2-conclusion)

---

<a id="A-L1-3"></a>

## Summary — Lesson 1.3 Exploring HCI

**Full lecture text:** [1.3 Exploring HCI](#L1-3) · **Lecture book pages:** pp. 46–73

**In one sentence:** A tour of HCI application areas grouped into Technologies (VR, AR, UbiComp & wearables, robotics, mobile), Ideas (context-sensitive computing, gesture, pen/touch, information visualisation, CSCW, social computing) and Domains (special needs, education, healthcare, security, games).

### Key points

- [Introduction to Exploring HCI](#L1-3-introduction-to-exploring-hci) — three (admittedly artificial, overlapping) categories:
  - **Technologies**: emerging technological capabilities enabling new interactions.
  - **Domains**: pre-existing areas that could be disrupted by computer interfaces (healthcare, education).
  - **Ideas**: theories about how people interact with interfaces and the world; span both of the others (e.g. AR enables context-sensitive computing).
  - Pick one area and keep it in mind; the course asks you to reflect on it throughout.
- [Technology: Virtual Reality](#L1-3-technology-virtual-reality) — Recording year described as the year VR hits the mainstream. VR = entirely new classification of interaction and visualisation; open problems: motion sickness, feedback on gestural interactions. Beyond games: tourism, commerce, art, education; a Michigan lab uses VR to treat phobias (safe but realistic confrontation of fears).
- [Technology: Augmented Reality](#L1-3-technology-augmented-reality) — VR **replaces** real-world visual/auditory (sometimes olfactory/kinesthetic) stimuli; AR **complements** what you see and hear (e.g. Google-Glass-like headset overlaying the driving route on your visual field). Possibilities: auto-translation of text/speech, restaurant reviews as you walk, museum/park tours tailored to a student's interests. Relies on cameras everywhere → societal problems; revisited in “interfaces and politics” (unit two).
- [Technology: UbiComp and Wearables](#L1-3-technology-ubicomp-and-wearables) — Ubiquitous (pervasive) computing = embedding computing in more and more everyday objects; related to the Internet of Things. Cheaper microprocessors + interconnection → computers in fridges, wristwatches. Modern HCI: computer use while driving or running; smart devices offload cognitive load (fridge tracks contents, advises at the right time). Wearables: exercise monitors (most common), smart watches, Google Glass, AR headsets, advanced hearing aids, robotic prosthetics — pushes HCI into human factors and industrial design territory.
- [Technology: Robotics](#L1-3-technology-robotics) — Human-Robot Interaction (HRI) is an emerging HCI subfield; first HRI conference 2006, Salt Lake City. Questions:
  - Big (HCI + AI + philosophy): ensuring robots don't harm humans through faulty reasoning; integrating robots into social lives (or not); loss of demand for human work.
  - Concrete: natural interaction via voice and touch; subtle feedback that input is received and understood; supporting humans teaching robots instead of programming them; robots that teach humans. Already applied in healthcare and disability services.
- [Technology: Mobile](#L1-3-technology-mobile) — Mobile-first world. Challenges: far less screen real estate, less precise input, distracted user. Opportunities: a computer with most people at all times (navigation, star-gazing); related to context-aware computing, ubiquitous computing, AR (mobile has the hardware). Open challenge: phones aren't yet true replacements for desktops/laptops — people don't write essays or program on them. Why not? What's needed?
- [Idea: Context-Sensitive Comp](#L1-3-idea-context-sensitive-comp) — “What time is it?” / “You can go ahead and go to lunch.” — nonsensical without context; humans rely on context constantly (some lessons suggest we can't interact without it). Context-sensitive computing gives computers that contextual knowledge: e.g. phone detects you're in the car and automatically brings up Google Maps and Audible. Services emerging; huge research space, especially with wearables, AR, ubicomp.
- [Idea: Gesture-Based Interaction](#L1-3-idea-gesture-based-interaction) — Joyner is on camera ~half the course partly to express himself through gestures. Gesture-based interaction: Microsoft Kinect (healthcare to gaming), wristbands reacting to hand motions. Fingers have some of the finest muscle movements → systems based on finger movement could support an incredible number of interactions; possibly typing invisibly in the air via wrist-muscle recognition — might finally let mobile replace traditional computers.
- [Idea: Pen- and Touch-Based Interaction](#L1-3-idea-pen-and-touch-based-interaction) — Technology coming full circle: we interacted directly with things we built, then computers required interfaces, now computers capture natural interaction again. Touch shortens the distance between user and task (first-time mouse user looks back and forth between mouse and screen; touch is like the real world). Touch lacks precision → pen-based interaction (pen on touchscreen, like pen on paper; Udacity courses record someone writing on screen). Tablet interaction used in art and music; most web comics drawn this way.
- [Idea: Information Visualization](#L1-3-idea-information-visualization) — Data science/ML draw conclusions, but they're useful only if communicated to ordinary people. A napkin drawing printed in a newspaper involves no computer, yet computers allow complex, animated, interactive re-representation. Key fit with HCI: a good interface matches the user's **mental model** to the reality of the task; a good visualisation matches the reader's mental model of the phenomenon to reality. A visualisation is just a representation of data, so the same representation principles apply.
- [Idea: CSCW](#L1-3-idea-cscw) — Computer-Supported Cooperative Work: using computers to support people working together. Community breaks it down by two dimensions, **time** and **place**:
  - Different time, different place: this course (watched long after recording, far from the studio).
  - Same time, different place: workplace chat like Slack and HipChat (mimic the real-time office).
  - Different time, same place: a museum kiosk where visitors enter where they come from to build a map.
  - Same time, same place: Amanda running the camera, Ben the teleprompter, David presenting — computers support co-located simultaneous cooperation.
  - So CSCW mediates cooperation across geographic/temporal borders but also helps co-located, simultaneous cooperation.
- [Idea: Social Computing](#L1-3-idea-social-computing) — How computers affect how we interact and socialise. Example: recreating social norms computationally — emojis/emoticons as virtual recreations of tacit face-to-face cues (same text takes different meanings with different emoticons). Scope: online gaming, Wikipedia, social media, dating websites — everywhere computing meets our social lives.
- [Domain: Special Needs](#L1-3-domain-special-needs) — Computing can compensate for disabilities, injuries, aging. Robotic prosthetic = engineering + neuroscience + HCI (how the person intends to use the limb) + robotics. Georgia Tech's Bruce Walker: how to communicate data to a blind person — visualisation excludes them, so his **sonification** lab communicates data with sound. Imagine VR for people with paralysis, or AI + context-aware computing for an autonomous wheelchair: small population, indescribable impact.
- [Domain: Education](#L1-3-domain-education) — Joyner also teaches Educational Technology at Georgia Tech (~1 year at recording). Much of ed-tech design is straightforward HCI, with a twist: you might **not** always want things as easy as possible — introduce **desirable difficulties**. But cognitive load must come from the **material**, not from figuring out the interface; the worst thing is raising cognitive load because students are thinking about your interface. Many noble ed-tech efforts failed due to poor HCI.
- [Domain: Healthcare](#L1-3-domain-healthcare) — Much current effort is processing massive recorded data, but data must connect to real people: tools for doctors to visually evaluate/compare diagnoses; tools for patients to monitor their health and treatment options; visualisation so patients see how decisions affect well-being; context-aware computing detecting when a patient is about to do something they shouldn't. Personal health apps: Fitbit (exercise), MyFitnessPal (diet) — succeed if easily usable, ideally almost invisible. Most fascinating: VR for exercise programmes and for therapy (confront fears safely but authentically).
- [Domain Security](#L1-3-domain-security) — Network-security classes focus on algorithms/encryption, but the most secure strategy is weakened if people refuse to use it; people have little patience for security that gets in the way. **For security to be useful it has to be usable.** HCI helps by (1) making actions easier: CAPTCHAs moved from recognising letters in complex images to a simple checkbox (system recognises human-like mouse movements); (2) visualising/communicating the need: explain the rationale behind password-complexity rules so they don't seem arbitrary; a password form that gamifies selection by ranking you against others on how hard your password is to guess.
- [Domain: Games](#L1-3-domain-games) — Video games are one of the purest examples of HCI; topics are very salient: logical **mapping** between actions and effects (controller actions should feel like acting in the game world); near-constant **feedback cycles** (act, evaluate, adjust). Many game-review criticisms are actually bad-HCI criticisms: controls tough to use, hard to tell what happened, penalty for failure too low or too high. Tight task–interface connection means task frustrations quickly reveal interface problems.
- [Reflections: Exploring HCI](#L1-3-reflections-exploring-hci) / [Conclusion to Exploring HCI](#L1-3-conclusion-to-exploring-hci) — Pick an area (listed or your own), read about it, keep it in mind; unit four provides extra readings on many topics (feel free to jump ahead). But first: fundamental principles and methods.

**Keywords to search for:** technologies / domains / ideas · virtual reality · phobias · augmented reality · Google Glass · UbiComp · pervasive computing · Internet of Things · wearables · human-robot interaction · 2006 Salt Lake City · mobile-first · context-sensitive computing · gesture-based interaction · Kinect · pen and touch · information visualization · mental model · CSCW · time and place · Slack / HipChat · social computing · emojis · special needs · Bruce Walker · sonification · desirable difficulties · cognitive load · Fitbit · MyFitnessPal · usable security · CAPTCHA · games · mapping · feedback cycles

**Jump to a section of the full text:** [Introduction to Exploring HCI](#L1-3-introduction-to-exploring-hci) · [Technology: Virtual Reality](#L1-3-technology-virtual-reality) · [Technology: Augmented Reality](#L1-3-technology-augmented-reality) · [Technology: UbiComp and Wearables](#L1-3-technology-ubicomp-and-wearables) · [Technology: Robotics](#L1-3-technology-robotics) · [Technology: Mobile](#L1-3-technology-mobile) · [Idea: Context-Sensitive Comp](#L1-3-idea-context-sensitive-comp) · [Idea: Gesture-Based Interaction](#L1-3-idea-gesture-based-interaction) · [Idea: Pen- and Touch-Based Interaction](#L1-3-idea-pen-and-touch-based-interaction) · [Idea: Information Visualization](#L1-3-idea-information-visualization) · [Idea: CSCW](#L1-3-idea-cscw) · [Idea: Social Computing](#L1-3-idea-social-computing) · [Domain: Special Needs](#L1-3-domain-special-needs) · [Domain: Education](#L1-3-domain-education) · [Domain: Healthcare](#L1-3-domain-healthcare) · [Domain Security](#L1-3-domain-security) · [Domain: Games](#L1-3-domain-games) · [Reflections: Exploring HCI](#L1-3-reflections-exploring-hci) · [Conclusion to Exploring HCI](#L1-3-conclusion-to-exploring-hci)

---

<a id="A-L2-1"></a>

## Summary — Lesson 2.1 Introduction to Principles

**Full lecture text:** [2.1 Introduction to Principles](#L2-1) · **Lecture book pages:** pp. 74–97

**In one sentence:** Sets up the principles unit: interfaces mediate between users and tasks (focus on the task, not the interface), usefulness vs usability, three views of the user (processor, predictor, participant) and user experience at individual, group and societal levels.

### Key points

- [Introduction to Design Principles](#L2-1-introduction-to-design-principles) — this lesson covers:
  - Focusing on users and tasks, not tools and interfaces on their own.
  - The role of the interface mediating between user and task.
  - Different views on the user's role in the system.
  - User experience more generally, at several levels.
- [Interfaces: Between Users and Tasks](#L2-1-interfaces-between-users-and-tasks) — Users use interfaces to accomplish tasks (true of pencils and steering wheels too; HCI focuses on computational interfaces). Focus on the interaction between user and task through the interface, not just user-and-interface. Novice mistake: jumping to the interface without understanding the task. Thermostat: interface focus → button placement, screen layout, readability (important but limited); task focus (“controlling the temperature in an area”) → **Nest** (learns from the user, acts autonomously) — revolutionary rather than iterative.
- [Quiz: Identifying a Task](#L2-1-quiz-identifying-a-task) — Clip of Morgan swiping a credit card. “Swiping her credit card” is too narrow — that's how she accomplishes the task. Better: completing a purchase / purchasing an item / exchanging goods — emphasising the real task lets us think more generally about improving the interface.
- [5 Tips: Identifying a Task](#L2-1-5-tips-identifying-a-task):
  1. **Watch real users** — don't just speculate or brainstorm; watch real users performing in the area.
  2. **Talk to them** — recruit participants to perform the task and talk through it; find out what they're thinking, their goals, their motives.
  3. **Start small** — look at the individual little interactions / smallest operators; if you assume you already understand the task you'll interpret everything in terms of what you believe.
  4. **Abstract up** — from small observations, abstract to the task; keep asking *why* until you get beyond the scope of your design (Morgan: swiping a card → why? make a purchase → why? acquire goods → why? repair her car — the task you want is somewhere in that sequence).
  5. **You are not your user** — even if you perform the task yourself, you design for everyone who performs it; leave behind your own experience and preconceptions.
  6. (These tips recur heavily in the methods unit — HCI research methods are largely about understanding users, motivations and tasks.)
- [Usefulness and Usability](#L2-1-usefulness-and-usability) — Goal: interfaces that are both **useful** (lets the user achieve a task — a low bar) and **usable**. A paper map is useful but not very usable (track where you are, plot the route, all while driving; pre-GPS people wrote turns down beforehand). Usability is the big concern → navigation apps. Designing “a better map” would not have produced a navigation app; understanding the task of navigation let us offload much of the cognitive load onto the interface, closing the loop between user and task.
- [Exploring HCI: HCI Principles](#L2-1-exploring-hci-hci-principles) — Pull together your chosen area: how it applies to the models of the human's role, the design guidelines, and society/culture. Bottom-up (low-level interactions → high-level effects) or top-down (desired outcome → individual operations)? No right answer; reflect on your reasoning process.
- [Views of the User: Processor](#L2-1-views-of-the-user-processor) — three roles the human can play: **processor, predictor, participant**. Processor view:
  - Human = sensory processor: input in, output out; like another computer whose inside we can't see.
  - Design concern: the interface must fit within known human limits (what humans can sense, store in memory, physically do).
  - Usability = physically usable (see all colours, touch all buttons).
  - Evaluation: **quantitative experiments** — numeric measurements (task completion time, reaction time).
  - Not the view generally taken for good design; time is divided between the other two.
- [Views of the User: Predictor](#L2-1-views-of-the-user-predictor):
  - Care about the human's knowledge, experience, expectations, thought process; they should be able to **predict** what will happen as a result of an action — map input to output; requires getting inside their head.
  - Interface must fit with what humans know; help them learn what they don't know and efficiently leverage what they do.
  - Evaluation: **qualitative studies**, often **ex situ**; e.g. **task analyses** (where users spend time) and **cognitive walkthroughs** (thought process through a task).
  - Still focuses on one user and one task.
- [Views of the User: Participant](#L2-1-views-of-the-user-participant):
  - User as participant in an environment: what else is going on — other tasks/interfaces, other people, what competes for attention, available cognitive resources, importance of the task relative to everything else.
  - Interface must fit with the **context**; not enough to be physically usable and known — it must be usable in the context where it's needed.
  - Evaluation: **in situ** studies — in the real world, real context (GPS app: real drivers on real roads, not the lab).
- [Good Design, Bad Design](#L2-1-good-design-bad-design) — Good: a GPS that warns you 20 seconds before a turn (“In 1,000 feet, turn left”). Bad: a GPS that warns 2 seconds before (“Turn left now, hurry”). Processor view → one second is enough (reaction time < 1 s); predictor view → user needs time to slow down and turn; participant view → 50 mph, screaming toddler, merging driver on a phone, another eating a cheeseburger → several reminders and plenty of time.
- [Quiz: Reflections: Views of the User](#L2-1-quiz-reflections-views-of-the-user) — Joyner's examples:
  - Processor (for worse): Udacity's contract-hours tracker expects you to enter hours per type of work — assumes something like the processor model; a computer can track process time, a human switching tasks five times a minute can't.
  - Predictor: the Udacity classroom around the video (lesson content organisation, progress meter, transcript) equips you to predict what's coming; offloads cognitive load so you focus on the material.
  - Participant: the “Sleep” alarm-clock app — monitors sleep cycles, rings at the optimal time, tracks patterns, makes recommendations; understands its role in a broader system.
- [User Experience, Sans Design](#L2-1-user-experience-sans-design):
  - UX design = attempting to create systems that dictate how the user experiences them (preferably positively). But user experience exists whether designed or not — “like the weather, there's never no weather, there's never no user experience”; it emerges from human–task interaction via the interface.
  - UX goes beyond the interaction: emotional, personal, experiential elements. **Individual** level: age, sex, race, personal experiences, gender, expectations; whether the person feels the interface was designed for them; frustration vs joy.
  - **Group** level: e.g. school reunions seem less important to people who graduated in the last 15 years — hypothesis: Facebook and email keep people in touch, changing the group UX.
  - **Societal** level: sometimes unintended (Twitter's creators didn't foresee its role in the Arab Spring); sometimes intentional (Facebook adding relationship statuses like civil unions — reflected a societal change and participated in normalising it), which feeds back to the individual feeling represented.
- [Quiz: Design Challenge: Morgan on the Street](#L2-1-quiz-design-challenge-morgan-on-the-street) — Morgan walks to work, listens to (mostly non-fiction) audiobooks, wants to take notes, leave bookmarks, everything you do when reading. Designing for her:
  - As processor: what information is communicated, when and how.
  - As predictor: how the interface meshes with her needs — ease of access, ease of commands.
  - As participant: broader interactions with her other tasks and social activities; how increased access to books changes her life.
  - Too big to answer quickly → becomes a running dialogue through the course (also UX at individual, friends-group and societal levels).
- [Conclusion to Intro to Design](#L2-1-conclusion-to-intro-to-design) — covered:
  - Interfaces mediate between users and tasks; best interfaces let users think about the task as much as possible.
  - Usability: efficiency and user satisfaction.
  - Three views of the user and how they change the definition of usability and evaluation.
  - UX at user, group and societal levels.

**Keywords to search for:** user / task / interface · Nest · swiping a credit card · 5 tips identifying a task · abstract up / why · you are not your user · useful vs usable · map vs navigation app · processor · predictor · participant · quantitative experiments · qualitative studies · ex situ · in situ · task analysis · cognitive walkthrough · GPS 20 seconds vs 2 seconds · Sleep app · user experience like the weather · individual / group / societal · Arab Spring · civil unions · Morgan on the street

**Jump to a section of the full text:** [Introduction to Design Principles](#L2-1-introduction-to-design-principles) · [Interfaces: Between Users and Tasks](#L2-1-interfaces-between-users-and-tasks) · [Quiz: Identifying a Task](#L2-1-quiz-identifying-a-task) · [5 Tips: Identifying a Task](#L2-1-5-tips-identifying-a-task) · [Usefulness and Usability](#L2-1-usefulness-and-usability) · [Exploring HCI: HCI Principles](#L2-1-exploring-hci-hci-principles) · [Views of the User: Processor](#L2-1-views-of-the-user-processor) · [Views of the User: Predictor](#L2-1-views-of-the-user-predictor) · [Views of the User: Participant](#L2-1-views-of-the-user-participant) · [Good Design, Bad Design](#L2-1-good-design-bad-design) · [Quiz: Reflections: Views of the User](#L2-1-quiz-reflections-views-of-the-user) · [User Experience, Sans Design](#L2-1-user-experience-sans-design) · [Quiz: Design Challenge: Morgan on the Street](#L2-1-quiz-design-challenge-morgan-on-the-street) · [Conclusion to Intro to Design](#L2-1-conclusion-to-intro-to-design)

---

<a id="A-L2-2"></a>

## Summary — Lesson 2.2 Feedback Cycles

**Full lecture text:** [2.2 Feedback Cycles](#L2-2) · **Lecture book pages:** pp. 98–127

**In one sentence:** Feedback cycles as the most fundamental HCI concept: the Gulf of Execution (how do I know what I can do?), the Gulf of Evaluation (how do I know what happened?), tips for bridging each, Norman's Seven Questions, and worked examples (microwave, thermostat, David's car, credit-card readers).

### Key points

- [Introduction to Feedback Cycles](#L2-2-introduction-to-feedback-cycles) — Feedback cycles = how people interact with the world and get feedback on the results. Lesson covers:
  - Ubiquity of feedback cycles.
  - **Gulf of execution**: distance between the user's goals and the execution of the actions required to realise them.
  - **Gulf of evaluation**: distance between the effects of those actions and the user's understanding of the results.
  - Seven questions to ask when designing feedback cycles; applications in everyday life.
- [Feedback Cycles are Fundamental](#L2-2-feedback-cycles-are-fundamental):
  - Ubiquitous with or without computers: reading, driving, interacting with people; how we learn everything (walking, Rubik's cube, third-order partial derivatives). Do something, see the result, adjust next time.
  - Related courses: Knowledge-Based AI (Ashok Goel & Joyner) — agents interact with, learn from and affect the world; Cyber-Physical Systems (Rahim Baez) — systems autonomously read input and react, no human; some call that AI because it mimics what a human does.
  - Definitions of intelligence based on feedback cycles: **Colvin** — adjusting to one's environment; **Dearborn** — learning or profiting by experience; adaptive behaviour generally; **Schank** — getting better over time.
  - Nearly all of HCI can be read as feedback cycles: person–task, person–interface, or systems of many people and interfaces.
- [Gulf of Execution](#L2-2-gulf-of-execution) — diagram: user (left) → input via interface → task/system (right) → output via interface → user. Gulf of execution = “how do I know what I can do?” / difference between what the user thinks they should have to do and what they actually have to do. Three components:
  1. **Identify the goal in the context of the system** (mismatch between own understanding and system structure — VCR → DVR → on-demand: goal “watch an aired programme” means “record it” on a VCR/DVR but “call up the existing version” on demand).
  2. **Identify the actions** necessary to accomplish the goal (navigate menus, find the programme).
  3. **Execute the actions** in the interface (knowing what to do but not where to find it is an execution difficulty).
- [Gulf of Execution Example](#L2-2-gulf-of-execution-example) — Microwaving chili: goal = heat it up; intent in system terms = microwave for one minute; actions = Time Cook → 1-0-0 → Start. Shortcut: press “1” and wait — fewer actions (narrower gulf) but harder to *identify* the action (possibly wider gulf for a novice). Good interface caters to both: a hard-but-discoverable way and a short-but-visible way. Rewind to the real goal: one minute may not be enough; the microwave has an automatic reheat that senses temperature — the best bridge may help the user **reframe their intention** (“heat until ready”).
- [5 Tips: Gulfs of Execution](#L2-2-5-tips-gulfs-of-execution):
  1. **Make functions discoverable** — a first-time user shouldn't need documentation or a class; functions clearly labelled within the interface.
  2. **Let the user mess around** — make poking around safe: no actions that can't be undone; no buttons that irreversibly ruin a document or setup.
  3. **Be consistent with other tools** — Ctrl+C copy, Ctrl+V paste; a diskette icon for save even though nobody uses floppy disks.
  4. **Know your user** — novices value identifying intentions and actions (discoverable menus); experts value doing the action (command line: lacks novice usability but very efficient).
  5. **Feed forward** — feedback on what the user *might* want to do; helps predict the result of an action (Facebook pull-to-refresh shows a refresh icon; if you don't finish pulling it doesn't refresh).
  6. (Derived from Don Norman and Jakob Nielsen's principles — covered in a later lesson.)
- [Gulf of Evaluation](#L2-2-gulf-of-evaluation) — the task must express the output of the user's actions through the interface; the user evaluates the new state. Three parts:
  1. **Physical form of output** — what did it actually do (visual, sound, vibration)?
  2. **Interpretation** — can the user interpret the real meaning (phone vibrates in pocket: do you know what it means or must you look)?
  3. **Evaluation** — does that interpretation mean the goal was accomplished (form submitted: received ≠ accepted)?
  4. On-demand example: pressing play hides the menus; expert interprets black screen as loading; novice interprets it as the service stopping (like a computer shutting down) → incorrectly evaluates failure. Fix: a buffering icon.
- [Gulf of Evaluation Example](#L2-2-gulf-of-evaluation-example) — Thermostat: goal = warmer room; heat turns on but how do you know? Maybe hear a click (one-time, quiet, can't double-check) or feel the vent (hard to reach); heater may not turn on immediately. Large gulf of evaluation; ideally the system also tells you *why* you weren't successful. Fix: mark on the thermostat that the heat is on — trivial, but only found by thinking from the user's perspective. Still not ideal: it sometimes doesn't run the heater even when set temperature is above room temperature and gives no indication why (wrong mode is visible only once you remember to check) — a message indicating the direction of the relationship would help.
- [5 Tips: Gulfs of Evaluation](#L2-2-5-tips-gulfs-of-evaluation):
  1. **Give feedback constantly** — don't wait until processing is done; feedback that input was received, what input was received, where the system is at every step.
  2. **Give feedback immediately** — let the user know they've been heard even before a full response (icons briefly grey out when tapped, even if the app takes a while to open).
  3. **Match the feedback to the action** — subtle actions, subtle feedback; significant actions, significant feedback (otherwise constant feedback becomes annoying).
  4. **Vary your feedback** — the screen is where interaction happens so visual feedback can get in the way; consider auditory or haptic feedback.
  5. **Leverage direct manipulation** — let users feel they're directly manipulating things (dragging, pulling to resize) — intuitive because it feels like interacting with the content. (Repeated loading into short-term memory helps solidify in long-term memory — see Human Abilities.)
- [Good Design, Bad Design: Feedback Cycles](#L2-2-good-design-bad-design-feedback-cycles) — Good: a phone that quietly clicks for each successful key press. Bad: a phone that loudly shouts every letter (“P. I. C.”). Small actions get small feedback; the only time a device should yell a confirmation is if you just ordered a nuclear launch.
- [Quiz: Reflections: Feedback Cycles](#L2-2-quiz-reflections-feedback-cycles) — Joyner's tripped breaker: labels didn't match, tried every breaker, shut off the whole house; the real fix was a reset button on the outlet itself (noticed only because his wife saw something flicker). Goal was easy to translate (“reset a breaker”) but figuring out the actions was very hard = large gulf of execution. Joke with Amanda not watching = no feedback on his performance = poor gulf of evaluation (same applies to filming or your project work).
- [Quiz: Feedback Cycles in David's Car 1](#L2-2-quiz-feedback-cycles-in-david-s-car-1) — Ignition button sits where the key used to go; with push-button start it could go anywhere, but it's placed where the driver **expects** it — bridging the gulf of execution by being consistent with expectations. Sometimes we violate this for other benefits, but all else equal, stay consistent.
- [Quiz: Feedback Cycles in David's Car 2](#L2-2-quiz-feedback-cycles-in-david-s-car-2) — Press the button: happy confirmation sound, but the car did **not** turn on — you must press the brake pedal while pressing the button. Poor gulf of execution (no indicator you're doing it wrong until you've done it wrong) but short gulf of evaluation (dashboard alert tells you to press the brake and then the button — easy to interpret, presented in context).
- [Quiz: Feedback Cycles in David's Car 3](#L2-2-quiz-feedback-cycles-in-david-s-car-3) — Improvements: show the brake-pedal alert as soon as the driver gets in, every time (doesn't widen the gulf for experts, narrows it for novices). Sound: the same sound plays on press whether or not the car turns on, then a different follow-up sound confirms it started; Joyner would prefer two different sounds from the start — presence of a sound confirms the press, nature of the sound confirms the effect.
- [Seven Questions for Bridging Gulfs](#L2-2-seven-questions-for-bridging-gulfs) — from Don Norman, *The Design of Everyday Things*; how easily can one…
  1. …determine the **function** of the device?
  2. …tell what **actions are possible**?
  3. …determine the **mapping from intention to physical movement**?
  4. …actually **perform the physical movement**?
  5. …tell what **state the system is in**?
  6. …tell if the system is in the **desired state**?
  7. …determine the **mapping from system state to interpretation**?
  8. These match the stages: interpret goal in context of device function → discern possible actions → identify how to perform / which action → perform → observe output → compare output to desired state → interpret the difference.
- [Exploring HCI: Feedback Cycles](#L2-2-exploring-hci-feedback-cycles) — Healthcare: feedback cycles help patients manage symptoms (test results must be easy to interpret and evaluate). Gesture interaction: hard to get feedback on how a gesture was interpreted and why; compare touch, where it's easy to see where you touched.
- [Quiz: Design Challenge: Credit Card Readers 1](#L2-2-quiz-design-challenge-credit-card-readers-1) — Square readers (Joyner's wife sells arts and crafts): swipe version vs insert version.
  - Swipe: no feedback on whether you're swiping correctly; you can be wrong in **both directions** (too fast or too slow) — people slow down more and more when the problem was being too slow; acceptable input bounded on both sides.
  - Insert is better: (1) gulf of execution — physically easier; can't push too far, so an error always means not far enough; (2) rich, immediate **physical** feedback — you feel the card stop, instead of delayed “try again”.
- [Quiz: Design Challenge: Credit Card Readers 2](#L2-2-quiz-design-challenge-credit-card-readers-2) — New problem: with insertion you let go of the card and may walk away without it (worse on mounted store readers). Options: a buzzer until the card is removed (ATMs do this; noisy, spoils a restaurant's ambience); pair the card with a smartphone and ring when they separate (new tech in every card — expensive); simplest: force the customer to remove the card to get the receipt and their goods.
- [Quiz: Design Challenge: Credit Card Readers 3](#L2-2-quiz-design-challenge-credit-card-readers-3) — What's wrong with “how do we make swiping/inserting easier?” — wrong task. The task is to pay for purchases as easily as possible; e.g. tap your phone on the reader (this reader supports it) using the thing people always carry. Incremental improvements to swiping are fine, but always keep your eyes on the underlying task.
- [Conclusion to Feedback Cycles](#L2-2-conclusion-to-feedback-cycles) — feedback cycles defined as the exchange of input and output between a user and a system to accomplish some goal. Covered:
  - Ubiquity in other fields.
  - Gulf of execution: distance between knowing what you want and executing the steps.
  - Gulf of evaluation: distance between making a change and evaluating whether the goal was accomplished.
  - Seven questions for bridging the gulfs. Next: methods for crossing them.

**Keywords to search for:** feedback cycle · gulf of execution · gulf of evaluation · identify goal / identify actions / execute actions · form / interpretation / evaluation · Colvin / Dearborn / Schank · Knowledge-Based AI · cyber-physical systems · microwave chili · Time Cook · automatic reheat · reframe intention · discoverable · mess around · diskette icon · feedforward · pull to refresh · buffering icon · thermostat heat indicator · icons grey out · match feedback to action · haptic · nuclear launch · tripped breaker · David's car / brake pedal · Seven Questions · Design of Everyday Things · Square reader · swipe vs insert · too fast or too slow · buzzer / ATM · tap your phone

**Jump to a section of the full text:** [Introduction to Feedback Cycles](#L2-2-introduction-to-feedback-cycles) · [Feedback Cycles are Fundamental](#L2-2-feedback-cycles-are-fundamental) · [Gulf of Execution](#L2-2-gulf-of-execution) · [Gulf of Execution Example](#L2-2-gulf-of-execution-example) · [5 Tips: Gulfs of Execution](#L2-2-5-tips-gulfs-of-execution) · [Gulf of Evaluation](#L2-2-gulf-of-evaluation) · [Gulf of Evaluation Example](#L2-2-gulf-of-evaluation-example) · [5 Tips: Gulfs of Evaluation](#L2-2-5-tips-gulfs-of-evaluation) · [Good Design, Bad Design: Feedback Cycles](#L2-2-good-design-bad-design-feedback-cycles) · [Quiz: Reflections: Feedback Cycles](#L2-2-quiz-reflections-feedback-cycles) · [Quiz: Feedback Cycles in David's Car 1](#L2-2-quiz-feedback-cycles-in-david-s-car-1) · [Quiz: Feedback Cycles in David's Car 2](#L2-2-quiz-feedback-cycles-in-david-s-car-2) · [Quiz: Feedback Cycles in David's Car 3](#L2-2-quiz-feedback-cycles-in-david-s-car-3) · [Seven Questions for Bridging Gulfs](#L2-2-seven-questions-for-bridging-gulfs) · [Exploring HCI: Feedback Cycles](#L2-2-exploring-hci-feedback-cycles) · [Quiz: Design Challenge: Credit Card Readers 1](#L2-2-quiz-design-challenge-credit-card-readers-1) · [Quiz: Design Challenge: Credit Card Readers 2](#L2-2-quiz-design-challenge-credit-card-readers-2) · [Quiz: Design Challenge: Credit Card Readers 3](#L2-2-quiz-design-challenge-credit-card-readers-3) · [Conclusion to Feedback Cycles](#L2-2-conclusion-to-feedback-cycles)

---

<a id="A-L2-3"></a>

## Summary — Lesson 2.3 Direct Manipulation

**Full lecture text:** [2.3 Direct Manipulation](#L2-3) · **Lecture book pages:** pp. 128–154

**In one sentence:** Two applications of good feedback cycles: direct manipulation (feel like you're directly controlling the object of the task — distance + direct engagement, per Hutchins, Hollan & Norman 1985) and invisible interfaces (invisible by learning vs invisible by design).

### Key points

- [Introduction to Direct Manipulation and Invisible Interfaces](#L2-3-introduction-to-direct-manipulation-and-invisible-interfaces) — Direct manipulation: the user should feel as much as possible like they're directly controlling the object of their task (drag to enlarge a photo rather than tap “zoom in”). Touchscreens make this increasingly possible. At their best interfaces disappear = **invisible interface**: no time thinking about the interface, all on the task.
- [Direct Manipulation: The Desktop Metaphor](#L2-3-direct-manipulation-the-desktop-metaphor) (first part) — Goal: narrow gulfs of execution and evaluation; direct manipulation is arguably the ultimate form, revolutionary in HCI history. Desktop metaphor: files/folders on screen mimic physical ones; moving a physical file = pick it up and move it; so moving on the computer should mimic that, leveraging real-world experience and expectations.
- [Direct Manipulation: The Desktop Metaphor](#L2-3-direct-manipulation-the-desktop-metaphor) (second part) — history of moving a file:
  - **Command line**: must remember **ls** to list, and the move command plus parameter order; no recourse if forgotten (Joyner Googled it before filming); little feedback — must change folders to check. Efficient once known, but nothing natural about it for a novice.
  - **Mouse**: click and drag into a folder; instant feedback (file disappears, sound effect); far more direct, but gulfs remain for novices — interpreting that moving the hand left moves the cursor left; clicking is only “kind of” grabbing.
  - **Touchscreen**: hold the icon and drag it into the folder — almost entirely direct; no prior knowledge needed.
  - General heuristic: how do we help the user interact as closely/directly as possible with the target of their task?
- [Paper Spotlight: "Direct Manipulation Interfaces"](#L2-3-paper-spotlight-direct-manipulation-interfaces) — seminal 1985 paper by **Edwin Hutchins, James Hollan and Don Norman** (Hutchins later co-authored the foundational distributed-cognition paper; Norman wrote *The Design of Everyday Things*). Two aspects of directness:
  1. **Distance** — between the user's goals and the system (= gulfs of execution/evaluation). Quote: “the feeling of directness is inversely proportional to the amount of cognitive effort it takes to manipulate and evaluate the system.” Two components: **semantic distance** (goals → their expression in the system; how hard it is to know what to do; covers identify-intentions and identify-actions) and **articulatory distance** (expression → execution; how hard it is to do what you know to do; covers execute-actions).
  2. Figure 6 of the paper: goals → intentions in context of interface → form of input/actions → execute → system acts → output form → interpret meaning → evaluate against goals. Joyner's example: rotating the paper in the viewer — rotate button turned it upside down (interpreted wrong direction, goal not met) → pressed twice more → right side up.
  3. Distance alone is only part — everything so far is true of feedback cycles generally. **Direct engagement** is what sets direct manipulation apart. Quote: systems that best exemplify direct manipulation “all give the qualitative feeling that one is directly engaged with the control of the objects — not with the programs, not with the computer, but with the semantic objects of our goals and intentions.” Moving files = moving representations of files; games = controlling the character; channels = selecting clear representations of channels.
  4. Gulfs can be shortened without direct manipulation, but it's a powerful method.
- [Exploring HCI: Direct Manipulation](#L2-3-exploring-hci-direct-manipulation) (first) — VR brings direct manipulation to 3D design: designers traditionally used 2D interfaces to design in 3D; in VR they rotate objects with the same hand motions as physical objects and walk around them. Open problem: physical objects push back against your hands — how to recreate that in VR?
- [Quiz: Reflections: Direct Manipulation](#L2-3-quiz-reflections-direct-manipulation) — Think of tasks without direct manipulation, especially where technology replaced something manual. Joyner's example: inserting an emoji means tapping an icon and scrolling a list — unlike reacting naturally in conversation; idea: a button that inserts the emoji matching your current facial expression (wink to wink, frown to frown) for common faces.
- [Babies and Direct Manipulation](#L2-3-babies-and-direct-manipulation) — Joyner's 18-month-old daughter Lucy can use a Kindle Fire tablet through direct manipulation though she couldn't use a keyboard or mouse. Even better example: tablet games for cats — cats can use tablets when they use direct manipulation.
- [Quiz: Exercise: Direct Manipulation](#L2-3-quiz-exercise-direct-manipulation) — Mac touchpad gestures: which are direct manipulation? Test: is what you do to the touchpad what you'd like to do to the screen itself?
  - Click (press): **yes** — pressing the touchpad like pressing the screen.
  - Two-finger tap for right-click: **no** — nothing natural about two fingers for a context menu; learned.
  - Two-finger scroll: **yes** — like physically pulling the page up/down.
  - Two-finger double-tap to zoom a little: **no** — no clear reason it should zoom; learned.
  - Pinch to zoom: **yes** — like grabbing the page and shrinking/enlarging it.
- [Making Indirect Manipulation](#L2-3-making-indirect-manipulation) — making indirect manipulation feel more direct: two-finger swipe from the right pulls up Notification Center on the right — feels direct because it appears where you swiped (touchpad as miniature screen), though they could have placed it anywhere (unlike scrolling, nothing about the content demands it). **Animation** helps: spreading fingers clears windows to the sides with an animation that mimics the gesture (windows could have faded or slid down — the chosen animation reinforces directness); pinching for Launchpad looks like zooming out. Lesson: direct manipulation is not only designing interactions that feel direct, but designing interfaces that lend themselves to interactions that feel direct.
- [Exploring HCI: Direct Manipulation](#L2-3-exploring-hci-direct-manipulation) (second) — Gesture interfaces: you're not touching anything; direct manipulation depends on immediate feedback mapping directly to the interaction — how to create that? VR: visually and auditorily convincing but a long way to go kinesthetically — how to create the feeling of direct manipulation with only visual/auditory feedback?
- [Invisible Interfaces](#L2-3-invisible-interfaces) — Whether through direct manipulation, innovative gulf-shrinking, or the user's patience and learning, the ultimate goal is an interface that becomes invisible: an interface exists in the middle but the user spends no time thinking about it. Stylus on a tablet feels like writing on paper (invisible); drawing with a mouse feels extremely unnatural (very aware of the mouse).
- [Good Design, Bad Design In](#L2-3-good-design-bad-design-in) — Good: interfaces that are *metaphorically* invisible. Bad: interfaces that are *literally* invisible — gesture-based interfaces are in one sense literally invisible, which is why great feedback matters (otherwise it's hard to gauge success of a gesture).
- [Invisibility by Learning](#L2-3-invisibility-by-learning) — Don't assume an invisible interface = great design; interfaces also become invisible because users **learn** them. Driving: you instinctively turn the wheel and brake to avoid someone — the steering wheel became invisible through practice, but people spend months learning, pay hundreds for classes, pass a complicated test. Driving is important enough to justify that curve; our interfaces won't get a year — we'll be lucky to get a minute. So aim for invisibility **by design**.
- [Invisibility by Design](#L2-3-invisibility-by-design) — Interfaces invisible from the moment the user starts; extremely tall order, rarely met, but the goal. This is why people underestimate HCI's complexity: when done right, people aren't aware anything was done. Principles for this: leveraging prior expectations, quick feedback, getting inside the user's head so their mental model matches the system. If invisibility is the hallmark of usable design, the whole course could be retitled “Creating Invisible Interfaces.”
- [5 Tips: Invisible Interfaces](#L2-3-5-tips-invisible-interfaces):
  1. **Use affordances** — visual design shows how it's used: buttons are for pressing, dials for turning, switches for flicking (more in the design-principles lesson).
  2. **Know your user** — invisibility to a novice = all interactions natural; to an expert = maximum efficiency.
  3. **Differentiate your user** — if designing for both, provide multiple ways: Copy/Paste in the Edit menu (discoverable) plus Ctrl+C/Ctrl+V (efficient).
  4. **Let your interface teach** — not tutorials/manuals; e.g. selecting Copy in the Edit menu shows the hotkey, teaching the efficient way without requiring prior knowledge.
  5. **Talk to your user** — ask what they're thinking while using it; note whether they talk about the task or the interface — if the interface, it's pretty visible.
- [Quiz: Reflections: Invisibility by Design](#L2-3-quiz-reflections-invisibility-by-design) — Joyner's favourite: **Portal 2**. Camera-axis preference (press up to look up vs inverted, like a joystick) is normally set in an options screen. Portal 2 has a character say “look up at the ceiling” / “look down at the floor” after a buzzer, assumes whichever direction you pressed is your preference, and sets it — no options screen; the game invisibly completed the goal of setting the camera preference.
- [Quiz: Design Challenge: The](#L2-3-quiz-design-challenge-the) (universal remote control) — classic undergraduate HCI problem; remotes aren't great because of how many functions and physical constraints (people tape over buttons for parents/kids). Joyner: great candidate for a **voice interface** (Comcast, Amazon experimenting). Challenge: voice commands aren't discoverable — if you don't know what you can say you can't find out — but TV/movie watching already has a natural vocabulary (“watch Community” → figure out DVR / On Demand / live). Ends with the Conan clip of Joyner's fan correction about Rand Paul.
- [Conclusion to Direct Manipulation](#L2-3-conclusion-to-direct-manipulation):
  - Interfaces are most effective when the user feels they're directly manipulating the object of the task.
  - Touchscreens and VR make manipulation feel more and more direct.
  - The most effective interfaces become invisible — no time thinking about the interface.
  - Invisible via learning or via design; we want design. To a large extent that's the definition of usable design.

**Keywords to search for:** direct manipulation · invisible interface · desktop metaphor · command line / ls · mouse · touchscreen · Hutchins, Hollan & Norman 1985 · distance · semantic distance · articulatory distance · direct engagement · Figure 6 · rotate paper · VR 3D design · emoji facial expression · Lucy / Kindle Fire · cats tablet · Mac touchpad · pinch to zoom · Notification Center · animation · Launchpad · stylus vs mouse · metaphorically vs literally invisible · invisibility by learning · driving · invisibility by design · affordances · let your interface teach · Portal 2 · universal remote · voice interface · watch Community

**Jump to a section of the full text:** [Introduction to Direct Manipulation and Invisible Interfaces](#L2-3-introduction-to-direct-manipulation-and-invisible-interfaces) · [Direct Manipulation: The Desktop Metaphor](#L2-3-direct-manipulation-the-desktop-metaphor) · [Direct Manipulation: The Desktop Metaphor](#L2-3-direct-manipulation-the-desktop-metaphor-2) · [Paper Spotlight: "Direct Manipulation Interfaces"](#L2-3-paper-spotlight-direct-manipulation-interfaces) · [Exploring HCI: Direct Manipulation](#L2-3-exploring-hci-direct-manipulation) · [Quiz: Reflections: Direct Manipulation](#L2-3-quiz-reflections-direct-manipulation) · [Babies and Direct Manipulation](#L2-3-babies-and-direct-manipulation) · [Quiz: Exercise: Direct Manipulation](#L2-3-quiz-exercise-direct-manipulation) · [Making Indirect Manipulation](#L2-3-making-indirect-manipulation) · [Exploring HCI: Direct Manipulation](#L2-3-exploring-hci-direct-manipulation-2) · [Invisible Interfaces](#L2-3-invisible-interfaces) · [Good Design, Bad Design In](#L2-3-good-design-bad-design-in) · [Invisibility by Learning](#L2-3-invisibility-by-learning) · [Invisibility by Design](#L2-3-invisibility-by-design) · [5 Tips: Invisible Interfaces](#L2-3-5-tips-invisible-interfaces) · [Quiz: Reflections: Invisibility by Design](#L2-3-quiz-reflections-invisibility-by-design) · [Quiz: Design Challenge: The](#L2-3-quiz-design-challenge-the) · [Conclusion to Direct Manipulation](#L2-3-conclusion-to-direct-manipulation)

---

<a id="A-L2-4"></a>

## Summary — Lesson 2.4 Human Abilities

**Full lecture text:** [2.4 Human Abilities](#L2-4) · **Lecture book pages:** pp. 155–186

**In one sentence:** Crash course in the psychology of the human as input–processing–output system: visual/auditory/haptic perception, three kinds of memory (perceptual store, short-term, long-term), learning (procedural vs declarative), cognitive load and the motor system.

### Key points

- [Introduction to Human Abilities](#L2-4-introduction-to-human-abilities) — HCI starts with the human; three systems:
  - **Input**: how stimuli are sent from the world and perceived in the mind.
  - **Processing**: cognition — how the brain stores and reasons over input.
  - **Output**: how the brain controls actions in the world.
  - High-level coverage; recommended: a psychology course on sensation and perception.
- [Information Processing](#L2-4-information-processing) — Adopts something like the **processor view**: what the human can do physically and cognitively; the human discussed almost the way we discuss the computer — consumes input, produces output; not worried here about where input came from or what actions do.
- [Sensation and Perception: Visual](#L2-4-sensation-and-perception-visual) — Morgan's eyes:
  - Centre of the eye: best for focusing on colour and tracking movement → put the most important details in the centre of view.
  - Peripheral vision: good at detecting motion, poor at colour and detail → use for some alerts, never require close focus there.
  - Colour-blindness: women ≈ 1 in 200; men ≈ 1 in 12 — significant → don't rely on colour to understand the interface; use colour only to emphasise information already present.
  - Sight is directional: looking the wrong way or eyes closed = missed visual feedback.
  - Visual acuity decreases with age → mind font size; ideally adjustable. Vision is hugely important — most HCI concepts connect to visual perception.
- [Sensation and Perception: Auditory](#L2-4-sensation-and-perception-auditory) — Discerns pitch and loudness; remarkably good at localising sound (can distinguish a nearby quiet sound from a far-away loud one even if equal when reaching the ear). Hearing is **not** directional — can't close or point ears, can't easily filter → good for alerts, but risks overwhelming her or sharing too much with people around her.
- [Sensation and Perception: Haptic](#L2-4-sensation-and-perception-haptic) — Skin feels only on contact (not at a distance): pressure, vibration, temperature. Like hearing, can't easily be filtered; unlike hearing, generally available only to the person touched → more personal feedback. Traditionally natural (feeling keys go down); with touchscreens, motion controls and VR, touch feedback must be explicitly designed in.
- [Quiz: Design Challenge: Message Alerts](#L2-4-quiz-design-challenge-message-alerts) — Alert Morgan to a text whether the phone is in her pocket or on the table, without disturbing people around her (loud vibration on a table counts as disturbing); any modality but only the phone's sensors. One design: use the camera/light sensor — light detected → screen visible → flash the flashlight or illuminate the screen; no light → in pocket → vibrate. Imperfect (purse, face-down) → iterate based on user experience.
- [Quiz: Memory: Perceptual Store](#L2-4-quiz-memory-perceptual-store) — three kinds of memory used here: **perceptual store / working memory**, **short-term memory**, **long-term memory** (some scientists add others, e.g. an intermediate “back of the mind” memory). Perceptual store lasts less than a second. Baddeley & Hitch (1974) model of working memory:
  1. **Visuospatial sketchpad** — holds visual information for active manipulation (picture a pencil).
  2. **Phonological loop** — verbal/auditory information (the sound of speech just heard).
  3. **Episodic buffer** — integrates information from the other systems and handles chronological ordering.
  4. All coordinated by a **central executive**.
  5. Scoreboard exercise: quickly flashed baseball picture, score was 0–0; baseball fans do better — domain expertise speeds processing (few innings marked → low score). Chess study: experts far better than novices at remembering realistic boards flashed briefly, no better at random boards → expertise or rehearsal delays decay of the perceptual buffer.
- [Quiz: Memory: Short Term and Chunking](#L2-4-quiz-memory-short-term-and-chunking) — Short-term memory is one of the biggest design concerns. Current research: users store only **4–5 chunks** at a time (the older “7 ± 2” idea is superseded). **Chunking** = grouping several bits into one chunk. Exercise: six letter-strings shown, then cat and daughter photos to prevent rehearsal; real words easy (one existing chunk), pronounceable fake words moderate (seen as pseudo-words), random letter strings hard (five chunks each).
- [Quiz: Memory: Short Term and Recognition](#L2-4-quiz-memory-short-term-and-recognition) — Asked which of six words you saw: much easier — **recognition** is far easier than **recall**. Design takeaway: minimise memory load by relying on recognition over recall.
- [Memory: Short Term Takeaways](#L2-4-memory-short-term-takeaways) — Don't ask the user to hold more than 4–5 chunks (ten numbers is too much). Increase effective capacity by helping users chunk (phone number: ten digits → three groups, in a familiar national format). Leverage recognition over recall — why menu bars and tool strips are ubiquitous: users recognise the icon/option rather than remember it.
- [Memory: Long Term Memory](#L2-4-memory-long-term-memory) — Seemingly unlimited store, but harder to load than short-term: generally requires putting something into short-term memory several times. **Leitner system** (flashcards, key–value pairs: words/definitions, countries/capitals, laws/formulas): known cards → right pile, unknown → left; tomorrow review only the left pile, moving remembered ones right; in four days review the right pile, moving forgotten ones back left; in practice use 3–5 piles, the long-retention pile reviewed perhaps yearly. Things remembered least are loaded into short-term memory most often, solidifying them in long-term memory.
- [Cognition: Learning](#L2-4-cognition-learning):
  - Interfaces should require as little learning as possible, yet teach users to be more efficient over time. PowerPoint: a first-time user finds Copy under Edit; the menu also shows the hotkey — teaching efficiency without assuming prior knowledge.
  - Two kinds of learning: **procedural** (how to do something — computer work, sports, instruments) vs **declarative** (knowledge about something — what you can answer when asked). “What's the hotkey for paste?” = declarative; “paste your clipboard here” = procedural; experts often answer the declarative question by mentally simulating the procedure.
  - Declarative is how we communicate; procedural is what we do in HCI. Strong procedural knowledge → **unconsciously competent**, hard to explain to someone lacking it. Designers are domain experts → prone to designing things easy for themselves but hard for everyone else.
- [Cognition: Cognitive Load](#L2-4-cognition-cognitive-load) — Brain-as-computer metaphor (community divided on whether it's literally true, but useful): finite cognitive resources, each activity consumes some. Calculus at home needs 60% — fine; in a test, stress takes 50% → insufficient resources → hypothesis for why test anxiety hurts; same for distractions, anxiety disorders. Two design applications: (1) reduce the load posed by the interface so the user focuses on the task; (2) understand what else competes for resources in context (GPS user has few resources to spare).
- [Quiz: Reflections: Cognitive Load](#L2-4-quiz-reflections-cognitive-load) — Programming has incredibly high load (goals for the line, function, programme; variables created…) — hence jokes about interrupting programmers. Good IDEs help: inline automated error checking offloads low-level syntax so the programmer focuses on the goal — offloading from user to interface, or “distributing cognitive load more evenly between components of the system” (links to **distributed cognition**).
- [5 Tips: Reducing Cognitive Load](#L2-4-5-tips-reducing-cognitive-load):
  1. **Use multiple modalities** — usually visual and verbal; one engaged system overloads while the other is bored; describe verbally and present visually.
  2. **Let the modalities complement each other** — presenting *different* content in two modalities raises load (Amanda showed something irrelevant on screen as a demonstration); each modality should support, illustrate or explain the other.
  3. **Give the user control of the pace** — built-in timers (menus disappearing, timed selections) dictate pace, induce stress, raise load; let the user control the pace (especially in education).
  4. **Emphasize essential content and minimize clutter** — discoverability says make functions findable, but 500 options raises load; emphasise common actions while still giving access to the full range.
  5. **Offload tasks** — look at what the user must do or remember at each stage; show what they entered on a previous screen; trigger manual tasks automatically.
- [Motor System](#L2-4-motor-system) — Also design for what users can physically do: speed, precision of clicks/taps. Example: two Android Spotify widgets — tray version has the X (close) in the top-right corner away from everything; lock-screen version has X right beside Skip. Tapping X instead of Skip is a frequent error while running/driving — not a perception or memory error, a **motor-precision** error; buttons are no smaller than keyboard keys, but less precision is available when reaching over quickly on a lock screen. (The + sign has no clear mapping to a function.) If constraints force the layout (e.g. Android allows one row on the lock screen), make the interface more **error-tolerant**: require a double-tap to close, or mute and give five seconds to confirm — reducing the penalty for errors.
- [Exploring HCI: Human Abilities](#L2-4-exploring-hci-human-abilities) — Which abilities matter depends on area: gestural interfaces/wearables → motor-system limits; educational technology → cognitive issues; VR → mainly perception (plus open questions about physical interaction).
- [Conclusion to Human Abilities](#L2-4-conclusion-to-human-abilities) — Covered perception (sight, sound, touch), cognition (memory, learning), motor system; only scratched the surface — entire courses/degrees exist; enough to keep human abilities in mind and know what to research.

**Keywords to search for:** input / processing / output · processor view · central vs peripheral vision · colour-blindness 1 in 12 / 1 in 200 · sight is directional · hearing not directional · localizing sound · haptic · message alert / light sensor · perceptual store · working memory · Baddeley & Hitch 1974 · visuospatial sketchpad · phonological loop · episodic buffer · central executive · scoreboard 0–0 · chess experts · short-term memory 4–5 chunks · 7 ± 2 · chunking · recognition over recall · menu bars · long-term memory · Leitner system · flashcards · procedural vs declarative · unconsciously competent · cognitive load · test anxiety · IDE inline errors · distributed cognition · multiple modalities · control the pace · offload tasks · Spotify widget · motor system · error tolerance / double-tap

**Jump to a section of the full text:** [Introduction to Human Abilities](#L2-4-introduction-to-human-abilities) · [Information Processing](#L2-4-information-processing) · [Sensation and Perception: Visual](#L2-4-sensation-and-perception-visual) · [Sensation and Perception: Auditory](#L2-4-sensation-and-perception-auditory) · [Sensation and Perception: Haptic](#L2-4-sensation-and-perception-haptic) · [Quiz: Design Challenge: Message Alerts](#L2-4-quiz-design-challenge-message-alerts) · [Quiz: Memory: Perceptual Store](#L2-4-quiz-memory-perceptual-store) · [Quiz: Memory: Short Term and Chunking](#L2-4-quiz-memory-short-term-and-chunking) · [Quiz: Memory: Short Term and Recognition](#L2-4-quiz-memory-short-term-and-recognition) · [Memory: Short Term Takeaways](#L2-4-memory-short-term-takeaways) · [Memory: Long Term Memory](#L2-4-memory-long-term-memory) · [Cognition: Learning](#L2-4-cognition-learning) · [Cognition: Cognitive Load](#L2-4-cognition-cognitive-load) · [Quiz: Reflections: Cognitive Load](#L2-4-quiz-reflections-cognitive-load) · [5 Tips: Reducing Cognitive Load](#L2-4-5-tips-reducing-cognitive-load) · [Motor System](#L2-4-motor-system) · [Exploring HCI: Human Abilities](#L2-4-exploring-hci-human-abilities) · [Conclusion to Human Abilities](#L2-4-conclusion-to-human-abilities)

---

<a id="A-L2-5"></a>

## Summary — Lesson 2.5 Design Principles and Heuristics

**Full lecture text:** [2.5 Design Principles and Heuristics](#L2-5) · **Lecture book pages:** pp. 187–236

**In one sentence:** Merges four famous sets of design guidelines — Norman's six principles, Nielsen's ten heuristics, Constantine & Lockwood's six principles, and the seven Principles of Universal Design — into Joyner's 15 principles: discoverability, simplicity, affordances, mapping, perceptibility, consistency, flexibility, equity, ease, comfort, structure, constraints, tolerance, feedback, documentation.

### Key points

- [Introduction to Design Principles](#L2-5-introduction-to-design-principles) / [The Sets](#L2-5-the-sets) — principles and heuristics are guidelines, not laws of gravity. The four sets:
  - **Don Norman** — six principles of design, *The Design of Everyday Things*; the most famous set. Newer editions add a seventh (**conceptual models**) which is a whole lesson of its own.
  - **Jakob Nielsen** — Ten Heuristics for UI design (book *Usability Inspection Methods*), usable for design and evaluation. Norman and Nielsen formed the **Nielsen Norman Group** (UX training, consulting, HCI research).
  - **Larry Constantine and Lucy Lockwood** — six principles of UI design in *Software for Use*.
  - **Ronald Mace** (North Carolina State University) — Seven Principles of Universal Design; continued by the Center for Excellence in Universal Design. Concerned with usability for the greatest number of people regardless of age, disability, etc.
  - Joyner merges the 29 combined principles into 15 — an abstraction; learn the original sets too (subtle differences, especially perceptibility, tolerance, feedback).
- The 15 principles and their sources (in lecture order):
  1. **Discoverability** — Norman, Nielsen, Constantine & Lockwood (visibility).
  2. **Simplicity** — Nielsen, Constantine & Lockwood, Universal Design (simple and intuitive use).
  3. **Affordances** — Norman (similar to familiarity principle, Dix et al.).
  4. **Mapping** — Norman, Nielsen.
  5. **Perceptibility** — Nielsen, Universal Design (similar to Norman's feedback).
  6. **Consistency** — Norman, Nielsen, Constantine & Lockwood (reuse).
  7. **Flexibility** — Nielsen, Universal Design (also Dix et al. flexibility principles).
  8. **Equity** — Universal Design.
  9. **Ease** — Universal Design.
  10. **Comfort** — Universal Design.
  11. **Structure** — Constantine & Lockwood.
  12. **Constraints** — Norman, Nielsen.
  13. **Tolerance** — Nielsen, Constantine & Lockwood, Universal Design (Dix et al.: recoverability).
  14. **Feedback** — Norman, Nielsen, Constantine & Lockwood.
  15. **Documentation** — Nielsen.
- [Discoverability](#L2-5-discoverability):
  - Norman: is it possible to figure out what actions are possible and where/how to perform them? Nielsen: minimise memory load by making objects, actions, options visible; instructions visible or easily retrievable. Constantine & Lockwood **visibility principle**: make all needed options/materials for a task visible without distracting with extraneous or redundant information.
  - Idea: functions visible so users discover them rather than reading documentation or tutorials. PowerPoint menus/toolbars — recognise “Arrange” rather than remember a command. Counter-example at OS level: Mac **Command-Shift-4** (screenshot of an area) is only learnable via Google/manual; Joyner (a PC user) re-Googles it each time.
  - Constantine & Lockwood: don't throw everything on screen — walk the line between discoverability and simplicity.
- [Quiz: Design Challenge: Discovering Gestures](#L2-5-quiz-design-challenge-discovering-gestures) — Morgan rejects a call, takes a screenshot, takes a selfie, makes a call; the phone has gestures for each (turn the phone over to reject; say “shoot” for a selfie) but they're not discoverable, and a menu of voice commands defeats the purpose. Ideas: tutorial in advance; in-context tutoring — briefly flash a title-bar message when something you did could have been a gesture/voice command; keep a log to check later.
- [Simplicity](#L2-5-simplicity) — tension with discoverability (too much visible → harder to find things). In three sets:
  - Nielsen (dialogues): no irrelevant or rarely needed information; every extra unit competes with relevant units and diminishes their relative visibility.
  - Constantine & Lockwood simplicity principle: make simple common tasks easy; communicate clearly and simply in the user's language; good shortcuts.
  - Universal Design “simple and intuitive use”: easy to understand regardless of experience, knowledge, language skills, or current concentration level.
  - Examples: Windows **Blue Screen of Death** old vs Windows 10 — softer blue, plain-language description, detailed info still there but de-emphasised (give users only as much as they need); New York **parking signs** — old sign impossible, new sign interpretable with little effort and even by someone who struggles with English.
- [Affordances](#L2-5-affordances) — design that by its very design tells you how to use it (buttons pressed, handles pulled, knobs turned; door handle as icon).
  - Norman: an affordance is “the relationship between the properties of an object and the capabilities of the agent that determine just how the object could possibly be used”; presence is jointly determined by the object's qualities and the agent's abilities — an affordance for one person isn't one for everyone (door handle if you didn't grow up with them). Affordances are defined by who the user is.
  - Virtual world lacks the inherent physical connection, so affordances are created manually: a button looks elevated on hover (affords pushing) and depressed/darker on click.
  - Ways to create naturalness: **visualise the space of options** (colour picker bar + notch); **metaphors/analogies** to physical devices (swipe to turn a page in a book-like interface); **signifiers** (Norman's newer editions) — in-context instructions like arrows indicating swipe direction or a button labelled “Menu” for actions with no real-world analogy. Also intuitive mappings and consistency with past designs.
- [Mapping](#L2-5-mapping) — relationship between interface and effects in the world.
  - Norman: mapping is a maths term — relationship between elements of two sets (interface and world); e.g. book icons mapping quotes to books. Nielsen: speak the user's language, familiar words/phrases/concepts, follow real-world conventions, natural and logical order — e.g. “cut, copy, paste” rather than technical terms like “duplicate”. Nielsen's heuristic = the goal; Norman's principle = one way to achieve it.
  - Example: multi-monitor arrangement screen mirrors physical layout (vs a list of pixel locations with the same information).
  - Affordance vs mapping (colour meter): the notch on a bar affords dragging (how to use); the white-to-black fade shows what dragging will *do* (effect). Mapping = design makes the effect clear, not just the use.
- [Quiz: Design Challenge: Mapping and Switches](#L2-5-quiz-design-challenge-mapping-and-switches) — Light switches afford flipping but have no mapping to which light; stove dials have icons showing the burner. Redesign ideas: letters (K kitchen, C counter, B breakfast room), icons resembling each light; simplest (and how it actually was): switches left-to-right control lights left-to-right in the room.
- [Perceptability](#L2-5-perceptability) — the user's ability to perceive the state of the system.
  - Nielsen: keep users informed about what is going on through appropriate feedback within reasonable time. Universal Design: communicate necessary information effectively regardless of ambient conditions or sensory abilities.
  - Similar to Norman's feedback (immediate, informative; poor feedback can be worse than none) — but feedback is so general it could apply to every principle, so this lesson reserves “feedback” for errors; the feedback-cycles lesson covers it generally.
  - Light switch and oven dial show state nicely. Violation: ceiling fan with two chains — awful mapping (which chain is which) and the fan chain gives no indication of current speed or how many settings; Joyner pulls, waits ten seconds, pulls again — and only works if the wall switch is on.
- [Consistency](#L2-5-consistency) — Norman, Nielsen, Constantine & Lockwood: use controls, visualisations, layouts consistently within our interfaces and across the community.
  - Norman: consistency is virtuous; lessons learned with one system transfer to others; if a new way is only slightly better, be consistent (significant improvements justify change — that's how we advance). Nielsen: users shouldn't wonder whether different words/situations/actions mean the same thing; follow platform conventions. Constantine & Lockwood **reuse**: reuse internal and external components and behaviours, consistency with purpose rather than arbitrary consistency (window colour doesn't matter; renaming copy to duplicate forces rethinking — fine only if it really does something different).
  - Consistency creates affordances by convention: links are blue and underlined (underlining now fading; contrasting colour remains; Wikipedia instantly readable). Also consistent hotkeys (copy, paste, select all), menu order (File, Edit, View…), Save/Open under File. Invisible when right, jarring when wrong.
- [Consistency: The Curious Case of Ctrl+Y](#L2-5-consistency-the-curious-case-of-ctrl-y) — In most interfaces Ctrl+Y = redo. In Visual Studio redo is by default Shift+Alt+Backspace and Ctrl+Y = **delete line**; pressing Ctrl+Y out of habit after undoing deletes the line, creating a new change and losing the entire redo tree. Reason: consistency — Ctrl+Y deleted a line in WordStar (one of the first word processors, before redo existed; Joyner heard Y stood for “Yank” but isn't sure) through Visual Basic 6, Visual Studio's predecessor. Microsoft chose consistency with predecessors over consistency with their other interfaces — honouring consistency one way violated it another. Multiple conflicting things to be consistent with; whether a change is worth the drop in consistency is something to test with users.
- [Flexibility](#L2-5-flexibility) — Right-click Cut/Paste vs Ctrl+X/Ctrl+V: both people are right. Nielsen: **accelerators** (hotkeys) speed up experts so the system caters to both novice and expert; let users tailor frequent actions. Universal Design: accommodate a wide range of individual preferences and abilities. Dix et al. have “flexibility principles” (customisability, multiple designs for the same task). Nielsen → novice vs expert; UD → abilities and preferences; same underlying principle: support the interactions people engage in naturally rather than forcing one.
- [Equity](#L2-5-equity) — Appears to clash with flexibility but both are Universal Design: design is useful and marketable to people with diverse abilities; provide the same means for all users — identical whenever possible, equivalent when not; avoid segregating or stigmatising. Actually complementary: equity = same user experience for all; flexibility = a means to achieve it (discoverable for novices, efficient for experts). Includes privacy and security. Example: **password requirements** — experts understand complex passwords, novices may not; requirements give novices the same security (equitable) while slightly frustrating them (arguably a flexibility violation) — principles sometimes compete.
- [Ease and Comfort](#L2-5-ease-and-comfort) — Both Universal Design, about physical interaction. **Ease** (which uses the word comfort): used efficiently and comfortably with minimum fatigue. **Comfort**: appropriate size and space for approach, reach, manipulation and use regardless of body size, posture or mobility. Historically little HCI relevance (user at a desk), increasingly relevant: computerised car-seat memory; mobile button sizes for users with tremors; wearables and VR.
- [Structure](#L2-5-structure) — Constantine & Lockwood; closer to narrow UI design. Organise the UI purposefully, meaningfully, based on clear consistent models apparent to users; put related things together, separate unrelated, differentiate dissimilar, make similar things resemble one another — i.e. help the user's mental model match the content. Borrows from pre-computer design (newspapers, textbooks): Wall Street Journal print vs website share lines/spacing separating categories, bold headlines, smaller body text (partly brand consistency; website differs e.g. links, shorter teasers).
- [Constraints](#L2-5-constraints) — usability means accounting for error; many theorists (and Joyner) say there's no such thing as user error — the system failed to prevent or recover. Constraints prevent erroneous actions in the first place.
  - Norman: constraints are powerful clues limiting possible actions; thoughtful constraints let people determine the proper course of action even in a novel situation. Nielsen: better than good error messages is careful design preventing problems — eliminate error-prone conditions or check for them and present a confirmation option (e.g. confirm before closing).
  - Password-reset screen: shows constraints visibly, flags violations as you type (“1234” too short, too few character classes) = **soft constraint** (tells you while doing it); refusing characters not on the keyboard = **hard constraint** (prevents invalid input).
- [Norman's Four Types of Constraints](#L2-5-norman-s-four-types-of-constraints) — not just preventing wrong input but ensuring correct input / knowing what to do next:
  1. **Physical** — physically prevent the wrong action: three-prong plug fits one way; USB sticks fit one way (but the constraint only appears after you've tried wrong — harder to see than a wall outlet).
  2. **Cultural** — society's rules: facing forward on escalators, forming a queue; beware intercultural differences.
  3. **Semantic** — inherent to the meaning of the situation (similar to affordances): a rear-view mirror must reflect from behind; semantics may change (autonomous vehicles may not need mirrors).
  4. **Logical** — self-evident from the situation: one screw and one hole left when assembling furniture.
- [Quiz: Reflections: Constraints](#L2-5-quiz-reflections-constraints) — Most principles are invisible when done well; constraints stand in the user's way and are visible — for the greater good. Joyner's Nissan Leaf: options screen (time, date…) is blocked once the car moves — a constraint serving **safety**, not usability; the car is made less usable to be safer.
- [Tolerance](#L2-5-tolerance) — Can't constrain away all errors; two principles for errors that occur: feedback and tolerance. Tolerance: users shouldn't risk causing too much trouble accidentally. Nielsen: users choose functions by mistake and need a clearly marked **emergency exit** without an extended dialogue; support undo and redo (most interested in supporting experimentation — which enhances discoverability because users feel safe poking around). Constantine & Lockwood tolerance principle: flexible and tolerant, reduce cost of mistakes/misuse via undo/redo while preventing errors where possible. Universal Design: minimise hazards and adverse consequences of accidental/unintended actions. Dix et al.: **recoverability**. Why Ctrl+Y in Visual Studio mattered: it breaks redo, a fundamental tolerance mechanism. **Jef Raskin**'s humorous law: “A computer shall not harm your work or, through inactivity, allow your work to come to harm.”
- [Feedback](#L2-5-feedback) — (in response to errors) the system should explain why the error happened and how to avoid it. Norman: feedback must be immediate and informative; poor feedback can be worse than none — distracting, uninformative, irritating, anxiety-provoking (classic Blue Screen of Death: terrifying, bold, cryptic). Nielsen: error messages in plain language (no codes), precisely indicate the problem, constructively suggest a solution — tight link with recoverability. Constantine & Lockwood feedback principle: keep users informed of actions/interpretations, changes of state, errors/exceptions through clear, concise, unambiguous language familiar to users (old BSOD fails; new one does better). Norman and C&L mean feedback generally — hence the whole feedback-cycles lesson.
- [Documentation](#L2-5-documentation) — Nielsen's last heuristic; placed last because usable design aims to avoid the need for documentation; modern users mostly won't read it unless required to use the interface. Nielsen: even though it's better without, help may be necessary — easy to search, focused on the user's task, concrete steps, not too large. Modern docs are task-framed (“what do you want to do” → steps) vs older docs listing everything an interface can do.
- [Exploring HCI: Design Principles and Heuristics](#L2-5-exploring-hci-design-principles-and-heuristics) — Gestural interfaces: constraints are hard (can't physically constrain movement) → feedback/feedforward instead. Complex domains: what does simplicity mean if the task is complex? Universal design concerns: excluding people with disabilities risks ethical and legal problems.
- [Other Sets of Principles](#L2-5-other-sets-of-principles) — 29 combined principles distilled to 15 (table shows sources). Norman's extra principle: conceptual models (own lesson). Other sets:
  - **Dix, Finlay, Abowd and Beale** — three categories: **Learnability** (how easily a user grasps an interface — discussed with mental models), **Flexibility** (how many ways it can be used), **Robustness** (feedback and error recovery).
  - **Jill Gerhardt-Powals** — principles for cognitive engineering / reducing cognitive load; useful for data processing and visualisation.
  - **Jef Raskin**, *The Humane Interface* — revolutionary design rules; not necessarily advocated, but an interesting different approach.
  - **Jim Foley et al.**, *Computer Graphics: Principles and Practice* — principles for 2D and 3D graphics.
  - **Susan Weinschenk and Dean Barker** — more holistic guidelines: linguistic and cultural sensitivity, tempo and pace, domain clarity. Many more exist.
- [Conclusion to Design Princip](#L2-5-conclusion-to-design-princip) — Lists from Norman, Nielsen, Constantine, Lockwood and the Institute for Universal Design combined into fifteen principles; guidelines not unbreakable rules; expect tensions between principles (a cool feature only experts understand; a new interaction method hard to make visible/learnable). Principles only get you so far — you still need needfinding, prototyping and evaluation.

**Keywords to search for:** 15 principles · Norman six principles · Nielsen ten heuristics · Constantine & Lockwood · Software for Use · Universal Design · Ronald Mace · Nielsen Norman Group · 29 principles · discoverability · visibility principle · Command-Shift-4 · discovering gestures · simplicity · Blue Screen of Death · parking signs · affordances · door handle · signifiers · metaphors · mapping · cut copy paste · monitor arrangement · colour meter · light switches · stove dials · perceptibility · ceiling fan chains · consistency · reuse · blue underlined links · Ctrl+Y · WordStar · Visual Basic 6 · Shift+Alt+Backspace · flexibility · accelerators · equity · password requirements · ease and comfort · tremors · structure · Wall Street Journal · constraints · soft vs hard constraint · physical / cultural / semantic / logical · Nissan Leaf · tolerance · emergency exit · recoverability · Jef Raskin · feedback for errors · documentation · Dix Finlay Abowd Beale · learnability / flexibility / robustness · Gerhardt-Powals · Foley · Weinschenk & Barker

**Jump to a section of the full text:** [Introduction to Design Principles](#L2-5-introduction-to-design-principles) · [The Sets](#L2-5-the-sets) · [Discoverability](#L2-5-discoverability) · [Quiz: Design Challenge: Discovering Gestures](#L2-5-quiz-design-challenge-discovering-gestures) · [Simplicity](#L2-5-simplicity) · [Affordances](#L2-5-affordances) · [Mapping](#L2-5-mapping) · [Quiz: Design Challenge: Mapping and Switches](#L2-5-quiz-design-challenge-mapping-and-switches) · [Perceptability](#L2-5-perceptability) · [Consistency](#L2-5-consistency) · [Consistency: The Curious Case of Ctrl+Y](#L2-5-consistency-the-curious-case-of-ctrl-y) · [Flexibility](#L2-5-flexibility) · [Equity](#L2-5-equity) · [Ease and Comfort](#L2-5-ease-and-comfort) · [Structure](#L2-5-structure) · [Constraints](#L2-5-constraints) · [Norman's Four Types of Constraints](#L2-5-norman-s-four-types-of-constraints) · [Quiz: Reflections: Constraints](#L2-5-quiz-reflections-constraints) · [Tolerance](#L2-5-tolerance) · [Feedback](#L2-5-feedback) · [Documentation](#L2-5-documentation) · [Exploring HCI: Design Principles and Heuristics](#L2-5-exploring-hci-design-principles-and-heuristics) · [Other Sets of Principles](#L2-5-other-sets-of-principles) · [Conclusion to Design Princip](#L2-5-conclusion-to-design-princip)

---

<a id="A-L3-1"></a>

## Summary — Lesson 3.1 Introduction to Methods

**Full lecture text:** [3.1 Introduction to Methods](#L3-1) · **Lecture book pages:** pp. 393–419

**In one sentence:** Opens the methods unit: user-centered design and its six ISO principles, primary/secondary/tertiary stakeholders, the four-phase design life cycle (needfinding → design alternatives → prototyping → evaluation), its relationship to feedback cycles, and qualitative vs quantitative data.

### Key points

- [Introduction to Research Methods](#L3-1-introduction-to-research-methods) — We rarely design for brand-new tasks; we design new ways to accomplish old tasks (Facebook: new way to socialise/communicate, meeting those needs better — depending who you ask). Novelty must have a purpose, grounded in a strong understanding of the user's task. Unit covers: user-centered design; the four-stage design life cycle; general methods for pursuing it; qualitative vs quantitative data.
- [User-Centered Design](#L3-1-user-centered-design) — Design that considers the user's needs throughout the entire process (“pretty much just good design”). Often design instead meets functional specifications, or designers assume they know the user without checking. UCD prioritises user needs while recognising we don't know them → involve users at every stage: examine needs in depth before starting (observe and ask), present alternatives and prototypes for feedback, evaluate near-final designs with real users. HCI principles speed this up, but guidelines alone can't produce great interfaces.
- [Principles of User-Centered Design](#L3-1-principles-of-user-centered-design) — six principles from the International Standards Organization (ISO):
  1. The design is based upon an **explicit understanding of users, tasks and environments** — gather and leverage that information throughout.
  2. **Users are involved throughout** design and development — from interviews/surveys about designs and prototypes to being on the design team.
  3. The design is **driven and refined by user-centered evaluation** — real users must evaluate prototypes and interfaces.
  4. The process is **iterative** — no tool is developed once, released and abandoned; constant iteration even after release.
  5. The design addresses the **whole user experience** — don't delineate one portion as your only interest.
  6. The design team includes **multidisciplinary skills and perspectives** — psychologists, designers, computer scientists, domain experts and more.
- [Stakeholders](#L3-1-stakeholders) — “user” isn't the only person we care about:
  - **Primary** stakeholder — uses the tool directly.
  - **Secondary** — doesn't use the system directly but interacts with its output.
  - **Tertiary** — never interacts with the tool or its output but is impacted by its existence.
  - Grade-book example (teachers send progress reports to parents): teachers primary; parents secondary (receive reports); students tertiary (affected, may never see reports). School administrators could be any level depending on setup (direct monitoring → primary; aggregated reports → secondary; no interaction → tertiary).
  - Consider impact on all: more parental access might foster involvement or enable helicopter parenting that prevents students developing metacognitive skills and self-discipline.
- [Quiz: Reflections: HCI Methods](#L3-1-quiz-reflections-hci-methods) — Alan Cooper's book *The Inmates Are Running the Asylum* (2004): technology as a dancing bear — people marvel that it dances at all, not that it dances well; same for software that works at all. Software engineers still often design UIs. Joyner's first job (between freshman and sophomore years) as UI designer for a broadcast company: engineers built a late-added configuration screen themselves — 50+ settings with 3–5 radio buttons each, no grid, illegible, unusable, but technically functional (met requirements of what, not how usable). Today UX is a differentiator: **Stash** (buy/sell small amounts of mutual funds) vs E-Trade — differentiated by automated investing, simple tracking, simplified summaries.
- [The Design Life Cycle](#L3-1-the-design-life-cycle) — four phases (general; subsumes many other versions):
  1. **Needfinding** — comprehensive understanding of the task: who the user is, context, why they do it, anything related.
  2. **Design alternatives** — multiple early ideas; avoid getting stuck on one idea too soon.
  3. **Prototyping** — build the ideas with most potential into something to put in front of users; low fidelity early (paper and pencil, verbal descriptions), refined over time.
  4. **User evaluation** (most important) — put prototypes in front of real users: likes/dislikes, what works. Then the cycle begins anew: feedback improves understanding (more needfinding), new alternatives, improved prototypes, evaluate again. Launch doesn't end the cycle — iterate with live users.
- [Methods for the Design Life Cycle](#L3-1-methods-for-the-design-life-cycle) — At every stage we gather information from users; the unit is a toolbox of methods. Many are big enough for whole courses (e.g. 3–4 minutes here on naturalistic observation vs entire textbooks) — enough to get started and know what to explore; remember the goal of understanding how big HCI is.
- [Design Life Cycles meets Feedback Cycles](#L3-1-design-life-cycles-meets-feedback-cycles) — HCI itself is a feedback cycle: user acts in an interface, judges output, repeats; we brainstorm/design interfaces, judge from evaluation output whether goals were met, repeat. Our “interface” is the tools to build and evaluate interfaces; our goal is to help users accomplish theirs.
- [Qualitative vs. Quantitative Data](#L3-1-qualitative-vs-quantitative-data):
  - **Quantitative** = anything numeric: statistical tests, summaries, formal conclusions, objective comparisons — strong for a very small class of things (narrow view).
  - **Qualitative** = everything else: descriptions, accounts, observations, natural language (open-ended survey responses, interview transcripts, bug reports, personal observations) — broader, more general picture; harder to draw formal conclusions; more prone to biases.
  - Qualitative can be converted to quantitative (count respondents mentioning course difficulty in free responses).
  - “Quantitative provides the **what**, qualitative provides the **how** or **why**.” Needfinding and early prototype evaluation → qualitative; after a few iterations → quantitative to find numeric improvements.
  - **Mixed methods** = both from the same participants for a more complete picture.
- [Quiz: Exercise: Quantitative vs Qualitative](#L3-1-quiz-exercise-quantitative-vs-qualitative) — end-of-course evaluation items:
  - Quantitative: 1–5 difficulty rating (tricky: numeric but not continuous — can't guarantee 3→4 equals 4→5; analysis more limited, still quantitative); hours per week; count of students mentioning office hours; percentage completing the survey; number of office-hours participants.
  - Qualitative: “what did you like about this course”; forum responses with non-anonymous reviews; transcript of the office-hours conversation.
- [Design Challenge: Recording MOOCS](#L3-1-design-challenge-recording-moocs) — Running design challenge for the methods unit: improving the MOOC recording process (close to home for Joyner).
- [Exploring HCI: HCI Methods](#L3-1-exploring-hci-hci-methods) — Brainstorm a conceptual plan for the design life cycle in your area: ed-tech → many stakeholders (students, parents, teachers, administrators); VR/wearables → technical constraints and creative workarounds; CSCW → study where the phenomenon exists (Wikipedia, distributed companies).
- [Conclusion to Introduction to Methods](#L3-1-conclusion-to-introduction-to-methods) — Four-step cycle: needfinding → design alternatives → prototyping → user evaluation → repeat; goal is user-centered design; rest of unit fills the toolbox with tools for the right data at the right time.

**Keywords to search for:** user-centered design · ISO six principles · iterative · whole user experience · multidisciplinary · stakeholders primary / secondary / tertiary · grade book · helicopter parenting · Inmates Are Running the Asylum · Alan Cooper · dancing bear · configuration screen 50 settings · Stash · design life cycle · needfinding · design alternatives · prototyping · user evaluation · toolbox · qualitative · quantitative · what vs how/why · mixed methods · 1 to 5 scale · Recording MOOCs

**Jump to a section of the full text:** [Introduction to Research Methods](#L3-1-introduction-to-research-methods) · [User-Centered Design](#L3-1-user-centered-design) · [Principles of User-Centered Design](#L3-1-principles-of-user-centered-design) · [Stakeholders](#L3-1-stakeholders) · [Quiz: Reflections: HCI Methods](#L3-1-quiz-reflections-hci-methods) · [The Design Life Cycle](#L3-1-the-design-life-cycle) · [Methods for the Design Life Cycle](#L3-1-methods-for-the-design-life-cycle) · [Design Life Cycles meets Feedback Cycles](#L3-1-design-life-cycles-meets-feedback-cycles) · [Qualitative vs. Quantitative Data](#L3-1-qualitative-vs-quantitative-data) · [Quiz: Exercise: Quantitative vs Qualitative](#L3-1-quiz-exercise-quantitative-vs-qualitative) · [Design Challenge: Recording MOOCS](#L3-1-design-challenge-recording-moocs) · [Exploring HCI: HCI Methods](#L3-1-exploring-hci-hci-methods) · [Conclusion to Introduction to Methods](#L3-1-conclusion-to-introduction-to-methods)

---

<a id="A-L3-2"></a>

## Summary — Lesson 3.2 Ethics and Human Research

**Full lecture text:** [3.2 Ethics and Human Research](#L3-2) · **Lecture book pages:** pp. 420–455

**In one sentence:** Research ethics for human-subjects work: the history behind Institutional Review Boards (Milgram, Tuskegee, Stanford prison, National Research Act 1974, Belmont Report), why ethics also improves data quality, the Georgia Tech CITI/IRB protocol process step by step, and ethics in industry (Facebook emotional-contagion study, Jackman & Kanerva).

### Key points

- [Introduction to Research Ethics](#L3-2-introduction-to-research-ethics) — Before working with real users: ethical considerations. At a university they're part of your contract; in industry obligations still apply. Important to preserve users' rights **and** to ensure the value of the data gathered. Lesson covers origins, basic considerations, and the IRB (Institutional Review Board) that governs human-subjects research.
- [Origin of Institutional Review Board](#L3-2-origin-of-institutional-review-board) — unethical experiments in the first half of the 20th century (Axis scientists in WWII, and in the US):
  - **Milgram's obedience experiment** — participants tricked into thinking they administered lethal shocks, to test obedience.
  - **Tuskegee syphilis study** — rural African American men intentionally injected with syphilis to study progression.
  - **Stanford prison experiment** — participants psychologically abused to test limits/behaviour.
  - Response: **National Research Act of 1974** → creation of IRBs to oversee university research. The **Belmont Report** summarises basic ethical principles research must follow to receive government support: benefits to society must outweigh risks to subjects; subjects selected fairly (direct response to Tuskegee); rigorous **informed consent** (know what they're getting into, can back out any time).
- [The Value of Research Ethics](#L3-2-the-value-of-research-ethics) — Not just bureaucracy. IRB's main task: ensure potential benefits are worth potential risks — including ensuring benefits are significant and data useful. IRB is sensitive to the **perception of coercion** (coerced participants give skewed data); watches for inherent biases, demanding too much, questions known to affect results. Training is about doing good research, not just ethical research; recording who is certified ensures personnel understand the basics. If research isn't useful, even the smallest risk outweighs nonexistent benefits.
- [Getting Started: CITI Training](#L3-2-getting-started-citi-training) — University projects/classes need IRB approval; processes differ by university (Georgia Tech shown). GT IRB site: researchintegrity.gatech.edu/irb → “Required training” → link to **CITI training** → log in with GT account → complete **Group 2: Social and Behavioral Research Investigators and Key Personnel** → receive completion report → ready for IRB.
- [Getting Started: IRB](#L3-2-getting-started-irb) — GT tool: **IRBWISE**. “My protocols” lists protocols you're added to. A **protocol** = description of a research project outlining IRB-approved procedures (consent, recruitment, experimentation…). Lists: approved; new/unsubmitted; waiting for IRB action; **amendments** (how you change an approved protocol — add researchers or change what's approved; must be submitted and accepted separately).
- [IRB Protocols: Basics](#L3-2-irb-protocols-basics) — You may just be added to an existing protocol but must understand what it permits. Draft protocol example: user study on people who exercise. Protocol fields:
  1. **Title** and certified personnel (required just to save).
  2. **Study personnel**: name, role, attach certification; the **Primary Investigator (PI)** must be added first and must be a faculty member.
  3. **Protocol description**: high-level — what will be done, goal, what subjects do.
  4. **Research design and methodology**: what users experience and in what order; experimental details such as assignment to conditions; **duration of participation** (not asking too much).
  5. **Data collection methods**: surveys, pre/post-tests, interview scripts — anything pre-prepared to elicit data.
  6. **Potential benefits** (must outweigh risks; can be to the community, not just participants).
  7. **Risks** (for usability studies usually those of normal computer work, but must be addressed).
  8. **Statistical analysis plan** (qualitative research may have none).
  9. **Start and end dates** (often data-collection phase + analysis phase). Remaining options (clinical, external funding) usually not applicable.
- [IRB Protocols: Human Subject Interaction](#L3-2-irb-protocols-human-subject-interaction) — answer “yes” to direct interaction, then describe subjects and data:
  1. **Number of subjects and genders** — don't waste participants' time if you won't analyse their data; be fair to genders (early research over-represented males).
  2. **Vulnerable populations** — people who may lack capacity for true informed consent; special accommodations.
  3. **Scientific justification for the number** — statistical tests: participants needed for an effect size; qualitative: smaller, based on perspectives needed; or external limits (class size).
  4. **Inclusion and exclusion criteria** — often inverses, sometimes specific (undergraduate CS education: include undergraduates; exclude those who already took a CS class).
  5. Skip clinical questions; provide steps to protect **rights and welfare of vulnerable populations** (e.g. how 10-year-olds understand they can opt out).
  6. **Recruitment procedures** — what you'll say, how you'll communicate; whether using the **Georgia Tech subject pool**; **compensation** (often none; funded studies may pay; subject pool often = extra credit in a psychology class). Recruitment matters especially in classroom research — instructor recruiting own students must make clear non-participation won't come back to haunt them.
- [IRB Protocols: Consent Procedures](#L3-2-irb-protocols-consent-procedures) — consent is one of the most important elements (from the Belmont Report):
  - Kind of consent: most commonly **written consent required** (signed or digitally signed form).
  - **Waiver of consent** — narrow circumstances where subjects aren't directly affected: already-generated anonymised educational/health data; non-identifying observation of a coffee-house ordering process.
  - **Waiver of documentation of consent** — low-risk research where the signed form would be the only record of identity (surveys, unrecorded interviews): inform of rights at the start; continued participation = implied consent.
  - Justification if a waiver is requested; plan for obtaining informed consent (form at start; clear they can withdraw at any time); extra boxes for children, non-English speakers, at-risk populations; assess **continuing consent** (continued participation = implied continued consent).
  - **Deception or concealment** — e.g. telling participants an interface works when a person behind the scenes supplies responses (testing a new Siri with hand-written responses); must be indicated.
  - Upload consent forms — GT Office of Research Integrity Assurance provides templates; disclose what is researched, why, how, why they were invited.
- [IRB Protocols: Wrapping Up](#L3-2-irb-protocols-wrapping-up) — Remaining relevant field: **Data management** — how participant data and identifying information are stored and safeguarded (password protection, encryption). Standard questions: Department of Defense involvement (no), radiation (no), nanotechnology (Joyner hopes one day). Upload additional documents (interview script, survey, recruitment script). Save and Continue → preview everything → declare/report conflicts of interest → Save & Continue → submit to your PI (Joyner is the PI, sees something different). IRB usually responds in about **three weeks** with acceptance or required changes.
- [Research Ethics and Industry](#L3-2-research-ethics-and-industry) — IRBs govern institutions receiving federal support. Companies research users constantly (rapid A/B experiments); much wouldn't pass a university IRB. **Facebook** paper “Experimental evidence of massive-scale emotional contagion through social networks”: tweaked news feeds to see if they could manipulate users' moods. Facebook: consistent with its data-use policy. Social scientists: not informed consent — informed consent is **specific** to an experiment, **temporary** for a known period, and **given without coercion**; “if you don't agree you can't use Facebook” may be coercion.
- [Quiz: Exercise: Research Ethics and Industry](#L3-2-quiz-exercise-research-ethics-and-industry) — was the Facebook study ethical?
  - Reasons “yes”: terms of service covered it (users agreed); Facebook has an internal IRB that reviewed it; an external IRB also reviewed it.
  - Reasons “no”: studies show users don't read terms of use — ethical obligation to make them aware; users couldn't opt out (only by deactivating the whole account — and they didn't know when the study started); users weren't notified they were participants or when it began/ended.
  - Fixes: separate the research consent process from the rest of Facebook; request explicit opt-in and alert users when the study ends (without revealing what was manipulated). Even if ethical, these could have reduced backlash — but might have affected results. These are the trade-offs. Joyner gives no right/wrong answer.
- [Paper Spotlight: "Evolving the IRB: Building Robust Review for Industry Research"](#L3-2-paper-spotlight-evolving-the-irb-building-robust-review-for-industry-research) — **Molly Jackman and Lauri Kanerva** (Facebook employees), Washington and Lee Law Review. Academic ethical guidelines don't always address industry considerations → advocate a new set of principles and practices specifically for industry rather than ignoring the non-applicable parts. Facebook's internal process relies on deferring to a research-area expert (external reviewer) who decides whether additional review or an external IRB is needed — replicating IRB's key property of reviewers with no incentive to permit an unethical study. Companies aren't legally bound by the Belmont Report (universities with federal funding are) → companies govern themselves; at a company without such a programme you must apply the standards yourself.
- [Conclusion to Research Ethics](#L3-2-conclusion-to-research-ethics) — Research ethics protect participants' rights and ensure good, useful data. Keep respect for participants at the forefront at every stage: be wary of experiments that might negatively affect users; only ask users to spend time on well-thought-out interfaces; respect users' viewpoints and position in the design process.

**Keywords to search for:** IRB · Institutional Review Board · Milgram · Tuskegee · Stanford prison · National Research Act 1974 · Belmont Report · informed consent · benefits outweigh risks · fair selection · perception of coercion · CITI training · Group 2 Social and Behavioral · IRBWISE · protocol · amendment · Primary Investigator faculty · duration of participation · vulnerable populations · inclusion / exclusion criteria · Georgia Tech subject pool · compensation / extra credit · written consent · waiver of consent · waiver of documentation of consent · implied continued consent · deception / concealment · data management · three weeks · Facebook emotional contagion · A/B experiments · specific / temporary / without coercion · opt-in · Jackman & Kanerva · Washington and Lee Law Review

**Jump to a section of the full text:** [Introduction to Research Ethics](#L3-2-introduction-to-research-ethics) · [Origin of Institutional Review Board](#L3-2-origin-of-institutional-review-board) · [The Value of Research Ethics](#L3-2-the-value-of-research-ethics) · [Getting Started: CITI Training](#L3-2-getting-started-citi-training) · [Getting Started: IRB](#L3-2-getting-started-irb) · [IRB Protocols: Basics](#L3-2-irb-protocols-basics) · [IRB Protocols: Human Subject Interaction](#L3-2-irb-protocols-human-subject-interaction) · [IRB Protocols: Consent Procedures](#L3-2-irb-protocols-consent-procedures) · [IRB Protocols: Wrapping Up](#L3-2-irb-protocols-wrapping-up) · [Research Ethics and Industry](#L3-2-research-ethics-and-industry) · [Quiz: Exercise: Research Ethics and Industry](#L3-2-quiz-exercise-research-ethics-and-industry) · [Paper Spotlight: "Evolving the IRB: Building Robust Review for Industry Research"](#L3-2-paper-spotlight-evolving-the-irb-building-robust-review-for-industry-research) · [Conclusion to Research Ethics](#L3-2-conclusion-to-research-ethics)

---

<a id="A-L3-3"></a>

## Summary — Lesson 3.3 Needfinding and Requirements Gathering

**Full lecture text:** [3.3 Needfinding and Requirements Gathering](#L3-3) · **Lecture book pages:** pp. 456–502

**In one sentence:** First stage of the design life cycle: the data inventory (seven questions), problem space and user types, five biases to avoid, needfinding methods from low to high intervention (naturalistic observation, participant observation, hacks & workarounds, errors, apprenticeship/ethnography, interviews & focus groups, think-aloud, surveys, existing interfaces/reviews/logs), then representing the need and defining requirements.

### Key points

- [Introduction to Needfinding](#L3-3-introduction-to-needfinding) — Needfinding = requirements gathering: find out what the user really needs. Biggest designer mistake: jumping to design before understanding the user or task. Enter with as few preconceived notions as possible (“when all you have is a hammer, everything looks like a nail”). Lesson: define general questions → methods to answer them → formalise into a shareable task model and a requirements list.
- [Data Inventory](#L3-3-data-inventory) — questions to be able to answer at the end (each needfinding activity should map to one or more):
  1. **Who are the users?** — ages, genders, levels of expertise.
  2. **Where are the users?** — their environment.
  3. **What is the context of the task?** — what else competes for attention.
  4. **What are their goals?** — what they're trying to accomplish.
  5. **Right now, what do they need?** — physical objects, information, collaborators.
  6. **What are their tasks?** — physically, cognitively, socially.
  7. **What are the subtasks?** — how they accomplish them.
- [The Problem Space](#L3-3-the-problem-space) — Identify where the task occurs, what else is going on, explicit and implicit needs. Alarm example: same task (turning off the alarm) viewed narrowly (user–interface interaction) vs broadly (whole problem space); zoom out further → why people need alarm systems at all → could lead to dorm-room security or office check-in systems. Take the broad approach. Methods are presented from the most authentic/general observation to progressively more targeted.
- [User Types](#L3-3-user-types) — Understand the full range of users: audiobook app for exercisers — kids or adults? expert or novice exercisers? expert or novice audiobook listeners? Business people who want to exercise while reading vs exercisers who want something else while exercising — similar task, different audiences/motivations/needs. **Sony Walkman** succeeded by identifying different needs for different types of people, designing for all, and marketing to each type (see *Doing Cultural Studies*, Hugh Mackay and Linda Janes).
- [5 Tips: Avoiding Bias in Needfinding](#L3-3-5-tips-avoiding-bias-in-needfinding):
  1. **Confirmation bias** — seeing what we want to see, noticing only what confirms prior beliefs. Avoid: look for signs you're wrong, test beliefs empirically, involve multiple people.
  2. **Observer bias** — subconsciously biasing users (more helpful with your own interface; leading survey phrasing). Avoid: separate experimenters with motives from participants, heavily script interactions, have someone else review scripts/surveys for leading questions.
  3. **Social desirability bias** — people are nice; if they know you designed it they'll say nice things. Avoid: hide the socially desirable response, more naturalistic observation, record objective data.
  4. **Voluntary response bias** — people with stronger opinions respond more (online reviews cluster at 5 and 1) → quantitative survey analysis oversamples extremes. Avoid: limit how much survey content is shown before starting; confirm conclusions with other methods.
  5. **Recall bias** — people are poor at recalling what they did/thought/felt. Avoid: set tasks in context, think-aloud during activities, interview during the activity.
  6. All biases are further controlled by using multiple forms of needfinding.
- [Naturalistic Observation](#L3-3-naturalistic-observation) — Simply watch people in their natural context (Joyner watches exercisers in the park from his porch). Start with specific observations and generalise (avoids confirmation bias). Observations: many exerciser types (walkers, joggers, runners, rollerbladers, yoga, leisurely vs strenuous bikers); bikers can't stop/start easily → avoid designs requiring pulling out the phone; groups vs individuals (would groups want this? — note as a question); people stretch before/after → possible start/end sequence. Limits: ethically can't interact or capture identifying video/photos; don't know what users are thinking → gives questions to ask later.
- [5 Tips: Naturalistic Observation](#L3-3-5-tips-naturalistic-observation):
  1. **Take notes** — be prepared to get targeted information, don't just sit and watch.
  2. **Start specific and then abstract** — write individual actions before interpreting/summarising; summarising too soon risks tunnel vision.
  3. **Spread out your sessions** — several 10–15-minute sessions rather than two hours once; reflection informs later sessions.
  4. **Find a partner** — observe together, take separate notes, compare interpretations.
  5. **Look for questions** — observation should generate questions for more targeted needfinding, not all the answers.
- [Participant Observation](#L3-3-participant-observation) — Experience the task yourself (Joyner jogs with an audiobook and a mic). Learned: he's out of shape; the app would help anyone doing participant observation (kept stopping to record notes); unexpected events made him want to go back in the book / hear things again; wanted to re-listen at home to take notes; sometimes a note, sometimes just a bookmark. Caution: **you are not your user** — don't over-represent your own experience; use it to inform what you ask users.
- [Hacks and Workarounds](#L3-3-hacks-and-workarounds) — Get inside users' heads by looking at how they use interfaces in unintended ways or break out of the interface. Workspace example: six monitors yet Post-It notes on the computer — they can't be covered, don't take screen space, visible when the computer is off: a hack around interface limitations. Don't just observe hacks and assume why — ask why they don't use the existing interface (maybe they don't know about it — a different design challenge). Related: **errors** — slips or mistakes users frequently make within the interface.
- [Errors](#L3-3-errors) — errors reveal improvements and the user's mental model:
  - **Slip** — mental model is right but execution fails: Joyner types into the wrong window because email is the active window, firing hotkeys that tag/delete random emails.
  - **Mistake** — mental model is weak: the Mac maximise button (sometimes full screen, sometimes slightly larger, sometimes a full-screen mode) vs PC's always-full-screen.
  - Method: watch people performing tasks and ask why things happen. More interaction than watching in the wild; approaching exercisers in public is awkward → recruit people to come in and describe experiences, or participate during their routine (notes/thinking aloud), or go to the extreme: apprenticeship.
- [Apprenticeship and Ethnography](#L3-3-apprenticeship-and-ethnography) — For particularly complex tasks, talking/observing isn't enough; become an expert yourself. Informed by **ethnography**: research a community/job by becoming a participant — beyond participant observation, integrating oneself and developing expertise. Udacity video editors' workflow (multiple programmes, workflows, people) can't be understood in an hour; Joyner would need to train under them, combining his HCI expertise with developed domain expertise. Huge fields on their own; resources provided.
- [Interviews with Focus Groups](#L3-3-interviews-with-focus-groups) — Most targeted: just talk to users. Morgan interview: biggest challenge is control — headphone button only pauses/plays; anything else means stopping, pulling out and unlocking the phone to rewind. Interviews get at what users think during a task; one-on-one or in groups → **focus groups** elicit information interviews don't, but risk overly **convergent thinking** (people agree rather than bring new ideas) → use alongside interviews and other techniques.
- [5 Tips: Interviews](#L3-3-5-tips-interviews):
  1. **Focus on the six W's** — who, what, where, when, why, how; avoid one-word or yes/no questions (better via surveys); open-ended, semi-structured questions.
  2. **Be aware of bias** — phrasing and interactions (only smiling when they say what you want biases them to agree).
  3. **Listen** — don't turn it into a conversation; the participant does the vast majority of talking; don't reveal anything that predisposes them to agree.
  4. **Organize the interview** — introduction, lighter questions to build trust, a summary at the end; be ready to push forward or pull back on track.
  5. **Practice** — rehearse on friends, family, research partners; subjects are hard to get, so make the most of them.
- [Quiz: Exercise: interviews](#L3-3-quiz-exercise-interviews) — six questions; three are good:
  - “Do you exercise?” — bad: yes/no. Better: “How often do you exercise?” (subsumes it, leaves room for detail) — good.
  - “Do you exercise for health or for pleasure?” — bad: false dichotomy (maybe social). Better: “Why do you exercise?”
  - “What, if anything, do you listen to while exercising?” — good. “What device do you use to listen…?” — good (doesn't assume smartphone).
  - “We're developing an app for listening to audiobooks while exercising. Would that be interesting to you?” — bad: **social desirability bias** (“great idea David, but I'd never use it” — nobody says that). Better: “Would you be interested in an app for listening to audiobooks while exercising?” — more collaborative, they feel they should say now if it's a bad idea.
- [Think-Aloud](#L3-3-think-aloud) — Like interviews but in the context of the task: Morgan thinks out loud while exercising and listening (voice recorder in the field; in a lab for computer tasks). Captures thoughts users forget afterwards. Danger: thinking aloud makes people act more deliberately and can change behaviour → check where behaviour differs. Alternative: **post-event protocol** — gather thoughts immediately after the activity; still fresh, less effect on performance.
- [Surveys](#L3-3-surveys) — Other methods are high effort for little data or few users (an hour for one interview). Surveys get many responses quickly, objectively phrased questions for quicker interpretation, administered asynchronously online at low cost (Joyner: idea Friday morning, IRB cooperation, survey sent within 24 hours, 150 responses in a week). Less thorough than interviews, but powerful for breadth and for deciding what to ask in interviews/focus groups.
- [5 Tips: Surveys](#L3-3-5-tips-surveys) — survey design is like interface design:
  1. **Less is more** — the biggest novice mistake is asking too much (hurts response rate and reliability); ask the minimum, only what you'll use.
  2. **Be aware of bias** — positive/negative connotations; implicit pressure to answer one way.
  3. **Tie them to the inventory** — every question connects to data you want; start from the goals and write questions from there.
  4. **Test it out** — colleagues pretend to be users; check you'd get the data you need.
  5. **Iterate** — test, see what works, revise; let participants give feedback on the survey itself.
- [Quiz: Exercise: Surveys](#L3-3-quiz-exercise-surveys) — intentionally bad survey, problems:
  - “Scale of 1 to 4, 1 = a lot, 4 = not at all” — what do 2 and 3 mean? Endpoints alone don't define a scale; usually use an **odd** number of options for a neutral middle (unless deliberately forcing a side).
  - Second scale is 1–6 — don't change the number of options between questions; and the scale direction is **reversed** (low = a lot vs high = a lot) — be consistent in direction and number of options.
  - “Why do you like to exercise?” — leading; assumes they like it.
  - “Have you listened to an audiobook this year?” — yes/no; “yes” hides 1 vs 100 audiobooks → make it open-ended.
- [Other Data Gathering Methods](#L3-3-other-data-gathering-methods):
  - Critique **existing interfaces** with evaluation methods (take-out ordering: phone, mobile, website).
  - Read **user reviews** of existing products (dozens of alarm-clock apps, thousands of reviews).
  - Use existing **interaction logs** (browser that anticipates what you'll open next — trends within and across users).
  - Be creative; use a variety of methods to paint a complete picture.
- [Quiz: Exercise: Needfinding Pros and Cons](#L3-3-quiz-exercise-needfinding-pros-and-cons) — methods: Naturalistic Observation, Participant Observation, Errors & Hacks, Interviews, Surveys, Focus Groups, Apprenticeship, Think-Aloud. Joyner's answers (relative):
  - **Analyzes data that already exists**: naturalistic observation (data produced on its own) and errors & hacks.
  - **Requires no recruitment**: naturalistic observation and participant observation (errors & hacks still need permission to view workspaces).
  - **Requires no synchronous participation**: surveys (exceptions possible: retrospective errors/hacks, written think-aloud) — why surveys scale.
  - **Investigates the participant's thoughts**: almost all when used correctly — except naturalistic observation.
  - **Occurs within the task context**: naturalistic and participant observation (but no access to real users' heads); apprenticeship and think-aloud capture the benefit best; interviews/focus groups can but usually don't; errors & hacks debatable (they occur in context, analysis doesn't).
  - **Cheaply gathers lots of users' data**: surveys only; everything else is expensive or small-scale (participant observation is cheap but one person).
- [Quiz: Design Challenge: Needfinding for Book Reading](#L3-3-quiz-design-challenge-needfinding-for-book-reading) — The other half of the picture: understand book-reading on its own (not a full life cycle — no prototyping for readers). Any method applies: watch readers taking notes in a library; reflect on ourselves (carefully); interviews/surveys/think-alouds (participants easy to find). Challenge: who are the users? Everyone who reads deliberately (sample widely) or a subset first (students, busy business people, people who walk/bike to work), abstracting later — eventually anyone who can't read/take notes traditionally (drivers, visually impaired). Define the user and task and design for them deliberately.
- [Iterative Needfinding](#L3-3-iterative-needfinding) — Needfinding can be its own cycle: observation (many joggers use one earphone) → interview (why? to hear cars/people in busy areas) → survey (how widespread?) → a split in results informs the next observation (which environments). Prototyping/evaluation also feed back into needfinding; the output of evaluation is more needfinding — don't do one needfinding stage then just ping-pong between prototyping and evaluation.
- [Revisiting the Inventory](#L3-3-revisiting-the-inventory) — After combining approaches (observed, asked, tried), pay attention to conflicting data: do you understand something users don't, or is your expertise still immature? Revisit the seven inventory questions (who, where, context, goals, needs, tasks, subtasks) with the data in mind.
- [Representing the Need](#L3-3-representing-the-need) — formalise understanding into something usable in design:
  - Step-by-step **task outline**, broken into subtasks down to the operator level.
  - Develop into a **hierarchical network** (more complex than a linear series).
  - Augment with a **diagram of structural relationships** among system components (how feedback reaches the user, how they interact).
  - Develop into a **flow-chart** with decision points and interruptions.
  - These resemble the outcomes of task analyses from the principles unit; can summarise into a comprehensive task analysis for design and prototyping.
- [Defining the Requirements](#L3-3-defining-the-requirements) — final needfinding step: requirements the final interface must meet — specific and evaluatable; may include non-task components from project requirements. User-task requirements:
  - **Functionality** — what the interface can do.
  - **Usability** — how interactions must work.
  - **Learnability** — how fast users can start using it.
  - **Accessibility** — who can use it.
  - External project requirements: **compatibility** (devices), **compliance** (privacy), **cost**, etc. Used to evaluate interfaces going forward.
- [Exploring HCI: Needfinding](#L3-3-exploring-hci-needfinding) — Technological innovation (AR/VR): initial phase similar — observe how people perform tasks now, naturalistically; later bring participants in to experience devices. Healthcare/education: wealth of naturalistic observation and existing interfaces to leverage. Always start with real users: observe in the wild, talk directly, or look at data they've generated.
- [Conclusion](#L3-3-conclusion) — Needfinding builds understanding of tasks, context, what else is going on, what users think and hold in working memory. Techniques from low to high intervention: observe in the wild / become a user; look closely at workspaces for errors and hacks or existing data; interact directly via surveys, interviews, focus groups; work alongside them developing expertise. Next: brainstorming design alternatives.

**Keywords to search for:** needfinding · requirements gathering · hammer and nail · data inventory · seven questions who/where/context/goals/needs/tasks/subtasks · problem space · alarm · user types · Sony Walkman · Doing Cultural Studies · confirmation bias · observer bias · social desirability bias · voluntary response bias · recall bias · naturalistic observation · porch / park · participant observation · you are not your user · hacks and workarounds · Post-It notes · errors · slip · mistake · Mac maximize button · apprenticeship · ethnography · video editors · interviews · focus groups · convergent thinking · six W's · think-aloud · post-event protocol · surveys · 150 responses · less is more · odd number of options · reversed scale · leading question · user reviews · logs · pros and cons table · iterative needfinding · one earphone · task outline · hierarchical network · flow-chart · requirements · functionality / usability / learnability / accessibility · compatibility / compliance / cost

**Jump to a section of the full text:** [Introduction to Needfinding](#L3-3-introduction-to-needfinding) · [Data Inventory](#L3-3-data-inventory) · [The Problem Space](#L3-3-the-problem-space) · [User Types](#L3-3-user-types) · [5 Tips: Avoiding Bias in Needfinding](#L3-3-5-tips-avoiding-bias-in-needfinding) · [Naturalistic Observation](#L3-3-naturalistic-observation) · [5 Tips: Naturalistic Observation](#L3-3-5-tips-naturalistic-observation) · [Participant Observation](#L3-3-participant-observation) · [Hacks and Workarounds](#L3-3-hacks-and-workarounds) · [Errors](#L3-3-errors) · [Apprenticeship and Ethnography](#L3-3-apprenticeship-and-ethnography) · [Interviews with Focus Groups](#L3-3-interviews-with-focus-groups) · [5 Tips: Interviews](#L3-3-5-tips-interviews) · [Quiz: Exercise: interviews](#L3-3-quiz-exercise-interviews) · [Think-Aloud](#L3-3-think-aloud) · [Surveys](#L3-3-surveys) · [5 Tips: Surveys](#L3-3-5-tips-surveys) · [Quiz: Exercise: Surveys](#L3-3-quiz-exercise-surveys) · [Other Data Gathering Methods](#L3-3-other-data-gathering-methods) · [Quiz: Exercise: Needfinding Pros and Cons](#L3-3-quiz-exercise-needfinding-pros-and-cons) · [Quiz: Design Challenge: Needfinding for Book Reading](#L3-3-quiz-design-challenge-needfinding-for-book-reading) · [Iterative Needfinding](#L3-3-iterative-needfinding) · [Revisiting the Inventory](#L3-3-revisiting-the-inventory) · [Representing the Need](#L3-3-representing-the-need) · [Defining the Requirements](#L3-3-defining-the-requirements) · [Exploring HCI: Needfinding](#L3-3-exploring-hci-needfinding) · [Conclusion](#L3-3-conclusion)

---

<a id="A-L3-4"></a>

## Summary — Lesson 3.4 Design Alternatives

**Full lecture text:** [3.4 Design Alternatives](#L3-4) · **Lecture book pages:** pp. 503–541

**In one sentence:** Second stage of the design life cycle: generate lots of ideas (individual brainstorming first, then group brainstorming with rules), then flesh them out and narrow to 3–4 alternatives using personas, user profiles, timelines, scenarios/storyboards and user modeling.

### Key points

- [Introduction to Design Alternatives](#L3-4-introduction-to-design-alternatives) — After understanding needs, brainstorm how to accomplish the task. Design is hard: unprecedented range of choices (desktops, laptops, tablets, smartphones, smartwatches, AR, VR, 2D, 3D, gesture, pen, keyboard, mouse, voice). Lesson: generating ideas, then exploring them to decide what to pursue.
- [The Second Biggest Mistake](#L3-4-the-second-biggest-mistake) — Biggest: designing before understanding users/task. **Second biggest: settling on a single design idea or genre too early.** Forms: staying too allegiant to existing designs (tweaking a thermostat never invents the Nest — distance yourself from existing solutions initially); or, for new tasks, sketching buttons while observing exercisers → tunnel vision, missing voice/gesture alternatives. Feels like a waste to develop interfaces you won't use, but exploring ideas you leave behind teaches you about the problem and makes you better at the ones you pursue; the final design is likely a combination (security system: keypad + key chain integrated). Design = iterative brainstorming, combining, abandoning, revising, improving — needs several ideas to start.
- [The Design Space](#L3-4-the-design-space) — Problem space (e.g. disabling a security system when entering a home) defined as far from current interfaces as possible; **design space** = the area in which we design solutions (currently wall-mounted devices and key chains; could expand to voice, mobile phones, wearables). Goal of this phase: explore and grow the space of possible designs; don't narrow too early.
- [Individual Brainstorming 1](#L3-4-individual-brainstorming-1) — Generate a lot of short, high-level ideas (not even necessarily interfaces). Research says start **individually**, not in meetings — groups coalesce around ideas early, whereas brainstorming needs volume. Each idea a few words or a sentence; don't judge; write everything. Vary interaction types (gesture, voice, touch), interfaces (smartwatch, tablet, AR), audiences (novice/expert, kids/adults); get silly (design for your dog, your cat, someone with three arms or one arm). Ideas load into your mind and resurface later.
- [Individual Brainstorming 2](#L3-4-individual-brainstorming-2) — Joyner's demo list for exercisers consuming books and taking notes: voice commands, gestures, voice transcription; separated feedback methods from interaction methods; crazy ideas: on-skin interface, augmented reality (Google Glass), portable keyboard (Twiddler). Messy is good; nothing crumpled or rejected (one cross-out was a wrong word).
- [5 Tips: Individual Brainstorming](#L3-4-5-tips-individual-brainstorming):
  1. **Write down the core problem** — keep it visible; divergent thinking while staying grounded.
  2. **Constrain yourself** — require at least one idea in several categories (Joyner: at least three using non-traditional interaction like touch/voice); force ideas that are too expensive or physically impossible.
  3. **Aim for 20** — don't stop before twenty one-sentence ideas; prevents tunnel vision on an early idea.
  4. **Take a break** — not ten minutes; stop and continue a couple of days later, ready to note ideas as they come.
  5. **Divide and conquer** — split the problem (e.g. take/review notes; control playback hands-free) and brainstorm each.
- [Challenges in Group Brainstorming](#L3-4-challenges-in-group-brainstorming) — Thompson (2008): four blocking behaviours, plus Joyner's fifth:
  1. **Social loafing** — people work less hard in groups; responsibility feels shared/deflected.
  2. **Conformity** — groups want to agree → convergent thinking, fewer and less varied ideas (brainstorming needs divergent thinking).
  3. **Production blocking** — dominant individuals make it hard for others to be heard; ideas win by volume, not strength.
  4. **Performance matching** — people converge in passion/performance → loss of momentum; usually saps the enthusiastic.
  5. **Power dynamics / biases** (Joyner's addition) — tacit pressure to build on the boss's suggestions; literature on gender, age, race biases in group sessions.
  6. Don't avoid group brainstorming — enter with strategies to address these, ideally after individual brainstorming.
- [Rules for Group Brainstorming](#L3-4-rules-for-group-brainstorming) — Osborn (1957), four rules:
  1. **Expressiveness** — share any idea out loud, however strange.
  2. **Nonevaluation** — no criticising or evaluating ideas yet.
  3. **Quantity** — as many as possible; more ideas → greater chance of a novel one.
  4. **Building** — don't criticise, but build on others' ideas.
- Oxley, Dzindolet and Paulus (1996), four more:
  1. **Stay focused** — keep the goal in mind.
  2. **No explaining ideas** — say it and move on; no justifying.
  3. **When you hit a roadblock, revisit the problem** — say it again out loud.
  4. **Encourage others** — prompt those not speaking.
  5. All eight prescribe individual behaviour and only work if everyone follows them: cover them, post publicly, call each other on breaking them.
- [5 Tips: Group Brainstorming](#L3-4-5-tips-group-brainstorming) — about the design of the activity:
  1. **Go through every individual idea** — individual brainstorming beforehand; explicitly cover each idea so no early convergence and everyone is heard.
  2. **Find the optimal size** — social loafing comes from lack of individual responsibility; generally no more than **five** people; use intermediate groups that pass ideas along if more perspectives are needed.
  3. **Set clear rules for communication** — a 20-second timer per speaker so nobody blocks others.
  4. **Set clear expectations** — enthusiasm wanes without knowing the session length or end condition; set a time or a number of ideas so people can assess where they are.
  5. **End with ideas, not decisions** — leave with several ideas, let them percolate, choose later.
- [Fleshing Out Ideas](#L3-4-fleshing-out-ideas) — Brainstorming yields many high-level alternatives (a few words each). Next: flesh out into **three or four** ideas worth prototyping. Some dismissed quickly (fine — good ideas need many ideas), some explored a little first, some combined. Rest of the lesson: thought experiments to decide what to keep, combine, dismiss.
- [Personas](#L3-4-personas) — Create actual characters representing users: name, face, details so you can mentally simulate (“what would Anika do?”; what's she thinking before exercising; what interrupts her) plus domain-specific info (why/when she exercises, books she likes, how she feels, where). Create at least **three or four** quite different personas (more if many stakeholders) representing the range of real people; ask how each would feel about each alternative.
- [User Profiles](#L3-4-user-profiles) — Personas = few characters reasoned about empathetically; user profiles = formulaically generate many by defining variables: novice vs expert; casual vs serious readers; highly motivated vs easily discouraged; high vs casual technological literacy; frequent vs occasional use. Frequent users → efficiency (may rely on more knowledge); occasional users → everything discoverable and visible (every return is like the first time). Both → very efficient yet discoverable methods, or two sets (menu Copy/Paste + hotkeys). Inexperienced designers either design for everybody (rarely works) or for no one in particular (parts good for different users, whole good for none). Understand the range and make sure it's feasible.
- [Timeline](#L3-4-timeline) — Stretch a persona over time (also called **journey maps**, though those cover much longer spans — the person's whole life/motivation; timelines are narrower, the period of interacting with the task). Anika: what sparks exercising → set-up (goes somewhere) → sets up audiobook, presses play, headphones in → exercise period → turns audiobook off. Questions: what prompts the task, what leads up to it, how they feel at every stage, how each alternative affects the experience. If Anika dislikes exercising, she's glum and low-motivation — a frustrating app could turn her off exercising entirely; if she loves it, she may forget to start the audiobook → build in a location-based reminder. Also explores differences between users (Anika loves exercising, Paul hates it).
- [Scenarios and Storyboards](#L3-4-scenarios-and-storyboards) — Timelines are general/routine; **scenarios** are specific interactions and events to handle; **storyboards** are sequences of drawings of a scenario. Example: Morgan jogging, a fire engine passes, she misses 30 seconds — how does she recover? Touch: stop, pull out phone, turn on screen, pause. Voice: wait for the engine to pass, then say rewind (too loud for her = too loud for the phone). Gesture: gesture to pause, then play when it's passed. Explore several scenarios × personas × alternatives (three degrees of freedom — not every combination; fluid). Some combinations rule out alternatives: loud areas matter → voice is doubtful; many exercisers carry weights → gestures less promising. Modern form: **video prototyping** — a video mock-up of someone using the interface.
- [User Modeling](#L3-4-user-modeling) — From the principles unit: task analysis, cognitive task analysis, human information processor models. Map the goals, operators, methods and selection rules of the **GOMS** model onto each alternative: how are goals achieved in each interface, how easy relatively; what the user must keep in mind given competing attention; likelihood each will work. Personas are personal/empathetic; user models are objective, measurable, comparable — e.g. phases with different efficiencies/speeds, so you can say how efficient one design is versus another.
- [Quiz: Exercise: Design Alternatives](#L3-4-quiz-exercise-design-alternatives) — which methods have which advantages (Joyner's answers, relative):
  - **Includes the entire task context**: scenarios only (personas/timelines arguably but too separated from the task).
  - **Includes the user's context**: personas and user profiles (who, why, motivations); scenarios/timelines arguably too.
  - **Delineates the target audience**: user profiles do the cleanest job (formally articulate the user space; personas are fuzzier).
  - **General workflows**: user modeling (phases/steps/operators); timelines to an extent (more about thinking/feeling).
  - **Captures activity over time**: scenarios, timelines, user modeling.
  - **Captures edge cases**: scenarios — pose novel situations (a fire engine wouldn't appear in a timeline or user model); much design time goes to unique circumstances outside routine interaction.
- [Exploring Ideas](#L3-4-exploring-ideas) — Applying the techniques to the brainstorm: rule out technologically unfeasible ideas (skin-based interfaces, AR — not wasted, part of free-flow brainstorming) and practically unfeasible ones (small dev team → no dedicated wearable). Timelines show users value efficiency getting started (no complex setup each time). Personas show high cognitive load (monitoring exercise, environment, listening) → keep load very low, sacrifice features for simplicity. Result — three alternatives to prototype: (1) traditional **touch** smartphone app (must pull out phone, but flexible); (2) **gestural** interface (people aren't holding the device; gesture recognition in infancy but smartwatch/Fitbit might support it); (3) **voice** interface (people aren't talking while exercising; doubles as note-taking).
- [Exploring HCI: Design Alternatives](#L3-4-exploring-hci-design-alternatives) — If you've already chosen a technology (wearables, gesture) you've put the cart before the horse — fine as a learning experience: find a task that lets you explore it; you're still testing whether e.g. AR is right, altering the task rather than the design. Other domains (healthcare): personas for every stakeholder — nurses, doctors, patients, managers, family — and scenarios affecting each.
- [Conclusion to Design Alternatives](#L3-4-conclusion-to-design-alternatives) — Generate lots of ideas (individual and group heuristics), then synthesise into a handful via thought experiments (nothing designed yet). End of stage: a handful of designs to carry forward and prototype for real user feedback.

**Keywords to search for:** design alternatives · second biggest mistake · tunnel vision · Nest · keypad + key chain · design space vs problem space · individual brainstorming first · get silly · on-skin interface · Twiddler · write down the core problem · aim for 20 · divide and conquer · Thompson 2008 · social loafing · conformity · production blocking · performance matching · power dynamics · Osborn 1957 · expressiveness / nonevaluation / quantity / building · Oxley Dzindolet Paulus 1996 · no explaining ideas · no more than five people · 20-second timer · end with ideas not decisions · three or four ideas · personas · Anika · user profiles · frequent vs occasional · timeline · journey map · scenarios · storyboards · fire engine · video prototyping · user modeling · GOMS · cognitive task analysis · edge cases · touch / gesture / voice

**Jump to a section of the full text:** [Introduction to Design Alternatives](#L3-4-introduction-to-design-alternatives) · [The Second Biggest Mistake](#L3-4-the-second-biggest-mistake) · [The Design Space](#L3-4-the-design-space) · [Individual Brainstorming 1](#L3-4-individual-brainstorming-1) · [Individual Brainstorming 2](#L3-4-individual-brainstorming-2) · [5 Tips: Individual Brainstorming](#L3-4-5-tips-individual-brainstorming) · [Challenges in Group Brainstorming](#L3-4-challenges-in-group-brainstorming) · [Rules for Group Brainstorming](#L3-4-rules-for-group-brainstorming) · [5 Tips: Group Brainstorming](#L3-4-5-tips-group-brainstorming) · [Fleshing Out Ideas](#L3-4-fleshing-out-ideas) · [Personas](#L3-4-personas) · [User Profiles](#L3-4-user-profiles) · [Timeline](#L3-4-timeline) · [Scenarios and Storyboards](#L3-4-scenarios-and-storyboards) · [User Modeling](#L3-4-user-modeling) · [Quiz: Exercise: Design Alternatives](#L3-4-quiz-exercise-design-alternatives) · [Exploring Ideas](#L3-4-exploring-ideas) · [Exploring HCI: Design Alternatives](#L3-4-exploring-hci-design-alternatives) · [Conclusion to Design Alternatives](#L3-4-conclusion-to-design-alternatives)

---

<a id="A-L3-5"></a>

## Summary — Lesson 3.5 Prototyping

**Full lecture text:** [3.5 Prototyping](#L3-5) · **Lecture book pages:** pp. 542–570

**In one sentence:** Third stage of the design life cycle: build things to put in front of users, from low to high fidelity — concepts (representation, fidelity, evaluation, scope), tradeoffs, five tips, and methods (verbal, paper/card, Wizard of Oz, wireframes, physical), plus how prototyping fits the iterative cycle at multiple levels.

### Key points

- [Introduction to Prototyping](#L3-5-introduction-to-prototyping) — After needfinding, alternatives and mental simulation, actually make things to put in front of users. Unlike brainstorming, prototypes must be buildable and testable — but not the entire interface first; get feedback as quickly as possible and build sophistication over iterations. Start with **low-fidelity** prototypes (assembled and revised quickly) and work toward **high-fidelity** (wireframes, working versions).
- [Basics of Prototyping](#L3-5-basics-of-prototyping) — early prototyping = rapid revision of preliminary ideas (first iterations); late prototyping = finishing touches or revising a live design. Four main concepts:
  - **Representation** — what the prototype *is*: early → textual descriptions, simple paper visuals; later → more visual, interactive. Verbal (change description on the fly) → paper (ball it up, redraw) → functional (takes real time). Only invest in complex prototypes once ideas are vetted with easier ones; don't sink months of engineering into something a drawing could have disproved.
  - **Fidelity** — completeness/maturity: low (paper, drawings; easy to change) → high (wireframes, functional interface; harder). Move from low to explore ideas to high to really test; fidelity and representation correlate heavily.
  - **Evaluation** — low fidelity: relative function (can it do what it's meant to? can the user tell what to press?); wireframes: readability; actual performance (task time, which design drives purchases) needs higher fidelity and more iterations. Early: potential; middle: physical usability with real detail (font size, layout); late: working or near-working.
  - **Scope** — **horizontal** prototype covers the whole design shallowly; **vertical** prototype covers a small portion in great detail (Facebook: vertical for the status-posting screen, horizontal for the site). Usually horizontal earlier, vertical later, but in reality back and forth.
  - Other questions (iterative vs revolutionary changes; how executable) largely fall under these.
- [Tradeoffs of Prototyping](#L3-5-tradeoffs-of-prototyping) — Low fidelity: easy to create/modify, weak for detailed comprehensive evaluation. High fidelity: detailed feedback, hard to build. Maximise the trade-off: start easy to evaluate big designs/plans and check you're on track; move to high fidelity once there's evidence designs are sound. Prototypes are prototypes, not complete interfaces; designers love to design — “don't become a runaway train of designing. Design deliberately and get feedback often.”
- [5 Tips: Prototyping](#L3-5-5-tips-prototyping):
  1. **Keep prototypes easy to change** — enable rapid revision; paper is easy, code or physical prototypes harder.
  2. **Make it clear that it's a prototype** — if it looks too good users focus on superficial elements (colours, fonts); a prototype that looks like one keeps them on what you're testing.
  3. **Be creative** — do whatever it takes to get feedback; don't let the prototype type constrain the feedback; switch types if needed.
  4. **Evaluate risks** — minimise time on bad designs via early feedback; ask how much you'd lose if users hate the parts they haven't seen; if more than a couple of hours, get feedback.
  5. **Prototype for feedback** — details like font and colour (Joyner admits he does this) aren't the feedback needed when exploring big alternatives; prototype for the kind of feedback you want.
- [Verbal Prototypes](#L3-5-verbal-prototypes) — Simplest: describe the design to the user (lowest fidelity; same as telling co-designers). Easy to do, hard to do well: **social desirability bias** is big — hard to describe your idea in a way that lets them disagree → ask for specific, critical feedback. **Expert blind spot**: as you become a domain expert, don't assume your explanation makes sense to a novice → use **analogies** (InstaCart = “Uber for groceries”; Uber is like taxis, InstaCart like a taxi for groceries).
- [Paper Prototyping](#L3-5-paper-prototyping) — Draw the ideas (on-screen interfaces or control placement in a vehicle). Easy-app alternative drawn on paper → Morgan: looks straightforward (play, fast forward) but wants to see where she is in the book → revised immediately on paper. She didn't comment on colour/font because the paper prototype obviously isn't about that — **the nature of the prototype tells the user what feedback you want**. Interaction too: four screens; “you want to take a note — what would you do?” → “view the notes” → note-taking screen → “record” → transcribes → stop. Insight: no reason to jump to a separate screen; put a note-taking button on the main screen. This is **card-based prototyping**: each screen on a card, swapped in and out to simulate the app — much interaction prototyped with little effort.
- [Wizard of Oz](#L3-5-wizard-of-oz) — For voice or gesture interfaces paper won't do. Named after “pay no attention to that man behind the curtain”: we do behind the scenes what the interface would do once implemented. Morgan's voice-commanded audiobook: “play”, “pause”, “note” (transcribes), “bookmark” (drops a bookmark without pausing); Joyner realises mid-test he needs “close note”. Feedback: should playback resume after a note? Morgan: resume five seconds back, because saying “note” steps over content. Can get very complex (whole programmes where a person supplies input at the right time); concept: **the user interacts authentically while a human supplies the unimplemented functionality.**
- [Wireframing](#L3-5-wireframing) — After paper feedback, formalise with more detailed tools mocking up what the interface will look like: experiment with font size, colours, screen real estate. Tools: built-in widget tools; rudimentary wireframing in PowerPoint or Google Drawings; popular paid: **Balsamiq**, **Axure** (professional UI/UX, teams); Microsoft/Adobe users: **Visio**, **InDesign**; free: **Pencil Project**, **Frame Box**; ask classmates/colleagues for newer tools. Joyner is curious what prototyping tools will emerge for VR/AR where a 2D canvas doesn't work.
- [Physical Prototypes](#L3-5-physical-prototypes) — For physical or 3D designs; **it doesn't have to work** — designers get tripped up thinking they need a working version. Bluetooth button device for exercisers prototyped with a car key fob (“pretend this button does this”): close enough shape/size; test the general idea of pressing buttons while exercising; tell Morgan how it works and watch whether she presses the right buttons (intuitiveness); or have her run with it and report whether holding something throws off her routine.
- [Quiz: Exercise: Prototyping Pros and Cons](#L3-5-quiz-exercise-prototyping-pros-and-cons) — methods: verbal, paper, card, Wizard of Oz, wireframes, physical. Joyner's answers:
  - **Revisable during interaction**: verbal, paper, card, Wizard of Oz (low fidelity — change on the spot; the wizard just changes how he runs it).
  - **Disguises superficial details**: the same four (nobody critiques the font of a hand drawing or the voice in a Wizard of Oz test) — focus on patterns of interaction.
  - **Simulates user interaction**: card, Wizard of Oz, (to an extent) wireframes and physical; verbal and paper just show something and ask (no interaction).
  - **Distributable to remote users**: wireframes (paper could be scanned, but paper prototyping is about the conversation around it; wireframes give a general impression).
  - **Prototypes look and feel**: inverse of disguising details — the later/higher-fidelity ones (wireframes, physical).
  - **Allows mobility**: Wizard of Oz (call things out while the user moves) and physical (hand it to them).
- [Design Life Cycle Revisited](#L3-5-design-life-cycle-revisited) — Misconception to cut off: you don't finish prototyping then move to evaluation. One prototype = one iteration through the cycle: initial needfinding → alternatives → paper prototypes → **evaluate the paper prototypes with real people** → results say whether to understand the task better, reconsider alternatives → return to prototyping: if successful, raise fidelity (wireframes, card prototype); if not, a different low-fidelity prototype → evaluate again. Time scales vary: a cycle can take one minute (user dislikes it → why? → mini-needfinding → quick brainstorm → sketch the fix → try again) or months — which is why months-long prototypes come only after several low-fidelity cycles.
- [Multi-Level Prototyping](#L3-5-multi-level-prototyping) — Prototypes needn't all be at the same level at the same time. Facebook redesigning its status-update box needn't implement a functional version to prototype — sketches/wireframes first. Multi-function apps (LinkedIn: edit profile, connect, browse feed; moving among them is itself a task): designing all screens and transitions at once is too much → **bottom-up** (individual screens first, then the whole experience) or **top-down** (overall navigation first, then screen contents). Prototyping can and should exist at multiple levels of fidelity at any time.
- [Exploring HCI: Prototyping](#L3-5-exploring-hci-prototyping) — Traditional screens: paper → wireframes → increasingly complete versions. Gestural or voice interaction: Wizard of Oz (human interprets commands). AR/wearables: get even more creative. Goal: feedback on ideas with the user, early — what can you create to get that feedback?
- [Conclusion to Prototyping](#L3-5-conclusion-to-prototyping) — Employ many methods to get feedback rapidly and iterate quickly toward the ultimate interface. Main goal: designs we can **evaluate with real users** (a hand-drawn interface's value is feedback, not deployment). The whole life cycle leads to evaluation — of ideas, prototypes, designs; user evaluation is the key to user-centered design, keeping focus on users' needs and experiences. Next: evaluation.

**Keywords to search for:** prototyping · low fidelity / high fidelity · early vs late prototyping · representation · fidelity · evaluation · scope · horizontal vs vertical prototype · Facebook status box · tradeoffs · runaway train of designing · make it clear it's a prototype · evaluate risks / couple of hours · prototype for feedback · verbal prototype · expert blind spot · analogy / Uber for groceries · InstaCart · paper prototype · card-based prototyping · note-taking button · Wizard of Oz · man behind the curtain · play / pause / note / bookmark / close note · five seconds back · wireframing · Balsamiq · Axure · Visio · InDesign · Pencil Project · Frame Box · PowerPoint / Google Drawings · physical prototype · key fob · doesn't have to work · pros and cons table · revisable during interaction · distributable to remote users · allows mobility · one prototype = one iteration · one-minute cycle · multi-level prototyping · LinkedIn · bottom-up vs top-down

**Jump to a section of the full text:** [Introduction to Prototyping](#L3-5-introduction-to-prototyping) · [Basics of Prototyping](#L3-5-basics-of-prototyping) · [Tradeoffs of Prototyping](#L3-5-tradeoffs-of-prototyping) · [5 Tips: Prototyping](#L3-5-5-tips-prototyping) · [Verbal Prototypes](#L3-5-verbal-prototypes) · [Paper Prototyping](#L3-5-paper-prototyping) · [Wizard of Oz](#L3-5-wizard-of-oz) · [Wireframing](#L3-5-wireframing) · [Physical Prototypes](#L3-5-physical-prototypes) · [Quiz: Exercise: Prototyping Pros and Cons](#L3-5-quiz-exercise-prototyping-pros-and-cons) · [Design Life Cycle Revisited](#L3-5-design-life-cycle-revisited) · [Multi-Level Prototyping](#L3-5-multi-level-prototyping) · [Exploring HCI: Prototyping](#L3-5-exploring-hci-prototyping) · [Conclusion to Prototyping](#L3-5-conclusion-to-prototyping)

---

<a id="partB"></a>

# Part B — Full Lecture Text

Verbatim content of the supplied lecture-note files, in course order. The “»” symbol marks a speaker change in video-transcript dialogue, exactly as in the source.

<a id="L1-1"></a>

## 1.1 Introduction to HCI

**CS6750 · Human–Computer Interaction** — Lecture notes (David Joyner, Summer 2017 lecture book, pp. 1–24)

*Full lecture content, restructured for revision. `»` marks a speaker change in video-transcript dialogue.*

[Back to summary of this lesson](#A-L1-1) · [Table of contents](#toc) · [Keyword index](#partC)

**Sections in this lesson:**

- [Humans](#L1-1-humans)
- [Computers](#L1-1-computers)
- [Interaction](#L1-1-interaction)
- [Quiz: Reflections: Interacting & Interfaces](#L1-1-quiz-reflections-interacting-interfaces)
- [The HCI Space](#L1-1-the-hci-space)
- [HCI in the Big Picture](#L1-1-hci-in-the-big-picture)
- [HCI vs Human Factors](#L1-1-hci-vs-human-factors)
- [HCI vs User Interface Design](#L1-1-hci-vs-user-interface-design)
- [HCI vs User Experience Design](#L1-1-hci-vs-user-experience-design)
- [HCI vs Psychology](#L1-1-hci-vs-psychology)
- [HCI: Research and Design](#L1-1-hci-research-and-design)
- [Welcome to HCI!](#L1-1-welcome-to-hci)

<a id="L1-1-humans"></a>

### Humans

[MUSIC] This is Morgan.

» Hello.

» Morgan is a human.

» Last time I checked.

» As a human, Morgan has various ways of perceiving the world around her, like seeing, hearing, and feeling.

» Is anyone else seeing these?

» There are a few more as well like smelling and tasting, but we won't deal with those as much.

» Thank goodness.

» But Morgan has more than senses. She also has memories, experiences, skills, knowledge.

» Thanks.

» In human computer interaction, we have to take into consideration every element of the human, from the way they perceive and interact with the world, to their long history of using computers and technology.

<a id="L1-1-computers"></a>

### Computers

This is a computer. Or at least, this is probably what you think of when you think of the term computer. But this is also a computer. And so is this. And so is this. And so is this. And so is this.

» Hey!

» This is Amanda, my video producer.

» Go on, I'm rolling.

» Right, and so is this. And so is this, and this, and this, and this, and even this. And so is this. And so is this. And so is this. [SOUND] And so is this. And so is this.

» Hey David?

» One second, trying to get to Squirtle. There we go. With mobile devices and augmented reality, HCI is quite literally everything. Pokemon Go was released a few days before I recorded this and augmented reality games like this turn effectively the entire world into an instance of HCI. Even out here in the middle of nowhere, I'm still doing something with computers.

<a id="L1-1-interaction"></a>

### Interaction

We have humans and we have computers and we're interested in the interaction between them. That interaction can take different forms though. The most obvious seems to be the human interacts with the computer and the computer interacts with the human in response. They go back and forth interacting, and that's a valid view. But it perhaps misses the more interesting part of HCI.

We can also think of the human interacting with the task, through the computer.

The interaction is really between the human and the task and the computer in the middle just mediates that interaction. Or to put this differently, the human and the computer together, interact with the task.

Ideally in this case, we're interested in making the interface as invisible as possible, so the user can spend as little time focusing on the interface and instead focus on the tasks that they're trying to accomplish.

Realistically, our interfaces are likely to stay somewhat visible. But our goal is to let the user spend as much time as possible thinking about the task, instead of thinking about our interface. We can all probably remember times when we've interacted with a piece of software and we felt like we spent all our time thinking about how to work the software. As opposed to accomplishing what we were using the software to do in the first place and that's frustrating. So our goal as designers, is to help the human feel like they're interacting directly with that task. While our interface, kind of vanishes, in the middle of that interaction.

<a id="L1-1-quiz-reflections-interacting-interfaces"></a>

### Quiz: Reflections: Interacting & Interfaces

We'll talk extensively about the idea of disappearing interfaces and designing with tasks in mind. But in all likelihood, you've used computers enough to already have some experience in this area. So take a moment and reflect on some of the tasks you do each day involving computers. Try to think of an example where you spend most of your time thinking about the task and an example where you spend most of your time thinking about the tool.

Video games actually give us some great examples of interfaces becoming invisible. A good video game is really characterized by the player feeling like they're actually inside the game world, as opposed to controlling it by pressing some buttons on a controller. We can do that through some intuitive controller design like pressing forward moves forward, and pressing backward moves backwards. But a lot of times we'll rely on the user to also learn how to control the game over time. But as they learn, it becomes invisible between them and their interaction. A classic example of a place where interaction is more visible, is the idea of having more than one remote control that controls what feels like the same system. So I have these two controllers that control my TV and my cable box together. And for me it feels like this is just one task, watching TV. But technologically, it's actually different tasks. So I have to think about am I using the number pad on this controller or this controller, depending on what I'm trying to do at a given time. So I spend a lot of time thinking about the interface and not as much thinking about the task.

<a id="L1-1-the-hci-space"></a>

### The HCI Space

One of the most exciting parts of HCI is it's incredible ubiquity. Computers are all around us and we interact with them everyday. It's exciting to think about designing the types of tools and interfaces we spend so much time dealing with, but there's a danger here too. Because we're all humans interacting with computers, we think we're experts at human-computer interaction. But that's not the case.

We might be experts at interacting with computers, but that doesn't make us experts at designing interactions between other humans and computers. We're like professional athletes or world-class scientists. Just because we're experts doesn't mean we know how to help other people also become experts.

In my experience, many people look at HCI like this. The red dot represents what they know and the black circle represents what they think there's to know. They know there's probably some things they don't know yet, but they're already pretty at it, and it wouldn't be too hard to become an expert. After studying HCI for a bit though, they look more like this. You can see that they've increased what they know but their perception of what there is to know has grown even more. That's the journey we'll be taking together. You'll learn to do work in HCI, but perhaps more importantly, you'll learn how complex and large the field of HCI is. Your knowledge will increase, but yet you might exit the class less confident in your HCI ability than when you started. You're taking the first step into a larger world.

<a id="L1-1-hci-in-the-big-picture"></a>

### HCI in the Big Picture

Now, what we've described so far is a huge field, far too big to cover in any one class. In fact there are lots of places where you can get an entire masters degree or PhD in human computer interaction. Here are some of the schools that offer programs like that. And these are just the school that offer actual degree programs in HCI, not computer science degrees with specializations in HCI, which would be almost any computer science program. So let's look more closely at what we're interested in for the purpose of the next several weeks. To do that, let's look at where HCI sits in a broader hierarchy of fields.

We can think of HCI as a subset of a broader field of human factors engineering. Human factors engineering is interested in a lot of the same ideas that we're interested in. But they aren't just interested in computers. Then there are also sub disciplines within HCI. This is just one way to represent this. Some people, for example, would put UI design under UX design, or put UX design on the same level as HCI, but this is the way I choose to present it. Generally, these use many of the same principles that we use in HCI, but they might apply them to a more narrow domain, or they might have their own principles and methods that they use in addition to what we talk about in HCI in general. So to get a feel for what we're talking about when we discuss HCI, let's compare it to these other different fields.

<a id="L1-1-hci-vs-human-factors"></a>

### HCI vs Human Factors

First let's start by comparing HCI to the broader field of human factors. Human factors is interested in designing interactions between people and products, systems or devices. That should sound familiar. We're interested in designing the interactions between people and computers. But computers are themselves products or systems. But human factors is interested in non-computing parts of this, as well.

Let's take an example. I drive a pretty new electric car, which means there are tons of computers all over it. From a HCI perspective, I might be interested in visualizing the data on the dashboard, or helping the driver control the radio. Human factors is interested not only in how I interact with the computerized parts of the car but the non-computerized parts as well. It's interested in things like the height of the steering wheel, the size of the mirrors, or the positioning of the chair. It's interested in designing the entire environment, not just the electronic elements. But that means it's interested in a lot of the same human characteristics that we care about, like how people perceive the world, and their own expectations about it. So many of the principles we'll discuss in this class, come from human factors engineering, applied more narrowly to computerized systems. But the exciting is that as computers become more and more ubiquitous, the number of application areas for HCI is growing. 20 years ago, a car might not have been an application of HCI. Ten years ago a wrist watch would have been more about industrial design than HCI. And without only the past couple years, things like showerheads and refrigerators have started to become truly computerized devices. As computers integrate themselves into more and more of our devices, the gap between human computer interaction and human factors engineering is shrinking. As computers become more and more ubiquitous there is coming a time when pretty much every single thing on your car, will actually be run through a computer. Don't believe me? Check out the inside of Teslas model S. When you look at the console of a Tesla, almost everything you see is giant computer Cars have become computers on wheels. Watches have become computers on wristbands. Car keys have become computers on keychains. Computers are everywhere. And so, HCI is everywhere.

<a id="L1-1-hci-vs-user-interface-design"></a>

### HCI vs User Interface Design

For many years, human-computer interaction was largely about user interface design. The earliest innovations in HCI were the creation of things like the light pen, the first computer mouse, which allow for flexible interaction with things on screen. But the focus was squarely on the screen.

And so, we developed many principles about how to design things nicely for a screen. We borrowed from the magazine and print industries and identify the value of grids in displaying content and guiding the users eyes around our interfaces.

We created laws that govern how difficult it is for users to select what they want on screen. We examined for example whether it's easier to select a menu on a Mac, where the menus are always at the top of the screen. Or on a PC, where they're grouped with the individual window.

We developed techniques for helping interfaces adapt to different screen sizes and we developed methods for rapidly prototyping user interfaces using pen and paper or wire frames.

Through this rich history, UI design really became its own well defined field. In fact, many of the concepts we'll cover in HCI were originally developed in the context of UI design. But in HCI, we're interested in things that go beyond the user's interaction with a single screen. Technically, you an cover that in UI design as well, but traditionally most of the UI design classes I see focus on on-screen interaction. In HCI, we'll talk about the more general methods that apply to any interface.

<a id="L1-1-hci-vs-user-experience-design"></a>

### HCI vs User Experience Design

The relationship between HCI and user experience design is a little bit closer. In fact, if you ask a dozen people working in the field, you'll likely get a dozen different answers about the difference.

For the purposes of our conversations though, we'll think about the difference like this. HCI is largely about understanding the interactions between humans and computers. User experience design is about dictating the interactions between users and computers. In order to design user experiences very well, you need to understand the user, you need to understand their interactions with interfaces. And that's why I personally consider user experience design to be a subfield of the broader area of HCI. In our conversations, we'll use the principles and methods from HCI to inform how we design user experiences. But it's important to note that this relationship is deeply symbiotic. We might use that understanding to inform how we design the user experiences. But then we evaluate those designs and based on their success or failures, we'll use that to inform our increasing knowledge of human computer interaction itself. If our understanding leads us to create good designs, that provides evidence that our understanding is correct. If we create a design with some understanding and that design doesn't work, then maybe our understanding was flawed and now our understanding of human computer interaction as a whole will increase. This is similar to something called design based research, which we'll talk about later, using the results of our designs to conduct research.

You might also notice that this is very related to our concept of feedback cycles. Just as a user uses an interface to participate in some task and then evaluates the result of their interaction, so also we design interfaces and evaluate their success. You'll find that feedback cycles are really all over this course and all over the world in general.

<a id="L1-1-hci-vs-psychology"></a>

### HCI vs Psychology

The research side of HCI connects to the relationship between HCI and psychology. And if we zoom out even further on this hierarchy of disciplines, we might say that human factors engineering itself is in many ways the merger of engineering and psychology. As well as other fields of design and cognitive science. In HCI, the engineering side takes the form of software engineering, but this connection to psychology remains, and in fact, it's symbiotic. We use our understanding of psychology, of human perception, of cognition to inform the way we design interfaces. We then use our evaluations of those interfaces to reflect on our understanding of psychology itself. In fact, at Georgia Tech, the Human Computer Interaction class is cross listed as a Computer Science and Psychology class.

So let's take an example of this. In 1992, psychologists working at Apple wanted to study how people organized the rapid flow of information in their work spaces.

They observed that people tended to form piles of related material, kind of like a less formal filing system, and so they then designed a computer interface, that would mimic that ability.

Finally, they used the results of that development to reflect on how people were managing their work spaces in the first place. So in the end, they had a better understanding of the thought processes of their users as well as an interface that actually helped users. So in the end, their design of an interface with an HCI informed their understanding of psychology more generally. We came away with a better understanding of the way humans think about their work spaces because of our experience designing something that was supposed to help them think about their work spaces.

<a id="L1-1-hci-research-and-design"></a>

### HCI: Research and Design

Now that we've talked at length about what HCI isn't, let's talk a little bit about what HCI actually is. On the one hand, HCI is about research. Many of the methods we'll discuss are about researching the user, understanding their needs,and evaluating their interactions with designs that we've prototyped for them. But on the other hand, HCI is about design. After all, design is that prototyping phase, even though we're prototyping with research in mind. HCI is about designing interactions to help humans interact with computers, oftentimes using some known principals for good interaction. Things like designing with distributed cognition in mind, or making sure the user develops good mental models of the way the interface works, or making sure they design with universal design in mind. We'll talk about all these topics later in our conversations. You don't need to worry about understanding any of these right now. What is important to understand right now, is that these aren't two isolated sides.

The results of our user research inform the designs we construct, and the results of our designs inform our ongoing research.

Again, you might notice this is very similar to the feedback cycles we're designing for our users. They use what they know to participate in the task, and then use the feedback from that participation to inform what they know. We use what we know to design good interfaces, and then use the results of those interfaces to inform our ongoing research. This is the heart of what HCI is, for the purpose of our conversations. Using research to inform our designs and using the results of those designs to inform our ongoing research. And this cycle appears anywhere that humans are using computers to participate in tasks. That could be sitting on a desk using a screen. That could be using a smartphone or a smartwatch. That could be participating with some kind of touch or gesture base system, or could be some interesting in merging technologies like virtual and augmented reality. In HCI were interested in the general principles and methods for designing and researching all of these things.

<a id="L1-1-welcome-to-hci"></a>

### Welcome to HCI!

So now you know what we're going to cover in our exploration of HCI. We're going to talk about some of the fundamental design principles that HCI researchers have discovered over the years. We're going to talk about performing user research, whether it be for new interfaces, or exploring human cognition. We're going to talk about the relationship between these two, how our research informs what we design, and how what we design helps us conduct research. And we're going to talk about how these principles work in a lot of domains, from technologies like augmented reality, to disciplines like healthcare. I hope you're excited. I know I am. I like to think of this not just as a course about human- computer interaction, but also an example of human-computer interaction. Humans using computers in new and engaging ways to teach about computer interaction. We hope this course exemplifies the principles as well as teaches them.

— End of Lesson 1.1 — [Back to summary](#A-L1-1) · [Contents](#toc)

---

<a id="L1-2"></a>

## 1.2 Introduction to CS6750

**CS6750 · Human–Computer Interaction** — Lecture notes (David Joyner, Summer 2017 lecture book, pp. 25–45)

*Full lecture content, restructured for revision. `»` marks a speaker change in video-transcript dialogue.*

[Back to summary of this lesson](#A-L1-2) · [Table of contents](#toc) · [Keyword index](#partC)

**Sections in this lesson:**

- [Introduction to CS6750](#L1-2-introduction-to-cs6750)
- [Learning Goals](#L1-2-learning-goals)
- [Learning Outcomes: To Design](#L1-2-learning-outcomes-to-design)
- [Learning Outcomes: Effectiveness](#L1-2-learning-outcomes-effectiveness)
- [Learning Outcomes: Between Humans and Computers](#L1-2-learning-outcomes-between-humans-and-computers)
- [Learning Strategies: Video Material](#L1-2-learning-strategies-video-material)
- [Learning Strategies: Georgia Tech](#L1-2-learning-strategies-georgia-tech)
- [Learning Assessments](#L1-2-learning-assessments)
- [Course Structure](#L1-2-course-structure)
- [5 Tips Doing Well in CS6750](#L1-2-5-tips-doing-well-in-cs6750)
- [Conclusion](#L1-2-conclusion)

<a id="L1-2-introduction-to-cs6750"></a>

### Introduction to CS6750

[MUSIC] Now that you understand a little bit about what human-computer interaction is, let's talk about what this class is going to be like. In this lesson, I am going to take you through a high level overview of this class. What material we'll cover, how it fits together, and what you should expect to know by the end of the course. I'll also talk a little bit about the assessments we'll use in the class, but be aware, these assessments are only applicable to students taking this class through Georgia Tech. If you're watching this course on your own or taking it to complement other courses you're taking, those assessments won't apply to you, but you'll get to hear a little bit about what students in the actual course do. If you are a student in the course, you should know the assessments do tend to change a bit semester to semester. I'm going to try and stay as general as possible to capture future changes, but make sure to pay attention to the specific materials you're provided for your semester.

<a id="L1-2-learning-goals"></a>

### Learning Goals

In education, a learning goal is something we want you to understand at the end of the course. It's the knowledge contained within your head that you might not have had when we got started. In this class we have three major learning goals.

First, we want you to understand some of the common principles in human computer interaction. These are the tried and true rules on how to design good interactions between humans and computers.

Second, we want you to understand design life cycle. That's how interfaces go from conception to prototypes to evaluation. And we especially want you to understand the roll of iteration in this process.

Third, we want you to understand the expense of the human computer inherent interaction field and the current applications available for HCI. HCI is really everywhere, from domains like healthcare, to technologies like virtual reality, to emerging techniques like sonification.

We want you to understand the broad range of application areas for HCI in the modern world.

<a id="L1-2-learning-outcomes-to-design"></a>

### Learning Outcomes: To Design

While learning goal is something we want you to know at the end of the course, a learning outcome is something we want you to be able to do. This course really has one learning outcomes but there are some nuances to it.

The learning outcome for this course is to be able to design effective interactions between humans and computers. The first part of this learning outcome is to design. But what is design? Well for us design is going to take two forms.

First, design is an activity where you're applying known principles to a new problem. For example we'll talk a lot about the importance of getting users to write kind of feedback at the right time. That's a plan of principle of feedback to some new design problem we encounter.

But design is a second form as well, design is also a process where you gather information, use it to develop design alternatives, evaluate them with users and revise them accordingly. When designing interface for some tasks, I would ask some potential users how they perform some task right now. I develop multiple different ideas for how we can help them. I give those to the users to evaluate, and I will use the experiences to try to improve the interface on that time.

So let's take an example of this. Imagine I was designing a new thermostat. On the one hand, designing a new thermostat means applying known HCR principles, like feedback and error tolerance to some new design. On the other hand, designing a new thermostat means creating different ideas, giving them to users, getting their feedback and then revising those designs. Both these sides of design are very important. You don't want to ignore decades of experience when designing new interfaces, but simply applying known principles to a new problem doesn't guarantee you have a good design. Designing is about both these things. And in fact, these two things are a vast majority of material that we'll cover in this course.

We'll cover the principles uncovered by a human factors engineering and human computer interaction research. And we'll cover the methods used in the HCI. We're gathering user requirements, developing designs, and evaluating new interfaces.

<a id="L1-2-learning-outcomes-effectiveness"></a>

### Learning Outcomes: Effectiveness

The first part of this learning outcome to design needed some definition, but the second part seems pretty straightforward, right? Not exactly. Effectiveness is defined in terms of our goal.

The most obvious goal here might be usability and for a lot of that's exactly what we're interested in. If I'm designing a new thermostat, I want the user to be able to create the outcome they want as easily as possible.

But maybe usability isn't my goal, maybe it's research. Maybe I'm interested in investigating what makes people think that the thermostat is working correctly. In that case, I might deliberately create some thermostats that are harder to read, just to see how that changes people's perceptions of the system.

Or it could be that my goal isn't to make the certain activity easier but rather to change that activity. Maybe I'm interested in reducing a home's carbon footprint. In that case, my goal is to get people to use less electricity. I might design the interface of the thermostat specifically to encourage people to use less. Maybe I'd show them a comparison to their neighbor's usage, or allow them to set energy usage goals. Or I could make the thermostat physically harder to turn up and down. So effectiveness is very much determined by the goal that I have in mind. We'll generally assume that our goal is usability, unless we state otherwise. But we'll definitely talk about some of those other goals as well.

<a id="L1-2-learning-outcomes-between-humans-and-computers"></a>

### Learning Outcomes: Between Humans and Computers

The final part of our desired learning outcome is between humans and computers. We want to design effective interactions between humans and computers. Well, what is important to note here, is where we're placing the emphasis. Note that we didn't say designing effective interfaces, because that puts the entire focus on the interface. We're deeply interested in the human's role in this interaction.

So rather than designing interfaces, designing programs, designing tools, we're designing interactions. We're designing tasks. We're designing how people accomplish their goals, not just the interface that they use to accomplish their goals.

Take our thermostat for example. When we started this process, our goal shouldn't be to design a thermostat. Our goal should be to design the way in which a person controls the temperature in their home. That subtle shift in emphasis is powerful. If you set out to design a better thermostat, you might design a wall-mounted device that's easier to read or easier to use.

But if you set to design a better way for people to control the temperature in their home, you might end up with Nest. A device that learns from the user and starts to control the temperature automatically.

<a id="L1-2-learning-strategies-video-material"></a>

### Learning Strategies: Video Material

Learning strategies are how we plan to actually impart that knowledge to you. This is how we attempt to help you achieve the learning goals and learning outcomes. Within these videos, we'll use a number of different strategies to try to help you understand the core principles and methodologies of HCI.

We'll use learning by example. Every lesson and, in fact, this course, as a whole. Is organized around a collection of running examples that will come up over and over again.

We use learning by doing. Throughout the course we'll ask you to engage in designing interactions to solve different problems in different contexts. These aren't required, since there's really no way we can verify if you've done them, but we really hope you'll take a few minutes and think about these. We'll also use learning by reflection a lot.

We'll ask you to reflect on times when you've encountered these things in your own everyday life. These strategies are useful because they connect to your own personal experiences but once again, there's a danger here.

One of the recurrent points in HCI is that when you are designing interactions, you are not your own user. Focusing too much on your own experiences can give you a false sense of expertise. So I'll use some strategies to help take you out of that comfort zone and confront how little you might understand these tasks with which you thought you were so familiar.

<a id="L1-2-learning-strategies-georgia-tech"></a>

### Learning Strategies: Georgia Tech

Within the full course at Georgia Tech, there are a number of other strategies in which you'll engage as well. First, we're really passionate about leveraging the student community in this class to improve the experience for everyone. Taking this class with you are people with experience in a variety of industries, many of whom have significant experience in HCI. So some strategies we'll use include peer learning, collaborative learning, learning by teaching, and communities of practice. You'll learn both from each other and with each other. You'll play the role of student, teacher, and partner, and you will learn from each perspective.

In addition, the entire course is built around the idea of project-based learning. Early in the semester, you'll form a team and start looking at a problem we've selected, or maybe one in which you're already interested. This project will then become the domain through which you explore the principles and methods of human-computer interaction. Who knows? By the end of the semester, you might even generate something with the potential to go forward as a real-world product, or as a research project.

<a id="L1-2-learning-assessments"></a>

### Learning Assessments

Learning goals are what we want you to understand. Learning outcomes or what we want you to be able to do. Learning assessments then, are how we evaluate whether you can do what we want you to be able to do and understand what we want you to understand. The learning outcome to this class is to be able to design effective interactions between humans and computers.

So the primary assessments in this class are to, say it with me, design effective interactions between humans and computers. You'll start with some relatively small scale tasks, recommending improvements to existing interfaces or undertaking some small design challenges. But as the semester goes on, you'll scope up towards a bigger challenge. You'll initially investigate that challenge individually and then you'll merge into teams to prototype and evaluate a full solution to the challenge you chose.

At the end, you'll be evaluated not just on the final design you generate but on the process by which it was generated.

<a id="L1-2-course-structure"></a>

### Course Structure

We'll close by talking about the overall structure of the content you'll be consuming. The course's lessons are designed to be as independent as possible, so you should be able to skip around if you want, but there's a certain logic to our planned presentation order. We discussed earlier the model HCI, how design informs research and research then informs design, so we'll start by discussing some of the core design principles of HCI.

Then we'll discuss the research methodologies for uncovering new user information, the iterative design lifecycle. We'll close by giving you the opportunity to peek at what's going on in the HCI community at large.

<a id="L1-2-5-tips-doing-well-in-cs6750"></a>

### 5 Tips Doing Well in CS6750

Here are five quick tips for doing well in this course. [SOUND] Number one. Look over the assignments early. Some of our assignments you can sit down and do them in an hour. But others require some advance coordination to talk to users, develop prototypes or test with real people. So go ahead and at least read all the assignment descriptions. Number 2. Start the assignments early. That's not just typical teacher talk saying, you can't get this done at the last minute. You probably can, but you're using interfaces like these in your everyday life. By starting early you're likely to get inspiration just in your day to day routine, and that's going to make writing the assignment significantly easier than trying to sit down and come up with something on the spot. Number three, participate, interact with your classmates, post on the forums, read others' posts. The knowledge and experience you gain there is just as valuable as anything you'll get listening to me in these videos. Number four, select an application area to explore. Next lesson you'll hear about several of the interesting areas of HCR research and development going on right now. Developing in many of these areas is outside the scope of this class, but I encourage you to pick an area in which you're interested and mentally revisit it throughout the course. Number five, leave behind what you know, or at least try. HCI is a huge area and yet many people believe that because they're already good at using computers, they'd be good at designing user experiences. But HCI above all else is about gaining a grounded understanding of the user's needs not assuming we already understand them. So while it's great to apply the course's principles to your every day life, be cautious about designing too narrowly based only on your own experiences.

<a id="L1-2-conclusion"></a>

### Conclusion

In this lesson, I've tried to give you some expectations of what this course will be like. We've gone over the course's goals, outcomes, learning strategies and assessments.

We've covered the course's learning outcome in great detail, to design effective interactions between humans and computers. Now I focus mostly on the video material, because the assignments, projects and exams are separate from these videos, and are likely to change pretty significantly semester to semester.

The video material here will cover three general areas, principles, methods and applications. To really get into the applications, it's useful to understand the principles and methods. But at the same time, it's useful to keep the applications in mind, while learning about the principles and methods. So next we're going to briefly preview some of the application areas for you to keep in mind during the rest of our conversations. Then after we cover principles and methods, we'll invite you to revisit these application areas, and leave room to explore whatever you find most interesting.

— End of Lesson 1.2 — [Back to summary](#A-L1-2) · [Contents](#toc)

---

<a id="L1-3"></a>

## 1.3 Exploring HCI

**CS6750 · Human–Computer Interaction** — Lecture notes (David Joyner, Summer 2017 lecture book, pp. 46–73)

*Full lecture content, restructured for revision. `»` marks a speaker change in video-transcript dialogue.*

[Back to summary of this lesson](#A-L1-3) · [Table of contents](#toc) · [Keyword index](#partC)

**Sections in this lesson:**

- [Introduction to Exploring HCI](#L1-3-introduction-to-exploring-hci)
- [Technology: Virtual Reality](#L1-3-technology-virtual-reality)
- [Technology: Augmented Reality](#L1-3-technology-augmented-reality)
- [Technology: UbiComp and Wearables](#L1-3-technology-ubicomp-and-wearables)
- [Technology: Robotics](#L1-3-technology-robotics)
- [Technology: Mobile](#L1-3-technology-mobile)
- [Idea: Context-Sensitive Comp](#L1-3-idea-context-sensitive-comp)
- [Idea: Gesture-Based Interaction](#L1-3-idea-gesture-based-interaction)
- [Idea: Pen- and Touch-Based Interaction](#L1-3-idea-pen-and-touch-based-interaction)
- [Idea: Information Visualization](#L1-3-idea-information-visualization)
- [Idea: CSCW](#L1-3-idea-cscw)
- [Idea: Social Computing](#L1-3-idea-social-computing)
- [Domain: Special Needs](#L1-3-domain-special-needs)
- [Domain: Education](#L1-3-domain-education)
- [Domain: Healthcare](#L1-3-domain-healthcare)
- [Domain Security](#L1-3-domain-security)
- [Domain: Games](#L1-3-domain-games)
- [Reflections: Exploring HCI](#L1-3-reflections-exploring-hci)
- [Conclusion to Exploring HCI](#L1-3-conclusion-to-exploring-hci)

<a id="L1-3-introduction-to-exploring-hci"></a>

### Introduction to Exploring HCI

[MUSIC] [SOUND] Computers are finding their way into more and more devices, and as a result HCI is becoming more and more ubiquitous. It used to be that you wouldn't really need to think too much about HCI when designing a car or designing a refrigerator, but more and more computing is pervading everything. At the same time, new technological developments are opening up new areas for exploration. We're seeing a lot of really fascinating progress in areas like virtual reality, augmented reality, wearable devices. As we study HCI, we're going to talk a lot about things you've already used like computers and phones. But we want you to keep in mind some of these more cutting edge application areas as well. After all, if you're really interested in going into HCI professionally, you'll be designing for these new application areas. So we're going to quickly preview some of these. We'll divide them into three areas, **technologies** , **domains** and **ideas** . Technologies are emerging technological capabilities that let us create new and interesting user interactions. Domains are pre- existing areas that could be significantly disrupted by computer interfaces like healthcare and education. Ideas span both of these. They are the theories about the way people interact with interfaces and the world around them. Now, our delineation of this is kind of artificial. There's a lot of overlap. New technologies like augmented reality are what allow emerging ideas like contact sensitive computing to really have the power that they do. But for organization, we'll group our application areas into these three categories. When one of these areas catches your eye, take a little while and delve into it a little bit deeper. Then keep that topic area in mind as you go through the rest of the HCI material. We'll revisit your chosen area throughout the course, and ask you to reflect on the application of the course's principals and methods to your application area.

<a id="L1-3-technology-virtual-reality"></a>

### Technology: Virtual Reality

The year that I'm recording this is what many have described as the year that virtual reality finally hits the mainstream. By the time you watch this, you'll probably be able to assess whether or not that was true, so come back in time and let me know. Virtual reality is an entire new classification of interaction and visualization and we're definitely still at the beginning of figuring out what we can do with these new tools. You could be one of the ones who figures out the best way to solve motion sickness or how to get proper feedback on gestural interactions.

A lot of the press around virtual reality has been around video games, but that's definitely not the only application. Tourism, commerce, art, education, virtual reality has applications to dozens of spaces. For example, there is a lab in Michigan that's using virtual reality to treat phobias. They're creating a safe space where people can very authentically and realistically confront their fears. The possible applications of virtual reality are really staggering. So I'd encourage you to check them out as you go through this class.

<a id="L1-3-technology-augmented-reality"></a>

### Technology: Augmented Reality

Virtual reality generally works by replacing the real world's visual, auditory, and sometimes even all factory or kinesthetic stimuli with it's own input. Augmented reality on the other hand, compliments what you see and hear in the real world. So for example, imagine a headset like a Google Glass that automatically overlays directions right on your visual field. If you were driving, it would highlight the route to take, instead of just popping up some visual reminder. The input it provides complements stimuli coming from the real world, and instead of just replacing them. And that creates some enormous challenges, but also some really incredible opportunities as well.

Imagine the devices that can integrate directly into our everyday lives, enhancing our reality. Imagine systems that could, for example, automatically translate text or speech in a foreign language, or could show your reviews for restaurants as you walk down the street. Imagine a system that students could use while touring national parks or museums, that would automatically point out interesting information, custom tailored to that student's own interests. The applications of augmented reality could be truly stunning, but it relies on cameras to take input from the world, and that actually raises some interesting societal problems. There are questions about what putting cameras everywhere would mean. So keep those in mind when we get to interfaces and politics, in unit two.

<a id="L1-3-technology-ubicomp-and-wearables"></a>

### Technology: UbiComp and Wearables

Ubiquitous Computing [SOUND] refers to trend towards embedding computing power in more and more everyday objects. You might also hear it referred to as pervasive computing, and it's deeply related to the emerging idea of an Internet of Things. A few years ago, you wouldn't have found computers in refrigerators and wristwatches, but as microprocessors became cheaper and as the world became increasingly interconnected, computers are becoming more and more ubiquitous. Modern HCI means thinking about whether someone might use a computer while they're driving a car or going on a run. It means figuring out how to build smart devices that offloads some of the cognitive load from the user, like refrigerators that track their own contents and deliver advice to the users right at the right time.

This push for increasing pervasiveness has also lead to [SOUND] the rise of wearable technologies. Exercise monitors are probably the most common examples of this, but smart watches, Google Glass, augmented reality headsets, and even things like advanced hearing aids and robotic prosthetic limbs, are all examples of wearable technology. This push carries us into areas usually reserved for human factors engineering and industrial design, which exemplifies the increasing role of HCI in the design of new products.

<a id="L1-3-technology-robotics"></a>

### Technology: Robotics

A lot of the current focus on robotics is on their physical construction and abilities or on the artificial intelligence that underlies their physical forms. But as robotics becomes more and more mainstream, we're going to see the emergence of a new subfield of human-computer interaction, human-robot interaction. The field actually already exists. The first conference on human robot interaction took place in 2006 in Salt Lake City, and several similar conferences have been created since then. Now as robots enter the mainstream, we're going to have to answer some interesting questions about how we interact with them.

For example, how do we ensure that robots don't harm humans through faulty reasoning. How do we integrate robots into our social lives, or do we even need to? As robots are capable of more and more, how do we deal with the loss of demand for human work? Now these questions all lie at the intersection of HCI, artificial intelligence and philosophy in general. But there are some more concrete questions we can answer as well. How do we pragmatically equip robots with the ability to naturally interact with humans based on things like voice and touch? How do we provide tasks that subtle feedback to humans interacting with robots to confirm their input is being received and properly understood? How do we support humans in teaching things to robots, instead of just programming them? Or alternatively, can we create robots that can teach things to humans? We already see robotics advances applied to things like healthcare and disability services. And I'm really excited to see where you take it next.

<a id="L1-3-technology-mobile"></a>

### Technology: Mobile

One of the biggest changes to computing over the past several years has been the incredible growth of mobile as a computing platform. We really live in a mobile first world and that introduces some significant design challenges.

Screen real estate is now far more limited, the input methods are less precise and the user is distracted. But mobile computing also presents some really big opportunities for HCI. Thanks in large part to mobile we're no longer interested just in a person sitting in front of a computer. With mobile phones, most people have a computer with them at all times anyway. We can use that to support experiences from navigation to star gazing. Mobile computing is deeply related to fields like context aware computing, ubiquitous computing and augmented reality, as it possesses the hardware necessary to compliment those efforts. But even on its own, mobile computing presents some fascinating challenges to address.

For me, the big one is that we haven't yet reached a point where we can use mobile phones for all the tasks we do on computers. Smart phones are great for social networking, personal organization, games, and lots of other things. But we haven't yet reached a point where the majority of people would sit down to write an essay, or do some programming on smart phones. Why haven't we? What do we need to do to make smart phones into true replacements for traditional desktop and laptop computers?

<a id="L1-3-idea-context-sensitive-comp"></a>

### Idea: Context-Sensitive Comp

What time is it? » You can go ahead and go to lunch. » Did that exchange make any sense? I asked Amanda for the time and she replied by saying I can go ahead and go get lunch. The text seems completely non-sensical and yet hearing that, you may have filled in the context that makes this conversation logical. You might think that I asked a while ago what time we were breaking for lunch, or maybe I mentioned that I forgot to eat breakfast. Amanda would have that context and she could use it to understand why I'm probably asking for the time. Context is a fundamental part of the way humans interact with other humans. Some lessons we'll talk about even suggest that we are completely incapable of interacting without context.

If context is such a pervasive part of the way humans communicate, then to build good interfaces between humans and computers, we must equip computers with some understanding of context.

That's where context-sensitive computing comes in. Context-sensitive computing attempts to give computer interfaces the contextual knowledge that humans have in their everyday lives. For example, I use my mobile phone differently depending on whether I'm sitting on the couch at home, or using it in my car, or walking around on the sidewalk. Imagine I didn't have to deliberately inform my phone of what mode I was in though. Imagine if it just detected that I was in my car and automatically brought up Google Maps and Audible for me. Services have started to emerge to provide this, but there's an enormous amount of research to be done on contact sensitive computing. Especially as it relates to things like wearbles, augmented reality, and ubiquitous computing.

<a id="L1-3-idea-gesture-based-interaction"></a>

### Idea: Gesture-Based Interaction

As this course goes on, you'll find that I'm on camera more often than you're accustomed to seeing in a Udacity course. Around half this course takes place with me on camera. There are a couple of reasons for that. The big one is that this is Human Computer Interaction. So it makes sense to put strong emphasis on the Human. But another big on is that when I'm on camera, I can express myself through gestures instead of just word and voice intonations. I can for example make a fist and really drive home and emphasize a point. I can explain that a topic applies to a very narrow portion of the field or a very wide portion of the field. We communicate naturally with gestures every day. In fact, we even have an entire language built out of gestures. So wouldn't it be great if our computers could interpret our gestures as well?

That's the emerging field of Gesture-Based Interaction. You've seen this with things like the Microsoft Connect which has far reaching applications from healthcare to gaming. We've started to see some applications of gesture based interaction on the go as well with wrist bands that react to certain hand motions. Gesture based interaction has enormous potential. The fingers have some of the finest muscle movements, meaning that a system based on finger movements could support an incredible number of interactions. We might see a day when it's possible to type invisibly in the air in front of you based on system's recognition of the movement in the muscles of your wrist. That might finally allow mobile devices to replace traditional computers altogether.

<a id="L1-3-idea-pen-and-touch-based-interaction"></a>

### Idea: Pen- and Touch-Based Interaction

I always find it interesting how certain technologies seem to come around full circle. For centuries we only interacted directly with the things that we built and then computers came along. And suddenly we needed interfaces between us and our tasks. Now, computers are trying to actively capture natural ways we've always interacted. Almost every computer I encounter now days has a touch screen. That's a powerful technique for creating simple user interfaces because it shortens the distance between the user and the tasks they’re trying to accomplish. Think about someone using a mouse for the first time. He might need to look back and forth from the screen to the mouse, to see how interacting down here, change things he sees up here. With a touch based interface, he interacts the same way he uses things in the real world around him. A challenge can sometimes be a lack of precision, but to make up for that we've also create pen based interaction. Just like a person can use a pen on paper, they can also use a pen on a touch screen. And in fact, you might be quite familiar with that, because most Udacity courses use exactly that technology. They record someone writing on a screen. That gives us the precision necessary to interact very delicately and specifically with our task. And as a result tablet based interaction methods have been used in fields like art and music. Most comics you find on the internet are actually drawn exactly like this, combining the precision of human fingers with the power of computation.

<a id="L1-3-idea-information-visualization"></a>

### Idea: Information Visualization

One of the biggest trends of the information age is the incredible availability of data. Scientists and researchers use data science and machine learning to look at lots of data and draw conclusions. But often times those conclusions are only useful if we can turnaround and communicate them to ordinary people. That's where information visualization comes in. Now at first glance you might not think of data visualization as an example of HCI. After all, I could draw a data visualization on a napkin and print in a newspaper and there's no computer involved anywhere in that process. But computers give us a powerful way to re-represent data in complex, animated, and interactive ways. We'll put links to some excellent examples in the notes. Now what's particularly notable about data visualization in HCI is the degree with which it fits perfectly with our methodologies for designing good interfaces. One goal of a good interface is to match the user's **mental model** to the reality of the task at hand. In the same way, the goal of information visualization is to match the reader's mental model of the phenomenon to the reality of it. So the same principles we discussed for designing good representations apply directly to designing good visualizations. After all, a visualization is just a representation of data.

<a id="L1-3-idea-cscw"></a>

### Idea: CSCW

CSCW stands for Computer-Supported Cooperated Work. The field is just what the name says. How do we use computers to support people working together. You're watching this course online. So odds are that you've experienced this closely. Maybe you've worked on a group project with a geographically distributed group. Maybe you've had a job working remotely. Distributed teams are one example of CSCW in action but there are many others. The community often breaks things down into two dimensions.

Time and place. We can think of design as whether or not we're designing for the users in the same time and place or users at different times in different places. This course is an example of designing for different time and different place. You're watching this long after I recorded this, likely from far away from our studio. Work place chat utilities like slack and hipchat would be examples of same time, different place. They allow people to communicate instantly across space, mimicking the real-time office experience. Now imagine a kiosk at a museum that asks visitors to enter their location to create a map of where everyone comes from. Now that would be different time, same place. Everyone uses the interface in the same place, but across time. And even when we're in the same time and place, computers can still support cooperation. In fact, right now, Amanda's running our camera, Ben's running the teleprompter and I'm standing up here talking at you. These different computers are supporting us in cooperating to create this course. So we can often think of CSCW as mediating cooperation across traditional geographic or temporal borders. But it can also help us with collocated simultaneous cooperation.

<a id="L1-3-idea-social-computing"></a>

### Idea: Social Computing

Social computing is the portion of HCI that's interested in how computers affect the way we interact and socialize. One thing that falls under this umbrella is the idea of recreating social norms within computational systems. So for example, when you chat online, you might often use emojis or emoticons. Those are virtual recreations of some of the tacit interaction we have with each other on a day-to-day basis. So, for example, these all take on different meanings depending on the emotion provided. Social computing is interested in a lot more than just emojis, of course.

From online gaming and Wikipedia, to social media, to dating websites, social computing is really interested in all areas where computing intersects with our social lives.

<a id="L1-3-domain-special-needs"></a>

### Domain: Special Needs

One of the most exciting application areas for HCI is in helping people with special needs. Computing can help us compensate for disabilities, injuries, aging. Think of a robotic prosthetic, for example. Of course, part of that is engineering, part of it is neuroscience. But it's also important to understand how the person intends to use such a limb in the tasks they need to perform. That's HCI intersecting with robotics.

Or take another example from some work done here at Georgia Tech by Bruce Walker, how do you communicate data to a blind person? We've talked about informational visualization, but if it's a visualization, it's leaving out a significant portion of the population. So Dr. Walker's sonification lab works on communicating data using sound. A lot of the emerging areas of HCI technology could have extraordinary significance to people with special needs. Imagine virtual reality for people suffering from some form of paralysis. Or imagine using artificial intelligence with context-aware computing to create an autonomous wheelchair. These are projects that would only target a small portion of the population, but the impact of that portion would be absolutely indescribable.

<a id="L1-3-domain-education"></a>

### Domain: Education

Hi, and welcome to educational technology. My name is David Joyner and I'm thrilled to bring you this course.

As you might guess, education is one of my favorite application areas of HCI. In fact, as I'm recording this, I've been teaching educational technology at Georgia Tech for about a year, and a huge portion of designing educational technology is really just straightforward HCI. But education puts some unique twists on the HCI process. Most fascinatingly, education is an area where you might not always want to make things as easy as possible. You might use HCI to introduce some desirable difficulties, some learning experiences for students. But it's important to ensure that the cognitive loads students experience during a learning task is based on the material itself. Not based on trying to figure out our interfaces. The worst thing you can do in HCI for education is raise the student's cognitive load because they're too busy thinking about your interface instead of the subject matter itself. Lots of very noble efforts in designing technology for education have failed due to poor HCI. So if you're interested in going into educational technology, you'll find a lot of valuable lessons in Human Computer Interaction.

<a id="L1-3-domain-healthcare"></a>

### Domain: Healthcare

A lot of current efforts in healthcare are about processing the massive quantities of data that are recorded everyday. But in order to make that data useful, it has to connect to real people at some point. Maybe it's equipping doctors with tools to more easily visually evaluate and compare different diagnoses. Maybe it's giving patients the tools necessary to monitor their own health and treatment options. Maybe that's information visualization so patients can understand how certain decisions affect their well-being. Maybe it's context aware computing that can detect when patients are about to do something they probably shouldn't do. There are also numerous applications of HCI to personal health like Fitbit for exercise monitoring or MyFitnessPal for tracking your diet. Those interfaces succeed if they're easily usable for users. Ideally, they'd be almost invisible. But perhaps the most fascinating upcoming intersection of HCI and health care is in virtual reality. Virtual reality exercise programs are already pretty common to make living an active lifestyle more fun, but what about virtual reality for therapy? That's actually already happening. We can use virtual reality to help people confront fears and anxieties in a safe, but highly authentic place. Healthcare in general is concerned with the health of humans. And computers are pretty commonly used in modern healthcare. So the applications of human computer interaction to healthcare are really huge.

<a id="L1-3-domain-security"></a>

### Domain Security

Classes on network security are often most concerned with the algorithms and encryption methods that must be safeguarded to ensure secure communications. But the most secure communication strategies in the world are weakened if people just refuse to use them. And historically, we've found people have very little patience for instances where security measures get in the way of them doing their tasks. For security to be useful it has to be usable. If it isn't usable, people just won't use it. XEI can increase the usability of security in a number of ways. For one, it can make those actions simply easier to perform. CAPTCHAs are forms that are meant to ensure users are humans. And they used to involve recognizing letters in complex images, but now they're often as simple as a check-box. The computer recognizes human-like mouse movements and uses that to evaluate whether the user is a human. That makes it much less frustrating to participate in that security activity. But HCI can also make security more usable by visualizing and communicating the need. Many people get frustrated when systems require passwords that meet certain standards or complexity, but that's because it seems arbitrary. If the system instead expresses to the user the rationale behind the requirement, the requirement can be much less frustrating. I've even seen a password form that treats password selection like a game where you're ranked against others for how difficult your password would be to guess. That's a way to incentivize strong password selection making security more usable.

<a id="L1-3-domain-games"></a>

### Domain: Games

Video games are one of the purest examples of HCI. They're actually a great place to study HCI, because so many of the topics we discuss are so salient. For example, we discussed the need for logical mapping between actions and effects. A good game exemplifies that. The actions that the user takes with the controller should feel like they're actually interacting within the game world. We discussed the power of feedback cycles. Video games are near constant feedback cycles as the user performs actions, evaluates the results and adjust accordingly. In fact, if you read through video game reviews you'll find that many of the criticisms are actually criticisms of bad HCI. The controls are tough to use, it's hard to figure out what happened. The penalty for failure is too low or too high. All of these are examples of poor interface design. In gaming though there's such a tight connection between the task and the interface. Their frustrations with a task can help us quickly identify problems with the interface.

<a id="L1-3-reflections-exploring-hci"></a>

### Reflections: Exploring HCI

Throughout our conversations we are going to explore some of the fundamental principles and methods of HCI. Depending on the curriculum surrounding this material, you will complete assignments, projects, exams and other assessments in some of these design areas. However we'd also like you to apply what you learn to an area of your choice. So pick an area, either one we've mentioned here, or one you'd like to know about separately, and keep it in mind as we go through the course. Our hope is that by the end of the course you'll be able to apply what you learn here to the area in which you're interested in working.

<a id="L1-3-conclusion-to-exploring-hci"></a>

### Conclusion to Exploring HCI

In this lesson, our goal has been to give you an overview of the exciting expanse of ongoing HCI research and development. We encourage you to select a topic you find interesting, read about it a little bit more, and think about it as you go through the course. Then in unit four we'll provide some additional readings and materials on many of these topics for you to peruse. And in fact you can feel free to jump ahead to there now as well. But before we get too far into what we want to design, we first must cover the fundamental principles and methods of HCI.

— End of Lesson 1.3 — [Back to summary](#A-L1-3) · [Contents](#toc)

---

<a id="L2-1"></a>

## 2.1 Introduction to Principles

**CS6750 · Human–Computer Interaction** — Lecture notes (David Joyner, Summer 2017 lecture book, pp. 74–97)

*Full lecture content, restructured for revision. `»` marks a speaker change in video-transcript dialogue.*

[Back to summary of this lesson](#A-L2-1) · [Table of contents](#toc) · [Keyword index](#partC)

**Sections in this lesson:**

- [Introduction to Design Principles](#L2-1-introduction-to-design-principles)
- [Interfaces: Between Users and Tasks](#L2-1-interfaces-between-users-and-tasks)
- [Quiz: Identifying a Task](#L2-1-quiz-identifying-a-task)
- [5 Tips: Identifying a Task](#L2-1-5-tips-identifying-a-task)
- [Usefulness and Usability](#L2-1-usefulness-and-usability)
- [Exploring HCI: HCI Principles](#L2-1-exploring-hci-hci-principles)
- [Views of the User: Processor](#L2-1-views-of-the-user-processor)
- [Views of the User: Predictor](#L2-1-views-of-the-user-predictor)
- [Views of the User: Participant](#L2-1-views-of-the-user-participant)
- [Good Design, Bad Design](#L2-1-good-design-bad-design)
- [Quiz: Reflections: Views of the User](#L2-1-quiz-reflections-views-of-the-user)
- [User Experience, Sans Design](#L2-1-user-experience-sans-design)
- [Quiz: Design Challenge: Morgan on the Street](#L2-1-quiz-design-challenge-morgan-on-the-street)
- [Conclusion to Intro to Design](#L2-1-conclusion-to-intro-to-design)

<a id="L2-1-introduction-to-design-principles"></a>

### Introduction to Design Principles

[MUSIC] For this portion of our conversation about human computer interaction, we're going to talk about some established principals that we'd uncovered after decades of designing user interfaces. We want to understand the fundamental building blocks of HCI, and separately we'll talk about how to build on those foundations to do new research and new development. To get started, though, let's first define some of the overarching ideas of design principles.

In this lesson, we're going to talk about the way we focus on users and tasks in HCI, not on tools and interfaces on their own.

We're going to talk about the role of the interface and how it mediates between user and the task.

We're going to discuss different views on the user's role in the system.

And we're going to talk about user experience more generally and how it exists at several different levels. Along the way, we'll tackle some design challenges, reflect on our own experiences, and try to apply what we learn to the broader field of HCI.

<a id="L2-1-interfaces-between-users-and-tasks"></a>

### Interfaces: Between Users and Tasks

At the heart of Human Computer Interaction is the idea that users use interfaces to accomplish some task. In general, that interface wouldn't actually have to be technological. This cycle exists for things like using pencils to write things or using a steering wheel to drive a car. But in HCI, we're going to focus on interfaces that are in some way computational or computerized. What's most important here though is our focus on the interaction between the user and the task though the interface, not just the interaction between the user and the interface itself. We're designing interfaces, sure, but to design a good interface, we need to understand both the users goals and the tasks they're trying to accomplish.

Understanding the task is really important. One of the mistakes many novice designers make, is jumping too quickly to the interface, without understanding the task. For example, think about designing a new thermostat. If you focus on the interface, the thermostat itself, you're going to focus on things like the placement of the buttons or the layout of the screen, on whether or not the user can actually read what's there, and things like that. And those are all important questions. But the task is controlling the temperature in an area. When you think about the task rather than just the interface, you think of things like nest, which is a device that tries to learn from its user and act autonomously. That's more than just an interface for controlling whether the heat or the air conditioning is on. That's an interface for controlling the temperature in your house. By focusing on the task instead of just the interface, we can come up with more revolutionary designs like the Nest rather than just iterative improvements to the same thermostats we've been using for years.

<a id="L2-1-quiz-identifying-a-task"></a>

### Quiz: Identifying a Task

Let's try identifying a task real quick. We're going to watch a short clip of Morgan. Watch what she does, and try to identify what task she is performing. [MUSIC] What was the task in that clip?

If you said she's swiping her credit card, you're thinking a little too narrowly. Swiping her credit card is just how she accomplishes her task. We're interested in something more like she's completing a purchase. She's purchasing an item. She's exchanging goods. Those all put more emphasis on the actual task she's accomplishing and let us think more generally about how we can make that interface even better.

<a id="L2-1-5-tips-identifying-a-task"></a>

### 5 Tips: Identifying a Task

Here are five quick tips for identifying a user task. One: Watch real users. Instead just speculating or brainstorming, get out there and watch real users performing in the area in which you’re interested. Two: Talk to them! You don’t have to just watch them. Recruit some participants to come perform the task and talk their way through it. Find out what they’re thinking, what their goals are, what their motives are. Three: Start small. Start by looking at the individual little interactions. It’s tempting to come in believing you already understand the task, but if you do, you’ll interpret everything you see in terms of what you already believe. Instead, start by looking at the smallest operators the user performs. Four: Abstract up. Working from those smaller observations, then try to abstract up to an understanding of the task they’re trying to complete. Keep asking why they’re performing these actions until you get beyond the scope of your design. For example: what is Morgan doing? Swiping a credit card. Why? To make a purchase. Why? To acquire some goods. Why? To repair her car. Somewhere in that sequence is likely the task for which we want to design. Five: You are not your user. Even if you yourself perform the task for which you’re designing, you’re not designing for you: you’re designing for everyone that performs the task. So, leave behind your own previous experiences and preconceived notions about it. These five quick tips come up a lot in the methods unit of HCI. HCI research methods are largely about understanding users, their motivations, and their tasks. So, we’ll talk much more about this later, but it’s good to keep in mind now.

<a id="L2-1-usefulness-and-usability"></a>

### Usefulness and Usability

The ultimate goal of design in HCI is to create interfaces that are both useful and usable. Useful means that the interface allows the user to achieve some task. But usefulness is a pretty low bar. For example, a map is useful for finding your way from one place to another, but it isn't the most usable thing in the world. You have to keep track of where you are. You have to plot your own route. And you have to do all of this while driving the car. So before GPS navigation, people would often manually write down the turns before they actually started driving somewhere they hadn't been before. So our big concern is usability. That's where we get things like navigation apps. Notice how we have to focus on understanding the task when we're performing design. If we set out to design a better map, we probably wouldn't have ended up with a navigation app.

It was through understanding the task of navigation itself that we realized we could offload a lot of the cognitive load of navigation onto the interface, closing the loop between the user and the task of navigation.

<a id="L2-1-exploring-hci-hci-principles"></a>

### Exploring HCI: HCI Principles

Throughout this unit I've repeatedly asked you to revisit the area of HCI that you chose to keep in mind throughout our conversations. Now take a second and try to pull all those things together. You've thought about how your chosen area applies to each of the models in the human's role, how it applies to the various different design guidelines, and how it interacts with society and culture as a whole. How does moving it through those different levels change the kinds of designs you have in mind? Are you building it from low level interactions to high level effects? Are you starting at the top with a desired outcome and working your way down to the individual operations? There are no right or wrong answers here. The important thing is reflecting on your own reasoning process.

<a id="L2-1-views-of-the-user-processor"></a>

### Views of the User: Processor

In looking at human-computer interaction, it's important that we understand the role that we expect the human to play in this overall system.

Let's talk about three different possible types of roles the human can play, processor, predictor, and participant.

First, we might think of the human as being nothing more than a sensory processor. They take input in and they spit output out. They're kind of like another computer in the system, just one that we can't see the inside of. If we are designing with this role in mind then our main concern is that the interface fit within known human limits. These are things like what humans can sense, what they can store in memory, and what they can physically do in the world. In this case, usability means that the interface is physically usable. User can see all the colors, touch all the buttons, and so on. With this model, we evaluate our interfaces with quantitative experiments. That means we take numeric measurements on how quickly the user can complete some task or how quickly they might react to some incoming stimulus. Now, as you might have guessed, the processor view is not the one we'll generally take when we talk about good design. Instead, we'll probably divide our time pretty equally between the other two perspectives.

<a id="L2-1-views-of-the-user-predictor"></a>

### Views of the User: Predictor

A second way of viewing the human is to view them as a predictor. Here, we care deeply about the human's knowledge, experience, expectations, and their thought process. That's why we call them the predictor. We want them to be able to predict what will happen in the world as a result of some action they take. So we want them to be able to map input to output. And that means getting inside their head. Understanding what they're thinking, what they're seeing, what they're feeling when they're interacting with some task. If we're taking this perspective, then the interface must fit with what humans know. It must fit with their knowledge. It must help the user learn what they don't already know and efficiently leverage what they do already know. And toward that end, we evaluate these kind of interfaces with qualitative studies. These are often ex situ studies. We might perform task analyses to see where users are spending their time. Or perform cognitive walk-throughs to understand the user's thought process throughout some task. We can see pretty clearly that this view gives us some advantages over viewing the user simply as a sensory processor, just as another computer in the system. However, here we're still focusing on one user and one task. And sometimes that's useful. But many times we want to look even more broadly than that. That's when we take the third participant peel.

<a id="L2-1-views-of-the-user-participant"></a>

### Views of the User: Participant

A third view on the user is to look at the user as a participant in some environment. That means we're not just interested in what's going on inside their head. We're also interested in what's going on around them at the same time, like what other tasks or interfaces they're using, or what other people they're interacting with. We want to understand for example, what's competing for their attention? What are their available cognitive resources? What's the importance of the task relative to everything else that's going on? So if we take this view, then our interface must fit with the context. It's not enough that the user is able to physically use the system and knows how to use the system. They must be able to actually interact with the system in the context where they need it. And because context is so important here, we evaluate it with in situ studies. We can't simply look at the user and the interface in a vacuum. We have to actually view and evaluate them in the real world using the interface in whatever context is most relevant. If we're evaluating a new GPS application, for example, we need to actually go out and look at it in the context of real drivers driving on real roads. The information we get from them using the app in our lab setting isn't as useful as understanding how they're going to actually use it out in the real world. These are in situ studies, which are studies of the interface and the user within the real complete context of the task.

<a id="L2-1-good-design-bad-design"></a>

### Good Design, Bad Design

[MUSIC] Good design, a GPS system that warns you 20 seconds before you need to make a turn.

» In 1,000 feet, turn left.

» Bad design, a GPS system that warns you two seconds before you need to make a turn.

» Turn left now, hurry. [SOUND] It sounds funny, but which view you take on the user can have a huge impact on the success of the interface. If you view the user just as a sensory processor, you might think that we only need to alert them a second before the upcoming turn because, after all, human reaction time is less than a second. If you view the user as a predictor, you understand they need time to slow the car down and actually make the turn. So they might need a few more seconds to execute the action of turning before being alerted they need to turn. And if you view the user as a participant, you'll understand this is happening while they're going 50 miles down the road with a screaming toddler in the backseat, trying to merge with the driver on a cell phone and the other one eating a cheeseburger. So it would probably be a good idea to give them a few or more reminders before the turn and plenty of time to get in the right position.

<a id="L2-1-quiz-reflections-views-of-the-user"></a>

### Quiz: Reflections: Views of the User

Let's take a moment to reflect on when you've encountered these different views of the user in your own history of interacting with computers. Try to think of a time when a program, an app or a device clearly treated you as each of these types of users for better or for worse.

For me, we have a system at Udacity we use to record hours for those of us that work on some contract projects. It asks us to enter the number of hours of the day we spend on each of a number of different types of work. The problem is that, that assumes something closely resembling the processor model. A computer can easily track how long different processes take. But for me, checking the amount of time spent on different tasks can be basically impossible. Checking my e-mails involves switching between five different tasks a minute. How am I suppose to track that? The system doesn't take into consideration a realistic view of my role in the system. Something more similar to the predictor view would be, well, the classroom you're viewing this in. Surrounding this video are a visual organization of the lesson's content, a meter measuring your progress through the video, representations of the video's transcript. These are all meant to equip you with the knowledge to predict what's coming next. This classroom takes a predictor view of the user. It offloads some of the cognitive load onto the interface allowing you to focus on the material. For the third view I personally would consider my alarm clock an example. I use an alarm clock app called Sleep. It monitors my sleep cycles, rings at the optimal time and tracks my sleep patterns to make recommendations. It understand its role as part of a broader system needed to help me sleep. It goes far beyond just interaction between me and an interface. It integrates into the entire system.

<a id="L2-1-user-experience-sans-design"></a>

### User Experience, Sans Design

By my definition, user experience design is attempting to create systems that dictate how the user will experience them. Preferably that the user will experience them positively. User experience in general, though, is a phenomenon that emerges out of the interactions between humans and tasks via interfaces. We might attempt to design that experience. But whether we design it or not, there is a user experience. It's kind of like the weather, there's never no weather, there's never no user experience. It might be a bad experience if we don't design it very well. But there's always some user experience going on and it emerges as a result of the human's interactions with the task via the interface. But user experience also goes beyond this simple interaction. It touches on the emotional, personal, and more experiential elements of the relationship. We can build this by expanding our understanding of the scope of the user experience. For just a particular individual, this is based on things like the individual's age, sex, or race, personal experiences, gender, expectations for the interface, and more. It goes beyond just designing an interface to help with a task. It touches on whether the individual feels like the interface was designed for them. It examines whether they're frustrated by the interface or joyous about it. Those are all parts of this user experience. We can take this further and talk about user experience at a group level. We can start to think about how interfaces lead to different user experiences among social or work groups. For example, I've known that school reunions seem to be much less important to people who've graduated within the past 15 years. And I hypothesize it's because Facebook and email have played such significant roles in keeping people in touch. It's fundamentally changed the social to group user experience. Those effects can then scope all the way up to the societal level. Sometimes these are unintended. For example, I doubt that the creators of Twitter, foresaw when they created their tool, how it would play a significant role in big societal changes like the Arab spring or, sometimes these might be intentional. For example, it was a significant change when Facebook added new relationship statuses to its profiles to reflect things like civil unions. That simultaneously reflected something that was already changing at the societal level. But it also participated in that change and helped normalize those kinds of relationships. And that then relates back to the individual by making sure the interface is designed such that each individual feels like it's actually designed with them in mind. The options are there for them to feel like they're properly represented within the system. These are all components of the general user experience that we need to think about as we design interfaces.

<a id="L2-1-quiz-design-challenge-morgan-on-the-street"></a>

### Quiz: Design Challenge: Morgan on the Street

So keeping in mind everything we've talked about, let's design something for Morgan. Morgan walks to work, she likes to listen to audio books, mostly nonfiction. But she doesn't just want to listen, she wants to be able to take notes and leave bookmarks. And do everything else you do when you're reading. What would designing for her look like, from the perspectives of viewing her as a processor, a predictor, and a participant? How much this different designs affect user experience as an individual, in her local group of friends, and the society as a whole if the design caught on.

As a processor, we might simply look at what information is communicated to Morgan, when, and how.

As a predictor, we might look instead at how the interface meshes with Morgan's needs with regard to this task, how easy it is to access, how easy the commands are to perform, and so on.

As a participant, we might look at the broader interactions between this interface and Morgan's other tasks and social activities. You might look at how increased access to books changes her life in other ways. But really, this challenge is too big to address this quickly. So instead, let's return to this challenge throughout our conversations, and use it as a running dialogue to explore HCI principles and methods.

<a id="L2-1-conclusion-to-intro-to-design"></a>

### Conclusion to Intro to Design

In this lesson we've covered some of the basic things you need to understand before we start talking about design principles.

We've covered the idea that interface is mediated between users and tasks. And the best interfaces are those that let the user spend as much time thinking about the task as possible.

We covered the idea of usability and how we have to keep in mind the efficiency and user satisfaction of the interface.

We covered three views of the user and how those different views affect how we define usability and evaluation.

We covered how the user experience is not just at the user level, but also at group and even societal levels.

— End of Lesson 2.1 — [Back to summary](#A-L2-1) · [Contents](#toc)

---

<a id="L2-2"></a>

## 2.2 Feedback Cycles

**CS6750 · Human–Computer Interaction** — Lecture notes (David Joyner, Summer 2017 lecture book, pp. 98–127)

*Full lecture content, restructured for revision. `»` marks a speaker change in video-transcript dialogue.*

[Back to summary of this lesson](#A-L2-2) · [Table of contents](#toc) · [Keyword index](#partC)

**Sections in this lesson:**

- [Introduction to Feedback Cycles](#L2-2-introduction-to-feedback-cycles)
- [Feedback Cycles are Fundamental](#L2-2-feedback-cycles-are-fundamental)
- [Gulf of Execution](#L2-2-gulf-of-execution)
- [Gulf of Execution Example](#L2-2-gulf-of-execution-example)
- [5 Tips: Gulfs of Execution](#L2-2-5-tips-gulfs-of-execution)
- [Gulf of Evaluation](#L2-2-gulf-of-evaluation)
- [Gulf of Evaluation Example](#L2-2-gulf-of-evaluation-example)
- [5 Tips: Gulfs of Evaluation](#L2-2-5-tips-gulfs-of-evaluation)
- [Good Design, Bad Design: Feedback Cycles](#L2-2-good-design-bad-design-feedback-cycles)
- [Quiz: Reflections: Feedback Cycles](#L2-2-quiz-reflections-feedback-cycles)
- [Quiz: Feedback Cycles in David's Car 1](#L2-2-quiz-feedback-cycles-in-david-s-car-1)
- [Quiz: Feedback Cycles in David's Car 2](#L2-2-quiz-feedback-cycles-in-david-s-car-2)
- [Quiz: Feedback Cycles in David's Car 3](#L2-2-quiz-feedback-cycles-in-david-s-car-3)
- [Seven Questions for Bridging Gulfs](#L2-2-seven-questions-for-bridging-gulfs)
- [Exploring HCI: Feedback Cycles](#L2-2-exploring-hci-feedback-cycles)
- [Quiz: Design Challenge: Credit Card Readers 1](#L2-2-quiz-design-challenge-credit-card-readers-1)
- [Quiz: Design Challenge: Credit Card Readers 2](#L2-2-quiz-design-challenge-credit-card-readers-2)
- [Quiz: Design Challenge: Credit Card Readers 3](#L2-2-quiz-design-challenge-credit-card-readers-3)
- [Conclusion to Feedback Cycles](#L2-2-conclusion-to-feedback-cycles)

<a id="L2-2-introduction-to-feedback-cycles"></a>

### Introduction to Feedback Cycles

[NOISE] Feedback cycles are the way in which people interact with the world, and then get feedback on the results of those interactions. We'll talk about the ubiquity of those feedback cycles.

Then we'll talk about the gulf of execution, which is the distance between a user's goals and the execution of the actions required to realize those goals.

Then we'll talk about the Gulf of evaluation, which is the distance between the effects of those actions and the user's understanding of those results.

We'll discuss seven questions we should ask ourselves when designing feedback cycles for users.

And we'll also look at applications of these in multiple areas of our everyday lives.

<a id="L2-2-feedback-cycles-are-fundamental"></a>

### Feedback Cycles are Fundamental

Feedback cycles are incredibly ubiquitous, whether or not there's a computational interface involved. Everything from reading to driving a car to interacting with other people could be an example of a feedback cycle in action. They're how we learn everything, from how to walk to how to solve a Rubik's cube to how to take the third order partial derivative of a function. I assume, I've never done that. We do something, we see the result, and we adjust what we do the next time accordingly. You may have even seen other examples of this before, too.

If you've taken Ashok's and mine knowledge-based AI class, we talk about how agents are constantly interacting with, learning from, and affecting the world around them. That's a feedback cycle.

If you've taken Rahim Baez's cyber physical systems course, you've seen this without human involved at all, as a system can autonomously read input and react accordingly. Under some definitions, some people would even call this the artificial intelligence, specifically because it mimics what a human actually does. They act in the world and they evaluate the result.

In fact, if you look at some of the definitions of intelligence out there, you'll find that many people actually define feedback cycles as the hallmark of intelligent behavior. Or they might define intelligence as abilities that must be gained through feedback cycles. Colvin's definition, for example, involves adjusting to one's environment, which means acting in it and then evaluating the results. Dearborn's definition of learning or profiting by experience is exactly this as well. You do something and experience the results, and learn from it. Adaptive behavior in general can be considered an example of a feedback cycle. Behavior means acting in the world. And adapting means processing the results and changing your behavior accordingly. And most generally, Schank's definition is clearly an ability gained through feedback cycles, getting better over time based on evaluation of the results of one's actions in the world. And Schank's general definition, getting better over time, is clearly something that can happen as a result of participation in a feedback cycle. We find that nearly all of HCI can be interpreted in some ways as an application of feedback cycles, whether between a person and a task, a person and an interface, or systems comprised of multiple people and multiple interfaces.

<a id="L2-2-gulf-of-execution"></a>

### Gulf of Execution

In our feedback cycle diagram, we have on the left, some user and on the right, some task or system. The user puts some input into the system through the interface and the system communicates some output back to the user again through the interface. Incumbent on this are two general challenges, the user's interaction with the task through the interface and the task's return to the user of the output via the interface.

The first is called the Gulf of execution. The Gulf of execution can be defined as how do I know what I can do. The user has some goals. How do they figure out how to make those goals a reality? How do they figure out what actions to take to make the state of the system match their goal state? This is the Gulf of execution. How hard is it to do in the interface what is necessary to accomplish the users' goals? Or alternatively, what's the difference between what the user thinks they should have to do and what they actually have to do.

Now there are a number of components of this. The first component, they need to be able to identify what their goal is in the context of the system. There might be a mismatch between their own understanding and the system's structure. Think of transitioning from an old-fashioned VCR to a more modern DVR or from a DVR to watching things on-demand. The user needs to think of their goal in terms of their current system. Second, they need to be able to identify the actions necessary to accomplish their goals. Now that they know what their goal is in the context of the system, they need to identify the actions that it will take to make that goal a reality. And third, once I've identified those actions, they need to actually execute the actions within the interface. Again, imagine someone who's learning to use an on demand video interface, when they're used to using things like VCRs and DVRs. Their goal hasn't changed. They want to watch some program that's already aired. But in the context of a VCR or a DVR, their intention might be to record that program. In the context of an on demand video interface, their intentions instead are to call up the existing version of that program. That's a mismatch between what they think their goal is and what their goal is in the context of this new system. But once they understand what the goal means in their current system, they now need to know how to pull up that program. They need to know how to navigate the menus and find the program that they want to watch and then start it playing. And then once they know what to do, they need to actually execute that series of button presses. For example, they might know what actions to perform but they might not know where to find them. That would present a difficulty in executing those actions. So the gulf of execution takes the user from understanding their own goals to understanding their goals in the context of the system, to understanding the actions necessary to realize those goals, to actually executing those actions. And each of these presents some difficulties.

<a id="L2-2-gulf-of-execution-example"></a>

### Gulf of Execution Example

Let's take a simple example of the gulf of execution. I'm making my lunch, I have my bowl of chili in the microwave. My goal is simple, I want to heat it up. How hard is that? Well, typically when I've been cooking in the past, cooking is defined in terms of the amount of time it takes. So, in the context of this system, I specify my intent as to microwave it for one minute. Now what are the actions necessary to do so? I press Time Cook to enter the time-cooking mode, I enter the time, one minute, and I press Start. I didn't press Start just now, but I would press Start. I specified my intent, microwave for one minute. I specified my actions, pressing the right sequence of buttons, and I executed those actions. Could we make this better? There were a lot of button presses to microwave for just one minute. If we think that's a common behavior, we might be able to make it simpler. Instead of pressing Time Cook one, zero, zero and Start, I might just press one and wait. Watch. [NOISE] So I've narrowed the gulf of execution by shrinking the number of actions required, but I may have enlarged it by making it more difficult to identify the actions required. When I look at the microwave, Time Cook gives me an idea of what that button does. So if I'm a novice at this, I can discover how to accomplish my goal. That's good for the gulf of execution. It's easier to look at the button and figure out what to do than to have to go look, read a manual, or anything like that and find out on your own. But once you know that all you have to do is press one, that's much easier to execute. That's something nice about this interface, it caters to both novices and experts, there's a hard and discoverable way and a short and visible way. But let's rewind all the way back to the goal I set up initially, my goal was to heat up my chili. I specified my intent in terms of the system as microwaving it for one minute. But was that the right thing to do? After one minute, my chili might not be hot enough, this microwave actually has an automatic reheat function that senses the food's temperature and stops when the time seems right. So the best bridge over the gulf of execution might also involve helping me reframe my intention. Instead of going to microwave for one minute, it might encourage me to reframe this as simply heating until ready and letting the microwave do the rest.

<a id="L2-2-5-tips-gulfs-of-execution"></a>

### 5 Tips: Gulfs of Execution

Here are five quick tips for bridging gulfs of execution. Number 1, make functions discoverable. Imagine a user is sitting in front of your interface for the very first time. How would they know what they can do? Do they have to read the documentation, take a class? Ideally the functions of the interface would be discoverable, meaning that they can find them clearly labelled within the interface. Number 2, let the user mess around. You want your user to poke around and discover things so make them feel safe in doing so. Don't include any actions that can't be undone, avoid any buttons that can irreversibly ruin their document or setup. That way the user will feel safe discovering things in your interface. Number 3, be consistent with other tools. We all want to try new things and innovate, but we can bridge gulfs of execution nicely by adopting the same standards that many other tools use. Use CTRL+C for copy and CTRL+V for paste. Use a diskette icon for save even though no one actually uses floppy disks anymore. This makes it easy for users to figure out what to do in your interface. Number 4, know your user. The gulf of execution has a number of components, identifying intentions, identifying the actions to take, and taking the actions. For novice users, identifying their intentions and actions are most valuable, so making commands discoverable through things like menus is preferable. For experts though, actually doing the action is more valuable. That's why many experts prefer the command line. Although it lacks many usability principles targeted at novices, it's very efficient. Number 5, feed forward. We've talked about feed back, which is a response to something the user did. Feed forward is more like feed back on what the user might want to do. It helps the user predict what the result of an action will be. For example, when you pull down the Facebook newsfeed on your phone, it starts to show a little refresh icon. If you don't finish pulling down, it doesn't refresh. That's feedforward, information on what will happen if you keep doing what you're doing. Many of these tips are derived from some of the fundamental principles of design pioneered by people like Don Norman and Jakob Nielsen, and we'll cover them more in another lesson.

<a id="L2-2-gulf-of-evaluation"></a>

### Gulf of Evaluation

The second challenge is for the task to express to the user through the interface the output of the actions that the user took. This is called the gulf of evaluation because the user needs to evaluate the new state of the system in response to the actions they took. Like the gulf of execution, we can think of this in terms of three parts. There's the actual physical form of the output from the interface. What did it actually do in response? There might be something visual, there might be a sound, a vibration, some kind of output. The second is interpretation. Can the user interpret the real meaning of that output? You might think of this in terms of a smartphone. If a smartphone vibrates in your pocket, can you interpret what the meaning of that output was or you have to pull the phone out and actually see? And then the third phase is evaluation. Can the user use that interpretation to evaluate whether or not their goals were accomplished? You can imagine submitting a form online. It might give you output that you interpret to mean that the form was received, but you might not be able to evaluate whether or not the form was actually accepted. Once they've received and interpreted that output, the final step is to evaluate whether or not that interpretation means that their goals were actually realized within the system. Take our on demand video service example again, imagine that the user has gotten all the way to finding the program that they want to watch and they've pressed the play button on their remote. Imagine the interface responds by hiding the menus that they were using to navigate amongst the service. Can they interpret the meaning of that output? And can they evaluate whether or not that interpretation means that their goals were realized? If they're a novice user, maybe not. An expert might correctly interpret that the screen blacking out is because the service is trying to load the video. They then evaluate that interpretation and determine that their goals have been realized. The service is trying to play the show they want to watch. But, a novice user might interpret that output to mean that the service has stopped working at all, like when your computer just shuts down and the screen goes black. They then incorrectly evaluate that their goals were not actually realized in the system. We might get over this by showing some kind of buffering icon. That's a different kind of output from the system that helps the user correctly interpret that the system is still working on the actions that they put in. They then can evaluate that maybe their goals were correctly realized after all because the system is still working to bring up their show. So, as you can see, each of these three stages presents some unique challenges.

<a id="L2-2-gulf-of-evaluation-example"></a>

### Gulf of Evaluation Example

Let's take a thermostat, for example. I have a goal to make the room warmer, so I do something to my thermostat with the intention of making the room warmer. What does the system do as a result? Well, it turns the heat on, that would be the successful result of my action. But how do I know that the heat was turned on? Well, maybe I can hear it, I might hear it click on. But that's a one time kind of thing and it might be quiet. And if I'm mishearing it, I have no way of double checking it. So I'm not sure if I heard it, and I have to go find a vent and put my hand on it and try to feel the heat coming out. And there's more going on in a heater, it might have worked, but the heater doesn't immediately turn on for one reason or the other. These are signs of a large gulf of evaluation. Neither the sound or the vent are optimal displays because they're either hard to reach or possible to miss. Feeling the heat might be easy to interpret, but hearing the heater turn on might not. So either way, I have to do a lot to evaluate whether or not my action was successful. And this is all for a very small piece of feedback. Ideally if I wasn't successful, we want the system to also tell me why I wasn't successful so I can evaluate what I did wrong and respond accordingly. There's a very large gulf of evaluation if there's no indicator on the actual thermostat. So how can we resolve that? Well, simple. We just mark on the thermostat that the heat is on. That sounds trivial, but nothing in the fundamental design of this system demanded a note like this. It's only in thinking about the system from the perspective of the user that we find that need. I can let you know as well, this system still isn't very ideal. For various reasons, it'll turn the heater on or the air conditioning off even when it hasn't reached the temperature I put in. And it gives me no indication of why. I can look at the system and evaluate that the temperature is set to lower than the current temperature in the room. But at the same time, I can see that the heater isn't on. Under those circumstances, I have no way of knowing if the heater's malfunctioning, if the switch is wrong, or I don't even know. In this case, it might just be that it's set to the wrong mode. The mode is visible, but after I remembered to check it, it appears to be malfunctioning. We can imagine an alternative message on the screen indicating the direction of the relationship or something similar that would give some sign that it's currently set incorrectly.

<a id="L2-2-5-tips-gulfs-of-evaluation"></a>

### 5 Tips: Gulfs of Evaluation

Here are five quick tips for bridging gulfs of evaluation. Number one, give feedback constantly. Don't automatically wait for whatever the user did to be processed in the system before giving feedback. Give them feedback that the input was received. Give them feedback on what input was received. Help the user understand where the system is in executing their action by giving feedback at every step of the process. Number two. Give feedback immediately. Let the user know they've been heard even when you're not ready to give them a full response yet. If they tap an icon to open an app, there should be immediate feedback just on that tap. That way, even if the app takes awhile to open, the user knows that the phone recognized their input. That's why icons briefly grey out when you tap them on your phone. Number three. Match the feedback to the action. It might seem like this amount of constant immediate feedback would get annoying and if executed poorly it really would. Subtle actions should have subtle feedback. Significant actions should have significant feedback. Number four, vary your feedback. It's often tempting to view our designs as existing solely on a screen and so we want to give the feedback on the screen. But the screen is where the interaction is taking place, so visual feedback can actually get in the way. Think about how auditory or haptic feedback can be used instead of relying just on visual feedback. Number five, leverage direct manipulation. We talk about this a lot more, but whenever possible, let the user feel like they're directly manipulating things in the system. Things like dragging stuff around or pulling something to make it larger or smaller are very intuitive actions. Because they feel like you're interacting directly with the content. Use that. Again, we talk far more about this in another lesson, but it's worth mentioning here as well. By loading these things into your short-term memory several times, we hope to help solidify them in your long-term memory. And that relationship is actually something we also talk about elsewhere in this unit.

<a id="L2-2-good-design-bad-design-feedback-cycles"></a>

### Good Design, Bad Design: Feedback Cycles

[MUSIC] Good design. A phone that quietly clicks every time a letter is successfully pressed to let you know that the press has been received. Bad design. A phone that loudly shouts every letter you type.

» P. I. C.

Remember small actions get small feedback. The only time you might want your device to yell a confirmation at you is, if you’d just ordered a nuclear launch or something.

<a id="L2-2-quiz-reflections-feedback-cycles"></a>

### Quiz: Reflections: Feedback Cycles

Let's pause for a second, and reflect on the roles of gulfs of execution and gulfs of evaluation in our own lives. So try to think of a time when you've encountered a wide gulf of execution, and a wide gulf of evaluation. This doesn't have to be a computer, it could be any interface. In other words, what was a time when you were interacting with an interface, but couldn't think of how to accomplish what you wanted to accomplish? What was a time when you were interacting with an interface and couldn't tell if you'd accomplished what you wanted to accomplish?

It's not a coincidence that I'm filming this in my basement. This actually happened to me a few weeks ago. The circuit to our basement was tripped, which is where we keep our modem, so our internet was out. Now this is a brand new house and it was the first time we tripped a breaker, so I pulled out my flashlight and I opened the panel. And none of the labels over here clearly corresponded to the breaker I was looking for over here. I ended up trying every single one of them and still it didn't work. I shut off everything in the house. Why didn't it work? In reality, there was a reset button on the outlet itself that had to be pressed. The only reason we noticed it was because my wife noticed something out of the corner of her eye turning on and off as I switched these. That was a terribly large gulf of execution. I knew what I wanted to accomplish, I could translate it into the system's terms easily, reset a breaker. But figuring out the actions to accomplish that goal was very difficult. That's a large gulf of execution. How was that? » [SOUND] What? Sorry, I wasn't paying attention. » You weren't watching? [LAUGH] So I have no way of knowing if that was good or not? Isn't that a terrible gulf of evaluation? I joke, but a lack of feedback on your performance at a task, whether it be filming, like I'm doing now or doing a project like you’ll do later in our material, presents the same kind of poor gulf of evaluation.

<a id="L2-2-quiz-feedback-cycles-in-david-s-car-1"></a>

### Quiz: Feedback Cycles in David's Car 1

15 years ago we might not have talked about cars in the context of discussing HCI, but nowadays this is basically a computer on wheels. So let's talk a little bit about how feedback cycles apply here. Let's start with the ignition. The button that I start my car is right here. Why is it located there?

Before cars had push button starts, this is where you inserted the key to turn on the ignition. Why? I have no idea. But I do know that now, the start button can be placed in any number of different locations. So why do we put it where we've always put it? Well, the reason is, that's where the driver expects it to be placed. We help them across the gulf of execution by designing a system that's consistent with their expectations about how it should work. It makes it easier for them to translate their intentions into actions. Now, other times we might violate this principle because of some other benefits we hope to gain. But generally speaking, when all else is equal, we want to stay consistent with the way users expect our systems to work.

<a id="L2-2-quiz-feedback-cycles-in-david-s-car-2"></a>

### Quiz: Feedback Cycles in David's Car 2

So we know where the ignition button is. Let's press it. [NOISE] Do you think the car turned on?

Well, what do we know? We know the car was off. We know this is clearly the power button based on how it's labeled and where it's located. And most importantly, when I pressed it we heard kind of a happy confirmation-y sound. So did the car turn on? Actually, it didn't. To turn this car on you have press the brake petal while pressing the on button. The car doesn't do a great job of helping us across that goal of execution. There's no indicator that you're doing it wrong until you've actually already done it wrong. But the car does give us a short gulf of evaluation. If you do it incorrectly, an alert pops up on the dashboard letting you know you need to press the brake pedal and then press the on button. The output presented is easy to interpret. As presented in the context of when you need to know that information, so you kind of understand that it’s a response to what you just did. So here we have some trouble with the gulf of execution but the gulf of evaluation is still pretty short. So now that I see this message I press down the brake pedal, press the on button [SOUND] and now the car is on.

<a id="L2-2-quiz-feedback-cycles-in-david-s-car-3"></a>

### Quiz: Feedback Cycles in David's Car 3

So now that we've seen the way this feedback cycle currently works, let's talk about improving it. How might we make this feedback cycle even better? How might we narrow the gulf of execution and the gulf of evaluation?

So here are a few ideas that I had. We know that the screen can show an alert when you try to turn the car on without pressing the brake pedal down. Why not show that alert as soon as the driver gets in the car every time? That doesn't widen the gulf of execution for an expert user, but it does narrow it for a novice user, because even a novice can see that alert the first time they get in the car. But what still throws me off to this day is the sound the car makes when you try and turn it on. Watch. [SOUND] Did the car turn on? No. It didn't that time. [SOUND] Now it turned on. So it plays the same sound initially when you press the button and then plays a different follow up sound to confirm that the car actually turned on. I know why they do this, that one sound just confirms that you pressed the button successfully while the other sound confirms that the car turned on. But for me, I would just as soon have two different sounds confirm whether or not you just pressed the button or whether the car turned on. That way, just the presence of a sound confirms the fact that the button was pressed and the nature of the sound confirms the effect of that press.

<a id="L2-2-seven-questions-for-bridging-gulfs"></a>

### Seven Questions for Bridging Gulfs

In his book, Design of Everyday Things, Don Norman outlines seven questions that we should ask when determining how usable a device is. Number one, how easily can one determine the function of the device? Number two, how easily can one tell what actions are possible? Number three, how easily can one determine the mapping from intention to physical movement? Number four, how easily can one actually perform physical movement? Number five, how easily can one tell what state the system is in? Number six, how easily can one tell if the system is in the desired state? And number seven, how easily can one determine the mapping from system state to interpretation? You'll notice these match our stages from earlier. Interpret you goal on the context of the devices function. Discern what actions are possible on the device. Identify how to perform an action or what action you want to perform. Perform the action. Observe the system's output. Compare the output to the desired state. And interpret the difference between the output and the desired state.

<a id="L2-2-exploring-hci-feedback-cycles"></a>

### Exploring HCI: Feedback Cycles

I asked you earlier to pick an area of HCI in which you're interested, and reflect on it as you go through this course. Depending on the area you selected, feedback cycles can play a huge number of different roles. In healthcare, for example, feedback cycles are critical to helping patients manage their symptoms, and that relies on the results of certain tests being easy to interpret and evaluate. Feedback cycles are also present in some of the bigger challenges for gesture based interactions. It can be difficult to get feedback on how a system interpreted a certain gesture and why it interpreted it that way. Compare that to touch, where it's generally very easy to understand where you touched the screen. So think for a moment about how feedback cycles affect the area you chose to keep in mind.

<a id="L2-2-quiz-design-challenge-credit-card-readers-1"></a>

### Quiz: Design Challenge: Credit Card Readers 1

Lately I've encountered another interesting example of feedback cycles in action. You may have actually seen this before as well. They're the new credit card readers. My wife sells arts and crafts at local events, and so she has these Square readers that can scan credit cards on her phone. One version lets you swipe, and the new version lets you insert the card. So let's check this out real quick. With the swipe version you just insert the card and pull it through, just like a traditional card reader. The problem is there's typically no feedback on whether you're swiping correctly. And what's more is you can be wrong in both directions. You can be both too fast or too slow. So you may have had a time when you were trying to swipe a credit card on some kind of reader, and you kept doing it more and more slowly and deliberately, thinking that the problem was that you had done it too fast originally. And then you discover that you've actually been going too slowly all along and your slowing down was actually counterproductive. There's no feedback here and the space and acceptable input is bounded on both sides. You have to go above one speed and below another speed. But now credit card readers are moving to this model where you just insert the card. You try, at least. In terms of feedback cycles, in what ways is this actually better?

First, in terms of the gulf of execution, the insertion method is actually physically easier to do. While you can be both too fast and too slow with the sliding method, you can't push it too far in with the insertion method. So you know if there's an error, it's because the card isn't far enough into the reader. And second, there's rich feedback with the insertion method. It doesn't even have to come from the screen telling you that you didn't do it correctly. You feel the card stop when it's far enough into the reader. You have immediate physical feedback on whether you're putting it in the right place, and whether you've actually put it far enough in, rather than delayed feedback asking you to try again after some kind of waiting period.

<a id="L2-2-quiz-design-challenge-credit-card-readers-2"></a>

### Quiz: Design Challenge: Credit Card Readers 2

So, using the insertion method is significantly easier. However, the insertion method introduces a new problem. With the sliding method, I never had to actually physically let go of my card, so there was little chance of me walking away without it. With the insertion method, I insert the card and I wait. I'm not used to having to remember to retrieve my card from the card reader. Now this isn't quite as big a deal with these new portable readers, but for the mounted ones you see in stores it can be far more problematic. So how can we build some feedback into the system to make sure people remember their cards when they walk away?

There are a few things we could do here. We might build some kind of buzzer into the card reader to let the customer know when they can take their card out. That would make sure that they don't leave without it. ATM machines often do this, actually. They'll ring a buzzer until the card and the cash are removed. But that's noisy and potentially irritating. It would mess with the ambiance of a restaurant or something like that. We could do something super complicated, like pair the credit card with a smartphone and ring the phone when it gets too far away from the credit card. But that requires adding some new technology to every single credit card, which could be a pretty big expense. So what about something simpler? Why not force a customer to remove the credit card in order to get the receipt and their goods? Unless they're going to walk away without what they came to buy, that'll ensure that they remember their card.

<a id="L2-2-quiz-design-challenge-credit-card-readers-3"></a>

### Quiz: Design Challenge: Credit Card Readers 3

Now notice one last thing about this example. We've been discussing how to make the process of sliding or swiping a credit card easier. What's wrong with that question?

The problem is that we're not focused on the right task. Our task shouldn't be to swipe a credit card, or insert a credit card, or anything like that. Our task should be how to most easily pay for purchases. And possibly the easiest way to do that would be to design a system that lets you just tap your phone against the reader, this reader actually does that. That way, we can use the thing that people have on them at all times. Now maybe that's isn't the best option for various other reasons, but the important thing is we need to focus on what we're really trying to accomplish. Not just how we've done it in the past. We can make incremental improvements just sliding or swiping or inserting a credit card all we want. But we should always keep our eyes on the underlying task that the user needs to accomplish.

<a id="L2-2-conclusion-to-feedback-cycles"></a>

### Conclusion to Feedback Cycles

Today we've talked about arguably the most fundamental concept of human computer interaction, feedback cycles. We describe feedback cycles for our purposes as the exchange of input and output between a user and a system to accomplish some goal.

We discussed feedback cycles' incredible ubiquity in other fields in discussions.

We talked about gulfs of execution, the distance between knowing what they want to accomplish and actually executing the steps necessary to accomplish it.

We talked about gulfs of evaluation, the distance between making some change in the system and evaluating whether or not the goal was accomplished.

We introduced the seven questions we need to ask ourselves to bridge those goals. Now that we understand these goals, our next goal is to understand methods for crossing them.

— End of Lesson 2.2 — [Back to summary](#A-L2-2) · [Contents](#toc)

---

<a id="L2-3"></a>

## 2.3 Direct Manipulation

**CS6750 · Human–Computer Interaction** — Lecture notes (David Joyner, Summer 2017 lecture book, pp. 128–154)

*Full lecture content, restructured for revision. `»` marks a speaker change in video-transcript dialogue.*

[Back to summary of this lesson](#A-L2-3) · [Table of contents](#toc) · [Keyword index](#partC)

**Sections in this lesson:**

- [Introduction to Direct Manipulation and Invisible Interfaces](#L2-3-introduction-to-direct-manipulation-and-invisible-interfaces)
- [Direct Manipulation: The Desktop Metaphor](#L2-3-direct-manipulation-the-desktop-metaphor)
- [Direct Manipulation: The Desktop Metaphor](#L2-3-direct-manipulation-the-desktop-metaphor-2)
- [Paper Spotlight: "Direct Manipulation Interfaces"](#L2-3-paper-spotlight-direct-manipulation-interfaces)
- [Exploring HCI: Direct Manipulation](#L2-3-exploring-hci-direct-manipulation)
- [Quiz: Reflections: Direct Manipulation](#L2-3-quiz-reflections-direct-manipulation)
- [Babies and Direct Manipulation](#L2-3-babies-and-direct-manipulation)
- [Quiz: Exercise: Direct Manipulation](#L2-3-quiz-exercise-direct-manipulation)
- [Making Indirect Manipulation](#L2-3-making-indirect-manipulation)
- [Exploring HCI: Direct Manipulation](#L2-3-exploring-hci-direct-manipulation-2)
- [Invisible Interfaces](#L2-3-invisible-interfaces)
- [Good Design, Bad Design In](#L2-3-good-design-bad-design-in)
- [Invisibility by Learning](#L2-3-invisibility-by-learning)
- [Invisibility by Design](#L2-3-invisibility-by-design)
- [5 Tips: Invisible Interfaces](#L2-3-5-tips-invisible-interfaces)
- [Quiz: Reflections: Invisibility by Design](#L2-3-quiz-reflections-invisibility-by-design)
- [Quiz: Design Challenge: The](#L2-3-quiz-design-challenge-the)
- [Conclusion to Direct Manipulation](#L2-3-conclusion-to-direct-manipulation)

<a id="L2-3-introduction-to-direct-manipulation-and-invisible-interfaces"></a>

### Introduction to Direct Manipulation and Invisible Interfaces

[MUSIC] Today we'll talk about two applications of good feedback cycles. Direct manipulation and invisible interfaces. Direct manipulation is the principle that the user should feel as much as possible like they're directly controlling the object of their task. So for example, if you're trying to enlarge an image on your phone, it might be better to be able to drag it with your fingers rather than tapping a button that says, zoom in. That way you're really interacting directly with the photo. New technologies like touch screens are making it more and more possible to feel like we're directly manipulating something, even when there's an interface in the way.

At their best, the interface actually disappears, which is what we mean by an invisible interface. With an invisible interface the user has to spend no time thinking about the interface that they're using. All their time is dedicated to thinking about the task that they're performing.

<a id="L2-3-direct-manipulation-the-desktop-metaphor"></a>

### Direct Manipulation: The Desktop Metaphor

Our goal is to narrow the gulf of execution and the gulf of evaluation as much as possible. And arguably the ultimate form of this is something called direct manipulation. Now today direct manipulation is a very common interaction style. But in the history of HCI it was a revolutionary new approach. Now to understand direct manipulation, let's talk about the desktop metaphor. The files and folders on your computer are meant to mimic physical files and folders on a desktop. So, here are on my physical desktop, I have some files. What do I do if I want to move them? Well, I pick them up and I move them. What do I do if I want to put them in a folder? I pick them up and put them in the folder. I'm physically moving the files from where they are to where I want them to be. If files and folders on a computer are meant to mimic files and folders on a physical desk, then shouldn't the act of moving them also mimic the real world action of moving them? Wouldn't it narrow the gulf execution to leverage that real world experience and that real world expectation?

<a id="L2-3-direct-manipulation-the-desktop-metaphor-2"></a>

### Direct Manipulation: The Desktop Metaphor

Files and folders on my computer are meant to mimic files and folders on my physical desk. So we ideally want the action of moving them around on my computer to mimic the action of moving them around on my physical desk. But it wasn't always like this. Before graphical user interfaces were common, we moved files around using command line interfaces like this. The folder structure is still the same on the operating system. But instead of visualizing it as folders and icons, I'm interacting with a text-based command line. To view the files, I might need to type a command like ls, which I just have to remember. If I don't remember that command, I don't have much recourse to go find out what I'm supposed to be doing. To move a file, I need to type something like this. I have to type the command, the file I want to move, and the folder I want to move it to. Again, if I forget the name of that command, or the order of the parameters to provide, there's not a whole lot I can do to recover from that. I need to run off to Google and find out what the correct order of the commands was. Which is actually what I did before filming this video because I don't actually use the terminal very often. Then when I execute that command, there's not a lot of feedback to let me know if it actually executed correctly. I might need to change folders to find out. There I see the files present in that folder but I had to go and look manually. There's nothing really natural about this. Now don't get me wrong, once you know how to interact with this interface, it's very efficient to use. But when you're a novice at it, when you've never used it before, this is completely unlike the task of managing physical files on your real desk.

Then, the computer mouse came along. And with it came the ability to move a mouse around the screen. Equipped with this, my action in moving files and folders becomes much more direct. I can actually just click the file I want to move and drag it into the new folder. I get instant feedback by the fact that the file disappeared as soon as I dragged it over. And there was a sound effect that you may or may not have been able to hear. So now instead of typing in some cryptic command that I just have to be able remember, I can just click on the file I want to move, and physically drag it to the folder in which I want to have it. That's a very natural interaction, it mimics what I do on my physical desk. Moving the mouse around is a lot better than having to type in those commands, but the gulf of execution and evaluation are still present, especially for some novice users. There's still some interpretation that has to happen to understand that when I move my hand a little left on the mouse, the cursor on screen will move to the left as well. And while clicking feels kind of like grabbing, there's still some interpretation there. It's more direct than the command line, but there's still a gap. The modern touchscreens made direct manipulation more direct than ever. Let's say I want to put an icon into a folder on my screen. How do I do it? I hold down the icon, and I drag it to the screen. The fact that if I wanted to move something around my desk, I would have to hold it down, means that this is almost entirely direct manipulation. I don't need any prior knowledge to attempt to do what feels natural for moving that icon into that folder. That gives us a nice, general heuristic to keep in mind. How do we help the user interact most closely with the target of their task? How do we make it so they're manipulating it as directly as possible?

<a id="L2-3-paper-spotlight-direct-manipulation-interfaces"></a>

### Paper Spotlight: "Direct Manipulation Interfaces"

The Seminal Paper on Direct Manipulation Interfaces came out in 1985 coauthored by Edwin Hutchins, James Hollan, and Don Norman. We'll talk a lot more about Hutchins and Norman later in our conversations. Hutchins coauthored the foundational paper on distributed cognitive and Norman created one of the most accepted sets of design principles in his seminal book, the Design of Everyday Things. But in 1985, direct manipulation was starting to become a more common design strategy. Hutchins, Hollan, and Norman identified two aspects of directness.

The first was distance. Distance is the distance between the users goals and the system itself. This is the idea of gulfs of execution and evaluation that we talked about in the context of feedback cycles. They write that "the feeling of directness is inversely proportional to the amount of cognitive effort it takes to manipulate and evaluate the system." In other words, the greater the cognitive load required to use the system, the less direct the interaction with the system actually feels.

The authors break distance into two components, semantic distance and articulatory distance. Semantic distance refers to the distance between the user's goals and their expression in the system. In other words, it's how hard it is to know what to do. Articulatory distance is the distance between expression and its execution. In other words, it's how hard it is to actually do what you know to do. You might notice that semantic distance encompasses our identify intentions and identify actions part of our gulf of execution. And articulatory distance comprises that execute actions phase.

This is brought together here in figure 6 from this paper. The user starts with some goals and translates those goals into the intentions in the context of the interface. They then translate those intentions into the form of the input, the actions, and execute those actions. The system then does something and then gives back some form of output. The user then interprets the form of that output to discern the meaning of that output, and then evaluates whether or not that meaning matches their goals. So to take an example, when I brought up this figure, I needed to rotate the paper to display it correctly. That was my goal. I translated that goal into the context of the application, a rotate option that was probably hidden somewhere. I then identified the action, which was pressing the rotate button, and I executed that action. The system then did something and returned the output to me. The output specifically was the paper turned upside down, instead of turned the way I wanted it. That was the form of the output. I then interpreted that form to discern the meaning that it had rotated it the wrong way. I evaluated that my goals weren't accomplished and now I knew what to do next. I then pressed the button two more times to rotate it twice again, and the system then returned that output to me. I interpreted the form of that output to mean that the figure was now right side up, and I evaluated that that matched my initial goals. You might be able to see that this cycle is happening constantly whenever you're interacting with a computational interface. You could think of it in terms of broad tasks like searching a document for some key word or you could think of it in terms of each individual little tasks like interacting with the menus and pulling up the right prompts. But distance is only one component of direct manipulation. It's possible to have interfaces with very little distance that nonetheless are not examples of this kind of direct interaction. Everything we've talked about so far is true of feedback cycles in general, not just of direct manipulation.

That's why the second component of this is direct engagement. What sets direct manipulation apart is this second component. The authors of the paper write that "the systems that best exemplify direct manipulation all give the qualitative feeling that one is directly engaged with the control of the objects— not with the programs, not with the computer, but with the semantic objects of our goals and intentions." If we're moving files we should be physically moving the representations of the files. If we're playing a game, we should be directly controlling our characters. If we're navigating channels, we should be specifically selecting clear representations of the channels that we want. That's what takes a general, good feedback cycle and makes it an instance of direct manipulation.

We can shorten the gulfs of execution and evaluation in a number of ways without direct manipulation, but direct manipulation is a powerful method for shortening that distance.

<a id="L2-3-exploring-hci-direct-manipulation"></a>

### Exploring HCI: Direct Manipulation

Virtual reality right now is making some incredible strides in facilitating direct manipulation in places where it just hasn't been possible before. Traditionally, when designers are designing stuff in 3D, they're forced to use a 2D interface. That translation from 2D to 3D really gets in the way of directly manipulating whatever is being designed. Through virtual reality though, designers are able to view what they're designing in 3D as if it's in the room there with them. They can rotate it around with the same hand motions you'd use to rotate a physical object. They can physically move around the object to get different angles on it. So virtual reality is allowing us to bring the principle of direct manipulation to tasks it hasn't been able to touch before. But there's still a lot of work to do. Gesture interfaces like those used in virtual reality struggle with some feedback issues. We aim to make the user feel like they're physically manipulating the artifact. But when you're working with something with you're hands, it pushes back against you. How do we recreate that in virtual reality?

<a id="L2-3-quiz-reflections-direct-manipulation"></a>

### Quiz: Reflections: Direct Manipulation

Take a moment real quick and reflect on some of the tasks you perform with computers day-to-day. What are some of the places where you don't interact through direct manipulation? If you're having trouble thinking of one, think especially about places where technology is replacing things you used to do manually. Chances are, the physical interface was a bit closer to the task than the new technical one. How can the technical interface better leverage direct manipulation?

When I was writing the script for this exact video, I was interrupted by a text message from a friend of mine. And in the reply I was writing, I wanted to include a smiley face. We know that using emojis and emoticons tends to humanize textual communication. On my phone, the interface for inserting an emoji is to tap an icon to bring up a list of all the emojis and then select the one that you want. When I'm reacting to someone in conversation, I'm not mentally scrolling through a list of all my possible emotions and then choosing the one that corresponds. I'm just reacting naturally. Why can't my phone capture that? Instead of having to select smiling from a list of emotions, maybe my phone could just have a button to insert the emotion corresponding to my current facial expression. So to wink, I would just wink. To frown, I would just frown. It wouldn't be possible to capture every possible face, but for some of the most commonly used ones, it might be more efficient.

<a id="L2-3-babies-and-direct-manipulation"></a>

### Babies and Direct Manipulation

There may be no better example of the power of direct manipulation than watching a baby use an interface. Let's watch my daughter, Lucy, try and use her Kindle Fire tablet. My daughter Lucy is 18 months old, yet when I give her an interface that uses direct manipulation, she's able to use it. She wouldn't be able to use a keyboard or a mouse yet, but because she's directly interacting with the things on the screen, she can use it.

Actually, there might be an even better example of direct manipulation in action. There are games made for tablet computers for cats. Yes, cats can use tablet computers when they use direct manipulation.

<a id="L2-3-quiz-exercise-direct-manipulation"></a>

### Quiz: Exercise: Direct Manipulation

Let's try a quick exercise on direct manipulation. The Mac touchpad is famous for facilitating a lot of different kinds of interactions. For example, I can press on it to click, press the two fingers to right-click. I can pull up and down with two fingers to scroll up and down. I can double tap with two fingers to scroll in and out a little bit. And I can pinch to zoom in and out a lot more. Which of these are good examples of direct manipulation in action?

Now there's some room for disagreement here, but I think these five seem to be pretty cut and dry. We can think about whether or not these are direct manipulation by considering whether or not what we're doing to the touchpad is what we'd like to do to the screen itself. For clicking, I would consider that direct manipulation because just as we press directly on the screen we're pressing directly on a touchpad. Right-clicking though, the two finger tap, doesn't really exemplify direct manipulation, because there's nothing natural about using two fingers to bring up a context menu as opposed to using one to click. We have to kind of learn that behavior. Scrolling makes sense because with scrolling it's like I'm physically pulling the page up and down to see different portions of it. The two finger tap for zooming in and out a little bit though isn't really direct manipulation, because there's no real clear reason that needs to zoom in, zoom out. Pinching on the other hand though, makes sense. Because it's as if I'm physically grabbing the page and shrinking and enlarging it. So some of these I would say are pretty good examples of direct manipulation. While others are things that we kind of have learn to do.

<a id="L2-3-making-indirect-manipulation"></a>

### Making Indirect Manipulation

The Mac Touchpad has some interesting examples of how you can make indirect manipulation feel more direct. For example, if I swipe from the right to the left on the touchpad with two fingers, it pulls up this notification center over on the right. This feels direct because the notification center popped up in the same place on the screen that I swiped on the touchpad. The touchpad is almost like a miniature version of the screen. But they could have placed a notification center anywhere and used any kind of interaction to pull it up. This isn't like scrolling where there is something fundamental about the content that demands a certain kind of interaction. They could have designed this however they wanted. But by placing the notification center there and using that interaction to pull it up, it feels more direct. Now, animation can also help us accomplish this. On the Touchpad, I can clear the windows off my desktop by kind of spreading out my fingers on the touchpad, and the animation shows them going off to the side. And while that's kind of like clearing off your desk, I'd argue it's not close enough to feel direct except that the animation on screen mimics that action as well. The windows could have faded away or they could have just slid to the bottom and still accomplish the same function of hiding what's on my desktop. But the animation they chose reinforces that interaction. It makes it feel more direct. The same thing actually applies with Launchpad, which we bring up with the opposite function by pinching our fingers together. The animation looks kind of like we're pulling back a little bit or zooming out and we see the launch pad come into view, just as the gesture is similar to zooming out on the screen. So direct manipulation isn't just about designing interactions that feel like you're directly manipulating the interface. It's also about designing interfaces that lend themselves to interactions that feel more direct.

<a id="L2-3-exploring-hci-direct-manipulation-2"></a>

### Exploring HCI: Direct Manipulation

Depending on the area of HCI that you chose to explore, direct manipulation might be a big open- question. So for gesture based interaction for example, you're generally not actually touching anything. Direct manipulation is contingent on immediate feedback that maps directly to the interaction. So how do you create that in a gesture-based interface? This is a big challenge for virtual reality as well. Virtual reality thrives on making you feel like you're somewhere else, both visually and auditorily, but it has a long way to go kinesthetically. How do you create the feeling of direct manipulation based on physical action when you can only give feedback visually or auditorily? So take a second and reflect on how these principals of direct manipulation apply to your chosen area of HCI.

<a id="L2-3-invisible-interfaces"></a>

### Invisible Interfaces

Whether through using direct manipulation, through innovative approaches to shrinking these gulfs or through the user's patience and learning, our ultimate goal is for the interface between the user and the task to become invisible.

What this means is that even though there is an interface in the middle, the user spends no time thinking about it. Instead, they feel like they're interacting directly with the task rather than with some interface.

So for example, I have a stylus and I'm going to write on this tablet computer. I'm interacting with an interface just translating my drawing into data in the system. But for me, this feels just like I'm writing on a normal page. That feels just like writing on paper. This interface between me and the data representation of my drawing underneath is pretty much invisible. I feel like I'm writing on paper.

Contrast that with trying to draw with a mouse. That feels extremely unnatural. I'm very well aware of the mouse as the interface between myself and this drawing task. So the direct manipulation facilitated by the stylus gets me much closer to my task and helps the interface disappear between me and what I'm trying to accomplish.

<a id="L2-3-good-design-bad-design-in"></a>

### Good Design, Bad Design In

[MUSIC] Good design. Interfaces that are metaphorically invisible.

Bad design, interfaces that are literally invisible. Well, kind of, just your base interfaces are in one sense literally invisible, that's actually why it's so important to give great feedback. Because otherwise, it's tough to gauge the success of a gesture interaction.

<a id="L2-3-invisibility-by-learning"></a>

### Invisibility by Learning

We shouldn't fall into the trap of assuming that just because an interface has become invisible, the design is great. Interfaces become invisible not just through great design, but also because users learn to use them. With enough practice and experience, many users will become sufficiently comfortable with many interfaces to feel invisibly integrated in the task. So take driving for example. Lets say I'm driving a car and I discover I'm headed right for someone. What's my reaction? Well I turn the wheel to the side and I press my brake. It's instinctive. I do it immediately, but think about that action. If I was just running down the street and suddenly I saw someone in front of me would it be natural for me to go like that? Of course not. The steering wheel was an interface I used to turn to the left. But it's become invisible during the task of driving because of all my practice with it. But just because the interface has become invisible doesn't mean it's great interface. People spend months learning to drive, they pay hundreds of dollars for classes. And they have to pass a complicated test. Driving is important enough that it can have that kind of learning curve. But for the interfaces that we design, we generally can't expect users to give us an entire year just to learn to use them. We'll be lucky if they give us an entire minute to learn to use them. So our goal is to make our interfaces invisible by design.

<a id="L2-3-invisibility-by-design"></a>

### Invisibility by Design

Our goal is to create interfaces that are invisible from the moment the user starts using them. They should feel immediately as if they're interacting with the task underlying the interface. Now this is an extremely tall order and one we honestly probably won't meet very often, but it's the goal. In fact, in my opinion, this is why people tend to underestimate the complexity of HCI. When you do things right, people won't be aware that you've done anything at all. So how do we create interfaces that are invisible from the very first moment the user starts using them? That's precisely what we'll discuss in a lot of our conversations about HCI. We'll talk about principles for creating interfaces that disappear like leveraging prior expectations and providing quick feedback. We'll also talk a lot about how to get inside the user's head and understand what they're seeing when they look at an interface that we can make sure that they're internal mental model matches the system. In fact, if we consider invisibility to be a hallmark of usable design, then this entire course could be retitled Creating Invisible Interfaces.

<a id="L2-3-5-tips-invisible-interfaces"></a>

### 5 Tips: Invisible Interfaces

Here are five tips for designing invisible interfaces. Number 1, use affordances. We talk more about affordances when we discuss design principles and heuristics. But affordances are places where the visual design of the interface is just how it's supposed to be used. Buttons are for pressing. Dials are for turning. Switches are for flicking. Use these expectations to make your interface more usable. Number 2, know your user. Invisibility means different things to different people. Invisibility to a novice means the interactions are all natural. But invisibility to an expert means maximizing efficiency. Know for whom you're trying to design. Number 3. Differentiate your user. Maybe you're designing something for both novices and experts. If that's the case, provide multiple ways of accomplishing tasks. For example, having copy and paste under the Edit menu keeps those options discoverable. But providing Ctrl C and Ctrl V as shortcuts keep those actions efficient. Number 4. Let your interface teach. When we think of teaching users how to use our software we usually think of tutorials or manuals. But ideally the interface itself will do the teaching. For example, when users select Copy and Paste from the Edit menu, they see the hotkey that corresponds to that function. The goal is to teach them a more efficient way of performing the actions without requiring them to already know that in order to do their work. Number 5. Talk to your user. We'll say this over and over again, but the best thing you can do is talk to the user. Ask them what they're thinking while they use an interface. Note especially whether they're talking about the task or the interface. If they're talking about the interface, then it's pretty visible.

<a id="L2-3-quiz-reflections-invisibility-by-design"></a>

### Quiz: Reflections: Invisibility by Design

Reflecting on where we've encountered invisible interfaces is difficult, because they were invisible. What makes them so good is the fact that we didn't have to notice them. But give it a try anyway. Try to think of a time where you picked up a new interface for the very first time and immediately knew exactly how to use it to accomplish the task you had in mind.

One of my favorite examples of an interface that is invisible by design comes from a video game called Portal 2. In lots of video games, you use a control stick to control the camera in game, but different people have different preferences for how the camera should behave. Some feel if you press up, you should look up. Others like myself, feel if you press down you should look up, more like you're controlling an airplane with a joystick. In most games you have to set this manually by going to options, selecting camera controls, and enabling or disabling a y axis and it's just a chore. But in portal two, watch what happens. » You will here a buzzer. When you hear the buzzer, look up at the ceiling. [SOUND] Good. You will hear a buzzer. When you hear the buzzer, look down at the floor. [SOUND] Good. This completes the gymnastic portion of your mandatory physical and mental wellness exercise. » Did you see that? It was so subtle you might not have even noticed it. A character in the game asked me to look up. The game assumed whichever direction I pressed was the way I would want to press when I want to look up. And set my preference accordingly. No option screen, no changing settings. The game automatically and invisibly had me complete my goal of correctly setting my camera preference.

<a id="L2-3-quiz-design-challenge-the"></a>

### Quiz: Design Challenge: The

For this design challenge, let's tackle one of the most common problems addressed in undergraduate HCI classes, designing a better remote control. Now, these probably aren't very good interfaces. And that's not to say that they're poorly designed, but the constraints on how many different things they have to do and how limiting the physical structure can be, make these difficult to use. You might have seen humorous images online of people putting tape over certain buttons on the controls to make them easier to use for their parents or their kids. How would we design an invisible interface for universal remote control, one that doesn't have the learning curves that these have?

Personally I think this is a great candidate for a voice interface. And in fact, Comcast, Amazon and others have already started experimenting with voice interfaces for remote controls. One of the challenges with voice interfaces is that generally the commands aren't very discoverable. Generally, if you don't know what you can say, you have no way of finding out. But watching TV and movies is such a normal part of our conversations that we already have a vocabulary of how to say what we want to do. The challenge is for us designers to make a system that can understand that vocabulary. That way when I say, watch Community, it understands that Community is a TV show and it tries to figure out, do I grab it from the DVR, do I grab it from On Demand, do I see if it's on live? The vocabulary for the user was very natural. So for example, watch Conan.

» Well tonight, a fan named David Joiner thinks he caught a mistake. He says it happened when I was telling a joke recently about Rand Paul.

» Hey Conan, I was watching your episode on April 17th, and you said that Rand Paul wanted to run for president.

I had to put that in there somewhere.

<a id="L2-3-conclusion-to-direct-manipulation"></a>

### Conclusion to Direct Manipulation

Today we have talked about two applications of effective feedback cycles. Direct manipulation, and invisible interfaces. We talked about how interfaces are most effective when the user has a sense that they're directly manipulating the object in their task. We talked about how modern technology like touch screens and virtual reality are making it possible for manipulation to feel more and more direct. We talked about how the most effective interfaces become invisible between the user and their task. It's just that the user spends no time at all thinking about the interface. And we talked about how interfaces can become invisible via either learning or design and are most interested in designing them to become invisible. To a large extent, that's the definition of usable design. Designing interfaces that disappear between the user and their task.

— End of Lesson 2.3 — [Back to summary](#A-L2-3) · [Contents](#toc)

---

<a id="L2-4"></a>

## 2.4 Human Abilities

**CS6750 · Human–Computer Interaction** — Lecture notes (David Joyner, Summer 2017 lecture book, pp. 155–186)

*Full lecture content, restructured for revision. `»` marks a speaker change in video-transcript dialogue.*

[Back to summary of this lesson](#A-L2-4) · [Table of contents](#toc) · [Keyword index](#partC)

**Sections in this lesson:**

- [Introduction to Human Abilities](#L2-4-introduction-to-human-abilities)
- [Information Processing](#L2-4-information-processing)
- [Sensation and Perception: Visual](#L2-4-sensation-and-perception-visual)
- [Sensation and Perception: Auditory](#L2-4-sensation-and-perception-auditory)
- [Sensation and Perception: Haptic](#L2-4-sensation-and-perception-haptic)
- [Quiz: Design Challenge: Message Alerts](#L2-4-quiz-design-challenge-message-alerts)
- [Quiz: Memory: Perceptual Store](#L2-4-quiz-memory-perceptual-store)
- [Quiz: Memory: Short Term and Chunking](#L2-4-quiz-memory-short-term-and-chunking)
- [Quiz: Memory: Short Term and Recognition](#L2-4-quiz-memory-short-term-and-recognition)
- [Memory: Short Term Takeaways](#L2-4-memory-short-term-takeaways)
- [Memory: Long Term Memory](#L2-4-memory-long-term-memory)
- [Cognition: Learning](#L2-4-cognition-learning)
- [Cognition: Cognitive Load](#L2-4-cognition-cognitive-load)
- [Quiz: Reflections: Cognitive Load](#L2-4-quiz-reflections-cognitive-load)
- [5 Tips: Reducing Cognitive Load](#L2-4-5-tips-reducing-cognitive-load)
- [Motor System](#L2-4-motor-system)
- [Exploring HCI: Human Abilities](#L2-4-exploring-hci-human-abilities)
- [Conclusion to Human Abilities](#L2-4-conclusion-to-human-abilities)

<a id="L2-4-introduction-to-human-abilities"></a>

### Introduction to Human Abilities

[MUSIC] Human computer interaction starts with human. So it's important that we understand who the human is, and what they're capable of doing. In this lesson, we're going to bring up some psychology of what humans can do. We'll look at three systems. Input, processing, and output.

Input is how stimuli are sent from the world, and perceived inside the mind.

Processing is cognition, how the brain stores, and reasons over the input it's received.

Output is how the brain then controls the individual's actions out in the world. Now, we're going to cover a lot of material at a very high level. If you're interested in hearing more, I recommend taking a psychology class, especially one focusing on sensation and perception. We'll put some recommended courses in the notes.

<a id="L2-4-information-processing"></a>

### Information Processing

In discussing human abilities, we're going to adopt something similar to the processor view of the human. For now we're interested in what they can do, physically, cognitively, and so on.

So we're going to focus exclusively on what's going on over here. We're going to look at how the person makes sense of input, and how they then act in the world. And right now, we're not going to worry too much about where that input came from, or what their actions in the world actually do. Notice that in this lesson we're discussing the human, almost the same way we discuss the computer, or the interface, in most lessons. The human is something that produces output and consumes input, just like a computer might be otherwise. But for now, we're only interested in how the human does this.

<a id="L2-4-sensation-and-perception-visual"></a>

### Sensation and Perception: Visual

Let's start by talking a bit about what the average person can sense and perceive. So, here we have Morgan again. Morgan has eyes. Morgan's eyes are useful for a lot of things.

The center of Morgan's eye is most useful for focusing closely on color or tracking movement. So, we can assume that the most important details should be placed in the center of her view. Morgan's peripheral vision is good for detecting motion, but it isn't as good for detecting color or detail. So while we might use her periphery for some alerts, we shouldn't require her to focus closely on anything out there.

As a woman, Morgan is unlikely to be colorblind, she has about a 1 in 200 chance. Men have a much greater prevalence of color blindness at about 1 in 12. Either way, that's a significant body of people. So we want to avoid relying on color to understand the interface. We can use it to emphasize knowledge that it's already present in the system, but using the system shouldn't rely on perceiving color. Sight is directional. If Morgan's looking the wrong way or has her eyes closed, she'll miss visual feedback.

As Morgan gets older, her visual acuity will decrease. So if we're designing something with older audiences in mind, we want to be careful of things like font size. Ideally, these would be adjustable to meet the needs of multiple audiences. All together though, Morgan's visual system is hugely important to her cognition. The majority of concepts we cover in HCI are likely connected to visual perception. [SOUND]

<a id="L2-4-sensation-and-perception-auditory"></a>

### Sensation and Perception: Auditory

Morgan also has ears.

Morgan can discern noises based on both their pitch and their loudness.

Her ears are remarkably good at localizing sound as well. In fact, she can tell the difference between a nearby quiet sound and a far away loud sound. Even if their relative pitches and loudnesses are the same when they reach her ear.

Unlike vision, hearing isn't directional. Morgan can't close her ears or point her ears the wrong direction so she can't as easily filter out auditory information. That might be useful for designing alerts, but it's problematic for overwhelming her or sharing too much information with the people around her.

<a id="L2-4-sensation-and-perception-haptic"></a>

### Sensation and Perception: Haptic

Morgan's skin can feel things.

It can't feel at a distance but it can feel when things are touching right up against it.

It can feel a variety of different types of input, like pressure, vibration and temperature. Like listening, Morgan can't easily filter out touch feedback. But unlike listening, touch feedback is generally only available to the person it's touching, so it can be used to create more personal feedback. Traditionally, touch feedback, or haptic feedback, has been very natural.

Morgan feels the keys go down as she presses them on keyboard.

But with touch screens, motion controls and virtual reality, touch needs to be more and more designed explicitly into the system if we're to use it.

<a id="L2-4-quiz-design-challenge-message-alerts"></a>

### Quiz: Design Challenge: Message Alerts

Let's design something for Morgan real quick. Let's tackle the common problem of being alerted when you've received a text message. Here are the constraints on our design for Morgan. It must alert her whether the phone is in her pocket or on the table. It cannot disturb the people around her. [SOUND] And yes, vibrating loudly against the table counts as disturbing the people around her. You're not restricted to just one modality, though, but you are restricted to the sensors that the phone has available.

Here's one possible design. We know that smart phones have cameras and light sensors on them. We can use that to determine where the phone is, and what kind of alert it should trigger. If the sensor detects light, that means the screen is visible, so it might alert her simply by flashing its flashlight or illuminating the screen. If the sensor does not detect light, it would infer that the phone is in her pocket and thus, would vibrate instead. Now, of course, this isn't perfect. It could be in her purse, or she could have put it face down. That's why we iterate on a design like this, to improve it based on the user's experiences.

<a id="L2-4-quiz-memory-perceptual-store"></a>

### Quiz: Memory: Perceptual Store

After the perception portion of this model comes the cognition portion, starting with memory. There are lots of different models of memory out there. For our purposes we're going to talk about three different kinds of memory, the perceptual store or working memory, the short-term memory, and the long term memory. Some scientists argue that there are other types of memory as well, like an intermediate sort of back of the mind memory. But the greatest consensus is around the existence of at least these three kinds.

So let's start with the first, the perceptual store or the working memory. The perceptual store is a very short term memory lasting less than a second. One of the most common models of working memory came from Baddeley and Hitch in 1974. They described it as having three parts. First, there's the visuospatial sketchpad which holds visual information for active manipulation. So for example, picture a pencil. The visuospatial sketchpad is where you're currently seeing that pencil. A second part is the phonological loop. The phonological loop is similar, but for verbal or auditory information. It stores the sounds or speech you've heard recently, such as the sound of me talking to you right now. A third part is the episodic buffer. The episodic buffer takes care of integrating information from the other systems as well as chronological ordering to put things in place. Finally all three of these are coordinated by a central executive.

So let's try an example of this. I'm going to very quickly show you a picture and ask you a question about it. Don't focus on any particular portion of the picture, try to view it as a whole.

What was the score on the scoreboard?

As you can now see, the score was 0 to 0. Now, as you tried to reason over that, what you probably did was picture the image in your mind. That was trying to reason over what was stored in the perceptual buffer, and it decayed very quickly. However, if you're a fan of baseball, you probably had a better chance of getting that right. That's because you have some domain expertise. You're better able to process images about that domain more quickly. You might, for example, have recognized that most of the innings weren't marked. So that increases the odds that the score of the game was pretty low. This idea is actually the foundation of a fascinating study about chess experts versus novices and recognizing the configuration of chess boards. The study found that experts were far better than novices at remembering realistic chess boards that were only flashed for a short period of time, like the one on the left. But experts were no better than novices at remembering random chessboards. So expertise, or rehearsal, delays the decay of the perceptual buffer.

<a id="L2-4-quiz-memory-short-term-and-chunking"></a>

### Quiz: Memory: Short Term and Chunking

When we're designing interfaces, short-term memory is one of our biggest concerns. It's important we avoid requiring the user to keep too much stored in short-term memory at a time. Current research shows that users can really only store four to five chunks of information at a time. For a long time, there was a popular idea that people could store seven, plus or minus two, items in memory at a time. But more recent research suggests that the number is really four to five chunks. There are two principals we need to keep in mind here though. The first, is the idea of chunking. Chunking is grouping together several bits of information into one chunk to remember.

So to illustrate this, let's try it out. I'm about to show you six combinations of letters. Try to memorize them and then enter them into the exercise that pops up. Are you ready? Now to keep you from just rehearsing it in your perceptual store until you can reenter it, I'm going to stall and show you some pictures of my cats.

There's one. There's both of them, and here's my daughter.

Okay, now fill in the words.

So what happened? Well, what likely happened is that you maybe had only a little bit of trouble remembering the two real words that were listed on the right. You might have had some more trouble remembering the two words that were listed in the middle that were fake words, but did nonetheless look like real words. And you probably had a lot of trouble remembering the two series of letters over on the left. Why is all of that? Well, when it came to memorizing these two words, you were just calling up a chunk that you've already had. You didn't see these as arbitrary collections of letters, you just saw them as words. For the ones in the middle, you've never seen those combinations of letters before, but you could pronounce them as if they were words. So you likely saw them as fake words rather than just random collection of letters. For these over the left though, you had to memorize five individual characters. So that's means that while these four were able to jump in the words or pseudo words. These likely had to be remembered as five chunks each. That's makes this much more difficult to remember than these.

<a id="L2-4-quiz-memory-short-term-and-recognition"></a>

### Quiz: Memory: Short Term and Recognition

However, there is a way we can make this easier. So let's ask a different question. Which of these six words did you see in the exercise previously?

Even if you had trouble just naming these series of letters in the exercise previously. You probably were much more successful at this exercise. Why is that? That's because it's far easier to recognize something you know than to recall it independently. And that's a useful take away for us as we design interfaces. We can minimize the memory load on the user by relying more on their ability to recognize things than to recall them.

<a id="L2-4-memory-short-term-takeaways"></a>

### Memory: Short Term Takeaways

So what are the implications of short term memory for HCI? We don't want to ask the user to hold too much in memory at a time, four to five chunks is all. Asking the user to hold ten numbers in short term memory, for example, would probably be too much. But we can increase the user's effective short term memory capacity by helping them chunk things.

For example, this is probably by far easier to remember, even though it's the same content. We've shrunk ten items into three. And we've used a format for phone numbers with which you're probably familiar if you're in the United States. If you're from outside the U.S., you might be familiar with a different grouping. But the same principle applies. And finally, when possible, we should leverage recognition over recall. For example, if I ask you to recite the number, maybe you could. In fact, go ahead. Try it.

Whether or not you could do that, you almost certainly, though, can pick it from this list. This is one of the reasons why menu bars and tool strips are so ubiquitous in software design. The user doesn't have to remember the icon for a command or the name of an option. They just have to recognize it when they see it.

<a id="L2-4-memory-long-term-memory"></a>

### Memory: Long Term Memory

Finally, we have long-term memory. Long-term memory is a seemingly unlimited store of memories, but it's harder to put something into long-term memory, than to put it into short-term memory. In fact, to load something into long-term memory, you generally need to put it into short-term memory several times.

To demonstrate this, I'm going to describe something called lightner system. The lightner system is a way of memorizing key value pairs, or in other words memorizing flashcards. Those can be words and their definitions, countries and their capitals, laws and their formulas, anything where you're given a key and asked to return a value. So I have some flashcards here that have the capitals of the world. What I do is go through each one, read the country, check to see if I remember the capital. And if I do, I'll put it in the pile on the right. I read the country and don't know the capital, I'll put it in the pile on the left. So let me do that real quick. [MUSIC] Now tomorrow, I will just go through the pile on the left. Any that I remember from the pile on the left tomorrow, I'll move to the pile on the right. Any that I still don't remember, will stay in the pile on the left. So I'm focusing my attention on those that I don't yet know. In four days, I'll go through the pile on the right. And any that I don't remember then, I'll move back to my pile on the left, to remind me to go through them each day. So the things that I remember least, are most often loaded in the short-term memory, solidifying them in my long-term memory. Now in practice, you wouldn't just do this with two piles, you'd do a three, or four, or five. And the long restoration pile you'd might only go through yearly, just to see if it's decayed yet.

<a id="L2-4-cognition-learning"></a>

### Cognition: Learning

Now let's talk a little bit about cognition. One of the most important cognitive processes to consider is learning. When we design interfaces, we are in some ways we are hoping the user has to learn as little as possible to find the interface useful. However, our interfaces should also teach the user over time how to use them most efficiently. We can take PowerPoint as an example of this. Let's pretend this is the first time I've ever used PowerPoint and I want to copy something. This application doesn't assume I know anything yet. If I poke around, I'll find the Copy button under the Edit menu, which is off-screen above the slide.

When I bring up that menu, it also shows the hot key that will allow me to actually copy something. That's helping me to learn to interact with the application more efficiently through hot keys instead of through menus. But yet, it's also not assuming that I already knew that, because I was still able to find this under that menu.

There are two kinds of learning we're most interested in, procedural and declarative. Procedural is how to do something. That can be doing work on a computer, playing sports, playing musical instrument. It's a task in which you're engaged or an activity you are performing, it's something that you do. Declarative learning is knowledge about something. It's what you know in your head. It's what you can answer when asked. So if I asked you, what's the hotkey for paste? I'm asking for a declarative knowledge. If I asked you, paste your clipboard here, I'm asking for procedural knowledge. If you're an expert computer user, you'd probably find it easier to just actually paste your clipboard than to answer me when I say, what's the hotkey for paste? And in all likelihood, when I ask you, what's the hotkey for paste, the way you remember it is you mentally simulate doing it, and then you look at what you simulated yourself doing. What's interesting is that while declarative knowledge is how we generally communicate with one another, procedural knowledge is generally what we do in HCI. When you have strong procedural knowledge, you may forget how you're doing what you're doing, because it's so second nature.

You're unconsciously competent with what you're doing. When you're in that state, it can be difficult to explain to someone who lacks that competence, because you aren't sure what makes you so good at it.

It's difficult to translate your subconscious procedure analogy into explicit declarative knowledge. A declarative knowledge is how we communicate, that's how we communicate with novice users.

This is important, because as the designers of interfaces, we're the experts in our domains. That means we're prone to design things that are easy for us to use but hard for anyone else.

<a id="L2-4-cognition-cognitive-load"></a>

### Cognition: Cognitive Load

To talk about cognitive load, let's think for a moment of the brain like it's a computer. The community is actually divided on whether or not the brain actually operates this way, but for the purposes of this explanation, it's a useful metaphor. So your brain has a certain number of resources available to it, the same way your computer has a certain number of processor resources available to it. Each thing that the brain is working on takes up some of those resources.

Let's say you're at home in a quiet area, working on a calculus problem that requires 60% of your cognitive resources. In that setting, you have plenty of resources to solve that problem.

However, then you go to take a calculus test. Now you have some stress in there. Now you're stressing about the impact this test is going to have on your grade. You're stressing about how well other people seem to think they are doing on it. Whether or not other people seem to be struggling while you struggle. This is taking up a lot of your cognitive resources. Here we see the stress taking up 50% of the cognitive resources you have. Now you don't have sufficient resources to complete the problem successfully. I hypothesize that's why test taking anxiety can have such a negative effect. It takes resources away from actually working on the test. You can apply these same principles to the presence of distractions, anxiety disorders and more. Cognitive load has two major applications to our working design interfaces.

One, we want to reduce the cognitive load posed by the interface, so that the user can focus on the task.

Second, we want to understand the context of what else is going on while users are using our interface. We need to understand what else is competing for the cognitive resources users need to use our interface. If we're designing a GPS or navigation system for example, we want to be aware that the user will have relatively few cognitive resources because they're focusing on so many things at once.

<a id="L2-4-quiz-reflections-cognitive-load"></a>

### Quiz: Reflections: Cognitive Load

Let's take a second and reflect on cognitive load. Try to think of a task where you've encountered a high cognitive load. What different things did you have to keep in mind at the same time? And how could an interface have actually helped you with this problem?

Computer programming is one task with an incredibly high cognitive load. At any given time, you're likely holding in working memory your goals for this line of code, your goals for this function, your goals for this portion of the program as a whole, the variables you've created and a lot more. That's why there's so many jokes about how bad it is to interrupt a programmer, because they have so much in working memory that they lose when they transition to another task. But there are ways good IDEs can help mitigate those issues. For example, inline automated error checking is one way to reduce the cognitive load on programmers, because it lets them focus more on what they're trying to accomplish rather than the low level syntax mistakes. In that way, the IDE offloads some of the responsibility from the user to the interface. Now we could phrase that a little bit differently too. We could describe this as distributing the cognitive load more evenly between the different components of the system, myself and the computer. That's a perspective we discuss when we talk about distributed cognition.

<a id="L2-4-5-tips-reducing-cognitive-load"></a>

### 5 Tips: Reducing Cognitive Load

Here are five quick tips for reducing cognitive load in your interfaces. Number 1, use multiple modalities. Most often, that's going to be both visual and verbal. But when only one system is engaged, it's natural for it to become overloaded while the other one becomes bored. So describe things verbally and also present them visually. Number 2, let the modalities complement each other.

Some people will take that first tip and use it as justification to present different content of the two modalities. That actually increases cognitive load because the user has to try to process two things at once, as you just noticed when Amanda put something irrelevant up while I said that.

Instead, focus on letting each modality support, illustrate or explain the other, instead of competing with the other.

Number 3, give the user control of the pace. That's more pertinent in educational applications of cognitive load, but oftentimes interfaces have built-in timers on things like menus disappearing or selections needing to be made. That dictates the pace, induces stress, and it raises cognitive load. Instead, let the user control the pace. Number 4, emphasize essential content and minimize clutter. The principal of discoverability says we want the user to be able to find the functions available to them, but that could also raise cognitive load if we just give users a list of 500 different options. To alleviate that, we can design our interfaces in a way that emphasizes the most common actions, while still giving access to the full range of possible options. Number 5, offload tasks. Look closely at what the user has to do or remember at every stage of the interface's operation. And ask if you can offload part of that task on to the interface. For example, if a user needs to remember something that they entered on a previous screen, show them what they entered. If there's a task they need to do manually, see if you can trigger it automatically.

<a id="L2-4-motor-system"></a>

### Motor System

So our user has received some input. It's entered her memory, she cognitively processed it. Now it's time to act in the world in response. In designing interfaces, we're also interested in what is physically possible for users to do. This includes things like, how fast they can move, or how precisely they can click or tap on something.

For example, here are two versions of the Spotify control widget that appears on Android phones. On the left is the version that's available in the tray of the phone that you can access at any given time by swiping down on the phone screen. And on the right is the version that appears on the lock screen when you turn on a locked phone while it's playing music. In each case, the X closes the app, which is consistent with a lot of other applications. The forward, back and pause buttons are similarly consistent with their usual meanings. I don't actually know what the plus sign here does. It's doesn't have a clear mapping to some underlying function. Now note on the left, we have the close button, in the top right corner. It's far away from anything else in the widget. On the right, the close button is right beside the skip button. I can speak from considerable personal experience, and say that the level of specificity or the level of precision required to tap that X, instead of tapping the skip button, is pretty significant. Especially if you're using this while running or driving, or anything besides just sitting there, interacting directly with your phone. The precision of the user's ability to tap on a button is significantly reduced in those situations. And in this case, that can lead to the quick error of closing the application when all you're trying to do is skip forward to the next song. This isn't an error in the perception of the screen. It's not an error in their memory of the controls. They're not thinking that the X button actually is the skip button. This is just an error in what they're physically able to perform at a given time. The interface relies on more precision than they would have in many circumstances. So this design doesn't take into consideration the motor system of the user or the full context surrounding usage of this application. This isn't as significant in the design on the left, because there's more room around that close button. If I aim for the forward button and miss, the worst that's going to happen is I might pause it. I'm not going to close it by accident. This is one example of how we need to be aware of the constraints on the user's motor system. What they can physically do, how precise or accurate they can be, and so on. And we have to be aware of that in the context where the application is going to be used as well. These buttons are no smaller than the keys on a smart phone keyboard but we expect more specificity when they're sitting there typing with their thumbs, as opposed to reaching over and interacting real quick on something on the lock screen. Now of course, there might be other constraints around this. There might be a reason why this button's placed there. There might be some constraint in the Android system that doesn't let them use more than one row of the lock screen. In that case, we would need to make our interface more tolerant of errors. Maybe require a double tap to close the app, or maybe we mute it when it's pressed and then gives the user five seconds to confirm that that's actually what they want to do. Those are ways of reducing the penalty for errors.

<a id="L2-4-exploring-hci-human-abilities"></a>

### Exploring HCI: Human Abilities

We've talked a lot about different human abilities in this lesson. Depending on the demand you chose, the human abilities in which you're interested, may vary dramatically. If you looking at gestural interfaces or wearable devices than the limitations of the human motor system might be very important. On the other hand, if you're interested in educational technology, you're likely more interested in some of the cognitive issues surrounding designing technology. For virtual reality, you're main concern will likely be perception. Although, there are interesting open questions about how we physically interact with virtual reality as well. So take a few moments and reflect on what the limitations of human ability are in the domain of HCI that you chose to explore.

<a id="L2-4-conclusion-to-human-abilities"></a>

### Conclusion to Human Abilities

Today, we've gone through a crash course on human abilities and perception. We started off by talking about the main ways people perceive the world around them through sight, sound and touch.

Then we discussed some of the components of cognition, especially memory and learning.

Then we discussed the motor system, how the person then interacts with the world around them. In this single lesson, we've only scratched the surface of human perception. There are entire courses, even entire degree programs, that focus on these principles. We'll give you some suggestions on some of the notes. So don't think we've given you a full view of the field. Instead, we hope we've given you just enough to start to keep human abilities in mind, and enough to know what to research as you start to learn to design interfaces.

— End of Lesson 2.4 — [Back to summary](#A-L2-4) · [Contents](#toc)

---

<a id="L2-5"></a>

## 2.5 Design Principles and Heuristics

**CS6750 · Human–Computer Interaction** — Lecture notes (David Joyner, Summer 2017 lecture book, pp. 187–236)

*Full lecture content, restructured for revision. `»` marks a speaker change in video-transcript dialogue.*

[Back to summary of this lesson](#A-L2-5) · [Table of contents](#toc) · [Keyword index](#partC)

**Sections in this lesson:**

- [Introduction to Design Principles](#L2-5-introduction-to-design-principles)
- [The Sets](#L2-5-the-sets)
- [Discoverability](#L2-5-discoverability)
- [Quiz: Design Challenge: Discovering Gestures](#L2-5-quiz-design-challenge-discovering-gestures)
- [Simplicity](#L2-5-simplicity)
- [Affordances](#L2-5-affordances)
- [Mapping](#L2-5-mapping)
- [Quiz: Design Challenge: Mapping and Switches](#L2-5-quiz-design-challenge-mapping-and-switches)
- [Perceptability](#L2-5-perceptability)
- [Consistency](#L2-5-consistency)
- [Consistency: The Curious Case of Ctrl+Y](#L2-5-consistency-the-curious-case-of-ctrl-y)
- [Flexibility](#L2-5-flexibility)
- [Equity](#L2-5-equity)
- [Ease and Comfort](#L2-5-ease-and-comfort)
- [Structure](#L2-5-structure)
- [Constraints](#L2-5-constraints)
- [Norman's Four Types of Constraints](#L2-5-norman-s-four-types-of-constraints)
- [Quiz: Reflections: Constraints](#L2-5-quiz-reflections-constraints)
- [Tolerance](#L2-5-tolerance)
- [Feedback](#L2-5-feedback)
- [Documentation](#L2-5-documentation)
- [Exploring HCI: Design Principles and Heuristics](#L2-5-exploring-hci-design-principles-and-heuristics)
- [Other Sets of Principles](#L2-5-other-sets-of-principles)
- [Conclusion to Design Princip](#L2-5-conclusion-to-design-princip)

<a id="L2-5-introduction-to-design-principles"></a>

### Introduction to Design Principles

[MUSIC] Over the many years of HCI development, experts have come up with a wide variety of principles and heuristics for designing good interfaces. None of these are hard and fast rules like the law of gravity or something. But they're useful guidelines to keep in mind when designing our interfaces. Likely, the most popular and influential of these is Don Norman's six principles of design.

Larry Constantine and Lucy Lockwood have a similar set of principles of user interface design, with some overlaps but also some distinctions.

Jacob Nielsen has a set of Ten Heuristics for user interface design that can be used for both design and evaluation.

And while those are all interested in general usability, there also exists a set of seven principles called Principles of Universal Design. These are similarly concerned with usability, but more specifically for the greatest number of people. Putting these four sets together, we'll talk about 15 unique principles for interaction design.

<a id="L2-5-the-sets"></a>

### The Sets

In this lesson we're going to talk about four sets of design principles. These aren't the only four sets, but they're the ones that I see referenced most often, and we'll talk about what some of the others might be at the end of the lesson. In this book, The Design of Everyday Things, Don Norman outlined his famous six design principles. This is probably the most famous set of design principles out there. The more recent versions of the book actually have a seventh principle. But that seventh principle is actually one of our entire lessons.

Jakob Nielsen outlines ten design heuristics in his book, Usability Inspection Methods. Many of Norman's principles are similar to Nielsen's but there's some unique ones, as well. What's interesting, is Norman and Nielsen went into business together and formed the Nielsen Norman Group, which is for user experience training, consulting, and HCI research.

In their book Software for Use, Larry Constantine and Lucy Lockwood outline an additional six principles. Again, many of them overlap with these two, but some of them are unique.

Finally, Ronald Mace of North Carolina State University proposed Seven Principles of Universal Design. The Center for Excellence in Universal Design, whose mobile site is presented here, has continued research in this area. These are a little bit different than the heuristics and principles presented in the other three. While these three are most concerned with usability in general, universal design is specifically concerned with designing interfaces and devices that can be used be everyone regardless of age, disability, and so on. To make this lesson a little easier to follow, I've tried to merge these four sets of principles into one larger set capturing the overlap between many of them.

In this lesson, we'll go through these 15 principles. These principles are intended to distill out some of the overlap between those different sets.

This table shows those 15 principles, my names for each of them, and which sets they come from. Note that my 15 principals are just an abstraction or summary of these sets of principles. And you should make sure to understand the sets themselves as well. There are some subtle differences between the principles I've grouped together from different sets. And we'll talk about those as we go forward. And again, note that these aren't the only four sets of design principals out there. At the end of the lesson, we'll chat about a few more. And we'll also mention when others apply within this lesson as well.

<a id="L2-5-discoverability"></a>

### Discoverability

Our first principle is discoverability.

Don Norman describes it by asking, is it possible to even figure out what actions are possible and where and how to perform them? Nielsen has a similar principle. He advises us to minimize the user's memory load by making objects, actions, and options visible. Instructions for use of the system should be visible or easily retrievable whenever appropriate. In other words, when the user doesn't know what to do, they should be able to easily figure out what to do. Constantine and Lockwood have a similar principle called the visibility principle. The design should make all needed options and materials for a given task visible without distracting the user with extraneous or redundant information. The idea behind all three of these principles is that relevant function should be made visible, so the user can discover them as opposed to having to read about them in some documentation or learn them through some tutorial.

Let's take an example of this real quick. Here in PowerPoint, there are a number of different menus available at the top, as well as some toolbars. The effect here is that I can browse the different functions available to me. I can discover what's there. For Nielsen, this means that I don't have to remember all of these. I just have to recognize them when I see them in the tool bars. For example, I don't have to remember Arrange as some keyboard I have to type in manually to bring up some ideas about how I might arrange things. All I have to do is recognize Arrange as the right button when I see it. Now while this might be true at the application level, it's not often true at the operating system level, because the operating system doesn't command so much screen real estate all the time and probably for good reason. So for example, on a Mac, I can use Command Shift 4 to take a screen shot only of a certain area of my screen. However, the only way I know of to find that is to Google it or read it in a manual. It isn't discoverable or visible on it's own. And you might never even realize it's possible. So the principle of discoverability advocates that functions be visible to the user, so that they can discover them, rather then relying on them learning them elsewhere. I actually use a PC more than a Mac. And whenever I come back to my Mac after not using it for awhile, I have to Google that again. I know it's possible, but I never remember the command that actually makes it happen.

Constantine and Lockwood's principle of visibility would add on to this that we shouldn't get too crazy. We want to make functions discoverable, but that doesn't mean just throwing everything on the screen. We want to walk a line between discoverability, and simplicity

<a id="L2-5-quiz-design-challenge-discovering-gestures"></a>

### Quiz: Design Challenge: Discovering Gestures

Discoverability is one of the challenges for designing gesture-based interfaces. To understand this, let's watch Morgan do some ordinary actions with her phone.

[MUSIC] [SOUND] [MUSIC] We just saw Morgan do four things with the phone. Reject a call, take a screenshot, take a selfie, and make a phone call. For each of those, this phone actually has a corresponding gesture that would have made it easier. She could have just turned the phone over to reject the call or said, shoot, to take the selfie. The problem is that these are not discoverable. Having a menu of voice commands kind of defeats the purpose of saving screen real estate and simplicity through gestures and voice commands. So, brainstorm a bit. How would you make these gesture commands more discoverable?

There's a lot of ways we might do this, from giving her a tutorial in advance, to giving her some tutoring in context. For example, we might use the title bar of the phone to just briefly flash a message letting the user know when something they've done could have been triggered by a gesture or a voice command. That way, we're delivering instruction in the context of the activity. We could also give a log of those so that they can check back at their convenience and see the tasks they could have performed in other ways.

<a id="L2-5-simplicity"></a>

### Simplicity

There often exists a tension between discoverability and simplicity. On the one hand, discoverability means you need to be able to find things. But how can you find them if they're not accessible or visible? That's how you get interfaces like this with way too many things visible. And ironically as a result, it actually becomes harder to find what you're looking for because there's so many different things you have to look at.

This is where the principle of simplicity comes in. Simplicity is part of three of our sets of principles, Nielsen's, Constantine and Lockwood's, and the universal design principles.

Nielsen writes specifically about dialogues. He says that the dialogues should not contain information which is irrelevant or rarely needed. Every extra unit of information competes with the relevant units of information, and diminishes their relative visibility, which we see with all those toolbars Constantine and Lockwood establishes as their simplicity principle. They say the design should make simple common tasks easy. Communicating clearly and simply in the user's own language and providing good shortcuts. Universal design is concerned with simplicity as well. Their principle of simple and intuitive use advocates the use of design easy to understand regardless of the user's experience, knowledge, language skills, or current concentration level. And in this principle you can see universal design's special concern with appealing to users of a variety of different levels of expertise, ages, disabilities, and so on.

Now in some ways, these principles are about designing interfaces but they cover other elements as well. One example of this is the infamous blue screen of death from the Windows operating systems. On the left we have the blue screen of death as it appeared in older versions of Windows. And on the right we have how it appears now on Windows 10. There are a lot of changes here. The blue is softer and more appealing. The description of the error is in plain language. But the same information is still provided, it's just de-emphasized. This is a nice application of Nielsen's heuristic. The user should only be given as much information as they need. Here, the information that most users would need, which is just that a problem occurred and here's how close I am to recovering from it, are presented more prominently than the detailed information that might only be useful to an expert.

Another interesting application of simplicity in action came when New York tried to create simpler signs to represent its allowed parking schedule.

Navigating the sign on the left is pretty much impossible. But it's pretty easy to interpret the one on the right. The universal design principle of simplicity is particularly interested in whether or not people of different experiences, levels of knowledge, or languages can figure out what to do. Navigating this sign requires a lot of cognitive attention and some language skills. Whereas I would hypothesize that even someone who struggles with English might be able to make sense oft the sign on the right. These two signs communicate the same information, but while the one on the left requires a lot of cognitive load and language skills, the one on the right can probably be understood with little effort and little experience.

<a id="L2-5-affordances"></a>

### Affordances

One way to keep design both simple and usable is to design interfaces that by their very design tell you how to use them. Don Norman describes these as affordances. The design of a thing affords or hints at the way it's supposed to be used. This is also similar to the familiarity principle from Dicks, et al. This is extremely common in the physical world because the physical design of objects is connected to the physical function that they serve. Buttons are meant to be pressed. Handles are meant to be pulled. Knobs are meant to be turned. You can simply look at it and understand how you're supposed to use it.

Our next principle is the principle of affordances.

Norman writes that an affordance is the relationship between the properties of an object and the capabilities of the agent that determine just how the object could possibly be used. In other words, an object with an affordance basically tells the user, by its very design, how it's meant to be used. I use a door handle as the icon for this because a door handle is a great example of an affordance. You can look at it and understand that you're probably supposed to pull it down or push it up. The very design of it tells you how you're supposed to use it. Norman goes on to say, the presence of an affordance is jointly determined by the qualities of the object and the abilities of the agent that is interacting. In other words, an affordance for one person isn't an affordance for everyone. If you didn't grow up around door handles than maybe that door handle doesn't have an affordance for you the way it would for someone who grew up around that. Our affordances are defined by who the user is.

The challenge is that in the virtual computer world, there's no such inherent connection between the physical design and the function of an interface, the way you might often find in the real world. For example, when I mouse over a button in my interface, the style that appears around it makes it look like it's elevated. Makes it look like it's popping out of the interface. That affords the action of then pushing it down, and I know that I need to click it to push it down.

When I click it, it depresses, it gets darker, it looks like it's sunk into the interface. So here we've manually created an affordance that would exist in the real world. The design of this button hints at how it's supposed to be used. It hints at the fact that it's supposed to be pressed. So we have to create that naturalness manually. We can do that in a number of different ways. We could, for example, visualize the space of options.

Here this color picture does a good job of this. The horizontal line effectively shows us the list of options available to us. The placement of the dial suggests where we are now. And there's this kind of implicit notion that I could drag this dial around to change my color. We can also leverage **metaphors** or analogies to physical devices. You can imagine that if this content was presented like a book, I might scroll through it by flicking to the side, as if it's a page. You may have seen interfaces that work exactly like that. Theres no computational reason why that should mean go to the next page or that should mean go back a page. Except that it makes sense in the context of the physical interface it's meant to mimic. We swipe in a book so let's swipe in a book-like interface.

Of course, there are also actions in the virtual world that have no real world analogy like pulling up a menu on a mobile site. In that case we might use signifiers. **Signifiers** are a principle in Norman's more recent editions. Signifiers are in context instructions like arrows to indicate which way to swipe for a particular action. Or in this case a button labelled Menu to indicate how to pull up a menu. In this way we can kind of create our own affordances by creating an intuitive mapping between controls and their effects in the world, being consistent with what others have done in the past.

<a id="L2-5-mapping"></a>

### Mapping

Norman and Nielsen both talk about the need for a mapping between interfaces and their effects in the world.

Norman notes that mapping is actually a technical term coming from mathematics that means a relationship between the elements of two sets of things. In this case, our two sets are the interface and the world. For example, these book icons might help you map these quotes to the books from which they were taken. Nielsen describes mapping by saying the system should speak the users' language, with words, phrases, and concepts that are familiar to the user, rather than system-oriented terms. Follow real-world conventions, making information appear in a natural and logical order. A great example of this, is the fact that we call cut, copy, and paste, cut, copy and paste. Surely there could have been more technical terms like duplicate instead of copy. But using cut, copy, and paste forms a natural mapping between our own vocabulary and what happens in the system. Note that these two principles are subtly different, but they're actually strongly related. Nielsen's heuristic describes the general goal, while Norman's principle describes one way to achieve it. Strong mappings help make information appear in natural and logical order.

A great example of this is setting the arrangement of different monitors. This actually comes from my display in my home office. This visualization creates a very natural mapping between the way the system treats the monitors, and they way they're actually laid out in the world. If there's a mismatch, or if something doesn't make sense, I can easily look at this and map it with the arrangement of the monitors in front of me and figure out what's going on. This could instead be shown as just a list of pixel locations. And that would still present all the exact same information, but in a way that isn't as easily mapped out to the real world. Now, mappings and affordances are similar principles, but they have a clear and important difference.

We can see that difference in our color meter again. Affordances were about creating interfaces where their designs suggested how they're supposed to be used. The placement of this notch along this horizontal bar, kind of affords the idea that it could be dragged around. The horizontal bar visualizes the space which makes it seem like we could move that notch around to set our color. However, that design on its own wouldn't necessarily create a good mapping. Imagine, if instead of the bar fading from white to black, it was just white the entire way. It would still be very obvious how you're supposed to use it. But it wouldn't be obvious what the effect of using it would actually be. It's the present of that fade from white to black that makes it easier to see what will happen if I actually drag that around. I can imagine it's going to make the colors fade from white to black. That creates the mapping to the effect of dragging it around on that meter. So mapping refers to creating interfaces where the design makes it clear what the effect will be when using them, not just creating interfaces where it's clear how you're supposed to use them. With this color meter, the arrangement of the controls makes clear what to do and the visualization underneath, makes it clear what will happen when I do it.

<a id="L2-5-quiz-design-challenge-mapping-and-switches"></a>

### Quiz: Design Challenge: Mapping and Switches

A good example of the difference between affordances and mappings is a light switch. A light switch very clearly affords how you're supposed to use it. You're supposed to flip it. But these switches have no mapping to what will happen when I switch them. I can look at it and clearly see what I'm supposed to do. But I can't tell what the effect is going to be in the real world.

Contrast with the dials on my stove. There are four dials and each is augmented with this little icon that tells you which burner is controlled by that dial. So there's a mapping between the controls and the effects. So how would you redesign these light switches to create not only affordances but also mappings. If relevant, this one turns on the breakfast room light, this one turns on the counter light and this one turns on the kitchen light.

There are a few things we could do actually. Maybe we could put a small letter next to each light switch that indicates which light in the room that switch controls. K for kitchen, C for counter top, B for breakfast room. Maybe we actually put icons that demonstrates which kind of light is controlled by each switch. So the counter top lights are kind of sconce lights, so maybe we put an icon that looks like the counter top lights. But likely the easiest thing is actually the way the system really was designed. I just didn't notice it until I started writing this video. The lights from left to right in the room are actually controlled by the light switches from left to right on the wall. This switch controls the light over there. This switch controls the light right here. And this switch controls the light back there. That actually forms a pretty intuitive mapping.

<a id="L2-5-perceptability"></a>

### Perceptability

Our next principle is perceptibility. Perceptibility refers to the user's ability to perceive the state of the system.

Nielsen states that the system should always keep users informed about what is going on, through appropriate feedback within reasonable time. That allows the user to perceive what's going on inside the system. Universal design notes that the design should communicate necessary information effectively to the user, regardless of ambient conditions or the user's sensory abilities. In other words, everyone using the interface should be able to perceive the current state. Note that this is also similar to Norman's notion of feedback. He writes that feedback must be immediate, must be informative, and that poor feedback can be worse than no feedback at all. But feedback is so ubiquitous, so general, that really, feedback could be applied to any principle we talk about in this entire lesson. So instead we're going to reserve this more narrow definition for when we talk about errors. And our lesson on feedback cycles covers the idea of feedback more generally. Things like light switches and oven dials, actually do this very nicely. I can look at a light switch and determine whether the system it controls is on or off, based on whether the switch is up or down. Same with the oven dial. I can immediately see where the dial is set. But there's a common household control, that flagrantly violates this principle of perceptibility.

Here's our ceiling fan, you might have one just like it. It has two chains. One controls the light, one controls the fan speed. But both only when the switch on the wall is on. Now first, the mapping here is awful. There's no indication which control is which. But worse, the fan chain, which is this one, doesn't give any indication of which setting the fan is on currently. I don't honestly even know how many settings it has. [SOUND] I don't know if pulling it makes it go up and then down, up and then off, down and then off. Whenever I use it, I just pull it, wait ten seconds and see if I like the speed, and then pull it again. And this is all only if the wall switch is on. Now, of course people have resolved this with dials or other controls, and yet these dang chains still seem to be the most common approach despite this challenge of perceptibility.

<a id="L2-5-consistency"></a>

### Consistency

Consistency is a principle from Norman, Nielsen, and Constantine and Lockwood. It refers to using controls, using visualizations, using layouts, using anything we use in our interface design consistently, across both the interfaces that we design and what we design more broadly as a community.

Norman writes that consistency in design is virtuous. It's a powerful word, there. It means that lessons learned with one system transfer readily to others. If a new way of doing things is only slightly better than the old, it's better to be consistent. Of course there will be times when new ways of doing things will be significantly better then the old. That is how we actually make progress, that is how we advance. If we are only making tiny little iterative improvements, it might be better to stick to the old way of doing things, because users are used to it. They are able to do it more efficiently. Nielsen writes that users should not have to wonder whether different words, situations, or actions mean the same thing. Follow platform conventions. In other words, be consistent with what other people have done on the same platform, in the same domain, and so on. Constantine and Lockwood describe consistency as reuse. They say the design should reuse internal and external components and behaviors, maintaining consistency with purpose rather than merely arbitrary consistency, thus reducing the need for users to rethink and remember. That means that we don't have to be consistent with things that don't really impact what the user knows to do. The color of the window, for example, isn't going to change whether the user understands what the word copy means in the context of an interface. But changing the word copy to duplicate might force users to actually rethink and remember what that term means. In some cases, that might be a good thing. If duplicate actually does something slightly different than copy, then changing that would force our users to understand that they're doing something different. But if we're doing the same thing, it's important to maintain consistency, so the user doesn't have to think as much and can focus on the task at hand, instead of on our interface. The general idea across all of these is we should be consistent both within and across interfaces to minimize the amount of learning the user needs to do to learn our interface. In this way, we create affordances on our own. Unlike traditional physical affordances, there's no physical reason for the interface to be designed a certain way, but by convention, we create expectations for users and then fulfill those expectations consistently.

One great example of following these conventions are the links we use in text on most websites. For whatever reason, an early convention on the internet was for links to be blue and underlined. Now when we want to indicate to users that some text is clickable, what do we do? Generally, we might make it blue and underline it. Sometimes we change this, as you can see here. Underlining has actually fallen out of fashion in a lot of places and now we just use the distinct text color to indicate a link that can be clicked. On some other sites, the color itself might be different. It might be red against blue text instead of blue against black. But the convention of using a contrasting color to mark links has remained and the most fundamental convention is still blue underlines. Again, there's no physical reason why links need to be blue, or why they even need to be a different text color at all. But that convention helps users understand how to use our interfaces. If you've used the internet before and then visit Wikipedia for the first time, you'll understand that these are links without even thinking about it. Most of the interfaces we design will have a number of functions in common with other interfaces. So by leveraging the way things have been done in the past, we can help users understand our interfaces more quickly.

Other common examples of consistency in interface design would include things like using consistent hot keys for things like copy, paste, and select all. Ordering the menus, file, edit, view, etc. Putting options like save and open under file. We don't even tend to think about these things when we're using an interface until we encounter one that defies our conventions. And yet, someone has to consciously decide to be consistent with established norms. This is an example of design becoming invisible. When people do it right, we don't notice they did it at all. When people put those options in the right places, we don't even think about it. But when people put them in the wrong places, it's pretty jarring and startling.

<a id="L2-5-consistency-the-curious-case-of-ctrl-y"></a>

### Consistency: The Curious Case of Ctrl+Y

One of my favorite examples of how consistency matters comes from Microsoft’s Visual Studio development environment. And to be clear: I adore Visual Studio, so I’m not just piling onto it. As you see here, in most interfaces, Ctrl+Y is the ‘redo’ hotkey. If you hit undo one too many times, you can hit Ctrl+Y to ‘redo’ the last ‘undone’ action.

But in Visual Studio, by default it’s… Shift+Alt+Backspace. What?! And what’s worse than this is Ctrl+Y is the ‘delete line’ function, which is a function I had never even heard of before Visual Studio. So, if you’re pressing Ctrl+Z a bunch of times to maybe rewind the changes you've made lately, and then you press Ctrl+Y out of habit because that's what every other interface uses for redo, the effect is that you delete the current line instead of redoing anything and that actually makes a new change, which means you lose that entire tree of redoable actions. Anything you've undone now can't be recovered. It’s infuriating. And yet, it isn’t without its reasons.The reason: consistency.

Ctrl+Y was the hotkey for delete function in WordStar, one of the very first word processors, before Ctrl+Y was the hotkey for the more general redo function. There wasn't even a redo function back then. I've heard that Y in this context stood for ‘Yank’, but I don't know how true that is. But Ctrl+Y had been used to delete a line for from WordStar all the way through Visual Basic 6, which was the predecessor of Visual Studio. So, in designing Visual Studio, Microsoft had a choice: be consistent with the convention from WordStar and Visual Basic 6, or be consistent with the convention they were using in their other interfaces. They chose to be consistent with the predecessors to Visual Studio, and they’ve stayed consistent with that ever since. So in trying to maintain the consistency principle in one way, they actually violated it in another way. So if you try to leverage the consistency principle you're going to encounter some challenges. There may be multiple conflicting things with which you want to be consistent. There may be questions about whether a certain change is worth the drop in consistency. These are things to test with users, which we’ll talk about in the next unit.

<a id="L2-5-flexibility"></a>

### Flexibility

Depending on your expertise with the computers, there's a strong chance you've found yourself on one side or the other of the following exchange. Imagine one person is watching another person use a computer. The person using the computer repeatedly right-clicks and selects Cut to cut things. And then right-clicks and selects Paste to paste them back again. The person watching insists that they can just use Ctrl+X and Ctrl+V. The person working doesn't understand why the person watching cares. The person watching doesn't understand why the person working won't use the more efficient method. And in reality, they're both right.

This is the principal of flexibility. These two options are available because of the principle of flexibility from both Nielsen's heuristics and the principles of universal design.

Nielsen specifically comments on the use of accelerators, which are hot keys. He says that accelerators may often speed up the interaction for the expert user, such that the system can cater to both inexperienced and experienced users. He advises that we allow users to tailor frequent actions. Universal design says something similar. They noted the design should accommodate a wide range of individual preferences and abilities. Another set of design principles from Dix et al also have a category of principles called flexibility principles, that advocate user customizability in supporting multiple designs for the same task. Here, Nielsen is most interested in catering to both novice and expert users, while the principles of universal design are more interested in accommodating users of various abilities and preferences. But the underlying principle here is the same, flexibility. Wherever possible, we should support the different interactions in which people engage naturally, rather than forcing them into one against their expertise or against their preference.

<a id="L2-5-equity"></a>

### Equity

The principle of flexibility in some ways appears to clash with the principle of equity. But both come from the principles of universal design.

The principle of flexibility said the design should accommodate a wide range of individual preferences and abilities. But the principle of equity says the design is useful and marketable to people with diverse abilities, and it goes on to say we should provide the same means for all users, identical whenever possible and equivalent when not. And we should avoid segregating or stigmatizing any users. Now, in some ways, these systems might compete. This says we should allow every user to use the system the same way, whereas this one says that we should allow different, flexible methods of interacting with the system. In reality, though, these are actually complementary of one another. Equity is largely about helping all users have the same user experience, while flexibility might be a means to achieve that. For example, if we want all our users to enjoy using our interface, keeping things discoverable for novice users and efficient for expert users allows us to accommodate a wide range of individual preferences and abilities. User experience in this instance means treating every user like they're within the target audience and extending the same benefits to all users, including things like privacy and security. We might do that in different ways, but the important note is that the experience is the same across all users. That's what equity is about.

One good example of equity in action are the requirements for password resets. We want to design a system so that both expert and novice users experience the same level of security. Security is part of the user experience. Now, experts, we would assume, understand the value of a complex password. Novices might not. So if we don't have requirements around passwords, novices might not experience the same level of security as experts. So password requirements can be seen as a way of making sure the user experience across novices and experts is the same with regard to security. In the process, we might actually frustrate novice users a little bit. You could actually see this as a violation of the flexibility principle, that we're not flexibly accommodating in the kind of interaction that novices want to have. But the important thing, is we're extending the same security benefits to everyone, and that's equitable treatment. And that's also a good example of how at times, the different design principles will appear to compete, and you have to decide what the best approach is going forward.

<a id="L2-5-ease-and-comfort"></a>

### Ease and Comfort

Ease and comfort are two similar ideas that come from the principles of universal design. And they also relate to equitable treatment, specifically in terms of physical interaction.

The ease principle, which interestingly uses the word comfort, says the design can be used efficiently and comfortably and with a minimum amount of fatigue. The comfort principle notes that appropriate size and space is provided for approach, reach, manipulation and use regardless of the user's body size, posture or mobility. Now, in the past, these principles didn't have an enormous amount of application to HCI. Because we generally assume that the user was sitting at their desk with a keyboard and a monitor. But as more and more interfaces are becoming equipped with computers, we'll find HCI dealing with these issues more and more. For example, the seat control in your car might now actually be run be a computer that remembers your settings and restores them when you get back in the car. That's an instance of HCI trying to improve user ease and comfort in a physical area.

Mobile interfaces are great examples of this as well. When deciding the size of buttons on a mobile interface, we should take into consideration that some users might have tremors that make it more difficult to interact precisely with different buttons. As we get into areas like wearable computing and virtual reality, these issues of ease and comfort are going to become more and more pertinent.

<a id="L2-5-structure"></a>

### Structure

The structure principle is concerned with the overall architecture of a user interface. In many ways, it’s more closely related to the narrower field of user interface design than HCI more generally.

It comes from Constantine and Lockwood and they define it as their structure principle which says that design should organize the user interface purposefully, in meaningful and useful ways based on clear, consistent models that are apparent and recognizable to users, putting related things together and separating unrelated things, differentiating dissimilar things and making similar things resemble one another. That's a long sentence. But what it really says is we should organize our user interfaces in ways that helps the user's mental model match the actual content of the task. What’s interesting to me about the structure principle is that it borrows from a form of UI design that predates computers considerably. We find many of the principles we learned in designing newspapers and textbooks apply nicely to user interfaces as well.

For example, this is the Wall Street journal print edition from several years ago. And here’s the Wall Street Journal web site. Notice many of the structural principles present in the print version are present in the website as well. Now part of that is for brand consistency. But part of it is because the very same ideas we use in developing magazines and newspapers still apply to the development of websites. Lines and spacing set apart different categories of articles. Headlines are still in bold while the article text is smaller. Now there are of course differences because web sites can for example link to articles while physical papers cannot, which is why these are all shorter than the actual paper are. But we see a lot of the same principles at work in the website that were at work in the physical layout. Those are largely parts of structure: organizing things in intuitive ways that groups similar parts, separates dissimilar ones, and helps the user navigate what they’re consuming.

<a id="L2-5-constraints"></a>

### Constraints

In designing user interfaces our goal is typically to make the interface usable. And a big part of usability is accounting for user error.

Many design theorists argue that there's actually no such thing as user error. If the user commits an error it was because the system was not structured in a way to prevent or recover from it. And I happen to agree with that. Now, one way we can avoid error is by preventing the user from performing erroneously in the first place. This is the idea of constraints. Constraining the user to only performing the correct actions in the first place.

On constraints, Norman writes, the constraints are powerful clues, limiting the set of possible actions. The thoughtful use of Constraints in design lets people readily determine the proper course of action, even in a novel situation. And remember, designing so that users are immediately comfortable in novel situations, is one of the goals of good user interface design. Nielsen notes that even better than good error messages is a careful design which prevents a problem from occurring in the first place. Either eliminate error-prone conditions or check for them and present users with a confirmation option before they commit to the action. For example, if our application was prone to users accidentally closing it when they don't mean to, ask them when it's about to close if that is actually what they meant to do. Both of these approaches refer to the need to stop faulty user input before it's even received. This is a principle you might already encounter a lot.

Our password reset screen actually does this pretty well. First, it shows us the constraints under which we're operating right there visibly on the screen so we're not left guessing as to what we're supposed to be doing. Then, as we start to interact, it tells us if we're violating any of those constraints.

So if I were just try to make my password the incredibly common, 1234, it immediately tells me that password isn't long enough and it doesn't represent enough character classes. Now, obviously, it can't prevent me from entering 1234 in the first place, since maybe that's along the way to a longer more valid password. But it's visualizing those constraints so that instead of submitting and getting frustrated when it didn't tell me I was doing it wrong until I'd actually done it, it actually tells me in right in the context of doing it that I'm not on the right track. This is kind of a soft constraint. It doesn't prevent me from doing something but it tells me while I'm doing it that I'm doing it wrong. A harder constraint goes along with that last bullet, can only contain characters printed on the computer's keyboard. Right now, I'm trying to paste in a character that isn't on the computer keyboard and it's just not showing it all together. It's a hard constraint against the inputting characters that aren't allowed. So it's preventing me from putting an invalid input in the first place. So in their simplest form, constraints can be described as preventing the user from putting in input that wasn't going to work anyway.

<a id="L2-5-norman-s-four-types-of-constraints"></a>

### Norman's Four Types of Constraints

Norman takes us a step further though, when he breaks down constraints into four sub-categories. These aren't just about preventing wrong input. They're also about insuring correct input. They're about making sure the user knows what to do next. Physical constraints are those that are literally physically prevent you from performing the wrong action. A three-prong plug, for example, can only physically be inserted in one way, which prevents mistakes. USB sticks can only be physically inserted one way all the way. But the constraint doesn't arise until you've already tried to do it incorrectly. You can look at a wall outlet and understand if you're trying to put it incorrectly. But it's harder to look at a USB and know whether you're trying to insert it the right way. A second kind is a cultural constraint. These are those rules that are generally followed by different societies, like facing forward on escalators, or forming a line while waiting. In designing we might rely on these, but we should be careful of intercultural differences. A third kind of constraint is a semantic constraint. Those are constraints that are inherent to the meaning of a situation. They're similar to affordances in that regard. For example, the purpose of a rear view mirror is to see behind you. So therefore, the mirror must reflect from behind, it's inherent to the idea of a rear view mirror, that it should reflect in a certain way. In the future that meaning might change, autonomous vehicles might not need mirrors for passengers, so the semantic constraints of today, might be gone tomorrow. And finally the fourth kind of constraint is a logical constraint. Logical constraints are things that are self-evident based on a situation, not just based on the design of something like a semantic constraint, but based on the situation at hand. For example, imagine building some furniture. When you reach the end, there's only one hole left, and only one screw. Logically, the one screw left is constrained to go in the one remaining hole. That's a logical constraint.

<a id="L2-5-quiz-reflections-constraints"></a>

### Quiz: Reflections: Constraints

A lot of the principles we talk about are cases where you might never even notice if they've been done well. There are principles of invisible design, where succeeding allows the user to focus on the underlying tasks. But constraints are different. Constraints actively stand in the user's way and that means they've become more visible. That's often a bad thing, but in the case of constraints it serves the greater good. Constraints might prevent users from entering invalid input or force users to adopt certain safeguards. So of all the principles we've discussed, this might be the one you've noticed. So take a second, and think. Can you think of any times you've encountered interfaces that had constraints in them?

I have kind of an interesting example of this. I can't demonstrate it well because the car has to be in motion, but on my Leaf there's an option screen, and it lets you change the time and the date, and some other options on the car. And you can use that option screen until the car starts moving. But at that point, the menu blocks you from using it, saying you can only use it when the car is at rest. That's for safety reasons. They don't want people fiddling with the option screen while driving. What makes it interesting, though, is it's a constraint that isn't in the service of usability, it's in the service of safety. The car is made less usable to make it more safe.

<a id="L2-5-tolerance"></a>

### Tolerance

We can't constrain away all errors all the time though. So there are two principles for how we deal with errors that do occur, feedback and tolerance. Tolerance means that users shouldn't be at risk of causing too much trouble accidentally.

For this, Nielsen writes that users often choose system functions by mistake. And will need a clearly marked emergency exit to leave the unwanted state without having to go through an extended dialogue. Support undo and redo. For Constantine and Lockwood this is the tolerance principle. They write the design should be flexible and tolerant, reducing the cost of mistakes and misuse by allowing undoing and redoing, while also preventing errors wherever possible. It should be becoming clearer, why that control Y issue with Visual Studio, was so significant. Undo and redo are fundamental concepts of tolerance. And that control Y issue, where control Y removes the line in Visual Studio gets in the way of redo allowing us to recover from mistakes. For Dix et al, this is the principle of recoverability. Now, Nielsen's definition is most interested in supporting user experimentation. The system should tolerate users poking around with things. Universal Design simply says, the design minimizes hazards and the adverse consequences of accidental or unintended actions. Dix et al also refers to this as the principle of recoverability. Now Nielsen's definition is most interested in supporting user experimentation. They system should tolerate users poking around with things. That actually enhances the principle of discoverability because if the user feels safe experimenting with things they're more likely to discover what's available to them. The principles from Constantine and Lockwood and the principles of Universal Design are more about recovering from traditional mistakes.

Jef Raskin poses this as a more humorous law of interface design. A computer shall not harm your work or through inactivity, allow your work to come to harm. So we first have to make sure that the system prevents the user from doing too much damage accidentally. Either by constraining them away from making those mistakes, or allowing an easy way to recover after those mistakes have been made.

<a id="L2-5-feedback"></a>

### Feedback

Second, the system should give plenty of feedback so that the user can understand why the error happened and how to avoid it in the future.

Norman writes that feedback must be immediate and it must be informative. Poor feedback can be worse than no feedback at all. Because it's distracting, uninformative, and, in many cases, irritating and anxiety-provoking. If anything has ever described the classic Windows Blue Screen of Death, it's this. It's terrifying. It's bold. It's cryptic. And it scares you more than it informs you. Nielsen writes that error messages should be expressed in plain language (no codes), precisely indicate the problem, and constructively suggest a solution. Note this tight relationship with recoverability. Not only should it be possible to recover from an error, the system should tell you exactly how to recover from an error. That's feedback in response to errors. For Constantine and Lockwood, this is the feedback principle. The design should keep users informed of actions or interpretations, changes of state or condition, and errors or exceptions... through clear, concise, and unambiguous language familiar to users. Again, the old Windows blue screen of death doesn't do this very well. Because the language is not familiar, it's not concise, and it doesn't actually tell you what the state or condition is. The new one does a much better job of this. Notice as well that Norman, Constantine, and Lockwood are interested in feedback more generally, not just in response to errors. That's so fundamental that we have an entire lesson on feedback cycles that really is more emblematic of the overall principle of feedback. Here we're most interested in feedback in response to errors, which is a very important concept on its own.

<a id="L2-5-documentation"></a>

### Documentation

Finally, Nielsen has one last heuristic regarding user error, documentation. I put this last for a reason, one goal of usable design is to avoid the need for documentation altogether. We want users to just interact naturally with our interfaces. In modern design, we probably can't rely on users reading our documentation at all unless they're being required to use our interface altogether.

And Nielsen generally agrees. He writes that even though it's better if the system can be used without documentation, it may be necessary to provide help and documentation. Any such information should be easy to search, focused on user's task, list concrete steps to be carried out, and not be too large. I feel modern design as a whole has made great strides in this direction over the past several years. Nowadays, most often, when you use documentation online or wherever you might find it, it's framed in terms of tasks. You input what you want to do, and it gives you a concrete list of steps to actually carry it out. That's a refreshing change compared to older documentation, which was more dedicated to just listing out everything a given interface could do without any consideration to what you were actually trying to do.

<a id="L2-5-exploring-hci-design-principles-and-heuristics"></a>

### Exploring HCI: Design Principles and Heuristics

We've talked about a bunch of different design principles in this lesson. How these design principles apply to your design tasks will differ significantly based on what area you're working in. In gestural interfaces, for example, constraint present a big challenge because we can't physically constrain our users movement. We have to give them feedback or feedforward in different ways. If we're working in particularly complex domains, we have to think hard about what simplicity means. If the underlying task is complex, how simple can and should the interface actually be? We might find ourselves in domains with enormous concerns regarding universal design. If you create something that a person with a disability can't use, you risk big problems, both ethically and legally. So take a few moments and reflect on how these design principles apply to the area of HCI that you've chose to investigate.

<a id="L2-5-other-sets-of-principles"></a>

### Other Sets of Principles

So I've attempted to distill the 29 combined principles from Norman, from Nielsen, Constantine, Lockwood, and the Institute for Universal Design into just these 15.

Here you can see where each of these principles comes from. I do recommend reading the original four lists to pick up on some of the more subtle differences between these principles that I grouped together, especially perceptibility, tolerance, and feedback. Note also that in more recent editions, Norman has one more principle: conceptual models. That's actually the subject of an entire lesson in this course. These also certainly aren't the only four sets of design principles. There are several more.

For example, Dix, Finlay, Abowd, and Beale propose three categories of principles: Learnability for how easily a user can grasp an interface, Flexibility for how many ways an interface can be used, and Robustness for how well an interface gives feedback and recovers from errors.

We'll talk about their learnability principles when we talk about mental models. Jill Gerhardt-Powels has a list of principles for cognitive engineering and especially at reducing cognitive load. Her list has some particularly useful applications for data processing and visualization. In the Human Interface, Jeff Raskin outlines some additional revolutionary design rules. I wouldn't necessarily advocate following them, but they're interesting to see a very different approach to things. In Computer Graphics Principles and Practice, Jim Foley and others give some principles that apply specifically to 2D and 3D computer graphics. And finally Susan Weinschenk and Dean Barker have a set of guidelines that provide an even more holistic view of interface design, including things like linguistic and cultural sensitivity, tempo and pace, and domain clarity. And even these are only some of the additional lists. There are many more that I encourage you to look into.

<a id="L2-5-conclusion-to-design-princip"></a>

### Conclusion to Design Princip

In this lesson, I’ve tried to take the various different lists of usability guidelines from different sources and distill them down to a list you can work with. We combined the lists from Don Norman, Jakob Nielsen, Larry Constantine, Lucy Lockwood, and the Institute for Universal Design into fifteen principles. Now remember, though, these are just guidelines, principles, and heuristics: none of them are unbreakable rules. You’ll often find yourself wrestling with tensions between multiple principles. There will be something cool you’ll want to implement, but only your most expert users will be able to understand it. Or, there will be some new interaction method that you want to test, but you aren’t sure how to make it visible or learnable to the user. These principles are things you should think about when designing, but they only get you so far. You still need needfinding, prototyping, and evaluation to find what actually works in reality.

— End of Lesson 2.5 — [Back to summary](#A-L2-5) · [Contents](#toc)

---

<a id="L3-1"></a>

## 3.1 Introduction to Methods

**CS6750 · Human–Computer Interaction** — Lecture notes (David Joyner, Summer 2017 lecture book, pp. 393–419)

*Full lecture content, restructured for revision. `»` marks a speaker change in video-transcript dialogue.*

[Back to summary of this lesson](#A-L3-1) · [Table of contents](#toc) · [Keyword index](#partC)

**Sections in this lesson:**

- [Introduction to Research Methods](#L3-1-introduction-to-research-methods)
- [User-Centered Design](#L3-1-user-centered-design)
- [Principles of User-Centered Design](#L3-1-principles-of-user-centered-design)
- [Stakeholders](#L3-1-stakeholders)
- [Quiz: Reflections: HCI Methods](#L3-1-quiz-reflections-hci-methods)
- [The Design Life Cycle](#L3-1-the-design-life-cycle)
- [Methods for the Design Life Cycle](#L3-1-methods-for-the-design-life-cycle)
- [Design Life Cycles meets Feedback Cycles](#L3-1-design-life-cycles-meets-feedback-cycles)
- [Qualitative vs. Quantitative Data](#L3-1-qualitative-vs-quantitative-data)
- [Quiz: Exercise: Quantitative vs Qualitative](#L3-1-quiz-exercise-quantitative-vs-qualitative)
- [Design Challenge: Recording MOOCS](#L3-1-design-challenge-recording-moocs)
- [Exploring HCI: HCI Methods](#L3-1-exploring-hci-hci-methods)
- [Conclusion to Introduction to Methods](#L3-1-conclusion-to-introduction-to-methods)

<a id="L3-1-introduction-to-research-methods"></a>

### Introduction to Research Methods

[MUSIC] When you start a design new interface, your goal is to design a interface that will meet the needs of the users better than the existing design. It's very rare that we design for tasks that users have never even perform before or almost always developing new ways to accomplish old tasks. Facebook, for example, was a new way to socialize and communicate with others, but the fundamental activities of socializing and communicating weren't new. Facebook just met those needs better. Or at least met certain needs better depending on who you ask. In order to design interactions that are better than existing designs, it's important to take into consideration the users' needs at every stage of the design process. That's what this unit of this course will cover.

We don't generally want to build creative novel interfaces just for the sake of creativity or novelty. We want novelty to have a purpose and to achieve that purpose it must be used with a strong understanding of the users task.

So in this unit we'll cover the Design Life Cycle as well as methods for gathering feedback and information from users at every stage of the cycle. However, before we get started on that, we need to set up some basic concepts we used throughout our discussions.

We'll start at discussing User-centered design.

And then we'll introduce the four stages design life cycle. We'll discuss a few general methods for pursuing the design life cycle.

And then, finally, we'll discuss the two kinds of information or data that we gather, Qualitative and Quantitative.

<a id="L3-1-user-centered-design"></a>

### User-Centered Design

User-centered design is design that considers the needs of the user throughout the entire design process. As far as we're concerned, that's pretty much just good design but oftentimes that isn't the way design is done. Design is often done to meet some functional specifications of what the tool must technically be able to accomplish, instead of considering the real needs of the user.

Or sometimes, people will go through an entire design process believing they understand the needs of the user without ever really checking. User-centered design is about prioritizing the user's needs while also recognizing that we don't know the user's needs. So we need to involve them at every stage of the process. Before we start, we need to examine the users needs in depth, both by observing them and by asking direct questions. After we start designing, we need to present our design alternatives and prototypes to the user, to get feedback. And when we near a design that we like, we need to evaluate the quality of the design with real users. Having a good working knowledge of HCI principles helps us go through this more quickly.

But we can't design great interfaces just by applying guidelines and heuristics alone. We have to interact with our users, understand their needs and involve them in the evaluation.

<a id="L3-1-principles-of-user-centered-design"></a>

### Principles of User-Centered Design

The International Standards Organization, has outlined six principles to follow when pursuing user- centered design. Number one, the design is based upon an explicit understanding of users, tasks and environments. That means that we must gather information about the users, the tasks they perform, and where they perform those tasks, and we need to leverage that knowledge throughout the design process.

Number two, users are involved throughout design and development. Involvement can take on many forms, from regularly participating with interviews and surveys about designs and prototypes to actually working on the design team alongside the designers themselves.

Number three, the design is driven and refined by user-centered evaluation. We absolutely must have real users evaluating the prototypes and interfaces that we assemble.

Number 4, the process is iterative. No tool is developed once, released, and then abandoned. Designs undergo constant iteration and improvement, even after being released.

Number 5, the design addresses the whole user experience. Many designers are tempted to delineate a certain portion of the experience as their primary interest, but we must address the entire user experience.

Number six, the design team includes multidisciplinary skills and perspectives. Good teams for pursuing user-centered design include people with a number of different backgrounds, like psychologists, designers, computer scientists, domain experts, and more. So keep these principles in mind when you're doing user experience design.

<a id="L3-1-stakeholders"></a>

### Stakeholders

When we talk about user-centered design, we throw around the word user as if it's pretty obvious what it means. The user is the person who uses the interface that we create, right? However, that's not the only person in whom were interested. There are multiple stakeholders in this design, and we want to explore how our design is going to affect all of them. The user themselves is what we call the primary stakeholder. They're the person who uses our tool directly.

Secondary stakeholders are people who don't use our system directly, but who might interact with the output of it in some way.

Tertiary stakeholders are people who never interact with the tool or even interact with its output, but who are nonetheless impacted by the existence of the tool. So let's take a couple of examples of this. Imagine we're designing a new grade book tool that makes it easier for teachers to send progress reports to parents. Teachers would interact with the tool, inputting grades and feedback. And so teachers would be our primary stakeholders. Parents receive the output of that tool. Parents receive the progress reports. And so they're secondary stakeholders. They interact with the output of the system, but not with the system itself. Students don't use the system at all, and maybe they don't even see the progress reports unless parents decide to share them. But they're nonetheless affected by the existence of this system. So they're tertiary stakeholders. School administrators might be another stakeholder, but where they fall in this would differ based on how the school sets up the relationship. If they can use the tool to directly monitor and intervene in student progress, they might be primary stakeholders. If they just see aggregated progress reports so they can monitor things, they might be secondary stake holders. If they never interact with the system in any way, they're nonetheless likely affected by the fact the system is there. And so they'd be tertiary stakeholders. In designing this tool, we need to keep all three kinds of stakeholders in mind. For example, how does parents having more consistent access to great information affect the students? It might foster increased involvement by parents, but it might also facilitate helicopter parenting, where parents are too controlling over their kid's school work and prevent them from developing the necessary meta-cognitive skills and self- discipline that they need to succeed later in life. User-centered design isn't just about catering to the user in the center of this diagram, but it's also about looking at the impact of our designs on all the stakeholders.

<a id="L3-1-quiz-reflections-hci-methods"></a>

### Quiz: Reflections: HCI Methods

You might actually come from a software engineering background, and so while user-centric designs sounds obvious to some people, you might have experienced the other side of the coin. In many industries and domains, software engineers are still left to design user interfaces themselves. There's a fantastic book about this called The Inmates Are Running the Asylum, by Alan Cooper. Where he compares technology to a dancing bear at a circus. He notes that people marvel at the dancing bear, not because it's good at dancing, but because it dances at all. The same way, people marvel at certain pieces of technology not because they work well, but because they work at all. The book was released in 2004 and since then the user has become more and more a focal point of design. And yet there are still places where individuals with little ACI background are designing user-facing interfaces for one reason or another. Since it's a stronger chance you've worked in software engineering, reflect on that a bit. Have you seen places where software engineers, data scientists, or even non-technical people were put in charge of designing user interfaces? How did it go?

I encountered this in my first job, actually. Somewhere between my freshman and sophomore years at Georgia Tech, I had a job as a user interface designer for a local broadcast company. I designed an interface, then I handed it over to a team of engineers for implementation. Late in the process, the requirements were changed a bit and new configuration screen was needed that the engineers just went ahead and looked up. We got the finish tool and it all worked beautifully and perfectly, except for this configuration screen. It was a list of over 50 different settings, each with 3 to 5 radio buttons to the side. Each setting was a different length. Each radio button label was a different length. There was kind of placed all over the canvas. There was no grid. It was illegible. It was unusable, but it was technically functional. It met the requirements described in terms of what the user must be able to do, just not how usable it was. Fortunately, there's a greater appreciation of the value of user-centered design now, than there was then. So, many spaces have become so crowded that the user experience is what can really set a company apart. I've actually been noticing a trend lately toward new user experiences around really old tasks. I use an app called stash to buy and sell small amounts of mutual funds. Buying mutual funds has been around forever and E-Trade has even been doing that online for a long time. What differentiates stash is the new user experience. Automated investing, simple tracking, simplified summaries. User experience design really has become a major differentiator between success and failure.

<a id="L3-1-the-design-life-cycle"></a>

### The Design Life Cycle

User centered design is about integrating the user into every phase of the design life cycle. So, we need to know two things. What the design life cycle is and how to integrate the user into each phase. Now if you look up design life cycles you'll find a lot of different ideas. We're going to discuss in terms of a four phase design life cycle that's pretty general and probably subsumes many of the other ones you'll find.

The first part of this is Needfinding. In Needfinding, we gather a comprehensive understanding of the task the users are trying to perform. That includes who the user is, what the context of the task is, why they're doing the task, and any other information related to what we're designing. Second, we develop multiple design alternatives. These are very early ideas on the different ways to approach the task. It's important to develop multiple alternatives to avoid getting stuck in one idea too soon. The third step is prototyping. We take the ideas with the most potential and we build them into prototypes that we can then actually put in front of a user. Early on we might do this in very low fidelity ways like with a paper and pencil, or even just verbally describing our ideas. But as we go on we refine and improve. Fourth, and most importantly, we perform user evaluation. We take our ideas that we prototyped and put them in front of actual users. We get their feedback, what they like and what they don't like, what works and what doesn't work, and then the cycle begins anew. The feedback we gain from the users, as well as our experience with these prototypes and design alternatives, improves our understanding of the problem. We now know new areas of the problem we might need to explore with some more need finding. Now we might have some new ideas for design alternatives, or some new ways of expanding the designs that we already have. We then take those things and use them to improve our prototypes. Either prototyping new ideas that we didn't have before, or making our prototypes more rigorous and more polished, so that we can get even better evaluation. And then we put them in front of users again. Each time we go through this cycle our understanding improves, our designs improve, and our prototypes improve. Eventually our prototypes develop to the point of being designs ready for launch, but the cycle doesn't end there. We keep iterating, now with live users doing the evaluation.

<a id="L3-1-methods-for-the-design-life-cycle"></a>

### Methods for the Design Life Cycle

At every stage of this design life cycle, we're interested in gathering information from the user to better inform our designs. To do that, we need a number of methods to actually obtain that information. Fortunately, there are a number of methods we can employ to try to gather the information we need. And in fact, the majority of this unit will go through all these different methods. These will become the tools in your toolbox. Things you can call upon to grab the information you need when you need it. Not the many of this method are so well-developed that you can cover them in the entire units, or even entire courses. For example, we'll spend about three or four minutes talking about naturalistic observation. And yet, there are entire textbooks and courses on how to do naturalistic observation really well. The goal of this is to give you enough information to get started and enough to know what you need to explore next. Remember, one of the original goals of this class was not just to understand more HCI but also to understand how big the field of HCI actually is.

<a id="L3-1-design-life-cycles-meets-feedback-cycles"></a>

### Design Life Cycles meets Feedback Cycles

When we talk about feedback cycles, we talk about how they're ubiquitous across nearly every field. And each CI itself, isn't any different. In a feedback cycle, the user does something in the interface to accomplish some goal. And then judges based on the output from the interface, whether the goal was accomplished, then they repeat and continue. In HCI, we're brainstorming and designing interfaces to accomplish goals. And then based on the output of our evaluations, we judge whether or not the goals of the interface were actually accomplished, then we repeat and continue. In many ways, we're doing the same things that our users are doing, trying to understand how to accomplish a task in an interface. Only in our case, our interface is the tools to build and evaluate interfaces and our goal is to help them accomplish their goal.

<a id="L3-1-qualitative-vs-quantitative-data"></a>

### Qualitative vs. Quantitative Data

There is one final distinction we need to understand going forward because it's going to come up at every stage of the design lifecycle, qualitative versus quantitative data. At every stage of the design lifecycle, we're interested in gathering data from users. Early on that might be descriptions of what they do when they're interacting with a task. Or it might be measures of how long certain tasks take to complete, or how many people judge a task to be difficult. Later on, though, it might be whether or not users prefer our new interfaces or how much better they perform on certain tasks.

Now data will always fall into one of two categories, qualitative and quantitative. Quantitative is probably the easier one to describe, quantitative data describes anything numeric.

When data is summarized numerically, we can perform statistical tests and summaries on it, draw formal conclusions, and make objective comparisons. Now there are a lot of strengths of quantitative data, but those strengths come in large part because quantitative data only captures a narrow view of what we might be interested in examining.

It's very strong for a very small class of things.

Qualitative data covers pretty much everything else.

Qualitative Data covers descriptions, accounts, observations, it's often in natural language. It could be open ended survey responses, or interview transcripts, or bug reports or just your personal observations.

Because of its flexibility, qualitative data gives us a much broader and more general picture of what we're examining. But the cost is that it's hard to generate formal conclusions based on qualitative data.

Qualitative data may be more prone to biases.

Now in some circumstances, we can convert qualitative data into quantitative data. For example, we could count the number of survey respondents to an end of course survey who mentioned course difficulty in their free response questions. Now the free response question would be qualitative data but numerically summarizing it generates quantitative data. Generally speaking, though, quantitative data and qualitative data serve different purposes in a design life cycle.

I've heard it described quantitative data provides the what, the qualitative data provides the how or the why. When performing need finding or when doing some initial prototype evaluations, we're likely interested in users' qualitative descriptions of their tasks or their experiences with the interface. It's generally only after a few iterations that we start to be interested in quantitative analysis, to find numeric improvements or changes.

We can also use these in conjunction with one another, collecting both quantitative and qualitative data from the same participants. That's referred to as a mixed method approach, it's a mix of qualitative and quantitative data to paint a more complete picture of the results.

<a id="L3-1-quiz-exercise-quantitative-vs-qualitative"></a>

### Quiz: Exercise: Quantitative vs Qualitative

Let's do a quick exercise on quantitative versus qualitative data. Let's imagine we're doing end of course evaluations for some class. For each of the following types of data, mark whether it would be considered quantitative or qualitative. You can skip ahead, if you don't want to listen to me read all these out. We have responses to on a scale of 1 to 5, rate this course's difficulty, responses to how much time did you spend per week on this course, responses to what did you like about this course, count of students mentioning office hours to the above questions, percentage of students that completed the survey, responses to a forum topic requesting non-anonymous course reviews, the number of participants in a late-semester office hours session, and the transcript of the conversation of that late-semester office hours session.

Quantitative data is numeric. Any of these things that can be measured numerically, really qualify as quantitative data. Many of these things are things that we can just count. We count the number of students mentioning office hours. We count the number of participants. Here we basically count the number of students that completed the survey and divided by all the students in the class. And here we have them count how many hours per week they think they spend in the course. The first option can be a little bit tricky. On a scale of one to five in a numeric scale, but because students have to choose one, two, three, four or five, it's not a continuous numeric scale. For example, we have no way of guaranteeing the student sees the difference between a three and a four as the same as the difference between a four and a five. The types of analysis we can do on the first kind of data, are more limited. But nonetheless it's still is measured numerically, so it still is quantitative data.

<a id="L3-1-design-challenge-recording-moocs"></a>

### Design Challenge: Recording MOOCS

As we go through the unit in this course on methods, we're going to take a running example as a design challenge to explore the different HCI research methods. I'm going to choose a challenge quite close to home for me. Improving the MOOC recording process.

<a id="L3-1-exploring-hci-hci-methods"></a>

### Exploring HCI: HCI Methods

As we go through the lessons in this unit, we're going to talk about the design life cycle. The process of finding user needs, brainstorming design alternatives, prototyping interfaces and evaluating those prototypes with users. Now depending on how you're taking this material, you might do this on your own with projects or assignments. Some of the most interesting applications of this material, though, are the emerging areas which might be outside the scopes of the assignments that you're doing. So as you're going through lessons in this unit, try to brainstorm a conceptual plan for how you might pursue the design life cycle in your area of interest. There are interesting issues that arise, unique different domains or application areas. In educational technology, for example, you need to take into consideration lots of stakeholders, students, parents, teachers, administrators and more. In virtual reality or wearable devices, you need to think a lot more about the technical constraints in finding creative ways to get around technological limitations to interaction. In computer supportive cooperative work, you might want to explore places where the phenomenon already exists like Wikipedia or geographically distributed companies. Throughout this unit, we'll revisit the stages of the design life cycle and explore how it might apply to your area of interest.

<a id="L3-1-conclusion-to-introduction-to-methods"></a>

### Conclusion to Introduction to Methods

In this lesson we introduce the concept of the design life cycle. There are a lot of versions of the design life cycle out there, but we're going to focus on the most general four-step cycle.

The cycle starts with needfinding, and then goes to constructing design alternatives, then to prototyping, and then to user evaluation, and then the cycle repeats.

The goal of this cycle is to realize user-centered design. Design that takes into consideration the user's needs at every step. In the rest of this unit, we're going to focus on filling up your design life cycle toolbox with tools for gathering the right kind of data at the right time, and using it in the right way.

— End of Lesson 3.1 — [Back to summary](#A-L3-1) · [Contents](#toc)

---

<a id="L3-2"></a>

## 3.2 Ethics and Human Research

**CS6750 · Human–Computer Interaction** — Lecture notes (David Joyner, Summer 2017 lecture book, pp. 420–455)

*Full lecture content, restructured for revision. `»` marks a speaker change in video-transcript dialogue.*

[Back to summary of this lesson](#A-L3-2) · [Table of contents](#toc) · [Keyword index](#partC)

**Sections in this lesson:**

- [Introduction to Research Ethics](#L3-2-introduction-to-research-ethics)
- [Origin of Institutional Review Board](#L3-2-origin-of-institutional-review-board)
- [The Value of Research Ethics](#L3-2-the-value-of-research-ethics)
- [Getting Started: CITI Training](#L3-2-getting-started-citi-training)
- [Getting Started: IRB](#L3-2-getting-started-irb)
- [IRB Protocols: Basics](#L3-2-irb-protocols-basics)
- [IRB Protocols: Human Subject Interaction](#L3-2-irb-protocols-human-subject-interaction)
- [IRB Protocols: Consent Procedures](#L3-2-irb-protocols-consent-procedures)
- [IRB Protocols: Wrapping Up](#L3-2-irb-protocols-wrapping-up)
- [Research Ethics and Industry](#L3-2-research-ethics-and-industry)
- [Quiz: Exercise: Research Ethics and Industry](#L3-2-quiz-exercise-research-ethics-and-industry)
- [Paper Spotlight: "Evolving the IRB: Building Robust Review for Industry Research"](#L3-2-paper-spotlight-evolving-the-irb-building-robust-review-for-industry-research)
- [Conclusion to Research Ethics](#L3-2-conclusion-to-research-ethics)

<a id="L3-2-introduction-to-research-ethics"></a>

### Introduction to Research Ethics

[MUSIC] Before we start working with real users there are a few ethical considerations we have to make. If you are doing a research as part of a university these are part of your contract with the university to do research on their behalf. Even if you are doing research independently for an industry there are still ethical obligations to follow. These considerations are important not only to preserve the rights of our users, but also to ensure the value of the data that we gather.

In this lesson, we'll talk a little bit about where these kinds of ethical considerations came from.

Then we'll talk about some of the basic ethical considerations that we need to make.

We'll also talk about Institutional Review Board, or IRB, the university organization that governs human subjects research.

<a id="L3-2-origin-of-institutional-review-board"></a>

### Origin of Institutional Review Board

In the first half of the 20th century, a number of pretty clearly unethical human subjects experiments took place. Many of them were conducted by scientists working for the Axis powers during World War II. But famously, many were also conducted right here in our own backyard, here in the United States. Among them were Milgam's obedience experiment where participants were tricked into thinking that they had administered lethal shocks to other participants to see how obedient they would be.

There was the Tuskegee syphilis study where rural African American men were intentionally injected with syphilis to study its progression.

And there was the Stanford prison experiment where participants were psychologically abused to test their limits or test how they would act under different circumstances.

In response to all this, the National Research Act of 1974 was passed, which led to the creation of institutional review boards to oversee research at universities.

The Belmont Report further summarizes basic ethical principles that research must follow in order to receive government support.

Among other things, the law dictated that the benefits to society must outweigh the risks to the subjects in the case of these experiments. It also dictated that subjects must be selected fairly, which was a direct response to the Tuskegee syphilis study. And perhaps most importantly, it demanded a rigorous informed consent procedures. So, the participants know what they're getting into and can back out at any time. These efforts all attempt to make sure that the positive results of research outweigh the negatives and that participant rights are always preserved.

<a id="L3-2-the-value-of-research-ethics"></a>

### The Value of Research Ethics

In this lesson, we're largely focusing on the practical steps we go through to get approval for human subject's research. But before we get into that, I want to highlight that this isn't just a bunch of bureaucratic steps necessary to make sure the people are treated ethically at all stages of research, IRBs main task is to make sure the potential benefits of the study are worth the potential risks. So as part of that, part of the role is to make sure the potential benefits are significant. A lot of the steps of the process are going to ensure that the data that we gather is useful. So for example, the IRB is sensitive about the perception of coercion. When participants feel coerced to participate in research, the data they actually supply may be skewed by that negative perception which impacts our results. Similarly, we might design studies that have some inherent biases or issues to them. We might demand too much from participants or ask questions that are known to affect our results. Much of the initial training to be certified to perform research is similarly not just about doing ethical research but also about doing good research. By recording who is certified, IRB helps ensure that research personnel all understand the basics of human subjects research. IRB is also there to monitor for these things as well and many of the steps of this process ensure that the research we perform is sound and useful. After all, if the research we perform is not useful, then even the smallest risks will outweigh the nonexistent benefits.

<a id="L3-2-getting-started-citi-training"></a>

### Getting Started: CITI Training

If you're going to be doing a research just part of a University project or University class, you need IRB approval. Different universities have different processes and policies for getting started with IRB. We're going to discuss the Georgia Tech policies and sets where these class is based but you should check with your university if you're from somewhere else to make sure you're following the right policies for your school. To get started, we need to complete the required training. So here I'm showing the IRB website, which is researchintegrity.gatech.edu/irb. And to get started, you need to complete your required training. So click required training over on the left.

This'll take you to a page that overviews the IRB required training and gives you a link of the left to begin your CITI training.

So click that, then login to your Georgia Tech account.

And you're going to want to complete Group 2, Social and Behavioral Research Investigators and Key Personnel. I can't show you exactly what it looks like to sign up fresh because I've already completed it. But you should be able to add a course and add that as your course. After you've completed CITI training you'll receive your completion report and then you'll be ready to get started with IRB.

<a id="L3-2-getting-started-irb"></a>

### Getting Started: IRB

After you've completed any necessary training you can access the IRB application for your own university. We're doing this in terms of Georgia Tech, so here's the tool we used called IRBWISE.

Here under my protocols, you'll see a list of all of the protocols to which you're added. A protocol is a description of a particular research project. It outlines the procedures that the IRB has approved regarding consent, recruitment, experimentation and more. Here we see approved protocols. Protocols that are new and haven't been submitted yet. Protocols that are waiting for the IRB to act on them. And amendments to protocols. Amendments are how we change earlier protocols to add new researchers or change what we're approved to do. After a protocol is approved, any changes must be submitted to the IRB as an amendment to be accepted separately.

<a id="L3-2-irb-protocols-basics"></a>

### IRB Protocols: Basics

Generally speaking, you might not ever be asked to complete a protocol yourself. You might instead just be added to an existing protocol. Still, you need to make sure to understand the procedures outlined by any protocol to which you're added, because they still govern what you do. So we'll run through the process of creating a protocol, but this will also cover the details to know about any protocol to which you are added. So for this, I have a draft protocol covering our user study on people who exercise.

Every protocol starts with the title of the protocol, and some certified personnel. These are required just to save the protocol.

We add approved research personnel on the study personnel page.

We would enter their name, select their role, and if their certification isn't already in the system, we would attach it here.

After adding them, they'll appear down here. The primary investigator, PI, must always be added first and it must be a faculty member.

The protocol description covers the study at a high level. This should briefly touch on what will be done, what the goal of the research is and what subjects will be asked to do. It doesn't cover all the details, but it covers enough for someone to understand generally what we're going for with this study.

Under the research design and methodology section, we describe our research. First, we describe the research design in the methodology. With human subjects research, this focuses on what users will experience and in what order. It also covers some experimental details like how subjects might be assigned different experimental conditions. Then we describe the duration of subject participation to make sure subjects aren't being asked to do too much.

Depending on what we're doing, we may need to provide data collection methods. This includes things like surveys, pre-tests and post-tests interview scripts, anything pre-prepared to elicit data for the participant. Then we also need to fully describe the potential benefits of the study. Remember, IRB is about making sure that the benefits out way the risks. If there are no benefits, then the benefits can't out way the risks. Benefits don't need to be to the individual participants though, but they could be to the greater community as a whole.

Similarly, we also needed to describe the risks associated with the study. For usability studies, very often our risks are not going to be very significant. Our risks might be those associated with normal work at a computer. But we still need to address this to acknowledge that we thought about what risks might arise to participants.

Then we describe the plan for the statistical analysis if we have one. Qualitative research might not have a statistical analysis plan, so that's why I've left this blank. Finally, we need to describe start and end dates of the research. Very often, this will break the research into a data collection phase and a research phase, where we actually analyze the data that we collected. Now we won't generally need to worry about many of the remaining options on this form, because we're not doing clinical studies and we generally don't have external funding unless you're working on a professor's research project. So now let's move on to subject details.

<a id="L3-2-irb-protocols-human-subject-interaction"></a>

### IRB Protocols: Human Subject Interaction

Because we're interested in human-computer interaction, we almost certainly will have human-subject interaction. So when it asks, will the research involve direct interaction with human subjects, we would click, yes.

That will bring us to a screen where we describe our subjects and the data we plan to collect from them. First, they want to know how many subjects we have and what genders. They want to make sure that we're not wasting participants' time if we're not going to actually analyze all their data. And that we're being fair to the different genders. A common problem in early research was over-representing male populations.

Second, they'll want to know if we're targeting any vulnerable populations. People that might not have the capacity to give true informed consent. If we do, we need to make special accommodations to make sure they're fully aware of their rights as participants.

Third, they want the scientific justification for the number of subjects to enroll in our study. Like I said, they want to make sure that we're not going to waste the time of a bunch of participants and then just throw their data out. That wouldn't be very respectful for our participants' time. If we're doing statistical tests this might be the number of participants necessary to find a certain effect size, which we'll talk about when we talk about quantitative research. If we're doing qualitative research, this is usually a smaller number and is more based on how many different perspectives we need to get a good picture of what we're trying to analyze. Alternatively, we might have external limits on our number of participants. For example, if you're doing classroom research, your maximum number of students is the maximum number of students in the class.

Next, we state the inclusion and exclusion criterion. The inclusion criterion are, who we specifically including, who's our targeting audience? The exclusion criterion are those that we're specifically excluding. Often times, one of these will just be the inverse of the other, but there may be times when we need to be more specific. For example, if we were doing research on undergraduate computer science education, our inclusion criteria might be undergraduate students. But our exclusion criteria would be undergraduate students that have previously taken a computer science class.

As before, we can skip the questions, for our purposes at least, that are more based on clinical research. But at the bottom, we need to provide the steps necessary to ensure additional protection of the rights and welfare of vulnerable populations. For example, if we're working with 10 year olds, how do we make sure 10 year olds really understand that they really do have the right to opt out of this research? We need to provide a plan for that here if we're working with a vulnerable population.

Finally, we also need to describe our recruitment procedures. How are we going to find our subjects? First, we'll note what we'll say and how we'll communicate with them here. If we're using the Georgia Tech subject pool, which is a system for finding research subjects within the Georgia Tech student body, we'll indicate so here.

And last, we'll note the kind of compensation we plan to provide the participants. Many times we won't compensate our participants at all. But if we're doing a bigger research study that actually has some external funding, it's pretty normal to give them some sort of monetary compensation for participation. It's we're using the George Tech subject pool, our compensation will often be extra credit in a certain class, very often a psychologist class. Note that the recruitment procedures are very important, especially if you're doing something like classroom research, where there can be a very significant perception of coercion to get people to participate. If I, as an instructor, am recruiting students in my own class to participate in my research project, I have to be very clear that it won't come back to haunt them if they choose not to participate.

<a id="L3-2-irb-protocols-consent-procedures"></a>

### IRB Protocols: Consent Procedures

One of the most important elements of IRB approval is consent, that was one of the things created by the Belmont Report. If we're doing any interaction with our human subjects, we definitely need to think about consent procedures.

On the consent information page, first, we need to indicate what kind of consent we'll receive. Most commonly, this will be written consent required. In this case, participants will sign or digitally sign, a consent form to start the study, but in some cases a waiver may be obtained.

First, a waiver of consent can be obtained under certain, pretty narrow circumstances, this generally means we don't need to receive the subject's consent at all. Most of the time this only applies when subjects will not be directly affected by the research. So for example, if we wanted to study educational or health data that's already been generated and is already anonymized, we might receive a waiver of consent. Because those subjects won't be impacted by the fact we're now researching their data. Similarly, if we were to go sit in a coffee house and just take notes on the order taking process in a way that didn't identify anyone. We might receive a waiver of consent, because our observation is not affecting those people.

We might also receive a waiver of documentation of consent. This occurs for low risk research, where the written consent itself, would be the only record of the participants identity. This applies to a lot of survey research or unrecorded interviews, where participants can be informed of their rights at the start, and their own continued participation constitutes continued implied consent. There's no reason to have them sign a consent form, because that consent form is the only reason we'd ever be able to identify them after the study.

After selecting our option, we need to provide a justification, if we requested a waiver. If we didn't, then no justification is necessary. We'll then describe the plan for obtaining informed consent. Generally, this will be to provide the consent form to participants at the start of a study, and make it very clear that they can withdraw from the study at any time.

If we're involving children, non English speakers or other at risk populations in our study, there may be some additional boxes to complete.

It's also important for us to assess whether participants are continuing to consent to the study. Often times, we do this by making it very clear at the start of the study that they can withdraw at any time. So that their continued participation constitutes implied continued consent.

Finally, it's also possible to have protocols where deception or concealment is proposed. In HCI, for example, we might want to tell participants that an interface is functioning even if someone behind the scenes is actually just making it look functional, so that we get good research data out of those participants. For example, if we were testing something like a new version of Siri, we might tell participants that it's functioning, when in reality someone is writing the responses by hand. If we're using deception or concealment like that, we'll indicate so here.

Then finally, we need to upload our consent forms.

At Georgia Tech the Office of Research Integrity Assurance provides consent form templates that we can tweak to match the specific needs of our study. The templates provide in depth directions on what to supply. Generally, this is where we disclose to participants the details of the rest of the protocol. What we're researching, why, how, and why they were invited to participate?

<a id="L3-2-irb-protocols-wrapping-up"></a>

### IRB Protocols: Wrapping Up

Of the remaining fields the only one we're likely interested in is the data management questions. The majority of the others cover either clinical research or biological research or other things that we hopefully won't touch on very much in human computer interaction. Unless the field has changed a lot by the time you're listening to this. Nonetheless though you should actually peek into the items to make sure that they don't apply to you if you're filling out a protocol like this. Under the Data Management section, we'll want to describe how we keep participants data safe. That'll include descriptions of the way we store it and define information about participants. And how we'll safeguard the data itself through password protection or encryption or anything like that.

Finally, there are always some questions that we answer for all studies even though they generally won't apply to us. Generally our studies won't involve the Department of Defense, generally they shouldn't involve Radiation. And one day I really kind of hope they involve Nanotechnology but we're probably not quite there yet.

So we'd mark no that there is no DoD involvement.

Finally, at the bottom, there's a place to upload some additional documents. This is where we would supply things like an interview script, a survey, a recruitment script and other documents that the IRB would want to see and approve. When we're done, we can click Save and Continue Application.

On the next page, we can preview everything on one flat screen, and then check off at the end that we have no conflicts of interest, or report them, if we do.

Then we'll click Save & Continue again.

And for y'all, you would then submit it to your primary investigator. I am the primary investigator so I see something a little bit different here than what you would see. After submission, we'll generally hear back from IRB in about three weeks about whether the study was accepted and what changes need to be made if not.

<a id="L3-2-research-ethics-and-industry"></a>

### Research Ethics and Industry

Institutional review boards govern any research institutions that receive support from the federal government. But what about research that doesn't receive any federal support? Very often, companies will do research on their users. This is especially common in HCI. Lots of companies are constantly doing very interesting testing on their users with a lot of rapid AB experiments. There's a lot of potential knowledge there, but at the same time much of what they do likely would not pass IRB if it were university research. This actually came up recently with Facebook in a paper they published titled experimental evidence of massive-scale emotional contagion through social networks. Basically, Facebook wanted to see if they could predict what would make users happy or sad. And as a result they tweaked the news feed for some users to test out their ideas. In other words, they tried to manipulate their user's mood for experimental purposes.

Now, Facebook argues that this was consistent with their own data use policy, which permits them to perform experiments like this. Some social scientists however would argue that this does not constitute informed consent. Informed consent they say is specific to a certain experiment, temporary for a known period of time and given without coercion. Some would argue that if you don't agree you can't use Facebook qualifies as coercion. These are some difficult issues and if you end up working in HCI industry, you'll likely find yourself wrestling with some of them.

<a id="L3-2-quiz-exercise-research-ethics-and-industry"></a>

### Quiz: Exercise: Research Ethics and Industry

People are still discussing whether or not Facebook's study on its impact on users' moods was ethical. Facebook maintains that the study was consistent with its own data use policy, which constitutes informed consent. Opponents argue that it doesn't. What do you think? If you think that this was ethical, why do you think it was ethical? If you think that it was unethical, what could've made it ethical?

If you said yes, there are several reasons you might have stated. You might agree that because the terms of service covered it, it was technically ethical research. The users did agree to things like this.

You may have actually read the article or read other publications about it and noted that Facebook actually has an internal IRB that reviews things like this.

And in this case, an external IRB did review the study.

If you said no, the reason you gave may have been that we know users are not aware of what's in terms of use. We have plenty of studies that indicate that users really don't spend any time reading what they're agreeing to. And while technically, it's true that they're still agreeing to it, what we're interested in here are participants' rights. If we know that users aren't reading what they're agreeing to, don't we have an ethical obligation to make sure they're aware before we go ahead with it.

We also might say no because users couldn't opt out of this study. Part of that is because opting out of the study alone means deactivating your entire Facebook account or just stopping using the tool. But part of it is that users also weren't aware that a study was now going on. They couldn't opt out of the study specifically, nor could they even opt out of it by closing down their entire Facebook account because they didn't know when the study had started.

That ties into the other issue. Users weren't notified that they were participants in an experiment. So even though they technically agreed to it when they agreed to Facebook's terms of service, one could argue the fact they weren't notified when the study was beginning and ending means that it wasn't ethical research. I'm not going to give you a right or wrong answer to this. There's a very interesting conversation to have about this. But what's most important here are the interesting questions that it brings up. Especially in regard to companies doing human subjects research that doesn't have any over sight from the federal government. If you agreed with these reasons why it wasn't ethical, what could they have done to fix it? Maybe they could have separated out the consent process for research studies from the rest of Facebook as a whole. Maybe they could have specifically requested that individual users opt-in, and alert them when the study was done, but not tell them what's actually being manipulated. And even if the original study was ethical, there were likely things that could have reduced the backlash. At the same time, those things might have affected the results. These are the tradeoffs that we deal with.

<a id="L3-2-paper-spotlight-evolving-the-irb-building-robust-review-for-industry-research"></a>

### Paper Spotlight: "Evolving the IRB: Building Robust Review for Industry Research"

In a recent paper in the Washington and Lee Law Review, Molly Jackman and Lauri Kanerva, two Facebook employees, explore exactly this issue.

Jackman and Kanerva specifically note that the ethical guidelines developed in the context of academia do not always address some of the considerations of industry.

In response, the authors directly advocate for setting up a set of principles and practices for industry environments. In other words, rather than just ignoring the parts that aren't relevant for industry, the authors advise creating a new set of standards specifically for industry.

To do so, Facebook designed its own internal review process. In this case, Facebook's process is heavily reliant on differing to a research area expert. And I don't say defer in a bad way. A key part of IRB is experiments are reviewed by people with no incentive to permit the study if it isn't ethical.

Facebook tries to replicate this by referring studies to an external reviewer who, in turn, decides whether or not an additional review and even external IRB is necessary. The other thing that's important to note though, is that Facebook isn't under any strong obligation to do this. Universities that receive federal funding are govern by the Belmont Report. But companies are not yet governed by any similar law. So we rely on companies to govern themselves. In Facebook's case, it seems to be going pretty well. But you might find yourself at a company that doesn't have such a program, and you'll have to apply these standards yourself.

<a id="L3-2-conclusion-to-research-ethics"></a>

### Conclusion to Research Ethics

In this lesson, we've talked about research ethics. Research ethics guide the human subject's research we do to make sure we're respecting the rights of our participants. But it also make sure the data we're gathering is good and useful. At every stage of our design life cycle, we want to keep respect for our participants at the forefront of our thought. That means being wary of experimenting in ways that might negatively affect users. That also means only asking users to dedicate their time to evaluating interfaces that are well thought out. And that means respecting users' viewpoints and position in the design process.

— End of Lesson 3.2 — [Back to summary](#A-L3-2) · [Contents](#toc)

---

<a id="L3-3"></a>

## 3.3 Needfinding and Requirements Gathering

**CS6750 · Human–Computer Interaction** — Lecture notes (David Joyner, Summer 2017 lecture book, pp. 456–502)

*Full lecture content, restructured for revision. `»` marks a speaker change in video-transcript dialogue.*

[Back to summary of this lesson](#A-L3-3) · [Table of contents](#toc) · [Keyword index](#partC)

**Sections in this lesson:**

- [Introduction to Needfinding](#L3-3-introduction-to-needfinding)
- [Data Inventory](#L3-3-data-inventory)
- [The Problem Space](#L3-3-the-problem-space)
- [User Types](#L3-3-user-types)
- [5 Tips: Avoiding Bias in Needfinding](#L3-3-5-tips-avoiding-bias-in-needfinding)
- [Naturalistic Observation](#L3-3-naturalistic-observation)
- [5 Tips: Naturalistic Observation](#L3-3-5-tips-naturalistic-observation)
- [Participant Observation](#L3-3-participant-observation)
- [Hacks and Workarounds](#L3-3-hacks-and-workarounds)
- [Errors](#L3-3-errors)
- [Apprenticeship and Ethnography](#L3-3-apprenticeship-and-ethnography)
- [Interviews with Focus Groups](#L3-3-interviews-with-focus-groups)
- [5 Tips: Interviews](#L3-3-5-tips-interviews)
- [Quiz: Exercise: interviews](#L3-3-quiz-exercise-interviews)
- [Think-Aloud](#L3-3-think-aloud)
- [Surveys](#L3-3-surveys)
- [5 Tips: Surveys](#L3-3-5-tips-surveys)
- [Quiz: Exercise: Surveys](#L3-3-quiz-exercise-surveys)
- [Other Data Gathering Methods](#L3-3-other-data-gathering-methods)
- [Quiz: Exercise: Needfinding Pros and Cons](#L3-3-quiz-exercise-needfinding-pros-and-cons)
- [Quiz: Design Challenge: Needfinding for Book Reading](#L3-3-quiz-design-challenge-needfinding-for-book-reading)
- [Iterative Needfinding](#L3-3-iterative-needfinding)
- [Revisiting the Inventory](#L3-3-revisiting-the-inventory)
- [Representing the Need](#L3-3-representing-the-need)
- [Defining the Requirements](#L3-3-defining-the-requirements)
- [Exploring HCI: Needfinding](#L3-3-exploring-hci-needfinding)
- [Conclusion](#L3-3-conclusion)

<a id="L3-3-introduction-to-needfinding"></a>

### Introduction to Needfinding

[MUSIC] The first stage of the design life cycle is needfinding, or requirements gathering. This is the stage where you go and try to find out what the user really needs. The biggest mistake that the designer can make is jumping to the design process before understanding the user or the task. We want to develop a deep understanding of the tasks they're trying to accomplish and why. As we do this, it's important to try to come in with as few preconceived notions as possible.

There's an old adage that says when all you have is a hammer, everything looks like a nail. This is similar. If you come in having already decided what approach you want to take it's tempting to only see the problem in terms of the approach you've chosen. So we're going to go through a process that attempts to avoid as many preconceived notions as possible.

We're going to start by defining some general questions we want to answer throughout the data gathering process about who the user is, what they're doing, and what they need.

Then we'll go through several methods of generating answers to those questions to gain a better understanding of the user.

Then we'll talk about how to formalize the data we gather into a shareable model of the task and a list of requirements for our ultimate interface. Note that each of these tools could get a lesson on its own on how to do it, so we'll try to provide some additional resources to read further on the tools you choose to use.

<a id="L3-3-data-inventory"></a>

### Data Inventory

Before we start our need-finding exercises, we also want to enter with some understanding of the data we want to gather. These are the questions we ultimately want to answer. That's not to say we should be answering them every step of the way, but rather, we want to gather the data necessary to come to a conclusion at the end. Now, there are lots of inventories of the types of data you could gather, but here's one useful list. One, who are the users? What are their ages, genders, levels of expertise? Two, where are the users? What is there environment? Number three, what is the context of the task? What else is competing for users' attention? Four, what are their goals? What are they trying to accomplish? Five, right now, what do they need? What are the physical objects? What information do they need? What collaborators do they need? Six, what are their tasks? What are they doing physically, cognitively, socially? And seven, what are the subtasks? How do they accomplish those subtasks? When you're designing your need finding methods, each thing you do should match up with one or more of these questions.

<a id="L3-3-the-problem-space"></a>

### The Problem Space

In order to do some real need finding, the first thing we need to do is identify the problem space. Where is the task occurring, what else is going on, what are the user's explicit and implicit needs? We'll talk about some of the methods for doing that in this lesson, but before we get into those methods, we want to understand the scope of the space we're looking at.

So consider the difference between these two actions. [MUSIC] Notice that in each of these, I'm doing the same task, turning off the alarm. But in the first scene we're focusing very narrowly on the interaction between the user and the interface. In the latter, we're taking into consideration a broader view of the problem space. We could zoom out even further if we wanted to and ask questions about Where and why people need alarm systems in the first place. That might lead us to designing things like security systems for dorm rooms or checking systems for office buildings. As we're going about need finding, we want to make sure we're taking the broad approach. Understanding the entire problem space in which we're interested, not just focusing narrowly on the user's interaction with a particular interface. So in our exploration of methods for need finding, we're going to start with the most authentic types of general observation, then move through progressively more targeted types of need finding.

<a id="L3-3-user-types"></a>

### User Types

Just as we want to get an idea of the physical space of the problem, we also want to get an idea of the space of the user. In other words, we want to understand who we're designing for. That comes up a lot when doing design alternatives and prototyping, but we also want to make sure to gather information about the full range of users for whom we're designing. So let's take the example of designing an audiobook app for people that exercise. Am I interested in audiobooks just for kids or for adults too? Am I interested in experts who are exercising or novices at it? Am I interested in experts at listening to audiobooks or am I interested in novices at that as well? Those are pretty key questions. They differentiate whether I'm designing for business people who want to be able to exercise while reading, or exercisers who want to be able to do something else while exercising. The task is similar for both but the audience, their motivations and their needs are different. So, I need to identify these different types of users and to read funny exercises on all of them. One of the most successful products of all time succeeded because of the attention to user types. The Sony Walkman became such a dramatic success because they identified different needs for different types of people, design their product in a way that it met all those needs, but then they market it specifically to those different types of individuals.

You can read more about that in a book called Doing Cultural Studies by Hugh Mackay and Linda Janes.

<a id="L3-3-5-tips-avoiding-bias-in-needfinding"></a>

### 5 Tips: Avoiding Bias in Needfinding

During needfinding, there are some significant considerations that need to be made to avoid biasing your results. Let's go through five of these possible biases. Number one, confirmation bias, confirmation bias is the phenomenon where we see what we want to see. We enter with some preconceived ideas of what we'll see, and we only notice the things that confirm our prior beliefs. Try to avoid this by specifically looking for signs that you're wrong, by testing your beliefs empirically, and by involving multiple individuals in the need finding process. Number two, observer bias, when we're interacting directly with users, we may subconsciously bias them. It might be more helpful, for example, with users using the interface that we designed compared to the ones that other people designed. On surveys, we might accidentally phrase questions in a way that elicits the answers that we want to hear. Try to avoid this by separating experimenters with motives from the participants. By heavily scripting interactions with users, and by having someone else review your interview scripts and your surveys for leading questions. Number three, social desirability bias, people tend to be nice. People want to help. If you're testing an interface and the participants know that you're the designer of the interface, they'll want to say something nice about it to make you happy. But that gets in the way of getting good data. Try to avoid this by hiding what the socially desirable response is by conducting more naturalistic observations and by recording objective data. Number four, voluntary response bias, studies have shown that people with stronger opinions are more likely to respond to optional surveys. You can see this often in online store reviews. The most common responses are often fives and ones. For us, that means if we perform quantitative analysis on surveys, we risk over sampling the more extreme views. Avoid this by limiting how much of the survey content is shown to users before they begin the survey and by confirming any conclusions with other methods. Number five, recall bias, studies have also shown that people aren't always very good at recalling what they did, what they thought, or how they felt during an activity they completed in the past. That can lead to misleading and incorrect data. Try to avoid this by setting tasks in contexts by having users think out loud during activities or conducting interviews during the activity itself. Now these biases can get a larger control also by making sure to engage in multiple forms of need finding.

<a id="L3-3-naturalistic-observation"></a>

### Naturalistic Observation

For certain tasks, a great way for us to understand the users need is to simply watch. A great way for me to start understanding what it's like to need an audiobook app for exercising is to come somewhere where people are exercising and just watch them exercise. This is called naturalistic observation, observing people in their natural context. So I'm fortunate that I actually live across the street from a park, so I can sit here in my rocking chair on my porch and just watch people exercising. Now, I want to start with very specific observations and then generalize out to more abstract tasks. That way I'll observe something called confirmation bias which is basically when you see what you want to see, so what do I notice? Well, I notice that there's a lot of different types of exercisers. There are walkers, joggers, runners I see some rollerbladers, I see some people doing yoga. I see a lot of people riding bikes but the bikers seem to be broken into two different kinds of groups. I see a lot of people biking kind of leisurely but I also see some bikers who are a little bit more strenuous about it. I'm also noticing that while joggers might be able to stop and start pretty quickly, that's harder for someone riding a bike. So I might want to avoid designs that force the user to pull out their phone a lot because that's going to be dangerous and awkward for people riding bikes. Now I also see people exercising in groups and also people exercising individually. For those people exercising in groups, I don't actually know if they'd be interested in this. Listening to something might kind of defeat the purpose of exercising together. So I'm going to have to note that down as a question I want to ask people later. I also see that many people tend to stretch before and after exercising and I'm wondering if we can use that. Then we can have some kind of starting and ending sequence for this, so that a single session is kind of book ending by both stretching, and interacting with our app. Note that by just watching people engage in the task of exercising, I'm gathering an enormous amount of information that might affect my design. But note also, that while naturalistic observation is great, I'm limited ethically in what I can do. I can't interact with users directly and I can't capture identifying information like videos and photographs that's why I can't show you what I'm seeing out here. I'm also limited in that I don't know anything about what those users are thinking. I don't know if the people working out in groups would want to be able to listen to audiobooks while they're doing yoga. I don't know if bluetooth headsets would be problematic for people riding bike, I need to do a lot more before I get to the design phase. But this has been very informative in my understanding of the problem space and giving me things I can ask people later on.

<a id="L3-3-5-tips-naturalistic-observation"></a>

### 5 Tips: Naturalistic Observation

Here are five quick tips for doing naturalistic observation. Number one, take notes. Don’t just sit around watching for a while. Be prepared to get a targeted information and observations about what you see. Number two, start specific and then abstract. Write down the individual little actions you see people doing before trying to interpret or summarize them. If you jump to summarizing too soon, you risk tunnel vision. Number three, spread out your sessions. Rather than sitting somewhere for two hours one day and then moving on, try to observe in shorter 10 to 15 minute sessions, several times. You may find interesting different information, and your growing understanding and reflection on past exercises will inform your future sessions. Number four, find a partner. Observe together with someone else. Take your own notes and then compare them later so you can see if you all interpreted the same scenarios or actions in the same way. Number five, look for questions. Naturalistic observations should inform the questions you decide to ask participants in more targeted need-finding exercises. You don't need to have all the answers based on observation alone. What you need is questions to investigate further.

<a id="L3-3-participant-observation"></a>

### Participant Observation

Sometimes it's not just enough to watch people engaging in a task. Sometimes we want to experience a task for ourselves. So that's what I'm going to do. I listen to audiobooks a lot. I don't really exercise. I should, but I don't. But I'm going to try this out. So I've got my audiobook queued up, I've got my mic on so I can take notes as I run. So I'm going to go on a jog and see what I discover.

So what did I learn?

I learned that I'm out of shape for one thing. I already knew that but I learned it again. I also learned that this app would be very useful for anyone doing participant observation on exercisers. Because I kept having to stop to record notes for myself, which I could have done with this app that I'm trying to implement. But aside from that, I noticed that unexpected things happen pretty often that made me wish that I could easily go back in my book. Or sometimes there are just things I just wanted to hear again, but there was no easy way to do that. I also notice that there's definitely the need there for me. I already planned to listen to everything again now that I'm home because there were notes I wanted to take that I couldn't take easily. I also noticed that while sometimes I wanted to take notes, sometimes I also just want to leave a bookmark.

Now we do have to be careful here though. Remember you are not your user. When you're working as a participant observer, you can avail useful insights, but you shouldn't over represent your own experiences. You should use this experience as a participant observer to inform what you ask users going forward

<a id="L3-3-hacks-and-workarounds"></a>

### Hacks and Workarounds

Let's zoom in a little bit more on what the user actually does or we can do naturalistic and participant observation without having to directly interact much with our users. We need to get inside users heads a little more to understand what they're thinking and doing. If you're trying to design interfaces to make existing tasks easier, one way to research that is to look at the hacks that users presently employ. How do they use interfaces in non-intended ways to accomplish tasks or how do they break out of the interface to accomplish a task that could have been accomplished with an interface? If you're designing a task meant to be performed at a desk like this, looking at the person's workspace can be a great way of accomplishing this. So for example, I have six monitors around. And yet, you still see Post-It notes on my computer. How could I possibly need more screen real estate? Well, Post-It notes can't be covered up. They don't take away from the existing screen real estate. They're visible even when the computer is off. So, this implicit notes here is the way to hack around the limitations of the computer interface. Now when you're looking at hacks, it's important to not just look at what the user does and assume you understand why. Look at their work around and ask them why they're using them. Find out why they don't just use the interface that's currently in place. You might find they just don't know about them, which presents a different kind of design challenge. Now hacks are related to another method we can use to uncover user needs as well, which are called errors. Whereas hacks are ways users get around the interface to accomplish their tasks, errors are slips or mistakes that users frequently make while performing the task within the interface.

<a id="L3-3-errors"></a>

### Errors

When we’re trying to make iterative improvements, one of the best places we can look is at the errors users make with the tools they currently have available. We can fix those errors, but we can also use those errors to understand a bit more about the user’s mental model. So, here’s a common example of an error, for me, which is a slip. I keep my email open on this window over here. I’ll frequently forget that it’s my active window while trying to type into a window over here. As a result, I’ll hit a bunch of hotkeys in my email interface. I’ll tag random emails, delete random emails. It's just kind of a mess. This is a slip because there’s nothing wrong with my mental model of how this works. I understand that there's an active window and it's not selected. The problem is that I can easily forget which window is active. Mistakes on the other hand, are places where my mental model is weak and for me a place where that happens when I’m using my Mac. I’m used to a PC, where the maximize button always makes a window take up the entire screen. I’ve actually never fully understood the maximize button on a Mac. Sometimes it seems to work like a PC maximize button. Sometimes it just expands the window a bit, but not to the entire screen. Sometimes it enters even like a full screen mode, hiding the top task bar. I make mistakes there because I don’t have a strong mental model of how it works. So, if you were watching me, you could see me making these errors, and you could ask me why I’m making them. Why did I choose to do that if that was my goal. That works for both discovering hacks and discovering errors: watch people performing their tasks, and ask them about why certain things happen the way that they do.

Discovering hacks and errors involves a little bit more user interaction than just watching people out in the wild. So how might we do that if we’re doing something like creating an app that people are going to use in public? Well maybe we actually go up to people we see exercising out in public. We can actually get approval to do that. But that's going to be a little bit awkward, and the data we get might not be great. So at this point, we might be better off recruiting people to come in and describe their experiences. People experience hacks and errors pretty consciously, so our best bet would likely be to target exercise groups or local areas where exercisers frequent and recruit people to come in for a short study. Or, maybe we could recruit people to participate in a study during their normal exercise routine, taking notes on their experience or talking us through their thought process. We could actually take that to an extreme and actually adopt something like an apprenticeship approach, where we train to become users.

<a id="L3-3-apprenticeship-and-ethnography"></a>

### Apprenticeship and Ethnography

If we're designing interfaces for particularly complex tasks, we might quickly find out that just talking to our participants or observing them really isn't enough to get the understanding we need to design those interfaces. For particularly complex tasks, we might need to become experts ourselves in order to design those programs. This is informed by the domain of ethnography, which recommends researching a community or a job or anything like that, by becoming a participant in it. It goes beyond just participant observation though, it's really about integrating oneself into that area and becoming an expert in it and learning about it as you go. So we bring in our expertise and design in HCI and use that combined with the expertise that we develop to create new interfaces for those people. So for example, our video editors here at Udacity have an incredible incredibly complex workflow involving multiple programs, multiple workflows, lots of different people and lots of moving parts. There's no possible way I could ever sit down with someone for just an hour and get a good enough picture of what they do, to design a new interface that will help them out, I really need to train under them. I really need to become an expert at video editing and recording myself, in order to help them out. It's kind of like an apprenticeship approach. They would apprentice me in their field and I would use the knowledge that I gain to design new interfaces to help them out. So ethnography and apprenticeship are huge fields of research both on their own and as they apply to HCI. So if you're interested in using that approach take a look at some of the resources that we're providing.

<a id="L3-3-interviews-with-focus-groups"></a>

### Interviews with Focus Groups

A most targeted way of gather information from users though is just to talk to them. One way of doing that might be to bring them in for an interview. So I'm sitting here with Morgan, who's one of the potential users for our audio book app targeted at exercisers. And we're especially interested in the kinds of task you perform while exercising and listening to audio books at the same time. So to start, what kind of challenges do you run into doing these two things at once?

» I think the biggest challenge is that it's hard to control it. I have headphones that have a button on them that can pause it and play. But if I want to do anything else I have to stop, pull up my phone and unlock it just to rewind.

Yeah, that makes sense. Thank you. Interviews are useful ways to get at with the user is thinking when they're engaging in a task. You can do interviews one on one like this or you can even do interviews in a group with multiple users at the same time.

Those tend to take on the form of focus groups, where a number of people are all talking together about some topic, and you can use them to tease out different kinds of information. Focus groups can elicit some information we don't get from this kind of an interview, but they also present the risk of overly convergent thinking. People tend to kind of agree with other instead of bringing in new ideas. So they should really be used in conjunction with interviews, as well as other need finding techniques.

<a id="L3-3-5-tips-interviews"></a>

### 5 Tips: Interviews

Here are five quick tips for conducting effective interviews. Now we recommend reading more about this before you actually start interviewing people. But these should get you started. Number one. Focus on the six W's when you're writing your questions. Who. What. Where. When. Why and how. Try to avoid questions that lend themselves to one world or only yes or no answers, those are better gathered via surveys. Use your interview questions to ask open-ended, semi-structured questions. Number two. Be aware of bias. Look at how you're phrasing your questions and interactions, and make sure you're not predisposing the participant to certain views. If you only smile when they say what you want them to say, for example you risk biasing them to agree with you. Number three. Listen. Many novice interviewers get caught up in having a conversation with a participant rather than gathering data from the participant. Make sure the participant is doing the vast majority of the talking. And don't reveal anything that might predispose them to agree with you. Number four. Organize the interview. Make sure to have an introduction phase. Some lighter questions to build trust and a summary at the end so the user understands the purpose of the questions. Be ready to push the interview forward or pull it back on track. Number five. Practice. Practice your questions on friends, family, or research partners in advance. Rehearse the entire interview, gathering subjects is tough so when you actually have them you want to make sure to get the most out of them.

<a id="L3-3-quiz-exercise-interviews"></a>

### Quiz: Exercise: interviews

Interviews are likely to be one of the most common ways you gather data. So let's run through some good and bad interview questions real quick. So here are six questions. Which of these would make good interview questions? Mark the ones that would be good. For the ones that would be bad, briefly brainstorm a way to rewrite the question to make it better. You can go ahead and skip forward to the exercise if you don't want to listen to me read them out. Number one, do you exercise? Number two, how often do you exercise? Number three, do you exercise for health or for pleasure? Number four, what, if anything do you listen to while exercising? Number five, what device do you use to listen to something while exercising? Number six, we're developing an app for listening to audio books while exercising. Would that be interesting to you?

Personally, I think three of these are good questions. Do you exercise, is not a great question, because it's kind of a yes or no question. How often do you exercise, is actually the better way of asking the same question. It's subsumes all the answers to do you exercise, but leaves more room for elaboration or more room for detail. Do you exercise for health or for pleasure, is not a great question, because it presents to the user a dichotomy. It might not be the way they actually think about the problem. Maybe there's some other reason they exercise. Maybe they do it to be social, for example. We want to leave open all the possibilities a user might have. So instead of asking, do you exercise for health or for pleasure, we probably want to ask, why do you exercise? The next two questions work pretty well, because they leave plenty of room for the participant to have a wide range of answers, and they're not leading them towards any particular answer. We're not asking, for example, what smartphone do you use to listen to something, because maybe they don't use a smartphone. This sixth one is interesting. We're developing an app for listening to audiobooks while exercising. Would that be interesting to you? What's wrong with that question? When we say, we're developing an app, we introduce something called social desirability bias. Because we're the ones developing the app, the user is going to feel some pressure to agree with us, to support our ideas. People like to support one another. And so even if they wouldn't be interested, they'll likely say that they would, because that's the supportive thing to say. No one wants to say, hey, great idea, David, but I would never use it. So what we want to make sure to do is create no incentive for a user to not give us the complete, honest answer. Worrying about hurting our feelings is one reason why they wouldn't be totally honest. So we might reword this question just to say, would you be interested in an app for listening to audiobooks while exercising? Now granted, the fact that we're the ones asking still probably will tip off the user that we're probably thinking about moving in that direction, but at least it's going to be a little more collaborative. We're not tipping them off that we're already planning to do this, we're telling them that we might be thinking about doing it. And so if they don't think it's a good idea, they kind of feel like they should tell us right now, to save us time down the road. So by rephrasing the question that way, we hopefully, avoid biasing the participant to just agree with us to be nice.

<a id="L3-3-think-aloud"></a>

### Think-Aloud

Think-aloud protocols are similar to interviews in that we're asking users to talk about their perceptions of the task. But with think-aloud, we're asking them to actually do so in the context of the task. So instead of bringing Morgan in to answer some questions about listening to audiobooks while exercising, I'll ask her to actually think out loud while listening to audiobooks and exercising. If this was a different task like something on a computer, I could have her just come into my lab and work on it. But since this is out in the world, what I might just do is give her a voice recorder to record her thoughts while she's out running and listening. Now think aloud is very useful, because it can help us get at users thoughts that they forget when they are no longer engaged in the task. But it's also a bit dangerous by asking people to think aloud about their task, we encourage them to think about it more deliberately and that can change the way they actually act. So while it's useful to get an understanding of what they are thinking, we should check to see if there are places where what they do differs when thinking out loud about it.

We can do that with what's called a post-event protocol, which is largely the same, except we wait to get the user's thoughts until immediately after the activity. That way, the activity is still fresh in their minds, but the act of thinking about it shouldn't affect their performance quite as much.

<a id="L3-3-surveys"></a>

### Surveys

Most of the other methods for need finding, like observation, interviewing, apprenticeship, require a significant amount of effort for what is often relatively little data. Or it's data from a small number of users. We might spend an entire hour interviewing a single possible user or an hour observing a small number of users in the world. The data we get from those interactions is deep and thorough, but sometimes, we also want broader data. Sometimes, we just want to know how many people encounter a certain difficulty or engage in a certain task. If we're designing an audio book app for exercisers, for example. Maybe we just want to know how often those people exercises or maybe we want to know what kind of books they listen to. At that point, a survey might be our more appropriate means of need finding. Surveys let us get a much larger number of responses very quickly and the questions can be phrased objectively, allowing for quicker interpretation. And plus, with the Internet, they can be administered asynchronously for at a pretty low cost. A few weeks ago, for example, I came up with the idea for a study on Friday morning. And with the great cooperation from our local IRB office, I was able to send out the survey to potential participants less than 24 hours later and receive 150 responses within a week. Now of course, the data I receive from that isn't nearly as thorough as what I would receive from interviewing some of those participants. But it's a powerful way of getting a larger amount of data. And it can be especially useful to decide what to ask participants during interviews or during focus groups.

<a id="L3-3-5-tips-surveys"></a>

### 5 Tips: Surveys

Survey design is a well documented art form. And in fact, designing surveys is very similar to designing interfaces themselves. So many of the lessons we learn in our conversations apply here are well. Here are five quick tips for designing and administering effective surveys. Number one, less is more. The biggest mistake that I see novice survey designers make is to ask way too much. That affects the response rate and the reliability of the data. Ask the minimum number of questions necessary to get the data that you need and only ask questions that you know that you'll use. Number two. Be aware of bias. Look at how you're phrasing the questions. Are there positive or negative connotations? Are participants implicitly pressured to answer one way or the other? Number three. Tie them to the inventory. Make sure every question on your survey connects to some of the data that you want to gather. Start with the goals of the survey and then write the questions from there. Number four. Test it out. Before sending it to real participants, have your co-workers or colleagues test out your survey. Pretend they're real users and see if you would get the data you need from their responses. Number five, iterate. Survey design is like interface design, test out your survey, see what works and what doesn't and revise it accordingly. Give participants a chance to give feedback on the survey itself, so that you can improve it for future iterations.

<a id="L3-3-quiz-exercise-surveys"></a>

### Quiz: Exercise: Surveys

Writing survey questions is an art, as well as a science. So let's take a look at an intentionally poorly designed survey, and see everything we can find that's wrong with it. So on the left is a survey. It's kind of short, mostly because of screen real estate. Write down in the box on the right everything that is wrong with this survey. Feel free to skip forward if you don't want to listen to me read out the questions. On a scale of 1 to 4 with 1 meaning a lot and 4 meaning not at all, how much do you enjoy exercising? Why do you like to exercise? On a scale of 1 to 6 with 1 meaning not at all and 6 meaning a lot, how much do you like audiobooks? Have you listened to an audiobook this year?

Here are a few of the problems that I intentionally put into this survey. Some of them are kind of obvious, but hopefully a couple others were a little bit more subtle and a little bit more interesting. First when I say on a scale of one to four with one meaning a lot and four meaning not at all, what do two and three mean exactly? It's not a very clear scale to just say the endpoint. Just giving the endpoints doesn't give a very clear scale. We usually also want to provide an odd number of options, so that users have kind of a neutral central option. Sometimes we'll want to force our participants to take one side or the other, but generally we want to give them that middle neutral option. Either way though, we definitely don't want to change the number of options between those two questions. Having one be 1 to 4 and the other be 1 to 6 is just confusing. And even worse, notice that we're reversing the scale between these two. In the first question, the low number means a lot. In the second question, the high number means a lot. That's just terrible design. We want to be consistent across our entire survey, both with the direction of our scale and the number of options unless there's a compelling reason not to. The second question is also guilty of being quite a leading question. Why do you like to exercise assumes the participant likes to exercise. What are they supposed to say if they don't? And finally, the last question is a yes or no question. Have you listened to an audiobook this year? Yes or no. No is kind of an interesting answer, but yes, I don't know if you listened to one audiobook this year or a 100 audiobooks this year. I don't know if you listened every single day or if you just listened once because you had a gift certificate. So we want to reword this question to be a little more open-ended and support a wider range of participant answers.

<a id="L3-3-other-data-gathering-methods"></a>

### Other Data Gathering Methods

So far we've discussed some of the more common approaches that need finding. Depending on your domain though, there might be some other things you can do. First, if you're designing for a task for which interfaces already exist, you might start by critiquing the interfaces that already exist using some of the evaluation methods that we'll cover later in the evaluation lesson. For example, if you're wanting to design a new system for ordering takeout food, you might evaluate the interfaces of calling in an order, ordering via mobile phone or ordering via a website.

Second and similarly, [SOUND] if you're trying to develop a tool to address a problem that people that are already addressing, you might go look at user reviews and see what people already like and dislike about existing products. For example, there are dozens of alarm clock apps out there, and thousands of reviews. If you want to design a new one, you could start there to find out what people need or what their common complaints are.

Third, if you're working on a task that already involves a lot of automatic logging like web surfing, you could try to get some logs of user interaction that have already been generated. For example, say you wanted to build a browser that's better at anticipating what the user will want to open next. You could grab data logs and look for trends both within and across users. You can creative with your data gathering methods. The goal is to use a variety of methods to paint a complete picture of the user's task.

<a id="L3-3-quiz-exercise-needfinding-pros-and-cons"></a>

### Quiz: Exercise: Needfinding Pros and Cons

In this lesson we've covered a wide variety of different methods for need finding. Each method has its own disadvantages and advantages. So let's start to wrap up the lesson by exploring this with an exercise. Here are the methods we've covered, and here are the potential advantages. For each row, for each advantage, mark which need-finding method actually has that advantage. Note that these might be somewhat relative, so your answer may differ from ours. Go ahead and skip to the exercise if you don't want to listen to me read these out. The columns from left to right are Naturalistic Observation, Participant Observation, Errors and Hacks, Interviews, Surveys, Focus Groups, Apprenticeship, and Think-Aloud. The potential advantages are Analyzes data that already exists, Requires no recruitment, Requires no synchronous participation, Investigates the participant's thoughts, occurs within the task context, and cheaply gathers lots of users' data.

Here's my answer to this very complicated exercise. Two methods that analyze data that already exists are Naturalistic Observation and Errors and Hacks. Naturalistic Observation doesn't necessarily analyze data that already exists, but it analyzes data that's being produced already on its own without observing it, so we don't have to go out and create an opportunity for data to happen. We just have to observe it and capture it where it's already taking place. Errors and Hacks, look at the way users already use interfaces to see what errors they regularly make or when they have to work around the interface. The two methods that require no recruitment are Naturalistic Observation and Participant Observation. In both cases, we don't need other human participants to come do anything differently based on the fact that we're doing some research. With interviews, surveys, Focus Groups, apprenticeship and Think- Aloud, we're always asking users to do something to accommodate us or to give us some data. And with Errors and Hacks, even if we can view that data on our own, we still need the user to give us permission to view their workspace or watch them do whatever they're doing. There might be some times when you can look for Errors and Hacks with Naturalistic Observation, but generally you need to get enough into the users head to understand why something's an error or why they need to use a certain hack. For the most part, all of these are going to need some synchronous participation. There might be some exceptions. For example, we could do a retrospective analysis of Errors and Hacks, or we can have someone do a Think-Aloud protocol where they actually write down their thoughts after doing a task. But generally speaking, the way most of these are usually done, they require synchronous participation. Surveys are the exception. Surveys we usually send out to someone, wait some period of time, and get back the results. So we never have to be interacting live with any of our participants. That's one of the reasons why surveys can get a lot more data than other methods. Adding more participants doesn't necessarily require more of our time, at least not to gather the data in the first place. Analyzing it might require more time at the end, but that's not synchronous either. As far as investigating participant thoughts is concerned, almost all these methods can investigate this when used correctly. We could do a survey does not actually investigate participants thoughts, but a well designed survey is going to trying get a heart of the users thinks about things. The only exception is Naturalistic Observation where by definition, we're just watching people we're not interacting with them or we're not asking them what they are thinking. It's always extremely valuable for us to be able to do some needfinding that occurs within the task context itself. And unfortunately interviews and surveys, which are some of our most common data gathering methods, very often don't occur within the task context. Naturalistic Observation and Participant Observation obviously do, but since they don't involved getting inside the real users head, their contributions are a little bit more limited. Apprenticeship and Think-Aloud really capture the benefits of occurring within the task context, because either way we get the user's thoughts while they're engaging with the task, or immediately thereafter. It is possible to do interviews and Focus Groups within the task contexts as well, it just isn't quite as common. Errors and Hacks are certainly debatable as well, because the Errors and Hacks themselves definitely occur within the task context, but our analysis of them usually doesn't. And finally, as we talk about when we discuss cognitive task analysis, one of the challenges with needfinding is that most of our approaches are extremely expensive. If we want to gather a lot of data cheaply, then we probably need to rely on surveys. Everything else is either going to incur a pretty significant cost or it just isn't capable of gathering a lot of data. For example, we could cheaply be participant observations for weeks on end, but we're only ever going to gather data from one person and that's never ideal.

<a id="L3-3-quiz-design-challenge-needfinding-for-book-reading"></a>

### Quiz: Design Challenge: Needfinding for Book Reading

The needfinding exercises that we've gone through so far focus on the needs of the exercisers. What can they do with their hands, what is the environment around them like while exercising, and so on? However, that's only half the picture for this particular design. Our ultimate goal is to bring the experience of consuming books to people that exercise, which means we also need to understand the task of book-reading on its own. Now a problem space is still around exercisers, so we wouldn't go through the entire design life cycle for book reading on its own. We don't need to design or prototype anything for them. But if we're going to bring the full book reading experience to people while exercising, we need to understand what that is. So take a moment and design an approach to needfinding for people who are reading on their own.

We could apply pretty much every single need-finding method that we've discussed to this task. We could, for example, go to the library and just watch people reading and see how they're taking notes. We've all likely done it ourselves. We can reflect on what we do while reading, although again, we need to be careful not to over-value our own priorities and approaches. Reading is common enough, that we can easily find participants for interviews, surveys, think alouds. The challenge here will be deciding who our users really are. Books are ubiquitous. Are we trying to cater to everyone who reads deliberately? If so, we need to sample a wide range of users or initially, we could choose a subset. We might cater to students who are studying or busy business people, or people that specifically walk or bike to work. We might start with one of those groups and then abstract out over time. We might eventually abstract all the way to just anyone who's unable to read and take notes the traditional way like people driving cars or people with visual impairments but that's further down the road. The more important thing is that we define who our user is, define the task in which we're interested, and deliberately design for that user and that task throughout the design life cycle.

<a id="L3-3-iterative-needfinding"></a>

### Iterative Needfinding

We've noted that design is a life cycle from needfinding to brainstorming design alternatives to prototyping to evaluation. And then, back to needfinding to continue the cycle again.

Needfinding on its own though can be a cycle by itself. For example, we might use the results of our naturalistic observation to inform the questions we asked during our interviews. For example, imagine that we noticed that very many joggers, jog with only one earphone in. That's a naturalistic observation, and then in an interview, we might ask, why do some of you jog with only one earphone in? And we might get the answer from the interview that it's to listen for cars or listen for someone trying to get their attention because they exercise in a busy area. Now that we understand why they have that behavior, maybe we develop a survey to try and see how widespread that behavior is, and ask, how many of you need to worry about what's around you when you're listening while driving? If we notice in those surveys a significant split in the number of people who were concerned about that, that might inform our next round of naturalistic observation. We might go out and look and see in what environments are people only wearing one headphone and in what environments are they wearing both.

So in that way all of the different kinds of need finding that we do can inform our next round of other kinds of need finding. We can go through entire cycles just of need finding without ever going on to our design alternatives or prototyping stages. However, the prototyping and evaluation that we do will then become another input into this. During our evaluation we might discover things that will then inform what we need to do next as far as need finding is concerned. Creating prototypes and evaluating them gives us data on what works and what doesn't. And that might inform what we want to observe to better understand the task going forward.

That's the reason why the output of evaluation is more needfinding. It would be a mistake to do one initial needfinding stage, and then jump in to a back and forth cycle of prototyping and evaluation.

<a id="L3-3-revisiting-the-inventory"></a>

### Revisiting the Inventory

During these need-finding exercises, you'll have gathered an enormous amount of information about your users. Ideally, you've combined different sets of these approaches. You've observed people performing the tasks, you've asked them about their thought process, and you tried it some yourself. Pay special attention to some of the places where the data seem to conflict. Are these cases where you as the designer understand some elements of the task that the users don't? Or are these cases where your expertise hasn't quite developed to the point of understanding the task? Once you've gone through the data gathering process, it's time to revisit that inventory of things we wanted to gather initially. One, who are the users? Two, where are the users? Three, what is the context of the task? Four, what are their goals? Five, right now, what do they need? Six, what are their tasks? And seven, what are the subtasks? Revisit these, with the results of your data gathering in mind.

<a id="L3-3-representing-the-need"></a>

### Representing the Need

Now that you have some understanding of the user’s needs, it’s time to try to formalize that into something we can use in design. There are a number of different ways we can do this.

For example, maybe we create a step-by-step task outline of the user engaging in some task. We can break those tasks down into sub-tasks as well, all the way down to the operator level.

We can further develop this kind of task outline into a hierarchical network, like we talked about before. This might involve more complexity than simply a linear series of actions.

We might further augment this with a diagram of the structural relationships amongst the components in the system and how they interact. This might give us some information about how we get feedback back to the user or how they interact with our interface in the first place.

From there, we might develop this even more into a flow-chart equipped with decision-making points or points of interruptions. Notice how these representations are very similar to the outcomes of the task analyses we talk about in the principles unit of our conversations. We can similarly use the data gathered from here to summarize a more comprehensive task analysis that will be useful in designing and prototyping our designs.

<a id="L3-3-defining-the-requirements"></a>

### Defining the Requirements

Finally, the final step for need-finding is to define our requirements. These are the requirements that our final interface must meet. They should be specific and evaluatable, and they can include some components that are outside of users tasks, as well, as defined by the project requirements.

In terms of user tasks, we might have requirements for guarding functionality, what the interface can actually do.

Usability, how certain user interactions must work.

Learnability, how fast the user can start to use the interface.

And accessibility, who can use the interface.

We might also have some that are generated by external project requirements, like compatibility, what devices the interface can run on.

Compliance, how the interface protects user privacy.

Cost, how much the final tool can actually cost, and so on. We'll use these to evaluate the interfaces we develop, going forward.

<a id="L3-3-exploring-hci-needfinding"></a>

### Exploring HCI: Needfinding

How might need finding work in your chosen area of HCI? If you're looking at designing for some technological innovation like augmented or virtual interactions, the initial phase might not actually be that different. Your goal is to understand how people perform tasks right now without your interface. So initially, you want to observe them in their naturalistic environment. Later though, you'll need to start thinking about bringing participants to you to experience the devices first hand. If you're interested in something like HCI for healthcare or education, you have a wealth of naturalistic observation available to you. You might even have existing interfaces doing what you want to do. And you can try to leverage those as part of your need finding exercises. Remember, no matter your area of application, you want to start with real users. That might be observing them in the wild, talking to them directly, or looking at data they've already generated.

<a id="L3-3-conclusion"></a>

### Conclusion

Today, we've talked about need finding. Need finding is how you develop your understanding of the needs of your user. What tasks are they completing? What are the context of those tasks? What else is going on? What are they thinking during the task and what do they have to hold in working memory? All these things feed into your understanding of our users needs.

Now we've discussed a number of different techniques to approach this, ranging from low intervention to high intervention.

On the low side, we can just observer our users in the wild or we can become users ourselves and participate in the task.

Working up we can try to look more closely at users areas to find errors or hacks, or peruse the data that they're already generating.

We might interact with them directly through surveys, interviews or focus groups.

Or we might choose to work alongside them, not just participating in the task independently, but learning from them and developing expertise itself. Once you've gained a sufficient understanding, it's time to move on to the next step, brainstorming design alternatives.

— End of Lesson 3.3 — [Back to summary](#A-L3-3) · [Contents](#toc)

---

<a id="L3-4"></a>

## 3.4 Design Alternatives

**CS6750 · Human–Computer Interaction** — Lecture notes (David Joyner, Summer 2017 lecture book, pp. 503–541)

*Full lecture content, restructured for revision. `»` marks a speaker change in video-transcript dialogue.*

[Back to summary of this lesson](#A-L3-4) · [Table of contents](#toc) · [Keyword index](#partC)

**Sections in this lesson:**

- [Introduction to Design Alternatives](#L3-4-introduction-to-design-alternatives)
- [The Second Biggest Mistake](#L3-4-the-second-biggest-mistake)
- [The Design Space](#L3-4-the-design-space)
- [Individual Brainstorming 1](#L3-4-individual-brainstorming-1)
- [Individual Brainstorming 2](#L3-4-individual-brainstorming-2)
- [5 Tips: Individual Brainstorming](#L3-4-5-tips-individual-brainstorming)
- [Challenges in Group Brainstorming](#L3-4-challenges-in-group-brainstorming)
- [Rules for Group Brainstorming](#L3-4-rules-for-group-brainstorming)
- [5 Tips: Group Brainstorming](#L3-4-5-tips-group-brainstorming)
- [Fleshing Out Ideas](#L3-4-fleshing-out-ideas)
- [Personas](#L3-4-personas)
- [User Profiles](#L3-4-user-profiles)
- [Timeline](#L3-4-timeline)
- [Scenarios and Storyboards](#L3-4-scenarios-and-storyboards)
- [User Modeling](#L3-4-user-modeling)
- [Quiz: Exercise: Design Alternatives](#L3-4-quiz-exercise-design-alternatives)
- [Exploring Ideas](#L3-4-exploring-ideas)
- [Exploring HCI: Design Alternatives](#L3-4-exploring-hci-design-alternatives)
- [Conclusion to Design Alternatives](#L3-4-conclusion-to-design-alternatives)

<a id="L3-4-introduction-to-design-alternatives"></a>

### Introduction to Design Alternatives

[MUSIC]. When we've developed a good understanding of the needs of our user, it's time to move on to the second phase of the design life cycle, design alternatives. This is when we start to brainstorm how to accomplish the task we've been investigating. The problem here is that design is very hard, it's hard for a number of reasons. The number of choices we have to make, and things we have to control is more expansive than ever before.

Are we designing for desktops, laptops, tablets, smart phones, smart watches, augmented reality, virtual reality, 2D, 3D, gesture input, pen input, keyboard input, mouse input, voice input?

In this lesson, we're going to talk about how to generate ideas for designs.

And then we'll chat about how to explore those ideas a bit further to figure out what you want to actually pursue.

<a id="L3-4-the-second-biggest-mistake"></a>

### The Second Biggest Mistake

The biggest mistake that a designer can make is jumping straight to designing an interface without understanding the users or understanding the task. The second biggest mistake though is settling on a single design idea or a single genre of design ideas too early.

This can take on multiple forms. One form is staying too allegiant to existing designs or products. Take the thermostat, for example, again. If you settled on tweaking the existing design of a thermostat you would never invent the Nest. So if you're working on improving an existing interface, try to actually distance yourself from the existing solutions, at least initially during the brainstorming session. But this is also a problem if you're designing interfaces for new tasks as well.

Imagine for instance, that while you were observing people exercising, you started sketching interface ideas like how to make the buttons big enough or what buttons need to be featured prominently. In doing so, you're getting tunnel vision and missing out on any design alternatives that might involve voice or gesture control. So the second biggest mistake you can make is focusing too strongly on one alternative from the very beginning, instead of exploring the entire range of possible design alternatives.

The reason why this is such a common mistake, is that there's this natural tendency to think of it as a waste of time to develop interfaces you're not going to end up using. You think you can get it done faster just by picking one early on and sticking to it. But flushing out ideas for interfaces you don't end up using isn't a waste of time, because by doing so you continue to learn more about the problem. The experience of exploring those ideas that you leave behind will make you a better designer for the ideas that you do choose to pursue. In all likelihood your ultimate design will be some combination of the design alternatives that you explored earlier. So, take my security system for an example. There are two ways of interacting with it, the key pad and the key chain. Two different designs that, in this particular instance, integrated just fine. Different alternatives won't always integrate side by side this easily, but the design process as a whole is an iterative process of brainstorming, combining, abandoning, revising and improving your ideas, and that requires you start with several ideas in the first place.

<a id="L3-4-the-design-space"></a>

### The Design Space

When we talk about the problem we're solving here we define the problem space as disabling a security system as we enter a home. We defined our problem as far as possible away from the current interfaces for doing it. The design space on the other hand is the area in which we design our solutions to this problem. The current design space for this problem is wall mounted devices and portable devices like my key chain. But as we design, the space of possible ideas might expand. For example, as we go along we might be interested in voice interfaces or interfaces with our mobile phones or wearable devices. Our goal during the design alternative phase is to explore the possible design space. We don't want to narrow down too early by sticking devices on walls or devices on keychains. We want to brainstorm lots of possible approaches, and grow a large space of possible designs.

<a id="L3-4-individual-brainstorming-1"></a>

### Individual Brainstorming 1

When you first start brainstorming, your goal is to generate a lot of ideas. These ideas can be very short, very high-level, and very general. Your goal is just to generate an expanse of them. They don’t even have to be ideas for interfaces: just any idea for solving the problem. If you look online, you’ll find numerous great guides to how to brainstorm ideas.

One of the most interesting takeaways is that research generally indicates that it’s better to start with individual brainstorming. That’s non-intuitive, though -- so often we hold meetings for brainstorming, but it should start individually. That’s because brainstorming is most effective when it initially just generates a lot of ideas, but groups tend to coalesce around ideas pretty early.

So, start out individually. Generate a lot of ideas. Each idea needs only be a few words or a sentence. Don’t worry right now if they’re good or bad. Write down everything.

Think about how you’d design with different types of interactions, like gestures, voice, or touch. Think about how you’d design for different interfaces, like smart watches, tablets, augmented reality. Think about how you’d design for different audiences, novices and experts, kids and adults. Get silly with it, some of the best ideas start as silly ideas. How would you design this for your dog, for your cat? How would you design this for someone with three arms? With one arm? Go nuts. Your goal is to generate a lot of ideas. These are going to get loaded into your mind and they’ll crop up in interesting ways throughout the rest of the design process. That’s why it’s important to generate a lot: you never know what will come up.

<a id="L3-4-individual-brainstorming-2"></a>

### Individual Brainstorming 2

So, I'm going to demonstrate this for you real quick. I'm going to brainstorm ideas for our problem of allowing exercisers to consume books and take notes. So, I have my paper for brainstorming, so please enjoy this 30 minute video of me sitting here writing at a desk.

[MUSIC] Here's my list of ideas. As you might be able to tell, it gets kind of crazy. It's kind of all over the place. You can kind of trace through my entire reasoning process on here. Also, some of the ideas are somewhat straightforward. I've got voice commands, I've got gestures, I've got voice transcription. I kind of tried to separate it out into feedback methods and also the way the user actually interacts because we could kind of combine those. Some of these are actually pretty crazy. I've got an on skin interface. So I've seen some prototypes for things that would let you actually just press on your skin to do different kinds of interactions. I've also got augmented reality, like Google Glass.

I've got a portable keyboard, like a Twiddler, so notice that this is kind of a mess. That's a good thing. Lists are fine, but chances are, a lot of your ideas are related to each other. Notice also that I never crumpled up my piece of paper, I never threw it away. I crossed one thing out, that's because I wrote the wrong word. Really, at this stage, you don't want to reject any ideas. Your goal is just to kind of free form brainstorm and get all your thoughts out there.

<a id="L3-4-5-tips-individual-brainstorming"></a>

### 5 Tips: Individual Brainstorming

Here are five quick tips for effective individual brain storming. Number one, write down the core problem. Keep this visible. You want to let your mind enter a divergent thinking mode but you also want to remain grounded in the problem. Writing down the problem and keeping it available will help you remain focused while remaining creative. Number two. Constrain yourself. Decide you want at least on idea in a number of different categories. Personally, I try to make sure I have at least three ideas that use nontraditional interaction methods, like touch and voice. You can constrain yourself in strange ways too. Force yourself to think of solutions that are too expensive or not physically possible. The act of thinking in these directions will help you out later. Number three. Aim for 20. Don't stop until you have twenty ideas. These ideas don't have to be very well-formed or complex, they can be simply one sentence descriptions of designs you might pursue. This forces you to think through the problem, rather than getting tunnel vision on an early idea. Number 4. Take a break. You don't need to come up with all of these at once and, in fact, you'll probably find it's easier if you leave and come back. I'm not just talking about a ten minute break either. Stop brainstorming and decide to continue a couple days later but be ready to write down new ideas that come to you. Number 5. Divide and conquer. If you're dealing with a problem like helping kids lead healthier lifestyles, divide it into smaller problems and brainstorm solutions to those. If we're designing audio books for exercises, for example, we might divide it into things like the ability to take and review notes, or the ability to control playback hands-free. Divide it like that and brainstorm solutions to each individual little problem.

<a id="L3-4-challenges-in-group-brainstorming"></a>

### Challenges in Group Brainstorming

Group brain storming presents some significant issues. Thompson in 2008 laid out four behaviors in group brainstorming that can block progress. The first is social loafing. People often don't tend to work as hard in groups as they would individually. It's easy to feel like the responsibility for unproductive brainstorming is shared and deflected. In individual brainstorming, it's clearly on the individual.

The second blocker is conformity, people in groups tend to want to agree. Studies have shown that group brainstorming leads to convergent thinking. The conversation the group has tends to force participants down the same line of thinking, generating fewer and less varied ideas than the individuals acting alone. During brainstorming, though, the goal is diversion thinking, lots of ideas, lots of creativity.

The third blocker is production blocking. In group brainstorming, there are often individuals who dominate the conversation and make it difficult for others to actually be heard. Their ideas can thus command more weight, not because of the strength of the ideas, but because of the volume of the description.

The fourth blocker is performance matching. People tend to converge in terms of passion and performance, which can lead to a loss of momentum over time. That might be able to get people excited if they're around other excited people initially, but more often than not, it saps the energy of those who enter with enthusiasm. In addition to these four challenges, I would add a fifth.

Group brainstorming may also be prone to power dynamics, or biases. No matter how supportive and collaborative a boss might be, there'll likely always exist a tacit pressure to build on her suggestions, which dampens creative brainstorming. There also exists considerable literature stating that other biases based on gender, age, race, complain to these group sessions as well. Now note that this doesn't mean group brainstorming should be avoided altogether. What it means is that we should enter into group brainstorming with strong ideas of how to address these issues, ideally, after a phase of individual brainstorming has already occurred.

<a id="L3-4-rules-for-group-brainstorming"></a>

### Rules for Group Brainstorming

To have an effective group brainstorming session, we need to have some rules to govern the individual's behavior to address those common challenges. In 1957, Osbourne outline four such rules. Number one, Expressiveness. Any idea that comes to mind, share it out loud, no matter how strange.

Number two, nonevaluation. No criticizing ideas, no evaluating the ideas themselves yet.

Number three, quantity. Brainstorming as many as possible. The more you have, the greater your idea of finding a novel idea.

Number four, building. While you shouldn't criticize other's ideas, you should absolutely try to build on them. Then, in 1996, Oxley, Dzindolet and Paulus presented four additional rules.

Number one, stay focused. Keep the goal in mind at all times.

Number two, no explaining ideas. Say the idea and move on. No justifying ideas.

Number three, when you hit a roadblock, revisit the problem. Say it again out loud.

Number four, encourage others. If someone isn't speaking up, encourage them to do so. Note that all eight of these rules prescribe what individuals should do, but they're only effective if every individual does them. So it's good to cover these rules, post them publicly, and call one another on breaking from them.

<a id="L3-4-5-tips-group-brainstorming"></a>

### 5 Tips: Group Brainstorming

The rules given by Osborn, Oxley, Dzindolet and Paulus are about helping individuals understand how they should act in group brainstorming. Here are a few additional tips though that apply less to the individual participants and more to the design of the activity as a whole. Number one, go through every individual idea. Have participants perform individual brainstorming ahead of time and bring ideas to the group brainstorming session. And explicitly make sure to go through each one. That will help avoid converging our own idea too early and make sure everyone is heard. Number two, find the optimal size. Social loafing occurs when there's a lack of individual responsibility. When you have so many people that not everyone would get to talk anyway, it's easy for disengagement to occur. I'd say a group brainstorming session should generally not involve more than five people. If more people need to give perspectives than that, then you can have intermediate groups that then send ideas along to a later group. Number three, set clear rules for communication. Get a 20 second timer and when someone starts talking, start it. Once the timer is up, someone else gets to speak. The goal is to ensure that no one can block others ideas by talking too much, whether intentionally or accidentally. Number four, set clear expectations. Enthusiasm starts to wane when people are unsure how long a session will go or what will mark its end. You might set the session to go a certain amount of time or dictate that a certain number of ideas must get generated. No matter how you do it, make sure that people participating can assess where in the brainstorming session they are. Number five. End with ideas, not decisions. It's tempting to want to leave a brainstorming session with a single idea on which to move forward, but that's not the goal. Your brainstorming session should end with several ideas. Then let them percolate in everyone's mind before coming back and choosing the ideas to pursue later.

<a id="L3-4-fleshing-out-ideas"></a>

### Fleshing Out Ideas

The brainstorming process should lead you to a list of bunch of high level general design alternatives. These are likely just a few words or a sentence each but they described some very general idea of how you might design the interface, to accomplish this task. Your next step is to try to flesh these ideas out into three or four ideas that are worth taking forward to the prototyping stage. Some of the ideas you might be able to dismiss pretty quickly, that's all right. You can't generate good ideas without generating a lot of ideas. Even though you won't end up using all of them. In other places, you might explore an idea a little before dismissing it or you might combine two ideas into a new idea. In the rest of this lesson, we'll give you some thought experiments you can use to evaluate these ideas and decide what to keep, what to combine and what to dismiss.

<a id="L3-4-personas"></a>

### Personas

The first common method we can use to flush out design alternatives is called personas. With personas we create actual characters to represent our users. So let's create a persona for the problem of helping exercisers take notes while reading books. We'll start by giving her a name and a face, and then we'll fill out some details. We want to understand who this persona is. We want to be able to mentally simulate her. We want to be able to say, what would Anika do in this situation? What is she thinking when she's about to go exercise? What kind of things might interrupt her? We might want to put in some more domain specific information as well. Like, why does this person exercise? When do they exercise? What kind of books do they like? How are they feeling when they're exercising? Where do they usually exercise?

We want to create at least three or four of these different personas, and perhaps more depending on how many different stakeholders we have for our problem. The important thing is that these should be pretty different people, representing different elements of our designs, different elements of our task, so we can explore its entire range. We don't want to design just for Anika, but we do want to design for real people. And so we should define personas that represent the range of real people that we care about. That way we can ask our questions like, how would Janet feel about this design alternative? Using this, we can start to extort the space and find the options that has the most appeal.

<a id="L3-4-user-profiles"></a>

### User Profiles

Personas are meant to give us a small number of characters that we can reason about empatheticly. However, it can sometimes also be useful to formulaicly generate a large number of user profiles to explore the full design space.

We can do this by defining a number of different variable about our users and the possibilities within each. So here our few examples, we can ask ourselves, do we care about novice users or expert users or both? Do we care about users that read casually, that read seriously, or both kinds of users? Do we only want to cater to users that are highly motivated to use our app, which can make things a little bit easier on us? Or do we want to assume that it won't take much to stop them from using our app? Can we assume a pretty high-level of technological literacy, or are we trying to cater to more casual users as well? And are we interested in users that are going to use our app all the time, or in users who are going to use our app only occasionally, or both? All of these decisions present some interesting design considerations that we need to keep in mind. For example, for users that are going to use our tool very often, our major consideration is efficiency. We want to make sure they can do what they need to do as quickly as possible. And oftentimes, that might be relying on them to know more about how to use the app. But if we're designing for users that use our app pretty rarely, we need to make sure to keep all the interactions discoverable and visible. That way every time they come back to the app, it's like the first time they came back to it. They don't need to remember anything from the previous time because we don't know how long it's been since the last time they've used it. If we want to design for both, then we have our work cut out for us. We need to either design very efficient interaction methods that nonetheless are discoverable and visible, or we need to design two sets of interaction methods. One way that's very discoverable and visible, and one way that's very efficient. We see this with our example of the hotkeys for copy and paste. If you don't know how to use them, you have a way of finding them. So it caters to either novice users or users who haven't used the program in awhile. But because you can also do it with simple hotkeys, it caters to those users who use it more frequently and makes it more efficient for those who are going to be doing it a lot. In deciding what to design, we need to understand what groups, what profiles we're designing for, and use that to inform our design decisions. Inexperienced designers often make big mistakes here. They either try to design for everybody, which rarely works, or they design with no one in particular in mind. And so, certain areas of program are good for some users, others are good for other types of users. An entire program as a whole is not good for any particular type of user. So it's very important that we understand the range of users that we're designing for, and that we make sure the range is actually something that we feasibly can design for.

<a id="L3-4-timeline"></a>

### Timeline

Building on the idea of a persona we can take that person and stretch her out over time and see what is she thinking, what is she doing at various stages of interacting with our interface or interacting with the task at hand. I've also heard this called journey maps although journey maps usually cover much longer periods of time. They cover the entire expanse of the person's life, why they are interested in something and where they are going from here. Timelines can be more narrowed to the specific time which users are interacting with the task or with the program. So our goal is to take that persona and stretched it out overtime.

So for our example, what sparks Anika to decide to exercise in the first place? That might be really useful information to know.

After she decided to exercise, what did she do next? In theory she doesn't just start right there. She goes exercise somewhere she has kind of setup process.

Then what does she do? In this case, maybe she set ups her audiobooks as she actually pushes play, puts her headphones in, and so on.

And then there's probably a period of actual exercise in our example.

And then at the end, she turns off the audiobook. The usefulness of drawing this as a timeline is it starts to let us ask some pretty interesting questions. What prompts this person to actually engage in the task in the first place? What actions lead up to the task? How are they feeling at every stage of the task? And can we use that? How would each design alternative impact their experience throughout this process? For example, if our persona for Anika was that she really doesn't like to exercise but she knows she really needs to, then we know her mood during this phase might be kind of glum. We need to design our app with the understanding that she might have kind of low motivation to engage in this at all. If our app is a little bit frustrating to use, then it might turn her off of exercising all together. On the other hand, if Anika really likes to exercise, then maybe she's in a very good mood during this phase. And if she likes exercising on its own, maybe she forgets to even set up the audio book at all. So then we need to design our app with that in mind. We need to design it such that there's something built into it that could maybe remind her that when she gets to a certain location, she meant to start her audio book. So stretching this out as a timeline lets us explore not only who the user is, but also what they're thinking and what they're feeling. And how what we design can integrate with a task that they're participating in. Exploring our different design alternatives in this way allows us to start to gauge which designs might have the greatest potential to positively impact the user's experience. And they also let us explore what might be different between different users. Our design might need to be different for Anika who loves to exercise, and Paul who hates exercising. This timeline let's us start to explore those more personal elements.

<a id="L3-4-scenarios-and-storyboards"></a>

### Scenarios and Storyboards

We can create general timelines or routine interactions with our design alternatives, but it's often even more interesting to examine the specific scenarios users will encounter while using our interfaces. Rather than outlining the whole course of interaction, scenarios let us discuss specific kinds of interactions and events that we want to be able to handle. These are sometimes also referred to as storyboards, sequences of diagrams or drawings that outline what happens in a particular scenario. The difference between timelines, and storyboards, and scenarios is that timelines, in my experience at least, tend to be pretty general. They're how a routine interaction with the interface, or a routine interaction with a design alternative goes. Scenarios and storyboards are more specific. They're about a particular person interacting in a particular way, with particular events coming up. So let's build one of these scenarios.

Morgan is out jogging when a fire engine goes by. It's so loud that she misses about 30 seconds of the book. How does she recover from this?

Well we want to go through that question with each of our different design alternatives. For our touch interface, she would need to stop, pull out her phone, turn on the screen, and pause the book. For our voice interface, she would have to wait for the fire engine to finish passing, and then say rewind, because chances are if it's too loud for her to hear her book, it's probably too loud for her phone to hear her voice command. But for a gestural interface she could simply make the gesture that would allow her to pause the book, and then play again when the fire engine is finished passing. Ideally we'd like to outline several such scenarios and explore them for various personas and design alternatives. Of course, now we're reaching three degrees of freedom. So it's not crucial that we explore every possible combination of persona, scenario, and design alternative. This is a more fluid process of exploring what ideas have potential and what ideas are worth exploring further. We might find there are certain combinations of scenarios and personas that we really care about, that completely rule out certain design alternatives. If we really care about allowing her to exercise in a loud area, that goes ahead and tells us that that voice interface might not be the direction we want to go in. Or for another example, if our earlier need finding exercises revealed a significant number of exercisers carry weights or other things in their hands, then gestural interfaces start to look a lot less promising. Now as video technology has gotten more and more ubiquitous, story boards have also taken on a different form in a lot of prototypes that I've seen. There's been an emergence of what is called, video prototyping. Which is basically doing a video mockup of what someone would actually look like interacting with a certain interface, to show to people so that they can see whether or not that would actually be something that would help them in their everyday life. So storyboards, taken to an extreme, could actually be a video mockup of what it would be like to use the finished product.

<a id="L3-4-user-modeling"></a>

### User Modeling

In our unit on principles, we talk about task analysis, including things like cognitive task analysis or human information processor models. Performing those analysis as part of our need finding also gives us a nice tool for exploring our design alternatives. Using this, we can start to look at how exactly the goals, operators, methods, and selection rules of the Gomes model map up to the ideas of our design alternatives. How does the user achieve each of their goals in each interface? How relatively easy are the goals to achieve between the different design alternatives? With the results of our cognitive task analysis, we can start to ask some deeper questions about what the user is keeping in mind as well. Given what we know about things competing for our user's attention, what are the likelihoods that each interface will work? In some ways, this is a similar process to using personas we outlined earlier, but with a subtle difference. Personas are personal and meant to give us an empathetic view of the user experience. User models are more objective and meant to give us a measurable and comparable view of the user experience. So ideally, the result of this kind of analysis is we would be able to say that the different alternatives have these different phases and these different phases have different efficiencies or different speeds associated with them. So, we could start to say exactly how efficient one design is compared to another.

<a id="L3-4-quiz-exercise-design-alternatives"></a>

### Quiz: Exercise: Design Alternatives

In this lesson we've covered several different ways of developing design alternatives. Each method has its advantages and disadvantages. So, let's start rap the lesson up by exploring this with an exercise. Here are the methods that we've covered and here are some other potential advantages. For each row, mark which of the different methods possesses that advantage. Note that these might be somewhat relative, so your answer might differ from ours and that's perfectly fine.

So personally here's my answer. For me scenarios are really the only ones that include the entire task context. You can make the case that personas and timelines do as well, but I tend to think that these are a little bit too separated from the task to really include the context. Personas and user profiles, on the other hand, do include the users context. They include plenty of information about who the user is, why they're doing this task, and what their motivations are. You could make the argument as well, that scenarios and timelines include the user's context. Because the way we describe them, they're instances of the personas being stretched out over a scenario or over time. User profile probably do the cleanest job of delineating the target audience. With our personas we have kind of a fuzzy idea of who are different users are. But our user profiles really formally articulate the space of your users in which we're interested. As far as general workflows that's what user modeling is really good at. It really outlines the phases or steps or operators that users use in a general sense. You could say the same thing about timelines to a certain extent although timelines are more focused on what the user is thinking and feeling and less on their actual workflow with regard to the task. As far as capturing activity over time, scenarios, timelines, and user modeling all have an element of time in what they analyze. And possibly one of the bigger benefits of using scenarios is they allow us to capture potential edge cases more easily. Timelines, user models, user profiles and personas are all about the general user or the general routine interaction with the task. But scenarios let us pose interesting and novel situations so that we can kind of mentally simulate how our different design alternatives will work with that scenario. For example, we wouldn't say that a fire engine going by Morgan, which is listening to an audiobook, is a routine thing, so it probably wouldn't come up in our timeline or in our user modeling. But we can develop a scenario that explores how is she going to deal with that particular event. And while it might seem a little silly to focus so much on edge cases, as we do more and more design, we start to discover that there are a lot of edge cases. They're all different. But a lot of our time is spent dealing with those unique circumstances that fall pretty far outside the routine interaction with the program.

<a id="L3-4-exploring-ideas"></a>

### Exploring Ideas

So let's apply these techniques to some of the ideas that I came up with earlier. The first thing I might do is go ahead and rule out any of the ideas that are just technologically unfeasible. Coming up with those wasn't a waste of time because they're part of a nice broad free flow brainstorming process. But skin based interfaces and augmented reality, probably are not on the table for the immediate future. I might also rule out the options that are unfeasible for some more practical reasons. We might a small team of developers, for example. So, a dedicated wearable device isn't really our expertise. Now the one I might do next is create some timelines, covering a sequence of events in exercising to use to explore these alternatives further. I might notice that the users I observed and talked with, valued efficiency in getting started. They don't want to have to walk through a complex set up process every time they start to exercise. I might also use my user persona's to explore the cognitive load of the users in these different alternatives. They have a lot going on, between monitoring their exercise progress, observing their environment, and listening to the book. So, I'm going to want to keep cognitive load very low. Now granted, we always want to keep cognitive load pretty low, but in this case, the competing tasks are significant enough, that I want to sacrifice features for simplicity, if it keeps that cognitive load pretty manageable. Now based on these timelines and these personas, I would probably end up here with three design alternatives that I want to explore. One is a traditional touch interface, a smartphone app. Then unfortunately it means the user is going to have to pull out their phone whenever they want to take a note. But if I can design it well enough that might not be an issue. I also know that approach gets me a lot of flexibility so it's good to at least explore it. A second approach is gestural interfaces. I know that people aren't usually holding their device while exercising. So it would be great if they had someway of interacting without pulling out their phone. Gestures might let us do that. Now in our gesture recognition is in its infancy, but we might be able delivered smart watched technology or something like a Fitbit to support interaction via gestures. A third approach is a voice interface, I know people generally aren't communicating verbally while exercising, so why not a voice interface? That can even double as the note taking interface. So now that I have three design alternatives that I'm interested in exploring, I would move on to the prototyping stage which is building some version of these that I can test with real users.

<a id="L3-4-exploring-hci-design-alternatives"></a>

### Exploring HCI: Design Alternatives

Design alternatives are where you explore different ways to facilitate the user's task. If you've already chosen to focus on a certain area of technology like wearable devices and just general interaction. Then in some ways, you've put the cart before the horse. You've chosen your design before exploring the problem. As a learning experience though, that's perfectly fine. It's fine to say, I want to explore augmented reality and I'm going to find a task that lets me do that. You're still exploring wether or not augmented reality is the right solution for that task. You're just altering the task, if not instead of altering the design if not. For other domains, you might need to make sure to create persona's for different stakeholders in healthcare, for instance. We would want to make sure any interface you design takes into consideration nurses, doctors, patients, managers family members and more. So you'd want to create personas for all those different types of people, as well and make sure to explore scenarios that affect each stakeholder.

<a id="L3-4-conclusion-to-design-alternatives"></a>

### Conclusion to Design Alternatives

The goal of the design alternative stage of the design life cycle, is to generate lots of ideas, and then synthesize those ideas into a handful worth exploring further.

So we started with some heuristics for generating lots and lots of ideas, through both individual and group brainstorming.

Then we proposed some methods for exploring those ideas, and deciding which one to pursue. Now these were all thought experiments. We haven't actually gotten to the point of designing any of these interfaces yet. That will be the next stage. At the end of the design alternative stage, we want to select a handful of designs that are worth carrying forward and prototyping, to then give the users for actual feedback.

— End of Lesson 3.4 — [Back to summary](#A-L3-4) · [Contents](#toc)

---

<a id="L3-5"></a>

## 3.5 Prototyping

**CS6750 · Human–Computer Interaction** — Lecture notes (David Joyner, Summer 2017 lecture book, pp. 542–570)

*Full lecture content, restructured for revision. `»` marks a speaker change in video-transcript dialogue.*

[Back to summary of this lesson](#A-L3-5) · [Table of contents](#toc) · [Keyword index](#partC)

**Sections in this lesson:**

- [Introduction to Prototyping](#L3-5-introduction-to-prototyping)
- [Basics of Prototyping](#L3-5-basics-of-prototyping)
- [Tradeoffs of Prototyping](#L3-5-tradeoffs-of-prototyping)
- [5 Tips: Prototyping](#L3-5-5-tips-prototyping)
- [Verbal Prototypes](#L3-5-verbal-prototypes)
- [Paper Prototyping](#L3-5-paper-prototyping)
- [Wizard of Oz](#L3-5-wizard-of-oz)
- [Wireframing](#L3-5-wireframing)
- [Physical Prototypes](#L3-5-physical-prototypes)
- [Quiz: Exercise: Prototyping Pros and Cons](#L3-5-quiz-exercise-prototyping-pros-and-cons)
- [Design Life Cycle Revisited](#L3-5-design-life-cycle-revisited)
- [Multi-Level Prototyping](#L3-5-multi-level-prototyping)
- [Exploring HCI: Prototyping](#L3-5-exploring-hci-prototyping)
- [Conclusion to Prototyping](#L3-5-conclusion-to-prototyping)

<a id="L3-5-introduction-to-prototyping"></a>

### Introduction to Prototyping

[MUSIC] So we've talked to our users. We've gathered some understanding of what they need. We've created some ideas for how we might address their need and we've mentally simulated those different alternatives.

Now it's time to start actually making things we can put in front of users. This is the prototyping stage. Like brainstorming design alternatives, this involves looking at the different ideas available to us and developing them a bit. But the major distinction is that in prototyping, we want to actually build things we can put in front of users. But that doesn't mean building the entire interface before we ever even have a user look at it. We want to get user feedback as quickly and rapidly as possible. And build up more sophisticated prototypes over time as we go through the design life cycle.

So we'll start with low fidelity prototypes, things that can be assembled and revised very quickly for rapid feedback from users.

Then we'll work our way towards higher fidelity prototypes, like wire frames or working versions of our interface.

<a id="L3-5-basics-of-prototyping"></a>

### Basics of Prototyping

To discuss prototyping there are a variety of different terms and concepts we need to understand. For the most part, these will apply to where in the prototyping timeline those concepts are used. In the early prototyping, we're doing a very rapid revision on preliminary ideas. This happens on our first few iterations through the design lifecycle. In late prototyping, we're putting the finishing touches on the final design, or revising a design that's already live. This happens when we've already been through several iterations of our design lifecycle. At the various phases, we'll generally use different types of prototypes in evaluations. Now, note that everything I'm about to say is pretty general, there will be lots of exceptions.

The first concept is representation, what is the prototype? Early on, we might be fine with just some textural descriptions or some simple visuals that we've written up on a piece of paper. Later on though, we'll want to make things more visual and maybe even more interactive. We only want to put the work into developing the more complex type of prototypes once we vetted the ideas with prototypes that are easier to build. So in a lot of ways, this is a spectrum of how easy prototypes are to build over time. A verbal prototype is literally just a description, and I can change my description on the fly. A paper prototype is drawn on paper, and similarly, I could ball up the paper, throw it away, and draw a new version pretty quickly. But things like actual functional prototypes that really work, those take a good bit of time. And so we only want to do those once we've already vetted that the ideas that we're going to build actually have some value. You don't want to sink lots of months and lots of engineering resources into building something that actually works. Only to find out there's some feedback you could have gotten just based on a drawing on a piece of paper that would have told you that your idea wasn't a very good one.

This brings us to our second concept, which is fidelity. Fidelity refers to the completeness or the maturity of the prototype. A low-fidelity prototype would be something like paper or simple drawings, very easy to change. A high-fidelity prototype would be something like a wireframe or an actual functional working interface, something that was harder to put together. We want to move from easily changeable low-fidelity prototypes to explore our ideas, to higher-fidelity prototypes to really test them out. Note that fidelity and representation are pretty closely related, low-fidelity is really about a prototype that's pretty far from being complete. And the same thing is true for some of our early methods of prototyping. They describe different ideas, but they very heavily correlate what kinds of representations you're going to use for different levels of fidelity.

Now these different kinds of prototypes also lend themselves to different kinds of evaluation structures. Low fidelity prototypes can fine for evaluating the relative function of an interface, whether or not it can do what's it's designed to do. If a user looks at the interface can they figure out what they're supposed to press? You can prototype that was just a drawing on a piece of paper, as opposed to a real functional prototype. Things like wireframes can be useful in evaluating the relative readability of the interface as well. However, to evaluate actual performance, like how long certain tasks take, or what design leads to more purchases. We generally need a higher fidelity prototype, through more iterations of the design lifecycle. So early on, we're really just evaluating whether or not our prototype even has the potential to do what we want it to do. Can a user physically use it? Can they identify what button to press and when? For that we need additional detail like font size and real screen layout. We need a real prototype that looks the way the final interface will look, even if it doesn't work quite yet. And then, to evaluate performance we really need a prototype that's working, or close to working, to evaluate certain tasks.

And then the final concept we need to understand, is the scope of the interface. Is it a horizontal prototype or a vertical prototype? Horizontal prototypes cover the design as a whole, but in a more shallow way. Vertical prototypes take a small portion of the interaction and prototype it in great detail. So for example, if we were designing Facebook, we might have a vertical prototype specifically for the status-posting screen and a horizontal prototype for the site in general. Now, in my experience, we usually start with horizontal prototypes earlier on, and move toward the deeper vertical prototype later. But in reality, you'll likely move back and forth among these more frequently throughout you iterations through the design lifecycle.

So, these are four the main concepts behind prototyping. There are other questions we might ask ourselves as well. Like whether we're prototyping iterative or revolutionary changes, and the extent to which the prototype needs to be executable. But in many ways, those fall under these previous concepts.

<a id="L3-5-tradeoffs-of-prototyping"></a>

### Tradeoffs of Prototyping

Prototyping is largely about the tradeoffs we have to make. Low fidelity prototypes like drawings are easy to create and modify, but they aren't as effective for detailed comprehensive evaluations. High fidelity prototypes, like actual working interfaces, can be used for detailed feedback and evaluation, but they're difficult to actually put together.

So, our goal is to maximize these trade-offs. We want to start with easier, low fidelity prototypes to get initial ideas, to evaluate big designs and big plans, and make sure we're on the right track.

Then as we go along, we can move to the higher fidelity prototypes that take more time assemble because we have initial evidence that our designs are actually sound. It's really important here also, to note that our prototypes are prototypes. They aren't complete interfaces. We've discussed the past that designers often have a tendency to jump straight to designing rather than getting to know their users. That's a big risk here as well because we're designing.

But we're designing specifically to get more feedback. So don't become a runaway train of designing. Design deliberately and get feedback often.

<a id="L3-5-5-tips-prototyping"></a>

### 5 Tips: Prototyping

Here are five quick tips for effective prototyping. Number one keep prototypes easy to change, your goal here is to enable to rapid revision and improvement. It's easy to make quick changes to something on paper but it's harder to make it a code or physical prototypes. Number two, make it clear that it's a prototype. If you make a prototype look too good users may focus on superficial elements like colors or font. By letting your prototype look like a prototype you can help them focus on what you're ready to test. Number three, be creative. Your goal is to get feedback. Do whatever it takes to get feedback. Don't let the type of prototype you're designing constrain the type of feedback you can get. If you find your current prototypes don't give you the right kind of feedback, find ones that do. Number 4, evaluate risks. One of the biggest goals of prototyping is to minimize the time spent pursuing bad designs by getting feedback on them early. How much would you lose if you found that users hate the parts of your design that they haven't seen yet? Whenever that answer gets to be longer than a couple hours, try to get feedback to make sure you're not wasting time. Number five, [SOUND] prototype for feedback. The goal of a prototype is to get feedback. You could spend a lot of time focusing on details like font selection and color choice, I know I do, but that's probably not the feedback you need when you're exploring your big alternatives. Prototype for the kind of feedback you want to get.

<a id="L3-5-verbal-prototypes"></a>

### Verbal Prototypes

At the very simplest, we have verbal prototypes. That means we're literally just describing the design we have in mind to our user. That's probably the lowest fidelity prototype possible. It's literally just telling the user the same thing we tell our co-designers. So it's extremely easy to do, although it can be hard to do effectively. Social desirability bias is big here because it's difficult to describe our idea in a way that allows the participant to feel comfortable disagreeing with us. So we need to make sure to ask for specific and critical feedback. At the same time though, how do we really know that the user understands the desire we're describing? We're working towards becoming experts in the areas in which we're designing, and we don't want to fall victim to expert blind spot by assuming our explanation makes sense to a novice. For that reason, analogies can be powerful tools for explaining prototypes. Describe your interface in terms of other tools the user might already know about. So for example, imagine I was pitching the idea of InstaCart, a grocery delivery company. I might've described it like, it's like Uber for groceries. Uber is a service kind of like taxis, and InstaCart is kind of like a taxi for groceries. That way of describing it in terms of an analogy to another interface can be a powerful way of helping your participant understand your idea more quickly.

<a id="L3-5-paper-prototyping"></a>

### Paper Prototyping

One step above just ‘describing our ideas’ to our user in a verbal prototype would be drawing them out. This is what we call a paper prototype. We could do this for anything from designing an on-screen interface to designing the placement of controls in a vehicle. Let’s go back to our example of designing a way for exercisers to consume and take notes on audiobooks. Let’s imagine one of my design alternatives was just for a very easy-to-use app so that the hassle of pulling out the phone isn’t too distracting. I might start this process simply by drawing up a prototype on paper.

Now I have a paper prototype. Now, I can talk to my user and ask her thoughts on it. We’ll talk more about the kinds of thoughts I’ll ask for when we discuss evaluation. But generally, I can say: hey Morgan, what about this design?

» Oh. Looks pretty good. It's straightforward. There's play. There's fast forward. You know I would like a way to see where I am in the book, though.

» That makes sense.

And notice that she didn’t comment on color or font or anything like that not because I said "hey, I'm ignoring font right now" but because it’s pretty obvious that I'm not caring about font right now. The nature of the paper prototype is it tells the user what kind of feedback we're looking for. We're looking for pretty basic layout information. Now because this is on paper, I can actually immediately revise my prototype and incorporate things that she suggested.

Now, I have a revision based on her feedback, and I can ask: hey, how's that?

» Looks great, David.

Now paper prototyping isn’t only useful for testing out just single interface designs. You can also do some interaction with it. Watch.

So here I have four screens prototyped. And so, when I give this to Morgan, I can say things like: imagine you're viewing this screen and you want to take a note to attach to your current place in the book. What would you do?

» Probably press the view the notes button.

Makes sense. After you press that what you're going to see is this screen for note-taking. What would you do then.

» Uh... Well, if I want to take a note then I would press the record button.

Yeah! Exactly. And then it would start recording you and it would transcribe what you say and at the end you would press stop to continue.

Interestingly, just doing this I've already noticed that there's really no reason to make her jump to a separate note-taking screen when she want to take a note while listening. It should actually just be a note-taking button here on the main screen.

So just like this I get to walk through some of the interaction with the app on paper and get some ideas like that on how to improve it. This is also called card-based prototyping. The idea is each screen is on a different card and I can quickly sub those cards in and out so we can simulate what it would be like to use the real application. So, that way, I can prototype a decent amount of the interface’s interaction with pretty low prototyping effort.

» Neat.

<a id="L3-5-wizard-of-oz"></a>

### Wizard of Oz

Paper prototyping is great when we're designing flat interfaces for screens. But what if you're designing a voice interface or a gesture interface? How do you prototype that? One way is called Wizard of Oz prototyping. Wizard of Oz prototyping is named as a reference to the famous scene from the classic movie of the same name.

» Whoa, pay no attention to that man behind the curtain.

The idea here is, that we, behind the curtain, do the things that the interface would do once it's actually implemented. That way we can test out the interactions that we plan to design and see how well they'll work.

So I have Morgan, and we're going to do a Wizard of Oz prototype for an interface that will allow exercisers to consume and take notes on audiobooks. So, I'll start by briefly telling her how the interface would work. Also, this interface is run by voice command. I'll simulate it on my phone. Also you'll say, play to play the book, pause to pause the book. You'll say, note to enter a note taking view where it will transcribe what you say. And bookmark to just drop a bookmark wherever you are but without pausing. So, whenever you're ready...

» Let's do it.

»» Our wealth consists of desirable things,

» Pause.

»» that is things

» Play.

»» To satisfy human wants directly or indirectly.

»» Book mark.

»» But not all desirable things are reckoned as well.

» Note. This book is so good.

I just realized actually I need a way for you stop the note when you're done. So say close note when you're done taking your note.

» Close note.

All right, you can stop. [LAUGH]. Now based on this prototype, I can also ask for some feedback. So Morgan do you think should automatically start playing again when you stop that bookmark? Or should it, what should it do?

» Well okay, so I think I'd actually like it to start playing five seconds back. Because I imagine saying, note, is going to step over some of the content.

Yeah, that makes sense, and we can go through this and quickly test out different ideas for how the interaction might work. In practice, Wizard of Oz prototypes can actually get very complex. You can have entire programs that work by having a person supply the requested input at the right time. But as a concept a Wizard of Oz prototype is a prototype where the user can interact authentically with the system. While a human supplies the functionality that hasn't yet been implemented.

<a id="L3-5-wireframing"></a>

### Wireframing

Paper prototyping involved drawing things simply on paper and it can be really for experimenting with overall layouts, especially because it tends to be a lot easier to revise and tweak those pretty naturally. After some feedback though, you'll likely want to start formalizing your designs a little bit more. One way of doing this would be called wire framing. In wire framing we use some more detailed tools to mock up what an interface might look like. For example, my paper prototype from earlier might become a wire frame like this. This lets us experiment with some additional details like font size, colors, and the challenges of screen real-estate. Now there are lots of tools out there for wire framing that come equipped with built-in common widgets and layouts, but you can also do some rudimentary wireframing in something as simple as PowerPoint.

Google drawings can be used the same way as well. So you don't need to get super fancy, although if you do a lot of wire framing you'll probably want to find a more streamlined tool.

Some of the more popular paid products include Balsamiq...

...and Axure. These are both targeted at professionals working in user interface or user experience design. Especially on teams and collaborating with a lot of people.

If you're familiar with the suites of tools from either Microsoft or Adobe, then Visio...

...or InDesign might also be great options for you to use because you're already somewhat familiar with those interfaces.

But you don't actually have to buy a tool to do good wireframing. There exists some free to use tools out there as well, like the Pencil Project...

...and Frame Box. Those are great to use, especially if you're just getting started. And of course, these are just the popular ones that I know about right now. There are almost certainly more out there that I'm not familiar with and more will surely come available, so check with your classmates or colleagues to see what they would recommend. I'm personally really excited to see what kind of prototyping options emerge for areas like virtual reality and augmented reality, where you can't really prototype on a 2D canvas like these.

<a id="L3-5-physical-prototypes"></a>

### Physical Prototypes

Wire framing is great for prototyping on-screen interfaces, but again, what if you're working on something more physical or three-dimensional? In that case, you might want to construct a physical prototype. But let's be clear, it doesn't have to actually work. That's where a lot of designers get tripped up. They think to get good feedback on a design they have to have a working version, but you don't. There are lots of elements you can test without actually implementing anything. So let's go back to our example of designing a way for exercisers to take notes on audio books.

One of my alternatives might be a Bluetooth device that synchronizes with the phone with buttons for different interactions. The individual will hold this while exercising and interact by pressing different buttons for play or pause or take a note. I've prototyped this just by taking my car's key fob, and we could just say that, pretend this button does this and this button does this. It's probably not the exact shape that I want, but it's pretty close. It's probably about the same size. And I can test the general idea of pressing buttons while exercising with this. And I can actually do a lot of testing with this. I can tell Morgan how it works and watch carefully to see if the buttons she presses are the right ones to evaluate the intuitiveness of the interface. Or I could just ask her to go running while holding it and give me feedback on whether or not holding something physical like this in her hand throws off her routine at all. I can do a lot of prototyping without a working version.

<a id="L3-5-quiz-exercise-prototyping-pros-and-cons"></a>

### Quiz: Exercise: Prototyping Pros and Cons

In this lesson we've covered various different methods for prototyping. Each method has its advantages and disadvantages. So let's start to wrap up the lesson by exploring this with another exercise. Here are the methods that we've covered and here are some of the potential advantages. For each row, mark the column to which that advantage applies. Note that as always, these are somewhat relative, so your answer might differ from ours.

So here are my answers. First when we're talking about things that are revisable during interaction, we're talking about things that I as the experimenter can get feedback from my user and immediately change my prototype. So if they say that that button label doesn't really makes sense, I can cross out that button label and immediately change it. That makes sense for prototypes that are very low fidelity. Verbal prototypes, I can immediately say okay, then let's make it the way you just described. Paper prototypes or card prototypes, I could quickly erase or cross out something on my prototype and change it. Wizard of Oz is similar. Since I'm running what's going on behind the scenes, I can just change the way I'm running it. Those four prototypes, because they're more low fidelity, also disguises superficial details. No one is going to look at a prototype that I drew by hand and say they don't like the font. No one is going to to listen to me run a Wizard of Oz prototype for a voice interface and say, I don't like the voice that you're using. These help us focus on the overall patterns of interaction and disguise some of the superficial elements that users would often have a tendency to get distracted by. However, as we prototype, we need to move from designing interfaces to designing interactions. Verbal prototypes and paper prototypes don't really cover interactions, they cover showing something and asking the user what they think, but they don't really go further than that. Card prototypes, Wizard of Oz prototypes, to a certain extent wireframing and to a certain extent physical prototypes all let us actually simulate the user interaction. With a card prototype, we're actually saying if you did that, then you would see this, so they can walk through the pattern of interaction. Wizard of Oz, we can simply call out or describe or simulate, this is what would happen if you do what you just described. Now, wifeframing you could do more like a paper prototype, where it's just a simple wire frame, but more generally, we use wire frames when we're ready to actually show different interfaces and the movement between them. Similarly with physical prototypes, the main reason why we would do a physical prototype is to hand a user, and say, pretend you're jogging, or pretend you're working in your office. How would this interact with what you're actually doing? We're simulating the way they would physically use it. Now among all of these, the wires frames are really the ones that are most easily distributable to remote users. You can make an argument that we can send scans for a paper prototypes but generally, a paper prototype isn't just about what's on paper. It's also about the conversations and descriptions that we're having around it and asking users what they think about certain elements. Whereas a wire frame is more about a general impression that users get. You can make the argument that paper prototypes can be sent easily, as well. But for me, I would only share wire frames with remote users. Now prototyping look and feel is really just the inverse of disguise and superficial details. Look and feel is really about those superficial elements that have a significant user impact, but are more easily modifiable within an overall pattern of functional interaction. So just as the earlier low fidelity prototypes support disguising details, the later ones support prototyping look and feel. As computers become more ubiquitous, and users are moving around while interacting with interfaces more and more, allowing mobility is really valuable. Wizard of Oz, since we're just calling things out to the user, let them move around, and same with physical prototypes. We can actually hand them to a user and have them physically interact, the way they would with the actual interface

<a id="L3-5-design-life-cycle-revisited"></a>

### Design Life Cycle Revisited

At this point, there's a risk of a major misconception that we should cut off right now. We started with need finding, then develop some design alternatives, and now we're prototyping. We've talked about how prototyping follows a timeline to low fidelity to high fidelity prototypes, from early to late prototyping. We might think that we move on to evaluation when we're done prototyping. That's not the way the design life cycle works though. We go through this cycle several times for a single design and a single prototype corresponds to a single iteration through the cycle. So we did some initial needfinding, we brainstormed some alternatives, and we prototyped those alternatives on paper. We don't jump straight from doing them on paper to doing them via wire framing or doing a functional prototype. We take those prototypes and we use them for evaluation. We evaluate those paper prototypes with real people. The results of that evaluation tell us if we need to go back and understand the task even better. Those results help us reflect on our alternatives as a whole, maybe come up with some new ones. Then, equipped with the results of that evaluation, that additional needfinding, and that additional brainstorming, we return to the prototyping phase. If our prototype seemed to be pretty successful and pretty sound, then maybe it's time to raise the fidelity of it. Maybe we take it from a paper prototype and actually do some wire frames, or do a car prototype around the actual interaction. If it wasn't very successful though, when we reach back here, we're going to do a different paper prototype, or a different low fidelity prototype, and then go to evaluation again. Each time we develop a new prototype we go through the same cycle again. Now that might sound extremely slow and deliberate but we also go through this on a very different time scales too. So for example, after we've gone through needfinding and designing alternative brainstorming, we can develop a paper prototype. We give it to a user and get their evaluation. They say that they don't like it. We ask them why, we ask them to describe what about their task isn't supported by that interface. That's in some ways another needfinding stage. Then we brainstorm real quick how we could resolve that. Maybe we just do that while we're sitting with that user and think it didn't support this element of what they described, but I could add that pretty quickly just by making this button or this function more visible. Now we very quickly have a new prototyping just by sketching out that addition to that paper prototype and now we can do it again. This cycle could take one minute. We could take one prototype, put it in front of a user, get their evaluation, figure out what they liked and didn't like, brainstorm a way to fix that, and then immediately revise it and try it again. We can go through this very, very quickly. We could also go through this very slowly, we could have prototypes that take months to develop. And generally that's why we only want to do that after we've gone through the cycle a few times. Because if we're going to take months to develop a prototype, we want to make sure we're probably going to get some pretty good evaluations on it. And we can make sure of that by prototyping the elements in lower fidelity first.

<a id="L3-5-multi-level-prototyping"></a>

### Multi-Level Prototyping

There's one other misconception that I've seen in some designers I've worked with that I feel is also worth explicitly acknowledging. All your prototypes don't have to be at the same level, at the same time. Take Facebook for example. Facebook is a complete app already implemented.

Imagine that Facebook wanted to redesign their status update box, which they've done pretty recently and have probably done since I recorded this. Just because the interface is complete in other ways doesn't mean that all future prototyping efforts need to be similarly high fidelity. They don't need to implement an entire new status composition screen just to prototype it. They can prototype it in lower fidelity with sketches, or wire frames, put that in front of users, get their feedback, before ever actually implementing it into a functional prototype or a working part of the website. This applies particularly strongly to the design of apps or programs with multiple functions.

So take something like the LinkedIn app. It has a number of different functions like editing your own profile, or connecting with others, or browsing your news feed. Each of these individual screens has its own tasks and interactions. And moving amongst them, is itself a task or a type of interaction. Trying to design all the screens and the transitions among them all at the same time is likely far too much. So we could take the bottom-up approach, where we would design the individual screens first, and then design the app experience as a whole. Or we might take the top-down approach and design the overall experience of moving between these different screens, and then design the contents of the individual screens. The point of this is that at any time, protoyping can and should exist at multiple levels of fidelity.

<a id="L3-5-exploring-hci-prototyping"></a>

### Exploring HCI: Prototyping

If you're working in an application area that relies on traditional screens and input methods, your prototyping process might be pretty straight forward. You'll go from paper prototypes, to wireframes, to exploring iteratively more complete versions of the final interface. For a lot of emerging domains though, you'll have to get somewhat creative with your prototyping. For things like to stroll or voice interaction, you can likely use Wizard of Oz prototyping by having a human interpret the actions or commands that will ultimately be interpreted by the computer. For augmented reality or wearable devices though, you might have to get even more creative. So, take a second and brainstorm how you might go about prototyping in your chosen field. Remember, your goal is to get feedback on your ideas with the user early. What can you create that will get you to that feedback?

<a id="L3-5-conclusion-to-prototyping"></a>

### Conclusion to Prototyping

In this lesson, we've talked about several methods for prototyping. Our goal is to employ a lot of methods to get feedback rapidly, and iterate quickly on our designs. Through that process, we can work our way towards creating our ultimate interface. The main goal of this prototyping process has to been to create designs we can evaluate with real users. We're obviously not going to deploy a hand draw interface to real customers, its value is in its ability to get us feedback. That's what the entire design life cycle has been leading towards, evaluation, evaluation our ideas, evaluating our prototypes, evaluation our designs. That user evaluation is the key to user centered design. Focusing on user evaluation insures that our focus is always on the user's needs and experiences.

So now that we've researched the user's needs, brainstormed some design alternatives, and created some sharable prototypes, let's move on to actual evaluation.

— End of Lesson 3.5 — [Back to summary](#A-L3-5) · [Contents](#toc)

---

<a id="partC"></a>

# Part C — Keyword Index

Alphabetical. Each entry names the lesson and the exact section of the full text where the term is explained, with a link.


### 1

- **1-to-5 scale (quantitative but not continuous)** — [Lesson 3.1 › Quiz: Exercise: Quantitative vs Qualitative](#L3-1-quiz-exercise-quantitative-vs-qualitative)
- **15 design principles (Joyner's merged list)** — [Lesson 2.5 › The Sets](#L2-5-the-sets) — sources table; see Part A summary

### 5

- **5 Tips: Avoiding bias in needfinding** — [Lesson 3.3 › 5 Tips: Avoiding Bias in Needfinding](#L3-3-5-tips-avoiding-bias-in-needfinding) — confirmation; observer; social desirability; voluntary response; recall
- **5 Tips: Doing well in CS6750** — [Lesson 1.2 › 5 Tips Doing Well in CS6750](#L1-2-5-tips-doing-well-in-cs6750) — look early; start early; participate; pick an area; leave behind what you know
- **5 Tips: Group brainstorming** — [Lesson 3.4 › 5 Tips: Group Brainstorming](#L3-4-5-tips-group-brainstorming) — every idea; ≤5 people; 20-second timer; expectations; ideas not decisions
- **5 Tips: Gulfs of evaluation** — [Lesson 2.2 › 5 Tips: Gulfs of Evaluation](#L2-2-5-tips-gulfs-of-evaluation) — constantly; immediately; match; vary; direct manipulation
- **5 Tips: Gulfs of execution** — [Lesson 2.2 › 5 Tips: Gulfs of Execution](#L2-2-5-tips-gulfs-of-execution) — discoverable; mess around; consistent; know your user; feed forward
- **5 Tips: Identifying a task** — [Lesson 2.1 › 5 Tips: Identifying a Task](#L2-1-5-tips-identifying-a-task) — watch; talk; start small; abstract up; you are not your user
- **5 Tips: Individual brainstorming** — [Lesson 3.4 › 5 Tips: Individual Brainstorming](#L3-4-5-tips-individual-brainstorming) — core problem; constrain; aim for 20; break; divide and conquer
- **5 Tips: Interviews** — [Lesson 3.3 › 5 Tips: Interviews](#L3-3-5-tips-interviews) — six W's; bias; listen; organize; practice
- **5 Tips: Invisible interfaces** — [Lesson 2.3 › 5 Tips: Invisible Interfaces](#L2-3-5-tips-invisible-interfaces) — affordances; know; differentiate; interface teaches; talk to user
- **5 Tips: Naturalistic observation** — [Lesson 3.3 › 5 Tips: Naturalistic Observation](#L3-3-5-tips-naturalistic-observation) — notes; specific→abstract; spread sessions; partner; look for questions
- **5 Tips: Prototyping** — [Lesson 3.5 › 5 Tips: Prototyping](#L3-5-5-tips-prototyping) — easy to change; clearly a prototype; creative; evaluate risks; prototype for feedback
- **5 Tips: Reducing cognitive load** — [Lesson 2.4 › 5 Tips: Reducing Cognitive Load](#L2-4-5-tips-reducing-cognitive-load) — multiple modalities; complement; pace; essential content; offload
- **5 Tips: Surveys** — [Lesson 3.3 › 5 Tips: Surveys](#L3-3-5-tips-surveys) — less is more; bias; inventory; test; iterate

### A

- **A/B experiments in industry** — [Lesson 3.2 › Research Ethics and Industry](#L3-2-research-ethics-and-industry)
- **Abstract up (keep asking why)** — [Lesson 2.1 › 5 Tips: Identifying a Task](#L2-1-5-tips-identifying-a-task)
- **Affordance vs mapping (colour meter; light switches vs stove dials)** — [Lesson 2.5 › Mapping](#L2-5-mapping) — switches challenge next section
- **Affordances** — [Lesson 2.5 › Affordances](#L2-5-affordances) — Norman's definition; door handle; hover/pressed button
- **Aim for 20 ideas** — [Lesson 3.4 › 5 Tips: Individual Brainstorming](#L3-4-5-tips-individual-brainstorming)
- **Amanda (video producer) / Ben (teleprompter)** — [Lesson 1.1 › Computers](#L1-1-computers) — also 1.3 CSCW; 2.2 reflections; 2.4 modalities
- **Apple 1992 'piles' study** — [Lesson 1.1 › HCI vs Psychology](#L1-1-hci-vs-psychology) — psychologists at Apple; piles of related material
- **Apprenticeship and ethnography (Udacity video editors)** — [Lesson 3.3 › Apprenticeship and Ethnography](#L3-3-apprenticeship-and-ethnography)
- **Arab Spring (Twitter) / Facebook civil-union statuses** — [Lesson 2.1 › User Experience, Sans Design](#L2-1-user-experience-sans-design) — societal-level UX
- **Assessments (evaluated on process as well as design)** — [Lesson 1.2 › Learning Assessments](#L1-2-learning-assessments)
- **Audiobook app for exercisers (running example, Unit 3)** — [Lesson 3.3 › User Types](#L3-3-user-types) — also 3.4 Exploring Ideas; 3.5 paper / Wizard of Oz / physical prototypes
- **Auditory perception (pitch, loudness, localisation; not directional)** — [Lesson 2.4 › Sensation and Perception: Auditory](#L2-4-sensation-and-perception-auditory)
- **Augmented reality (AR)** — [Lesson 1.3 › Technology: Augmented Reality](#L1-3-technology-augmented-reality) — complements rather than replaces; cameras raise societal questions

### B

- **Bad survey exercise (scales, reversed direction, leading, yes/no)** — [Lesson 3.3 › Quiz: Exercise: Surveys](#L3-3-quiz-exercise-surveys) — odd number of options
- **Baddeley & Hitch (1974) working-memory model** — [Lesson 2.4 › Quiz: Memory: Perceptual Store](#L2-4-quiz-memory-perceptual-store) — visuospatial sketchpad; phonological loop; episodic buffer; central executive
- **Belmont Report** — [Lesson 3.2 › Origin of Institutional Review Board](#L3-2-origin-of-institutional-review-board) — benefits > risks; fair selection; informed consent
- **Blue Screen of Death (old vs Windows 10)** — [Lesson 2.5 › Simplicity](#L2-5-simplicity) — also Feedback section
- **Blue underlined links (convention)** — [Lesson 2.5 › Consistency](#L2-5-consistency)
- **Buffering icon (on-demand black screen)** — [Lesson 2.2 › Gulf of Evaluation](#L2-2-gulf-of-evaluation)

### C

- **CAPTCHA** — [Lesson 1.3 › Domain Security](#L1-3-domain-security)
- **Ceiling fan chains** — [Lesson 2.5 › Perceptability](#L2-5-perceptability)
- **Chess experts vs novices (perceptual buffer)** — [Lesson 2.4 › Quiz: Memory: Perceptual Store](#L2-4-quiz-memory-perceptual-store)
- **Chunking** — [Lesson 2.4 › Quiz: Memory: Short Term and Chunking](#L2-4-quiz-memory-short-term-and-chunking) — words vs pseudo-words vs letter strings
- **CITI training (Group 2: Social and Behavioral)** — [Lesson 3.2 › Getting Started: CITI Training](#L3-2-getting-started-citi-training)
- **Cognitive load (brain-as-computer; test anxiety)** — [Lesson 2.4 › Cognition: Cognitive Load](#L2-4-cognition-cognitive-load) — reduce interface load; understand context
- **Cognitive walkthrough** — [Lesson 2.1 › Views of the User: Predictor](#L2-1-views-of-the-user-predictor)
- **Colour-blindness statistics** — [Lesson 2.4 › Sensation and Perception: Visual](#L2-4-sensation-and-perception-visual)
- **Colvin / Dearborn / Schank (definitions of intelligence)** — [Lesson 2.2 › Feedback Cycles are Fundamental](#L2-2-feedback-cycles-are-fundamental)
- **Command line (ls, move) vs mouse vs touchscreen** — [Lesson 2.3 › Direct Manipulation: The Desktop Metaphor](#L2-3-direct-manipulation-the-desktop-metaphor)
- **Command-Shift-4 (Mac screenshot) — not discoverable** — [Lesson 2.5 › Discoverability](#L2-5-discoverability)
- **Computers (everything is a computer; Pokémon Go)** — [Lesson 1.1 › Computers](#L1-1-computers)
- **Conceptual models (Norman's seventh principle)** — [Lesson 2.5 › Other Sets of Principles](#L2-5-other-sets-of-principles) — own lesson; also The Sets
- **Configuration screen with 50 settings (Joyner's first job)** — [Lesson 3.1 › Quiz: Reflections: HCI Methods](#L3-1-quiz-reflections-hci-methods)
- **Confirmation bias** — [Lesson 3.3 › 5 Tips: Avoiding Bias in Needfinding](#L3-3-5-tips-avoiding-bias-in-needfinding)
- **Consistency** — [Lesson 2.5 › Consistency](#L2-5-consistency) — 'consistency is virtuous'; reuse; blue underlined links
- **Constantine & Lockwood — Software for Use** — [Lesson 2.5 › The Sets](#L2-5-the-sets)
- **Constraints (no such thing as user error; soft vs hard)** — [Lesson 2.5 › Constraints](#L2-5-constraints) — password reset screen
- **Context-sensitive (context-aware) computing** — [Lesson 1.3 › Idea: Context-Sensitive Comp](#L1-3-idea-context-sensitive-comp) — 'What time is it?' / lunch
- **Course structure (principles → methods → community)** — [Lesson 1.2 › Course Structure](#L1-2-course-structure)
- **CSCW (Computer-Supported Cooperative Work)** — [Lesson 1.3 › Idea: CSCW](#L1-3-idea-cscw) — time × place matrix
- **Ctrl+Y in Visual Studio (delete line; WordStar; Visual Basic 6)** — [Lesson 2.5 › Consistency: The Curious Case of Ctrl+Y](#L2-5-consistency-the-curious-case-of-ctrl-y)

### D

- **Data inventory (seven questions)** — [Lesson 3.3 › Data Inventory](#L3-3-data-inventory) — who; where; context; goals; needs; tasks; subtasks
- **Data management; conflicts of interest; ~three weeks response** — [Lesson 3.2 › IRB Protocols: Wrapping Up](#L3-2-irb-protocols-wrapping-up)
- **David's car: brake pedal + button; confirmation sounds** — [Lesson 2.2 › Quiz: Feedback Cycles in David's Car 2](#L2-2-quiz-feedback-cycles-in-david-s-car-2) — improvements in Car 3
- **David's car: ignition button placement (consistency with expectations)** — [Lesson 2.2 › Quiz: Feedback Cycles in David's Car 1](#L2-2-quiz-feedback-cycles-in-david-s-car-1)
- **Deception or concealment (e.g. fake Siri)** — [Lesson 3.2 › IRB Protocols: Consent Procedures](#L3-2-irb-protocols-consent-procedures)
- **Design as activity vs design as process** — [Lesson 1.2 › Learning Outcomes: To Design](#L1-2-learning-outcomes-to-design)
- **Design life cycle (needfinding → alternatives → prototyping → evaluation)** — [Lesson 3.1 › The Design Life Cycle](#L3-1-the-design-life-cycle)
- **Design life cycle as a feedback cycle** — [Lesson 3.1 › Design Life Cycles meets Feedback Cycles](#L3-1-design-life-cycles-meets-feedback-cycles)
- **Design space (vs problem space)** — [Lesson 3.4 › The Design Space](#L3-4-the-design-space)
- **Design-alternatives pros and cons table** — [Lesson 3.4 › Quiz: Exercise: Design Alternatives](#L3-4-quiz-exercise-design-alternatives) — task context; user context; audience; workflows; time; edge cases
- **Design-based research** — [Lesson 1.1 › HCI vs User Experience Design](#L1-1-hci-vs-user-experience-design) — using results of designs to conduct research
- **Desktop metaphor (files and folders)** — [Lesson 2.3 › Direct Manipulation: The Desktop Metaphor](#L2-3-direct-manipulation-the-desktop-metaphor) — command line → mouse → touchscreen
- **Direct engagement** — [Lesson 2.3 › Paper Spotlight](#L2-3-paper-spotlight-direct-manipulation-interfaces) — 'semantic objects of our goals and intentions'
- **Direct manipulation (definition)** — [Lesson 2.3 › Introduction to Direct Manipulation and Invisible Interfaces](#L2-3-introduction-to-direct-manipulation-and-invisible-interfaces)
- **Discoverability** — [Lesson 2.5 › Discoverability](#L2-5-discoverability) — Command-Shift-4 example; visibility principle
- **Discovering gestures (design challenge)** — [Lesson 2.5 › Quiz: Design Challenge: Discovering Gestures](#L2-5-quiz-design-challenge-discovering-gestures) — flash a title-bar hint in context; log
- **Distance (semantic vs articulatory)** — [Lesson 2.3 › Paper Spotlight](#L2-3-paper-spotlight-direct-manipulation-interfaces)
- **Distributed cognition (mentioned)** — [Lesson 2.4 › Quiz: Reflections: Cognitive Load](#L2-4-quiz-reflections-cognitive-load) — also 1.1 and 2.3 Paper Spotlight
- **Dix, Finlay, Abowd & Beale — learnability, flexibility, robustness** — [Lesson 2.5 › Other Sets of Principles](#L2-5-other-sets-of-principles)
- **Documentation (Nielsen; task-framed help)** — [Lesson 2.5 › Documentation](#L2-5-documentation)
- **Don Norman — six principles; Design of Everyday Things** — [Lesson 2.5 › The Sets](#L2-5-the-sets) — seventh = conceptual models

### E

- **Ease and Comfort (Universal Design; tremors; car seat memory)** — [Lesson 2.5 › Ease and Comfort](#L2-5-ease-and-comfort)
- **Edge cases (scenarios)** — [Lesson 3.4 › Quiz: Exercise: Design Alternatives](#L3-4-quiz-exercise-design-alternatives)
- **Education (desirable difficulties; cognitive load from material not interface)** — [Lesson 1.3 › Domain: Education](#L1-3-domain-education)
- **Effectiveness (defined by the goal: usability, research, change the activity)** — [Lesson 1.2 › Learning Outcomes: Effectiveness](#L1-2-learning-outcomes-effectiveness) — carbon-footprint thermostat
- **Emojis / emoticons** — [Lesson 1.3 › Idea: Social Computing](#L1-3-idea-social-computing) — also 2.3 reflections (facial-expression emoji idea)
- **Equity (same means for all; password requirements)** — [Lesson 2.5 › Equity](#L2-5-equity)
- **Errors: slips vs mistakes** — [Lesson 3.3 › Errors](#L3-3-errors) — wrong active window (slip); Mac maximize button (mistake)
- **Evaluation (where the life cycle leads)** — [Lesson 3.5 › Conclusion to Prototyping](#L3-5-conclusion-to-prototyping)
- **Existing interfaces, user reviews, interaction logs** — [Lesson 3.3 › Other Data Gathering Methods](#L3-3-other-data-gathering-methods)
- **Expert at using computers ≠ expert at designing interactions** — [Lesson 1.1 › The HCI Space](#L1-1-the-hci-space) — athlete / scientist analogy
- **Expert blind spot** — [Lesson 3.5 › Verbal Prototypes](#L3-5-verbal-prototypes)
- **Exploring HCI reflections (chosen application area)** — [Lesson 1.3 › Reflections: Exploring HCI](#L1-3-reflections-exploring-hci) — each later lesson has an 'Exploring HCI' section
- **Exploring ideas → touch, gesture, voice alternatives** — [Lesson 3.4 › Exploring Ideas](#L3-4-exploring-ideas)

### F

- **Facebook emotional-contagion study** — [Lesson 3.2 › Research Ethics and Industry](#L3-2-research-ethics-and-industry) — ethical? see following Exercise
- **Feedback (in response to errors; plain language, no codes)** — [Lesson 2.5 › Feedback](#L2-5-feedback)
- **Feedback cycles (definition)** — [Lesson 2.2 › Introduction to Feedback Cycles](#L2-2-introduction-to-feedback-cycles) — exchange of input/output between user and system
- **Feedback cycles are fundamental / definitions of intelligence** — [Lesson 2.2 › Feedback Cycles are Fundamental](#L2-2-feedback-cycles-are-fundamental) — Colvin, Dearborn, Schank
- **Feedforward** — [Lesson 2.2 › 5 Tips: Gulfs of Execution](#L2-2-5-tips-gulfs-of-execution) — Facebook pull-to-refresh
- **Figure 6 (goals → intentions → actions → output → interpret → evaluate)** — [Lesson 2.3 › Paper Spotlight](#L2-3-paper-spotlight-direct-manipulation-interfaces) — rotate-the-paper example
- **Fleshing out ideas (narrow to three or four)** — [Lesson 3.4 › Fleshing Out Ideas](#L3-4-fleshing-out-ideas)
- **Flexibility (accelerators; right-click vs hotkeys)** — [Lesson 2.5 › Flexibility](#L2-5-flexibility)
- **Forgetting the card in the reader (buzzer, phone pairing, hold receipt)** — [Lesson 2.2 › Quiz: Design Challenge: Credit Card Readers 2](#L2-2-quiz-design-challenge-credit-card-readers-2)

### G

- **Games domain** — [Lesson 1.3 › Domain: Games](#L1-3-domain-games) — mapping; feedback cycles; reviews = HCI criticisms
- **Georgia Tech subject pool (extra credit)** — [Lesson 3.2 › IRB Protocols: Human Subject Interaction](#L3-2-irb-protocols-human-subject-interaction)
- **Gerhardt-Powals; Raskin; Foley; Weinschenk & Barker (other sets)** — [Lesson 2.5 › Other Sets of Principles](#L2-5-other-sets-of-principles)
- **Gesture-based interaction** — [Lesson 1.3 › Idea: Gesture-Based Interaction](#L1-3-idea-gesture-based-interaction) — Kinect; fingers have finest muscle movements
- **GOMS model** — [Lesson 3.4 › User Modeling](#L3-4-user-modeling)
- **Good vs bad interview questions (exercise)** — [Lesson 3.3 › Quiz: Exercise: interviews](#L3-3-quiz-exercise-interviews) — yes/no; false dichotomy; 'we're developing an app'
- **GPS warning 20 seconds vs 2 seconds** — [Lesson 2.1 › Good Design, Bad Design](#L2-1-good-design-bad-design)
- **Grids (borrowed from print)** — [Lesson 1.1 › HCI vs User Interface Design](#L1-1-hci-vs-user-interface-design)
- **Gulf of evaluation (definition and three parts)** — [Lesson 2.2 › Gulf of Evaluation](#L2-2-gulf-of-evaluation) — form; interpretation; evaluation
- **Gulf of execution (definition and three components)** — [Lesson 2.2 › Gulf of Execution](#L2-2-gulf-of-execution) — identify goal; identify actions; execute actions

### H

- **Hacks and workarounds (Post-It notes on six monitors)** — [Lesson 3.3 › Hacks and Workarounds](#L3-3-hacks-and-workarounds)
- **Hammer and nail adage** — [Lesson 3.3 › Introduction to Needfinding](#L3-3-introduction-to-needfinding)
- **Haptic perception (pressure, vibration, temperature; personal)** — [Lesson 2.4 › Sensation and Perception: Haptic](#L2-4-sensation-and-perception-haptic)
- **Healthcare domain** — [Lesson 1.3 › Domain: Healthcare](#L1-3-domain-healthcare) — Fitbit, MyFitnessPal, VR therapy
- **Hierarchy of fields (human factors ⊃ HCI ⊃ UI/UX design)** — [Lesson 1.1 › HCI in the Big Picture](#L1-1-hci-in-the-big-picture)
- **Horizontal vs vertical prototypes** — [Lesson 3.5 › Basics of Prototyping](#L3-5-basics-of-prototyping) — Facebook status screen vs whole site
- **Human factors engineering** — [Lesson 1.1 › HCI vs Human Factors](#L1-1-hci-vs-human-factors) — non-computing parts too; electric car example
- **Human-robot interaction (HRI)** — [Lesson 1.3 › Technology: Robotics](#L1-3-technology-robotics) — first conference 2006, Salt Lake City
- **Humans (senses, memories, experiences, skills, knowledge)** — [Lesson 1.1 › Humans](#L1-1-humans)
- **Hutchins, Hollan & Norman (1985) 'Direct Manipulation Interfaces'** — [Lesson 2.3 › Paper Spotlight](#L2-3-paper-spotlight-direct-manipulation-interfaces) — distance + direct engagement

### I

- **Identifying a task (Morgan swiping a credit card)** — [Lesson 2.1 › Quiz: Identifying a Task](#L2-1-quiz-identifying-a-task)
- **In situ vs ex situ studies** — [Lesson 2.1 › Views of the User: Predictor](#L2-1-views-of-the-user-predictor) — ex situ in Predictor; in situ in Participant
- **Individual brainstorming (start individually; get silly)** — [Lesson 3.4 › Individual Brainstorming 1](#L3-4-individual-brainstorming-1) — Joyner's list in part 2
- **Information visualization** — [Lesson 1.3 › Idea: Information Visualization](#L1-3-idea-information-visualization) — match the reader's mental model to reality
- **Informed consent** — [Lesson 3.2 › IRB Protocols: Consent Procedures](#L3-2-irb-protocols-consent-procedures) — also Origin; Industry (specific, temporary, without coercion)
- **Input / processing / output (human abilities model)** — [Lesson 2.4 › Introduction to Human Abilities](#L2-4-introduction-to-human-abilities)
- **Institutional Review Board (IRB)** — [Lesson 3.2 › Origin of Institutional Review Board](#L3-2-origin-of-institutional-review-board) — history; see also Getting Started: IRB
- **Interaction: human ↔ task through the computer** — [Lesson 1.1 › Interaction](#L1-1-interaction) — computer mediates; goal is an invisible interface
- **Interactions, not interfaces (design the task)** — [Lesson 1.2 › Learning Outcomes: Between Humans and Computers](#L1-2-learning-outcomes-between-humans-and-computers) — leads to Nest
- **Interface mediates between user and task** — [Lesson 2.1 › Interfaces: Between Users and Tasks](#L2-1-interfaces-between-users-and-tasks)
- **Interviews and focus groups** — [Lesson 3.3 › Interviews with Focus Groups](#L3-3-interviews-with-focus-groups) — focus groups risk convergent thinking
- **Invisibility by design** — [Lesson 2.3 › Invisibility by Design](#L2-3-invisibility-by-design) — 'Creating Invisible Interfaces'
- **Invisibility by learning (driving)** — [Lesson 2.3 › Invisibility by Learning](#L2-3-invisibility-by-learning)
- **Invisible interfaces (definition; stylus vs mouse)** — [Lesson 2.3 › Invisible Interfaces](#L2-3-invisible-interfaces)
- **IRBWISE; protocol; amendment** — [Lesson 3.2 › Getting Started: IRB](#L3-2-getting-started-irb)
- **ISO six principles of user-centered design** — [Lesson 3.1 › Principles of User-Centered Design](#L3-1-principles-of-user-centered-design)
- **Iterative needfinding (one earphone example)** — [Lesson 3.3 › Iterative Needfinding](#L3-3-iterative-needfinding)

### J

- **Jackman & Kanerva — 'Evolving the IRB' (Washington and Lee Law Review)** — [Lesson 3.2 › Paper Spotlight](#L3-2-paper-spotlight-evolving-the-irb-building-robust-review-for-industry-research)
- **Jakob Nielsen — ten heuristics; Usability Inspection Methods** — [Lesson 2.5 › The Sets](#L2-5-the-sets)
- **Jef Raskin's law (computer shall not harm your work)** — [Lesson 2.5 › Tolerance](#L2-5-tolerance) — also Other Sets (The Humane Interface)

### L

- **Learning by example / doing / reflection** — [Lesson 1.2 › Learning Strategies: Video Material](#L1-2-learning-strategies-video-material)
- **Learning goals (three)** — [Lesson 1.2 › Learning Goals](#L1-2-learning-goals) — principles; design life cycle; expanse/applications
- **Learning outcome: design effective interactions between humans and computers** — [Lesson 1.2 › Learning Outcomes: To Design](#L1-2-learning-outcomes-to-design)
- **Light pen and first computer mouse** — [Lesson 1.1 › HCI vs User Interface Design](#L1-1-hci-vs-user-interface-design)
- **Light switches and stove dials (mapping challenge)** — [Lesson 2.5 › Quiz: Design Challenge: Mapping and Switches](#L2-5-quiz-design-challenge-mapping-and-switches)
- **Long-term memory / Leitner system (flashcards)** — [Lesson 2.4 › Memory: Long Term Memory](#L2-4-memory-long-term-memory)
- **Lucy (18-month-old) and Kindle Fire; cats using tablets** — [Lesson 2.3 › Babies and Direct Manipulation](#L2-3-babies-and-direct-manipulation)

### M

- **Mac menu bar vs PC window menus (selection difficulty)** — [Lesson 1.1 › HCI vs User Interface Design](#L1-1-hci-vs-user-interface-design)
- **Mac touchpad gestures (which are direct manipulation)** — [Lesson 2.3 › Quiz: Exercise: Direct Manipulation](#L2-3-quiz-exercise-direct-manipulation) — click, scroll, pinch = yes; right-click, double-tap zoom = no
- **Mapping** — [Lesson 2.5 › Mapping](#L2-5-mapping) — cut/copy/paste; monitor arrangement; colour meter fade
- **Memory: three kinds (perceptual store, short-term, long-term)** — [Lesson 2.4 › Quiz: Memory: Perceptual Store](#L2-4-quiz-memory-perceptual-store)
- **Message alerts design challenge (light sensor → flash or vibrate)** — [Lesson 2.4 › Quiz: Design Challenge: Message Alerts](#L2-4-quiz-design-challenge-message-alerts)
- **Metaphorically vs literally invisible** — [Lesson 2.3 › Good Design, Bad Design In](#L2-3-good-design-bad-design-in)
- **Metaphors / analogies to physical devices (swipe a page)** — [Lesson 2.5 › Affordances](#L2-5-affordances)
- **Microwave / chili example (Time Cook; press 1; automatic reheat)** — [Lesson 2.2 › Gulf of Execution Example](#L2-2-gulf-of-execution-example)
- **Milgram obedience experiment** — [Lesson 3.2 › Origin of Institutional Review Board](#L3-2-origin-of-institutional-review-board)
- **Mixed methods** — [Lesson 3.1 › Qualitative vs. Quantitative Data](#L3-1-qualitative-vs-quantitative-data)
- **Mobile computing (mobile-first)** — [Lesson 1.3 › Technology: Mobile](#L1-3-technology-mobile) — limited screen, imprecise input, distracted user
- **Morgan (running example character)** — [Lesson 1.1 › Humans](#L1-1-humans) — appears in 2.1, 2.4, 2.5, 3.3, 3.4, 3.5
- **Morgan on the Street (design challenge)** — [Lesson 2.1 › Quiz: Design Challenge: Morgan on the Street](#L2-1-quiz-design-challenge-morgan-on-the-street) — audiobooks while walking; running example
- **Motor system / Spotify widget close vs skip button** — [Lesson 2.4 › Motor System](#L2-4-motor-system) — error tolerance: double-tap, 5-second confirm
- **Multi-level prototyping (LinkedIn; bottom-up vs top-down)** — [Lesson 3.5 › Multi-Level Prototyping](#L3-5-multi-level-prototyping)

### N

- **National Research Act of 1974** — [Lesson 3.2 › Origin of Institutional Review Board](#L3-2-origin-of-institutional-review-board)
- **Naturalistic observation** — [Lesson 3.3 › Naturalistic Observation](#L3-3-naturalistic-observation) — park from the porch; ethical limits
- **Needfinding / requirements gathering (definition)** — [Lesson 3.3 › Introduction to Needfinding](#L3-3-introduction-to-needfinding) — biggest mistake: designing before understanding
- **Needfinding for book reading (design challenge)** — [Lesson 3.3 › Quiz: Design Challenge: Needfinding for Book Reading](#L3-3-quiz-design-challenge-needfinding-for-book-reading)
- **Needfinding pros and cons table** — [Lesson 3.3 › Quiz: Exercise: Needfinding Pros and Cons](#L3-3-quiz-exercise-needfinding-pros-and-cons) — six advantages × eight methods
- **Nest thermostat** — [Lesson 2.1 › Interfaces: Between Users and Tasks](#L2-1-interfaces-between-users-and-tasks) — also 1.2 and 3.4 Second Biggest Mistake
- **New York parking signs** — [Lesson 2.5 › Simplicity](#L2-5-simplicity)
- **Nielsen Norman Group** — [Lesson 2.5 › The Sets](#L2-5-the-sets)
- **Nissan Leaf options screen locked while moving (safety constraint)** — [Lesson 2.5 › Quiz: Reflections: Constraints](#L2-5-quiz-reflections-constraints)
- **Norman's four types of constraints (physical, cultural, semantic, logical)** — [Lesson 2.5 › Norman's Four Types of Constraints](#L2-5-norman-s-four-types-of-constraints)
- **Notification Center swipe; animation (clearing windows, Launchpad)** — [Lesson 2.3 › Making Indirect Manipulation](#L2-3-making-indirect-manipulation) — making indirect manipulation feel direct

### O

- **Observer bias** — [Lesson 3.3 › 5 Tips: Avoiding Bias in Needfinding](#L3-3-5-tips-avoiding-bias-in-needfinding)
- **One prototype = one iteration; one-minute cycle** — [Lesson 3.5 › Design Life Cycle Revisited](#L3-5-design-life-cycle-revisited)
- **Osborn (1957) — four rules (expressiveness, nonevaluation, quantity, building)** — [Lesson 3.4 › Rules for Group Brainstorming](#L3-4-rules-for-group-brainstorming)
- **Oxley, Dzindolet & Paulus (1996) — four more rules** — [Lesson 3.4 › Rules for Group Brainstorming](#L3-4-rules-for-group-brainstorming) — stay focused; no explaining; revisit problem; encourage others

### P

- **Paper prototyping / card-based prototyping** — [Lesson 3.5 › Paper Prototyping](#L3-5-paper-prototyping) — Morgan wants to see where she is in the book
- **Participant observation (Joyner jogs)** — [Lesson 3.3 › Participant Observation](#L3-3-participant-observation)
- **Peer learning, collaborative learning, learning by teaching, communities of practice** — [Lesson 1.2 › Learning Strategies: Georgia Tech](#L1-2-learning-strategies-georgia-tech)
- **Pen- and touch-based interaction** — [Lesson 1.3 › Idea: Pen- and Touch-Based Interaction](#L1-3-idea-pen-and-touch-based-interaction)
- **Perceptibility** — [Lesson 2.5 › Perceptability](#L2-5-perceptability) — ceiling-fan chains violate it
- **Perception of coercion** — [Lesson 3.2 › The Value of Research Ethics](#L3-2-the-value-of-research-ethics) — also recruitment in classroom research
- **Personas (Anika)** — [Lesson 3.4 › Personas](#L3-4-personas) — 3–4 different personas
- **Phone that shouts every letter (small actions, small feedback)** — [Lesson 2.2 › Good Design, Bad Design: Feedback Cycles](#L2-2-good-design-bad-design-feedback-cycles)
- **Phone-number chunking** — [Lesson 2.4 › Memory: Short Term Takeaways](#L2-4-memory-short-term-takeaways)
- **Physical prototypes (key fob; doesn't have to work)** — [Lesson 3.5 › Physical Prototypes](#L3-5-physical-prototypes)
- **Portal 2 (camera-axis preference set invisibly)** — [Lesson 2.3 › Quiz: Reflections: Invisibility by Design](#L2-3-quiz-reflections-invisibility-by-design)
- **PowerPoint Copy in Edit menu shows hotkey (interface teaches)** — [Lesson 2.4 › Cognition: Learning](#L2-4-cognition-learning) — also 2.3 5 Tips
- **Primary Investigator (PI)** — [Lesson 3.2 › IRB Protocols: Basics](#L3-2-irb-protocols-basics) — added first; must be faculty
- **Problem space (alarm example)** — [Lesson 3.3 › The Problem Space](#L3-3-the-problem-space)
- **Procedural vs declarative learning** — [Lesson 2.4 › Cognition: Learning](#L2-4-cognition-learning) — unconsciously competent; designers are experts
- **Production blocking** — [Lesson 3.4 › Challenges in Group Brainstorming](#L3-4-challenges-in-group-brainstorming)
- **Programming / IDE inline error checking (cognitive load)** — [Lesson 2.4 › Quiz: Reflections: Cognitive Load](#L2-4-quiz-reflections-cognitive-load) — links to distributed cognition
- **Project-based learning** — [Lesson 1.2 › Learning Strategies: Georgia Tech](#L1-2-learning-strategies-georgia-tech)
- **Protocol fields (PI must be faculty; description; methodology; benefits; risks; dates)** — [Lesson 3.2 › IRB Protocols: Basics](#L3-2-irb-protocols-basics)
- **Prototyping (early vs late; low vs high fidelity)** — [Lesson 3.5 › Basics of Prototyping](#L3-5-basics-of-prototyping)
- **Prototyping pros and cons table** — [Lesson 3.5 › Quiz: Exercise: Prototyping Pros and Cons](#L3-5-quiz-exercise-prototyping-pros-and-cons) — revisable; disguises details; simulates interaction; remote; look and feel; mobility
- **Psychology and HCI (cross-listed at Georgia Tech)** — [Lesson 1.1 › HCI vs Psychology](#L1-1-hci-vs-psychology)

### Q

- **Qualitative vs quantitative data** — [Lesson 3.1 › Qualitative vs. Quantitative Data](#L3-1-qualitative-vs-quantitative-data) — 'what' vs 'how/why'; mixed methods

### R

- **Recall bias** — [Lesson 3.3 › 5 Tips: Avoiding Bias in Needfinding](#L3-3-5-tips-avoiding-bias-in-needfinding)
- **Recognition over recall** — [Lesson 2.4 › Quiz: Memory: Short Term and Recognition](#L2-4-quiz-memory-short-term-and-recognition) — menu bars, tool strips (Takeaways)
- **Recording MOOCs (methods-unit design challenge)** — [Lesson 3.1 › Design Challenge: Recording MOOCS](#L3-1-design-challenge-recording-moocs)
- **Red dot / black circle (what you know vs what there is to know)** — [Lesson 1.1 › The HCI Space](#L1-1-the-hci-space)
- **Representation / fidelity / evaluation / scope (four concepts)** — [Lesson 3.5 › Basics of Prototyping](#L3-5-basics-of-prototyping)
- **Representing the need (task outline, hierarchical network, structural diagram, flow-chart)** — [Lesson 3.3 › Representing the Need](#L3-3-representing-the-need)
- **Requirements (functionality, usability, learnability, accessibility; compatibility, compliance, cost)** — [Lesson 3.3 › Defining the Requirements](#L3-3-defining-the-requirements)
- **Research informs design, design informs research** — [Lesson 1.1 › HCI: Research and Design](#L1-1-hci-research-and-design) — 'the heart of HCI'

### S

- **Scenarios and storyboards (fire engine)** — [Lesson 3.4 › Scenarios and Storyboards](#L3-4-scenarios-and-storyboards) — video prototyping
- **Second biggest mistake (settling on one idea too early)** — [Lesson 3.4 › The Second Biggest Mistake](#L3-4-the-second-biggest-mistake) — keypad + key chain
- **Security domain (usable security)** — [Lesson 1.3 › Domain Security](#L1-3-domain-security) — CAPTCHA checkbox; explain password rules; password game
- **Seven Questions for bridging gulfs (Norman)** — [Lesson 2.2 › Seven Questions for Bridging Gulfs](#L2-2-seven-questions-for-bridging-gulfs)
- **Short-term memory: 4–5 chunks (vs 7 ± 2)** — [Lesson 2.4 › Quiz: Memory: Short Term and Chunking](#L2-4-quiz-memory-short-term-and-chunking)
- **Signifiers** — [Lesson 2.5 › Affordances](#L2-5-affordances) — in-context instructions (arrows, 'Menu' label)
- **Simplicity** — [Lesson 2.5 › Simplicity](#L2-5-simplicity) — Blue Screen of Death; NY parking signs
- **Six W's (who, what, where, when, why, how)** — [Lesson 3.3 › 5 Tips: Interviews](#L3-3-5-tips-interviews)
- **Social computing** — [Lesson 1.3 › Idea: Social Computing](#L1-3-idea-social-computing) — emojis as recreated social norms
- **Social desirability bias** — [Lesson 3.3 › 5 Tips: Avoiding Bias in Needfinding](#L3-3-5-tips-avoiding-bias-in-needfinding) — also interview exercise; verbal prototypes (3.5)
- **Social loafing** — [Lesson 3.4 › Challenges in Group Brainstorming](#L3-4-challenges-in-group-brainstorming)
- **Sonification / Bruce Walker** — [Lesson 1.3 › Domain: Special Needs](#L1-3-domain-special-needs) — communicating data via sound
- **Special needs (accessibility domain)** — [Lesson 1.3 › Domain: Special Needs](#L1-3-domain-special-needs)
- **Square credit-card reader: swipe vs insert** — [Lesson 2.2 › Quiz: Design Challenge: Credit Card Readers 1](#L2-2-quiz-design-challenge-credit-card-readers-1) — too fast or too slow; physical feedback
- **Stakeholders: primary, secondary, tertiary** — [Lesson 3.1 › Stakeholders](#L3-1-stakeholders) — grade-book example; helicopter parenting
- **Stanford prison experiment** — [Lesson 3.2 › Origin of Institutional Review Board](#L3-2-origin-of-institutional-review-board)
- **Stash vs E-Trade (UX as differentiator)** — [Lesson 3.1 › Quiz: Reflections: HCI Methods](#L3-1-quiz-reflections-hci-methods)
- **Structure (Constantine & Lockwood; Wall Street Journal)** — [Lesson 2.5 › Structure](#L2-5-structure)
- **Subjects: number/genders, vulnerable populations, justification, inclusion/exclusion, recruitment, compensation** — [Lesson 3.2 › IRB Protocols: Human Subject Interaction](#L3-2-irb-protocols-human-subject-interaction)
- **Surveys (breadth; 150 responses in a week)** — [Lesson 3.3 › Surveys](#L3-3-surveys)

### T

- **Task analysis** — [Lesson 2.1 › Views of the User: Predictor](#L2-1-views-of-the-user-predictor) — also 3.3 Representing the Need; 3.4 User Modeling
- **Technologies / Domains / Ideas (three categories)** — [Lesson 1.3 › Introduction to Exploring HCI](#L1-3-introduction-to-exploring-hci)
- **Tesla Model S / computers on wheels** — [Lesson 1.1 › HCI vs Human Factors](#L1-1-hci-vs-human-factors)
- **The Inmates Are Running the Asylum (Alan Cooper) — dancing bear** — [Lesson 3.1 › Quiz: Reflections: HCI Methods](#L3-1-quiz-reflections-hci-methods)
- **Thermostat (recurring example)** — [Lesson 1.2 › Learning Outcomes: To Design](#L1-2-learning-outcomes-to-design) — also 2.1 Interfaces; 2.2 Gulf of Evaluation Example; 3.4 Second Biggest Mistake
- **Thermostat heat-on indicator example** — [Lesson 2.2 › Gulf of Evaluation Example](#L2-2-gulf-of-evaluation-example)
- **Think-aloud protocol / post-event protocol** — [Lesson 3.3 › Think-Aloud](#L3-3-think-aloud)
- **Thompson (2008) — four blockers of group brainstorming** — [Lesson 3.4 › Challenges in Group Brainstorming](#L3-4-challenges-in-group-brainstorming) — social loafing; conformity; production blocking; performance matching (+ power dynamics)
- **Time and place matrix (same/different)** — [Lesson 1.3 › Idea: CSCW](#L1-3-idea-cscw) — course; Slack/HipChat; museum kiosk; camera/teleprompter
- **Timeline / journey map** — [Lesson 3.4 › Timeline](#L3-4-timeline)
- **Tolerance (emergency exit; undo/redo; recoverability)** — [Lesson 2.5 › Tolerance](#L2-5-tolerance) — Raskin's law
- **Toolbox of methods** — [Lesson 3.1 › Methods for the Design Life Cycle](#L3-1-methods-for-the-design-life-cycle)
- **Tradeoffs of prototyping ('runaway train of designing')** — [Lesson 3.5 › Tradeoffs of Prototyping](#L3-5-tradeoffs-of-prototyping)
- **Tripped breaker / reset button on outlet** — [Lesson 2.2 › Quiz: Reflections: Feedback Cycles](#L2-2-quiz-reflections-feedback-cycles)
- **Tuskegee syphilis study** — [Lesson 3.2 › Origin of Institutional Review Board](#L3-2-origin-of-institutional-review-board) — fair selection requirement
- **Two remote controls (visible interface example)** — [Lesson 1.1 › Quiz: Reflections: Interacting & Interfaces](#L1-1-quiz-reflections-interacting-interfaces)

### U

- **Ubiquitous / pervasive computing, Internet of Things** — [Lesson 1.3 › Technology: UbiComp and Wearables](#L1-3-technology-ubicomp-and-wearables)
- **Udacity hours tracker / classroom / Sleep app (three views examples)** — [Lesson 2.1 › Quiz: Reflections: Views of the User](#L2-1-quiz-reflections-views-of-the-user)
- **Unit four readings** — [Lesson 1.3 › Conclusion to Exploring HCI](#L1-3-conclusion-to-exploring-hci)
- **Universal Design — Seven Principles (Ronald Mace, NC State)** — [Lesson 2.5 › The Sets](#L2-5-the-sets)
- **Universal remote control (voice interface design challenge)** — [Lesson 2.3 › Quiz: Design Challenge: The](#L2-3-quiz-design-challenge-the) — 'watch Community'; Conan clip
- **Usefulness vs usability** — [Lesson 2.1 › Usefulness and Usability](#L2-1-usefulness-and-usability) — map vs navigation app
- **User experience (UX) design** — [Lesson 1.1 › HCI vs User Experience Design](#L1-1-hci-vs-user-experience-design) — HCI understands; UX dictates; symbiotic
- **User experience at individual, group and societal levels** — [Lesson 2.1 › User Experience, Sans Design](#L2-1-user-experience-sans-design) — 'never no user experience' — like the weather
- **User interface (UI) design** — [Lesson 1.1 › HCI vs User Interface Design](#L1-1-hci-vs-user-interface-design) — light pen, mouse, grids, Mac vs PC menus, wireframes
- **User modeling (GOMS: goals, operators, methods, selection rules)** — [Lesson 3.4 › User Modeling](#L3-4-user-modeling)
- **User profiles (variables; frequent vs occasional users)** — [Lesson 3.4 › User Profiles](#L3-4-user-profiles)
- **User types / Sony Walkman** — [Lesson 3.3 › User Types](#L3-3-user-types) — Doing Cultural Studies (Mackay & Janes)
- **User-centered design (definition)** — [Lesson 3.1 › User-Centered Design](#L3-1-user-centered-design)

### V

- **VCR / DVR / on-demand example** — [Lesson 2.2 › Gulf of Execution](#L2-2-gulf-of-execution)
- **Verbal prototypes (analogies; 'Uber for groceries'; expert blind spot)** — [Lesson 3.5 › Verbal Prototypes](#L3-5-verbal-prototypes)
- **Video games as invisible interfaces** — [Lesson 1.1 › Quiz: Reflections: Interacting & Interfaces](#L1-1-quiz-reflections-interacting-interfaces) — also Domain: Games in 1.3
- **Video prototyping** — [Lesson 3.4 › Scenarios and Storyboards](#L3-4-scenarios-and-storyboards)
- **Views of the user: participant** — [Lesson 2.1 › Views of the User: Participant](#L2-1-views-of-the-user-participant) — context; in situ studies
- **Views of the user: predictor** — [Lesson 2.1 › Views of the User: Predictor](#L2-1-views-of-the-user-predictor) — knowledge/expectations; qualitative, ex situ; task analysis, cognitive walkthrough
- **Views of the user: processor** — [Lesson 2.1 › Views of the User: Processor](#L2-1-views-of-the-user-processor) — physical limits; quantitative experiments
- **Virtual reality (VR)** — [Lesson 1.3 › Technology: Virtual Reality](#L1-3-technology-virtual-reality) — phobia treatment lab in Michigan; also 2.3 direct manipulation
- **Visual perception (centre vs periphery; colour-blindness; acuity with age)** — [Lesson 2.4 › Sensation and Perception: Visual](#L2-4-sensation-and-perception-visual) — 1 in 12 men, 1 in 200 women
- **Voluntary response bias** — [Lesson 3.3 › 5 Tips: Avoiding Bias in Needfinding](#L3-3-5-tips-avoiding-bias-in-needfinding)
- **VR and 3D design (direct manipulation)** — [Lesson 2.3 › Exploring HCI: Direct Manipulation](#L2-3-exploring-hci-direct-manipulation)

### W

- **Waiver of consent / waiver of documentation of consent** — [Lesson 3.2 › IRB Protocols: Consent Procedures](#L3-2-irb-protocols-consent-procedures)
- **Wearables** — [Lesson 1.3 › Technology: UbiComp and Wearables](#L1-3-technology-ubicomp-and-wearables) — exercise monitors, smart watches, Google Glass, hearing aids, prosthetics
- **Wireframing tools (Balsamiq, Axure, Visio, InDesign, Pencil Project, Frame Box)** — [Lesson 3.5 › Wireframing](#L3-5-wireframing)
- **Wizard of Oz prototyping** — [Lesson 3.5 › Wizard of Oz](#L3-5-wizard-of-oz) — human supplies unimplemented functionality; 'close note'; five seconds back
- **Wrong task: 'pay for purchases' not 'swipe a card' (tap your phone)** — [Lesson 2.2 › Quiz: Design Challenge: Credit Card Readers 3](#L2-2-quiz-design-challenge-credit-card-readers-3)

### Y

- **You are not your (own) user** — [Lesson 1.2 › Learning Strategies: Video Material](#L1-2-learning-strategies-video-material) — also 2.1 5 Tips; 3.3 Participant Observation
