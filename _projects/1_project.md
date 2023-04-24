---
layout: page
title: Dialogue Agent Consistency Evaluation
description: Evaluating chatbot language models
img: /assets/img/dance.png
importance: 1
category: masters
# github: https://github.com/echodarkstar/cs538-project
---

This work was done as a course project for Stony Brook University's CSE 538 Natural Language Processing, Fall 19. The motivation behind this project was to understand where persona based chatbots could go wrong while interacting with a user. We wanted to do this quantitatively, running multiple trial episodes.

####  Abstract:

Persona based neural conversational models are important in the world of chatbots and to test the consistency of such models is integral for them being performant. We present an automated mechanism to detect the breaking point of such models, specifically targeting “TransferTransfo” (Wolf et al., 2019b). Natural language inference is used to calculate a metric stating the average number of utterances required to break a persona based model. An extensive comparison between and random-sequenced-inputs and personality-sentences-permuted-inputs has been performed.

<a href="{{ site.baseurl }}/assets/pdf/dance.pdf">Project Report</a>

<a href="https://github.com/echodarkstar/cs538-project">Code</a>

<img  style="height:75%;width:75%;display:block;margin-left:auto;margin-right:auto;" src="{{ site.baseurl }}/assets/img/dance1.png" alt="" title="framework"/>
<img style="display:block;margin-left:auto;margin-right:auto;" src="{{ site.baseurl }}/assets/img/dance2.png" alt="" title="finetuning"/>

