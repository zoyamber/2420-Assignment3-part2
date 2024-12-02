# **2420 Assignment 3 Part-2**

## **Introduction**


In this part of the assignment, we will build upon the skills learned in part 1 by deploying two new servers with enhanced configurations. This will allow you to deepen your understanding of web configuration, system administration, and load balancing.


## **Table of Contents**


**Task 1:** Server Setup

**Task 2:** Load Balancer

**Task 3:** Update Starter Code

**Task 4:** Update Server Configuration


## **Task 1:** Create two new digital ocean droplets running Arch Linux

The first task is to create two new digital ocean droplets with the tag `web`. These tags will be used when you setup your load balancer.


**Step 1:** Open your digital ocean account, and press the `droplets` panel on the left of the screen


**Step 2:** Next, press the blue `Create Droplet` button on the right of the screen


**Step 3:** When Navigating too choose region, select `San Franciscon`, And make sure `DataCenter 3. SFO3` is selected


**Step 4:** Next, when choosing an image select custom image and choose `Arch-Linux-x84_64-cloudimg-20240901.259602.qcow2`


**Step 5:** You may select select basic droplet size, along with Regular CPU option and $6 / mo


**Step 6:** Under `Choose Authentication Method` select SSH Key along with you SSH key


**Step 7:** Under Quantity Select `2 Droplets`, and name your Droplets `Arch-Linux-1` and `Arch-Linux-2`

**Step 8:** Lastly, under tags, type in the tag `web` and press the blue `Create Droplet` button


Verify that the droplets are running with the image below. A green dot should be beside both the names.


**img**



## **Task 2:** Creating a load balancer
