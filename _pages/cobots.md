---
layout: archive
title: "Collaborative Robots"
permalink: /cobots/
author_profile: true
---
I designed and implemented a full-stack robotic system that integrates task planning, motion planning, perception, and low-level control for real-world deployment. The system facilitates safe and efficient human–robot collaboration through human intent inference and trajectory prediction, enabling intelligent and adaptive coordination.
<p align="center">
<img src="/images/robotSystem.png" width="500">
</p>

<hr class="divider">

<div class="project-row">

  <div class="media-stack">

    <div class="media">
      <iframe src="https://www.youtube.com/embed/4DlgnFjfwkY?start=10"
        frameborder="0"
        allowfullscreen>
      </iframe>
    </div>

    <div class="media">
      <img src="/images/plan.png"  alt="demo">
    </div>

  </div>

  <div class="description">
    <h3>Human Plan Recognition</h3>
    <p>
      A collaborative robot’s high-level policy should align with human intent. To achieve this, we first learn object-centric action representations, and then classify action trajectories to infer the human’s underlying plan. Motion types are learned via an LSTM-based sequence model, object categories are inferred through learned visual perception, and action trajectory similarity is captured using dynamic time warping to classify action patterns and infer intent.
    </p>
  </div>

</div>

<hr class="divider">

<div class="project-row">

  <div class="media-stack">

    <div class="media">
      <iframe src="https://www.youtube.com/embed/wfle8Ry7z54"
        frameborder="0"
        allowfullscreen>
      </iframe>
    </div>

    <div class="media">
      <img src="/images/system.png"  alt="demo">
    </div>

  </div>

  <div class="description">
    <h3>Learning High-Level Collaborative Robot Policies from Single-Agent Demonstrations </h3>
    <p>
      Directly learning collaborative strategies is challenging due to the complexity of tasks and the variability of human actions, as collecting diverse and high-quality human–robot interaction data is often expensive and limited. To overcome this, we propose to learn high-level collaborative planning from readily available single-agent demonstrations. Specifically, we first construct a hierarchical task model that captures both sequential and parallel structures across multiple levels of abstraction. We then develop an optimization-based planner that exploits the inferred parallelism to prioritize robot actions that can be executed concurrently with human activities. This enables efficient coordination without requiring explicit human demonstration data, reducing spatial conflicts, shortening task completion time, and improving overall human satisfaction.
    </p>
  </div>

</div>


<hr class="divider">

<div class="project-row">

  <div class="media-stack">

    <div class="media">
      <iframe src="https://www.youtube.com/embed/2dqS9r0xBGo?start=15"
        frameborder="0"
        allowfullscreen>
      </iframe>
    </div>

    <div class="media">
      <img src="/images/adaptable_NN.png"  alt="demo">
    </div>

  </div>

  <div class="description">
    <h3>Online Learning Neural Network for Short-term Trajectory Prediction</h3>
    <p>
      Robots must accurately predict human motion to safely plan their own trajectories and enable efficient collaboration. We propose a semi-adaptive neural network for human motion prediction that provides real-time uncertainty estimates. Recursive Least Squares Parameter Adaptation (RLS-PAA) is employed for online parameter adaptation and uncertainty quantification.
    </p>
  </div>
 
</div>
<hr class="divider">


<div class="project-row">
  <div class="media">
    <img src="/images/lognormal.png"  alt="demo">
  </div>


  <div class="description">
    <h3>Long-Term Human Trajectory Prediction Using Adaptable Sigma Lognormal Functions </h3>
    <p>
      Unlike prior work with fixed prediction horizons, we define an action-dependent horizon conditioned on the predictability of future human behavior. We jointly predict human motion and estimate the durations of ongoing and future actions using a sigma-lognormal model, which compactly represents velocity profiles and enables analytic duration inference. To capture behavioral variability, we incorporate an online adaptation scheme that updates model parameters from streaming observations, inferred human intent, and scene context.
    </p>
  </div>

</div>




