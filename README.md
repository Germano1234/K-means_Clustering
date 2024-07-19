
# K-means Clustering with MITRE Attack Tactics

This project, conducted in collaboration with the University of West Florida, aims to differentiate between attack data and normal data using K-means clustering. The project utilizes data from the MITRE ATT&CK framework, which classifies and describes the tactics and techniques used by adversaries during cyber-attacks.

## Project Overview

The primary goal of this project is to develop a model that can accurately classify data points as either normal or indicative of reconnaissance attacks. The K-means clustering algorithm is used to group the data points based on their features, and the results are analyzed to identify patterns associated with different types of activities.

## Features

- **Data Preprocessing:** Scaling of features for better clustering performance.
- **K-means Clustering:** Implementation of the K-means algorithm to cluster the data.
- **PCA Visualization:** Visualization of the clustering results using Principal Component Analysis (PCA).
- **MITRE ATT&CK Tactics Integration:** Mapping of the clusters to MITRE ATT&CK tactics to interpret the clustering results.

## Visualization

The results are visualized using PCA to reduce the dimensionality of the feature space. The clusters are displayed in a scatter plot, with colors representing different types of activities based on the MITRE ATT&CK tactics.

## Results

The model successfully separates normal data from reconnaissance attacks, as illustrated by the distinct clusters in the PCA plot. This approach provides a valuable tool for cybersecurity professionals to detect and analyze malicious activities.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- University of West Florida for their support and resources.
- The MITRE Corporation for the ATT&CK framework.
