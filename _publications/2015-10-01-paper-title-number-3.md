---
title: "TOP: Trajectory Optimization via Parallel Optimization towards Constant Time Complexity"
collection: publications
category: manuscripts
permalink: 'https://arxiv.org/abs/2507.10290'
excerpt: 'This paper proposes a novel trajectory optimization framework based on the Consensus Alternating Direction Method of Multipliers (CADMM) algorithm, which decomposes the trajectory into multiple segments and solves the subproblems in parallel.'
date: 2025-10-10
venue: 'IEEE Robotics and Automation Letters'
# slidesurl: 'https://arxiv.org/pdf/2507.10290'
paperurl: 'https://arxiv.org/pdf/2507.10290'
videourl: 'https://www.bilibili.com/video/BV12DW1zEEfp/?spm_id_from=333.337.search-card.all.click&vd_source=3533ba40792bf622b3fb90fb0749bda2'
citation: 'Yu J, Chen N, Liu G, et al. TOP: Trajectory Optimization via Parallel Optimization towards Constant Time Complexity[J]. arXiv preprint arXiv:2507.10290, 2025.'
---

## Abstract

This paper proposes a novel trajectory optimization framework based on the Consensus Alternating Direction Method of Multipliers (CADMM) algorithm, which decomposes the trajectory into multiple segments and solves the subproblems in parallel. This approach achieves constant time complexity for trajectory optimization problems.

## Video Demonstration

<div style="position: relative; width: 100%; padding-bottom: 56.25%; height: 0; overflow: hidden; margin: 20px 0;">
  <iframe 
    src="//player.bilibili.com/player.html?bvid=BV12DW1zEEfp&page=1&high_quality=1&danmaku=0" 
    scrolling="no" 
    border="0" 
    frameborder="no" 
    framespacing="0" 
    allowfullscreen="true" 
    style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border-radius: 8px;">
  </iframe>
</div>

*Video: Demonstration of the TOP trajectory optimization algorithm showing parallel computation and real-time performance.*

## Key Contributions

- Novel parallel trajectory optimization framework using CADMM
- Constant time complexity achievement through segment decomposition
- Real-time performance suitable for robotics applications
- Comprehensive experimental validation

## Technical Details

The proposed TOP (Trajectory Optimization via Parallel Optimization) method addresses the computational bottleneck in traditional trajectory optimization by leveraging parallel processing capabilities. The key innovation lies in the decomposition strategy that maintains solution quality while dramatically reducing computation time.

### Algorithm Overview

1. **Trajectory Segmentation**: Divide the trajectory into multiple segments
2. **Parallel Subproblem Solving**: Solve each segment optimization independently
3. **Consensus Mechanism**: Ensure continuity and smoothness across segments
4. **Iterative Refinement**: Converge to globally optimal solution

## Experimental Results

Our experiments demonstrate that the TOP algorithm achieves:
- **10x speedup** compared to traditional sequential methods
- **Constant time complexity** regardless of trajectory length
- **Maintained solution quality** with minimal optimality gap
- **Real-time performance** suitable for online planning

## Applications

This work has significant implications for:
- Autonomous vehicle path planning
- Robotic manipulation trajectory generation
- Drone flight path optimization
- Real-time motion planning systems
