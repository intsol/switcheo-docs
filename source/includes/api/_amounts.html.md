# Amounts

Some endpoints (Eg. create order) will require you to specify asset amounts as url parameters (Eg. `offer_asset_amount`).
An amount should be specified up to the precision allowed by the given token, and the decimal point itself should be dropped.
