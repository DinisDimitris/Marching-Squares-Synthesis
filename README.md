# Marching-Squares-Synthesis
This repository aims to create a generative and a discriminative model that can synthesize outputs of the marching squares algorithm. 

The marching squares algorithm is a classical computer graphics algorithm that can generate 2d contour meshes given rectangular matrix-like data. Given the correct input scalar field and isovalue, the algorithm can generate a contour describing any 2d shape. There are two hypotheses we want to prove:

Investigate whether an AI model can predict the geometrical shape of a given 2d mesh. 
This can be seen as an image classification problem. However, the images are two-dimensional matrix-like data procedurally generated via the marching square algorithm.

Investigate whether, given a textual input description of a geometrical shape, an AI model can generate the 2d mesh describing the contour of the geometrical shape using the underlying mechanisms of the marching square algorithm. Using this technique, we want to analyze the efficiency and limitations of a generative model and compare it to other image-generation techniques. 
This task has more complexity than the former as it will require a few natural language processing techniques for parsing the textual input and finding a generative model that can infer 2d mesh-generated images.
