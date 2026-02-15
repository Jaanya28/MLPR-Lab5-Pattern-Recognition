# MLPR-Lab5-Pattern-Recognition
Machine Learning &amp; Pattern Recognition Lab 5 Assignment
# Machine Learning & Pattern Recognition Lab 5

## Aim
To detect faces in an image, extract color-based features, cluster faces using K-Means, and classify a new face based on similarity.

## Methodology
The Viola–Jones Haar Cascade method was used for face detection. Detected face regions were converted to HSV color space, and Hue & Saturation features were extracted. K-Means clustering was applied to group similar faces. A template face image was then classified based on its feature similarity.

## Results
Faces were successfully detected and clustered based on color characteristics. The template face was classified into the closest cluster using feature similarity.

## Observations
Lighting and color variations influence clustering results. HSV color space improves robustness by separating color information from brightness.

## Key Learnings
This lab demonstrates the complete pattern recognition pipeline: detection, feature extraction, clustering, classification, and visualization.

## Sample Output
(Add screenshots of your plots here)

## Conclusion
Distance-based clustering provides an effective approach for grouping visually similar data. Feature selection plays a critical role in improving classification performance.

<img width="1268" height="633" alt="Screenshot 2026-02-15 at 16 33 57" src="https://github.com/user-attachments/assets/3a9f54e8-3f6f-4509-9435-3edc26002b8e" />
<img width="1039" height="572" alt="Screenshot 2026-02-15 at 16 34 15" src="https://github.com/user-attachments/assets/1cb7c836-7bd0-44ff-912a-07cd270427b7" />
<img width="1039" height="572" alt="Screenshot 2026-02-15 at 16 34 30" src="https://github.com/user-attachments/assets/7b7c8a16-138d-46ab-944a-6dc651a13d3b" />
<img width="415" height="405" alt="Screenshot 2026-02-15 at 16 34 44" src="https://github.com/user-attachments/assets/497d24dd-80ad-4353-bdac-a76ba764c0af" />
<img width="1012" height="548" alt="Screenshot 2026-02-15 at 16 34 59" src="https://github.com/user-attachments/assets/64be09b1-48ff-48cc-ba63-a9180d7f4084" />
<img width="1012" height="548" alt="Screenshot 2026-02-15 at 16 35 07" src="https://github.com/user-attachments/assets/cd31c5f3-3559-44c0-9be7-bb165ea0c055" />

