---
layout: post
title:  "Josh Beauregard's Mob Programming Guidelines"
date:   2017-11-14 14:00
categories: extreme programming, mobbing
---

# Mob Programming Basics

> &quot;All the brilliant minds working together on the same thing, at the same time, in the same space, and at the same computer&quot;

&mdash; Woody Zuil ( [http://mobprogramming.org/](http://mobprogramming.org/))

This is basically _Strong Style_ Pairing with more than a pair.

## Goals

* Get the task at hand done
* Create knowledge redundancy across WIP and finished work.
* Bring skillets together to create stronger everything:
  * Engineers who mob generally have a greater understanding of all the parts.
  * Product owners who mob have a greater understanding of feature pain points.
  * Mobbed code is generally less error prone due to multiple eyes.
* Reduced need for code review process as it&#39;s is combined into the dev session.

## Roles.

* **Navigator**: The person dictating the logic. The only one talking. A required participant in Koans sessions and young teams. In advanced teams this may become the entire mob not just a single person.
* Driver: The person at the keyboard. This person does not need any technical knowledge just willingness to type. This hat will rotate through people throughout the session.
* **The Moberator** : The facilitator of the mob. Organizes location and topics. Looks out for the welfare of the participants, keeps time. Required for beginning the mobbing process but good to have all the time. This can be a rotating hat.
* **The Product/Task Owner** : This person sets the goals of the session and can provide guidance. An optional participant.
* **Researcher** : A person dedicated to searching for answers as the mob works. Mobbers can ask them to do technical research or other communication during a session so that the mobbers can focus on the code.
* **The Mob** : Everyone else in the room. The will be present and preparing to navigate. Listening and being ready to correct or enhance the code to spec. Researching or helping the Navigator figure things out by:
  * Researching API&#39;s.
  * Guiding whiteboards \* providing technical knowledge.
* **Auditors** : Observers learning and absorbing.

## General Guidelines

* Have a spec to work to.
* No talking when you are not the _Navigator_ unless invited or if you are a _Product Owner_ you can enforce the needs of the product.
* Set a time limit on Navigating and Driving. 4 Mins is a good amount of time. After the alarm goes off let the navigator finish their thought. (A few timers are in the tools section bellow.)
* Let people be wrong. In 4 minutes no one will lead the project too off course from a technical stand point. They seeing where you went wrong is a very strong way to enforce learning.
* Not all Drivers have to Navigate.

### Talking to the Driver.

**Intent -&gt; Technical -&gt; Dictation**

When giving directions it is best to start with your intent over syntax. Drivers may have other methods of achieving the same result then the navigator and it is better for them to use the process that they are familiar with rather than having to relearn on the fly how to use an IDE or syntax for a process.

A sentence with &quot;In Order to, do a task, please do this&quot; is a great starting point.

If the navigator hesitates or asks how, provide them with a technical hint, such as a function or method that they want to use.

If there is still hesitation on the Drivers part, then a Navigator can feel free to dictate key strokes.

#### Sample diolog

__Intent__

&quot;We need to create a conditional based on whether or not foo equals bar.&quot;

__Technical__

&quot;Create an _if_ block with the argument being foo equals bar.&quot;

__Dictated__

Please type if. Open parentheses. Variable foo, double equal signs. Space in quotes, bar. ....

## Pain Management

* **NO DELETING**. Replace to spec. This is a participant pain management rule. It is better to explain why something need to be replaced than to just tell people that they were wrong and all their efforts need to be deleted.

### Planning the event.

All participants need the ability to share a development workspace including keyboard and mouse control.

## Mob event invites should include:

* A repo for people to pre clone and get familiar with.
* Goals/Stories for the session.
* Links to relevant documentation.
* Any extra tools needed to take part as defined but the _Moberator_ or _Product Owner_

## Good starting stories for team building.

Pair Programming can be awkward at first. Trying to working on new features can be to much pressure for a new pair to work in. 
The bellow items are good for rapid rapport building between developers.

* Code Koans
* Refactoring
* Test engineering
* Pseudo Coding


## Tools

### Workspace sharing.
* Skype
* Slack
* Zoom (Zoom.us) &lt;* Preferred by me

### White-boarding.

* hackpad.net

### Retros:

https://www.pointingpoker.com/Retro
* [http://funretro.github.io](Fun Retro)


### Timers

* [http://oss.jahed.io/agility/timer.html](http://oss.jahed.io/agility/timer.html)
* [http://www.online-stopwatch.com/countdown-timer/](http://www.online-stopwatch.com/countdown-timer/)
* [https://github.com/MobProgramming/MobTimer.Python](https://github.com/MobProgramming/MobTimer.Python)
* [https://atom.io/packages/mob-timer](https://atom.io/packages/mob-timer)
