# Cueless-Motor-Imagery-EEG-Dataset
This dataset contains EEG recordings from 50 individuals using the Emotiv EPOC X Brain-Computer Interface (BCI), recorded at a sampling frequency of 128 Hz. The data was collected to support research on decoding brain signals for mental command recognition in BCI applications. Participants performed various mental tasks, including baseline conditions with eyes open and eyes closed, to capture covert brain activity linked to directional intent.

## Dataset Specifications

### Device Used
**Emotiv EPOC X** — A wireless EEG headset used to capture signals during mental tasks.

### Sampling Frequency
EEG data were recorded at 128 Hz.

### Number of Channels
The dataset includes signals from 14 electrodes based on the international 10–20 system:

- **Channels**: AF3, F7, F3, FC5, T7, P7, O1, O2, P8, T8, FC6, F4, F8, AF4  
- **Regions**:
  - *Frontal (AF3, AF4, F3, F4, F7, F8)* — attention, working memory, decision making  
  - *Frontocentral (FC5, FC6)* — motor planning and coordination  
  - *Temporal (T7, T8)* — auditory processing and memory  
  - *Parietal (P7, P8)* — sensory processing and spatial awareness  
  - *Occipital (O1, O2)* — visual processing

## Participant Information

- **Subjects**: 50 healthy individuals  
- **Age Range**: 18–25 years  
- **Gender**: Inclusive of both male and female participants  
- **Baseline Condition**:  
  - Eyes open: 15 seconds  
  - Eyes closed: 15 seconds

## Data Format

- **File Type**: `.csv`  
- **Mental Commands**: Up, Down, Left, Right  
- **Labels**:
  - Up = 8  
  - Down = 16  
  - Left = 32  
  - Right = 64  
- **Trials per Command**: 10 per subject  
- **Trial Duration**: 8 seconds

## Citation

If you use this dataset, please cite:  
**Sado T. Osimeozemeokhai, *Decoding Directional Intent from Cueless EEG Motor Imagery with Emotiv Epoc X*, 2025.**

## License

This dataset is released under the **Creative Commons Zero v1.0 Universal (CC0)** license.
