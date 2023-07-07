# fallDetectionSystem
We have enhanced the capabilities of human pose estimation using the openpifpaf library. Our augmentation includes support for multi-camera and multi-person tracking. Additionally, we have incorporated a long short-term memory (LSTM) neural network into the system to predict two classes: "Fall" or "No Fall". To accomplish this, we extract five temporal and spatial features from the detected poses. These features are then fed into an LSTM classifier for further processing and classification.

```shell script
pip install -r requirements.txt
```

## Dataset
The [UP-Fall Detection](https://sites.google.com/up.edu.mx/har-up/) was used to train the LSTM model.

## Outputs
Here are some of the desired outputs by the fall detector
![Output1: Normal](https://github.com/Alkesh6/fallDetectionSystem/blob/main/examples/output.png)
![Output2: Fall Warning](https://github.com/Alkesh6/fallDetectionSystem/blob/main/examples/output-1.png)
![Output3: Fall](https://github.com/Alkesh6/fallDetectionSystem/blob/main/examples/output-2.png)




