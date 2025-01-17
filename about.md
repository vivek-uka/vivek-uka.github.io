---
layout: page
title: About
permalink: /about/
---
<!-- <img src="{{ site.url }}/assets/images/me.png" alt="alternatetext"  align="right" style="width:22%;height:22%;">      -->  
<p align="justify">  
I am Vivek Adajania, a researcher and software engineer in Robotics. Starting this November, I will join Oxa to work on Universal Autonomy. Currently, I work at Addverb Technologies on warehouse fleet management. I did a MASc degree under Angela Schoellig, Learning Systems and Robotics Lab, University of Toronto.
<br>  
   
</p>	
<p align="center">
  [<a href="https://scholar.google.com/citations?user=VxiCvuIAAAAJ&hl=en">Google Scholar </a>|<a href="https://www.linkedin.com/in/vivekadajania/">Linkedin </a>|<a href="https://github.com/vivek-uka"> Github</a>]
</p><br>

<!-- <h6>Click on images to watch it on Youtube</h6> -->
### Projects
<ol>
   <li><h4> Safe Multi-Robot motion planning </h4></li>
  Online, scalable, distributed, and safe trajectory generation algorithm for quadrotor swarms in cluttered and complex environments.
  <p align="center">
   <iframe width="450" height="253" src="https://www.youtube.com/embed/BfJbkWcNU_s" title="AMSwarmX: Safe Swarm Coordination in CompleX Environments via Implicit Non-Convex Decomposition" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
 </p>  
  <p align="center">
  <iframe width="450" height="253" src="https://www.youtube.com/embed/YnK3trXbAic" title="AMSwarm: An Alternating Minimization Approach for Safe Motion Planning of Quadrotor Swarms" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
 </p>
<!--   <p align="center">
<iframe width="450" height="253" src="https://www.youtube.com/embed/poTJmqn9BTk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> 
</p> -->
  <li><h4> Multi-Modal MPC for autonomous driving</h4></li>
  <i>Research Project</i>: Developed a real-time MPC algorithm that captures different driving modalities by generating several goal-directed trajectories in parallel; the resulting trajectories are ranked based on a meta-cost function to accomplish a high-level driving objective.
<p align="center">
<iframe width="450" height="253" src="https://www.youtube.com/embed/HPME4cYlR24" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>
  <!--   <p align="center"><a href="https://youtu.be/uDG9M1NHW_c">
<img src="{{ site.url }}/assets/images/acado_thread.png" alt="Watch on Youtube" width="75%" height="75%">
</a></p> -->
<li><h4>Fixed-Wing-Aerial Vehicle Trajectory Optimization in Urban Settings</h4></li>
  <p align="justify">
<i>Research Project</i>: Developed a novel optimizer which exploits the computational structure of the non-linear trajectory optimization problem. Our optimizers builds an insight that the seemingly non-linear trajectory optimization has an implicit multi-convex structure. It outperforms the state-of-the-art implementation of SQP ACADO Toolkit in terms of computation time and solution quality.</p>
<p align="center">
<iframe width="450" height="253" src="https://www.youtube.com/embed/Qk7wdQ39Onk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>
<li><h4>Occlusion-Free Target Tracking with Quadrotors</h4></li>
<i>Research Project</i>: Developed a fast MPC algorithm that can run real-time laptops and devices such as Jetson TX2 for the problem of quadrotor tracking a target. Our approach relies on novel reformulations for the tracking, collision, and occlusion constraints that induce a multi-convex structure in the resulting trajectory optimization. We exploit these mathematical structures using the split Bregman Iteration technique, eventually reducing our MPC to a series of convex Quadratic Programs solvable in a few milliseconds.
 <p align="center">
<iframe width="450" height="253" src="https://www.youtube.com/embed/D97A7I7qUts" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </p>
  
  <li><h4>Multi-Robot System for Warehouse application</h4></li>
  <p align="justify">
  <i>Final Year Project</i>: Developed a multi-robot navigation system by incorporating diverse concepts and algorithms such as distributed model predictive control, A* search algorithm, On-demand Collision Avoidane, and Leader-Follower formation scheme. The problem statement was divided into three parts: single-robot navigation, multi-robot navigation, multi-robot cooperation to transport a deformable object. We validated and tested algorithms in Gazebo environment.</p><br>
 <a href="https://youtu.be/ncNinuzSq00">
   <img src="{{ site.url }}/assets/gifs/fyp_1.gif" alt="fyp1" style="width:45%;height:45%;"> <a href="https://youtu.be/ncNinuzSq00"><img src="{{ site.url }}/assets/gifs/fyp_2.gif" alt="fyp2" align="right" style="width:45%;height:45%;"></a>
  <p align="center">
  <iframe width="450" height="253" src="https://www.youtube.com/embed/ncNinuzSq00" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
   </p>
   
   
  <li><h4>Asia-Pacific Robot Contest</h4></li>  
  <p align="justify">
<i>Competition</i>: Developed an autonomous navigation system for Omni-directional robots from its embedded system to motion planning and control.</p>
  <p align="center">
  <iframe width="450" height="253" src="https://www.youtube.com/embed/bhk94eT4mUk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </p>
   <p align="center">
  <iframe width="450" height="253" src="https://www.youtube.com/embed/-p3lqOd0fhs" title="Autonomous Omni-directional robot" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
  </p>
   
<!--   <li><h4>Non-Linear Model Predictive Control with Gradient Descent Variant</h4></li>
  <p align="justify">Developed deep learning inspired gradient descent variant RMSPprop using Autograd and incorporated it in a NMPC setup for non-holonomic robots.</p><br>
  <p align="center"><img src="{{ site.url }}/assets/gifs/rmsprop.gif" alt="rmsprop" align="center" style="width:75%;height:75%;"></p> -->
  
  <li><h4>Planning Techniques</h4></li>
  <i>Personal Project</i>: Followed RI16-730 Planning techniques in Robotics and implemented planners such as A*, ARA*, D*, Wave front planner, navigation potential functions, etc. Moreover, wrote blogs<a href="https://dv367.github.io">&#128279;</a> on implementation and results. <br> 
   <p align="center"><img src="{{ site.url }}/assets/gifs/intro5.gif" alt="robocon" align="center" style="width:75%;height:75%;"><br>
     Robot Chasing a Target</p> 


