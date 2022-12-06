# rolegrants

Code to automate granting / revoking access to users in database for multiple hosts

- clean code with easy understanding to add future requests

- host level variables are declared which can be filtered by {{ inventory_hostname }} and can run for multiple databases and schemas.

- won't run on existing access of users 

- check for user existing and create it on the flow




# next ideas :

each user have separate tasks having tags with names in below user list

"postgres"

"kpi_service"

"qa_kpi_service" 

"ad_spend_app" 

"cost_aggregator" 

"abuilder" 

"monitoring" 

"segmentation_lookup" 

"segmentation_lookup_ab2"

"support"

