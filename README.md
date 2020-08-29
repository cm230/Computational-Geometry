# Computational Geometry
The field of __computational geometry__ emerged in the 1970s and deals with the study of data structures and algorithms for solving geometric problems. This includes, in particular, the determination of topological structures within images, or indeed higher-dimensional representations, such as point neighbourhoods, which can help derive geometric meaning from, for example, digital image data.

__Computer vision__ is primarily concerned with still or moving image processing, understanding and reconstruction. Due to impressive, super-human results delivered by deep neural network-powered algorithms, the computer vision application areas of object identification (classification), object detection (classification & localisation) and object segmentation (classification, localisation & boundary detection) have been receiving steadily increasing attention in research and industry.

![Voronoi diagrams](https://github.com/cm230/Computational-Geometry/blob/master/VoronoiDiagram.png)

Unsurprisingly, given these overlapping areas of interest, computational geometry has useful concepts to offer to the field of computer vision, and its counterpart, computer graphics. The Voronoi diagram (a.k.a. Dirichlet tessellation, Voronoi tessellation or Voronoi partition) of a set of points (see, for example, the illustrations above), and its dual, the points’ Delaunay triangulation (a.k.a. Delone triangulation; see the example below), are examples for such useful concepts. Relevant computer vision applications include face recognition, face morphing, image synthesis and surface modeling. I demonstrate the use of the Delaunay triangulation/Voronoi diagram of faces in images as a precursor for applications such as face recognition or face morphing.

This repo provides the Python code in form of a Jupyter Notebook accompanying my [Medium](https://medium.com/datadriveninvestor/computational-geometry-for-computer-vision-f140fab91c76) blog post on this subject.

<p align="center">
  <img src="https://github.com/cm230/Computational-Geometry/blob/master/Delaunay2.png"/>
</p>
