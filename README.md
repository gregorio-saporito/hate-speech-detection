# hate-speech-detection

### Task
Hate speech detection plays a pivotal role in preventing the uncontrolled spread of hate online. The aim of this project is to:
- build a classifier capable of discerning among comments considered hateful, offensive, or neither of the two
- identify relevant terminology associated with each class

The intrinsic complexities of natural language processing make this task arduous. This is particularly true when it comes to distinguishing between hateful versus offensive content since their boundaries are hard to define quantitatively.

### Data
The data was retrieved from Davidson et al. (2017) and it can be downloaded from their [repository](https://github.com/t-davidson/hate-speech-and-offensive-language). The dataset contains roughly 25k tweets extracted throught the Twitter API containing posts considered by internet users as hateful. These posts were manually labelled by  CrowdFlower (CF) workers into three categories:
- 0 for hate speech
- 1 for offensive content
- 2 for tweets not falling into the previous categories

### Code and Reproducibility
The solution is written with Python 3 in Google Colab for easier reproducibility of the results. The link to run the code can be found by clicking on the main.ipynb file of this Github repository where there will be a button directing the user to Colab. Once connected to the "Python 3 Google Compute Engine backend" it will be sufficient to upload the labeled_data.csv file in the dedicated section of the notebook.

![alt text](https://github.com/gregorio-saporito/hate-speech-detection/blob/main/plots/Capture.PNG)
