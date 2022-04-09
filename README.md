# Demakeup Project Use Unet model, Resnet50 Pretrained

# Datasets: 
Makeup Style ---- No makeup ---- Makup
![0](https://user-images.githubusercontent.com/80930272/158276541-c1f6b408-f056-4094-a604-d6d24e9e81da.png)

# Model:
Unet architecture + Resnet50 Pretrained

![Screenshot 2022-03-15 062958](https://user-images.githubusercontent.com/80930272/158277432-8e6f1989-73b4-4e4b-b9f6-f0ea3ef34f00.png)

# Loss: You can choose L1 Loss or Perceptual Loss 

## L1 loss
![Screenshot 2022-03-15 063132](https://user-images.githubusercontent.com/80930272/158277584-1bb0e178-52d0-4bb8-ab7f-ce792c68c3f7.png)

## Perceptual Loss 
![Screenshot 2022-03-15 063356](https://user-images.githubusercontent.com/80930272/158277832-6504ead5-2900-4605-a459-0fac9202bd7c.png)

# Training: I used Kaggle to train model.
- Training 150 epochs with L1 loss
- Training 150 epochs with Perceptual Loss 

# Result:
## L1 loss
### PSNR: 29.8
### Makeup --- Demakeup Target --- Demakeup Result
![testing_result_0](https://user-images.githubusercontent.com/80930272/158278006-181a2847-6341-4fc3-b0e0-a72a3e528fa5.png)
![testing_result_9](https://user-images.githubusercontent.com/80930272/158278094-11db5b4c-867c-474e-a5f6-9c43a97fe8bc.png)
![testing_result_8](https://user-images.githubusercontent.com/80930272/158278269-cc5d3ebe-92a8-4603-aed4-80cde15f59e9.png)

## Perceptual Loss 
### PSNR: 30.08
### Makeup --- Demakeup Target --- Demakeup Result
![testing_result_3](https://user-images.githubusercontent.com/80930272/159156347-8b985761-4d50-4678-a459-a70e176871be.png)
![testing_result_4](https://user-images.githubusercontent.com/80930272/159156361-fc8784e7-3acb-43b0-9088-0a26e728096a.png)
![testing_result_12](https://user-images.githubusercontent.com/80930272/159156364-45c63420-878d-4c42-8a4d-b621aa9feee4.png)

# Reference
- https://arxiv.org/abs/2104.01867
- https://arxiv.org/pdf/1505.04597v1.pdf
- https://github.com/VinAIResearch/CPM
