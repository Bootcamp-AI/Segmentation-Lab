## Semantic Segmentation Lab ##

#### Setup

#### Clone the Repository and Run the Notebook

Run the commands below to clone the lab repository and then run the notebook:
```sh
git clone https://github.com/bootcamp-ai/Segmentation-Lab.git
# Make sure your conda environment is activated!
jupyter notebook
```
The Jupyter interface will open in your browser. You can then access the cloned repo and the Jupyter Notebook from there. We are specifically working with the `segmentation_lab.ipynb` which can be found in following path `code/segmentation_lab.ipynb`.

#### Download the Data

After you have the notebook up and running be sure to download the [training](https://s3-us-west-1.amazonaws.com/udacity-robotics/Deep+Learning+Data/Lab/train.zip) and [validation](https://s3-us-west-1.amazonaws.com/udacity-robotics/Deep+Learning+Data/Lab/validation.zip) data. Then put the respective folders in the `/data` directory.


Once the notebook is up and running and the data is downloaded, you can follow the instructions in the notebook and fill out the required pieces of code marked by `TODOs`. It is important to take time and read the comments in the notebook. On top of following along with the classroom lessons for guidance on how to fill out the `TODOs` be sure to check the notebook for relevant information as well. By the end you will have your first basic implementation of the network needed to get the project running! 

It is important to note that some computer platforms (CPU-only) may take up to 3 hours to train the network, depending on a few factors. 

The recommended strategy for dealing with this problem is to complete the building out the notebook and debugging on your local system before moving to a faster system for the training portion.  Once your network is running correctly you can then launch your notebook from your AWS instance in order to speed up training times.  
