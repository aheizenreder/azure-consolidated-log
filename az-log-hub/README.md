This sub-project contains Terraform script to create a Azure Log Analytics Workspace. This Log Analytics Workspace instance simulates a central logging tartget.
To identify points to required RBAC assigments the scripts in this sub-project have to be executed with a user that has no access to application subscription.
The required subscriptions are created in an other project (az-create-subscriptions).
The dummy ressources generating log entries are created in separate sub-project (az-application).
