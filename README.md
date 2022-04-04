##Digit classifier on the SVHN (Street View Housing Number) dataset

Recognising multi-digit numbers in photographs captured at street level is an important component of modern-day map making. A classic 
example of a corpus of such street-level photographs is Google’s Street View imagery composed of hundreds of millions of geo-located 360-degree panoramic 
images. 

The ability to automatically transcribe an address number from a geo-located patch of pixels and associate the transcribed number with a known street address 
helps pinpoint, with a high degree of accuracy, the location of the building it represents. More broadly, recognising numbers in photographs is a problem of interest 
to the optical character recognition community. 
While OCR on constrained domains like document processing is well studied, arbitrary multi-character text recognition in photographs is still highly challenging. This 
difficulty arises due to the wide variability in the visual appearance of text in the wild on account of a large range of fonts, colours, styles, orientations, and character 
arrangements. 

The recognition problem is further complicated by environmental factors such as lighting, shadows, specularity, and occlusions as well as by image acquisition 
factors such as resolution, motion, and focus blurs. In this project, we will use the dataset with images centred around a single digit (many of the images do contain 
some distractors at the sides). Although we are taking a sample of the data which is simpler, it is more complex than MNIST because of the distractors

Dataset:
The SVHN is a real-world image dataset for developing machine learning and object recognition algorithms with the minimal requirement on 
data formatting but comes from a significantly harder, unsolved, real-world problem (recognising digits and numbers in natural scene images). SVHN is obtained 
from house numbers in Google Street View images.

