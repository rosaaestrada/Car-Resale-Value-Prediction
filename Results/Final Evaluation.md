# Final Evaluation

### Can we predict the optimal selling price of a car?
* Yes - the models demonstrate good predictive power, especially **Random Forest** which achieved:
  * R² = 0.72, meaning it explains 72% of the variation in selling prices.
  * MAE ≈ 1.10, suggesting that predicted prices are on average within $1,100 of actual prices.
* This shows that the model can provide reasonably accurate pricing guidance, especially useful for dealerships, platforms, or sellers looking to set competitive yet fair prices.

<img src= "https://github.com/rosaaestrada/Car-Resale-Value-Prediction/blob/main/Results/Images/Actual%20vs.%20Predicted%20Selling%20Price%20(Random%20Forest).png?raw=true" alt= "" width= "" hieght= "">

### What factors influence resale value?
* Present price (original price of the car) — strongest predictor
* Year / Car Age — newer cars retain more value
* Kms Driven — contributes slightly
* Fuel type, seller type, and transmission — have a smaller but relevant impact
  * These findings suggest that resale value is primarily influenced by the car’s original cost, age, and usage, with brand and type also playing roles.

<img src= "https://github.com/rosaaestrada/Car-Resale-Value-Prediction/blob/main/Results/Images/Feature%20Importance%20(Random%20Forest).png?raw=true" alt= "" width= "" hieght= "">
 
### Which brands hold their value best?
* Vitara Brezza retains ~94% of its original price — highest among all brands
* Motorcycles and scooters also perform very well:
  *  Bajaj Avenger, TVS Sport, UM Renegade Mojave, Activa 4G all retain 90%+ of value
* These high-performing brands indicate strong demand and slower depreciation, ideal for buyers prioritizing long-term value.

| Car Name                 | Present Price | Selling Price | Value Retained % |
|--------------------------|---------------|---------------|------------------|
| vitara brezza            |	9.83         | 9.250	       | 94.099695          |
| bajaj avenger 150        |	0.80	       | 0.750	       | 93.750000           |
| um renegade mojave       |	1.82	       | 1.700	       | 93.406593           |
| tvs sport                |	0.52	       | 0.480	       | 92.307692           |
| yamaha fz 16             |	0.82	       | 0.750	       | 91.463415           |
| honda activa 4g          |	0.51	       | 0.465	       | 91.176471           |
| hero passion x pro       |	0.55	       | 0.500	       | 90.909091           |
| bajaj dominar 400        |	1.60	       | 1.450	       | 90.625000           |
| royal enfield bullet 350 |	1.17	       | 1.050	       | 89.743590           |
| honda dream yuga         |	0.54	       | 0.480	       | 88.888889           |

### Do automatic cars depreciate faster than manual ones?
* Yes
  *  Automatic cars lose on average 5.50
  *  Manual cars lose 2.57
* The boxplot confirms this — automatics have a higher median depreciation and more variability.
* Automatic cars depreciate more, likely due to higher upfront cost and lower resale demand in some markets.

<img src= "https://github.com/rosaaestrada/Car-Resale-Value-Prediction/blob/main/Results/Images/Box%20Plot%20Depreciation%20Comparison.png?raw=true" alt= "" width= "" hieght= "">

### Does high mileage equal lower price?
* Surprisingly, not strongly in this dataset
  *  Correlation = 0.03, which means almost no linear relationship
  *  The scatterplot shows most cars under 100,000 km, limiting variability
  *  While there's a visual trend suggesting higher mileage might reduce price, it's not strong statistically
* Mileage alone isn’t a strong determinant — other factors like age, brand, and present price weigh more heavily.

<img src= "https://github.com/rosaaestrada/Car-Resale-Value-Prediction/blob/main/Results/Images/Relationship%20Between%20Mileage%20and%20Selling%20Price.png?raw=true" alt= "" width= "" hieght= "">
