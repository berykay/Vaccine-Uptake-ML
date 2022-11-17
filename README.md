## <p align="center">Machine Learning Project</p> 
This project is both a competition and a school project. In this project, I trained my data with different models. Before I start the links maybe you want to visit is below.
</br>
Used Language: Python
</br></br></br>
You can earn more details from the competition web address: https://www.drivendata.org/competitions/66/flu-shot-learning/ </br> 

<a href="https://www.drivendata.org/competitions/66/flu-shot-learning/"><img src="https://user-images.githubusercontent.com/74079494/202309852-f8d9ec79-6ab9-4731-9733-1be13edc5c33.png" width="450"></a>
 </br></br>

Also I have a 6 minute Turkish Youtube video to explaning what did I do. Youtube video: https://www.youtube.com/watch?v=iA6EOTKcBss </br>

<a href="https://www.youtube.com/watch?v=iA6EOTKcBss"><img src="https://user-images.githubusercontent.com/74079494/202311644-cdc7ce54-1820-4071-9d98-1e5013d5c38e.png" width="600"></a> 
</br></br>

## <p align="center"> Exploratory Data Analysis (EDA)</p> 
In my data, there were many Object Data type and null variables. So, I needed to make the data ready for training. </br></br>
<img src="https://user-images.githubusercontent.com/74079494/202315106-ed5b2d6e-8e5d-45e3-9fc6-bd3b88dff02a.png" height="550">
<img src="https://user-images.githubusercontent.com/74079494/202316378-6d4b3d6f-dfe9-4cbf-ada8-af2a798c6691.png" height="550">
</br></br>
For converting object data type to usable data type (numeric data type), I have tried 3 method. 
</br>
<ol type="1">
 <li>Label Encoding: In label encoding in Python, we replace the categorical value with a numeric value between 0 and the number of classes minus 1. If the categorical variable value contains 5 distinct classes, we use (0, 1, 2, 3, and 4).</li>
 <li>One-Hot Encoding: One-hot encoding can be applied to the integer representation. This is where the integer encoded variable is removed and a new binary variable is added for each unique integer value.</li>
 <li>Both Label Encoding and One-Hot Encoding: I tried to separate group by group. However, it does not work well</li>
 </ol>
 </br>
 <ol>
The best solution for me was the 1st one. 
</ol>
</br>
I normalized data for better results and also for fast training. I also deleted some features because of the null-non_null ratio.




</br></br>
## <p align="center">Models That I Used</p> 
<ul> 
 <li>SVM</li> 
 
 ![image](https://user-images.githubusercontent.com/74079494/202320632-ec2cc05e-724d-4aa1-925c-1ac4f9f89e4b.png)
 
 </br>
 <li>Logistic regression</li>

  ![image](https://user-images.githubusercontent.com/74079494/202321034-f1fc8a46-f34b-4ac5-b80f-3de13cf5f071.png)

</br>
 <li>XGBoost</li>
 
 ![image](https://user-images.githubusercontent.com/74079494/202321759-563bf34f-dcff-4a47-be38-c69ba0b2cc70.png)

</br>
 <li>LightGBM</li>
 
 ![image](https://user-images.githubusercontent.com/74079494/202321840-96387184-80fd-4659-85ea-b1834264a978.png)

 
 </br>
 <li> Multi-Layer Perceptron (MLP)</li>
 
 ![image](https://user-images.githubusercontent.com/74079494/202321907-56a068a1-c8ca-4fd0-a648-b927afa0e50c.png)
 </br>
 
</ul>
 
## <p align="center">Last Words</p> 
 This project was my first machine learning project. So, I have been aware of some mistakes after I worked on different machine learning projects. For example, I used MLP but probably did not find the best parameters, or I just deleted some features, but I would try something for them before deleting them, etc. Whatever happens, I have learned many things. I hope I will learn and progress on this path.
 
## <p align="center">References</p> 
<ol>
 <li>https://www.mygreatlearning.com/blog/label-encoding-in-python/</li>
 <li>https://medium.com/deep-learning-turkiye/nedir-bu-destek-vektör-makineleri-makine-öğrenmesi-serisi-2-94e576e4223e </li>
 <li>https://veribilimcisi.com/2017/07/18/lojistik-regresyon/</li>
 <li>https://machinelearningmastery.com/how-to-one-hot-encode-sequence-data-in-python/ </li>
 <li>https://www.geeksforgeeks.org/ml-one-hot-encoding-of-datasets-in-python/</li>
 <li>https://analyticsindiamag.com/5-ways-handle-missing-values-machine-learning-datasets/</li>
 <li>https://www.veribilimiokulu.com/xgboost-nasil-calisir/</li>
 <li>https://machinelearninggeek.com/multi-layer-perceptron-neural-network-using-python/</li>
 <li>https://www.kaggle.com/code/prashant111/lightgbm-classifier-in-python/notebook</li> 
 <li>https://machinelearningmastery.com/why-one-hot-encode-data-in-machine-learning/</li>
</ol>
 
