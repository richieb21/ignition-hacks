## Ignition Hacks 2022 Team UTS 1


The following project uses LSTM and RNN to predict future EEG signals based on "EEG Dataset Recorded In A Car Simulator". 

Specifically, an architecture of stacked LSTM with a Dense Layer is used. 

Results including accuracy and loss statistics are interpreted using the Python library Tensorflow. 

Participants in the hackathon: Alam Chinna, John Hu, Richard Bai. 

## Main Aims
Use EEG signals from the brain in order to accurately predict and alert drivers of their next microsleep cycle and take preventative measures.
The data is specifically electroencephalography data from a driving simulation. Cycles are extrapolated and used to determine the next expected microsleep cycle. 

Difficulty lies in multistep time series forecasting or series forecasting which constitutes unsupervised learning

## Biological Sleep Response
EEG measures post-synaptic potentials from large groups of neurons which trigger during an event. Non-invasive EEGs consist of specially placed electrodes placed on the scalp to measure brain activity and find the difference between signals. During periods of drowsiness, certain regions of the brain such as the hypothalamus will activate and send alpha, beta, gamma, or theta waves. This allows differences in EEG recordings to indicate sleepiness vs wakefulness. 
