# CapsPhase
CapsPhase: Capsule Neural Network for Seismic Phase Classification and Picking

CapsPhase consists of several layers, e.g., convolutional, primary capsule, and digit capsule layer. The convolutional layer extracts the significant features from the seismic data, while the primary capsule combines the extracted features into several vector representations named capsules. Afterward, the primary capsule is connected to the digit capsule layer using a dynamic routing strategy to obtain the vector representation of each output class, i.e., P-wave, S-wave, and noise class.
