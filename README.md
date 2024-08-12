# Cv2_based_object_tracking_curve_fitting_through_least_square_methods
The code uploaded utilizes cv2 to compute the centroid of the object that is under observation as it creates a parabolic trajectory through its motion. The folloeing GIF shows the object in motion for 
which the trajectory has to be calculated.

<img src="https://github.com/user-attachments/assets/b8413abf-ed22-414f-84c7-2c9f9c4ee7b0" alt="object_tracking" width="400"/>

The problem is solved by using the logical not operation after converting the image to grayscale. This helps in filtering out the pixels of the object through which the controid is calculated.
These centroids make a set of coordinates that are further used for application of the least square method to compute the estimated parabolic trajectory. Consider the following plots which demonstrate
the calculated parabola.

<img src="https://github.com/user-attachments/assets/03a620c8-88cc-4930-872a-fe77894e8b0c" alt="parabola_plot" width="400"/>

Another plot that shows the estimated trajectory on a frame extracted from the video.
<img src="https://github.com/user-attachments/assets/1a1e1b42-3a4f-4d88-b0c1-e986c241ce90" alt="parabola_image" width="400"/>
