# DECISION-TREE-IMPLEMENTATION

**COMPANY**: CODETECH IT SOLUTIONS

**NAME**: DEVARASETTY SRI RANGA CHANDANA NAIDU

**INTERN ID**: CT06DF182

**DOMAIN**: MACHINE LEARNING

**BATCH DURATION**: May 24th, 2025 to July 9th, 2025

**MENTOR NAME**: NEELA SANTHOSH KUMAR

PROJECT DESCRIPTION:

This project is about the implementation of the Decision Tree, which is a popular supervised learning method used for classification issues in machine learning. Decision trees are simple and easy to interpret and are the basis of more complex ensemble methods such as Random Forests. The initial aim of this project was to comprehend the theoretical concepts behind decision trees
and then apply that knowledge into an executable implementation using Python.
We builds a decision tree recursively choosing the attribute that maximizes information gain at each node. Information gain is computed in terms of entropy, which is a measure of impurity or randomness in the data set. By reducing entropy, the algorithm in effect divides the data into progressively purer subsets and ends up with a tree structure with each path from the root to a leaf node denoting a classification rule.
The implementation consists of the following steps:

Data Handling: The data is kept as a list of dictionaries, with each dictionary being an example mapping attribute names to their respective values.

Entropy Calculation: A function is defined to calculate the entropy of a group of examples as a function of class label distribution.

Information Gain: For every attribute, the amount of reduction in entropy (information gain) is determined and the attribute which gives the largest gain is selected for partitioning.

Recursive Tree Construction: The set is divided according to the chosen attribute and the procedure is recursively repeated for each subset until one of the stopping criteria is fulfilled—like all examples belonging to the same class label, or no remaining attributes.

Prediction & Tree Traversal: After construction, the tree may be employed to classify novel examples through the traversal of the tree from the root according to the attribute values in the example.

Resources Used
To learn and develop this project, a range of learning resources were used:

YouTube Tutorials
YouTube proved to be an important resource, with visual and intuitive descriptions of decision trees. Channels like StatQuest with Josh Starmer, Simplilearn, and Codebasics presented great tutorials on the theory as well as the hands-on coding of the ID3 algorithm. These videos facilitated the explanation of intricate mathematical concepts such as entropy and information gain through simple examples, many with real-world analogies.

Learning with videos really helped with the clarity of concepts, particularly with visualizing decision trees splitting data with every level. A few videos also showed how to manually construct decision trees and verify the outcomes with the automated approaches such as scikit-learn, which was helpful for checking the hand-coded implementation.

AI-Powered Tools (e.g., ChatGPT,copilot,gemini)
To supplement learning on YouTube, AI-assisted tools such as ChatGPT were utilized to get better insights, clear any uncertainties, and debug the implementation. They were especially useful in:

Converting pseudocode into functional Python code.

Suggesting improvements in optimizing or expanding the project (e.g., incorporating pruning or varying the splitting criteria).

Developing test datasets and checking the accuracy of the decision tree.

This AI assistance was like having a personal tutor at hand 24/7, filling the gap between theory learning and actual coding.

Other Online Sources
Different articles and documentation provided by websites such as GeeksforGeeks, Towards Data Science, and Scikit-learn were consulted for different methods and to cross-check implementations. These sources provided different insights and assisted in the enhancement of code robustness.

#OUTPUT OF THE TASK

<img width="1710" alt="Image" src="https://github.com/user-attachments/assets/2a21a648-ec46-4812-873a-8dc512024f4b" />









