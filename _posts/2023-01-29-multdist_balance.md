---
title: "Multisensory (dis-)integration for robot balance control"
date: 2023-01-29
---

# Multisensory (dis-)integration for robot balance control

Type: Master thesis
Status: ongoing

We humans can rely on mutliple senses when moving and acting in our environment. We can even focus on one sense, blend out others, trust or distrust them, or rely on just a subset of them. This skill becomes especially important when our senses don't match up anymore.

Together with [Max](http://lauflabor.ifs-tud.de/doku.php?id=lab_members:lab_members_maximilian_alexander_stasica) and our student Sebastian we explore a sort of visual illusion, the [moving room illusion](https://www.youtube.com/watch?v=F4xenIulg_8), where especially the proprioceptive and visual input clash. //
Using a custom VR/ simulation environment we could reconstruct this kind of optical flow illusion and conducted an experiment measuring the body and head motion, muscle activations, and ground forces. Now, Sebastian is exploring methods from (inverse) reinforcement learning (RL/ IRL) to train a controller capable of balancing an inverted pendulum based on comparable visual and proprioceptive inputs. 

With the insights from this study we hope to create more robust control algorithms that can adapt their usage of sensory input. Such improvements could also be usable for smarter prothesis or exoskeleton controllers.

### Showcase
Some first insights in what the visual part and some extracted optical flow looks like for the agent:

<!-- <video controls="controls" width="600" height="300" name="Launching event">
  <source src="https://uvest.github.io/figures/optical_flow_1.mp4">
</video>

<video controls="controls" width="600" height="300" name="Launching event">
  <source src="https://uvest.github.io/figures/optical_flow_3.mp4">
</video> -->

... poor agent.