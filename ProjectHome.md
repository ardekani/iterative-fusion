We use Richardson–Lucy (RL) deconvolution to combine multiple images of a simulated object into a single image in the context of modern fluorescence microscopy techniques. RL deconvolution can merge images with very different point-spread functions, such as in multiview light-sheet microscopes(1, 2), while preserving the best resolution information present in each image. We show that RL deconvolution is also easily applied to merge high-resolution, high-noise images with low-resolution, low-noise images, relevant when complementing conventional microscopy with localization microscopy. We also use RL deconvolution to merge images produced by different simulated illumination patterns, relevant to structured illumination microscopy (SIM, 3, 4) and image scanning microscopy (ISM). The quality of our ISM reconstructions is at least as good as reconstructions using standard inversion algorithms for ISM data, but our method follows a simpler recipe that requires no mathematical insight. Finally, we apply RL deconvolution to merge a series of ten images with varying signal and resolution levels. This combination is relevant to gated stimulated-emission depletion (STED) microscopy, and shows that merges of high-quality images are possible even in cases for which a non-iterative inversion algorithm is unknown.

Find the `ChemPhysChem` paper relevant code here, and the article at  http://dx.doi.org/10.1002/cphc.201300831

  1. M. Temerinac-Ott, O. Ronneberger, P. Ochs, W. Driever, T. Brox, H. Burkhardt, IEEE Trans. Image Process 2012, 21, 1863
  1. M. Temerinac-Ott, O. Ronneberger, R. Nitschke, W. Driever, H. Burkhardt, IEEE I. S. Biomed. Imaging 2011, 899
  1. M. G. Gustafsson, J. Microsc. 2000, 198, 82
  1. C. B. Müller, J. Enderlein, Phys. Rev. Lett. 2010, 104, 198101