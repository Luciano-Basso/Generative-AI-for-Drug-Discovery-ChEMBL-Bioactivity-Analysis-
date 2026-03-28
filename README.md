# Generative-AI-for-Drug-Discovery-ChEMBL-Bioactivity-Analysis-
In this collaborative project, we explored how machine learning and generative AI could help discover new drug candidates. We used the open-access ChEMBL database, which contains millions of known molecules and data about how strongly they interact with different protein targets related to diseases.

My role focused on preparing and analysing the data so it could be used by machine learning models. I cleaned the dataset by filtering out molecules that showed little or no biological activity and kept only those with strong measured effects. I also removed problematic molecules that can interfere with experiments.

After that, I converted the chemical structures into numerical features using molecular fingerprints such as ECFP and MACCS keys so they could be analyzed by machine learning algorithms. I then tested dimensionality reduction methods like PCA and t-SNE and experimented with clustering algorithms such as HDBSCAN and K-Means to group molecules that had similar structures and biological activity.

These clusters help map out regions of chemical space where promising molecules already exist. The idea is that generative AI models can then use this information to design new molecules with similar properties.

This approach is useful for researchers because it helps narrow down the huge number of possible molecules that could exist. Instead of testing millions of compounds through trial and error in the lab, machine learning can highlight the most promising candidates first. This can save researchers a lot of time, reduce experimental costs, and speed up the early stages of drug discovery.

