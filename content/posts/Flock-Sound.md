---
title: "Flock Music"

---
 a collaboration with the <font size="4.5">Itay Niv </font>


<font size="6"> Flock Sound </font> - [click HERE](http://flocksound.live/) </font>







<u>The concept - </u>

Create an application that generates a t-SNE map of selected audio data, and have an "outsider" to trigger the samples in the browser.

<u>The process - </u>

Using Gene Kogan's ML4A guides, t-SNE audio Python script,
we analyzed and segmented large quantities of audio data.
Using principal component analysis, we ended up with a 2D vector map of sound-similarities represented in a JSON file.

We started to experiment with the performative aspect of the output. Initially playing back samples using video to trigger the samples through pixel analysis. The video-triggering seemed less interesting, and we were looking for a more organic generation.

![](/gallery/images/Flock/tsne.png)

So, we took the p5 Flocking example and decided to fit it into our application and have the flocking objects trigger the samples.

Developing the Javascript code was not easy, to say the least. We ran into a-lot of problem as we were infusing the Flocking code (which is very intricate) into our t-SNE layout code.

The biggest challenge, as always, is finding the right data (audio) that would create an interesting generation, and will also work well with the t-SNE app - meaning that the analysis would create organic segments that sound good.

![](https://media.giphy.com/media/5WgXy1nTB7bTyQUktL/giphy.gif)
