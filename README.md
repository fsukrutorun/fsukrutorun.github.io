<!--
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
saved from url=(0037)http://www.cs.bilkent.edu.tr/~sukruf/ 
<html xmlns="http://www.w3.org/1999/xhtml"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
-->
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">

<head>
<meta http-equiv="content-type" content="text/html; charset=UTF-8" />
<meta name="description" content="Fahreddin Sukru Torun" />
<meta name="keywords" content="Sukru Torun, Fahreddin Sukru Torun, F. Sukru Torun"/>

<script type="text/javascript">
function toggleMe(a){
  var e=document.getElementById(a);
  if(!e)return true;
  if(e.style.display=="none"){
    e.style.display="block"
  } else {
    e.style.display="none"
  }
  return true;
}

function switchTo(a){
  var e=document.getElementById(a);
  if(!e)return true;
  document.getElementById("publications").style.display="none";
  document.getElementById("projects").style.display="none";
  document.getElementById("schedule").style.display="none";
  document.getElementById("publications_button").style.fontWeight="normal";
  document.getElementById("projects_button").style.fontWeight="normal";
  document.getElementById("schedule_button").style.fontWeight="normal";
  e.style.display="block";
  document.getElementById(a.concat("_button")).style.fontWeight="bold";
  return true;
}

</script>

<title>F. Şükrü Torun</title>
<link rel="stylesheet" href="style.css" type="text/css" />
</head><body>
<div id="testdiv">
<table>
      <tr>
        <td>
          <img src="me1.jpg" style="float:left; margin-right:10px" height="250"/>
        </td>
        <td>
          <h3d>Fahreddin Şükrü Torun</h3d><br/>
          
          <h2>Asst. Prof.  at <a href="http://www.aybu.edu.tr"> Ankara Yildirim Beyazit University </a> in  
          Computer Engineering Department. </br>		
				
          email: <a href="mailto:ftorun@ybu.edu.tr">ftorun at ybu.edu.tr</a>, 
          <a href="mailto:fsukrutorun@gmail.com">fsukrutorun@gmail.com</a><br/>
          website: <a href="https://avesis.aybu.edu.tr/ftorun"> avesis.aybu.edu.tr/ftorun </a> <br/>
<!--
my CV: <a href="cv.pdf">pdf</a>
-->
</h2>

<p>I am an assistant professor at Computer Engineering Department of Ankara Yildirim Beyazit University, Turkey.
Prior to joining AYBU, I was a postdoctoral researcher at APO (Algorithmes Parallèles et Optimisation-Parallel Algorithms and Optimization) Team in IRIT/CNRS - ENSEEIHT, Toulouse, FRANCE.
I got my PhD. from Bilkent University as a member of the Parallel and Distributed Computing Lab under the supervision of Prof. Cevdet Aykanat and Assoc. Prof. Murat Manguoglu.
My main area of research is parallel scientific computing.
I am interested in algorithm development, parallel and distributed programming, iterative and direct linear system solvers and graph-hypergraph partitioning.   
<br/>
</p>

</td>
</tr>
</table>
	
  <div class="button"><strong><span style="font-style: italic;">Research Interests</span></strong><em></em></div>
  <p>
  <ul>
	<li>High Performance Computing</li>
   <li>Parallel and distributed programming</li>	
	<li>Graph and Hyperhraph Partitioning</li>
   <li>Numerical Linear Algebra</li>
	<li>Parallel Iterative Solvers </li>
	<li>Parallel Sparse Matrix-Vector Multiplication</li>
  </ul>
  </p>
	<p></p>
  
  
  <table style="width:100%">
  <tr>
    <td width="20%">       
<!--
      <div id="publications_button" class="button" style="font-weight: bold;" onclick="return switchTo(&#39;publications&#39;)"><span style="font-style: italic;">Publications</span><em></em></div>
-->
      <div id="pub_button" class="button" ><span style="font-style: italic;"></span><em></em> <a href="#publications">Selected Publications </a> </div>
    </td>
    <td width="20%">     
      <div id="soft_button" class="button" ><span style="font-style: italic;"></span><em></em> <a href="#software"> Software </a> </div>
    </td>    
    <td width="20%">       
      <div id="pro_button" class="button" ><span style="font-style: italic;"></span><em></em> <a href="#projects"> Projects </a> </div>
    </td>
    <td width="20%">       
      <div id="teaching_button" class="button" ><span style="font-style: italic;"></span><em></em> <a href="#teaching"> Teaching </a> </div>
    </td>
    <td width="20%">
      <div id="schedule_button" class="button" ><span style="font-style: italic;"></span><em></em> <a href="#schedule"> Schedule </a> </div>
    </td>
  </tr>
</table>
	
<div id="publications" style="display:block">
<table>

<tr>
      <td>
        <h1>Improving the scalability of the ABCD Solver with a combination of new load balancing and communication minimization techniques
</h1>
        <p><h3b><i>Iain Duff, Philippe Leleux, Daniel Ruiz, F. Sukru Torun</i> </h3b>
          <br/><h3c>PARCO 2019, Prague, Czech Republic, 10-13 September 2019</h3c>
        </p>	
        <div id="Underdetermined">       
The hybrid scheme block row-projection method implemented
in the ABCD Solver is designed for solving large sparse unsymmetric
systems of equations on distributed memory parallel computers. The
method implements a block Cimmino iterative scheme, accelerated with
a stabilized block conjugate gradient algorithm.  An augmented pseudodirect variant has also been developed to overcome convergence issues.
<a onclick="return toggleMe('underabs')">More</a>
<div id="underabs" style="display:none">
Both methods are included in the ABCD solver with a hybrid parallelization
scheme. The parallel performance of the ABCD Solver is improved
in the first non-beta release, version 1.0, which we present in this
paper. Novel algorithms for the distribution of partitions to processes
are introduced to minimize communication as well as to balance the
workload. Furthermore, the master-slave approach on each subsystem
is also improved in order to achieve higher scalability through run-time
placement of processes. We illustrate the improved parallel scalability
of the ABCD Solver on a distributed memory architecture by solving
several problems from the SuiteSparse Matrix Collection.
 </div>
 <br>
 <br>
 		  <a href="https://www.conftool.org/parco2019/sessions.php">Conference Program</a>
		  <br/>        
         
        <br/>
        <p></p>
        </div>  
    </td>
    <td><img src="web1.png" alt="Placement of Slaves" style="float:left; margin-bottom:10px" width="250"/>    
    </td>
  </tr>

  <tr>
      <td>
        <h1>Parallel Minimum Norm Solution of Sparse Block Diagonal Column Overlapped Underdetermined Systems</h1>
        <p><h3b><i>F. Sukru Torun, Murat Manguoglu, Cevdet Aykanat</i> </h3b>
          <br/><h3c>ACM Transactions on Mathematical Software (TOMS), Volume 43 Issue 4, No:31 (January 2017), 21 pages.<a href="http://dl.acm.org/authorize?N21577" title="Parallel Minimum Norm Solution of Sparse Block Diagonal Column Overlapped Underdetermined Systems"> Download</a>
          <!-- <iframe src="http://dl.acm.org/authorizestats?N21577" width="100%" height="20" scrolling="no" frameborder="0">frames are not supported</iframe> -->

          <a href="http://dl.acm.org/citation.cfm?id=3004280">http://dl.acm.org/citation.cfm?id=3004280</a> <br/>


        </h3c>
        </p>	
        <div id="Underdetermined">
        Underdetermined systems of equations in which the minimum norm solution needs to be 
computed arise in many applications, such as geophysics, signal processing, and 
biomedical engineering. In this article, we introduce a new parallel algorithm for 
obtaining the minimum 2-norm solution of an underdetermined system of equations. 
The proposed algorithm is based on the Balance scheme, which was originally developed 
for the parallel solution of banded linear systems.
	The proposed scheme assumes a 
generalized banded form where the coefficient matrix has column overlapped block 
structure in which the blocks could be dense or sparse.
<a onclick="return toggleMe('underabs')">More</a>
<div id="underabs" style="display:none">In this article, we implement
 the more general sparse case. The blocks can be handled independently by any existing 
 sequential or parallel QR factorization library. A smaller reduced system is formed 
 and solved before obtaining the minimum norm solution of the original system in 
 parallel. We experimentally compare and confirm the error bound of the proposed 
 method against the QR factorization based techniques by using true single-precision
  arithmetic. We implement the proposed algorithm by using the message passing paradigm.
   We demonstrate numerical effectiveness as well as parallel scalability of the 
   proposed algorithm on both shared and distributed memory architectures for
 solving various types of problems.
 </div>
        <br/>
        <p></p>
        </div>  
    </td>
    <td><img src="under1.png" alt="Underdetermined System" style="float:left; margin-bottom:10px" width="250"/>    
    </td>
  </tr>
  
  
   <tr>
      <td>
        <h1>Solving Sparse Underdetermined Linear Least Squares Problems on Parallel Computing Platforms</h1>
        <p><h3b><i>F. Sukru Torun, Murat Manguoglu, Cevdet Aykanat</i> </h3b>
          <br/><h3c>17th SIAM Conference on Parallel Processing for Scientific Computing, April 12-15 2016, Paris-France. <a href="http://meetings.siam.org/sess/dsp_programsess.cfm?SESSIONCODE=23009">link</a> <br/></h3c>
          <h3c>Chair of the Matrix Factorization Session</h3c>
          <br/>        
        </p>
        <div id="SIAM">
        Computing the minimum 2-norm solution is essential for many areas such as geophysics, signal processing and biomedical engineering. 
        In this work, we present a new parallel algorithm for solving sparse underdetermined linear systems where the coefficient matrix is block diagonal with overlapping columns. 
        The proposed parallel approach handles the diagonal blocks independently and the reduced system involving the shared unknowns. 
        Experimental results show the effectiveness of the proposed scheme on various parallel computing platforms.
		  <br/>
		  <a href="2016siamPP16.pptx">Slides</a>
		  <br/>        
        
        <p></p>
        </div>  
    </td>
    <td>
		<p><img src="under5.png" style="float:left; margin-bottom:10px" width="250"/>
		</p>
    </td>
  </tr>
  <tr>
      <td>
        <h1>A Novel Partitioning Method for Accelerating the Block Cimmino Algorithm </h1>
        <p><h3b><i>F. Sukru Torun, Murat Manguoglu, Cevdet Aykanat</i> </h3b>
          <br/><h3c>SIAM Journal on Scientific Computing (SISC), 40(6), C827–C850. (December 2018) </h3c>
        </p>
        <div id="simax">
        We propose a novel block-row partitioning method in order to improve the convergence rate of the block Cimmino algorithm for solving general sparse linear systems of equations. 
        The convergence rate of the block Cimmino algorithm depends on the orthogonality among the block rows obtained by the partitioning method. 
        The proposed method takes numerical orthogonality among block rows into account by proposing a row inner-product graph model of the coefficient matrix. 
        In the graph partitioning formulation defined on this graph model, the partitioning objective of minimizing the cutsize directly corresponds to minimizing the sum of inter-block inner products between block rows thus leading to an improvement in the eigenvalue spectrum of the iteration matrix. This in turn leads to a significant reduction in the number of iterations required for convergence. 
        Extensive experiments conducted on a large set of matrices confirm the validity of the proposed method against a state-of-the-art method.
        <a href="https://epubs.siam.org/doi/10.1137/18M1166407">Paper</a> 
 </div>
        <br/>
        <p></p>
        </div>  
    </td>
    <td><img src="simax1.png" alt="Block Cimmino" style="float:left; margin-bottom:10px" width="250"/>    
    </td>
  </tr>


 <tr>
      <td>
        <h1>Minimizing Communication Through Computational Redundancy in Parallel Iterative Solvers</h1>
        <p><h3b><i>F. Sukru Torun</i> </h3b>
          <br/><h3c>	Thesis (Master's) Bilkent University, 2011. <a href="http://repository.bilkent.edu.tr/bitstream/handle/11693/15774/0006481.pdf?sequence=1&isAllowed=y">Thesis</a> <br/>
        </h3c>
        </p>
        <div id="SpMxV">
        Sparse matrix vector multiplication (SpMxV) of the form y = Ax is a kernel operation in iterative linear solvers used in scientific applications. In these solvers, the SpMxV operation is performed repeatedly with the same sparse matrix through iterations until convergence. Depending on the matrix and its decomposition, parallel SpMxV operation necessitates communication among processors in the parallel environment. The communication can be reduced by intelligent decomposition. However, we can further decrease the communication through data replication and redundant computation. The communication occurs due to the transfer of x-vector entries in row-parallel SpMxV computation. The input  vector x of the next iteration is computed from the output vector of the current  iteration through linear vector operations.
 <a onclick="return toggleMe('SpMxVabs')">More</a>
<div id="SpMxVabs" style="display:none">
	 Hence, a processor may compute a  y-vector entry redundantly, which leads to a x-vector entry in the following iteration,
 instead of receiving that x-vector entry from another processor. Thus,
 redundant computation of that y-vector entry may lead to reduction in communication.
 In this thesis, we devise a directed-graph-based model that correctly captures
 the computation and communication pattern for above-mentioned iterative
 solvers. Moreover, we formulate the communication minimization by utilizing
 redundant computation of y-vector entries as a combinatorial problem on this
 directed graph model. We propose two heuristics to solve this combinatorial
 problem. Experimental results indicate that the communication reducing strategy
 by redundantly computing is promising.
 </div>
          <br/>
        <p></p>
        </div>  
    </td>
    <td><img src="rep1.png" style="float:left; margin-bottom:10px" width="250"/>
    </td>
  </tr>  

  
   </table>
   </div>
   

<hr>
<hr>
<div id="software">
 <h3d> Software: </h3d>
 </br>
  <table>
     <tr>
      <td>
        <h1><u><b>Numerically aware partitioning for Block Cimmino </b> </u></h1>        
         <h3c>Reference: F. Sukru Torun, Murat Manguoglu, and Cevdet Aykanat. "A NOVEL PARTITIONING METHOD FOR ACCELERATING THE BLOCK CIMMINO ALGORITHM." SIAM Journal on Scientific Computing (2018 - Accepted for Publication) <a href="https://arxiv.org/abs/1710.07769" title="A Novel Partitioning Method for Accelerating the Block Cimmino Algorithm"> Paper</a><br/>
        </h3c>
        </p>
        <div id="hinge">
           <p>
        Source code for numerically aware row-block partitioning for Block Cimmino Iterative method in ABCD Solver is source code is distributed under the GNU Lesser General Public License. 
        This is a simplified C++ implementation of the work that is published in SIAM SISC 2018.
        </p>
        >> <a href="GRIP_v1.1.tar.gz">GRIP (Row Inner-Product Graph partitioner for ABCD) version 1.1 </a> <<
        <p></p>
<!--
        <p>You need to do patch the code I attached and modify the config_file.info as part_type 5. </br>
        1. patch abcd/src/structure.cpp < Numerically_Aware_Partitioning_patch.txt </br>
        2. update config_file.info with part_type 5
        </p>     
 			<a href="Numerically_Aware_Partitioning_patch.txt">Numerically_Aware_Partitioning_patch.txt</a>       
        
-->
        </div>  
    </td>
  </tr>
  <tr>
      <td>
        <h1><u><b>ParBaMiN: </b> <b>Par</b>allel <b>Ba</b>lance Scheme Algorithm for <b>Mi</b>nimum <b>N</b>orm Solution of Underdetermined Systems </u></h1>
        <p><h3b><i>F. Sukru Torun</i> </h3b>
          <br/><h3c>Reference: F. Sukru Torun, Murat Manguoglu, and Cevdet Aykanat. 2017. Parallel Minimum Norm Solution of Sparse Block Diagonal Column Overlapped Underdetermined Systems. ACM Trans. Math. Softw. 43, 4, Article 31. <a href="http://dl.acm.org/authorize?N21577" title="Parallel Minimum Norm Solution of Sparse Block Diagonal Column Overlapped Underdetermined Systems"> Paper</a><br/>
        </h3c>
        </p>
        <div id="hinge">
        A distributed parallel algorithm for solving minimum 2-norm solution of an underdetermined system on distributed memory high performance computing (HPC) platforms. This software is implemented in C++ programming languages and it uses MPI library for communication among processors.
        Each processor concurrently and independently applies QR factorization on the sub-matrices. Sparse QR factorization of SuiteSparse (<a href="http://www.suitesparse.com" target="_blank">www.suitesparse.com</a>) package is used in local sparse QR factorization operations.
        The performance of the proposed method may increase by adding the parallelism mechanisms of multi-threaded SuiteSparseQR and multi-threaded BLAS for the local QR factorizations. 
		  This algorithm can be considered as an scalable extension of any multithreaded general sparse QR factorization algorithm
			to distributed memory architectures for computing minimum 2-norm solution of underdetermined linear least squares problems.<br/>
 			<a href="ParBaMiN.zip">ParBaMiN</a>       
        <p></p>
        </div>  
    </td>
  </tr>
    <tr>
      <td>
        <h1><b>ParBaMiN_matlab: </b> A Sequential MATLAB program for <b>Par</b>allel <b>Ba</b>lance Scheme Algorithm for <b>Mi</b>nimum <b>N</b>orm Solution of Underdetermined Systems</h1>
        <p><h3b><i>F. Sukru Torun</i> </h3b>
          <br/><h3c>Reference: F. Sukru Torun, Murat Manguoglu, and Cevdet Aykanat. 2017. Parallel Minimum Norm Solution of Sparse Block Diagonal Column Overlapped Underdetermined Systems. ACM Trans. Math. Softw. 43, 4, Article 31.<a href="http://dl.acm.org/authorize?N21577" title="Parallel Minimum Norm Solution of Sparse Block Diagonal Column Overlapped Underdetermined Systems"> Paper</a> <br/>
        </h3c>
        </p>
        <div id="hinge">
        A simple MATLAB program for the solving Minimum Norm Solution of Sparse Block Diagonal Column Overlapped Underdetermined Systems. 
        It is a sequential version of Parallel Minimum Norm Solution of Sparse Block Diagonal Column Overlapped Underdetermined Systems.
        Sparse QR factorization with Householder reflection of spqr routine in SuiteSparseQR package is used in local sparse QR factorization operations.
        <br/>
        <a href="ParBaMiN_matlab.zip">ParBaMiN_matlab</a>
        <br/>
        <p></p>
        </div>
        </td>
  </tr>
        <br/>
   </table>

</div>

<hr>
<hr>
<div id="projects">
   <h3d> Projects: </h3d>
   </br>
   </br>
 <table>
     <tr>
      <td>
        <h1><u><b>EoCoE: Energy oriented Centre of Excellence </b> </u></h1>        
         <h3c>Within the Horizon2020 framework of the European Union. Budget: 5.5 Million €<br/>
        </h3c>
        Post-Doctoral Research Fellow (2017)
        </p>
        <div id="hinge">
           <p>
         The project coordinates a pan-European network covering 21 teams in 8 countries with a total budget of 5.5 M€. 
         EoCoE assists the energy transition via targeted support to four renewable
energy pillars: Meteo, Materials, Water and Fusion. These four pillars are anchored within a strong transversal multidisciplinary
basis providing high-end expertise in applied mathematics and HPC.
        </p>        
        </div>  
    </td>
  </tr>
  </table>
</div>

<hr>
<hr>
<div id="teaching">
   <h3d> Teaching: </h3d>
   </br>
   </br>  
  <table>     
     <tr>
         <td>
          <b> Courses Given: </b>      
         </td>
      </tr>
	  <tr>
         <td>
           <u>Fall 2019-2020:  </u>
           <ul>
         <li>CENG 305 Operating Systems,        </li>
         <li>CENG 323 Introduction to Parallel Scientific Computing,        </li>
         <li>CENG 595 High Performance Scientific Computing</li>
         </ul> 
       </td>
    </tr>
     <tr>
         <td>
           <u>Spring 2018-2019:  </u>
           <ul>
         <li>CENG 206 Programming Languages,        </li>
         <li>CENG 316 Parallel Programming,        </li>
         <li>CENG 502 Parallel Algorithms</li>
         </ul> 
       </td>
    </tr>  
      <tr>
         <td>
        <u>Fall 2018-2019: </u>
        <ul>
      <li>CENG 305 Operating Systems,        </li>
      <li>CENG 508 Distributed Systems</li>
      </ul> 
       </td>
    </tr>
   
  </table>
  
</div>

<hr>
<hr>
<div id="schedule">
   <h3d> Schedule: </h3d>
   </br>
   </br>
  <iframe src="https://www.google.com/calendar/embed?src=fsukrutorun%40gmail.com&ctz=Europe/Istanbul" style="border: 0" width="800" height="600" frameborder="0" scrolling="no"></iframe>
</div>

<hr>
<hr>
<div id="schedule">
<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=a&t=m&d=DKZvCp6a4YPzSarUg9o4L8DRVIndXj1vq35_Us-cAcI&co=2d78ad&ct=ffffff&cmo=3acc3a&cmn=ff5353'></script>
</div>
</div>


</body></html>



<!--
**fsukrutorun/fsukrutorun** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
