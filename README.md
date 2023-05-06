Download Link: https://assignmentchef.com/product/solved-ece495-assignment-4-object-detection-with-ssd
<br>
<ul>

 <li>Continue gaining experience with PyTorch and helper libraries</li>

 <li>Understand the VOC Object Detection Dataset</li>

 <li>Train and evaluate the SSD neural network architecture</li>

 <li>Perform an ablation study testing a different base network and learning rate schedule</li>

 <li>Learn the Non-Maximum Suppression (NMS) algorithm</li>

</ul>




<strong>Resources and Instructions </strong><u>Environment Setup:</u>

We recommend using Google Colab to complete this assignment.

<ol>

 <li>Create a folder called “ece495_assignment4” within your Google Colab “Colab Notebooks” folder.</li>

 <li>Upload the assignment ipynb, utils.py and json files to the Google Colab “ece495_assignment4” folder</li>

 <li>Open the assignment

  <ul>

   <li>Runtime -&gt; change runtime type</li>

   <li>Set hardware accelerator to GPU</li>

   <li></li>

  </ul></li>

</ol>




<u>Assignment:</u>

<ol start="2">

 <li>Ablation study on using a different network base

  <ul>

   <li>Model A: Train and evaluate the SSD network with the default VGG base.</li>

   <li>Model B: Implement the ResNetBase class. Then train and evaluate this model.</li>

  </ul></li>

 <li>Ablation study on updating the learning rate

  <ul>

   <li>Model C: Train and evaluate the SSD network with the default VGG base but also with a PyTorch learning rate scheduler.</li>

  </ul></li>

 <li>Answer 2 questions on the differences from the NMS pseudo code described in the lectures / tutorial and the implemented version in the code.</li>

</ol>




<u>Deliverable HTML output:</u>

In the Jupyter notebook, go to File &gt; Download as &gt; HTML (.html) Submit a ZIP file containing the HTML output. Please follow the naming convention of your zip file: a4_&lt;user_id&gt;.zip