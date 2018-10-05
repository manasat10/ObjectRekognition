# ObjectRekognition

                                                Object Rekognition
This project is to provides information for detecting objects and calculating price and quantity , object name.
 The object recognition problem can be defined as a labeling problem based on models of known objects. Formally, given an image containing one or more objects of interest (and background) and a set of labels corresponding to a set of models known to the system, the system should assign correct labels to regions, or a set of regions, in the image. The object recognition problem is closely tied to the segmentation problem: without at least a partial recognition of objects, segmentation cannot be done, and without segmentation, object recognition is not possible. 

 

For example, Amazon Rekognition Image is able to detect the presence of a objects and also provide the percentage of object. It has in the accuracy of each detected label.
 
A label or a tag is an object, scene, or concept found in an image based on its contents. For example, a photo of drink cokes on a Basket may contain labels. We calculate the price, quantity and object name.  We can also look at the request to the API and the response from the API as a reference
Object Representation:

Images represent a scene from a camera's perspective. It appears natural to represent objects in a camera-centric, or viewer-centered, coordinate system. Another possibility is to represent objects in an object-centered coordinate system. Of course, one may represent objects in a world coordinate system also. Since it is easy to transform from one coordinate system to another using their relative positions, the central issue in selecting the proper coordinate system to represent objects is the ease of representation to allow the most efficient representation for feature detection and subsequent processes. 
A representation allows certain operations to be efficient at the cost of other operations. Representations for object recognition are no exception. Designers must consider the parameters in their design problems to select the best representation for the task. 
How to Detect Objects :
You can upload an image that you own or provide the URL to an image as input in the Amazon Rekognition console. Amazon Rekognition returns the object and scenes, confidence scores for each object, and scene it detects in the image you provide.
Note
The image must be less than 5MB in size and must be of JPEG or PNG format.
To detect objects and scenes in an image  provide
1.	Open the Amazon Rekognition console.
2.	Choose Object and scene detection.
3.	Do one of the following:
•	Upload an image – Choose Upload, go to the location where you stored your image, and then select the image.
•	Use a URL – Type the URL in the text box, and then choose Go.
4.	View the confidence score of each label detected in the Labels | Confidence pane.




 
