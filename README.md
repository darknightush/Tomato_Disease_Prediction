### :tw-1f33f: PlantVillage Dataset :tw-1f33f: 

This dataset is taken from Kaggle and below the link is given.
https://www.kaggle.com/emmarex/plantdisease

### :tw-1f33f:  :tw-1f345:  Tomato Disease Prediction   :tw-1f345: :tw-1f33f: 


#### :tw-1f33f:  Early Blight  :tw-1f33f: 
- Early blight is one of the most common tomato diseases, occurring nearly every season wherever tomatoes are grown.
- It affects leaves, fruits and stems and can be severely yield limiting when susceptible cultivars are used and weather is favorable.
- Severe defoliation can occur and result in sunscald on the fruit.  
- Early blight is common in both field and high tunnel tomato production in Minnesota.

![](https://content.ces.ncsu.edu/media/images/IMG_1301.JPG)

(Source credit :  NC State Extension Publications - NC State University)

#### :tw-1f33f:  Late Blight  :tw-1f33f: 
- Late blight is a potentially devastating disease of tomato and potato, infecting leaves, stems, tomato fruit, and potato tubers.
- The disease spreads quickly in fields and can result in total crop failure if untreated.
- Late blight does not occur every year in Minnesota. 
- Late blight of potato was responsible for the Irish potato famine of the late 1840s.

![](https://www.openaccessgovernment.org/wp-content/uploads/2019/12/dreamstime_s_83237974.jpg)

(Source credit :  Open Access Goverment and Paplauski Vital)

###  :tw-1f33f:  Objective  :tw-1f33f: 
- Developing deep learning model to predict image of tomato leaves which will be having a disease.
- Creating User Interface using Gradio Library

####  :tw-1f33f:  Prerequisites  :tw-1f33f: 
- Python = 3.7.12
- Tensorflow (with Keras) = 2.5.0
- Seaborn = 0.11.2
- Jupyter=1.0.0
- Gradio=2.6.3

####  :tw-1f33f:  Instructions  :tw-1f33f: 
- Create an anaconda environment "myenv" with mentioned Python version.
"conda create -n myenv python=3.7.12".

- Run command "pip install -r requirements.txt"  on your prompt.

- Run "Tomato_Disease_Prediction.ipynb" this file at the end "h5.file" will generate which will be later used by another file "User_Interface.ipynb"

- Now, Run "User_Interface.ipynb",  at the end you will see public url, click on it check the model prediction!

### :tw-1f33f:  Interface Sample :tw-1f33f:

![image](https://raw.githubusercontent.com/darknightush/Tomato_Disease_Prediction/Master/snapshots/early.PNG)

![image](https://raw.githubusercontent.com/darknightush/Tomato_Disease_Prediction/Master/snapshots/Healthy.PNG)

![image](https://raw.githubusercontent.com/darknightush/Tomato_Disease_Prediction/Master/snapshots/late.PNG)



####  :tw-1f33f: Images Credits  :tw-1f33f:
- NC State Extension Publications - NC State University
- Open Access Goverment and Paplauski Vital

####  :tw-1f33f: Acknowledgements :tw-1f33f:
- This dataset was gotten from spMohanty's GitHub Repo
