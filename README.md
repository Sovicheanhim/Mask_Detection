# CoronaMaskOn
> Mask control with computer vision
> This project is my modification from ulgacemre.I like the idea of this and I thought it would be cool to implement this. But all credits go to ulgacemre. He is the one who made the happen.


![](images/corona.png)

WHO(World Health Organization)
https://www.who.int/health-topics/coronavirus#tab=tab_1

Coronavirus disease (COVID-19) is an infectious disease caused by a newly discovered coronavirus.
Most people infected with the COVID-19 virus will experience mild to moderate respiratory illness and recover without requiring special treatment.  Older people, and those with underlying medical problems like cardiovascular disease, diabetes, chronic respiratory disease, and cancer are more likely to develop serious illness.
).

<p>
<img width="410" height="360" src="images/mask_off.png" >
<img width="410" height="360" src="images/mask_on.png" align="right">
</p>

# Dataset 

- The pictures were downloaded from google with the [chrome extension](https://chrome.google.com/webstore/detail/download-all-images/ifipmflagepipjokmbdecpmjbibjnakm).
- Faces in the pictures were detected and extracted with the Opencv library. After that converted to grayscale format. 

![](images/prepare_data.png)

# Training
Training details are in this notebook: [training.ipynb](training.ipynb).

# Try It Yourself

Here is where you can find the trained model [here](https://drive.google.com/open?id=1nRxPkhaljcz53KJCN51p2DHrobVLQAnB).

To try application with webcam, run below code.

``` 

python camera_mask_control.py

```

