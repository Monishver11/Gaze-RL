##### Gaze-RL

Implementation for "Deep Decision Making with RL" course project titled "Gaze-Guided Reinforcement Learning for Visual Search"

Visual search is a fundamental task that humans perform effortlessly, but it remains challenging for autonomous agents. This project explores how human visual attention patterns can be leveraged to improve reinforcement learning for object search tasks in the AI2-THOR environment.

Our approach combines:

- A pretrained gaze prediction model
- Three integration methods for incorporating gaze information:
  - Channel integration
  - Bottleneck integration
  - Weighted integration
- A dual-level integration framework that utilises gaze for both perception and reward shaping

**Setup and Installation**

```bash
conda env create -f environment.yml
conda activate gaze-rl-stable
```

**Usage**

<!-- ```bash
cd Gaze-RL/
python src/train_gaze_guided_rl_final.py --target Microwave --integration channel --exp-name gaze_channel_exp
``` -->

For a detailed explanation of this project, including motivation, methodology, and comprehensive results, visit our [blog post](https://monishver11.github.io/projects/2_project/).
