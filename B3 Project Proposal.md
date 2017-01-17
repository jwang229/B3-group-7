# Project Proposal
*Razi Rais, Lucy Wu, Judy Wang*

Technology is continuing to advance, and with machines that are now capable of imaging the human brain faster and in higher resolution than before, creating a map of the brain is no longer a distant goal. Although there is still a lot to be discovered about depression, extensive research has already been done on adults, whereas scientists are still in the dark about childhood depression. Treatments, both therapy and medication, have been developed for adults, but because so little is known about childhood depression, the only treatments prescribed for children are counseling, and the occasional anti-depressant. It is also harder to understand and diagnose childhood depression; it may be difficult for kids to articulate their feelings, and during the “teenage” years rampant with mood swings, it may be hard to distinguish depression from their everyday emotions. 

This 10-year large-scale clinical research study is proposed to investigate childhood depression. The first part of the study involves scanning the brains of both depressed and normal children via Magnetic Resonance Imaging (MRI). These images will be put through an algorithm that will be able to diagnose a child for depression by comparing his/her MRI scan to the images of depressed and healthy brains. 

Additionally, MRI scans from adults will be taken to compare the structural changes caused by child-onset depression and adult-onset depression. A trial using Electron Microscopy (EM) will be conducted using adult tissue samples collected from neurosurgeries. This trial will analyze depression at a synaptic level in these tissue samples, with the hope that by uploading all the data and findings to the cloud, future research can expand on this research to understand depression in humans at the cellular and molecular levels. 

Our 10 year study plans to follow 1000 recruited children subjects starting from when they are 10 years old, and to scan their brains biannually (once in the summer, once in the winter). In this group, approximately half of the children will be already diagnosed with depression with the other half being normal, healthy subjects. To account for any gender differences in brain structure, including potentially different brain developments during puberty, the male to female ratio in both experimental groups will be kept as close to 50:50 as possible. 

From the data collected, the MRIs will be merged together using Large Deformation Diffeomorphic Metric Mapping (LDDMM) technique to create standardized images of a brain for either a female or male, at a specific age, either in the winter or summer. With a total of 80 standardized images after 10 years, researchers will be able to compare the standardized images of depressed and normal brains to observe the potential differences in brain structure due to depression. 

An algorithm will be designed such that a child could input his/her gender, age, and time of the year (summer or winter), and the MRI scan of that child would be compared to both the depressed and normal scans in order to determine whether the child has depression.This algorithm will use a Random Forest classifier to iterate through all of the MRI images of male brains and female brains at each age to train itself to identify depression in adolescents. All project data will be uploaded and stored to the cloud. This facilitates the algorithm design process where new MRIs of normal and depressed children can be easily accessed and entered into the algorithm to increase the dataset size for the diagnosis. 

This first part of the project will involve collaboration with Johns Hopkins Medical Institute Department of Neurology, which will be supplying the equipment that will be used, including MRI machines. Our initial estimate of research personnels required is approximately a team of 5 biologists and physicians to assist in data collection and interpretation and 10-15 research scientists with expertise in fields ranging from neuroimaging to computer science to assist in the data extraction and analysis process. 

Concurrently with the first part of this study that focuses on the onset and childhood development of depression, the second part compares childhood and adult depression. We will be performing MRI scans on a randomly selected group of 40-50 adult patients, half of which acquired childhood-onset depression and the other half adult-onset depression. An additional 50 adults without depression will be scanned to provide control data. The same image analysis will be conducted to compare the structural brain areas affected by depression between children and adults. This will provide insight into both long-term development of depression but also will evaluate potential differences in brain structure between childhood-onset and adult-onset depression. In addition, volumetric segmentation of EM data will be used to better understand the nano-scaled neuronal processes. Because MRI images only show brain structures, electron microscopy is a more effective method to image patients with depression in order to decipher the neural network underlying the development of depression. EM will be conducted on only a few patient brain tissue samples. This second part of the project will involve recruitment of a team of approximately 5-10 research scientists in collaboration with JHMI Department of Neurology and the National Institute on Mental Health. The sheer volume of both MRI and EM data obtained in this second part will also require the data to be uploaded and stored to the cloud. 

*All data will be shared with the Human Connectome Project after the length of this research study to further the efforts of NIH in the field of neuroimaging.* 


**Proposed 10-Year Budget** 
1. Magnetic Resonance Imaging scans: 
  * Will be using MRI machines of partner labs and hospitals, including JHMI 
  * Cost estimate of $1000 per scan 
  * First part of the study requires biannual scans for 1000 subjects over the course of 10 years = 20,000 scans 
  * Second part of the study requires one-time scans for 100 adult subjects = 100 scans 
  * Rough cost calculation = 20.1 million USD 
  
2. Electron Microscopy scans: 
  * Will be using EM of partner labs 
  * Rough cost calculation = 2 million USD 
  
3. Data storage/upload/download via cloud: 
  * Estimated 14MB of data per MRI scan and 500TB of data for EM scan images 
  * 20,100 MRI scans will require 280.7 GB of data storage space 
  * Most data analysis and processing will be done using open source toolkits and softwares (e.g. ImageNet, MATLAB) 
  * Google Cloud: 0.026 (storage) + free upload + 0.08 (download) per month per GB = 6.4 million USD 
  
4. Hired research personnels: 
  * Upper bound of 30 research personnels proposed for the study 
  * Yearly salary for senior computer scientist ($150,000), senior biotechnology scientist ($120,000), regular research scientist ($80,000), recruited part-time physicians ($200,000) 
  * Cost estimate for a team of 5 CS experts, 5 neuroimaging experts, 15 research scientists, and 5 part-time neurosurgeons = 35.5 million USD 
  
5. Basic laboratory setup and gear: 
  * Estimated cost of $20,000 per year over a 10 year period = 0.2 million USD 
  * Multiuser license to laboratory information system = 0.2 million USD 
 
6. Compensation for voluntary research subjects: 
  * Cost estimate of $200 per volunteer subject (for healthy children experimental group) = 0.1 million USD 

Sources of Cost | Amount (in millions USD) 
--------------------- | ---------------------------------- 
MRI Scans | 20.1 
EM Scans | 2.0 
Data Storage/Download | 6.4 
Research Team | 35.5 
Lab Setup | 0.4 
Volunteer Subjects | 0.1 
Total | **64.5** 


## References 

[1] N., Niida, A., & Motomura, M. (2011). Diagnosis of depression by MRI scans with the use of VSRAD – a promising auxiliary means of diagnosis: a report of 10 years research. International Journal of General Medicine, 377. https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3100220/ 

[2] Open Connectome Project. (n.d.). Retrieved January 17, 2017, from http://www.openconnectomeproject.org/

[3] Random Forests Leo Breiman and Adele Cutler. (n.d.). Retrieved January 17, 2017, from https://www.stat.berkeley.edu/~breiman/RandomForests/cc_home.htm

[4] Moreland, S. C., & Bonin, L. (2015, October 13). Patient education: Depression treatment options for children and adolescents (Beyond the Basics). Retrieved January 17, 2017, from https://www.uptodate.com/contents/depression-treatment-options-for-children-and-adolescents-beyond-the-basics

[5] NITRC-R: LDDMM (n.d.). Retrieved January 17, 2017, from https://www.nitrc.org/projects/lddmm-volume/
