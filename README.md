# CSI Organ At Risk AutoSegmentation on TMH 3D CT Dataset <br />
Auto segmentation of Cranio-spinal Irradiation Organs At Risk in 5mm 3D CT Scans <br />

# Dataset <br />
   Tata Memorial Hospital CSI 3D CT Data <br />
# Models Used - <br />
   3D UNET <br />

# Classes <br />
   Background, Spleen, Right and Left kidney, Esophagus, Liver, Stomach, Pancreas, Bowel Bag, Right and Left Lungs <br />

# Configuration <br />
   Image Preprocessing - Random Center Crop, Drop Invalid range, Clipping, Resizing, Volume Intensity Normalization <br />
   Optimizer- Adam Optimizer <br />
   LR - Cosine Annealing LR <br />
   Loss Fn - BCEDICE LOSS at Multiple Output Layers/scales <br />

# Results <br />
   •Dice Score between 0.7 - 0.9 for all the classes except Esophagus <br />

![ Alt text ](https://github.com/parth-radonc/TMH_CSI_OAR_SEGMENTATION/blob/main/Results/res.jpg?raw=true) 

 
