# Auto-encoder + K-shape clustering
In India, residential consumers are traditionally segmented
based on their monthly energy consumption. The adoption of Advanced
Metering Infrastructure offers an opportunity to utilize detailed smart
meter data for more precise consumer segmentation, helping electricity
distribution companies to implement tailored demand response policies.
This paper presents an analysis of consumer segmentation based on the
clustering of load profiles from 84 residential buildings in India using
smart meter data. Unlike existing methods that apply clustering algorithms directly, this research incorporates a novel improvement through
a two-stage clustering process combining an Autoencoder network with
the K-shape clustering algorithm. In the first stage, the Autoencoder
transforms the input load profiles into a lower-dimensional latent space,
effectively capturing the most significant features of the data. In the subsequent stage, the K-shape clustering algorithm is applied to these latent
space vectors. This approach leverages the Autoencoder’s ability to reduce noise and highlight essential patterns, resulting in more accurate
and efficient clustering of load profiles compared to using the K-shape
algorithm alone. Our analysis demonstrates that the proposed two-stage
clustering method enhances the performance of the traditional K-shape
algorithm, as evaluated using clustering evaluation metrics such as the
Calinski-Harabasz Index, Davies-Bouldin Score, and Silhouette Index.
The results also indicate that rural consumers in Indian residential households can be effectively grouped into four distinct segments through this
method. These clusters can be analyzed alongside the total load curve of
a state or region for a given day to identify those contributing to peak
demand. Subsequently, targeted price-based or incentive-based demand
response schemes can be devised for these consumer clusters.
