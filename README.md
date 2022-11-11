# Sub-GStory
Code submission for Project - Story Generation using Scene Graphs, Term Project for Graph Machine Learning Foundations and Application (AI60007), 2022 Autumn, IIT Kharagpur

> Install Dependencies and Data as instructed in SUBGC_README.md

> Please find story generation code (training + demo) in `StoryGen/`

## Running the Demo
1. Install pretrained models and caption generations. 
> Download `https://drive.google.com/file/d/1dL9LQRjLqs_jhb8k5h2XMHO7h-NqpBDn/view?usp=sharing` and unzip inside `pretrained/`  
> Download `https://drive.google.com/file/d/1taV1acf1XmW1x0BjY1zYStqHKwTKbk3d/view?usp=sharing` and unzip inside `StoryGen/`

2. Run self-explanatory ipynb - `StoryGen/demo.ipynb`

## Training
1. For Sub-GC model training for COCO and Flickr datasets, run `bash train.sh Sub_GC_MRNN` and `bash train.sh Sub_GC_Flickr`
2. For C2S-LM model training, follow the jupyter notebook `StoryGen/seq2seq_train.ipynb`

## Inference
1. For just caption generation, run `bash test.sh Sub_GC_MRNN` and `bash test.sh Sub_GC_Flickr`
2. For full inference, follow the jupyter notebook  `StoryGen/demo.ipynb`

#### Also check out our presentation on this topic - [Link](https://github.com/Debjoy10/Sub-GStory/blob/master/Story%20Generation%20from%20Scene%20Graphs%20PPT.pdf) (Also uploaded in this repository)
### Video Presentation - [Link](https://youtu.be/qWBA0hsFRjQ)

## Contributors
1. Debjoy Saha
2. Shubhesh Anand
3. Divyanshu Sheth
