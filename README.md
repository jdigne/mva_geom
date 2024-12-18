# Geometry Processing and Geometric Deep Learning

## Lecturers:

- [Etienne Corman](https://members.loria.fr/ECorman/) (junior CNRS researcher, LORIA)
- [Julie Digne](https://liris.cnrs.fr/julie.digne/) (senior CNRS researcher, LIRIS)
- [Maks Ovsjanikov](https://www.lix.polytechnique.fr/~maks/) (Professor at Ecole Polytechnique, LIX)

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

Please note that we will limit the number of possible groups per paper to 3. In other words, if 3 teams have already selected a specific paper on our list, we will not allow any other groups to pick it. Therefore, it is in your interest to select as soon as possible. Once you have made your selection, please notify us of the paper (and team members of your group) by email via GeometricDeepLearning@protonmail.com.

The **Strict Deadline** for selecting the paper to present is **midnight Nov. 6th**. We will not accept any requests after that date. Once we have all the selections, we will schedule final presentations (which are likely to happen remotely via Zoom).

The list of papers is available at this [link](https://docs.google.com/document/d/1iVGCgSMZf_lFjlYCdPU__8Tux8y1pf-TiKqnVniCATA/edit?tab=t.0).

The papers have been selected and the final schedule is ready! You can find the schedule at this [link](https://docs.google.com/document/d/15WPGpft7smMMixXV0LAlb3y_Sby5Kkoh_1I_-6mz7nE/edit?tab=t.0). Please follow the instructions below (in addition of the other instructions above):
- Presentations should last 20 minutes, there will be a limited tolerance if you are late, as the schedule is tight.
- There will be 5 minutes of questions, either on the paper or on some concepts seen during the course.
- The presentations should be in english
- We ask you to join the zoom link only 5 minutes before the start of your time slot, and to be on time to respect everyone's schedule.

Don't hesitate to let us know if you have any questions or comments.


## Planning 2024 (tentative dates)

Courses take place at ENS Paris Saclay on Wednesdays. Courses are from 1 pm to 3:20 pm followed by lab work from 3:40 to 5:40 pm.

- Oct. 2nd (**Room 1Z53**): Lecture 1 (E. Corman) ([Intro](slides/MVA_Course_Introduction.pdf), [Slides](slides/MVA_lecture1.pdf), [Lab](td/TD1.zip), [Lab correction](td/TD1_Corrrection.ipynb)): Intro to Discrete Differential Geometry. Basic differential operators on surfaces in both the smooth and discrete settings. Operator discretization through FEM. Geodesics. Functions, derivatives, integration, convolution on surfaces.
- Oct. 9th (**Room 1B36**): Lecture 2 (E. Corman) ([Slides](slides/MVA_lecture2.pdf), [Lab](td/TD2.zip), [Lab correction](https://nuage.lix.polytechnique.fr/index.php/s/NZsqdRZPY78Gic7)):  Discrete Differential Geometry part 2. Spectral methods + manipulating geometry, Curvature. Shape deformation, Optimization of geometric energies. Surface parameterization. Mappings between surfaces. Basic surface topology, and topological constraints.
- Oct. 16th (**Room 1Z18**): Lecture 3 (M. Ovsjanikov): ([Slides part 1](slides/MVA_lecture3_part1.pdf) -- [with extra background](slides/MVA_lecture3_part1_wextra_slides.pdf), [Slides part 2](slides/MVA_lecture3_part2.pdf), [Lecture recording](https://ens-paris-saclay-fr.zoom.us/rec/share/_czVt9bwwjrdiAeGm5qGdXpeh8XlTNbEbo27D4OHkso80_bX8tixYhscL6j3m0sg.F-kj5suMXU3LZYIK), (password: fyz0FtU%), [Lab](td/TD3_Q.ipynb)  [Lab correction](td/TD3_Q_correction.ipynb)): Extrinsic learning approaches for regular data in 2D and 3D. Intrinsic approaches. Convolution on surfaces and triangle meshes. Geodesic CNNs and their variants. Spectral methods, pros and cons. Learning via diffusion.
- Oct. 30th (**Room 1Z18**): Lecture 4 (M. Ovsjanikov): ([Slides](slides/MVA_lecture4_cmp.pdf), [Lecture recording](https://www.dropbox.com/s/bxn9lhwbrqjuxm8/GMT20241030-120528_Recording_1790x956.mp4?dl=0), [Lab](td/TD_4.ipynb), [Lab correction](https://nuage.lix.polytechnique.fr/index.php/s/PcJMN2b2qjepGAB)): Projection-based approaches. Learning on Point clouds. Common point-based architectures (PointNet, PointNet++, DGCNN, KPConv, Sparse Convolution, Point Transformers). Applications (surface reconstruction, point cloud filtering).
- Nov. 6th (**Room 1Z18**): Lecture 5 (J. Digne): Neural fields for surface representation, generation and analysis. DeepSDF, Occupancy networks.([Slides](slides/MVA_lecture5.pdf), [Lab](td/TD_5.ipynb))
- Nov. 13th (**Room 1Z53**): Lecture 6 (J. Digne): Generative models for shapes, Latent Shape Spaces, Novel View Synthesis ([Slides](slides/MVA_lecture6.pdf), [Lab](td/TP_6.ipynb))
- **Nov 27th-28th: Paper reading presentations (zoom)**


## Registration and mailing list
A registration form will be sent to all MVA students to subscribe to the course mailing-list.

## Validation
- Lab (20%): the 2nd (Oct. 9th), 4th (Oct. 30th) and 6th (Nov. 13th) labs will be evaluated. The files can be sent up to one week after the class. We will keep the best two grades.
- Quizz (20%): based on the material of 1st, 3rd and 5th lectures. 15 minutes at the beginning of 2nd, 4th and 6th TDs. We will keep the best two grades.
- Oral presentation (60%): presentation with slides of a research paper.
