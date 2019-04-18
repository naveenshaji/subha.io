---
title: 'Elevating employee productivity in the workplace'
subtitle: 'UX Research and Design'
date: 2019-02-30 00:00:00
featured_image: '/images/productivity_00.jpg'
---

![](/images/productivity_00.jpg)

---

## Introduction

Productivity is to the modern world, what enlightenment was to the 18th century. Modern man is on a never-ending quest to improve productivity and get ahead of the game. Technology brought with it avenues for improving various aspects of livelihood -- this made sure that physiological, safety, belonging, and esteem needs were taken care of for a wide majority of people. However, productivity was a product of self- actualization more than any of these, and Maslow was right -- the quest that ensued was one for self-actualization more than anything else.

What can we as designers do about it? Accepting that productivity is a user goal while designing for the user is a start. Augmented Reality workspaces sure sound like the next big step towards amplifying user productivity, however, it's the small changes in things used by large amounts of people that make the most impact.

---

## Problem Statement

_How might we improve productivity for users in the workplace?_

While plotting this on the Abstraction Ladder, or a Why-How line, it was found to be more towards the strategic side. Taking it down a notch to the 'How' side gives us something a bit more tactical that we can ultimately work with.

---

_How might we help users get things done at the right time?_

Even though the workplace bit has been left out, the productivity in the workplace is a factor of what a person does throughout their day, and therefore helping users get things done will have a positive role in their physiological state and workplace productivity.

> "It's crucial to frame the problem just right. A great problem statement needs to be strategic and tactical at the same time."


---

## Secondary Research

General principles for increasing productivity in the workplace, not specific to digital platforms were collected and analyzed. Some of the key takeaways were:

* Limiting time spent on certain tasks.
* Using commute time to plan events for the rest of the day. Having clear cut tasks for a certain day that must be accomplished.
* Limiting Multitasking.
* Taking care of the bigger tasks when you’re most alert.

Studies show that humans are more efficient and alert during certain times of the day. The internal clock mechanism that we possess is called the circadian rhythm. This rhythm is different for each person and governs how alert we are at any given time. We are most productive during highly alert periods.
The bigger tasks, if identified, should ideally be tackled during this phase.

Most people set reminders on their phones only to have it bothering them when they least expect it. All people don’t live by a fixed time schedule. They go about their own lives, some with rigid, and some with more flexible time schedules.

Time becomes unreliable in cases like this. Location is found to be an alternative that links people to things that they need to be reminded about.

> "For example - I want to be reminded to meet my boss when I get in at work next morning. There was some traffic the next morning, and I ran late. This caused the remainder that I had set to go off while I was stuck in commute and watching a YouTube video. I promptly dismissed it, and ended up forgetting about the meeting."

This would not happen if instead of time, location was also a feature that could trigger reminders.

---

## Persona Hypothesis

The Personas were chosen to be some of the more extreme users -- this was done so that it encompasses the entire spectrum of user experience levels and usage.

#### Priya

Priya is an introvert and likes everything around her to be in her control. She often feels uneasy in a social situation when she feels like she is not the one in control. She likes setting deadlines for every task and is focused on productivity. She reads during her free time and often loses herself in the activity. She has a small pocket diary where she puts down important notes and dates that she has to remember.

#### Murali

Murali loves adventures and the outdoors. A very easy-going and friendly person. He loves to watch Netflix and eat pizza after work every day. He goes out with his friends quite often. Recently he's been getting poor performance reviews at work and he is looking to get things back under control and improve his productivity. He is quite tech-savvy and loves tinkering with stuff.

---

## Ideation

With a problem statement in place, it's time for brainstorming and ideation.

> "I followed a divergent thinking pattern with an 'all-ideas-go-on-the-wall' policy. This promotes creativity in thinking without constraints."

The wildest ideas are welcome at this point.

The goal was to get as many ideas out there as possible and to map this out on an affinity diagram.

Thinking tools like brain writing and lateral thinking were employed in generating ideas creatively.

![](/images/productivity_2.jpg)

---

## Validation Framework

Once the ideas were clustered into an affinity diagram, more convergent thinking methods like the importance-feasibility matrix were used to focus on one area and then narrow it down to a few solutions that were feasible.

---

## The Solution Scope

The scope sets in stone what ideation has led to, and serves to keep context while moving forward on to the Information Architecture and User Flows.
The app runs on iOS and Android and helps the users manage their To Do list effectively and efficiently by recommending personalized tasks based on key research findings.

- Highlight work tasks during work hours
- Identify productive hours based on usage
- Use ML to predict and identify difficult tasks or tasks that don't get done on time
- Recommend difficult tasks during productive hours
- Confine work tasks to work hours mostly to preserve work-life balance
- Accommodate the paradox of choice by limiting the number of tasks that are highlighted at one time
- Integrate with other services like e-mail, GitHub, Slack, and Calendar to provide a cohesive experience.
- Location based reminders to remind when the user is near a location. This is helpful for things like shopping lists

#### Circadian Rhythm Detection

As pointed out in Secondary Research Insights, the human circadian rhythm governs the more and less productive hours in a person’s day. Machine Learning algorithms have been trained to detect the exact part of a person’s sleep cycle to better optimise services for that person.

This is implemented here in re-ordering the tasks according to the time of day and location. Based on completion of tasks, it is possible to gauge an approximation of the circadian rhythm of a person, and hence help recommend appropriate tasks for the time of day.
More difficult tasks are the ones which stay around, and don’t get completed for a long while, or beyond the deadline.

---

## Information Architecture

The different data structures were categorized based on a quick card sorting user study. The information architecture was drawn up based on this.

![](/images/productivity_3.jpg)

---

## Wireframing

After a few iterations, the wireframes on paper were finalized. These were very low fidelity and dealt mostly with how data was presented.

---

## Visual Design Patterns and Guidelines

Having consistent design guidelines in place is always important. 

> "I put together a quick style guide before starting out designing the surface of the app. I’ve used a Fibonacci series to define the font sizes, as well as, the layout spacing."

This ensures a highly consistent design experience.

![](/images/productivity_4.jpg)

---

## Inclusive Design - Accessibility Guidelines

The Web Content Accessibility Guidelines (WCAG) 2.0 covers a wide range of recommendations for making Web content more accessible. Compliance with the Guidelines makes content accessible to a wider range of people with disabilities, including blindness and low vision, deafness and hearing loss, learning disabilities, cognitive limitations, limited movement, speech disabilities, photosensitivity and combinations of these.

> "Accessibility was a major factor during the entire visual design phase, and most design decisions have been taken keeping accessibility in mind."

The Visual Design of this app including all aspects of the UI and color palette conform to at least AA on the WCAG 2.0 Specifications.

--- 

## User Flows

![](/images/productivity_1.jpg)

---

## Usability Testing

The mockups were linked together to create prototypes, these were then tested by a few users. This revealed key insights which helped create user journey maps for the persona that we had.

---

## User Journey Mapping

![](/images/productivity_5.jpg)

---

## Insights

There were a few key takeaways from the journey maps that were created.

Priya sometimes likes having the flexibility of quickly noting down something while she is reading. She doesn’t want to be distracted from the reading experience. The app required too many steps to add a simple reminder and that distracted her to the point that she would not want to use the app.

The current system does not indicate how many tasks or reminders are remaining for the current day. This made Priya open up all the tasks for the day every time she checked the app which essentially ruined the point of the recommender system we have in place.

The current system of adding an email as a reminder worked very well for Priya. She was quite happy with the experience.

Many times when Priya opened the add screen she wanted to type down the task that was in her mind first before creating a category for it. This was frustrating as the app only allowed for selecting/creating a category before saving the current task.

---

## Refinements

Based on the takeaways from the usability testing and journey mapping, some of the flows were iterated with usability as the driving factor.

#### Geo-Tagging

Geo-tagging for tasks was now added. This is a neat little feature that reminds you when you are near the tagged location. This is especially helpful when you don’t know when you’re going to reach somewhere and what to have the app remind you when you’re about to reach instead of the remainder going off at a predestined time.

#### Linearized Flow

The entire add-task flow has been redesigned from the ground- up. Instead of having multiple options after tapping the add button, now it’s a linear flow which can be used to add multiple tasks one after the other with the return key while choosing to add extra information like subtasks/notes/location optionally. This provides for a more refined experience with an emphasised focus on quickly and easily adding something that comes to your mind.

#### Elimination

Elements that complicate the workflow with very small returns were eliminated to create a more focussed experience for the users with only one main flow. This has been done after understanding the simplistic mental model users have of a To Do list.

The monthly view did not need emphasis and was one of the least used features during the testing. This has been shortened to a calendar icon and placed next to the search instead.

Separate pages to view full lists were cumbersome as can been seen from the insights in the journey map. This was eliminated in favour of a simple list with category dropdowns to choose categories.

---

## Updated User Flows

![](/images/productivity_1.jpg)