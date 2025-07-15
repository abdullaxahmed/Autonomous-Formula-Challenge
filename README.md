# Autonomous-Formula-Challenge


## Overview

This project showcases a small-scale autonomous formula car developed for the Open Robotics International Competition (ORIC) and the Global Robotics Challenge (GRC). The system is designed to navigate racing tracks fully autonomously by adjusting its steering and velocity based on real-time sensor input.

At the core of the speed control system is a fuzzy logic–based decision model that continuously interprets 1D LiDAR data to adapt the vehicle's velocity based on track conditions. Steering is handled through a custom rule-based algorithm that calculates direction by analyzing lateral distance differences.


### Key objectives:
- Achieving smooth and reactive navigation on curved tracks
- Maintaining optimal speed through adaptive control
- Demonstrating robust performance in a competitive autonomous racing scenario

## System Prototype

<table>
  <tr>
    <td align="center">
      <img src="images/Prototype Side View.png" width="300"/>
    </td>
    <td align="center">
      <img src="images/Prototype Top View.png" width="270"/>
    </td>
  </tr>
</table>

Small-scale autonomous formula car prototype featuring a mounted 1D LiDAR sensors, onboard computer for real-time processing, wireless communication module, and a top-mounted emergency stop system. Designed with a compact and functional control layout optimized for autonomous track navigation.

## Track Environment

<p align="center">
  <img src="images/Racing Track.png" width="500"/>
</p>

 Testing track used for performance evaluation, designed to challenge autonomous navigation through varying curves and straight-line segments.



