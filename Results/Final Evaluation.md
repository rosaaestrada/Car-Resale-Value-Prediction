# Final Evaluation

### Can we predict the optimal selling price of a car?
* Yes - the models demonstrate good predictive power, especially **Random Forest** which achieved:
  * R² = 0.72, meaning it explains 72% of the variation in selling prices.
  * MAE ≈ 1.10, suggesting that predicted prices are on average within $1,100 of actual prices.
* This shows that the model can provide reasonably accurate pricing guidance, especially useful for dealerships, platforms, or sellers looking to set competitive yet fair prices.

<img src= "" alt= "" width= "" hieght= "">

### What factors influence resale value?
* Present price (original price of the car) — strongest predictor
* Year / Car Age — newer cars retain more value
* Kms Driven — contributes slightly
* Fuel type, seller type, and transmission — have a smaller but relevant impact
  * These findings suggest that resale value is primarily influenced by the car’s original cost, age, and usage, with brand and type also playing roles.

<img src= "" alt= "" width= "" hieght= "">
 
### Which brands hold their value best?
* Vitara Brezza retains ~94% of its original price — highest among all brands
* Motorcycles and scooters also perform very well:
  *  Bajaj Avenger, TVS Sport, UM Renegade Mojave, Activa 4G all retain 90%+ of value
* These high-performing brands indicate strong demand and slower depreciation, ideal for buyers prioritizing long-term value.

<img src= "" alt= "" width= "" hieght= "">

### Do automatic cars depreciate faster than manual ones?
* Yes
  *  Automatic cars lose on average 5.50
  *  Manual cars lose 2.57
* The boxplot confirms this — automatics have a higher median depreciation and more variability.
* Automatic cars depreciate more, likely due to higher upfront cost and lower resale demand in some markets.

<img src= "" alt= "" width= "" hieght= "">

### Does high mileage equal lower price?
* Surprisingly, not strongly in this dataset
  *  Correlation = 0.03, which means almost no linear relationship
  *  The scatterplot shows most cars under 100,000 km, limiting variability
  *  While there's a visual trend suggesting higher mileage might reduce price, it's not strong statistically
* Mileage alone isn’t a strong determinant — other factors like age, brand, and present price weigh more heavily.

<img src= "" alt= "" width= "" hieght= "">
