# Import Other Assets w/ Custom Fields

The following scripts are provided by Samanage as examples and training purposes only and not designed to work in every use case without some modification to the script itself. These scripts are not supported by Samanage as part of your Samanage Master Subscription Agreement, however if you would like this script customized to support your use case, please contact us at api.scripts@samanage.com.

## Overview

This simple script imports other_asset into Samanage based on a CSV data source.
Each row of the CSV will create a new Other Asset to Samanage as an JSON object based on the [template](https://www.samanage.com/api/other_assets.html).
In this example, each row has columns which are selected by `row["Column Name"]`.

To run the script simply enter:

`ruby import_other_assets.rb API_TOKEN other_assets.csv` or for the eu datacenter: `ruby import_other_assets.rb API_TOKEN other_assets.csv eu`