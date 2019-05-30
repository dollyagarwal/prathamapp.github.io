---
layout: post
title: Assess the developmental needs of the individual child
subtitle: develop a tool to understand children's reactions & comprehension while watching videos
tags: [vision, emotion detection, facial recognition]
---


**Objective:** To analyse child’s comprehension to the video course content

**Concept:** To develop a tool to understand how children are responding/comprehending to the course video content they watch

**Issues addressed:** "No two children are the same". Some learn quickly; others are slow. How do we assess the developmental needs of the individual children? The Pradigi App provides learning content in the form of videos and games which are same for every children. We need to find ways to make learning "relevant, authentic, and valuable" in a child’s lives. This can be done if we can interpret comprehension level of students to the same video by analysing their non-verbal communication like facial expressions etc.

**Tech Needs:**

<table>
  <tr>
    <td>Projects</td>
    <td>Know-how</td>
    <td>Status</td>
  </tr>
  <tr>
    <td>Project Conceptualization - which non-verbal cues to look for to understand a child’s response/comprehension to a video content and what should be the labels</td>
    <td>Non-Verbal Communication Expert</td>
    <td>Not Started</td>
  </tr>
  <tr>
    <td>An android app to collect labeled dataset to be used for testing and training the ML model</td>
    <td>Android Development</td>
    <td>Not Started</td>
  </tr>
  <tr>
    <td>Feature Engineering: Video sample filtering (if required) to transform in a format that can be used to train the ML model</td>
    <td>Video processing</td>
    <td>Not Started</td>
  </tr>
  <tr>
    <td>Develop and test ML Model to take filtered video samples and corresponding labels as input and predict the non-verbal cues and predict the comprehension level of the child to a particular video content</td>
    <td>Machine Learning and Deep Learning Algorithms</td>
    <td>Not Started</td>
  </tr>
  <tr>
    <td>Conceptualize and integrate the designed ML model within our PraDigi app (Deployment)</td>
    <td>Android Development</td>
    <td>Not Started</td>
  </tr>
</table>


**Details:**
Facial expression is the most frequently used nonverbal communication mode by the children and facial expressions of the students are significantly correlated to their emotions which helps to recognize their comprehension towards the course content. Student’s facial expressions can be used as a valuable source of feedback.  It can be used to determine whether or not to slow down, speed up, or in some other way modify the presentation of content. Recognition of emotions from facial expressions involves the task of categorizing active and spontaneous facial expressions to extract information about the underlying emotional states. Momentary expressions that signal emotions include muscle movements such as raising the eyebrows, wrinkling the forehead, rolling the eyes or curling the lip. When students are feeling uncomfortable, they may have lowered brow, drawn together brow, horizontal or vertical forehead wrinkles, and have a hard time in maintaining eye contact.

We need a tool which can evaluate these facial expressions to understand how the child is comprehending to the content they are viewing. This will help us implement TaRL (Teaching at the Right Level) by recommending content according to their comprehension level.

Source: [https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3795200/](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3795200/)
