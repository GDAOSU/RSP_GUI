RPC Stereo Processor - A software package for processing RPC-based satellite stereo images
===================================

**Lumache** (/lu'make/) is a Python library for cooks and food lovers that
creates recipes mixing random ingredients.  It pulls data from the `Open Food
Facts database <https://world.openfoodfacts.org/>`_ and offers a *simple* and
*intuitive* API.

Check out the :doc:`usage` section for further information, including how to
:ref:`install <installation>` the project.

.. note::

   This project is under active development.
   
.. toctree::

   usage
   gallery

RPC Stereo Processor is an operational-ready software developed by me when I was still a student. It can handle most of the satellite images with RPC as their geometric model. It implements a modified version of the most advanced dense matching algorithms, which generates very dense point clouds from satellite stereo images. The whole software is highly optimized and the final products include pixel-wise dense color point clouds, DSM raster, obj triangular mesh, true-orthophoto.

A software wrapper of RSP has won the `IARPA 3D challenge <https://community.topcoder.com/longcontest/?module=ViewProblemStatement&rd=16805&pm=14383/>`_ `Top-5 <https://www.iarpa.gov/challenges/3dchallenge.html/>`_ 2016.

A software wrapper of RSP has won the IEEE Data Fusion Contest 2019 Semantic 3D reconstruction Using Multi-view Satellite Imageries, two wins in the contest!

A software wrapper supporting Multi-view processing using RSP is shown below:

.. raw:: html

   <iframe width="560" height="315" src="https://www.youtube.com/embed/7YV1R7zhnS8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen=""></iframe>

Functions:

-  GCP/Tie Point based bias correction and adjustment of RPC file
-  L2 image generation (ortho-ready)
-  Dense color point cloud generation
-  DSM generation with/without hole filling
-  Epipolar rectification
-  True ortho-photo rectification
- Pan-Sharpening

Tested datasets:

- IKONOS
- Worldview 1/2/3
- Cartosat 1
- ZiYuan-3 (ZY-3)
- Geoeye 1
- Pleiades

How to Get the  Software:

Please follow the link here to apply for a test license, and note this is not for the Multi-view version of the software (which is not robust enough to release for the moment). You can access the publicly shared google group to ask questions about the use of the software if you encounter any issues. Please note to cite the following publications if you use this software in your research:

Rongjun Qin (2016). RPC Stereo Processor (RSP) –A software package for digital surface model and orthophoto generation from satellite stereo imagery. International Annals of the Photogram., Remote Sens. & Spatial Information Sci. ISPRS Congress 2016. Prague, Czech Republic, July 11-19, 2016
Rongjun Qin (2014). Change Detection on LOD 2 Building Models with Very High Resolution Spaceborne Stereo Imagery. ISPRS Journal of Photogrammetry and Remote Sensing. 96 (2014), 179-192