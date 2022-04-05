# Sales_Projections
The goal for this project is to use python to analyze features within a dataset and create regression models that can be used to predict sales in the future.
Our Data dictionary is as follows: 

Variable Name |	Description
Item_Identifier -	Unique product ID
Item_Weight -	Weight of product
Item_Fat_Content -	Whether the product is low fat or regular
Item_Visibility -	The percentage of total display area of all products in a store allocated to the particular product
Item_Type -	The category to which the product belongs
Item_MRP -	Maximum Retail Price (list price) of the product
Outlet_Identifier -	Unique store ID
Outlet_Establishment_Year -	The year in which store was established
Outlet_Size -	The size of the store in terms of ground area covered
Outlet_Location_Type -	The type of area in which the store is located
Outlet_Type -	Whether the outlet is a grocery store or some sort of supermarket
Item_Outlet_Sales -	Sales of the product in the particular store. This is the target variable to be predicted.

Fig. 1
![image](https://user-images.githubusercontent.com/98555801/161663984-a838c472-1385-4869-ac34-46276db75e53.png)
Fig. 2
![image](https://user-images.githubusercontent.com/98555801/161664328-a37938d7-5b17-4116-b150-35e5ef9f0212.png)
Fig. 3
![image](https://user-images.githubusercontent.com/98555801/161664353-f2eeeaab-8bf1-40d1-8878-9a06223f13ad.png)
Fig. 4
![image](https://user-images.githubusercontent.com/98555801/161664374-0de434f4-6c23-44bc-b114-b5dc366461bc.png)

In this analysis we use various figures to explore our data (above). Figure 1 is a barchart of total sales at each outlet. Figure 2 explores foodsales by fat content at outlets with the highest and lowest sales. Figure 3 explores the differences in item visibility at these outlets Finally, figure 4 shows the number of sales of each item type at each outlet of interest.

Lastly, we conclude this analysis with a comparison of regression models to determine which model is best suited for making predictions of data in the future. We begin with a simple linear regression model and compare it to a regression tree. Based on our data, we determine a regression tree is best suited to making predictions about new data in the future. 
