---
layout: page
title: Enhancing STEM Education using Augmented Reality and Machine Learning
titleshort: STEM Mobile App
img: assets/img/aurel/preview.jpg
importance: 2
category: work
related_publications: false
---

<h2>Abstract</h2>

Learning Science, Technology, Engineering andMathematics (STEM) in the 21st century has been evolved from the conventional textbook to the interactive platform using electronic devices. This paper presents the implementation of a mobile application system, named AUREL (Augmented Reality Learning) in enhancing the learning experience by projecting Augmented Reality (AR) objects onto 2D images. This AR visualization is used to improve the understanding of STEM subjects and increases the enthusiasm of students towards STEM subjects. In this implementation, Google’s Cloud Tensor Processing Units (TPUs) are used to train specific datasets alongside Cloud Vision API to detect a wide range of objects. MLKit for Firebase is used to host the custom TensorFlow Lite models for specific use cases for better accuracy. On the other hand, Google Cloud Platform (GCP) is used to harvest STEM data, manage STEM 3D information and data processing. Subsequently, the processed information will be displayed in AR in the mobile application using ARCore’s Sceneform SDK. The application of AUREL could be extended to all science subjects so that students can learn using an interactive platform.




<h2>Application Pipeline</h2>

<div class="row">
    <div class="col-sm-9 mt-3 mt-md-0 mx-auto">
        {% include figure.liquid loading="eager" path="assets/img/aurel/flow.png" title="example image" class="img-fluid rounded z-depth-0" %}
    </div>
</div>


<h2>Multistage Inferencing Approach</h2>

<div class="row">
    <div class="col-sm-8 mt-3 mt-md-0 mx-auto">
        {% include figure.liquid loading="eager" path="assets/img/aurel/approach.png" title="example image" class="img-fluid rounded z-depth-0" %}
    </div>
</div>
<div class="caption">
    (a) All-in-one Network vs (b) Multistage Inferencing Approach
</div>



<h2>Experiments and Results</h2>

<div class="row">
    <div class="col-sm mt-3 mt-md-0 mx-auto">
        {% include figure.liquid loading="eager" path="assets/img/aurel/table1.png" title="example image" class="img-fluid rounded z-depth-0" %}
    </div>
</div>

<div class="row">
    <div class="col-sm-9 mt-3 mt-md-0 mx-auto">
        {% include figure.liquid loading="eager" path="assets/img/aurel/heart.png" title="example image" class="img-fluid rounded z-depth-0" %}
    </div>
</div>






<!-- You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}. -->



<h2>Reference</h2>


Conference paper is available [here](/assets/pdf/ang2019enhancing.pdf)
Journal extension is available [here](/assets/pdf/ang2020multistage.pdf)

If you find this work useful, please cite us:
{% raw %}

```html
@inproceedings{ang2019enhancing,
  title = {Enhancing STEM education using augmented reality and machine learning},
  author = {Ang, Ivan and Lim, King Hann},
  booktitle = {2019 7th International Conference on Smart Computing \& Communications (ICSCC)},
  pages = {1--5},
  year = {2019},
  organization = {IEEE},
}
```

{% endraw %}
