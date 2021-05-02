# The SARB

Note: We used [Compostnet](https://github.com/sarahmfrost/compostnet) as our dataset.

We created a bin, known as the SARB(self automated recycling bin), using the raspberry pi, that sorts out different types of waste materials automatically. The person has to put the item in the bin and then it will land on a slab of wood inside the bin. The item will be detected at first by a PIR sensor attached to our Raspberry PI. This sends a notification to the Camera Module(v2), which scans the object and then uses an image recognition software known as tensorflow (coded into our raspberry pi 4b) to work out whether the item is recyclable or not. A motor attached to the raspberry pi is instructed to move a lever, which is connected to a pivot, towards the required side of the right bin. Then the slab of wood collapses to put the item in its respective bin. We aim to reduce the amount of waste sent to landfills and incinerators and conserve natural resources. As recycling saves energy it also reduces greenhouse gas emissions, which helps to tackle climate change. Our automated recycling bin could be a step in the right direction to solve climate change. The items we used will be explained in detail next. 

## Step 1: Getting the code
Clone the GitHub onto a raspberry pi, using 'git clone ' on the raspberry pi terminal. 
## Step 2: Run the code or Create your own dataset.
If you are happy with the amount of images provided, all you have to do is run the code. Otherwise, you will have to add images to the file paths on the code and re preprocess the images, by running preprocess_images.py. 

## Step 3:




## Model Summary and Loss/Val Loss Chart

![loss_and_val_loss](https://user-images.githubusercontent.com/74100481/116826085-220c4c80-ab8a-11eb-853d-097272bc223f.jpg)


![This is the Model Summary](https://user-images.githubusercontent.com/74100481/116826087-246ea680-ab8a-11eb-943f-5180637ec508.png)

## Predictions

These are the predictions that the SARBnet.ipynb code produced.
![prediction_1](https://user-images.githubusercontent.com/74100481/116826422-ce026780-ab8b-11eb-94d8-2bd74f2394cb.png)


# Useful Links:

[google colab with our code on](https://colab.research.google.com/drive/12FXVMgZL7BkdDpsMrkfoTFxgxIgPeXEP?usp=sharing)

