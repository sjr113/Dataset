# Dataset
The collection of datasets that combine various imaging techniques and neuroengineering methods, specifically focused on brain-related visual decoding research.


Combined Imaging Neuroengineering for Brain (CineBrain) Datasets
The CineBrain dataset collection represents a state-of-the-art resource for brain activity analysis across multiple imaging modalities, including fMRI, EEG, and MEG, with a focus on understanding visual processing and object recognition in the human brain. These datasets integrate data from various neuroimaging techniques, providing valuable insights into neural responses to visual stimuli. Below is an overview of the key datasets included in the CineBrain collection:

1. fMRI Handwritten Character Dataset
Stimulus Type: Image

EEG: ×

MEG: ×

fMRI: √

Introduction:
The fMRI Handwritten Character Dataset is designed to study the brain's ability to reconstruct handwritten letter images from fMRI activity. The dataset includes fMRI signals from three subjects, who were presented with handwritten images of the letters "B", "R", "A", "I", "N", and "S" in a 56x56 resolution. The brain activity recorded during this experiment comes from the V1 and V2 areas of the visual cortex, which are crucial for early visual processing. The dataset contains a total of 2420 voxels from these brain regions, and the goal is to use these fMRI signals to reconstruct the presented handwritten images.

Key Features:

fMRI data collected from three subjects.

Stimuli: Handwritten letters ("B", "R", "A", "I", "N", "S").

Voxel data from the V1 and V2 areas of the brain (2420 voxels).

Resolution: 56×56 for each handwritten character.

Applications:

Visual decoding and brain image reconstruction.

Understanding early visual processing mechanisms in the brain.

Applications in brain-computer interfaces (BCI) for visual stimuli decoding.

2. THINGS-EEG Dataset
Stimulus Type: Image

EEG: √

MEG: ×

fMRI: ×

Introduction:
The THINGS-EEG Dataset is a large-scale electroencephalography (EEG) dataset designed to model human visual object recognition. It includes EEG recordings from 50 subjects, who viewed 22,248 images corresponding to 1,854 different object concepts from the THINGS stimulus set. The data was collected using a rapid serial visual presentation (RSVP) paradigm, where images were shown with a stimulus onset asynchrony (SOA) of 200 ms. Each subject participated in 4 equivalent experiments, resulting in a total of 82,160 image trials per subject.

Key Features:

50 subjects with EEG recordings.

22,248 images of 1,854 different object concepts.

Stimulus onset asynchrony (SOA) of 200 ms using RSVP.

Total of 82,160 trials per subject (4 experiments per subject).

Applications:

Investigating the neural basis of object recognition.

Modeling visual object processing in the human brain.

Development of algorithms for real-time object recognition based on EEG signals.

3. THINGS-MEG Dataset
Stimulus Type: Image

EEG: ×

MEG: √

fMRI: ×

Introduction:
The THINGS-MEG Dataset is a large-scale magnetoencephalography (MEG) dataset, designed to study visual object processing in the human brain. It contains MEG data from four subjects, who were shown 22,448 unique images representing 1,854 different object types. These stimuli were presented during 12 scanning sessions, and the subjects performed an odd-ball detection task while the images were displayed. To ensure data quality, the subjects' heads were stabilized and repositioned between sessions using custom head casts. The dataset is formatted in the Brain Imaging Data Structure (BIDS) and pre-processed with fmriprep to facilitate further analysis.

Key Features:

4 subjects with MEG recordings.

22,448 images representing 1,854 object types.

Odd-ball detection task during image presentation.

Custom head casts used for stabilization between sessions.

Data formatted in BIDS and pre-processed with fmriprep.

Applications:

Understanding object representation in the human brain using MEG.

Studying the temporal dynamics of visual object processing.

Investigating the neural mechanisms of visual perception and attention in the human brain.

Summary of Datasets
Dataset Name	Stimulus Type	EEG	MEG	fMRI	Description
fMRI Handwritten Character	Image	×	×	√	Focuses on reconstructing handwritten letters from fMRI data, collected from the V1 and V2 areas of the brain, using stimuli of handwritten characters (B, R, A, I, N, S).
THINGS-EEG	Image	√	×	×	A large-scale EEG dataset for studying visual object recognition, containing EEG data from 50 subjects in response to 22,248 images of 1,854 object concepts from the THINGS set.
THINGS-MEG	Image	×	√	×	A large-scale MEG dataset for studying visual object representations, with 4 subjects viewing 22,448 images during odd-ball detection tasks.

Conclusion
The CineBrain datasets offer an invaluable resource for research into visual perception, object recognition, and brain decoding. By leveraging data from multiple neuroimaging techniques (fMRI, EEG, and MEG), these datasets provide a comprehensive understanding of how the brain processes visual stimuli across different time and spatial scales. Researchers in fields such as visual neuroscience, brain-computer interfaces (BCI), and computational vision can utilize these datasets to further investigate brain activity and improve the design of neuroengineering technologies.


