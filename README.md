# Lab 5
## Aim
To detect faces, extract Hue and Saturation features, perform K-Means clustering, and classify a template face.

## Methodology
- Face detection using Haar Cascade
- Feature extraction in HSV color space
- K-Means clustering
- Template face classification

## Visual Results
1. Multi Face Detection
  <img width="1595" height="1042" alt="image" src="https://github.com/user-attachments/assets/8ac63ab9-7458-4927-97a6-938b26c3b73f" />

2. Template Face Detection
   <img width="497" height="533" alt="image" src="https://github.com/user-attachments/assets/c22141b7-e568-4378-b5cd-58d77ce0d321" />

3. HSV Feature Distribution (With Face Thumbnails)
   <img width="1380" height="729" alt="image" src="https://github.com/user-attachments/assets/03939027-c511-4592-b9ad-91a868bd4c20" />

4. Clustered Faces with Centroids
   <img width="1382" height="730" alt="image" src="https://github.com/user-attachments/assets/b78c6354-27e4-48ce-b530-7de37fd14ec7" />

5. Clusters with Template (Image Overlay)
   <img width="1379" height="740" alt="image" src="https://github.com/user-attachments/assets/eeb4c17c-9f10-4f01-a0b5-391c02385964" />

6. Final Classification Plot
   <img width="1381" height="748" alt="image" src="https://github.com/user-attachments/assets/8273a9f0-6710-419c-aadb-4465e93fd7ad" />


## Results
Faces were grouped into two clusters based on color features.
The template image was successfully classified into one of the clusters.

## Conclusion
Distance-based clustering can group similar faces using simple color features.
