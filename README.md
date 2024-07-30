# face-segmentation.Pytorch


## Training
+ 1.Prepare training data: -- download [CelebAMask-HQ dataset](https://github.com/switchablenorms/CelebAMask-HQ)

   -- change file path in the prepropess_data.py and run
> python prepropess_data.py

If you do not wish to train the model, you can download [pre-trained model](https://drive.google.com/file/d/154JgKpzCPW82qINcVieuPH3fZ2e0P812/view) and save it in res/cp.

# evaluate using GPU
python test.py
## Results

<div align="center">
  <img src="https://user-images.githubusercontent.com/92161283/214219180-64441ea6-1da5-456f-9ea4-0acb4094ecb3.png" width="400" />
  <img src="https://user-images.githubusercontent.com/92161283/214226581-91c4b672-2c4a-48b6-afe3-962ebe31837b.png" width="400" />
</div>

<div align="center">
  <img src="https://user-images.githubusercontent.com/92161283/214226827-b01cd1a0-f385-4aca-8a37-eaeda47fe4b6.png" width="400" />
  <img src="https://user-images.githubusercontent.com/92161283/214226925-d7f06fbd-ff03-4054-8942-6e9f21c497f7.png" width="400" />
</div>

