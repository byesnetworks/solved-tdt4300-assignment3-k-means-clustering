Download Link: https://assignmentchef.com/product/solved-tdt4300-assignment3-k-means-clustering
<br>
<h2>1       k-Means Clustering</h2>

<h3>1.1      Assignment</h3>

This is a programming part of the assignment. Your task is to implement the k-means clustering algorithm and assess the quality of the outputs by calculating Silhouette Coefficient. You are given a Jupyter Notebook<a href="#_ftn1" name="_ftnref1"><sup>[1]</sup></a> (formerly known as the IPython Notebook) file k_means_clustering.ipynb in which you have to implement only two functions: kmeans() and silhouette_score(). Everything else has already been prepared for you. As you have maybe already guessed, the programming language of our choice is Python.

Before you start, you need to install Jupyter Notebook and Python 3. Having that done, open your terminal, navigate to a folder with the k_means_clustering.ipynb file, and execute the command jupyter notebook. A window of your Internet browser should pop-up with the Jupyter Notebook interface. Open the k_means_clustering.ipynb notebook, read it carefully through, and execute it line by line. If this is new to you, get yourself familiar with the Jupyter Notebook and Python.

The assignment is very easy as you do not have to worry about anything else except the core k-means algorithm and Silhouette Coefficient. If you consider yourself a good programmer but without knowledge of Python, you should not have struggles, and you can add a new programming language to your portfolio. If you consider yourself a rather unexperienced programmer and without knowledge of Python, it is a good chance to learn new beginner friendly programming language, and gain more practice in programming. If programming scares you, seek help from other students. Use Piazza to find help if you do not know anyone. We do not have to remind you that plagiarism is not tolerable.

1

<em>Clustering                                                                                                                                     </em>2

<h2>2          Hierarchical Agglomerative Clustering (HAC)</h2>

<ul>

 <li>Explain the Hierarchical Agglomerative Clustering (HAC) and the difference between MINlink and MAX-link.</li>

 <li>You are given a two-dimensional dataset shown in Table 1. Perform HAC (for both MINlink and MAX-link) and present the results in the form of dendrogram. Use the Euclidean distance. <strong>Describe thoroughly the process and the outcome of each step.</strong></li>

 <li>Verify your results using the KNIME data analytics platform. For clarification, MIN-link and MAX-link is in KNIME referred as <em>SINGLE </em>and <em>COMPLETE </em>linkage methods. We provide you the file <em>csv </em>containing the very same data. <strong>Present a picture of your workflow and the dendrograms.</strong></li>

</ul>

<table width="91">

 <tbody>

  <tr>

   <td width="35"><em>ID</em></td>

   <td width="32"><em>x</em></td>

   <td width="25"><em>y</em></td>

  </tr>

  <tr>

   <td width="35">A</td>

   <td width="32">4</td>

   <td width="25">3</td>

  </tr>

  <tr>

   <td width="35">B</td>

   <td width="32">5</td>

   <td width="25">8</td>

  </tr>

  <tr>

   <td width="35">C</td>

   <td width="32">5</td>

   <td width="25">7</td>

  </tr>

  <tr>

   <td width="35">D</td>

   <td width="32">9</td>

   <td width="25">2</td>

  </tr>

  <tr>

   <td width="35">E</td>

   <td width="32">11</td>

   <td width="25">6</td>

  </tr>

  <tr>

   <td width="35">F</td>

   <td width="32">14</td>

   <td width="25">8</td>

  </tr>

 </tbody>

</table>

Table 1: Dataset for HAC.

<h2>3       DBSCAN Clustering</h2>

You are given following points: <em>P</em><sub>1 </sub>= (1<em>,</em>1), <em>P</em><sub>2 </sub>= (3<em>,</em>3), <em>P</em><sub>3 </sub>= (3<em>,</em>4), <em>P</em><sub>4 </sub>= (2<em>,</em>4), <em>P</em><sub>5 </sub>= (6<em>,</em>5), <em>P</em><sub>6 </sub>= (7<em>,</em>6), <em>P</em><sub>7 </sub>= (7<em>,</em>8), <em>P</em><sub>8 </sub>= (6<em>,</em>10), <em>P</em><sub>9 </sub>= (12<em>,</em>4), <em>P</em><sub>10 </sub>= (5<em>,</em>11), <em>P</em><sub>11 </sub>= (6<em>,</em>11), <em>P</em><sub>12 </sub>= (5<em>,</em>10), <em>P</em><sub>13 </sub>= (16<em>,</em>8), <em>P</em><sub>14 </sub>= (11<em>,</em>9), <em>P</em><sub>15 </sub>= (13<em>,</em>8), <em>P</em><sub>16 </sub>= (10<em>,</em>7), <em>P</em><sub>17 </sub>= (12<em>,</em>8), <em>P</em><sub>18 </sub>= (15<em>,</em>3).

<ul>

 <li>Your task is to perform DBSCAN clustering given the parameters <em>Eps </em>= 2 (Euclidean metric) and <em>MinPts </em>= 3 (including the analyzed point). Identify core, border and noise points. Identify clusters. <strong>Describe thoroughly the process and the outcome of each step.</strong></li>

 <li>Verify your results using the KNIME data analytics platform. We provide you the file <em>csv </em>containing the very same data. <strong>Present a picture of your workflow and the scatter plot with marked clusters and outliers.</strong></li>

</ul>

<em>Clustering                                                                                                                                     </em>3

<a href="#_ftnref1" name="_ftn1">[1]</a> https://jupyter.org/