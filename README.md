C4L Image Dataset
=================
This is a collection of 2D and 3D images used for grayscale image processing tests. It includes at least 8 images of each of the following sizes:

* 256x256 - 65.5k pixels
* 512x512 - 262k pixels
* 1024x1024 - 1.05m pixels
* 1920x1080 - 2.07m pixels - 1080p or 'HD'
* 2560x1440 - 3.69m pixels - 1440p or '2K'
* 2560x1920 - 4.92m pixels - 5 MP camera photo
* 256x256x128 - 8.39m voxels

Each set contains a randomly generated image.


Conversion Notes
================
All images that were originally in color were converted to grayscale using Rec. 601:

```
0.299 R + 0.587 G + 0.114 B
```

Original images may be cropped and/or resized to fit into one of the predefined image sizes. All images are stored as uint8-PNG images. For some images this required rescaling the data.


Image Sources
=============

USC SIPI Image Dataset
----------------------
From: [sipi.usc.edu/database/database.php](http://sipi.usc.edu/database/database.php). Each of the photos is listed with the filename given from the USC SIPI dataset and categorized by license. 
License: See [sipi.usc.edu/database/copyright.php](http://sipi.usc.edu/database/copyright.php) for details.

* USC/USC-SIPI Copyright, free to use for research
  * 256x256/jellybeans.png - misc/4.1.08.tiff
  * 512x512/motioncar.png  - sequences/motion04.512.tiff
  * 1024x1024/pentagon.png - aerials/3.2.25.tiff
  * 1024x1024/sandiego.png - aerials/2.2.01.tiff
* Brodatz Textures, copyright Dover Pictorial Archive Series (see  [this](http://graphics.stanford.edu/projects/texture/faq/brodatz.html), allowed to use up to 3 in a project)
  * 512x512/bark.png       - textures/1.1.02.tiff
  * 512x512/brick wall.png - textures/1.2.12.tiff
  * 512x512/sand.png       - textures/1.1.07.tiff
* Unknown copyright status:
  * 256x256/moon.png       - misc/5.1.09.tiff
  * 256x256/clock.png      - misc/5.1.12.tiff
  * 256x256/chemical.png   - misc/5.1.14.tiff
  * 256x256/cronkite.png   - sequences/6.1.01.tiff
  * 256x256/tree.png       - misc/4.1.06.tiff
  * 512x512/aerial.png     - misc/5.2.09.tiff
  * 512x512/boat.png       - misc/boat.512.tiff
  * 512x512/mandrill.png   - misc/4.2.03.tiff
  * 512x512/pepper.png     - misc/4.2.07.tiff
  * 512x512/plane.png      - misc/4.2.05.tiff
  * 512x512/stream.png     - misc/5.2.10.tiff
  * 512x512/tank.png       - misc/7.1.03.tiff
  * 1024x1024/man.png      - misc/5.3.01.tiff
  * 1024x1024/u2airplane.png - misc/7.2.01.tiff

Henry Guennadi Levkin Corpus
----------------------------
From: [hlevkin.com/06testimages.htm](http://hlevkin.com/06testimages.htm). 
License: Unknown.

* 256x256/cameraman.png
* 256x256/finger.png
* 1920x1080/bone_scint.png
* 1920x1080/rainier.png

NASA
----
From: [nasa.gov](https://www.nasa.gov/) and [hubblesite.org](https://hubblesite.org/). 
License: Public domain.

* 1024x1024/neptune.png
* 1920x1080/mars.png
* 2560x1920/hudf.png
* 2560x1920/sun.png

SpaceX
------
From: [spacex.com/media](https://www.spacex.com/media). 
License: Public domain.

* 2560x1440/demo1ready.png
* 2560x1440/rocket.png
* 2560x1440/rocketbay.png

Cancer Imaging Archive
----------------------
From: [cancerimagingarchive.net](https://www.cancerimagingarchive.net/). 
License: CC BY 3.0. 
General citation: Clark K *et al*. The Cancer Imaging Archive (TCIA): Maintaining and Operating a Public Information Repository, Journal of Digital Imaging, Volume 26, Number 6, December, 2013, pp 1045-1057.

Each individual collection within the archive also has its own citation:

* 2560x1440/cancer.png - [CPTAC-GBM](https://wiki.cancerimagingarchive.net/display/Public/CPTAC-GBM) - C3L-03747-21 
Radiology Data from the Cancer Institute Clinical Proteomic Tumor Analysis Consortium Glioblastoma Multiforme \[CPTAC-GBM\] collection. (2018). [doi:10.7937/k9/tcia.2018.3rje41q1](https://doi.org/10.7937/k9/tcia.2018.3rje41q1)
* 256x256x128/brain-ct/\*.png - [TCGA-GBM](https://wiki.cancerimagingarchive.net/display/Public/TCGA-GBM) - TCGA-06-5410 
Scarpace L *et al*. (2016). Radiology Data from The Cancer Genome Atlas Glioblastoma Multiforme \[TCGA-GBM\] collection. [doi:10.7937/K9/TCIA.2016.RNYFUYE9](http://doi.org/10.7937/K9/TCIA.2016.RNYFUYE9)
* 256x256x128/brain-mr/\*.png - [TCGA-LGG](https://wiki.cancerimagingarchive.net/display/Public/TCGA-LGG) - TCGA-FG-A60K 
Pedano N, *et al*. (2016). Radiology Data from The Cancer Genome Atlas Low Grade Glioma \[TCGA-LGG\] collection. [doi:10.7937/K9/TCIA.2016.L4LTD3TK](http://doi.org/10.7937/K9/TCIA.2016.L4LTD3TK).
* 256x256x128/chest-pet/\*.png - [TCGA-LUSC](https://wiki.cancerimagingarchive.net/display/Public/TCGA-LUSC) - TCGA-60-2712 
Kirk S, *et al*. (2016). Radiology Data from The Cancer Genome Atlas Lung Squamous Cell Carcinoma \[TCGA-LUSC\] collection. [doi:10.7937/K9/TCIA.2016.TYGKKFMQ](http://doi.org/10.7937/K9/TCIA.2016.TYGKKFMQ)
* 256x256x128/chest-ct/\*.png - [NSCLC Radiogenomics](https://wiki.cancerimagingarchive.net/display/Public/NSCLC+Radiogenomics) - AMC-029 
Bakr S, *et al*. (2017). Data for NSCLC Radiogenomics Collection. [doi:10.7937/K9/TCIA.2017.7hs46erv](http://doi.org/10.7937/K9/TCIA.2017.7hs46erv)

Acknowledgements:
* Data used in this publication were generated by the National Cancer Institute Clinical Proteomic Tumor Analysis Consortium (CPTAC).
* The results shown here are in whole or part based upon data generated by the TCGA Research Network: [cancergenome.nih.gov](http://cancergenome.nih.gov/).

Open Access Series of Imaging Studies (OASIS)
---------------------------------------------
From: [oasis-brains.org](https://www.oasis-brains.org/#data)
License: CC BY 4.0.
Citation: Open Access Series of Imaging Studies (OASIS): Longitudinal MRI Data in Nondemented and Demented Older Adults. Marcus, DS, Fotenos, AF, Csernansky, JG, Morris, JC, Buckner, RL, 2010. Journal of Cognitive Neuroscience, 22, 2677-2684. [doi:10.1162/jocn.2009.21407](https://www.doi.org/10.1162/jocn.2009.21407).

* 256x256x128/oas2-3/*.png - [OAS2_0001_MR2](https://central.xnat.org/app/action/DisplayItemAction/search_element/xnat%3AmrSessionData/search_field/xnat%3AmrSessionData.ID/search_value/CENTRAL_E00090/popup/false/project/CENTRAL_OASIS_LONG)

National Archives Videos
------------------------
From [catalog.archives.gov](https://catalog.archives.gov/).

* 256x256x128/splashing/\*.png - [catalog.archives.gov/id/37490](https://catalog.archives.gov/id/37490) 
Moving Images No. 131-B-10; "CAMP ACTIVITIES OF BOYS AND GIRLS," ca. 1937-1940; Records of the Office of Alien Property, Record Group 131; National Archives at College Park, College Park, MD.
* 256x256x128/crowd/\*.png - [catalog.archives.gov/id/49737](https://catalog.archives.gov/id/49737) 
Moving Images No. 306.3394; "The March In Washington - 1963," August 1963; Records of the U.S. Information Agency, Record Group 306; National Archives at College Park, College Park, MD.

Other
-----
| Name | From | License |
| - | - | - |
| 2560x1920/hippocampus.png | [CIL:40967](http://www.cellimagelibrary.org/images/40967)<br>[doi:10.7295/W9CIL40967](https://doi.org/doi:10.7295/W9CIL40967) | CC BY NC ND |
| 1024x1024/gravel.png | [craziwolf-seamless-textures](https://www.deviantart.com/craziwolf/art/16-Free-Premium-Seamless-Ground-Textures-1024X1024-300739637) | CC BY 3.0 |
| 1024x1024/moss.png | [craziwolf-seamless-textures](https://www.deviantart.com/craziwolf/art/16-Free-Premium-Seamless-Ground-Textures-1024X1024-300739637) | CC BY 3.0 |
| 1920x1080/weathered-wood.png | [newevolutiondesigns-wood-textures](https://newevolutiondesigns.com/free-weathered-wood-textures) | CC BY 3.0 |

Electron Microscopy
-------------------
The 'em' images that are present in each image size are from the 'neuropil' dataset collected for Bush, J (2018). Spatial Distribution of Subcellular Organelles in Hippocampal Dendrites from High-Resolution EM Images. UC San Diego. This subset is licensed under CC BY 4.0.

Personal
--------
These photos were personally taken. 
License: CC BY 4.0.

* 1920x1080/stone.png
* 1920x1080/rocklayers.png
* 2560x1440/sandyrock.png
* 2560x1440/thewave.png

Generated
---------
All random images were generated for this image dataset as uniform random generated images. All of them can be used without any license.

