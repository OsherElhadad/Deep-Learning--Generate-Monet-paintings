
# Deep Learning Project

  

### Introduction

Our project involves utilizing deep learning techniques to create Monet-inspired images from photographs. To achieve this, we acquired a dataset from 'kaggle' containing both Monet's artworks and regular photographs. We then proceeded to train multiple models using this dataset. The project is composed of two phases: training and testing, and it explores two distinct image style transfer architectures: cycleGAN and neural style transfer.


## Colab notebook structure:

The train notebook is divided to 3 parts, data and 2 architectures: CycleGan and Neural Style Transfer using VGG:

- [Final Project - Deep Learning - Training Notebook](https://colab.research.google.com/drive/1eo1SebGTWmZGYwd7NeUekpKRtKbnLta_?usp=sharing#scrollTo=Final_Project_Deep_Learning_Training_Notebook)

	- [Libraries, Data and Defualt Seed](https://colab.research.google.com/drive/1eo1SebGTWmZGYwd7NeUekpKRtKbnLta_?usp=sharing#scrollTo=Libraries_Data_and_Defualt_Seed)

		- [Import Libraries](https://colab.research.google.com/drive/1eo1SebGTWmZGYwd7NeUekpKRtKbnLta_?usp=sharing#scrollTo=Import_Libraries)

		- [Load Dataset](https://colab.research.google.com/drive/1eo1SebGTWmZGYwd7NeUekpKRtKbnLta_?usp=sharing#scrollTo=Load_Dataset)

		- [Set Default Random Seed](https://colab.research.google.com/drive/1eo1SebGTWmZGYwd7NeUekpKRtKbnLta_?usp=sharing#scrollTo=Set_Default_Random_Seed)

- [CycleGAN - Monet paintings](https://colab.research.google.com/drive/1eo1SebGTWmZGYwd7NeUekpKRtKbnLta_?usp=sharing#scrollTo=CycleGAN_Monet_paintings)

	- [Smart Select Paintings](https://colab.research.google.com/drive/1eo1SebGTWmZGYwd7NeUekpKRtKbnLta_?usp=sharing#scrollTo=Smart_Select_Paintings)

	- [Custom Dataset](https://colab.research.google.com/drive/1eo1SebGTWmZGYwd7NeUekpKRtKbnLta_?usp=sharing#scrollTo=Custom_Dataset)

	- [Create datasets and dataloader](https://colab.research.google.com/drive/1eo1SebGTWmZGYwd7NeUekpKRtKbnLta_?usp=sharing#scrollTo=Create_datasets_and_dataloader)

		- [Show dataloader batch as images](https://colab.research.google.com/drive/1eo1SebGTWmZGYwd7NeUekpKRtKbnLta_?usp=sharing#scrollTo=Show_dataloader_batch_as_images)

	- [Discriminator and Generator models](https://colab.research.google.com/drive/1eo1SebGTWmZGYwd7NeUekpKRtKbnLta_?usp=sharing#scrollTo=Discriminator_and_Generator_models)

		- [Convolution and Deconvolution](https://colab.research.google.com/drive/1eo1SebGTWmZGYwd7NeUekpKRtKbnLta_?usp=sharing#scrollTo=Convolution_and_Deconvolution)

		- [Residual Block](https://colab.research.google.com/drive/1eo1SebGTWmZGYwd7NeUekpKRtKbnLta_?usp=sharing#scrollTo=Residual_Block)

		- [Discriminator Model](https://colab.research.google.com/drive/1eo1SebGTWmZGYwd7NeUekpKRtKbnLta_?usp=sharing#scrollTo=Discriminator_Model)

			- [Discriminator loss](https://colab.research.google.com/drive/1eo1SebGTWmZGYwd7NeUekpKRtKbnLta_?usp=sharing#scrollTo=Discriminator_loss)

		- [Generator Model](https://colab.research.google.com/drive/1eo1SebGTWmZGYwd7NeUekpKRtKbnLta_?usp=sharing#scrollTo=Generator_Model)

			- [Cycle Generator loss](https://colab.research.google.com/drive/1eo1SebGTWmZGYwd7NeUekpKRtKbnLta_?usp=sharing#scrollTo=Cycle_Generator_loss)

	- [Training Functions](https://colab.research.google.com/drive/1eo1SebGTWmZGYwd7NeUekpKRtKbnLta_?usp=sharing#scrollTo=Training_Functions)

	- [Experiment 1](https://colab.research.google.com/drive/1eo1SebGTWmZGYwd7NeUekpKRtKbnLta_?usp=sharing#scrollTo=Experiment_1)

	- [Experiment 2](https://colab.research.google.com/drive/1eo1SebGTWmZGYwd7NeUekpKRtKbnLta_?usp=sharing#scrollTo=Experiment_2)

	- [Experiment 3 - Best Model](https://colab.research.google.com/drive/1eo1SebGTWmZGYwd7NeUekpKRtKbnLta_?usp=sharing#scrollTo=Experiment_3_Best_Model)

- [Neural Style Transfer - Monet paintings](https://colab.research.google.com/drive/1eo1SebGTWmZGYwd7NeUekpKRtKbnLta_?usp=sharing#scrollTo=Neural_Style_Transfer_Monet_paintings)

	- [VGG Model](https://colab.research.google.com/drive/1eo1SebGTWmZGYwd7NeUekpKRtKbnLta_?usp=sharing#scrollTo=VGG_Model)

	- [Experiments on the model](https://colab.research.google.com/drive/1eo1SebGTWmZGYwd7NeUekpKRtKbnLta_?usp=sharing#scrollTo=Experiments_on_the_model)

		- [Base Model](https://colab.research.google.com/drive/1eo1SebGTWmZGYwd7NeUekpKRtKbnLta_?usp=sharing#scrollTo=Base_Model)

		- [Experiment 1](https://colab.research.google.com/drive/1eo1SebGTWmZGYwd7NeUekpKRtKbnLta_?usp=sharing#scrollTo=Experiment_1)

		- [Experiment 2](https://colab.research.google.com/drive/1eo1SebGTWmZGYwd7NeUekpKRtKbnLta_?usp=sharing#scrollTo=Experiment_2)

		- [Experiment 3](https://colab.research.google.com/drive/1eo1SebGTWmZGYwd7NeUekpKRtKbnLta_?usp=sharing#scrollTo=Experiment_3)

		- [Experiment 4 - Best Model](https://colab.research.google.com/drive/1eo1SebGTWmZGYwd7NeUekpKRtKbnLta_?usp=sharing#scrollTo=Experiment_4_Best_Model)
  
The test notebook is also divided to 3 parts, data and 2 architectures: CycleGan and Neural Style Transfer using VGG:

  - [Final Project - Deep Learning - Test Notebook](https://colab.research.google.com/drive/1Rxzt4qTrm6R4wO-U5xuPwPYqasfUy_Qz?usp=sharing#scrollTo=Final_Project_Deep_Learning_Test_Notebook)

	- [Libraries and default seed](https://colab.research.google.com/drive/1Rxzt4qTrm6R4wO-U5xuPwPYqasfUy_Qz?usp=sharing#scrollTo=Libraries_and_default_seed)

		- [Import Libraries](https://colab.research.google.com/drive/1Rxzt4qTrm6R4wO-U5xuPwPYqasfUy_Qz?usp=sharing#scrollTo=Import_Libraries)

		- [Set Default Random Seed](https://colab.research.google.com/drive/1Rxzt4qTrm6R4wO-U5xuPwPYqasfUy_Qz?usp=sharing#scrollTo=Set_Default_Random_Seed)

- [CycleGAN - Monet paintings](https://colab.research.google.com/drive/1Rxzt4qTrm6R4wO-U5xuPwPYqasfUy_Qz?usp=sharing#scrollTo=CycleGAN_Monet_paintings)

	- [Custom Dataset](https://colab.research.google.com/drive/1Rxzt4qTrm6R4wO-U5xuPwPYqasfUy_Qz?usp=sharing#scrollTo=Custom_Dataset)

	- [Generator model](https://colab.research.google.com/drive/1Rxzt4qTrm6R4wO-U5xuPwPYqasfUy_Qz?usp=sharing#scrollTo=Generator_model)

		- [Convolution and Deconvolution](https://colab.research.google.com/drive/1Rxzt4qTrm6R4wO-U5xuPwPYqasfUy_Qz?usp=sharing#scrollTo=Convolution_and_Deconvolution)

		- [Residual Block](https://colab.research.google.com/drive/1Rxzt4qTrm6R4wO-U5xuPwPYqasfUy_Qz?usp=sharing#scrollTo=Residual_Block)

		- [Generator Model](https://colab.research.google.com/drive/1Rxzt4qTrm6R4wO-U5xuPwPYqasfUy_Qz?usp=sharing#scrollTo=Generator_Model)

	- [Load The Trained CycleGAN Model](https://colab.research.google.com/drive/1Rxzt4qTrm6R4wO-U5xuPwPYqasfUy_Qz?usp=sharing#scrollTo=Load_The_Trained_CycleGAN_Model)

	- [Show generated monet paintings](https://colab.research.google.com/drive/1Rxzt4qTrm6R4wO-U5xuPwPYqasfUy_Qz?usp=sharing#scrollTo=Show_generated_monet_paintings)

- [Second Model - Neural Style Transfer (NST)](https://colab.research.google.com/drive/1Rxzt4qTrm6R4wO-U5xuPwPYqasfUy_Qz?usp=sharing#scrollTo=Second_Model_Neural_Style_Transfer_NST_)

	- [Load Dataset](https://colab.research.google.com/drive/1Rxzt4qTrm6R4wO-U5xuPwPYqasfUy_Qz?usp=sharing#scrollTo=Load_Dataset)

	- [Create datasets and dataloader](https://colab.research.google.com/drive/1Rxzt4qTrm6R4wO-U5xuPwPYqasfUy_Qz?usp=sharing#scrollTo=Create_datasets_and_dataloader)

	- [VGG Model](https://colab.research.google.com/drive/1Rxzt4qTrm6R4wO-U5xuPwPYqasfUy_Qz?usp=sharing#scrollTo=VGG_Model)

	- [Test Model](https://colab.research.google.com/drive/1Rxzt4qTrm6R4wO-U5xuPwPYqasfUy_Qz?usp=sharing#scrollTo=Test_Model)

## Instructions to run code
Train notebook:

- To run the first model, CycleGan, you need first to run the "Libraries, Data and Defualt Seed" section and then run "CycleGan - Monet paintings" section.

- To run the second model, Neural Style Transfer, you need first to run the "Libraries, Data and Defualt Seed" section and then run "Neural Style Transfer - Monet Paintings" section.

Test notebook:

- To run the first model, CycleGan, you need first to run the "Final Project - Deep Learning - Test Notebook" section and then run "CycleGan - Monet paintings" section and upload a 256x256 photo.

- To run the second model, Neural Style Transfer, you need first to run all and upload a 256x256 photo.
