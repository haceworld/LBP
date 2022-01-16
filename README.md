Local  Binary Pattern (LBP)

Task:  Converting multiple images in a folder (also a single image) to LBP images 

LBP-Local-Binary-Pattern
Local binary patterns are a features used for classification in the field of machine vision. It is a powerful powerful feature in texture classification; if the local binary pattern feature is combined with the directional gradient histogram, it can effectively improve the detection effect. Local binary mode is a simple but very efficient texture operator. It compares each pixel with its neighbors and saves the result as a binary number. Due to its strong discriminative power and computational simplicity, local binary pattern texture operators have been applied in different scenarios. The most important property of LBP is robustness to grayscale changes such as illumination changes. Another important feature of it is its computational simplicity, which enables real-time analysis of images.

This is the code for preproessing original images to local binary pattern (LBP) images. This code is put together for help researcher process their images into LBP. The good thing about this code is that it reads multiple images from a folder, process them into LBP, and save them in another folder. Few changes that needs to be done are: Just change the path to your folders. The result of the code is presented below:



![CT2](https://user-images.githubusercontent.com/61402731/149645426-baf7ff76-7d1a-4efa-8006-b053db232d9b.png)
Original CT image










![CT_2_LBP](https://user-images.githubusercontent.com/61402731/149645424-14478e74-4d7c-42ea-a7b9-425e71d77782.jpg)

LBP CT image









