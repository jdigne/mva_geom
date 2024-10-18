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

For your final project, you will be asked to present a research paper related to our course. The main goals are: 1. Read and understand the article, 2. Understand the background (context in which the work is done), 3. Understand the presented solution, 4. Understand the strengths and weaknesses of this solution, 5. Possibly highlight future/follow-up work. We will schedule slots of approximately 30 minutes, in which during the first 20 minutes we will ask you to give your presentation covering the article that you have chosen, and the remaining 10 minutes dedicated to the Q&A from our side. Please note that
- You are not required to implement the paper.
- If you do implement it (or run the publicly released code), you can of course mention this during your presentation and show the obtained results.
- During the Q&A we might ask you questions from the course that might be related to the presented paper.


## Planning 2024 (tentative dates)

Courses take place at ENS Paris Saclay on Wednesdays. Courses are from 1 pm to 3:20 pm followed by lab work from 3:40 to 5:40 pm.

- Oct. 2nd (**Room 1Z53**): Lecture 1 (E. Corman) ([Intro](slides/MVA_Course_Introduction.pdf), [Slides](slides/MVA_lecture1.pdf), [Lab](td/TD1.zip), [Lab correction](td/TD1_Corrrection.ipynb)): Intro to Discrete Differential Geometry. Basic differential operators on surfaces in both the smooth and discrete settings. Operator discretization through FEM. Geodesics. Functions, derivatives, integration, convolution on surfaces.
- Oct. 9th (**Room 1B36**): Lecture 2 (E. Corman) ([Slides](slides/MVA_lecture2.pdf), [Lab](td/TD2.zip)):  Discrete Differential Geometry part 2. Spectral methods + manipulating geometry, Curvature. Shape deformation, Optimization of geometric energies. Surface parameterization. Mappings between surfaces. Basic surface topology, and topological constraints.
- Oct. 16th (**Room 1Z18**): Lecture 3 (M. Ovsjanikov): [Slides part 1](slides/MVA_lecture3_part1.pdf) ([with extra background](slides/MVA_lecture3_part1_wextra_slides.pdf)), ([Slides part 2](slides/MVA_lecture3_part2.pdf)), [Lab](td/TD3_Q.ipynb)  Extrinsic learning approaches for regular data in 2D and 3D. Intrinsic approaches. Convolution on surfaces and triangle meshes. Geodesic CNNs and their variants. Spectral methods, pros and cons. Learning via diffusion.
- Oct. 30th (**Room 1Z18**): Lecture 4 (M. Ovsjanikov): Projection-based approaches. Learning on Point clouds. Common point-based architectures (PointNet, PointNet++, DGCNN, KPConv, etc.). Applications (surface reconstruction, point cloud filtering).
- Nov. 6th (**Room 1Z18**): Lecture 5 (J. Digne): Neural fields for surface representation, generation and analysis. Neural Radiance fields and Neural Fields regularization. DeepSDF, Occupancy networks, Fast Fourier Features.
- Nov. 13th (**Room 1Z53**): Lecture 6 (J. Digne): Generative Modeling (how to generate the surface structure). Local synthesis. E.g., geometric texture synthesis. In-painting. Mesh generation, Differentiable meshing.
- Nov 20th (**Room 1Z18**): Paper reading presentations

## Registration and mailing list
A registration form will be sent to all MVA students to subscribe to the course mailing-list.

## Validation
- Lab (20%): the 2nd (Oct. 9th), 4th (Oct. 30th) and 6th (Nov. 13th) labs will be evaluated. The files can be sent up to one week after the class. We will keep the best two grades.
- Quizz (20%): based on the material of 1st, 3rd and 5th lectures. 15 minutes at the beginning of 2nd, 4th and 6th TDs. We will keep the best two grades.
- Oral presentation (60%): presentation with slides of a research paper.
