# CNN_parking

The purpose is the development of machine learning models for the detection of empty on-street parking spaces in urban road networks based on data provided by in-vehicle cameras that are already, or soon will be, a standard vehicle equipment. A rolling spatial interval is used to identify the existence of an on-street parking space and the properties of empty spaces are used to determine the availability of the parking space. Convolutional Neural Networks are developed, trained and evaluated with the use of images from a moving vehicle camera. The images are preprocessed and converted to suitable matrices, so that only the useful information for the empty on-street parking space detection problem is preserved. The optimized Convolutional Networks, in terms of structural and learning parameters, provided predictions for the detection of empty on-street parking spaces with approximately 90% average accuracy. The proposed model, although not deep, performs better than a relatively complex SVMs, which supports its appropriateness as an approach. 

Experiment Specifications                                                                     
Device:			GoPro Hero 4 Camera                                                                                          
Method of Input:	1080 Medium Video                                                                                         
Position:		0cm from the ground, with an angle of 75 degrees from perpendicular                                       
Location:		Athens Greece                                                                                              
Dates (Weather):	21st of April 2016 (sunny), 4th of May 2016 (cloudy, clear), 7th of May 2016 (sunny)
Image Generation:       Captured every 0.1 sec from the saved videos                                                                       
Image Size:             Uploaded on 128x72 – Initially 1280x720                                                                      
Image Categories:       Manual Classification into two groups “Easy” and “Difficult” –as they are given- after excluding captures of intersections
Sets:	Easy(7413), Difficult (923)                                                                      
Image Cropping:	Final Image Size used to train CNN 128x56 – cropped top 16 pixels-                                        

To download the data visit https://app.box.com/s/qm5jp9va9dck218jytbse1fy85knqz8s 

For further questions contact kgkolias93@gmail.com.
