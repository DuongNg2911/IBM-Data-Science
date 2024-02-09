- Decision Trees:
  - Objective: Select attributes that more predictiveness/less impurity/ lower entropy
 
<img width="650" alt="Screenshot 2024-02-09 at 4 36 32 PM" src="https://github.com/DuongNg2911/IBM-Data-Science/assets/127082369/24b2c183-d237-47a3-91be-8a24ee6a8218">
  - Impurity of node = Entropy

<img width="639" alt="Screenshot 2024-02-09 at 4 39 56 PM" src="https://github.com/DuongNg2911/IBM-Data-Science/assets/127082369/16a201a2-137d-4a78-a225-5e9412068707">
  - Entropy: Measure of randomness or uncertainty
  - The lower the entropy, the less uniform the distribution, the purer the node 

<img width="647" alt="Screenshot 2024-02-09 at 4 43 28 PM" src="https://github.com/DuongNg2911/IBM-Data-Science/assets/127082369/f1d27e4a-bed9-4155-84c3-448f2f7e16a4">
  - After calculating entropy from each attribute, calculate information gain to select which attribute to split from
  - Select the tree with higher information gain after splitting

<img width="634" alt="Screenshot 2024-02-09 at 4 46 06 PM" src="https://github.com/DuongNg2911/IBM-Data-Science/assets/127082369/a3ade361-fd7c-4e0e-bbb2-3252becd355e">
  - Information gain is the information that can increase the level of certainty after splitting
  - The lower the entropy, the higher the information gain 
