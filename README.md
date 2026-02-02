This codes are used to create models to detect fashion review fake reviews. The used dataset are reviews coming from Amazon Reviews.

The approach used here are Heterogenous Graph Neural Network with the combination of SGDCTH for Group Level Detection and SL-GAD for review-level detection. These approach are strengthen using Curriculum Learning to gradually train the level of understanding from the model to distinguish fake and genuine reviews.

The research come with a great result by exceeding the accuracy of the baseline models such as plain SL-GAD and SGDCTH.