GraphTS is a novel method for building a complex network from the EMG time series to visualize and diagnose neuromuscular disorders. Also, classified health and patient samples using machine learning & deep learning techniques. This approach can also be used as an assistant tool to neuromuscular specialists:

First, the three groups' healthy, myopathy, and neuropathy signals are prepared and processed (Combination of datasets I & II). The signals are windowed for accurate identification and investigation of the behavior of signals. 
Then, the linear envelope of the signal is applied to reduce the noise effect and focus on the initial values considering the fluctuating patterns of each group.
Finally, a complex network is developed through time series using the standard visibility graph algorithm.

Visualization of the networks resulting from the proposed approach is a valuable tool for experts in this field. The network features are also fed into machine learning architectures to help automate the diagnosis.

Dataset I: https://physionet.org/content/emgdb/1.0.0/

Dataset II: http://www.emglab.net/emglab/Signals/N2001/index.html
