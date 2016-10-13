<h1>The Sports-1M Dataset</h1>

![http://cs.stanford.edu/people/karpathy/deepvideo/sz70sx.jpg](http://cs.stanford.edu/people/karpathy/deepvideo/sz70sx.jpg)

Academic dataset that accompanies the paper "[Large-scale Video Classiﬁcation with Convolutional Neural Networks.](http://cs.stanford.edu/people/karpathy/deepvideo/)" (Andrej Karpathy, George Toderici, Sanketh Shetty, Thomas Leung, Rahul Sukthankar, Li Fei-Fei).

This dataset contains 1,133,158 video URLs which have been annotated automatically with [487 labels](https://github.com/gtoderici/sports-1m-dataset/blob/master/labels.txt). The annotation was done via the [YouTube Topics API](https://developers.google.com/youtube/v3/guides/searching_by_topic). If you wish to use the YouTube API yourself, we have provided the topic ID for each of the classes [here](https://github.com/gtoderici/sports-1m-dataset/blob/master/sports_mids.txt). Example thumbnails for each class can be found [here](http://cs.stanford.edu/people/karpathy/deepvideo/classes.html).


## Getting the Data ##

If you'd like to download the necessary files for this benchmark, run the following command:
```
git clone https://github.com/gtoderici/sports-1m-dataset.git
```

Once you have downloaded the data, please read the [README](https://github.com/gtoderici/sports-1m-dataset/blob/master/README) file in order to see how to use this data.

## Text File Format ##
The [487 labels](https://github.com/gtoderici/sports-1m-dataset/blob/master/labels.txt) file is encoded in UTF-8. Therefore, in order to be able to read all the label names correctly you need to make sure that you are using an UTF-8 compatible text editor.

## Freebase Machine IDs/YouTube Topic ID#

The [sports_mid.txt](https://github.com/gtoderici/sports-1m-dataset/blob/master/sports_mids.txt) file lists the machine ID followed by a comma and the class ID (matching the 487 labels).

## Notes ##
There is a [discussion group](https://groups.google.com/forum/#!forum/sports-1m-dataset) about this dataset. Please post specific questions there, and group members may be able to help.

## Related Datasets ##

Google Research has announced the availability of the [YouTube-8M](https://research.google.com/youtube8m/) dataset. Sports-1M is included within this new dataset, with frame-level features already extracted. If computational complexity is a concern (i.e., it is not feasible to extract features from Sports-1M), we highly recommend this new dataset, since it already provides the features.
