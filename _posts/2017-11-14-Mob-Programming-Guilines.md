---
layout: post
title:  "Josh Beauregard's Mob Programming Guidelines"
date:   2017-11-14 14:00
categories: extreme programming, mobbing
---

# Mob Programming Basics

> "All the brilliant minds working together on the same thing, at the same time, in the same space, and at the same computer"
- Woody Zuil (http://mobprogramming.org/)

This is basically _Strong Style_ Pairing with more then a pair.

## Goals

* Get the task at hand done
* Create knowledge redundancy accoss WIP and finished work.
* Bring skillets together to create stronger everything:
  * Engeneers who mob generally have a greater undestaning of all the parts.
  * Product owners who mob have a greater understanding of feature pain points.
  * Mobbed code is genreally less error prone due to multiple eyes.
* Reduced need for code review process as it's is combined into the dev session.

## Roles.

* __Navigator__: The person dictating the logic. The only one talking. A required participant in Koans sessions and young teams. In advanced teams this may become the entire mob not just a single person.
* __Driver__: The person at the keyboard. This person does not need any technical knowledge just willingness to type. This hat will rotate through people through out the session.
* __The Moberator__: The facilitator of the mob. Organizes location and topics. Looks out for the welfare of the participants, keeps time. Required for beginning the mobbing process but good to have all the time. This can be a rotating hat.
* __The Product/Task Owner__: This person sets the goals of the session and can provide guidance. An optional participant.
* __Researcher__: A person dedicated to serching for answers as the mob works. Mobbers can ask them to do technical research or other communcation durring a session so that the mobbers can focus on the code.
* __The Mob__: Everyone else in the room. The will be present and preparing to navigate. Listening and being ready to correct or enhance the code to spec.
Researching or helping the Navigator figure things out by:
  * Researching API's.
  * Guiding whiteboards
  * Providing technical knowledge.
* __Auditors__: Observers learning and absorbing.

## General Guidelines

* Have a spec to work to. 
* No talking when your not the _Navigator_ unless invited or if you are a _Product Owner_ you can can inforce the needs of the product.
* Set a time limit on Navigating and Driving. 4 Mins is a good amount of time. After the alarm goes off let the navigator finish their thought. (A few timers are in the tools section bellow.)
* Let people be wrong. In 4 mins no one will lead the project too off course from a technical stand point. They seeing where you went wrong is a very strong way to enforce learning.
* Not all Drivers have to Navigate.

### Navagation guide lines.

__Intent -> Technical -> Dictation__

When giving directions it is best to start with your intent over syntax. Drivers may have other methods of achaving the same result then the navigator and it is beter for them to use the process that they are fimilier with rather then having to relean on the fly how to use an IDE or syxtax for a process.

A sentence with "In Order to, do a task, please do this" is a great starting point.

If the navigaotr hesitates or asks how, provide them with a technical hint, such as a function or method that they want to use.

If there is is still hesitation on the Drivers part, then a Navigator can feel free to dictate key strokes.

#### Sample diolog

__Intent__
> We need to create a condtional based on whether or not foo equals bar.

__Technical__
> Create an _if_ block with the argument being foo equals bar.

__Dictated__
> Please type if. Open prenethises. Variable foo, double equal signs. Space in quotes , bar. ....

## Josh's single inflexable Rule

* NO DELETING. Replace to spec. This is a pain managment rule. It is better to explain why somehing need to be replaced than to tell people they they were wrong and all their efforts need to be deleted.

## Planning the event.

All participants need the ability to share a development workspace includeing keyboard and mouse control.

## Mob event invites should include:

* A repo for people to pre clone and get firmillier with.
* Goals/Stories for the session.
* Links to relevant documentation.
* Any extra tools needed to take part as defiend but the _Moberator_ or _Product Owner_

## Good starting stories for team building.
* Code koans
* Refactoring
* Test engneering.

## Tools
### Workspace sharing.
* Skype
* Slack
* Zoom (Zoom.us) <- Perfered by me

### White-boarding.
hackpad.net

### Retros:

https://www.pointingpoker.com/Retro

### Timers
http://oss.jahed.io/agility/timer.html
http://www.online-stopwatch.com/countdown-timer/
https://github.com/MobProgramming/MobTimer.Python
https://atom.io/packages/mob-timer
