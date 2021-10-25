### Data:

Bankrupt data 

The data is very Unbalanced
    - 220 out of 6819 were bankrupted
    - 6599 out of 6819 were not bankrupted
![data](https://user-images.githubusercontent.com/57165743/138775699-d42b005c-101c-47bb-b295-f5703f594fe8.png)

### Preprocessing
1 Used Cor_martrix & VIF  to identify Multicollinearity and remove som features 
2. Scaling some features:  the given data are mostly ratios and shall fall between 0-1
The data outside of this range shall be outlier ? 
I include them and do min-max scaling, since some of the include bankrupted companies  

<img width="499" alt="outlier" src="https://user-images.githubusercontent.com/57165743/138776086-9cedae0e-bddd-4f80-9a4c-7df0f6c4503c.png">


### diff model comparison: 
tried diff models to run the data, but the F1 score remain pretty low

<img width="263" alt="MVP_res" src="https://user-images.githubusercontent.com/57165743/138776314-5492e1cd-5e5d-4037-b835-e93b729ed20a.png">


### Feature work 

- Try bagging or bootstrapping on the model
- continue trying & reducing the number of features (through VIF) to make it more interpretable and able to apply to different data (S&P500)
  - currently : 69 features
