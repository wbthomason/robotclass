---
layout: post
title: "the course"
date: 2014-08-23 13:47:23 -0400
comments: true
description: "Intro to the course"
author: Wil
categories: [lecture, intro]
---

Welcome to ENGR 1501: Introduction to Aerial Robotics. This post will go over the course's objectives, expectations, and structure, discuss some motivations for studying robotics, and give a brief overview of the structure of the quadcopter we'll be building in the first few weeks. We'll get started with the syllabus.

<!--more-->

### Syllabus
The syllabus can be found [here](http://1drv.ms/1BhxqNa); this will be where the most up to date version lives throughout the semester. Aside from the topic listing, which we'll discuss later, the most important parts of the syllabus can be summed up as follows:

* **Intent of the course:** To provide students with a basic survey of modern robotics, in hopes of sparking interest in the field.
* **Structure of the course:** Biweekly meetings on Tuesdays, which will typically consist of a short review of the week's material followed by time to work construction/modification of the quadrotor. The exact balance of these components will vary by week as necessary.
* **Course requirements:** No textbook, but some programming experience - preferably in C/C++, preferably dealing with embedded hardware - is required. Any prior experience with robotics is welcomed, although students with such experience are cautioned that this is very much an introductory course.
* **Course grading:** The course is graded Pass/Fail, with grades being calculated as follows: 20% from a quiz on the week's material, given at the beginning of each class meeting, the remaining 80% from the successful completion of the quadrotor project, and a possible 10% bonus for participating in the final obstacle course challenge (assuming that this happens).

### Topics
The course will go over a fairly wide range of topics. Despite the relatively short period of time we have to cover this material, this approach was chosen over a deeper focus on a smaller topic set because of the intended nature of the course as a survey of the field. However, if any students are interested in going more in depth into any of the topics covered/related topics, I'm more than willing to accommodate - to the point of changing the schedule/syllabus if there's interest from a sufficient proportion of the students.

After this week's administrivia and discussion of reasons for studying robotics, we'll dive right into the course proper. The general arc of topics moves somewhat from lower to higher level concepts, starting with control theory and kinematics, moving through subjects in artificial intelligence, and finishing with investigation of one of the most important problems in robotics (SLAM) and a section on computer vision. Another way to consider the organization of the course is in terms of loosely growing "knowledge" of the world possessed by the studied systems. We start by learning about actuators and systems that create a change in the physical world, but don't know much about the world by themselves, move into means of reasoning about state, and wrap up by finally fully incorporating information about the world, gathered through sensors and processed through the aforementioned reasoning techniques, into .
