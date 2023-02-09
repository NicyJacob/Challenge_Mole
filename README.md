# Challenge_Mole
The objective is to develop a tool that identifies moles on the human body that require medical attention. This solution will empower individuals to take control of their skin health, and provide a simple and efficient way for doctors to identify moles that may need further examination.


## Description
The project is divided into two stages, which are captured in the folder structure of the repository.

Neural Network Training: The 'Code' folder holds the Python code responsible for training a Convolutional Neural Network (CNN) model. The model is trained using a dataset that features images of benign and malignant skin cancers.

Mole Detection Interface: The 'Demo - Mole Detection.ipynb' file contains the program that powers the interface used to detect cancerous moles. Simply upload an image, and the program will use the trained CNN model to identify moles that may require medical attention.


## Getting Started
Dependencies needed before running the program. 

    pip install gradio
    pip install opencv-python

Executing program: 
Run the file Demo - Mole Detection.ipynb



## Output
![Interface](https://user-images.githubusercontent.com/113432231/217790245-51ceb7cf-3368-4e84-ac86-26ec0deacf30.png)


## Next Steps 
To further enhance the accuracy of image classification, consider the following steps:

Multi-Input Neural Network: By incorporating additional features such as age, gender, and location from metadata, a multi-input neural network can provide even more context and precision when classifying images.

Pre-Trained Model Utilization: A wide range of pre-trained models are readily available for image classification, including VGG-16, ResNet50, and Xception. Adopting a pre-trained model can significantly reduce training time and give access to established online tools, ultimately resulting in improved accuracy and efficiency.

## License
Free license

## Contact
Nicy Jacob: nicy.ck@gmail.com

## Acknowledgments
BeCode Arai4 AI coaches(Chrysanthi and Louis)
