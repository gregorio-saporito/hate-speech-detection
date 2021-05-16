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
