# Discount-Rate-Bootstrapping
A code to bootstrap discount rates from the US Treasury Bond price qoutes from Wall Street Journal website. The repository has three different methods to bootstrap the discount rate curve.
1. Using Regression: This provides an incomplete picture of the bootstrapped curve as there is missing T bond price data for dates between years 2030 and 2040
2. Using 15Y USD IR swap rate to fill in the gap of missing price data
3. Using data from STRIPs to fill in the gap of missing price data
