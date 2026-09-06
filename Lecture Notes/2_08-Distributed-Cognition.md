# 2.8 Distributed Cognition

**CS6750 · Human–Computer Interaction** — Lecture notes (David Joyner, Summer 2017 lecture book, pp. 311–343)  
*Full lecture content, restructured for revision. `»` marks a speaker change in video-transcript dialogue.*

## Contents
- [Introduction to Distributed Cognition](#introduction-to-distributed-cognition)
- [Distributed Cognition](#distributed-cognition)
- [Paper Spotlight: "How a Cockpit Remembers Its Speeds"](#paper-spotlight-how-a-cockpit-remembers-its-speeds)
- [How a Cockpit Remembers Its Speed](#how-a-cockpit-remembers-its-speed)
- [Distributed Cognition and Cognitive Load](#distributed-cognition-and-cognitive-load)
- [Quiz: Exercise: Distributed Cognition](#quiz-exercise-distributed-cognition)
- [Distributed Cognition as a Lens](#distributed-cognition-as-a-lens)
- [Quiz: Reflections: Distributed Cognition](#quiz-reflections-distributed-cognition)
- [Distributed Cognition to Social Cognition](#distributed-cognition-to-social-cognition)
- [Social Cognition](#social-cognition)
- [Quiz: Design Challenge: Social Cognition](#quiz-design-challenge-social-cognition)
- [Situated Action](#situated-action)
- [Situated Action and Memory](#situated-action-and-memory)
- [Paper Spotlight: "Plans and Situated Actions"](#paper-spotlight-plans-and-situated-actions)
- [Activity Theory](#activity-theory)
- [Paper Spotlight: "Activity Theory and Human-Computer Interaction"](#paper-spotlight-activity-theory-and-human-computer-interaction)
- [Paper Spotlight: "Studying Context: A Comparison of Activity Theory, Situated Action Models, and Distributed Cognition"](#paper-spotlight-studying-context-a-comparison-of-activity-theory-situated-action-models-and-distributed-cognition)
- [Exploring HCI: Distributed Cognition](#exploring-hci-distributed-cognition)
- [Conclusion to Distributed Cognition](#conclusion-to-distributed-cognition)

## Introduction to Distributed Cognition

[MUSIC] In discussing a human-computer interaction, there's often a tendency to look narrowly at the user interacting with the computer. Or slightly more broadly at the user interacting with the task through some computer. But many times we're interested in zooming even further out. We're interested, not only in the interaction between the human, the computer and the task, but also in the context in which that interaction takes place. So today we're going to look at four different models or theories, of the context surrounding ACI.

We'll focus primarily on distributed cognition, which is one of the dominant theories on the interplay between multiple agents, artifacts, and contexts.

We'll also touch on three other significant theories, social cognition, situated action, and activity theory.

## Distributed Cognition

Cognition on its own is interested in thought processes and experiences and we naturally think of those as occurring inside the mind. But distributed cognition suggests that models of the mind should be extended outside the mind. This theory proposes expanding the unit we use to analyze intelligence from a single mind to a mind equipped with other minds and artifacts and their relationships among them.

So let’s take an example or this. Amanda, give me a hard addition problem.

<Amanda: 1238 + 6437>

Okay can I do that in my head? No, I honestly can't even remember the numbers you just read to me. But I have a pen and paper her, and using those, I can pretty easily write down the numbers. So give those numbers to me again.

<Amanda: 1238 + 6437>

Okay, and using that I can now do the calculation by hand, and the answer is 7675.

Now, did I get smarter when I grabbed the pen and paper? Not really, not by the usual definition of “smarter” at least. But the system comprised of myself, the pen, the paper is a lot more than just my mind on its own. The cognition was distributed amongst these artifacts. Specifically, the paper took care of remembering the numbers for me and remembering and tracking my progress so. So, instead of adding 1238 plus 6437, I was really just adding 8+7, 3+3, 2+4 and so on.

## Paper Spotlight: "How a Cockpit Remembers Its Speeds"

One of the seminal works in distributed cognition research is a paper in the Journal of Cognitive Science from 1995 called “How a Cockpit Remembers its Speeds” by Edwin Hutchins. You might recognize Edwin Hutchins' name from our lesson on direct manipulation and invisible interfaces. He was one of the coauthors there along with Don Norman. It’s one of my favorite papers, in part simply because of the very subtle change in emphasis in its title. We tend to think of ‘remembering’ as a uniquely human or biological behavior. We describe computers as having memory, but we don’t usually describe computers as remembering things. Remembering is more of a human behavior. But the paper title twists that a little bit. It isn't the human, it' isn't the pilot remembering, it's the cockpit remembering. What is the cockpit? The cockpit is a collection of controls, sensors, and interfaces, as well as the pilots themselves. The paper title tells us that it's this entire system: the pilots, the sensors, the controls, and the interfaces among them that do the remembering. The system as a whole, the cockpit as a whole is remembering the speed, not just the human pilot or pilots inside the cockpit. No individual part in isolation remembers what the system as a whole can remember.

## How a Cockpit Remembers Its Speed

In order to understand the application of distributed cognition to the cockpit, it's important for us to first understand what challenge it's addressing. The technical reasons for this are a bit complex, and I strongly encourage reading the full paper to get the full picture. But to understand the simplified description I'll give here, here's what you need to know.

When a plane is descending for landing, there exists a number of different changes the pilots need to make to the wing configurations. These changes are made at different speeds during the descent. When the plane slows down to a certain speed, it demands a certain change to the wind configuration. The speeds at which these configuration changes must happen differ based on a number of different variables. So for every flight there's a unique set of speeds that must be remembered. That's why the title of this paper is, How a Cockpit Remembers Its Speeds, Speeds, plural. It isn't just remembering how fast it's going now, it's remembering a sequence of speeds at which multiple changes must be made. The configuration changes to the wings must be made during the descent at narrowly defined times. That creates a high cognitive load. Pilots must act quickly. And mistakes could mean the deaths of themselves and hundreds of others. So how do they do this?

First, the pilots have pages that contain the speeds for their descent, based on different parameters. The cockpit itself has an entire booklet of pages like this.

So we know that the cockpit has its pilots who are responsible for actually reasoning over things. But that booklet forms that cockpits long term memory of different speeds for different parameters. Then, prior to the descent, the pilots find the page from that booklet that corresponds to their current parameters. They pull it out and pin it up inside the cockpit. That way, the sheet is accessible to both pilots. And they're able to check one another's actions throughout. This becomes one form of the cockpits short term memory, a temporary representation of the current speeds. At this point, we have to attribute knowledge of those speeds to the cockpit itself. If we were to isolate either pilot, they would be unable to say what the speeds are from memory, but without the pilots to interpret those speeds, the card itself is meaningless. So it's the system of the entire cockpit, including the pilots, the booklet and the current card that remembers the speeds.

Then as the pilots begin the descent, they mark the different speeds right on the speedometer with these little speed bugs. The speed bugs tell them which speeds to remember in a way that can just be visually compared. When they see the speedometer pass a speed bug, they know it's time to make a certain change.

This is like the working memory for the cockpit. The short-term memory stores the numbers in a way that the pilots can reason over, but the speed bugs on the speedometer store them in a way that they can very quickly just visually compare. They don't need to remember the numbers themselves, or do any math. All they have to do is visually compare the speed bugs to the current position of the speedometer. So what do we see from the system as a whole? Well, we see the long term memory in the book of cards. We see a short term memory in the card they selected. We see a working memory in the speed bugs on the speedometer. And we see decisions on when to make configuration changes distributed across the pilots and these artifacts. No single part of this cockpit, not the pilots, not the speed bugs, not the cards, could perform the action necessary to land a plane on their own. It's only the system as a whole that does so. That's the essence of distributive cognition. The cognition involved in landing this plane is distributed across the components of the system. This is a deeper notion than just using interfaces to help us do tasks. The important thing here is that these different interfaces serve cognitive roles in the system.

## Distributed Cognition and Cognitive Load

Distributed cognition is deeply related to the idea of cognitive load. Recall the cognitive load refers to your minds ability to only deal with a certain amount of information at a time. Distributed cognition suggests that artifacts add additional cognitive resources. That means the same cognitive load is distributed across a greater number of resources. Artifacts are like plugging extra memory into your brain. Driving is a good example of this. Sometimes while driving, you're cognitive load can be very, very high. You have to keep track of the other cars around you. You have to keep track of your own speed to monitor your route planning. You have to make predictions about traffic patterns. You have to pay attention to your own level of gasoline, or in my case, electric charge. You might be attending to something in your car as well, like talking to your passenger, or keeping an eye on your child in the back seat. It can be a big challenge. A GPS is a way of off-loading one of the tasks, navigation, on to another system. And thus, your cognition, is now distributed between you In the GPS. Turn on cruise control and now it's distributed across the car, as well. Your off loading the task of tracking your speed to the car. Every task you also de-artifacts, decreases your own personal cognitive load.

## Quiz: Exercise: Distributed Cognition

Let's analyze a simple task from the perspective of distributed cognition. Here we see Morgan paying some bills the old fashioned way. For each bill she pulls it off the pile, reads it, writes a check and puts them together in a stack on the right. Where do we delineate this system? What are its parts?

We're interested in any part of the system that performs some of the cognition for Morgan. While the chair, table, and light over head make this possible, they aren't serving any cognitive roles. Morgan herself, of course, is, and two piles of bills are too. They are an external memory of what bills Morgan has already paid, and what she still needs to pay. This way she doesn't have to mentally keep track of what bills she has left to do. The bills themselves remember a lot of the information for her as well like the amounts and the destinations they need to be sent to. What about the pen and checkbook? That's when things start to get a little bit more tricky. The checkbook itself is part of the system because it takes care of the record keeping task for Morgan. Checkbooks create carbon copies, which means Morgan doesn't have to think about tracking the checks manually. The pen is a means of communicating between these systems, which means it's part of our distributed cognition system as well.

## Distributed Cognition as a Lens

Something important to note is that distributed cognition isn't really another design principle. Distributed cognition is more of a way of looking at interface design. It's a way of approaching the problem that puts your attention squarely on how to extend the mind across artifacts. We can actually view many of our design principles as examples of distributed cognition. So this is my computer, and when I set this up, I wasn't thinking about it in terms of distributed cognition. And yet we can use distributive cognition as a lens through which to view this design.

For example, I always have my calendar open on the right. That's a way of off loading having to keep track of my daily schedule in working memory. It bugs me if I have a teleconference to attend or somewhere I need to go. In fact I rely on this so much it gets me in trouble. It doesn't keep track of where I need to be for a given meeting and if I fail to keep track of that in working memory I might end up at home when I need to be at Georgia Tech. We can even view trivial things like a clock as an example of distributed cognition that prevents me from having to keep track of the passage of time manually. The point is that distributed cognition is a way of looking at interfaces and interface design that focuses your attention on what systems as a whole can accomplish as opposed to individuals on their own.

## Quiz: Reflections: Distributed Cognition

Distributed cognition is a fun one to reflect on because we can take it to some pretty silly extremes. We can go so far as to say that I don't heat up my dinner. The system compromised of myself and the microwave heats it up. And I offload the need to track the time to cook on to my microwave's timer. And that's a perfectly valid way of looking at things. But what we're interested in is places where interfaces don't just make our lives more convenient. We're interested in places where they systems comprised of us and interfaces are capable of doing more, specifically because those interfaces exhibit certain cognitive qualities. The systems might perceive, they might remember, they might learn, they might act on our behalf. In some way they're all floating a cognitive task from us. And as a result, the system comprised of us and the interface, is capable of doing more. So reflect on that a bit, what is the place where the system comprised of you and some number of interfaces is capable of doing more than you alone? Specifically, because of the cognitive qualities that the interfaces possess.

Almost any interface on the computer can be analyzed from the perspective of distributed cognition but right now, I'm most interested in my email. My email is an unbelievable extension of my long term memory because whenever I see anything in email, I know I don't actually need to commit it to my own long-term memory. It's there, it's safe forever, and if I ever need to find it again, I'll be able to find it. Now, finding it might take some work sometimes, but rarely as much work as manually remembering it. For me, I also mark messages as unread if I'm the one they're waiting on, or if I need to make sure I come back to them. And so, my email is an external memory of both all my communications via email, and tasks that are waiting on me to move forward.

## Distributed Cognition to Social Cognition

Distributed cognition is concerned with how the mind can be extended by relations with other artifacts and other individuals.

Because we're interface designers, we probably focus most of our time on the artifacts part of that. After all, even though we're designing tasks, the artifacts are what we're actually creating that's out in the world.

But the other part of distributed cognition, distributing across individuals presents a powerful opportunity as well. This used to be far more important, actually.

Before the days of GPS navigation, a different form of navigation assistance existed. It was your spouse or your friend sitting in the passenger seat, reading a map and calling out directions to you.

And while mobile devices and artificial intelligence may have replaced humans in some such systems, there are still lots of places where the role of distributing across humans is crucial. Here's an example of this in action today.

At Udacity, we use a tool for managing projects called JIRA. It breaks down projects into multiple pieces that can be moved through a series of steps and assigned to different responsible individuals. The entire value of JIRA is that it manages distributing tasks across members of a team. Thus, when a project is completed, it is completed by the system comprising the individual team members and JIRA itself.

## Social Cognition

The social portion of distributed cognition is concerned with how social connections create systems that can, together, accomplish tasks. So for example, you and your friend sitting in the passenger seat, together form a system capable of navigating to a new destination without a GPS. But social cognition is not only concerned with how social relationships combine to accomplish tasks. It's also concerned with the cognitive underpinnings of social interactions themselves. It's interested in how perception, memory, and learning relate to social phenomena. As interface designers, though, why do we care? Well, in case you haven't noticed, one of the most common applications of interface design today involves social media. Everything is becoming social. Facebook tries to tell you when your friends are already nearby. Udacity tries to connect you with other students working on the same material as you. Video games are increasingly trying to convince you to share your achievements and highlights with your friends. And yet, often times, our interfaces are at odds with how we really think about social interaction. Designing for this well involves understanding the cognitive underpinnings of social relationships. My PlayStation, for example, has a feature for finding my real life friends, and then communicating to them my gaming habits. But really, I probably don't want them to know how much I might play video games. If I come unprepared for recording today, I certainly don't want Amanda to know it was because I was playing Skyrim for six hours last night. So if we're going to design interfaces that integrate with social interactions, we have to understand how social interactions actually work. So an understanding of social cognition is very important if that's the direction you want to take.

## Quiz: Design Challenge: Social Cognition

Let's talk about challenge of designing for social relationships. I like to play video games. I'm friends with people from work. So it's natural that I might want to play games with people from work. But at the same time, my relationship with people from work isn't purely social. If they see I'm playing a game, maybe they say, hey, David's got some free time. I should ask him to help me out with something. Or if they see I spend a lot of time playing video games, maybe they more generally say hey, David's got plenty of time to take on a new tasks. How do we design a social video gaming system that nonetheless protects against these kinds of perceptions?

There are lot of creative ways we might tackle this problem. One might be a base social video game relationship around something like tender. Tinder, if this is still around by the time you're watching this, is a dating app were you express interest in another's in are only connected if they also express interest in you. We can apply the same colonoscopy to video games. You can set it such that My Contacts can't just look up my game playing habits. But if they're also playing or interested in playing, they'll learn that I am playing as well. In terms of social cognition, that's kind of getting at the idea of an in-group. Your behaviors are only seen by those who share them and thus are in no position to judge them.

## Situated Action

Like distributed cognition, situated action is strongly concerned with the context within which people interact. But unlike distributed cognition, situated action is not interested in the long-term and enduring or permanent interactions amongst these things. That’s not to say the theory denies the existence of long-term memory, but it just has a different focus. Situated action focuses on humans as improvisers. It’s interested not in the kinds of problems that people have solved before, but in the kinds of novel, situational problems that arise all the time. So, for an example of this, this is the first time I’m filming with my daughter on camera. I don’t know how she’ll act. I don’t have contingency plans set up for how to react if she acts strangely or if she distracts me from my script. I’m just going to figure this out as I go along. This is the kind of interaction that situated action is interested in. And that’s an important view for us to hold as interface designers. While we like to think we’re in charge of structuring the task for our users, in reality the tasks that we perform is going to grow out of their interaction. We can try our best to guide it in certain directions, but until we actually get our hands on it, the task doesn’t exist. The task of me filming with my daughter didn't exist until this moment. Once we've got our hands on it, the task is what we do, not what we designed. So as users, when we use an interface, when we actually do something, we're defining the task as we go along. So, there are three takeaways here.

One, we must examine the interfaces we design within the context in which they’re used.

Two, we must understand that the task that users perform grows out of their interaction with our interfaces -- we don’t define it.

And three, we can try to structure it as much as we can, but until users get started, the task itself doesn’t exist -- and once they get started, they play a significant role in defining the task.

## Situated Action and Memory

Situated action gives us a valuable lens to examine issues of memory. We mention in our lessons on memory and on design principles that recognition is easier than recall. People have an easier time recognizing the right answer, or option when they see it rather than recalling it from scratch. That's in part because memory is so context dependent. Recognition provides the necessary context to identify the right option. Relying on recall, means there's little context to cue the right answer to the users memory. Now I encountered an interesting example of the value of situated action a little while ago. My mother just had surgery. And so I would often go over to help her out with things. And every time I would go over, she'd have four, five favors to ask me. Inevitably I would forget a couple of those favors and have to be reminded, but she would always remember. Why was she so much better able to remember the favors than me? Does she just have a better memory? She didn't make a list. She didn't write them down or anything like that. So the distributed cognition perspective doesn't find an external memory being used or anything like that. My hypothesis from the perspective of situated action, is that she has the context behind the tasks. She knows why they need to be done. She knows what will happen if they aren't. For her, they're part of a broader narrative. For me, they're items on a list. I have no context for why they're there. Or what would happen if they're undone. For her, they're easy to remember because they're situated in a larger context. For me, they're difficult because they're isolated.

## Paper Spotlight: "Plans and Situated Actions"

Lucy Suchman's 1985 book, Plans and Situated Actions is the seminal book on the philosophy of situated action. The book is a detailed comparison between two views of human action.

The first view, she writes, views the organization and significance of action as derived from plans. And this is a model we very often adopt when developing interfaces. Users make plans and users carry out those plans, but Suchman introduces a second view as well.

In this view, people simply act in the world, and plans are what we derive from those actions. Instead of plans dictating actions, plans are interpretations of actions. What this means for us as interface designers is that rather than assuming the user has a plan in mind that they're actively carrying out, we might consider viewing only their immediate interaction with the current screen instead. In other words, forget the history of actions that led the user to a certain screen and ask just once they're here how do they know what to do next?

Later in the book, Lucy Suchman specifically touches on communication between humans and machines. There's a lot more depth here as well, the key take away for us is to focus on the resources available to the user at any given time. But I do recommend reading the book and this chapter for more insights.

## Activity Theory

Activity theory is a massive and well developed set of theories regarding interaction between various pieces of an activity. The theory as a whole is so complex that you could teach an entire class on it alone. It predates HCI. And in fact, activity theory is one of the first places the idea of interacting through an interface actually came from. In our conversations about HCI though, there are three main contributions of activity theory that I'd like you to come away with. First, when we discuss designing tasks and completing tasks through an interface, we risk missing a key component. Why? We could jump straight to designing the task, but why is the user completing the task in the first place? That can have significant implications for our design.

Activity theory generalizes our unit of analysis from the task to the activity. We're not just interested in what they're doing, but why they're doing it and what it means to them. Our designs will be different, for example, if users are using a system because they're required to or because they choose to. Notice how this is similar to our discussion of distributed cognition, as well. In distributed cognition, we were generalizing the unit of analysis from a person, to a system of people and artifacts. Here, we're generalizing the unit of analysis from a task to an activity surrounding a task. In both ways, we're zooming out on the task and the design space.

Second, activity theory puts an emphasis on the idea that we can create low level operations from higher level actions. We saw something similar to this with GOMS models, where methods were made up of operators. This has a special historical significance. Before activity theory and similar theories reached HCI in the 1980s, HCI was largely concerned with minute things, like how quickly a person can click a button or type in a command. Activity theory helped us zoom out from those low level interactions, those low level operators, to general user needs at the action or the activity levels. And third, activity theory points out that actions by the user can actually move up and down this hierarchy. A common example of this is driving a car. The first time you drove a car, shifting gears between park and drive was a very conscious action made up of operators like grabbing the gear shift and moving it in the right direction and letting go. You had to think about how to press the button, which way to push the stick, and when to release it. However, after driving a few times, shifting gears just becomes second nature. It becomes more like an operator. It shifted from being a conscious goal to an operator in your broader driving behavior. Notice a similarity here to our previous discussion on learning curves. How quickly an action moves from being a conscious action to a subconscious operator is also a function of how good the learning curve is on that design. Notice also, this is similar to the question of invisible interfaces. A good invisible interface helps users focus on their actions inside the task, rather than the operators they use to interact with the system.

## Paper Spotlight: "Activity Theory and Human-Computer Interaction"

In 1996, Bonnie Nardi edited a prominent book on the study of context in human-computer interaction, titled Context and Consciousness. The entire book is worth reading, but two papers in particular stand out to me, both by Nardi herself. The first is a short paper that serves in some ways as an introduction to the book as a whole. It's not a long paper, only four pages, so I highly recommend reading it. It won't take you long. Here, Nardi outlines the general application of activity theory to HCI.

She notes that activity theory offers a set of perspectives on human activity and a set of concepts for describing that activity. And this is exactly what HCI research needs as we struggle to understand and describe context, situation and practice. She particularly notes that the theory is uniquely suited to addressing some of the interesting issues facing HCI in 1996. And for that reason, it's also fascinating to view from a historical perspective. Today we understand the role that context has grown to play, especially with emerging technologies. It's fascinating to me to look back at how the community was constructing that debate 20 years ago.

## Paper Spotlight: "Studying Context: A Comparison of Activity Theory, Situated Action Models, and Distributed Cognition"

In this lesson we covered three theories on studying context in human computer interaction. Distributed cognition, Situated action and Activity theory. If your having trouble keeping the three straight though, Nardi has a great paper for you. From her volume context in consciousness. Nardi wrote a comparison between the three philosophy is she titled, Studying Context: A Comparison of Activity Theory, Situated Action Models, and Distributed Cognition.

She starts by giving a great one page summary of each of these three views, which would be really good if you're having trouble understanding the finer points of these theories.

Even more usefully, she goes on to give commentary on the difference between these three big theories.

First, she notes the activity theory and distributive cognition are driven by goals. Whereas situated action de-emphasizes goals for a focus on improvisation.

She goes on to summarize that situated actions says goals are constructed retroactively to interpret our past actions.

Nardi also evaluates the role of permanent, persistent structures, noting their important for activity theory and distributed cognition. But present attention for situated action. So here we again see a similarity between activity theory and distributed cognition.

So what makes them different? Well, Nardi writes that the main difference between activity theory and distributed cognition is their evaluation of the symmetry between people and artifacts.

Activity theory regards in this fundamentally different, giving that humans have consciousness.

Distributed cognition by contrast believes that artifacts can serve cognitive roles. And so those should be considered conceptually equivalent to humans. So that gives a high level overview of the difference between these three theories. These theories are big and complex of course and the complete paper goes into much more detail. But this should provide a decent glimpse at the distinctions, at least enough to get you started reading the paper for yourself.

## Exploring HCI: Distributed Cognition

Distributed cognition is a perspective on analyzing systems that helps us emphasize the cognitive components of interfaces themselves. It helps us look at things we design as extensions of the user's own cognition. We can view anything from notes on a desktop to the entire Internet as an extension of the user's own memory. We can view things like Gmail's automatic email filtering as off-loading cognitive tasks from the user. In looking at things through this lens, we focus on the output not just of people of into interfaces, but on the combination of people and interfaces together. So, what are they able to do together that neither of them could do individually? As we close this lesson, think about this in terms of your chosen areas of HCI. What are the cognitive components of the areas with that you're dealing? How do augmented reality and wearable devices off-load some of the user's cognition onto the interface? And as occasional technology, or in HCI for health care, what are the tasks being accomplished by the system's comprised of users and interfaces?

## Conclusion to Distributed Cognition

In this lesson, we've talked about distributed cognition and a couple related theories. The commonality of all these theories was their emphasis on context in integrated systems. Distributed cognition is interested in how cognition can be distributed among multiple individuals and artifacts, all working together. By taking a distributed view of interface design, we can think about what the combination of our users and our interfaces are able to accomplish.

Situated action and activity theory give additional perspectives of this, focusing respectively on the importance of ad hoc improvisation and the need to emphasize users' motives beyond just their goals. The common ground for all these theories is that our interfaces are not simply between user and their task, but they also exist in some kind of greater context.
