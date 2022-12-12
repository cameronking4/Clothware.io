# Clothware.io
Turn 2D images of clothing into realistic 3D garments. Use Clothware API to automate your clothing design, character design or integrate it into an e-commerce solution. Click [here](https://84fb-184-105-175-12.ngrok.io/docs#/default/upload_upload_post) to demo!

![Demo!](/demopants.gif "Example of generated 3D AMIRI pants")<br>
![Demo!](/image (2).png "Keypoint mapping texture onto 3d tshirt")<br>

## How it works 

Using API, make POST call with front & back images of T-shirt or pants. Specify type in form as 'shirt' or 'pants". <br>

![Clothware API!](/sc1.png "Make POST call with input form data")<br>

If the POST request is successful, you will recieve the generated 3D object, it's keypoints and texture.png. <br>

![Generate 3D Object!](/sc2.png "Get 3D object and texture")<br>

Drag the artifacts into an object viewer, such as [this one (3dviewer.net)](https://3dviewer.net/) and export the model. <br>
You can also manipulate the texture.png file in any [photo editor](https://pixlr.com) to refine the look and design of the garment.

## Examples

You can test the API with front (odd) & back (even) image files found in the 'input' folder of this repo. <br>
You can view example generated 3d objects by downloading one of the output zip files found in the 'output' folder of this repo.

![Success!](/demo.gif "Make use of 3d artifacts")<br>
