---
title: 3. Dummy data and privacy
layout: default
nav_order: 7
has_toc: T
---

## Topic Summary
We learn about why dummy data is more practical and less risky in most situations. We also go over how to make dummy data, so you feel empowered to make some when the time comes. 

## Learning Objectives

# Dummy Data

## Why make dummy data
Because of data privacy, can’t always upload data to AIs, but being able to do this is helpful when troubleshooting code or just building an analysis. Advanced coders use dummy data all the time. In addition, having fake data to work with allows you to know the results of statistical tests, which is always a good way to check code. 

## Making a dummy dataset
### What makes a good dummy dataset
The most useful fake datasets have a few qualities.
1.	Small
2.	Big differences between treatment groups (to see the difference easily in plots and guarantee a significant result when testing statistical models)
3.	Similar to what your real data look like. For example if your data have three treatment groups that were measured on two different days, your fake data should also have this. Fake data should also replicate the structure of your data. So if your real data have measurements for each day in different columns, your fake data should also have that structure. 
### Let's make one!
#### in R

An example of making a dummy dataframe in R. <strong>This is the way to go if you have more complex data structures.</strong> Make sure that the format you save the summy data in is the same as your real data. 
```

## make vectors
patient_id = c("1", "2", "3", "4", "5",
              "1", "2", "3", "4", "5")
day = c("1", "1","1","1","1",
        "2","2","2","2","2")
distance_ran = c("400", "350", "351", "410", "310", 
                 "6000", "5250", "5265", "6150", "4650") # distances for day 2 all 15 x day 1 values

## make a dataframe
run_train = data.frame(patient_id, day, distance_ran)

## can then save as a .csv file that can be uploaded to ChatGPT
write.csv(run_train, “run_train.csv”)

```

<div style="margin-left: 5%; margin-top: 20px; margin-bottom: 40px">
<img src="images/run_data.png" alt="new dataframe screenshot" width="30%"/>
</div>

#### In Excel
<strong>This is the way to go if you have simple data structures </strong>. 
Write out the values in an Excel document and save it in the same format that your real data are in.

## Upload the dummy data to ChatGPT
Upload the data to ChatGPT (button circled in blue) and ask it for summary stats. 
<div style="margin-left: 5%; margin-top: 20px; margin-bottom: 40px">
<img src="images/chat_upload.png" alt="showing where the upload button is" width="50%"/>
</div>

# Data Privacy
