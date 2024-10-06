# NASA International Space Apps Challenge - Seismic Detection Across the Solar System

Hi! We are Kabsa Warriors. A group of diverse people specializing in different fields. The group chose this challenge in order to address the problem in seismology missions, struggling with power requirements necessary to send continuous seismic data back to Earth. With Kabsa Warrior's creativity and thinking outside of the box, we devised another approach in gathering necessary data by compressing them into a singular and meaningful values, velocity. <br></br>

# What did we contribute in this challenge?

With the current problem in sending back seismic reading data and sending only necessary data, it takes a lot of power to send back seismic data. Instead, we converted the data (velocity) into statistical values that will determine which type of seismic event (specifically moonquake) and send that special information back to Earth for further purposes.<br></br>

# How does this help in seismic detection?

Since the seismic values have been converted into meaningful values, this type of approach helps in optimizing data size, and resulting in less power requirements sending data back to Earth. By thinking outside of the box, the group implemented this method to assist technology advancements and can be improved through adding sufficient data, as well as improving the machine learning algorithm. Now, seismologists can make a decision on values that really matter, and ultimately, determine possible events, and causes in a seismic event.<br></br>

# Testing the Kabsa Warrior's methodology!

Now, before testing the jupyter notebook that the group created, we must ensure that the file tree directory must be organized in order to avoid errors in running the source code. Make sure to complete the directory requirements below:

<br></br>
The file structure on this GitHub contains these files:

```bash
.
├── balanced_data
├── models
├── README.md
└── SeismicActivity_KW.ipynb
```

<br></br>
The final directory structure should be like this:
(Note: Download the other files here [Space Apps 2024 Seismic Detection Data Packet](https://wufs.wustl.edu/SpaceApps/data/space_apps_2024_seismic_detection.zip))

```bash
.
├── balanced_data
├── models
├── data/
│   └── lunar/
│       └── kabsawarrior_model
│       └── test
│           └── data
│               └── S12_GradeB
│               └── S15_GradeA
│               └── S15_GradeB
│               └── S16_GradeA
│               └── S16_GradeB
│       └── training
│               └── catalog
│               └── data
│               └── plots
├── SeismicActivity_KW.ipynb
└── README.md
```

<br></br>

Important things to remember:

<li> balanced_data - consists of useful aggregated data that can be used for ML testing</li>
<li> models - contains the machine learning models that were used to compare, for best testing, use Gradient Boosting Machine.</li>
<li> kabsawarrior_model - this directory contains the final output for predicting seismic event data</li>

<br></br>

# Before You Explore!

Upon completing the correct directory or file structure, you can now run 'SeismicActivity_KW.ipynb' and run each code inside the notebook. Make sure you read the contents inside before running ensure smooth demo, as well as check out the recommendation + conclusion for further development. <br></br>

_To Infinity and Beyond! -Buzz Lightyear_
