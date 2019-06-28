# BachelorProjectIMM
Thesis Python script substitution.
Datasets have been created in Microsoft Excel and hereafter converted to CSV extension. The data is separated by a comma and saved in UTF-8 configuration. 
The script is developed in the programming language Python. The program Jupyter Notebook is used in which a Notebook file is created.

Two data frames are being created by naming them respectively, df1 and df2. Furthermore, all the NONE values filtered in df1 because there are 17 ingredients of which the protein value is unknown. Mainly because these are foreign or exotic products of which there is no info.
In het function removeNone all the NONE values are being filtered. Hereafter is copy made of the original file because the original recipe also needs to exist. With the copy file, the protein value is linked to al the substitutes. This happens in the first for-loop after the file copy is being made. Then the protein values will be compared with each other and het highest value will be taken, also known as max_value in het script. The ingredient with the highest value replaces the original ingredient and the recipe is printed. Lastly, there is a calculation of the total protein value of the recipe. This ease analyzing the increase between the recipes. 

In het function removeNone all the NONE values are being filtered. Hereafter is copy made of the original file because the original recipe also needs to exist. With the copy file, the protein value is linked to al the substitutes. This happens in the first for-loop after the file copy is being made. Then the protein values will be compared with each other and het highest value will be taken, also known as max_value in het script. The ingredient with the highest value                                    
replaces the original ingredient and the recipe is printed. Lastly, there is a calculation of the total protein value of the recipe. This ease analyzing the increase between the recipes. 

Link of online survey can be found here:https://www.survio.com/survey/d/X9T8I0Q8L1B9Q2G9V
