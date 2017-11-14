---
layout: post
title:  "Josh Beauregard's Mob Programming Guidelines"
date:   2017-11-14 14:00
categories: extreme programming, mobbing
---

# Mob Programming Basics

> "All the brilliant minds working together on the same thing, at the same time, in the same space, and at the same computer"
- Woody Zuil http://mobprogramming.org/

## Goals

* Get the task at hand done
* Create knowledge redundancy accoss WIP and finished work.
* Bring skillets together to create stronger everything:
  * Engeneers who mob generally have a greater undestaning of all the parts.
  * Product owners who mob have a greater understanding of feature pain points.
  * Mobbed code is genreally less error prone due to multiple eyes.
* Reduced need for code review process as it's is combined into the dev session.

## Roles.

* __Navigator__: The person dictating the logic. The only one talking. A required participant in Koans sessions.
* __Driver__: The person at the keyboard. This person does not need any technical knowledge just willingness to type. A required participant
* __The Moberator__: The facilitator of the mob. Organizes location and topics. Looks out for the welfare of the participants, keeps time. Required for beginning the mobbing process but good to have all the time. This can be a rotating hat.
* __The Product/Task Owner__: This person sets the goals of the session and can provide guidance. An optional participant.
* __Researcher__: A person dedicated to serching for answers as the mob works. Mobbers can ask them to do technical research or other communcation durring a session so that the mobbers can focus on the code.
* __The Mob__: Every one else in the room. The will be present and preparing to navigate. Listening and being ready to correct or enhance the code to spec.
Researching or helping the Navigator figure things out by:
  * Researching API's.
  * Guiding whiteboards
  * Providing technical knowledge.
Required participants.
* __Auditors__: Observers learning and absorbing.

## Guidelines

* Have a spec to work to. 
* No talking when your not the _Navigator_ unless invited or if you are a _Product Owner_ you can can inforce the needs of the product.
* Set a time limit on Navigating and Driving. 4 Mins is a good amount of time. After the alarm goes off let the navigator finish their thought. (A few timers are in the tools section bellow.)
* Let people be wrong. In 4 mins no one will lead the project too off course from a technical stand point. They seeing where you went wrong is a very strong way to enforce learning.
* Not all Drivers have to Navigate.

### Navigator Directive guidelines.

When giving directions it is best to start with your intent over syntax. It is a lot easier for a Driver to drive when they know why something to happen.

Navigating with "To reduce cruft. search and replace all instances of foo with bar". This gives the diver more freedom than. "type, colon, percentage sign, slash, foo, slash, bar, slash, g enter".

So start your directives with Intent and let the driver tell you that he does no know how.

## Josh's single inflexable Rule

* NO DELETING. Replace to spec. This is a hurt managment rule. It is better to explain why somehing need to be replaced than to tell people they they were wrong and all their efforts need to be deleted.

## Planning the event.

All participants other then auditors need to have:
__Either__
* Access to a work station capable of editing and testing the software.
* A git client
* Read Write Access to the code repository/branch worked on.
* A fave texteditor

__Or__
 
The ability to share a workspace set up for that.

## Mob event invites should include:

* A repo for people to pre clone.
* Goals for the session.
* Links to relevant documentation.
* Any extra tools needed to take part as defiend but the _Moberator_ or _Product Owner_

## Tools
### Workspace sharing.
* Skype
* Screenhero
* Zoom <- Perfered by me

### White-boarding.
hackpad.net

### Retros:

https://www.pointingpoker.com/Retro

### Timers
http://oss.jahed.io/agility/timer.html
http://www.online-stopwatch.com/countdown-timer/
https://github.com/MobProgramming/MobTimer.Python
https://atom.io/packages/mob-timer
