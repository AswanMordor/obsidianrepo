**Rutgers Website**: https://psych.rutgers.edu/faculty-profiles-a-contacts/107-elizabeth-torres
**Lab Website**: https://sites.google.com/site/blurbaboutmywork/publications?authuser=0
**Email**:  [ebtorres@psych.rutgers.edu](mailto:ebtorres@psych.rutgers.edu)

**Paper to Read**: Personalized Biometrics of Physical Pain Agree with Psychophysics by Participants with Sensory over Responsivity - Journal of Personalized Medicine

## Email
Good morning Prof. Torres,  
  
I came across your lab when looking into computational research at Rutgers, and found the work that you are doing on using computation to analyze voluntary behavior very interesting. I've read your paper on developing a set of personalized objective pain characteristics by comparing SOR with control EEG readings; while there is definitely a lot for me to learn to fully understand it, I felt that it was an exciting step forward especially since the standard pain scale is extremely subjective and can be in some cases an impediment to making good clinical decisions.  
  
If you have any spare time, I would love to ask you some questions about your research and your lab, to see if I would possibly be a good fit to join your research.  
  
A bit about me: I am a premedical post-bacc student at Rutgers, with my degree being a B.S. in Electrical and Computer Engineering from UT Austin with a focus in software. After graduation, I worked at Charles Schwab in their cybersecurity infrastructure division for ~2 years before making the decision to pursue medicine to combine my software skills with. I am very interested in the research and development of computational ways to improve healthcare decisions, both from the perspective of a clinician and a patient, which is why your research appeals to me.  
  
I've attached my resume to this email for your perusal and my availability for zoom or an in-person meeting. No matter what, I appreciate you for taking the time to read this email and hope to hear from you soon!

In-person (for this semester, the summer and next semester are much more open): 
F - 2pm onwards
M,W,Th - 9-10am and 5:30-7:30pm

Over Zoom:
Same as in-person and W,Th 11:30-2pm, M 11:30-1pm

-Neel Drain

## General Notes about her Lab:
- About her research consequences: "They consequently facilitate the measurements and the diagnosis of specific sensory-motor deficits, the identification of their source and the design of therapies to improve motor learning and performance in activities of every-day life."
- Assesing natural voluntary movements to create early-life therapies 
- Clinincal research subjects: Stroke patients + parkinson's patients + children with Autism
- Computational efforts: motor learning, adaptation, and planning
- About the computational objecttive: "The main objective of this interdisciplinary collaborative effort is to identify general principles and laws of mental operations required in voluntary behavior that generate testable predictions at different levels of abstraction."

## Notes about Personalized Biometrics of Physics Pain... Paper
**Summary**: Quantifying personalized moment-to-moment pain via EEG brain activity (using temperature) for patients with Sensory over Responsivity (vs control). Creating a scalabile gradient for pain measurements which can be standardized for the person rather than by averages across a population.

**Vocab.**
- Electrophysiology: physiology for the electrical phenomena associated with nervous and other bodily activity
- Sensory Over Responsivity (SOR): stimuli that are not typically painful are percieved as abnormally irritating, unpleasent, or painful (generally found in those with certain physchological/neurological disorders)
- Affective-emotive: thoughts/feelings including emotions 
- Noxious Input: stimulus stong enough to threaten tissue damage
- Reafferent: when a sensory organ moves relative to a static stimulus (think eye movement)
- Maximal cross-coherence: max. measure of similarity between singal bands, (deals with time series and signal processing)
- Adjacency matrix: matrix table to denote wheter vertices are adjacent to eachother in a finite graph

**Intro.**
- The sensastion of touch is a collective afferent nervous receptor effort including pressure (mechanoreceptors), temperature (thermoreceptors), and pain (nociceptors)
- Using EEG activity to view fluctuations in the brain and how they distribute during the resting state of a peson who reports atypical sensations of pain, but does not have their afferent pathway severed 
- Need objective charaterizations of pain to augment self-reporting
- Using data (peak amplitude distributions) perviously thought of as noise (old and new)

**Materials and Methods**
- Participants: 21 (5m, 16f) naive to testing, all did not have regular use of pain medication nor had known physchological, neurological, or metabolic disorders; with no known reported pain 24hrs. in advance 
- SOR group (8f, 1m) and control(8f 3m)...not sure what happened to the last male
- 3 blocks: 1. Resting, 2. Pain via heat, 3. Pain via heat - gradually increasing heat
- Measured EEG brain readings 
- Used max cross-coherence values to build adjacency matrix for different EEG channels yeilding a network graph where nodes are EEG channels (and their activities), while edges are the max. cross coherence (e.g. similiarity). The graph was then clustered, and the graph (one per patient) with the highest cluster coefficient (most cluster-y) being the "hub channel"
- Lots of statistics and stochistic processes... used to find a signal signature used to measure by

**Results**
- Reduced max. cross-coherence in the SOR channels compared with the control during the resting state, yeilds reduced cortical interactions for beta and gamma bands as a characteristic for SOR
- During resting state SOR clusters were less tight, but max. cross-coherence and clusters were not statistically different between the SOR group and the control group (however shape and scale of response during pain were statistically significant and almost respectively)
- But, during the second pain block, both groups were very similiar in their responses 
- SOR beta and gamma bands tend to shift quicker during pain transitions

**Discussion**
- EEG findings of SOR group at baseline resting differed from control 
- Each participant was baselined to themselves using the statistic netword grpahing and clustering methods rather than to a group baseline
- Control: expoential EMD with high Noise-Signal-Ratio yeilds a memoryless system whereby sensations are not lingering enough to cause pain
- SOR: symmetrical (Gaussian-like) EMD yeilds a lingering sensation that is brough up to discomfort, reported as pain (quasi memory-like)
- Due to the exponential EMD signal, the control expeinces in-the-moment pain without buffered memory, and therefore the control's brain does not anticipate incoming pain
- However, the SOR brain recognizes the pain stimulus more and builds a "memory buffer" in the brain to register the change more conciously 
- BUT this memroy buffer only lasts during the initial pain stimulus, weherby during the middle of the pain block, SOR was similarly "memoryless" as the control
- E.g. the transitions from resting to pain, and from pain to resting are the important bits
- The "lingering" pain sensation is referring to the SOR brain caching the pain stumulus long enough that is is brought into awareness, rather than in the control where the stimulus is too short or too weak and is discarded (memoryless system) before it can eb brought into awareness

**Conclusions**
- Advancing the understanding of physical pain perception as registered by micro-fluctiations of brain EEG signals




