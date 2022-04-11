RigNet for 2D Characters

This project was inspired by https://github.com/zhan-xu/RigNet and developed during Google Explore CSResearch 2021-2022.

Abstract:
2DRigNet is a method that automates the process of rigging or creating a skeletal structure for 2D characters. Given
a 2D character, the 2DRigNet retrieves a 3D character from a database whose front view is similar to the 2D character. It then uses RigNet, an existing method that rigs 3D characters, to predict a skeleton and skinning weights for that character and transfers the skeleton and skinning weights back to the original 2D character. This would streamline the rigging process for 2D animators so that they can move on to the process of modifying character movements.


Image Reconstruction Results<br />
![Screen Shot 2022-04-11 at 11 30 46](https://user-images.githubusercontent.com/61430150/162710699-0e4eed2d-5370-43fe-a8c5-31fe5bee8dd6.png)<br />

Image Retrieval Results<br />
![Screen Shot 2022-04-11 at 11 31 01](https://user-images.githubusercontent.com/61430150/162711061-1bbce867-ab0f-4c3a-928c-19f16a755aad.png)<br />

The next step of the process is shape transfer.
