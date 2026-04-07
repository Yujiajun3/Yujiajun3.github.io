---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<div style="margin-bottom: 30px; text-align: center;">
  <a href="{{ base_path }}/assets/cv.pdf" class="btn btn--info" target="_blank" style="padding: 10px 20px; font-size: 1.1em; border-radius: 30px; box-shadow: 0 4px 6px rgba(0,0,0,0.1);">
    <i class="fa fa-file-pdf-o"></i> Download Full PDF CV
  </a>
</div>

<!-- ==================== Education ==================== -->
<h2 style="border-bottom: 2px solid #e1e5e9; padding-bottom: 10px; margin-top: 40px;">
  <i class="fa fa-graduation-cap"></i> Education
</h2>

<div style="background: #fff; border-left: 4px solid #007bff; padding: 15px 20px; margin-bottom: 20px; box-shadow: 0 2px 5px rgba(0,0,0,0.05); border-radius: 0 8px 8px 0;">
  <h3 style="margin-top: 0; margin-bottom: 5px;">Zhejiang University, Hangzhou <span style="float: right; font-size: 0.8em; color: #666; font-weight: normal;">2024.09 - 2027.06</span></h3>
  <div style="color: #444; font-weight: bold;">M.S. in Control Science and Engineering</div>
  <ul style="margin-top: 10px; margin-bottom: 0; color: #555;">
    <li><strong>Lab:</strong> <a href="http://zju-fast.com/">FastLab (Fire Group)</a></li>
    <li><strong>Supervisors:</strong> Prof. <a href="http://zju-fast.com/research-group/yanjun-cao/">Yanjun Cao</a> and Prof. <a href="http://zju-fast.com/research-group/chao-xu/">Chao Xu</a></li>
    <li><strong>Research Focus:</strong> Trajectory Planning & Optimization, Reinforcement Learning, End-to-End Autonomous Navigation</li>
    <li><strong>Honors:</strong> Outstanding Graduate Student of Zhejiang University (2024-2025); Outstanding Graduate Student of ZJU Huzhou Institute (2025)</li>
  </ul>
</div>

<div style="background: #fff; border-left: 4px solid #007bff; padding: 15px 20px; margin-bottom: 20px; box-shadow: 0 2px 5px rgba(0,0,0,0.05); border-radius: 0 8px 8px 0;">
  <h3 style="margin-top: 0; margin-bottom: 5px;">Harbin Institute of Technology, Harbin <span style="float: right; font-size: 0.8em; color: #666; font-weight: normal;">2020.09 - 2024.06</span></h3>
  <div style="color: #444; font-weight: bold;">B.E. in Robotics Engineering</div>
  <ul style="margin-top: 10px; margin-bottom: 0; color: #555;">
    <li><strong>GPA:</strong> 93.13 / 100 &nbsp;|&nbsp; <strong>Rank:</strong> 5 / 298</li>
    <li><strong>Honors:</strong> National Scholarship; <strong>First Prize in National Intelligent Car Competition</strong>; SMC First-Class Scholarship; People's Scholarship (multiple times)</li>
  </ul>
</div>

<!-- ==================== Publications ==================== -->
<h2 style="border-bottom: 2px solid #e1e5e9; padding-bottom: 10px; margin-top: 40px;">
  <i class="fa fa-file-text"></i> Publications
</h2>

<div style="background: #fff; border-left: 4px solid #28a745; padding: 15px 20px; margin-bottom: 20px; box-shadow: 0 2px 5px rgba(0,0,0,0.05); border-radius: 0 8px 8px 0;">
  <div style="display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap;">
    <span style="background-color: #28a745; color: white; padding: 2px 10px; border-radius: 12px; font-weight: bold; font-size: 0.8em;">Accepted</span>
    <span style="font-size: 0.85em; color: #666;">RA-L 2025 · Presented at ICRA 2026</span>
  </div>
  <h3 style="margin-top: 8px; margin-bottom: 5px;">[1] TOP: Trajectory Optimization via Parallel Optimization towards Constant Time Complexity</h3>
  <div style="color: #555; font-size: 0.95em;"><strong>Jiajun Yu</strong><sup>†</sup>, Nanhe Chen<sup>†</sup>, Guodong Liu, Chao Xu, Fei Gao, and Yanjun Cao</div>
  <p style="margin-top: 8px; margin-bottom: 8px; color: #555; font-size: 0.9em;">
    Proposed an ADMM-based parallel trajectory optimization framework that decomposes trajectories into independent sub-problems, reducing per-iteration time complexity to O(1). Achieved >10× speedup over serial SOTA on 100-segment trajectories; GPU deployment enables millisecond-level optimization for 1000-segment trajectories.
  </p>
  <div style="margin-top: 8px;">
    <a href="https://arxiv.org/pdf/2507.10290" style="background: #007bff; color: white; padding: 3px 10px; border-radius: 12px; font-size: 0.85em; text-decoration: none; margin-right: 5px;">Paper</a>
    <a href="https://www.bilibili.com/video/BV12DW1zEEfp/" style="background: #fb7299; color: white; padding: 3px 10px; border-radius: 12px; font-size: 0.85em; text-decoration: none;">Video</a>
  </div>
</div>

<div style="background: #fff; border-left: 4px solid #ffc107; padding: 15px 20px; margin-bottom: 20px; box-shadow: 0 2px 5px rgba(0,0,0,0.05); border-radius: 0 8px 8px 0;">
  <div style="display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap;">
    <span style="background-color: #ffc107; color: #212529; padding: 2px 10px; border-radius: 12px; font-weight: bold; font-size: 0.8em;">To be Submitted</span>
    <span style="font-size: 0.85em; color: #666;">IEEE T-RO 2026</span>
  </div>
  <h3 style="margin-top: 8px; margin-bottom: 5px;">[2] Learning Safety-enhanced Navigation with Integrated Model Information</h3>
  <div style="color: #555; font-size: 0.95em;">Nanhe Chen<sup>†</sup>, <strong>Jiajun Yu</strong><sup>†</sup>, Mengke Zhang<sup>†</sup>, Pengxiang Zhou, Chao Xu, Fei Gao, and Yanjun Cao</div>
  <p style="margin-top: 8px; margin-bottom: 0; color: #555; font-size: 0.9em;">
    Proposed an end-to-end visual navigation framework integrating differentiable physics engine with safety-constrained policy optimization. Leveraged PALM for near-KKT convergence in a single loop. Achieved zero-shot sim-to-real transfer across differential-drive, tracked, and quadruped platforms with zero collision rate in dense environments.
  </p>
</div>

<div style="background: #fff; border-left: 4px solid #ffc107; padding: 15px 20px; margin-bottom: 20px; box-shadow: 0 2px 5px rgba(0,0,0,0.05); border-radius: 0 8px 8px 0;">
  <div style="display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap;">
    <span style="background-color: #ffc107; color: #212529; padding: 2px 10px; border-radius: 12px; font-weight: bold; font-size: 0.8em;">To be Submitted</span>
    <span style="font-size: 0.85em; color: #666;">RA-L 2026</span>
  </div>
  <h3 style="margin-top: 8px; margin-bottom: 5px;">[3] ATRS: Adaptive Trajectory Re-splitting via a Shared Neural Policy for Parallel Optimization</h3>
  <div style="color: #555; font-size: 0.95em;"><strong>Jiajun Yu</strong>, Guodong Liu, Chao Xu, Fei Gao, and Yanjun Cao</div>
  <p style="margin-top: 8px; margin-bottom: 0; color: #555; font-size: 0.9em;">
    Proposed embedding a shared deep RL agent into the ADMM optimization loop to dynamically restructure trajectory segments, eliminating the optimization bottleneck. Modeled adaptive splitting as a MASP-MDP with a shared Actor-Critic architecture, generalizing across arbitrary segment counts. Achieved 26% fewer iterations and 19.1% less computation time versus baselines; real quadrotor traversing unknown forests in 35 ms.
  </p>
</div>

<div style="background: #fff; border-left: 4px solid #ffc107; padding: 15px 20px; margin-bottom: 20px; box-shadow: 0 2px 5px rgba(0,0,0,0.05); border-radius: 0 8px 8px 0;">
  <div style="display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap;">
    <span style="background-color: #ffc107; color: #212529; padding: 2px 10px; border-radius: 12px; font-weight: bold; font-size: 0.8em;">To be Submitted</span>
    <span style="font-size: 0.85em; color: #666;">RA-L 2026</span>
  </div>
  <h3 style="margin-top: 8px; margin-bottom: 5px;">[4] Whole-body Planning for Any-Shape Robot directly in Point Cloud</h3>
  <div style="color: #555; font-size: 0.95em;">Guodong Liu<sup>†</sup>, <strong>Jiajun Yu</strong><sup>†</sup>, Chao Xu, Fei Gao, and Yanjun Cao</div>
  <p style="margin-top: 8px; margin-bottom: 0; color: #555; font-size: 0.9em;">
    Proposed a dual-layer framework for whole-body trajectory optimization of arbitrary-shape robots directly in raw point clouds. Leveraged convex decomposition for differentiable signed-distance constraints with ADMM-based parallel solving. Full GPU pipeline completes in 19.86 ms in narrow mixed environments; real quadrotor with LiDAR navigates unknown environments in real time.
  </p>
</div>

<div style="background: #fff; border-left: 4px solid #ffc107; padding: 15px 20px; margin-bottom: 20px; box-shadow: 0 2px 5px rgba(0,0,0,0.05); border-radius: 0 8px 8px 0;">
  <div style="display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap;">
    <span style="background-color: #ffc107; color: #212529; padding: 2px 10px; border-radius: 12px; font-weight: bold; font-size: 0.8em;">To be Submitted</span>
    <span style="font-size: 0.85em; color: #666;">RA-L 2026</span>
  </div>
  <h3 style="margin-top: 8px; margin-bottom: 5px;">[5] CoNiPA: Cooperative Non-inertial Control Framework with LSTM-Enhanced Predictive Awareness</h3>
  <div style="color: #555; font-size: 0.95em;">Mingxuan Zhang<sup>†</sup>, <strong>Jiajun Yu</strong><sup>†</sup>, Baozhe Zhang<sup>†</sup>, Chao Xu, Fei Gao, and Yanjun Cao</div>
  <p style="margin-top: 8px; margin-bottom: 0; color: #555; font-size: 0.9em;">
    Proposed an active perception-aware control framework for GPS-denied air-ground cooperation. Unified UAV trajectory and gimbal orientation optimization under non-inertial dynamics via MPC. LSTM-based time-varying IMU prediction compensates for model mismatch. Achieved >98% target visibility and 20 cm tracking accuracy in aggressive maneuvers across simulation and real-world experiments.
  </p>
</div>

<!-- ==================== Projects ==================== -->
<h2 style="border-bottom: 2px solid #e1e5e9; padding-bottom: 10px; margin-top: 40px;">
  <i class="fa fa-rocket"></i> Projects
</h2>

<div style="background: #fff; border-left: 4px solid #6f42c1; padding: 15px 20px; margin-bottom: 20px; box-shadow: 0 2px 5px rgba(0,0,0,0.05); border-radius: 0 8px 8px 0;">
  <h3 style="margin-top: 0; margin-bottom: 5px;">Air-Ground Cooperation without Global Information <span style="float: right; font-size: 0.8em; color: #666; font-weight: normal;">IROS 2025 EXPO</span></h3>
  <div style="color: #444; font-weight: bold;">Planning & Control Lead</div>
  <ul style="margin-top: 10px; margin-bottom: 0; color: #555;">
    <li>RoFly and CubeTrack cooperation with CREPES and CoNi-MPC for GPS-denied autonomous air-ground systems.</li>
    <li>Achieved real-time relative pose estimation, non-inertial trajectory tracking, and fleet coordination across multi-scenario real-robot demonstrations.</li>
  </ul>
  <div style="margin-top: 8px;">
    <a href="https://fast-fire.github.io/IROS2025-EXPO-DisplayPage/" style="background: #6f42c1; color: white; padding: 3px 10px; border-radius: 12px; font-size: 0.85em; text-decoration: none;">Project Page</a>
  </div>
</div>

<div style="background: #fff; border-left: 4px solid #6f42c1; padding: 15px 20px; margin-bottom: 20px; box-shadow: 0 2px 5px rgba(0,0,0,0.05); border-radius: 0 8px 8px 0;">
  <h3 style="margin-top: 0; margin-bottom: 5px;">Autonomous UAV Inspection System for Power Substations <span style="float: right; font-size: 0.8em; color: #666; font-weight: normal;">Enterprise Project</span></h3>
  <div style="color: #444; font-weight: bold;">Planning & Control Lead</div>
  <ul style="margin-top: 10px; margin-bottom: 0; color: #555;">
    <li>Developed a micro UAV (&lt;800 g, &gt;15 min endurance) autonomous inspection system for complex indoor substation environments.</li>
    <li>Implemented GPS-denied real-time visual localization via onboard ORB-SLAM; equipped with thermal and RGB cameras for equipment temperature monitoring and instrument reading detection.</li>
    <li>Achieved full-coverage path planning with interest-point-guided global coverage and local obstacle-avoidance trajectory optimization. Successfully deployed and tested on-site.</li>
  </ul>
</div>

<!-- ==================== Technical Skills ==================== -->
<h2 style="border-bottom: 2px solid #e1e5e9; padding-bottom: 10px; margin-top: 40px;">
  <i class="fa fa-code"></i> Technical Skills
</h2>

<div style="display: flex; flex-wrap: wrap; gap: 10px; margin-bottom: 10px;">
  <span style="background: #e9ecef; padding: 5px 12px; border-radius: 15px; font-size: 0.9em; color: #333;">C/C++</span>
  <span style="background: #e9ecef; padding: 5px 12px; border-radius: 15px; font-size: 0.9em; color: #333;">Python</span>
  <span style="background: #e9ecef; padding: 5px 12px; border-radius: 15px; font-size: 0.9em; color: #333;">PyTorch / libtorch</span>
  <span style="background: #e9ecef; padding: 5px 12px; border-radius: 15px; font-size: 0.9em; color: #333;">CUDA / CuPy</span>
  <span style="background: #e9ecef; padding: 5px 12px; border-radius: 15px; font-size: 0.9em; color: #333;">ROS / ROS2</span>
  <span style="background: #e9ecef; padding: 5px 12px; border-radius: 15px; font-size: 0.9em; color: #333;">Isaac Gym/Sim</span>
  <span style="background: #e9ecef; padding: 5px 12px; border-radius: 15px; font-size: 0.9em; color: #333;">Gazebo</span>
</div>
<div style="display: flex; flex-wrap: wrap; gap: 10px;">
  <span style="background: #dbeafe; padding: 5px 12px; border-radius: 15px; font-size: 0.9em; color: #1e40af;">Trajectory Optimization</span>
  <span style="background: #dbeafe; padding: 5px 12px; border-radius: 15px; font-size: 0.9em; color: #1e40af;">Reinforcement Learning (PPO, TD3, SAC)</span>
  <span style="background: #dbeafe; padding: 5px 12px; border-radius: 15px; font-size: 0.9em; color: #1e40af;">Convex Optimization</span>
  <span style="background: #dbeafe; padding: 5px 12px; border-radius: 15px; font-size: 0.9em; color: #1e40af;">Differentiable Simulation</span>
  <span style="background: #dbeafe; padding: 5px 12px; border-radius: 15px; font-size: 0.9em; color: #1e40af;">Parallel Computing</span>
  <span style="background: #dbeafe; padding: 5px 12px; border-radius: 15px; font-size: 0.9em; color: #1e40af;">World Models</span>
</div>
