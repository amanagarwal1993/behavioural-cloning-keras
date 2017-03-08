# Project: Behavioural Cloning
This is the third project in Udacity's [Self Driving Car Nanodegree Program](http://udacity.com/drive). In this project I trained a car in a simulator to learn how to drive on its own, making steering decisions based on camera images.

**Detailed report can be seen [here](writeup_report.md).**

### How the project is organized
Overview of the different files submitted in the project
1. **`model.py`**: The primary python file which houses all the code to pre-process images, create the Keras model and train the model. You don't need to run this file.
2. **`aws-model-final.ipynb`**: A Jupyter notebook which houses the same code as the model.py file.
3. **`model-tiny3.h5`**: Never mind the weird name. It's the saved, trained model.
4. **`drive.py`**: A python file which connects your saved model to the car simulator.
5. **`writeup_report.md`**: A report summarizing the results etc.

To run the project, open the simulator and the command line on your computer. Type the following:
```
python drive.py model-tiny3.h5
```
Then open the simulator and turn on the *Autonomous Mode*.

## License
[GNU General Public License](http://choosealicense.com/licenses/gpl-3.0/#)
