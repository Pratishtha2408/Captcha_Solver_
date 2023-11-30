Team name: Next_level_neuro

Team members:
Pratishtha Dhiraj
(pratishtha.dhiraj.ece20@itbhu.ac.in)

Riya Saini
(riya.saini.ece20@itbhu.ac.in)

Approach:

To extract letters and captcha images we have used python computervision library opencv.
#Using the segmentation code (img_cleaning(), read()) ->
	1. Segment letters from digital images as well as handwritten images
	2. Can read colorful images(red,blue,black text on white background)
	3. To some extend the code also segments shadowed images
	4. Can also segment letters in the presence of noise

For training the model we have used CNN 
Loss is evaluated using Cross Entrophy loss 
Optimizer used is Adam

