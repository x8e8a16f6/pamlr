# PAMLR: A Passive-Active Multi-Armed Bandit-Based Solution for LoRa Channel Allocation

**Jihoon Yun**, Chengzhang Li, and Anish Arora

**ACM BuildSys 2023**  
The 10th ACM International Conference on Systems for Energy-Efficient
Buildings, Cities, and Transportation

📄 [ACM Digital Library](https://doi.org/10.1145/3600100.3623725)  
📖 [arXiv](https://arxiv.org/abs/2410.05147)

## Overview

PAMLR is an energy-efficient channel allocation framework for LoRa networks
operating in dynamic urban environments.

The framework combines low-cost passive channel measurements with selective
active measurements to identify reliable communication channels while reducing
the energy cost of channel monitoring. A Multi-Armed Bandit (MAB) approach is
used to explore and select promising channels based primarily on passive
measurements, while occasional active measurements update channel-specific
noise thresholds to account for fading and changing channel conditions.

## Key Contributions

- Developed a Multi-Armed Bandit-based channel allocation approach that
  combines passive and active channel measurements.
- Reduced the need for energy-intensive active measurements by leveraging
  frequent, low-cost passive measurements for channel exploration.
- Introduced channel-specific noise thresholds that use active measurements
  to capture changing channel conditions and guide passive channel evaluation.
- Designed an adaptive sampling mechanism to adjust passive and active
  measurement rates in response to channel dynamics.
- Validated the approach through simulations and field measurements across
  multiple urban environments.

## Evaluation

PAMLR was evaluated using both controlled simulations and real-world LoRa
measurements collected in multiple urban environments.

The results demonstrate that PAMLR can maintain low SNR regret relative to
optimal channel selection while substantially reducing the energy required
for channel measurements. The experiments also show that increasing
low-cost passive measurements can compensate for reducing expensive active
measurements.

## Research Topics

`LoRa` `LPWAN` `Multi-Armed Bandit` `Reinforcement Learning`
`Wireless Networks` `IoT` `Energy-Efficient Systems`

## Citation

Jihoon Yun, Chengzhang Li, and Anish Arora.
"PAMLR: A Passive-Active Multi-Armed Bandit-Based Solution for LoRa Channel Allocation."
ACM BuildSys 2023.
