# Geometry Processing and Geometric Deep Learning

## Lecturers:

- [Etienne Corman](https://members.loria.fr/ECorman/) (junior CNRS researcher, LORIA)
- [Julie Digne](https://liris.cnrs.fr/julie.digne/) (senior CNRS researcher, LIRIS)
- [Maks Ovsjanikov](https://www.lix.polytechnique.fr/~maks/) (Professor at Ecole Polytechnique, LIX)
- [Emery Pierson](https://daidedou.github.io) (Postdoc at Ecole Polytechnique, LIX)

## Goals of the course

 This course will introduce students to advanced topics in modern geometric data analysis (the field known as Geometry Processing) with focus on: 
a) mathematical foundations (discrete differential geometry, mapping, optimization), and 
b) deep learning for best performing methods. 


We will give an overview of the foundations in surface-based analysis and processing before moving to modern techniques based on deep learning for solving problems such as 3D shape classification, correspondence, parametrization, etc. Finally, we will cover recent approaches for generating geometry, from both the mesh and shape-based perspectives.

## Final Projects

For your final project, you will be asked to present a research paper related to our course. The main goals are:
1. Read and understand the article,
2. Understand the background (context in which the work is done),
3. Understand the presented solution,
4. Understand the strengths and weaknesses of this solution,
5. Possibly highlight future/follow-up work.

We will schedule slots of approximately 30 minutes, in which during the first 20 minutes we will ask you to give your presentation covering the article that you have chosen, and the remaining 10 minutes dedicated to the Q&A from our side. Please note that
- You are not required to implement the paper.
- If you do implement it (or run the publicly released code), you can, of course mention, this during your presentation and show the obtained results.
- During the Q&A we might ask you questions from the course that might be related to the presented paper.
- You can join in teams (of up to 2 members) to do this. Indeed we **strongly encourage** you to partner up with someone else for this final project.

We will send (by email) a list of possible papers to present. If you would like to present a paper that's not on the list, please feel free to email us at GeometricDeepLearning@protonmail.com to get our approval. 

Please note that we will limit the number of possible groups per paper to 3. In other words, if 3 teams have already selected a specific paper on our list, we will not allow any other groups to pick it. Therefore, it is in your interest to select a paper as soon as possible. Once you have made your selection, please notify us of the paper (and team members of your group) by email via GeometricDeepLearning@protonmail.com.

The **Strict Deadline** for selecting the paper to present is **midnight Nov. 6th**. We will not accept any requests after that date. Once we have all the selections, we will schedule final presentations (which will happen remotely via Zoom).


The list of papers to be selected is available at this [link](https://docs.google.com/document/d/1_3aIV7NAPX8fJbfrbK-QQ3lbd7nRO6Ww2aZqCqVHKs4/edit?tab=t.0). 

You need to send an e-mail to geometricdeeplearning@protonmail.com to validate your selection.

The list of papers with student choices is ready, available at this [link](https://docs.google.com/document/d/1S0aNDZlxVh1BYbQooUTqVfqOTHgSujWLvVnVruDkCFk/edit?tab=t.0). Please verify if the paper your selected is the right one.

<!--The list of papers is available at this [link](https://docs.google.com/document/d/1iVGCgSMZf_lFjlYCdPU__8Tux8y1pf-TiKqnVniCATA/edit?tab=t.0).

The papers have been selected and the final schedule is ready! You can find the schedule at this [link](https://docs.google.com/document/d/15WPGpft7smMMixXV0LAlb3y_Sby5Kkoh_1I_-6mz7nE/edit?tab=t.0).
 Please follow the instructions below (in addition of the other instructions above):
- Presentations should last 20 minutes, there will be a limited tolerance if you are late, as the schedule is tight.
- There will be 5 minutes of questions, either on the paper or on some concepts seen during the course.
- The presentations should be in english
- We ask you to join the zoom link only 5 minutes before the start of your time slot, and to be on time to respect everyone's schedule.

Don't hesitate to let us know if you have any questions or comments.-->


## Planning 2025 (tentative dates)

Courses take place at Université paris Cité (Cochin or Cordeliers sites) on Wednesdays. *Courses are from 1 pm to 3:20 pm followed by lab work from 3:40 to 5:40 pm.*

- Oct. 1st (**Cordeliers Rdc - Cordeliers Pavillon 3**, [Intro](https://members.loria.fr/ECorman/mva_geom/MVA_Course_Introduction.pdf), [Slides](https://members.loria.fr/ECorman/mva_geom/MVA_lecture1.pdf), [TD1](https://members.loria.fr/ECorman/mva_geom/TD1.zip), [Colab version](https://colab.research.google.com/drive/1qUBrdEXiUEsRJpgVUMrrwkceoz7QnMB1?usp=sharing), [TD1 Correction](https://members.loria.fr/ECorman/mva_geom/TD1_correction.ipynb)): Lecture 1 (E. Corman): Intro to Discrete Differential Geometry. Basic differential operators on surfaces in both the smooth and discrete settings. Operator discretization through FEM. Geodesics. Functions, derivatives, integration, convolution on surfaces.
- Oct. 8th (**Cordeliers Rdc - Cordeliers Pavillon 3**,[Slides](https://members.loria.fr/ECorman/mva_geom/MVA_lecture2.pdf), [TD2](https://members.loria.fr/ECorman/mva_geom/TD2.ipynb), [Colab version](https://colab.research.google.com/drive/1Mpy5uCqA_zM7P-tCpTqTM5oHr0MgH2Yx?usp=sharing), [Quiz 1](https://surveyjs.io/published?id=349f91ad-bb37-4f5d-918c-efb38c06f044)): Lecture 2 (E. Corman):  Discrete Differential Geometry part 2. Spectral methods + manipulating geometry, Curvature. Shape deformation, Optimization of geometric energies. Surface parameterization. Mappings between surfaces. Basic surface topology, and topological constraints.
- Oct. 15th (**Cochin Amphitheatre Luton**): Lecture 3 (M. Ovsjanikov): 3D Deep Learning part 1. Multi-view and volumetric approaches. [Slides](https://www.dropbox.com/scl/fi/rhtvkvhoux6sahbd355sv/MVA-2025-Lecture-3-part-1.pdf?rlkey=oxzmhzcd3infhw1b3gvj0ts8w&st=2yz3qp69&dl=0) Point-based Learning (PointNet, PointNet++, DGCNN, KPConv, Point Cloud Transformers) [Slides](https://www.dropbox.com/scl/fi/65mtjl6fh97e4dtdqxemk/MVA-2025-Lecture-3-part-2.pdf?rlkey=8ttqg4czd9gpds7umabojphdb&st=3budjilg&dl=0). [TD3](https://jdigne.github.io/mva_geom/Lab4.ipynb).
- Nov. 12th (**Cochin Amphitheatre Luton**): Lecture 4 (M. Ovsjanikov):  3D Deep Learning part 2. Intrinsic learning on surfaces. Geodesic Convolutional Neural Networks, Learning via Diffusion. [Slides](https://drive.google.com/file/d/1T_pMiqwajwrCiVDsgtIza1oEpUKkcS4w/view?usp=sharing), [Lab (colab link)](https://colab.research.google.com/drive/1WoqCGan-uSiL7yzogCKIp3rq-hMgpOjQ?usp=sharing)
- Nov. 19th (**Cochin Amphitheatre Luton**): Lecture 5 (J. Digne): Neural fields for surface representation, generation and analysis. DeepSDF, Occupancy networks. [Slides](https://liris.cnrs.fr/julie.digne/cours/cours_mva1.pdf), [Lab](https://liris.cnrs.fr/julie.digne/cours/TD5.ipynb), [Colab](https://colab.research.google.com/drive/11Bmmsrbia_Wr5vgGNG7IXTV2YGu9-3wS?usp=sharing)

- Nov. 26th (**Cochin Amphitheatre Luton**): Lecture 6 (J. Digne): Generative models for shapes, Latent Shape Spaces, Novel View Synthesis.
- **(tentative) Dec 10th-11th: Paper reading presentations (zoom)**


## Registration and mailing list
A registration form will be sent to all MVA students to subscribe to the course mailing-list.

## Validation
- Lab (20%): the 2nd, 4th and 6th labs will be evaluated. The files can be sent **up to one week after the class** at **GeometricDeepLearning@protonmail.com**. We will keep the best two grades.
- Quizz (20%): based on the material of 1st, 3rd and 5th lectures. 15 minutes at the beginning of 2nd, 4th and 6th TDs. We will keep the best two grades.
- Oral presentation (60%): presentation with slides of a research paper.
