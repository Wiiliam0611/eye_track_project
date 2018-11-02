# eye_track_project [![GitHub](https://img.shields.io/github/license/mashape/apistatus.svg)](https://github.com/Wiiliam0611/eye_track_project/blob/master/LICENSE)

## Aim

Looking for someone who can help us solve this problem with other algorithms.
We would like to compare the impact of each feature on the visibility of the ad.

## Introduction

The goal of this project is to predict which features of an online product image will affect the attention of the consumers. With a previous experiment on 91 participants who used eye trackers to view 23 commercial images, a data set has been generate. By adopting the linear regression algorithm in machine learning, the research finds that the color’s HV, white space gaussian 3 and average saturation of a product’s picture are highly related to the viewers’ attention.


![image](https://github.com/Wiiliam0611/eye_track_project/blob/master/6911540901874_.pic.jpg)

## Background

Humans produce multiple forms of eye movement (Rayner 2009), but only fixation and saccades are used in this report. Fixation time varies between 80 and 600 milliseconds, the main information is obtained by the fixation, its regular frequency < 3 Hz, but the eyeball in this process is not completely still (Schiller 1998). Saccades are fast eye movements with a frequency of 3 times per second. The relatively stable interlaced period of the two eye saccades is called fixation (Rayner 2009). During saccades, effective visual processing is largely suppressed, and the main information is collected during the fixation, but this does not mean that the saccades information is useless information.
<br>
Eye tracking technology tracks the gaze point by measuring the position of the eye's gaze point or the movement of the eyeball relative to the head.
<br>
The eye movement data used in this report contains the time and number of times the subject fixations and saccades(Hervet et al. 2011). The subject image is divided into small pieces and the current position information is collected to determine whether the information contained in the advertisement is valued.


## Contributing

Our Team will test your algorithms with our database.
Please follow the workflow below: 
1. Fork the repository.
2. Clone the project to your computer.
3. Work on your fork and make your additions algorithms.
4. Commit changes to your own branch.
5. Submit a Pull request.
6. Waiting for your algorithm testing report.


## Data Feature description


The data used in this project is mainly from Dr Yina Li’s research. In her research, she conducted an experiment which included 81 participants. Each of them was asked to watch 23 different screenshots of product lists which were from eBay, Alibaba, and Amazon. When they were watching the screenshots, an eye track device was used to record the eye movement of the testers. In the end, 634485 pieces of data has been recorded as row data with 83 attributes.
The other part of data is from Dr Yina Li’s another research. In this research, Dr Li et al developed an algorithm which can calculate color richness, stroke thickness and other features of a given picture. By adopting this technique, the 23 different screenshots were divided into 228 product pictures with 23 calculated features. 


[Detail Description](https://github.com/Wiiliam0611/eye_track_project/blob/master/Intro%20of%20Varible.docx)

## License (MIT)
[License](https://github.com/Wiiliam0611/eye_track_project/blob/master/LICENSE)

## Reference

Hervet G., Guérard, K., Tremblay S & Chtourou, M. S. 2011, ‘Is banner blindness genuine? Eye tracking Internet text advertising’, viewed 5 October, < https://onlinelibrary.wiley.com/doi/abs/10.1002/acp.1742>.

Rayner, K. 2009, ‘The thirty fifth Sir Frederick Bartlett Lecture: eye movements and attention in reading, scene perception, and visual search’, viewed 10 October, < https://doi.org/10.1080/17470210902816461>.

Schiller, P. H., 1998, ‘The neural control of visually guided eye movements’, Cognitive Neuroscience, viewed 7 October, <http://www.psy.vanderbilt.edu/faculty/schall/pdfs/nselconv.pdf>.


