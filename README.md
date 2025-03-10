# CLGA-dataset
```plaintext
dataset/
├── assignment_2d/
│   ├── prob_{0..20}
│       ├──description.txt
│       ├── code_example.py
│       ├── sample.json 
├── assignment_3d/
│   ├── prob_{0..20}
│       ├──description.txt
│       ├── code_example.py
│       ├── sample.json 
```
The dataset is divided into 2D and 3D. In each dataset, ```description.txt``` contains the problem description, aiming to introduce the parameters, constraints, and optimization objectives in the assignment problem. ```code_example.py``` is a sample code, hoping that the large model will output code in this format for direct execution. ```sample.json``` is a set of sample inputs and outputs based on the code, used to verify whether the code is correct.