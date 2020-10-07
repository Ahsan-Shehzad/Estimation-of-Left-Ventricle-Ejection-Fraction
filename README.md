# Comparative Study for Estimation of Left Ventricle Ejection Fraction using Cardiac MRIs
Human heart has two main chambers Left Ventricle (LV) and Right Ventricle (RV).
Ejection Fraction (EF) is the blood volume ratio of LV, systole (heart contraction)
and diastole (heart relaxation) ejected with each heartbeat. Ejection fraction of left
ventricle is a key indicator for diagnosing cardiac diseases. One of the methods
was to calculate the blood volume by using 3-D model, some segmentation techniques
and learning base methods. The proposed method is for accurate estimation
of blood volume for cardiac left ventricle without applying any basic mathematical
shape.This method is based on region growing segmentation and on Cavalieri
stereology volume estimation method. The stereology volume is estimated by calculating
area of segmented images multiply with slice thickness. Then we train the
curve fitting model and regression model to those stereology volumes with systole
and diastole blood volume label. The trained model predicts the cardiac left ventricle
systole and diastole blood volume. The ejection fraction ratio is calculated from
the predicted blood volumes. Further we analyze this approach based on gender
and age. The proposed method requires different number of short axis views of LV.
The data of 700 subjects (with different number of cardiac MRIs slices of each subject)
was collected with their systole and diastole blood volume labels. Dataset set
is provided on kaggle website. Dataset contains seven hundred subject data. Each
subject has different number of LV view scans. One view contains thirty MR slices.
All Images are in DICOM format. Dataset is divided into training and testing set.
Five hundred subject’s data used for training and two hundred subject’s data used
for testing. The systole and diastolic blood volume of those subject is provided as
target. Our method gives less Root Mean Square Error (RMSE) when we divide
data on age bases. Our method is computationally less expensive because has less
computational cost in term of time and hardware resources.
