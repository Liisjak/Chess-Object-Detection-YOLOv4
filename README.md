# Chess-Object-Detection-YOLOv4

### Watch the presentation of the whole procedure of creating the chess pieces object detection model, position digitiser and smartphone application in this [YouTube video](https://www.youtube.com/watch?v=Tj1lcSwxBYY).

In-depth, step-by-step explanation for some of the steps is given in the Jupyter Notebooks. In the following, instructions on how an when to use the files uploaded in this repository are given. For visual presentation of each step, watching the above Youtube video is recommended.

# CHAPTER1 1: 

The purpose of this step is creating images that can be used with a Photogrammetry software to create 3D models of the pieces. I used the so-called "Void method". Watch this video for more details on this method:
- [Erik Christensen: Scanning in the Void - A short video on good turntable setups](https://www.youtube.com/watch?v=Il6LVXqSlRg)
Photogrammetry softwares rely on background features to calculate the camera positions for each image. For this reason, the object must be at rest while the camera moves around it. The point of the "Void method" is to create images that have no features in the background. In this case, the only image features that the Photogrammetry software can use are the features of the piece itself. Main advantage of this method is that you can use a turntable and spin the piece while the camera is at rest. In general photogrammetry is very delicate work. Many things can (and will) go wrong. If you do not have the photography equipment, required for the "Void method", you can use normal photogrammetry. Two excellent videos on this subject:
- [Switch & Lever: How to Copy (almost) Any Object](https://www.youtube.com/watch?v=0WTns1ItVss) 
- [CG Geek: How to 3D Photoscan Easy and Free!](https://www.youtube.com/watch?v=k4NTf0hMjtY)