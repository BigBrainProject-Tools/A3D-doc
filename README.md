# Atelier3D wiki
Table of Contents
=================
 1. [Introduction](#introduction)
 2. [Installation](#installation)
 3. [Documentation](#documentation)\
     3.1 [User Guide][link_userguide]\
     3.2 [Contributor Guide][link_contributors]
 4. [Publications](#publications)
 5. [Support](#support)
 6. [About us](#about-us)
 7. [Terms and Conditions](#terms-and-conditions)

## Introduction
Atelier3D is a general software framework designed for the processing, visualization and analysis of large 3D datasets. It was originally developed at the National Research Council of Canada in the context of 3D imaging R&D in numerous application contexts [2-6]. This specific version of the Software, Atelier3D-MCIN, is jointly developed with the McGill Centre for Integrative Neuroscience in Montreal to support the work on applications related to very large datasets in neuroscience such as the BigBrain[1].

Atelier3D-MCIN has a new interface specifically adapted to Neuroscience, and specific features to support annotation and segmentation of high-resolution brain volumetric datasets.

Atelier3D combines a unique set of features to support analysis of very large histology datasets such as the BigBrain, while still providing an interface very similar to standard neuroscience visualization tools:

- High-speed data streaming: Large histology stacks can be located locally or on a remote server.

- Native out-of-core asynchronous graphic rendering: There is no breaking point or performance issue associated with the size of the dataset. Efficient multi-resolution representations are available for dense volume data, extracted surfaces, and voxel annotations.

- Designed for HD and 4K monitors: The software offers excellent performance on very large Displays.

- Optimized for multi-axial oblique cuts: There is no performance reduction when slicing models outside the original reference frame.

- High Quality graphics: The software supports overlaying different modalities and supports order-independent transparency.

- I/O converters: Import and import for numerous volumes(minc, nifty, openVDB) and meshes formats(obj, osg, etc...)

- Annotation tools: Complete set of tools for manual voxel annotation and surface generation/integration to and from the volume space


## Installation
*in preparation*

## Documentation

### Users
For more information please read our [user guide][link_userguide].

### Contributors
For those interested in extending or contributing to our [Atelier3D wiki][link_a3d-wiki], please read our [contributors guideline][link_contributors]. 

## Publications

1. Amunts K, Lepage C, Borgeat L, Mohlberg H, Dickscheid T, Rousseau ME, Bludau S, Bazin PL, Lewis LB, Oros-Peusquens AM, Shah NJ, Lippert T, Zilles K, Evans AC (2013) BigBrain: An ultrahigh-resolution 3D human brain model. Science, 340(6139): 1472-1475

2. Godin G, Borgeat L, Beraldin JA, Blais F (2010) Issues in acquiring, processing and visualizing large and detailed 3D models. 44th Annual Conference on Information Sciences and Systems (CISS), 1-6

3. Borgeat L, Poirier G, Beraldin A, Godin G, Massicotte P, Picard M (2009) A framework for the registration of color images with 3D models. 16th IEEE International Conference on Image Processing (ICIP), 69-72

4. Borgeat L, Godin G, Massicotte P, Poirier G, Blais F, Beraldin JA (2007) Visualizing and analyzing the Mona Lisa. IEEE Computer Graphics and Applications 27(6):60-68

5. Borgeat L, Godin G, Blais F, Beraldin JA, Massicotte P, Poirier G (2007) Visualizing and analyzing large and detailed 3D datasets. Proc of 2nd ISPRS

6. Borgeat L, Godin G, Blais F, Massicotte P, Lahanier C (2005) GoLD: Interactive display of huge colored and textured models. ACM Transactions on Graphics (TOG) 24(3):869-877


## Support

If you have a question about Atelier3D or have encountered an issue while using this tool, post a message on the [user group][link_bbpf_a3d], or subscribe to the [BigBrain Project Discourse forum][link_bbpf] and join the discussion!

If you have found a bug in the software, feel free to open an issue or submit a patch after reviewing our [CONTRIBUTING.md][link_contributors] documentation.

## About Us

[BigBrain Project][link_bbp]

[Computer Vision and Graphics, NRCC][link_nrcc_a3d]

## Terms and Conditions

Terms and conditions for use, reproduction, distribution and contribution are found in [LICENSE.txt][link_terms-and-conditions].

[link_contributors]: https://github.com/BigBrainProject-Tools/A3D-wiki/main/CONTRIBUTING.md
[link_userguide]: https://github.com/BigBrainProject-Tools/A3D-wiki/main/USERGUIDE.md
[link_terms-and-conditions]: https://github.com/BigBrainProject-Tools/A3D-wiki/main/LICENSE.txt
[link_bbp]: https://bigbrainproject.org
[link_bbpf]: https://bigbrain-forum.loris.ca/
[link_bbpf_a3d]: https://bigbrain-forum.loris.ca/
[link_nrcc_a3d]: https://nrc.canada.ca/en/research-development/products-services/technical-advisory-services/computer-vision-graphics
[link_a3d-wiki]:https://wiki.bigbrainproject.org/
