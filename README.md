# Skin-Tone-Analyzer

<p align="center">
  <img width="" height="" src="http://vinslookbook.com/wp-content/uploads/2013/06/make-up-1278366_1920.jpg">
</p>

<!-- wp:paragraph -->
<p>In the <a href="http://vinslookbook.com/skin-undertone-detection/">Skin Undertone Detection Project,</a> I mentioned that there was no concrete way to analyze skin and accurately detect the undertones. Well a similar problem occurs with the skintone. Especially for girls with naturally tan skin. Here is how I would implement a skintone analyzer using Artificial Intelligence.</p>
<!-- /wp:paragraph -->

<!-- wp:heading {"level":3} -->
<h3>Principle:</h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>An individual's skin pigmentation is the result of genetics, being the product of both of the individual's biological parents' genetic makeup, and exposure to sun. The types of skintone are classified as:</p>
<!-- /wp:paragraph -->

<!-- wp:list -->
<ul><li>Type I: Light skin </li><li>Type II: Fair skin </li><li>Type III: Medium skin </li><li>Type IV: Olive skin</li><li>Type V: Tan brown skin </li><li>Type VI: Rich brown skin </li></ul>
<!-- /wp:list -->

<!-- wp:heading {"level":3} -->
<h3>Ideology:</h3>
<!-- /wp:heading -->

<!-- wp:list {"ordered":true} -->
<ol><li>Create a unique color scale with human skintones.</li><li>The user takes an image of their wrist just below their palm.</li><li>Match the color of the image with the unique color scale.</li></ol>
<!-- /wp:list -->

<!-- wp:heading {"level":3} -->
<h3>Dataset</h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p><strong>Name: Skin Dataset</strong></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><strong>Data Set Information:</strong></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>The skin dataset is collected by randomly sampling B,G,R values from face images of various age groups (young, middle, and old), race groups (white, black, and asian), and genders obtained from FERET database and PAL database. Total learning sample size is 245057; out of which 50859 is the skin samples and 194198 is non-skin samples. Color FERET Image Database:&nbsp;<a href="http://face.nist.gov/colorferet/request.html" rel="nofollow">[Web Link]</a>, PAL Face Database from Productive Aging Laboratory, The University of Texas at Dallas:&nbsp;<a href="https://pal.utdallas.edu/facedb/" rel="nofollow">[Web Link]</a>.&nbsp;<br></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><strong>Attribute Information:</strong></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>This dataset is of the dimension 245057 * 4 where first three columns are B,G,R (x1,x2, and x3 features) values and fourth column is of the class labels (decision variable y).</p>
<!-- /wp:paragraph -->

<p align="center">
  <a href="https://play.google.com/store/apps/details?id=com.vins.vinslookbook&hl=en">
  <img width="300" height="80" src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcSojpFFWqTqH_wHsjAwe--ZdKXrsSNZBDWNNz4qK8fYRX_wK0Wb&usqp=CAU"> 
</p>
