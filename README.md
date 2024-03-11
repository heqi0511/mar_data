# mar_data

# fraud
Processed data is in fraud.csv. It has more than one column for predicting, listed below:
actions                       object
times                         object
execution_time                 int64
Amount                         int32
device_freq                  float64
ip_freq                      float64
beneficiary_freq             float64
application_freq             float64
is_fraud                       int64
Action time mean             float64
Action time std              float64
log(amount)                  float64
time_to_first_action         float64
actions_str                   object
total_time_to_transaction    float64

Here is_fraud is the binary variable indicating whether or not it is a fraud transaction.

