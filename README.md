# Business Understanding

To help Tensa with computer vision for their A.I. tennis ball machine.

# Data Understanding

I created the dataset used for this project. It consisted of a balanced class of approximately 6,000 images of myself hitting forehand and backhand tennis shots. The data used for this project enabled me to build a convolutional neural network model for image classification. This model will aid in the ball machine being able to detect whether a player is hitting a forehand or backhand for training purposes. The limitations of this dataset was that it was fairly small and only consisted of images of myself from a couple different camera angles.

![forehandshot](images/forehandvids_493.jpg)

# Data Preperation

   I started by filming myself in a few different locations hitting approximately 200 forehands and 200 backhands. I then used an open source editing program called "Shotcut" to edit all of my swings from the start of my swing up until the point of contact with the tennis ball. I eventually added images that included more of a complete swing. I then converted these edited video shots into an mp4 format so that they could be extracted into frames.
    I extracted the frames into folders and labeled the frames as either belonging to one of two classes, "1" for forehand and "0" for backhand. I constructed an iterator into my pipeline to be able to call on specific "batches" of data. I then scaled my data in the pipeline to make sure that all the images used were the same size.
    I then set up a train, test, split which was 80% for training, 10% for validation, and 10% for testing. I then set up a way to save and load my data after it has been trained into my pipeline so that more data could be input in the future.

# Modeling

# Evaluation

# Conclusion

## Limitations

The limitations of this dataset was that I only used images of myself hitting forehands and backhands in a few locations from a couple different camera angles. To build a more robust model I will have to add a lot more variance to the data.

## Recommendations

## Next Steps

Adding more variance to the dataset. 
Gathering images of different people hitting forehands and backhands from different camera angles in different backgrounds.


