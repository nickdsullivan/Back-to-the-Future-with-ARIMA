# Back to the Future with ARIMA
This project aims to use an ARIMA with both future and past values to fill in missing data.
For example, let's say your data was corrupted at random points in your time series data.   
If you just use a regular ARIMA model at predict at those points broken you will not be using what you know in the future.
All of the python packages I have seen have not been able to have both future and past values predict your arima model.  

The "order" of your model will not simply be q, d, p but q and p will take a range of values ex: [-1,1], 0, 0
X_t = B_0 * X_(t-1) + B_1 *  X_(t-1)



I am still wo
