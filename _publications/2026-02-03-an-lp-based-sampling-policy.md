---
title: "An LP-based Sampling Policy for Multi-Armed Bandits with Side-Observations and Stochastic Availability"
collection: publications
permalink: /publication/2026-02-03-an-lp-based-sampling-policy
excerpt: ''
date: 2026-02-03
venue: 'WiOpt 2026'
publish_details: 'Under review at WiOpt, 2026'
# slidesurl: 'https://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://tinyurl.com/wiopt2026fullversion'
# bibtexurl:''
# citation: ''
---
We study the stochastic multi-armed bandit (MAB) problem where an underlying network structure enables sideobservations across related actions. We use a bipartite graph to link actions to a set of unknowns, such that selecting an action reveals observations for all the unknowns it is connected to. While previous works rely on the assumption that all actions are permanently accessible, we investigate the more practical setting of stochastic availability, where the set of feasible actions (the “activation set”) varies dynamically in each round. This framework models real-world systems with both structural dependencies and volatility, such as social networks where users provide sideinformation about their peers’ preferences, yet are not always online to be queried. To address this challenge, we propose UCB-LP-A, a novel policy that leverages a Linear Programming (LP) approach to optimize exploration-exploitation trade-offs under stochastic availability. Unlike standard network bandit algorithms that assume constant access, UCB-LP-A computes an optimal sampling distribution over the realizable activation sets, ensuring that the necessary observations are gathered using only the currently active arms. We derive a theoretical upper bound on the regret of our policy, characterizing the impact of both the network structure and the activation probabilities. Finally, we demonstrate through numerical simulations that UCB-LP-A significantly outperforms existing heuristics that ignore either the side-information or the availability constraints.