Dataset description
Cement (cement) -- quantitative -- kg in a m3 mixture -- Input Variable
Blast Furnace Slag (slag) -- quantitative -- kg in a m3 mixture -- Input Variable
Fly Ash (ash) -- quantitative -- kg in a m3 mixture -- Input Variable
Water (water) -- quantitative -- kg in a m3 mixture -- Input Variable
Superplasticizer (superplastic) -- quantitative -- kg in a m3 mixture -- Input Variable
Coarse Aggregate (coarseagg) -- quantitative -- kg in a m3 mixture -- Input Variable
Fine Aggregate (fineagg) -- quantitative -- kg in a m3 mixture -- Input Variable
Age(age) -- quantitative -- Day (1~365) -- Input Variable
Concrete compressive strength(strength) -- quantitative -- MPa -- Output Variable

Steps involved:
Import the library
First look at the data
Exploratory data analysis
3.1. IQR and ouliers analysis (box plot)
3.2. Distribution of independent variables
3.3. Pair plots
3.4. Heat map analysis
4. Model Building using
4.1 Linear regression
4.2 lasso,Ridge,Elastic net regression
4.3 decision tree regressor
4.4 svr
4.5 Randomforest regressor
4.6 xgboost


hypertuning the parameters of the models and used ensemble technique- stacking to combine multiple models for the better results and also reduced root_mean_square_error

