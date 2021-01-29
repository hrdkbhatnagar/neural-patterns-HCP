# Analysis of neural patterns between face and shape recognition

### Rationale 

Facial expressions are among the most informative stimuli we perceive: Even a split-second impression of a person's face gives us an estimate of their mood and direction of attention. Existing neurological evidence strongly suggests the existence of machinery dedicated to processing facial expressions in the human brain. We consider an essential shape recognition process gates this facial expression processing machinery.

### Workflow

Therefore, we propose that the facial expression recognition mechanism shares some shape recognition steps in the visual system in the cortical areas. We tested this hypothesis using the fMRI data from the [Human Connectome Project](https://www.humanconnectome.org/study/hcp-young-adult/data-releases) of 339 subjects performing an emotion processing task.

<img src="https://lh5.googleusercontent.com/FQcAVfn-k_C7XQlMm_VCS2DtgL1POU2ZDi4EGAJPTr-TJX7zk06DE8nvqNYSzcYir95EMNU-R7O_kT2JopuYlsz-xMNWK5ZFF5A4a52mSZZ8s6s7afVibU8FuYCvrcpt02m-0jUc" alt="task"
	title="task paradigm" style="width: 70%; height: 90%" />

Similar to the [Hariri emotion task](https://science.sciencemag.org/content/297/5580/400.full) paradigm, the subjects matched fearful or angry facial expressions with expressions on the bottom of the screen and also matched geometric shapes like longitudinal and latitudinal ellipses.

We separately analysed BOLD activations of the cortical surface regions of the two tasks using Multi-variate pattern analysis. We first selected the top 5% most active brain regions for both the tasks using ANOVA feature selection. These selected features using a support vector machine, classified facial expressions recognition from resting-state with an accuracy of 83%, and 81% for the shape recognition task.

Further, the selected areas in ventral stream visual cortex like Posterior Inferior Temporal, Fusiform Face Complex, VMV3 in a ventromedial visual area, which best correlated with object recognition, showed a high correlation with facial expression recognition as well. The other cortical regions involving primary and early visual cortical sectors were also common to both the recognition tasks, but with varying degrees of activation. Their functional connectivity graphs were illustrated as: 



