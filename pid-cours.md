---
title: How PID control work
description: A dive into PID control with great exemple
date: '2023-11-27'
categories:
    - cours
    - english
published: true
---

## Summary
1. Definition of PID
    - What does it mean
    - What does it do
    - What can it be used for
2. Use case
    - PID formula
    - Example
    - Limitation
3. PID integration into ESP32 COOP
    - How to adapt 
    - How to integrate flexibility

## Definition of PID
### What does it mean

By now you certainly know what it means: **P**roportional, **I**ntegral, and **D**erivative. <br>In other words, it is a mathematical formula to reach a goal in the perfect way. It could be adjusting to the best temperature or making a motor stop at the right place. But with only this knowledge, we won't go very far.

### What does it do

PID 