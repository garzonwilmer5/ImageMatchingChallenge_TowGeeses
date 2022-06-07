<h1>Image Matching Challenge 2022</h1>
<h2>Team towGeeses</h2>
 <ul>
  <li>Wilmer David Garzón Cáceres</li>
  <li>Juan Sebastian Santcoloma Barrera</li>
</ul>

<p> Solution of place 45/642 <b>(top 8%)</b></p>

<h3>Explanation</h3>
<p>This solution combain use the models LoFTR [1] ans SuperGlue [2] to find key point matches in a pair of images,
each image is preprocesed with geometrical transformations in order to make an augmentation of the data. 
The points coordinates finded by geometrical transformation must be returnned to original image coordinates.</p>
<p>The fundamental matrix is finded using the robust estimator MAGSAC++ [3] avalible in openCV.</p>

<h3>References</h3>
[1] J. Sun, Z. Shen, Y. Wang, H. Bao, and X. Zhou, ‘LoFTR: Detector-Free Local Feature Matching with Transformers’, CVPR, 2021.
<br/>
[2] P.-E. Sarlin, D. DeTone, T. Malisiewicz, and A. Rabinovich, ‘SuperGlue: Learning Feature Matching with Graph Neural Networks’, CVPR, 2020.
<br/>
[3]	D. Barath, J. Noskova, M. Ivashechkin, and J. Matas, ‘MAGSAC++, a fast, reliable and accurate robust estimator’. arXiv, 2019.
