---
layout: content
data: line-chart
title: How to read a line chart
isHome: true
keywords: line chart, time series, rate
---

# {{ page.title }}

## What is a line chart?

Line charts are one of the most commonly used chart types. A line chart is most often used to show how something changes over time, like the population of New Zealand. You may have heard this type of data or chart called a 'time series'.

https://figure.nz/chart/lEJCQOvLUEVdohvs

For this type of chart, the x-axis (that's the horizontal one) will show time. It could be seconds, days, months, years, or even something like days since a certain event/threshold. 

The y-axis (the vertical one) shows the thing you are measuring, like the number of people in New Zealand. There are a few different types of measurements you'll often see for this.

## Types of measures

1. Counts

This is how many of a thing there are, like people, or dogs, or cars imported. A line chart using counts shows you whether the number of something is increasing or decreasing over time.

2. Measures

These are measurements of something, like height, weight, volume, temperature, speed. A line chart using measures shows you how the attribute you are measuring changes over time, like charting your height each month.

3. Proportions or Percentages

A propotion or percentage tells you how much something is compared to the total amount, like the proportion of women who are CEOs. A line chart using proportions or percentages helps us understand whether an increase or decrease over time in our count or meausre changes the relationship that has to the total number. 

If we look at our CEO example, if 5 new women are hired as CEOs, and no new men are hired, our proportion of women CEOs increases. But if lots of men were hired too, our proportion may not increase.

4. Rates

A rate is a measure of how often something happens, also called 'frequency'. A rate can either be:

- The frequency that something happens over a specific interval of time. For example a rate of 30 km per hour.
- The frequency that something happens in a particular group or population. For example, the rate of breast cancer in New Zealand is 1 in 2,118 for women and people with breasts in their 20s.

Statistics like population mortality rates are usually shared as a rate per 1000 people. Be careful when you see or use a rate. It’s important to check what the constant (the ‘per 1000’ bit) is, as different statistics use different measures, like per 100, per 1000, per 100,000. Or even per 2,118, in the case of the breast cancer statistic!

Like proportions or percentages, using a rate on a line chart is a way of telling us whether something is increasing or decreasing compared to the population as a whole.

## Reading a line chart

1. Read the words.

Read the title, the axis labels, and the legends. Check any definitions for words you don't know. You may find these in the metadata, or you might need to look up the source information. Read who collected the data, and how they collected it. Are they a trustworthy source?

2. Check the axis scales

Check how each axis is scaled. Is it a simple number, or is it thousands or millions. Check if the axis scale is consistently spaced (linear), or if it uses a different scale like log scale*. 

This can also help identify charts where someone is trying to mislead you by using an inconsistent scale.

* a log scale is a way of showing numbers that are over a very wide range on a single chart. It's often used for exponential growth to help us assess whether the rate of growth is increasing or decreasing.

3. Check the axis start point. 

Generally, you expect a linear line chart to start the y-axis (vertical axis) at 0. If a line chart doesn't start at 0, it can be a warning sign. However, not all charts that start at a number other than 0 are misleading. Sometimes, when you're looking at a timeseries with small but significant changes to a large number, starting at 0 would hide these changes. In this instance, it can be helpful to start at a larger number, but the axis should be clearly labelled to show this.
