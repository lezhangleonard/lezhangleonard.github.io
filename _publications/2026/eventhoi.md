---
title:          "EventHOI: Event-Driven Energy-Efficient Hand-Object Interaction Logging on Smartglasses"
date:           2026-10-04 00:01:00 -0400
selected:       true
pub:            "Manuscript under review at SenSys"
pub_date:       "2027"

abstract: >-
  Hand-object interactions (HOIs) are fundamental units of everyday human activities, capturing how people manipulate objects during daily routines. Automatically logging these interactions from an egocentric perspective can provide time-stamped evidence of daily actions, enabling applications such as memory assistance. However, practical HOI logging on smartglasses remains challenging because continuous RGB capture and wireless transmission exceed wearable energy and bandwidth budgets. We present EventHOI, an event-driven HOI detection and compression system that enables energy-efficient RGB sampling and HOI-aware encoding on smartglasses while preserving downstream HOI logging performance. EventHOI uses low-power event sensing as an always-on sentinel to detect HOI motions and trigger RGB sensing only when HOIs likely occur. A lightweight IMU-based egomotion cancellation pipeline suppresses spurious head-induced events. EventHOI further identifies HOI saliency regions from residual events to guide spatial-temporal compression for efficient transmission and VLM-based HOI logging. We build a smartglasses prototype, implement the end-to-end pipeline, and collect 10 hours of real-world data across multiple users, activities, and environments. On this real-world testbed and a 50-hour egocentric dataset, EventHOI reduces always-on backend power by 5.8--10.4x, uplink bandwidth by 3.0x, and RGB capture by 1.5--3.8x compared to RGB-only baselines, with minimal HOI recognition accuracy loss.

cover:          /assets/images/covers/eventhoi.png
authors:
  - Le Zhang
  - Kailai Cui
  - Hao Chen
  - Vlad Roznyatovskiy
  - Jianzhong Zhang
  - Anhong Guo
  - Kang G. Shin
  - Ke Sun
links:
  Project: https://eventhoi.github.io
---
