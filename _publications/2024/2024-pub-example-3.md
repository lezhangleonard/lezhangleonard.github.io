---
title:          "Efficient Multitask Learning on Resource-constrained Systems"
date:           2024-05-12 00:01:00 +0800
selected:       true
pub:            "International Conference on Embedded Wireless Systems and Networks (EWSN)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2024"

abstract: >-
We present Antler, which exploits the affinity between all pairs of tasks in a multitask inference system to construct a compact graph representation of the task set and finds an optimal order of execution of the tasks such that the end-to-end time and energy cost of inference is reduced while the accuracy remains similar to the state-of-the-art. The design of Antler is based on two observations: first, tasks running on the same platform shows affinity, which is leveraged to find a compact graph representation of the tasks that helps avoid unnecessary computations of overlapping subtasks in the task set; and second, tasks that run on the same system may have dependencies, which is leveraged to find an optimal ordering of the tasks that helps avoid unnecessary computations of the dependent tasks or the remaining portion of a task. We implement two systems: a 16-bit TI MSP430FR5994-based custom-designed ultra-low-power system, and a 32-bit ARM Cortex M4/M7-based off-the-shelf STM32H747 board. We conduct both dataset-driven experiments as well as real-world deployments with these systems. We observe that Antler's execution time and energy consumption are the lowest compared to all baseline systems and by leveraging the similarity of tasks and by reusing the intermediate results from previous task, Antler reduces the inference time by 2.3X -- 4.6X and saves 56\% -- 78\% energy, when compared to the state-of-the-art.
cover:          /assets/images/covers/antler.jpg
authors:
  - Yubo Luo
  - Le Zhang
  - Zhenyu Wang
  - Shahriar Nirjon
links:
  Paper: https://arxiv.org/abs/2302.13155
---
