## Product recommendations for positive customers
1. Create project environment using command.
conda create -n bmc_new python==3.9 -y

2. Conda activate bmc_new

3. Create repository in github and provide the relevant name. Also create .gitignore and readme.md file while creating repository.
repository name is prod_recommendations

4. Install all the required packages by running requirement.txt file
pip install -r requirement.txt file

5. Create all the necessary files if required. eg. logging , exception handling, setup.py.

6. Create folder named 'src' and start writing codes for the project. Create sub folder named 'notebooks' and 
do the experiments with the projects.
7. Data analysis and insight is in the notebook folder - "Printer Related product recommendations_detail_analysis.ipynb"

8. Please note: I have created repositor and pushed all the changes to the github.
origin/bmc-project-2023.

9. Go to github - https://github.com/jjasmin123/prod_recommendations.git
Copy the link in your desired folder name using - cd https://github.com/jjasmin123/prod_recommendations.git.
Select branch name - origin/bmc-project-2023. You will see all the codes here.


10. Project description and steps.
a. data - provided data is in json format. Used online converter apps to convert this data into csv format.
b. Detail analysis of data is in the notebook - "Printer Related product recommendations_detail_analysis.ipynb"
c. Used "Collaborative Filtering" and "Item-based collaborative filtering" methods to recommend customers for the desired products and products to the desired customers respectively.
d. See the predictions or deployment of these methods are already present in the notebook - "Printer Related product recommendations_detail_analysis.ipynb"
