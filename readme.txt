The dataset can be found in the folder by the name of CovidData_GradientCrescent. Decompressing this folder will give you 2 folders by the name of two and all. These are the datasets for the binary problem and multi class problem respectively.

For both the notebooks, we have not commented out the function to train the model. If you decided to train the model yourself, you can do so by directly running the cells where we use the fit_generator() method. If you choose to run the codes with our trained and saved weights, you can do so by loading the model weights as we have mentioned below.


The ipython notebook for the binary task is  is called 'task_1.ipynb'
The weights for the model (Tuned VGG16)  used for evaluating on the test set is in the file "best_model.h5"


The ipython notebook for the multiclass calssification is called 'task_2.ipynb'
In Task 2 we have used 3 models for evaluating on the test set. 
The file with the weights are as follows:

Tuned VGG16: "best_model_task2.h5"
Tuned Xception: "best_model_2_task2.h5"
Tuned Self created network: "best_model_3_task2.h5"