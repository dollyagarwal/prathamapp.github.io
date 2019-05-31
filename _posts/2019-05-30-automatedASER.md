---
layout: post
title: Automated Diagnostic Tool to measure ASER level
subtitle: Developing a ML model trained on ASER data to be used as a standalone testing tool and as a part of adaptive learning solutions
tags: [speech,test,deep learning]
comments: true
---

**Objective:** Create an automated diagnostic tool to measure ASER level of children.

**Concept:** Developing a ML model that would be trained on ASER data and then be utilized as a standalone testing tool and as a part of adaptive learning solutions for basic numeracy and literacy in English and Indic languages.

**Issues addressed:** Oral evaluation is considered the most effective approach right now for basic literacy and spoken fluency. The need of trained evaluators for the same, puts a limit on the number of children that can be evaluated. Without a diagnostic evaluation it is difficult for teachers to provide learning content according to the child’s level.

**Tech Needs:**

<table>
  <tr>
    <td>Projects</td>
    <td>Know-how</td>
    <td>Status</td>
  </tr>
  <tr>
    <td>An android app to collect labeled dataset to be used for testing and training the ML model</td>
    <td>Android Development</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>Audio sample filtering - remove background noise and speaker diarization to extract only child’s voice</td>
    <td>Audio-signal processing</td>
    <td>In-Progress</td>
  </tr>
  <tr>
    <td>Develop and test ML Model to take filtered audio samples and corresponding questions/text and labels (no. of mistakes and proficiency-level)  as input and predict proficiency level</td>
    <td>Machine Learning and Deep Learning Algorithms</td>
    <td>Not Started</td>
  </tr>
  <tr>
    <td>Conceptualize and integrate the designed ML model with an Android app (Deployment)</td>
    <td>Android Development</td>
    <td>Not Started</td>
  </tr>
</table>


**Details:** We are moving to the era of self and group learning; an automated assessment tools would be imperative to drive the motivation and check learning outcomes.

The model will consume audio samples of a child and predict his/her basic numeracy and literacy level. A child can be classified in any of the 5 Reading levels(Beginner, Letter level, word level, short paragraph level, story level)  and 5 Numeracy levels (Beginner, Single Number recognition(0-9), Double Number recognition(11-99), two digits number subtraction with borrowing, three digit number division by one digit number)
For this classification, the features used will be pronunciation correctness, speaking rate, and fluency and calculation correctness for Math problems:

●	Text/pronunciation mistakes (analyzed through speech to text recognition)

●	No. of pauses and length of pause (analyzed through audio signal processing)

●	Calculation mistakes (for Math problems)

Growing on the initial understanding of reading fluency, we hope to create oral assessment tools for science, humanities, communication skills and more. Moreover, we can recognise children’s strengths and weaknesses and plan their courses accordingly.

**Progress:** An Android app has been designed to collect human evaluated training data. This app is being used in different villages of India (Maharashtra, Uttar Pradesh and Rajasthan) to collect audio samples of children reading out different levels of text (letter, word, paragraph and story), numbers (two digit, single digit) and solution to basic numeric problems(subtraction and division) along with the proficiency level marked by the evaluator.
