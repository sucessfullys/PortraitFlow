# PortraitFlow-RL: Enhancing the Naturalness and Realism of Portrait Generation through a Two-Stage SFT+RL Paradigm Based on Flux 2
<div align="center">
  <img src="dataset/图片2.png" width="90%" alt="PortraitFlow-RL Overview"/> 
</div>

PortraitFlow-RL is a Flux 2-based portrait generation enhancement framework. It adopts a two-stage training paradigm, where supervised fine-tuning (SFT) is first used to improve instruction following and portrait-specific generation quality, followed by reinforcement learning (RL) to further align the model with human preferences for naturalness, realism, and visual fidelity.

## Installing Dependencies

Install from source (recommended):
```
git clone https://github.com/sucessfullys/PortraitFlow.git
cd PortraitFlow
pip install -e .
```

## 💗 Acknowledgement <a name="acknowledgement"></a> 
We would like to express our sincere gratitude to the following open-source projects:
- [Flux2](https://github.com/black-forest-labs/flux2)
- [Flow-GRPO](https://github.com/yifan123/flow_grpo)
- [DGPO](https://github.com/Luo-Yihong/DGPO)

