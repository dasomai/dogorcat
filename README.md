# dogorcat
## Image Classifier with PyTorch.


Use Anaconda to setup environment

https://pytorch.org/

Run this command: 

`conda install pytorch torchvision torchaudio pytorch-cuda=11.6 -c pytorch -c nvidia`


Setup other package along the way. 

After activate the environment. Run Jupyter Notebook by using anaconda navigate. 

Unzip the data set to train the model. 

At the train(model):

you can change the:

num_of_epochs = 300 

to 400 or more to become more accurate. 

Then change the load model here: 

model.load_state_dict(torch.load("models/model_ep299.pth"))


Resize the image to 256 pixel


## RESULT:



![image](https://user-images.githubusercontent.com/61308335/208120972-737a9db2-ce80-43cd-93fb-b97a460fe646.png)

![image](https://user-images.githubusercontent.com/61308335/208121098-d6fe0f3d-7665-4e2e-806f-c2d67d9e1225.png)

![image](https://user-images.githubusercontent.com/61308335/208121153-fef5c66b-b08f-475d-8315-fe510f07b0d8.png)


## Explain the code:

https://blog.paperspace.com/object-localization-using-pytorch-1/

https://blog.paperspace.com/object-localization-pytorch-2/



