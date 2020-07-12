# Tool-To-Help-Policing
This project was built in Gurugram Police Cyber Security Internship under guidance of `Mr Rakshit Tandan` (Cyber Security Expert). It is a Vehicle Tracking Web App specially designed for Police Authorities to find the required vehicle very easily.
## Working of Model
First of all, the input from cctv camera will get processed into the DL Algorithm for detection of License Plate of the vehicle. After the number on the license plate get detected,Location of the camera with the number plate will be saved into the database with date and time. So in website if we want to find the location of any vehicle which is connected to any crime or the any type of F.I.R is done for that vehicle ,it can be found easliy.
#### Install these packages to run the License Plate detection Model.
##### Install [opencv](https://pypi.org/project/opencv-python/)
`pip install opencv-python`

##### Install [pytesseract](https://pypi.org/project/pytesseract/)
`pip install pytesseract`

##### Install [Firebase](https://pypi.org/project/firebase/)
`pip install firebase`

Pass any recording to [this](https://github.com/Ruchikamodgil/Tool-to-help-policing/blob/master/Vehicle%20License%20Plate%20Detection.ipynb) to detect the License Plate of vehicle.

### Input
![img](https://github.com/Ruchikamodgil/Tool-to-help-policing/blob/master/input.png)
### Result
![img](https://github.com/Ruchikamodgil/Tool-to-help-policing/blob/master/result.png)

### After the detection of License Plates, the information get updated into the database and the police authorities can fetch the information using this Dektop App.
![img](https://github.com/Ruchikamodgil/Tool-to-help-policing/blob/master/web%20page.png)


### Input the License Plate number and get the results i.e., Live Location of Vehicle on map with Time and Date.
![img](https://github.com/Ruchikamodgil/Tool-to-help-policing/blob/master/web%20results.png)



## [Link](https://drive.google.com/file/d/1HKoMZYo1Nr1DIwAz_hGTtDlGtpqxFk75/view?usp=sharing) to demo video(it contains the proper demo on how to use this with explained Features)

# [Link](https://gdeepanshu46.github.io/findmyvehicle.github.io/) to Website (Made for Authorities only)
