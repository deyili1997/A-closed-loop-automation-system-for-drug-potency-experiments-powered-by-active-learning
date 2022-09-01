# 02762_Final_Project: An Autonomous Robotic Platform Driven by an Active Learning Algorithm to Predict Drug Combinations Potency

Matthew Mo, Eric Li, Brittany Gomez

In this experiment, automation and active learning are leveraged together to streamline possible drug combinations that could be useful against cancer cells. The experimental model is based on a combination matrix that can screen much larger amounts of drug concentrations never seen before.1 It is a high throughput method that explores over 20,000 different drug concentration combinations.

Three potential anti-cancer drugs were used in tandem with metformin. Griseofulvin, an antifungal agent, shown to induce G2/M cell cycle arrest and apoptosis in HeLa cells.2 Camptothecin is an anti-cancer drug known to cause apoptosis in HeLa cells, more specifically through caspases and serine proteases.3 Chloramphenicol, is a broad spectrum antibiotic shown to partially work through caspase apoptosis.4 Although metformin is non-toxic and is commonly used by a variety of people for dietary and health reasons, there is evidence that it can act synergistically with an anti-cancer drug.5

Active learning has been making waves recently with a slew of scientists using it.6 This has become the case due to it being able to deliver conclusions with less experiments, equaling less time and money. In this study, query-by-committee coupled with deep learning, Random Forest Regressor and Gaussian regression coupled with maximizing expected improvement (MEI) were explored in the simulation. Random Forest Regressor coupled with MEI was chosen to guide the experiment. 

Content of this repo:
1. Design folder is the ideas and experimental configuration prior to the physical run of the experiments
2. Simulation data preparation folder is for preparing data to run active learning simulation 
3. 1st_round folder is for initialization (training) data and validation data
4. 2ns_round folderis only for training data
5. Accuracy folder is for the validation of the trained model
