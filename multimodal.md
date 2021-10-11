## Welcome to Navigating Audio-Visual Event Detection Across Mismatched Modalities

**DEMOs are here!**

> We use our model to separately parse the event of three modalities: Audio, Visual and Audio-Visual. Audio-Visual means an event happens simultaneously in audio and video.
> Our model predicts the onset(s) and offset(s) of each event. Here yellow represents audio, blue indicates video and green (blue+yellow) means audio-visual, same as the paper.
> The cutline is as follows:

<img src="src/multimodal/cutline.png" align="middle" alt="cutline" width="352" height="62"/>



### Parsing result from VEBA test set: 
> These are videos chosen from our VEBA dataset (test set), the parsing result from our model is presented below each video.
> We annotate the onset and offset for all of the videos in our VEBA test set for performance evaluation.
> Here, for each case, we list the ground truth (annotation from VEBA) along with the real parsing output from our model below.

#### Case 1:

<video width="480" height="270" controls>
    <source src="src/multimodal/VEBA/1HNGJDppKG0_60.000_70.000.mp4" type="video/mp4">
</video>

##### Groud Truth:

<img src="src/multimodal/VEBA/1HNGJDppKG0_gt.png" alt="1HNGJDppKG0_0" width="500" height="34"/>

##### Ours:

<img src="src/multimodal/VEBA/1HNGJDppKG0_ours.png" alt="1HNGJDppKG0_1" width="500" height="34"/>

#### Case 2:

<video width="480" height="270" controls>
    <source src="src/multimodal/VEBA/-2RPPODqLy4_30.000_40.000.mp4" type="video/mp4">
</video>

##### Groud Truth:

<img src="src/multimodal/VEBA/-2RPPODqLy4_gt.png" alt="-2RPPODqLy4_0" width="500" height="42"/>

##### Ours:

<img src="src/multimodal/VEBA/-2RPPODqLy4_ours.png" alt="-2RPPODqLy4_1" width="500" height="42"/>

#### Case 3:

<video width="480" height="270" controls>
    <source src="src/multimodal/VEBA/Am5GHLnpl44_30.000_40.000.mp4" type="video/mp4">
</video>

##### Groud Truth:

<img src="src/multimodal/VEBA/Am5GHLnpl44_gt.png" alt="Am5GHLnpl44_0" width="500" height="50"/>

##### Ours:

<img src="src/multimodal/VEBA/Am5GHLnpl44_ours.png" alt="Am5GHLnpl44_1" width="500" height="67"/>




### A Revise on original labels from AVE dataset: 
> These are videos chosen from the AVE dataset, where the annotated events are all audio-visual. 
> We put a comparison between our parsing result and the original labels to demonstrate the potential of our model in refining previous audio-visual labels.

#### Case 1:

<video width="480" height="270" controls>
    <source src="src/multimodal/AVE/0lFf-HP86Q0.mp4" type="video/mp4">
</video>

##### Original:
<img src="src/multimodal/AVE/0lFf-HP86Q0_ori.png" alt="0lFf-HP86Q0_0" width="500" height="21"/>

##### Ours: 

<img src="src/multimodal/AVE/0lFf-HP86Q0_ours.png" alt="0lFf-HP86Q0_1" width="500" height="21"/>

#### Case 2:

<video width="480" height="270" controls>
    <source src="src/multimodal/AVE/16eUxQwxxbs.mp4" type="video/mp4">
</video>

##### Original:
<img src="src/multimodal/AVE/16eUxQwxxbs_ori.png" alt="22olCB3wQaA_0" width="500" height="21"/>

##### Ours: 

<img src="src/multimodal/AVE/16eUxQwxxbs_ours.png" alt="22olCB3wQaA_1" width="500" height="42"/>

#### Case 3:

<video width="480" height="270" controls>
    <source src="src/multimodal/AVE/22olCB3wQaA.mp4" type="video/mp4">
</video>

##### Original:

<img src="src/multimodal/AVE/22olCB3wQaA_ori.png" alt="22olCB3wQaA_0" width="500" height="21"/>

##### Ours:

<img src="src/multimodal/AVE/22olCB3wQaA_ours.png" alt="22olCB3wQaA_1" width="500" height="42"/>
