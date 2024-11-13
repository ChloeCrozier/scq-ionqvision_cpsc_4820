## Quantum Machine Learning Project
# Intro 
This assignment is an altered version of the IonQ challege at the SCQuantathonv1 quantum hackathon. 

In this assignment, you will be experimenting with a quantum machine learning module. This assignment should help you become more comfortable with encoders, ansatz, and machine learning models. 

# Setup
1. Click the link at the end of this README to open this github repo in qBraid lab. Alternatively, open the qBraid lab, click `git` on the left-side toolbar, click `clone a repository`, and paste `https://github.com/njones93531/SCQ-ionqvision.git`. You should now have access to the folder `SCQ-ionqvision`, where the rest of the assignment will take place.
2. Open `SCQ_IonQ_Challenge.ipynb`. This file contains the code you will run to test your machine learning model. It also contains a lot of helpful information. Please read over this file. 
3. Go to the `Environments` tab on the right-side toolbar, and click `Add`. Type `ionq` into the search bar. You should see an environment titled `IonQ Vision Challenge`. Select and install that environment. 
4. In `SCQ_IonQ_Challenge.ipynb`, click in the top-right corner where it says `Python3 [Default]` to change the kernel. You should change it to `Python3 [ionq-vision]`. 
5. Open `ansatz_library_custom.py`. This is the file you will edit for this assignment. 


# Objectives
In this assignment, you will be running the jupyter notebook `SQC_IonQ_Challenge.ipynb`. You do not need to edit this file, you only need to run it to see your results. 

You *will* need to edit `ansatz_library_custom.py`. In this file, there are sections marked out by comments for you to edit. 

Objective 1: Run the model using the default ansatz and encoder (no change). Analyze the performance. 

Objective 2: Edit the class CustomEncoder in `ansatz_library_custom.py`. Try to achieve a higher classification accuracy with your new encoder. You can visualize your encoder by rerunning the cell in `SCQ_IonQ_Challenge.ipynb` that draws your encoder circuit. Explain what you changed, how the accuracy changed, and why you think the model behaved differently.

Objective 3: Edit the class CustomAnsatz in `ansatz_library_custom.py`. Try to achieve a higher classification accuracy with your new ansatz. You can visualize your ansatz by rerunning the cell in `SCQ_IonQ_Challenge.ipynb` that draws your ansatz circuit. Explain what you changed, how the accuracy changed, and why you think the model behaved differently.

You may need to explicitly save `ansatz_library_custom.py` before the changes will become visible to `SCQ_IonQ_Challenge.ipynb`. You should not need to change `SCQ_IonQ_Challenge.ipynb`. You should only need to make changes to `ansatz_library_custom.py`. 

# Submission
You will need to submit three files for this assignment. 
1. Submit a written file that contains your answers for each of the objectives. 
2. Download and submit your `SCQ_IonQ_Challenge.ipynb` after running it the final time. While you should not edit the file, the version you submit will contain all the output you recieved after your changes to `ansatz_library_custom.py`.
3. Download and submit your `ansatz_library_custom.py`. 

# Open in qBraid
[<img src="https://qbraid-static.s3.amazonaws.com/logos/Launch_on_qBraid_white.png" width="150">](https://account.qbraid.com?gitHubUrl=https://github.com/njones93531/SCQ-ionqvision)
