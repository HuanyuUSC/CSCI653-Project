# CSCI653-Project
This is the repos for CSCI653 course project.
The preliminary idea is that the intersection volume of two 3D object can be computed as a double surface integral. The double surface integral can be computed in a highly parallel way and can be accelerated even further by using FMM. 
It should be interesting to do the calculations for all kind of geometry representations like mesh, point cloud, implicit surfaces, etc. 
It could have potential applications also in contact detection and handling.

The expected result is that we can compute intersection volume much faster than any naive methods, probably even real time for complex geometries. We may even develop a contact handling method using intersection volume. The target venue for the work is Siggraph 2026.

I am also planning to team up with Zhiyuan Gao, my labmate.
