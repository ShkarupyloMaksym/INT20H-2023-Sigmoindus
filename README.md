# Correlation Results


## Event name to Subscription cancel

### Highest correlation
| Event name | Correlation |
|--|--|
| Chat Conversation Opened |  0.731 |
|Wallet Opened|0.559
|Account History Transaction Details|0.463|
|Transaction Refund| 0.219

### Lowest correlation
| Event name | Correlation |
|--|--|
| Add Payment Method Success |  -0.532 |
|Sign Up Success|-0.467
|Add Vehicle Success|-0.451|


## User state to Subscription cancel
### Highest correlation
| State | Correlation |
|--|--|
| FL |  0.063 |
|CA| 0.060
|IL| 0.048

### Lowest correlation
| State | Correlation |
|--|--|
| NY | -0.037 |
|WI| -0.024
| CT | -0.024 |

## Event platform to Subscription cancel
| Platform | Correlation |
|--|--|
| ios | 0.065 |
|android| 0.060

## Device manufacture to Subscription cancel
### Highest correlation
| Device | Correlation |
|--|--|
| samsung | 0.069 |
|Apple| 0.065
### Lowest correlation
| Device | Correlation |
|--|--|
| Wingtech | -0.028 |
|TCL| -0.028

## Event attributes to Subscription cancel


### -  Account History Transaction Details

| 'Attribute name': {Value} | Correlation | 
|--|--|
|'Type' :{'Auto Payment'}|0.322
-- -
### - Account Setup Skip

| 'Attribute name': {Value} | Correlation | 
|--|--|
|'Screen' :{'Address Details'}|0.365
-- -
### - Add Payment Method Failed

| 'Attribute name': {Value} | Correlation | 
|--|--|
|'Tokenized Pay' :{'Google Pay'}|0.398
-- -
### - Add Payment Method Success

| 'Attribute name': {Value} | Correlation | 
|--|--|
|'Tokenized Pay' :{'Google Pay'}|0.088
|'Tokenized Pay' :{'Apple Pay'}|-0.038
|'Payment Method':{'PayPal'}|-0.036
-- -
### - Add Vehicle Break

| 'Attribute name': {Value} | Correlation | 
|--|--|
|'Error Code' :{'ERROR-NaN10'}|-0.05

-- -
### - Add Vehicle Success

| 'Attribute name': {Value} | Correlation | 
|--|--|
|'Color' :{'White'}|-0.043
|'Model' :{'xB'}|0.499
|'Model' :{'Excursion'}|0.499
|'Make' :{'Scion'}|0.499
-- -
### - Calculator Used

| 'Attribute name': {Value} | Correlation | 
|--|--|
|'Selected Route Type':{'One'}|1
|'Google Map Installed' :{'false'}|1
-- -
### - Chat Conversation Opened

| 'Attribute name': {Value} | Correlation | 
|--|--|
|'From':{'Menu'}|  0.093
|'From':{'Transaction Details'}|0.073
|'Transaction Type':{'AutoPayment'}|0.051
-- -
### - Order

| 'Attribute name': {Value} | Correlation | 
|--|--|
|'Premium Membership':{'True'}|  1

-- -
### - Sign Out

| 'Attribute name': {Value} | Correlation | 
|--|--|
|'Type':{'Manual'}|  0.886
-- -
### - Transaction Refund

| 'Attribute name': {Value} | Correlation | 
|--|--|
|'Id':{'2d795a386ea1e02252e543886b812a9b'}|    0.208
|'Id':{'cbf30aa0674eb25b54c37bed044f220b'}|    0.208
