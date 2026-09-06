# 2.4 Human Abilities

**CS6750 · Human–Computer Interaction** — Lecture notes (David Joyner, Summer 2017 lecture book, pp. 155–186)  
*Full lecture content, restructured for revision. `»` marks a speaker change in video-transcript dialogue.*

## Contents
- [Introduction to Human Abilities](#introduction-to-human-abilities)
- [Information Processing](#information-processing)
- [Sensation and Perception: Visual](#sensation-and-perception-visual)
- [Sensation and Perception: Auditory](#sensation-and-perception-auditory)
- [Sensation and Perception: Haptic](#sensation-and-perception-haptic)
- [Quiz: Design Challenge: Message Alerts](#quiz-design-challenge-message-alerts)
- [Quiz: Memory: Perceptual Store](#quiz-memory-perceptual-store)
- [Quiz: Memory: Short Term and Chunking](#quiz-memory-short-term-and-chunking)
- [Quiz: Memory: Short Term and Recognition](#quiz-memory-short-term-and-recognition)
- [Memory: Short Term Takeaways](#memory-short-term-takeaways)
- [Memory: Long Term Memory](#memory-long-term-memory)
- [Cognition: Learning](#cognition-learning)
- [Cognition: Cognitive Load](#cognition-cognitive-load)
- [Quiz: Reflections: Cognitive Load](#quiz-reflections-cognitive-load)
- [5 Tips: Reducing Cognitive Load](#5-tips-reducing-cognitive-load)
- [Motor System](#motor-system)
- [Exploring HCI: Human Abilities](#exploring-hci-human-abilities)
- [Conclusion to Human Abilities](#conclusion-to-human-abilities)

## Introduction to Human Abilities

[MUSIC] Human computer interaction starts with human. So it's important that we understand who the human is, and what they're capable of doing. In this lesson, we're going to bring up some psychology of what humans can do. We'll look at three systems. Input, processing, and output.

Input is how stimuli are sent from the world, and perceived inside the mind.

Processing is cognition, how the brain stores, and reasons over the input it's received.

Output is how the brain then controls the individual's actions out in the world. Now, we're going to cover a lot of material at a very high level. If you're interested in hearing more, I recommend taking a psychology class, especially one focusing on sensation and perception. We'll put some recommended courses in the notes.

## Information Processing

In discussing human abilities, we're going to adopt something similar to the processor view of the human. For now we're interested in what they can do, physically, cognitively, and so on.

So we're going to focus exclusively on what's going on over here. We're going to look at how the person makes sense of input, and how they then act in the world. And right now, we're not going to worry too much about where that input came from, or what their actions in the world actually do. Notice that in this lesson we're discussing the human, almost the same way we discuss the computer, or the interface, in most lessons. The human is something that produces output and consumes input, just like a computer might be otherwise. But for now, we're only interested in how the human does this.

## Sensation and Perception: Visual

Let's start by talking a bit about what the average person can sense and perceive. So, here we have Morgan again. Morgan has eyes. Morgan's eyes are useful for a lot of things.

The center of Morgan's eye is most useful for focusing closely on color or tracking movement. So, we can assume that the most important details should be placed in the center of her view. Morgan's peripheral vision is good for detecting motion, but it isn't as good for detecting color or detail. So while we might use her periphery for some alerts, we shouldn't require her to focus closely on anything out there.

As a woman, Morgan is unlikely to be colorblind, she has about a 1 in 200 chance. Men have a much greater prevalence of color blindness at about 1 in 12. Either way, that's a significant body of people. So we want to avoid relying on color to understand the interface. We can use it to emphasize knowledge that it's already present in the system, but using the system shouldn't rely on perceiving color. Sight is directional. If Morgan's looking the wrong way or has her eyes closed, she'll miss visual feedback.

As Morgan gets older, her visual acuity will decrease. So if we're designing something with older audiences in mind, we want to be careful of things like font size. Ideally, these would be adjustable to meet the needs of multiple audiences. All together though, Morgan's visual system is hugely important to her cognition. The majority of concepts we cover in HCI are likely connected to visual perception. [SOUND]

## Sensation and Perception: Auditory

Morgan also has ears.

Morgan can discern noises based on both their pitch and their loudness.

Her ears are remarkably good at localizing sound as well. In fact, she can tell the difference between a nearby quiet sound and a far away loud sound. Even if their relative pitches and loudnesses are the same when they reach her ear.

Unlike vision, hearing isn't directional. Morgan can't close her ears or point her ears the wrong direction so she can't as easily filter out auditory information. That might be useful for designing alerts, but it's problematic for overwhelming her or sharing too much information with the people around her.

## Sensation and Perception: Haptic

Morgan's skin can feel things.

It can't feel at a distance but it can feel when things are touching right up against it.

It can feel a variety of different types of input, like pressure, vibration and temperature. Like listening, Morgan can't easily filter out touch feedback. But unlike listening, touch feedback is generally only available to the person it's touching, so it can be used to create more personal feedback. Traditionally, touch feedback, or haptic feedback, has been very natural.

Morgan feels the keys go down as she presses them on keyboard.

But with touch screens, motion controls and virtual reality, touch needs to be more and more designed explicitly into the system if we're to use it.

## Quiz: Design Challenge: Message Alerts

Let's design something for Morgan real quick. Let's tackle the common problem of being alerted when you've received a text message. Here are the constraints on our design for Morgan. It must alert her whether the phone is in her pocket or on the table. It cannot disturb the people around her. [SOUND] And yes, vibrating loudly against the table counts as disturbing the people around her. You're not restricted to just one modality, though, but you are restricted to the sensors that the phone has available.

Here's one possible design. We know that smart phones have cameras and light sensors on them. We can use that to determine where the phone is, and what kind of alert it should trigger. If the sensor detects light, that means the screen is visible, so it might alert her simply by flashing its flashlight or illuminating the screen. If the sensor does not detect light, it would infer that the phone is in her pocket and thus, would vibrate instead. Now, of course, this isn't perfect. It could be in her purse, or she could have put it face down. That's why we iterate on a design like this, to improve it based on the user's experiences.

## Quiz: Memory: Perceptual Store

After the perception portion of this model comes the cognition portion, starting with memory. There are lots of different models of memory out there. For our purposes we're going to talk about three different kinds of memory, the perceptual store or working memory, the short-term memory, and the long term memory. Some scientists argue that there are other types of memory as well, like an intermediate sort of back of the mind memory. But the greatest consensus is around the existence of at least these three kinds.

So let's start with the first, the perceptual store or the working memory. The perceptual store is a very short term memory lasting less than a second. One of the most common models of working memory came from Baddeley and Hitch in 1974. They described it as having three parts. First, there's the visuospatial sketchpad which holds visual information for active manipulation. So for example, picture a pencil. The visuospatial sketchpad is where you're currently seeing that pencil. A second part is the phonological loop. The phonological loop is similar, but for verbal or auditory information. It stores the sounds or speech you've heard recently, such as the sound of me talking to you right now. A third part is the episodic buffer. The episodic buffer takes care of integrating information from the other systems as well as chronological ordering to put things in place. Finally all three of these are coordinated by a central executive.

So let's try an example of this. I'm going to very quickly show you a picture and ask you a question about it. Don't focus on any particular portion of the picture, try to view it as a whole.

What was the score on the scoreboard?

As you can now see, the score was 0 to 0. Now, as you tried to reason over that, what you probably did was picture the image in your mind. That was trying to reason over what was stored in the perceptual buffer, and it decayed very quickly. However, if you're a fan of baseball, you probably had a better chance of getting that right. That's because you have some domain expertise. You're better able to process images about that domain more quickly. You might, for example, have recognized that most of the innings weren't marked. So that increases the odds that the score of the game was pretty low. This idea is actually the foundation of a fascinating study about chess experts versus novices and recognizing the configuration of chess boards. The study found that experts were far better than novices at remembering realistic chess boards that were only flashed for a short period of time, like the one on the left. But experts were no better than novices at remembering random chessboards. So expertise, or rehearsal, delays the decay of the perceptual buffer.

## Quiz: Memory: Short Term and Chunking

When we're designing interfaces, short-term memory is one of our biggest concerns. It's important we avoid requiring the user to keep too much stored in short-term memory at a time. Current research shows that users can really only store four to five chunks of information at a time. For a long time, there was a popular idea that people could store seven, plus or minus two, items in memory at a time. But more recent research suggests that the number is really four to five chunks. There are two principals we need to keep in mind here though. The first, is the idea of chunking. Chunking is grouping together several bits of information into one chunk to remember.

So to illustrate this, let's try it out. I'm about to show you six combinations of letters. Try to memorize them and then enter them into the exercise that pops up. Are you ready? Now to keep you from just rehearsing it in your perceptual store until you can reenter it, I'm going to stall and show you some pictures of my cats.

There's one. There's both of them, and here's my daughter.

Okay, now fill in the words.

So what happened? Well, what likely happened is that you maybe had only a little bit of trouble remembering the two real words that were listed on the right. You might have had some more trouble remembering the two words that were listed in the middle that were fake words, but did nonetheless look like real words. And you probably had a lot of trouble remembering the two series of letters over on the left. Why is all of that? Well, when it came to memorizing these two words, you were just calling up a chunk that you've already had. You didn't see these as arbitrary collections of letters, you just saw them as words. For the ones in the middle, you've never seen those combinations of letters before, but you could pronounce them as if they were words. So you likely saw them as fake words rather than just random collection of letters. For these over the left though, you had to memorize five individual characters. So that's means that while these four were able to jump in the words or pseudo words. These likely had to be remembered as five chunks each. That's makes this much more difficult to remember than these.

## Quiz: Memory: Short Term and Recognition

However, there is a way we can make this easier. So let's ask a different question. Which of these six words did you see in the exercise previously?

Even if you had trouble just naming these series of letters in the exercise previously. You probably were much more successful at this exercise. Why is that? That's because it's far easier to recognize something you know than to recall it independently. And that's a useful take away for us as we design interfaces. We can minimize the memory load on the user by relying more on their ability to recognize things than to recall them.

## Memory: Short Term Takeaways

So what are the implications of short term memory for HCI? We don't want to ask the user to hold too much in memory at a time, four to five chunks is all. Asking the user to hold ten numbers in short term memory, for example, would probably be too much. But we can increase the user's effective short term memory capacity by helping them chunk things.

For example, this is probably by far easier to remember, even though it's the same content. We've shrunk ten items into three. And we've used a format for phone numbers with which you're probably familiar if you're in the United States. If you're from outside the U.S., you might be familiar with a different grouping. But the same principle applies. And finally, when possible, we should leverage recognition over recall. For example, if I ask you to recite the number, maybe you could. In fact, go ahead. Try it.

Whether or not you could do that, you almost certainly, though, can pick it from this list. This is one of the reasons why menu bars and tool strips are so ubiquitous in software design. The user doesn't have to remember the icon for a command or the name of an option. They just have to recognize it when they see it.

## Memory: Long Term Memory

Finally, we have long-term memory. Long-term memory is a seemingly unlimited store of memories, but it's harder to put something into long-term memory, than to put it into short-term memory. In fact, to load something into long-term memory, you generally need to put it into short-term memory several times.

To demonstrate this, I'm going to describe something called lightner system. The lightner system is a way of memorizing key value pairs, or in other words memorizing flashcards. Those can be words and their definitions, countries and their capitals, laws and their formulas, anything where you're given a key and asked to return a value. So I have some flashcards here that have the capitals of the world. What I do is go through each one, read the country, check to see if I remember the capital. And if I do, I'll put it in the pile on the right. I read the country and don't know the capital, I'll put it in the pile on the left. So let me do that real quick. [MUSIC] Now tomorrow, I will just go through the pile on the left. Any that I remember from the pile on the left tomorrow, I'll move to the pile on the right. Any that I still don't remember, will stay in the pile on the left. So I'm focusing my attention on those that I don't yet know. In four days, I'll go through the pile on the right. And any that I don't remember then, I'll move back to my pile on the left, to remind me to go through them each day. So the things that I remember least, are most often loaded in the short-term memory, solidifying them in my long-term memory. Now in practice, you wouldn't just do this with two piles, you'd do a three, or four, or five. And the long restoration pile you'd might only go through yearly, just to see if it's decayed yet.

## Cognition: Learning

Now let's talk a little bit about cognition. One of the most important cognitive processes to consider is learning. When we design interfaces, we are in some ways we are hoping the user has to learn as little as possible to find the interface useful. However, our interfaces should also teach the user over time how to use them most efficiently. We can take PowerPoint as an example of this. Let's pretend this is the first time I've ever used PowerPoint and I want to copy something. This application doesn't assume I know anything yet. If I poke around, I'll find the Copy button under the Edit menu, which is off-screen above the slide.

When I bring up that menu, it also shows the hot key that will allow me to actually copy something. That's helping me to learn to interact with the application more efficiently through hot keys instead of through menus. But yet, it's also not assuming that I already knew that, because I was still able to find this under that menu.

There are two kinds of learning we're most interested in, procedural and declarative. Procedural is how to do something. That can be doing work on a computer, playing sports, playing musical instrument. It's a task in which you're engaged or an activity you are performing, it's something that you do. Declarative learning is knowledge about something. It's what you know in your head. It's what you can answer when asked. So if I asked you, what's the hotkey for paste? I'm asking for a declarative knowledge. If I asked you, paste your clipboard here, I'm asking for procedural knowledge. If you're an expert computer user, you'd probably find it easier to just actually paste your clipboard than to answer me when I say, what's the hotkey for paste? And in all likelihood, when I ask you, what's the hotkey for paste, the way you remember it is you mentally simulate doing it, and then you look at what you simulated yourself doing. What's interesting is that while declarative knowledge is how we generally communicate with one another, procedural knowledge is generally what we do in HCI. When you have strong procedural knowledge, you may forget how you're doing what you're doing, because it's so second nature.

You're unconsciously competent with what you're doing. When you're in that state, it can be difficult to explain to someone who lacks that competence, because you aren't sure what makes you so good at it.

It's difficult to translate your subconscious procedure analogy into explicit declarative knowledge. A declarative knowledge is how we communicate, that's how we communicate with novice users.

This is important, because as the designers of interfaces, we're the experts in our domains. That means we're prone to design things that are easy for us to use but hard for anyone else.

## Cognition: Cognitive Load

To talk about cognitive load, let's think for a moment of the brain like it's a computer. The community is actually divided on whether or not the brain actually operates this way, but for the purposes of this explanation, it's a useful metaphor. So your brain has a certain number of resources available to it, the same way your computer has a certain number of processor resources available to it. Each thing that the brain is working on takes up some of those resources.

Let's say you're at home in a quiet area, working on a calculus problem that requires 60% of your cognitive resources. In that setting, you have plenty of resources to solve that problem.

However, then you go to take a calculus test. Now you have some stress in there. Now you're stressing about the impact this test is going to have on your grade. You're stressing about how well other people seem to think they are doing on it. Whether or not other people seem to be struggling while you struggle. This is taking up a lot of your cognitive resources. Here we see the stress taking up 50% of the cognitive resources you have. Now you don't have sufficient resources to complete the problem successfully. I hypothesize that's why test taking anxiety can have such a negative effect. It takes resources away from actually working on the test. You can apply these same principles to the presence of distractions, anxiety disorders and more. Cognitive load has two major applications to our working design interfaces.

One, we want to reduce the cognitive load posed by the interface, so that the user can focus on the task.

Second, we want to understand the context of what else is going on while users are using our interface. We need to understand what else is competing for the cognitive resources users need to use our interface. If we're designing a GPS or navigation system for example, we want to be aware that the user will have relatively few cognitive resources because they're focusing on so many things at once.

## Quiz: Reflections: Cognitive Load

Let's take a second and reflect on cognitive load. Try to think of a task where you've encountered a high cognitive load. What different things did you have to keep in mind at the same time? And how could an interface have actually helped you with this problem?

Computer programming is one task with an incredibly high cognitive load. At any given time, you're likely holding in working memory your goals for this line of code, your goals for this function, your goals for this portion of the program as a whole, the variables you've created and a lot more. That's why there's so many jokes about how bad it is to interrupt a programmer, because they have so much in working memory that they lose when they transition to another task. But there are ways good IDEs can help mitigate those issues. For example, inline automated error checking is one way to reduce the cognitive load on programmers, because it lets them focus more on what they're trying to accomplish rather than the low level syntax mistakes. In that way, the IDE offloads some of the responsibility from the user to the interface. Now we could phrase that a little bit differently too. We could describe this as distributing the cognitive load more evenly between the different components of the system, myself and the computer. That's a perspective we discuss when we talk about distributed cognition.

## 5 Tips: Reducing Cognitive Load

Here are five quick tips for reducing cognitive load in your interfaces. Number 1, use multiple modalities. Most often, that's going to be both visual and verbal. But when only one system is engaged, it's natural for it to become overloaded while the other one becomes bored. So describe things verbally and also present them visually. Number 2, let the modalities complement each other.

Some people will take that first tip and use it as justification to present different content of the two modalities. That actually increases cognitive load because the user has to try to process two things at once, as you just noticed when Amanda put something irrelevant up while I said that.

Instead, focus on letting each modality support, illustrate or explain the other, instead of competing with the other.

Number 3, give the user control of the pace. That's more pertinent in educational applications of cognitive load, but oftentimes interfaces have built-in timers on things like menus disappearing or selections needing to be made. That dictates the pace, induces stress, and it raises cognitive load. Instead, let the user control the pace. Number 4, emphasize essential content and minimize clutter. The principal of discoverability says we want the user to be able to find the functions available to them, but that could also raise cognitive load if we just give users a list of 500 different options. To alleviate that, we can design our interfaces in a way that emphasizes the most common actions, while still giving access to the full range of possible options. Number 5, offload tasks. Look closely at what the user has to do or remember at every stage of the interface's operation. And ask if you can offload part of that task on to the interface. For example, if a user needs to remember something that they entered on a previous screen, show them what they entered. If there's a task they need to do manually, see if you can trigger it automatically.

## Motor System

So our user has received some input. It's entered her memory, she cognitively processed it. Now it's time to act in the world in response. In designing interfaces, we're also interested in what is physically possible for users to do. This includes things like, how fast they can move, or how precisely they can click or tap on something.

For example, here are two versions of the Spotify control widget that appears on Android phones. On the left is the version that's available in the tray of the phone that you can access at any given time by swiping down on the phone screen. And on the right is the version that appears on the lock screen when you turn on a locked phone while it's playing music. In each case, the X closes the app, which is consistent with a lot of other applications. The forward, back and pause buttons are similarly consistent with their usual meanings. I don't actually know what the plus sign here does. It's doesn't have a clear mapping to some underlying function. Now note on the left, we have the close button, in the top right corner. It's far away from anything else in the widget. On the right, the close button is right beside the skip button. I can speak from considerable personal experience, and say that the level of specificity or the level of precision required to tap that X, instead of tapping the skip button, is pretty significant. Especially if you're using this while running or driving, or anything besides just sitting there, interacting directly with your phone. The precision of the user's ability to tap on a button is significantly reduced in those situations. And in this case, that can lead to the quick error of closing the application when all you're trying to do is skip forward to the next song. This isn't an error in the perception of the screen. It's not an error in their memory of the controls. They're not thinking that the X button actually is the skip button. This is just an error in what they're physically able to perform at a given time. The interface relies on more precision than they would have in many circumstances. So this design doesn't take into consideration the motor system of the user or the full context surrounding usage of this application. This isn't as significant in the design on the left, because there's more room around that close button. If I aim for the forward button and miss, the worst that's going to happen is I might pause it. I'm not going to close it by accident. This is one example of how we need to be aware of the constraints on the user's motor system. What they can physically do, how precise or accurate they can be, and so on. And we have to be aware of that in the context where the application is going to be used as well. These buttons are no smaller than the keys on a smart phone keyboard but we expect more specificity when they're sitting there typing with their thumbs, as opposed to reaching over and interacting real quick on something on the lock screen. Now of course, there might be other constraints around this. There might be a reason why this button's placed there. There might be some constraint in the Android system that doesn't let them use more than one row of the lock screen. In that case, we would need to make our interface more tolerant of errors. Maybe require a double tap to close the app, or maybe we mute it when it's pressed and then gives the user five seconds to confirm that that's actually what they want to do. Those are ways of reducing the penalty for errors.

## Exploring HCI: Human Abilities

We've talked a lot about different human abilities in this lesson. Depending on the demand you chose, the human abilities in which you're interested, may vary dramatically. If you looking at gestural interfaces or wearable devices than the limitations of the human motor system might be very important. On the other hand, if you're interested in educational technology, you're likely more interested in some of the cognitive issues surrounding designing technology. For virtual reality, you're main concern will likely be perception. Although, there are interesting open questions about how we physically interact with virtual reality as well. So take a few moments and reflect on what the limitations of human ability are in the domain of HCI that you chose to explore.

## Conclusion to Human Abilities

Today, we've gone through a crash course on human abilities and perception. We started off by talking about the main ways people perceive the world around them through sight, sound and touch.

Then we discussed some of the components of cognition, especially memory and learning.

Then we discussed the motor system, how the person then interacts with the world around them. In this single lesson, we've only scratched the surface of human perception. There are entire courses, even entire degree programs, that focus on these principles. We'll give you some suggestions on some of the notes. So don't think we've given you a full view of the field. Instead, we hope we've given you just enough to start to keep human abilities in mind, and enough to know what to research as you start to learn to design interfaces.
