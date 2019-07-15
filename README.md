## Sensor Fusion : Extended Kalman Filter

* In this project I combined input from LIDAR and RADAR sensors which are located on a self-driving car, to detect and track the movement of another car in the environment. 

* Both sensors give us information about the position and velocity of the second car, but each of them has advantages and disadvantages.

* When combining the input from both of them, we can get a much more accurate information about the second car's movement.

* Using the the Extended Kalman filter algorithm , we can predict the location and the velocity of the second car in the next second.

### Technical details
---
* The project is in C++ and using a third party library called Eigen : <http://eigen.tuxfamily.org/index.php?title=Main_Page>

* The 2 videos below show the predicted car's movement in a Unity simulator. The first show the prediction for dataset 1  (LIDAR and RADAR sensors data) and the second show the prediction for a second dataset.

* The prediction is shown as green arrows, the RADAR input are blue dots and the LIDAR input are red dots.

* The RMSE (root-mean-square error ) is a frequently used measure of the differences between values predicted and the values actually observed.

Dataset1:


[![Dataset1](http://i.imgur.com/9wPOwgq.png)](https://vimeo.com/229871486 "Dataset1")



Dataset2:


[![Dataset2](http://i.imgur.com/XUeWwiB.png)](https://vimeo.com/229871527 "Dataset2")
