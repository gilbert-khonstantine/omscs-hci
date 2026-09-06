# 2.7 Task Analysis

**CS6750 · Human–Computer Interaction** — Lecture notes (David Joyner, Summer 2017 lecture book, pp. 282–310)  
*Full lecture content, restructured for revision. `»` marks a speaker change in video-transcript dialogue.*

## Contents
- [Introduction to Task Analysis](#introduction-to-task-analysis)
- [GOMS Model](#goms-model)
- [GOMS Model in Action](#goms-model-in-action)
- [Quiz: Design Challenge: Security System 1](#quiz-design-challenge-security-system-1)
- [Strengths and Weaknesses of GOMS](#strengths-and-weaknesses-of-goms)
- [Paper Spotlight: "The GOMS Family of User Interface Analysis Techniques: Comparison and Contrast"](#paper-spotlight-the-goms-family-of-user-interface-analysis-techniques-comparison-and-contrast)
- [5 Tips: Developing GOMS Models](#5-tips-developing-goms-models)
- [GOMS to Cognitive Task Analysis](#goms-to-cognitive-task-analysis)
- [Quiz: Reflections: Task Analysis](#quiz-reflections-task-analysis)
- [Cognitive Task Analysis](#cognitive-task-analysis)
- [Hierarchical Task Analysis](#hierarchical-task-analysis)
- [Quiz: Design Challenges: Security System 2](#quiz-design-challenges-security-system-2)
- [Cognitive Task Analysis Strengths and Weaknesses](#cognitive-task-analysis-strengths-and-weaknesses)
- [Other Task Analysis Frameworks](#other-task-analysis-frameworks)
- [Exploring HCI: Task Analysis](#exploring-hci-task-analysis)
- [Conclusion to Task Analysis](#conclusion-to-task-analysis)

## Introduction to Task Analysis

[MUSIC] When looking at human computer interaction, we're really looking at the tasks that users perform. We look at the tasks that they're performing now and we try to restructure those tasks to be more efficient using new interfaces. In all of this, the task is at the heart of the exercise. What task are they performing?

So today, we're going to talk about two methods for formally articulating the tasks that people are completing.

First, we'll discuss human information processor models, especially the GOMS Model which focuses on the input to the user and the output from the user. Note this is similar to the processor model of the user that we discuss elsewhere.

Second, we'll discuss cognitive task analysis. A way of trying to get inside the users head instead of focusing just on the input and the output. Note that that's similar to the predictor model of the user that we also discuss elsewhere.

## GOMS Model

The GOMS model is a human information processor model so it builds off the processor model of the human's role in a system. The GOMS model gets its name from the four sets of information it proposes gathering about a task. G, stands for the users Goals in the system. O, stands for the Operators the user can perform in the system. M stands for the Methods that the user can use to achieve those goals. And S stands for the Selection rules that the user uses to choose among different competing methods. So the GOMS Model proposes that every human interact with the system has a set of Goals that they want to accomplish. They have sent methods that they can choose from to accomplish those goals. Each of those methods is comprise of a series of Operators that carries out that method. And they have some Selection rules that help them decide what method to use and when.

The GOMS model is often visualized like this. The user starts with some initial situation, and they have a goal in mind that they want to accomplish, so they apply their selection of rule to choice between different competing methods to accomplish that goal. Once they've chosen a method, they execute that series of operators and makes that goal a reality

## GOMS Model in Action

We can take the GOMS model and apply it to a number of different domains. So let's take the example of needing to communicate a message to a coworker.

We have an initial situation, which is the need to transfer information to a coworker. That carries with it the implicit goal of the information having been transferred. We might have a number of different methods in mind for how we could do that. We could email them, we could walk over and talk to them in person. And we also have some selection rules that dictate how we choose amongst these methods. If what we need to transfer is very time-sensitive, maybe we walk over and talk to them in person or call them on the phone. If the information we need to transfer is complex and detailed, maybe we write them an email. Or if it's more casual, maybe we chat with them or text them. No matter what method we choose, we then execute the series of operators that carries out that method, and the result is our goal is accomplished, the information has been transmitted.

Or we could also take the problem of navigation. Our initial situation is the need to get to our destination, which carries with it the implicit goal of having reached our destination. We might have different methods, like take the scenic route, take the highway route, take the surface streets, and some selection rules that might say something like, when it's rush hour on the highway, take surface streets, or if it's not time sensitive, take the scenic route. After choosing, we execute those operators and reach our goal. So in this way, GOMS models capture our goals, our different methods for carrying out those goals, and the individual operators that we use to execute those methods.

## Quiz: Design Challenge: Security System 1

Let's try this out. We're going to watch Morgan enter the house and undo her security system two different ways. After you watch the video, try to outline Morgan's goals, outcomes, methods, and selection rules. [MUSIC] Now try to outline the goals, outcomes, methods and selection rules for these two methods of disabling the security system.

Here's one example of how you might design a GOMS model for disabling a security system. Our initial situation is that we're entering the home with the alarm set and we have two methods for disabling the alarm. We can use the keypad or we can use the keychain. Either way, our goal is that we've entered the home and reenabled the alarm. Our selection rules might be something like if we have our hands full, we're going to use the keypad so that we can get inside and put the stuff down. But if we don't have our hands full, we'll use the keychain. You might come up with other models for this that have either different methods, different operators, different selection rules. There are a lot of different ways we can capture a task with the GOMS model, depending on what you choose to focus on.

## Strengths and Weaknesses of GOMS

There are strengths and weaknesses to the GOMS representation for tasks. One weakness is that it doesn't automatically address a lot of the complexity of these problems. For example, there are likely many different methods and sub-methods for addressing this goal. Before even getting to selection rules among what route to take, you might decide whether to take public transportation or whether to work from home that day. In parallel to that, even after deciding to drive, you might decide what car to take if your family has more than one car. The standard GOMS model leaves those kinds of things out, although there are augmented versions that have been created to deal with this kind of complexity, like CMN-GOMS and NGOMSL. We'll talk about those a bit more later.

A second weakness is that the GOMS model assumes the user already has these methods in mind. That means the user is already an expert in the area. GOMS does not do a good job of accounting for novices or accounting for user errors. For example, if you're driving in an unfamiliar location, you don't even know what the methods are, let alone how to choose among them.

The strength of GOMS, on the other hand, is its ability to formalize user interaction into steps that we can actually use to make predictions. We can measure how long each of these operators takes, and so we can predict the overall efficiency of using a certain interface. For example, in this GOMS model, if we had included the operator "pull keys out of the user's pocket" we might quickly identify that the relative efficiency of these two methods is very much dependent on how long that step takes. The keychain method may be a lot faster if the user can get their key chain out pretty quickly. But for other users, the fact that they need to pull something out of their pocket while holding bags or holding a baby makes the keypad a more efficient option. By performing that kind of reasoning, we can focus on areas that either method and the interface as a whole can be improved.

## Paper Spotlight: "The GOMS Family of User Interface Analysis Techniques: Comparison and Contrast"

There are several varieties of GOMS models, these varieties share the commonality of goals operators, methods, and selection criteria, but they differ in what additional elements they provide. Bonnie John and David Kieras covered four popular variations in a paper from 1996. The first is the Vanilla GOMS we've talked about so far. And the other three, are KLM GOMS, CMN GOMS, and NGOMSL. Let's talk about what those acronyms actually mean.

They start with the Keystroke-Level Model, which is the simplest technique. Here, the designer simply specifies the operators and execution times for an action, and sums them to find the complexity of an interaction. This method proposed six different types of operators, although for moderate interfaces, we would need some new ones to cover touch screens and other novel interfaces.

A second variation, is CMN-GOMS. CMN-GOMS is an extension of GOMS that features sub methods and conditions in a strict GOAL hierarchy.

For example, here we see a hierarchy of GOALs, as well as the ability to choose between multiple GOALs in different areas. Notice also the level of granularity behind these GOMS models. The GOALs go all the way down to little GOALs, like moving text or deleting phrases. These are very, very low-level GOALS.

Notice also the way this model is being used. The authors are using it to find the places where there's a lot of complexity that can be cut out. They do this by modeling how long each individual action takes, as well as looking at the number of interactions required and seeing if they can be cut down a bit.

A third variation is called Natural GOMS Language. Natural GOMS language, or NGOMSL, is a natural language form of GOMS that lends itself to human interpretation. In all these cases, the important point of emphasis is the way that these models allow us to focus in on places where we might be asking too much of the user.

For example, in this model, the user is being asked to carry a lot of information in working memory. By making the assumptions and actions and operators this detailed, this model lets us target where working memory's being overly taxed in a way that we might miss when we're doing higher level designs.

## 5 Tips: Developing GOMS Models

Here are five quick tips for developing GOMS models. Number 1, focus on small goals. We've used some pretty big examples, but GOMS was really designed to work in the context of very small goals, like navigating to the end of a document. You can abstract up from there, but start by identifying smaller, moment to moment goals. Number 2, nest goals instead of operators. It's possible to nest goals. For example, in our GOMS model of navigation, we could develop it further and break the overall task of navigating down to smaller goals like changing lanes or plotting routes. Operators, however, are the smallest atoms of a GOMS model. They don't break down any further and those must be the actual actions that are performed. Number 3, differentiate descriptive and prescriptive. Make sure to identify whether you're building a model of what people do or what you want them to do. You can build a goal model of what people should do with your interface. But you shouldn't trick yourself into thinking that's necessarily what they will do. Number 4, assign costs to operators. GOMS was designed to let us make predictions about how long certain methods will take. The only way we can do that is if we have some measurement of how long individual operations take. Usually this is time, but depending on the domain, we might be interested in phrasing the cost differently as well. Number 5, use GOMS to trim waste. One of the benefits of GOMS is it lets you visualize where an unnecessary number of operators are required to accomplish some task. That's bolstered by the costs we assign to those operators. So use GOMS to identify places where the number of operators required can be simplified by the interface.

## GOMS to Cognitive Task Analysis

GOMS models are human information processor models. This method largely assumes the human is an input output machine, and it doesn't get too much into the internal reasoning of the human. Instead, it distills their reasoning into things that can be described explicitly like goals and methods. Some would argue, myself included, that human reasoning is actually too nuanced and complex to be so simplified. They, or we, advocate other models to get more into what goes on inside the user's head. That's where cognitive task analysis comes in. Cognitive task analysis is another way of examining tasks, but it puts a much higher emphasis on things like memory, attention, and cognitive load. Thus, cognitive task analysis adopts more of the predictor view of the human's role in the system.

## Quiz: Reflections: Task Analysis

This conflict between more processor-oriented and more predictor-oriented models of the user actually gets at the core of an old battle in psychology between behaviorism and cognitivism. Behaviorism emphasized things that could be observed. We can see what input a person is receiving. We can see the output they're producing. And that might be all we need to understand the design of things.

Cognitivism, on the other hand, suggests we can and should get into the mind of what people are actually thinking and how systems like memory and learning and perception actually work. So take a moment and reflect on what you think about this. When designing interfaces, how much attention should you devote to observable goals, operators and methods? And how much do you devote to understanding internal thought processes, like cognition, learning, and memory?

You can probably guess my bias on this issue, given that I've already badmouthed the processor model and I also teach cognitive systems. So I'm generally going to prefer methods that focus on cognition. I think it's important to note here though that both approaches have significant value. The GOMS model and its emphasis on identifying goals and operators is actually very useful in HCI. Because it forces us to very clearly and deliberately identify user goals and the sequence of actions that accomplish them. We can get so caught up in user experiences that we forget the user experience is born out of individual operators. So while I wouldn't advocate focusing solely on the user as some kind of input output information processor, there's value in defining the user's operation as clearly and specifically as we define a computer's.

## Cognitive Task Analysis

Cognitive Task Analysis is not really a single method, but it's more of a type of method to approaching the evaluation of how people complete tasks. Performing a cognitive task analysis involves a number of different techniques and methods that we'll discuss more when we discuss the design life cycle. For right now, though, we’re interested in what kinds of information we’re trying to gather, not how we’re gathering it. Cognitive task analyses are especially concerned with understanding the underlying thought process in performing a task. Not just what we can see, but specifically what we *can’t* see. There are a lot of different methods for performing cognitive task analyses, but most methods follow a particular common sequence.

First, we want to collect some preliminary knowledge. While we as interface designers don’t need to become experts in a field, we need a good bit of familiarity with it. So, we might observe people performing the task, for example. In navigation, for example, we might just watch someone driving and using a GPS.

Our second step is to identify knowledge representations. In other words, what kinds of things does the user need to know to complete their task? Note that we’re not yet concerned with the actual knowledge they have, only the types or structures of the knowledge that they have. For example, we want to know: does this task involve a series of steps in a certain order? Does it involve a collection of tasks to check off in any order? Does it involve a web of knowledge to memorize? For navigation, for example, we would identify that the structure of the knowledge is a sequence of actions in order, as well as some knowledge of things to monitor as we go.

Then, in the third stage, we actually want to populate those knowledge representations. This is the stage where we start to recognize what the user actually knows. With navigation, for example, they know to start the GPS, to enter an address, and to obey the turns while monitoring traffic and speed and things like that. During this stage, we identify all the specific actions they take, the knowledge they must have in mind to take those actions, the interruptions that can change their thought processes, the equipment involved, and the sensory experience of the user. We do this by applying focused knowledge elicitation methods. In other words, we get users to tell us what's going on in their heads or what's going on in their environment. Or sometimes we do things that help us understand parts of the task that the user isn't even themselves aware of.

Then, we analyze and verify the data we acquired. Part of that is just confirming with the people we observed that our understanding is correct. We might watch them do something and infer it's for one reason when in reality it's for a very different reason. So we want to present to our users our results and make sure that they agree with our understanding of their task. Then, we attempt to formalize it into structures that can be compared and summarized across multiple data-gathering methods.

And finally, we format our results for the intended application. We need to take those results and format them in a way that's useful for interface design. We want to develop models that show what the user was thinking, feeling, and remembering at any given time and make those relationships explicit. The result might look something like this:

Here we see a very high-level model of the process of driving to a destination. What’s interesting to note is that these tasks in the middle are highly cognitive rather than observable. If I had no knowledge about driving and sat in a passenger’s seat watching the driver, I might never know that they’re monitoring their route progress or keeping an eye on their dashboard for how much fuel they have left. If you have kids you may have experienced this personally, actually. To a kid sitting in the back seat, Mommy or Daddy are just sitting in the driver's seat just like they're sitting in the passenger's seat. They don't have a full understanding of the fact that you have a much higher cognitive load and you're doing a lot more things while you're driving than they are. That's because what you're doing is not observable. It's all in your head. So to get at these things I might have the user think out loud about what they’re doing while they’re going it. I might have them tell me what they're thinking while they're driving the car. That would give me some insights into these cognitive elements of the task.

## Hierarchical Task Analysis

Cognitive task analysis advocates building models of human reasoning and decision-making in complex tasks. However, a challenge presented here is that very often, large tasks are actually composed of many multiple smaller tasks. We can see this plainly present in our cognitive model of driving. These tasks are so high-level that it’s almost useless to describe driving in these terms. Each part could be broken down into various sub-tasks like iteratively checking all the cars around you or periodically checking how long it is until the next turn needs to be made. What’s more, these smaller tasks could then be used in different contexts. Route-monitoring, for example, isn’t only useful while driving a car -- it might be useful while running or biking or while riding as a passenger. Traffic monitoring might be something an autonomous vehicle might do, not just the human user. So, the analysis of a task in a particular context could be useful in designing interfaces for other contexts if we break the analysis down into subtasks. So let’s take a simple example of this.

Here’s a somewhat simple model of the act of buying something online. Notice that a lot of the tasks involved here are general to anyone shopping on any web site, and yet every web site needs to provide all of these functions. As a side note, notice also the interesting analogy going on with the top two.

Online, there is no cart or checkout station, but we borrowed those to help the user understand the shopping process online and how similar it is to shopping in a store.

Anyhow, if we treat this cognitive task analysis more hierarchically we can start to see a well-defined subtask around this checkout process. Every online vendor I've ever encountered has these steps in its checkout process. Now because this is so well-defined, we could leverage existing tools, like existing payment widgets or something like PayPal. This hierarchical task analysis helps us understand what tools might already be available to accomplish certain portions of our task or how we might design certain things to transfer between different tasks and different contexts. Hierarchical task analysis also lets the designers of the site abstract over this part of the process and focus more on what might make their particular site unique. This type of task analysis is so common that you generally will find tasks and subtasks whenever you’re looking at the results of a cognitive task analyses. So it’s important to remember the strengths supplied by this hierarchy: abstracting out unnecessary details for a certain level or abstraction, modularizing designs or principles so they can be transferred between different tasks or different contexts, and organizing cognitive task analysis in a way that makes it easier to understand and reason over. Lastly, it’s also important to note that the cognitive and hierarchical task analyses we’ve shown here are extremely simplistic, mostly, honestly, because of limited screen real estate. When you’re creating real cognitive models, you’ll likely have several levels of abstractions, several different states, and additional annotating information like what the user has to keep in mind or how they might be feeling at a certain stage of the analysis. We’ll put some examples of some good, thorough models in the notes.

## Quiz: Design Challenges: Security System 2

Let’s watch the videos of Morgan disabling her security system again. This time, though, let’s try to approach this from a more cognitive task analysis perspective. We won’t be able to do that fully because doing a full cognitive task analysis means interviewing, asking the user to think out loud, and more, but we can at least try out this approach. Remember, in doing a cognitive task analysis for a task like this, your goal is to build a model of the sequence of thoughts going on inside the user's. Pay special attention to what she needs to remember at each step of the process.

What we saw here was that to get inside and disable the alarm, there was a sequence of actions that had to be completed, but some of them could be completed in different orders. If she used the keypad, she had to first unlock the door and then open the door. Then she could either disable the alarm on the keypad or close the door. And after closing the door, she could re-lock the door, though she could also do that before disarming the alarm. So there's some choices there. With the keychain, the sequence of tasks related to the door remain the same, but she had the option of disarming the alarm before even entering. However, that required remembering to do so. When using the keypad, she didn't have to remember because the alarm beeps at her until she turns it off. But she has to remember the key code. Performing these cognitive task analyses gives us the information necessary to evaluate different approaches and look for areas of improvement. For example, if she can disable the alarm just by pressing the keychain button, why does she need to press it at all? Why doesn't it just detect that she's coming in with a keychain in her pocket?

## Cognitive Task Analysis Strengths and Weaknesses

Just like GOMS models, cognitive task analysis also have some strength and some weaknesses. One strength is that they emphasize mental processes. Unlike the GOMS model, cognitive task analysis puts an emphasis on what goes on inside the users head. It's thus much better equipped to understand how experts think and work.

The information it generates is also formal enough to be used for interface design, for comparison in mode alternatives and more. There are disadvantages though.

One, cogni-task analysis are incredibly time-consuming to perform. They involve talking to multiple experts for extended period of time, then systematically analyzing the data.

A second weakness is that cogni-task analysis risk deemphasizing context. In zooming in on the individual's own thought processes, cogni-task analysis risks deemphasizing details that are out in the world. Like the role of physical capabilities or interactions amongst different people, or different artifacts.

And third, like GOMS models, cogni-task analysis also isn't well suited to novices. It's well suited to expert users who have very strong models of the way they work and clearly understand their own mental thought processes. But they're not very well suited for novice users who are still trying to learn how to use an interface.

## Other Task Analysis Frameworks

GOMS and cognitive tasks analysis are just two of the many alternatives to understanding how users approach tasks. More in line with the human information processor models, there exist models like KLM, TLM, and MHP, which capture even finer grain actions for estimating performance speed. There are other extensions to GOMS as well that add things like sub goals, or other ways of expressing content like CPM-GOMS and NGOMSL. CPM-GOMS focuses on parallel tasks, while NGOMSL provides a natural language interface for interacting with GOMS models. More on the lines of cognitive models, there exists other methods as well like CDM, TKS, CFM, Applied Cognitive Task Analyses, and Skill-Based Cognitive Task Analyses. CDM puts a focus on places where critical decisions occur. TKS focuses on the nature of humans' knowledge. CFM focuses on complexity. ACTA and Skill-Based CTA are two ways of gathering the information necessary to create a cognitive model. There also exists other frameworks more common in other disciplines, for example, production systems are common to an artificial intelligence. But they're intended to model cognitive systems the same way these cognitive models do. So we can apply production systems here as well and attempt to prescribe rules for users to follow.

## Exploring HCI: Task Analysis

Every possible application of HCI involves users completing some sort of task. That task might be something within a domain. In educational technology, for example, that task might be learning how to do a certain kind of problem. If your area is more technological, the task might be something the user is doing through your application, like using virtual reality and gesture recognition to sculpt a virtual statue. Take a moment and try to think of the kinds of tasks you might be interested in exploring in your chosen application area. Do they lend themselves more to an information processor model like GOMS? Or to cognitive models like hierarchical task analysis? And how can you tell?

## Conclusion to Task Analysis

Today we've talked at length about two general methods for approaching task analysis.

One, the GOMS family of approaches tries to distill tasks down to their goals, operators, methods and selection rules.

The other, cognitive task analyses, aim to get in the head of the user and understand what they're thinking, feeling and remembering at every stage of the task. When we discussed design life cycle we focus a bit on how to fill these models with information but our focus there is on the methods for gathering the information rather than the structure of the information itself. So it's important to keep these methods in mind when we talk about that.
