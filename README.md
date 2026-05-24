
### Problem Statement
Airbnb hosts struggle to set optimal prices. Pricing too high reduces bookings; too low leaves revenue on the table. This project uses machine learning to predict fair market prices based on listing characteristics.

### Why Multiple Linear Regression?
- **Interpretability:** Coefficients show how each feature affects price
- **Real-world relevance:** Pricing is naturally continuous
- **Course alignment:** MLR is a core topic in CSM354
- **Efficiency:** Trains quickly, suitable for moderate-sized data

### Key Questions to Answer
1. Which features most strongly influence Airbnb prices?
2. Can we predict prices within ±$20 of actual?
3. Are there interactions between features (e.g., neighborhood × room type)?

**Numerical Features:**
- `number_of_reviews`: Total reviews received (0-629)
- `reviews_per_month`: Monthly review rate (0-96)
- `availability_365`: Days available in next year (0-365)
- `minimum_nights`: Minimum stay required (1-1250 days)

**Categorical Features:**
- `room_type`: Entire home, Private room, Shared room
- `neighbourhood`: NYC boroughs (Manhattan, Brooklyn, etc.)
- `host_verified`: Whether host is verified



## CONCLUSIONS & COURSE OBJECTIVES

✓ **Examined MLR Techniques:**
- Successfully implemented SLR → MLR progression
- Understood feature scaling, standardization
- Verified MLR assumptions

✓ **Analyzed Evaluation Metrics:**
- Computed R², RMSE, MAE thoroughly
- Performed residual analysis
- Cross-validation to ensure generalization



###  Key Learnings

1. **Data Quality Matters:** 80% of project time was EDA + preprocessing
2. **Feature Engineering is an Art:** Created interaction features improved model
3. **Assumptions are Important:** Verified MLR assumptions through rigorous testing
4. **Evaluation is Multifaceted:** Can't rely on single metric (R² alone is insufficient)
5. **Generalization is Critical:** Test R² vs Train R² comparison revealed model stability
