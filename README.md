pointcloudtransformationstep
==============================

Step for applying an input geometric transformation to a point cloud

Requires
--------
- GIAS2 : https://bitbucket.org/jangle/gias2

Inputs
------
- **pointcloud** [list] : A list of point coordinates.
- **geometrictransform** : an object containing the similarity transformation.

Outputs
-------
- **pointcloud** [list] : A list of transformed point coordinates.

Configuration
-------------
- **identifier** : Unique name for the step.

Usage
-----
This step is used to apply a similarity (rigid-body and optionally scaling) transform to a pointcloud.