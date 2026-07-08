# FEDGMMINT
FL initialization

The limitations of FL in the presence of statistically heterogeneous data distributions. 
In practical deployments, data across participating silos is rarely identically distributed. Differences in acquisition environments, sensing devices, temporal conditions, and local sampling strategies lead to non-IID local datasets.
In vision tasks, such distributional shifts are particularly severe due to variations in illumination, background context, and scene composition.
Standard federated optimization methods implicitly assume that local data distributions are similar.
Under non-IID conditions, this assumption is violated, leading to divergent local updates, slow convergence, and excessive communication requirements.
Empirical studies consistently show that naïve federated averaging performs poorly in such settings, particularly for high-dimensional vision models. 
These observations motivate the exploration of FL mechanisms that explicitly model or account for distributional
heterogeneity, enabling more stable convergence and efficient collaborative training in realistic non-IID scenarios.
