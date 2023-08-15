# Cattle Body Parts Image Dataset for Object Detection Dataset

## Intro
This dataset is a curated collection of images featuring various cattle body parts aimed at facilitating object detection tasks. The dataset contains a total of 428 high-quality photos, meticulously annotated with three distinct classes: "Back," "Head," and "Leg."


## Motivation
Accurate and reliable identification of different cattle body parts is crucial for various agricultural and veterinary applications. This dataset aims to provide a valuable resource for researchers, developers, and enthusiasts working on object detection tasks involving cattle, ultimately contributing to advancements in livestock management, health monitoring, and related fields.

## Data 
### Overview
- Total Images: 428
- Classes: Back, Head, Leg
- Annotations: Bounding boxes for each class

### Contents
```
📦 Cattle_Body_Parts_OD.zip
 ┣ 📂 images
 ┃  ┣ 📜 image1.jpg
 ┃  ┣ 📜 image2.jpg
 ┃  ┗ ...
 ┗ 📂 annotations
    ┣ 📜 image1.json
    ┣ 📜 image2.json
    ┗ ...
```

### Annotation Format
Each annotation file corresponds to an image in the dataset and is formatted as per the [LabelMe](https://github.com/wkentaro/labelme) [JSON](https://www.json.org/json-en.html) standard. These annotations define the bounding box coordinates for each labeled body part, enabling straightforward integration into object detection pipelines.

## License
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
