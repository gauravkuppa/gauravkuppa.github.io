---
title: "ShineOn: Illuminating Design Choices for Practical Video-based Virtual Try-on"
collection: publications
permalink: /publication/2010-10-01-paper-title-number-2
excerpt: 'This paper is about the number 2. The number 3 is left for future work.'
date: 2010-10-01
venue: 'Journal 1'
paperurl: 'http://academicpages.github.io/files/paper2.pdf'
citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---
[* denotes equal contribution]

**Gaurav Kuppa** *, Andrew Jong *, Vera Liu, Ziwei Liu, and Teng Moh

Generation of Human Behavior Workshop at WACV 2021. 

<details>
<summary><b>Abstract</b></summary>
Virtual try-on has garnered interest as a neural rendering benchmark task to evaluate complex object transfer and scene composition.
Recent works in virtual clothing try-on feature a plethora of possible architectural and data representation choices.
However, they present little clarity on quantifying the isolated visual effect of each choice, nor do they specify the hyperparameter details that are key
to experimental reproduction. Our work, ShineOn, approaches the try-on task from a bottom-up approach and aims to shine light on the visual and quantitative effects of each experiment. 
We build a series of scientific experiments to isolate effective design choices in video synthesis for virtual clothing try-on.
Specifically, we investigate the effect of different pose annotations, self-attention layer placement, and activation functions on the quantitative and qualitative performance of video virtual try-on. 
We find that DensePose annotations not only enhance face details but also decrease memory usage and training time.
Next, we find that attention layers improve face and neck quality. Finally, we show that GELU and ReLU activation functions are the most effective in our experiments despite the appeal of newer activations such as Swish and Sine.
We will release a well-organized code base, hyperparameters, and model checkpoints to support the reproducibility of our results.
We expect our extensive experiments and code to greatly inform future design choices in video virtual try-on. 
Our code may be accessed at https://github.com/andrewjong/ShineOn-Virtual-Tryon.
</details> 

[ [Paper (preprint coming soon)]() ] [ [Code (coming soon)](https://github.com/andrewjong/ShineOn-Virtual-Tryon) ]