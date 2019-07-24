title: A System for Efficient 3D-Printed Stop-Motion Face Animation
author: Rinat Abdrashitov, Alec Jacobson, Karan Singh
html header: <meta property="og:image" content="http://www.dgp.toronto.edu/projects/stop-motion-faces/teaser.jpg" />
<meta property="og:description" content="Computer animation in conjunction with 3D printing has the potential to positively impact traditional stop-motion animation. As 3D printing every frame of a computer animation is prohibitively slow and expensive, 3D printed stop-motion can only be viable if animations can be faithfully reproduced using a compact library of 3D printed and efficiently assemblable parts.  We thus present the first system for processing computer animation sequences (typically faces) to produce an optimal set of replacement parts for use in 3D printed stop-motion animation.  Given an input animation sequence of topology invariant deforming meshes, our problem is to output a library of replacement parts and per-animation-frame assignment of the parts, such that we maximally approximate the input animation, while minimizing the amount of 3D printing and assembly.  Inspired by current stop-motion workflows, a user manually indicates which parts of the model are preferred for segmentation; then, we find curves with minimal deformation along which to segment the mesh. We then present a novel algorithm to zero out deformations along the segment boundaries, so that replacement sets for each part can be interchangeably and seamlessly assembled together. The part boundaries are designed to ease 3D printing and instrumentation for assembly. Each part is then independently optimized using a graph-cut technique to find a set of replacements, whose size can be user defined, or automatically computed to adhere to a printing budget or allowed deviation from the original animation. Our evaluation is threefold: we show results on a variety of facial animations, both digital and 3D printed, critiqued by a professional animator; we show the impact of various algorithmic parameters; and compare our results to naive solutions. Our approach can reduce the printing time and cost significantly for stop-motion animated films." ></meta>
<meta name="twitter:card" content="summary"></meta>
<meta name="og:title" content="A System for Efficient 3D-Printed Stop-Motion Face Animation"></meta>
css: style.css

# A System for Efficient 3D-Printed Stop-Motion Face Animation

<div class=authors>

Rinat Abdrashitov, Alec Jacobson, Karan Singh

University of Toronto

</div>

![](teaser.jpg)

## Abstract
Computer animation in conjunction with 3D printing has the potential to positively impact traditional stop-motion animation. As 3D printing every frame of a computer animation is prohibitively slow and expensive, 3D printed stop-motion can only be viable if animations can be faithfully reproduced using a compact library of 3D printed and efficiently assemblable parts.  We thus present the first system for processing computer animation sequences (typically faces) to produce an optimal set of replacement parts for use in 3D printed stop-motion animation.  Given an input animation sequence of topology invariant deforming meshes, our problem is to output a library of replacement parts and per-animation-frame assignment of the parts, such that we maximally approximate the input animation, while minimizing the amount of 3D printing and assembly.  Inspired by current stop-motion workflows, a user manually indicates which parts of the model are preferred for segmentation; then, we find curves with minimal deformation along which to segment the mesh. We then present a novel algorithm to zero out deformations along the segment boundaries, so that replacement sets for each part can be interchangeably and seamlessly assembled together. The part boundaries are designed to ease 3D printing and instrumentation for assembly. Each part is then independently optimized using a graph-cut technique to find a set of replacements, whose size can be user defined, or automatically computed to adhere to a printing budget or allowed deviation from the original animation. Our evaluation is threefold: we show results on a variety of facial animations, both digital and 3D printed, critiqued by a professional animator; we show the impact of various algorithmic parameters; and compare our results to naive solutions. Our approach can reduce the printing time and cost significantly for stop-motion animated films.

## Downloads
 - [Paper](a-system-for-efficient-3d-printed-stop-motion-face-animation-tog-2019-abdrashitov-et-al.pdf)
 - [Paper (low res)](a-system-for-efficient-3d-printed-stop-motion-face-animation-tog-2019-compressed-abdrashitov-et-al.pdf)
 - [Video](a-system-for-efficient-3d-printed-stop-motion-face-animation-tog-2019-abdrashitov-et-al.mp4)

## Video

<iframe width="560" height="315" src="https://www.youtube.com/embed/fCyJ-HZ7AT4" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<!-- Embed Youtube video here -->

## BibTeX

```
@article{Abdrashitov:StopMotionFaces:2019,
  title={A System for Efficient 3D-Printed Stop-Motion Face Animation},
  author={Rinat Abdrashitov and Alec Jacobson and Karan Singh},
  year = {2019},
  journal = {ACM Transactions on Graphics}, 
}
```

## Acknowledgements 
This work is funded in part by NSERC Discovery, the Canada Research Chairs Program, Fields Institute CQAM Labs, and gifts from Autodesk, Adobe, and MESH. We thank members of the dgp at University of Toronto for discussions and draft reviews.

<!-- `multimarkdown --process-html -o index.{html,md}` -->

