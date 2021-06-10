# Data-Science-Hackathon-2017

### Team
NLPAin team won 5th place out of 20 at the EPAM Data Science Hackathon in Saint Petersburg in 2017.

Participants: 
* Egor Malykh
* Anastasia Avdeeva
* Maxim Tischuk
* Anna Anisimova
* Kuchkarov Ildus 

### Task definition

1. Find questions similar to the one entered by the user
2. Show a short summary of the answers to these questions and the tags that match them

### Data - STACK OVERFLOW
1. Randomly selected 2% of all available questions (289122 questions)
2. All answers to the selected questions were added (451429 replies)
3. All comments for the selected questions and answers were added (617492 comments)

![tags timeline](https://user-images.githubusercontent.com/82182857/121495199-18280580-c9e2-11eb-8082-52178dee99b0.jpg)

![tags_graph](https://user-images.githubusercontent.com/82182857/121495367-3d1c7880-c9e2-11eb-824f-a55a6c987a7d.png){:height="50%" width="50%"}

### Solution
1. TF-IDF + PCA + HNSW for a quick search for similar questions
2. TextRank for summarization
3. Heuristics based on data analysis

### Demo
![demo](https://user-images.githubusercontent.com/82182857/121495489-53c2cf80-c9e2-11eb-8158-f07ec7519572.png =607x450)
<demo src="https://user-images.githubusercontent.com/82182857/121495489-53c2cf80-c9e2-11eb-8158-f07ec7519572.png" width="450" height="607">









