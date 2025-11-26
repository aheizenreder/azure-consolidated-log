This sub-project contains Terraform script to create sample ressources. This ressources are configured for logging in an Azure Log Analytics Workspace in the same supsrciption and in a separate Log Analytics Workspace in a separate subscription.
To identify points to required RBAC assigments the scripts in this sub-project have to be executed with a user that has no access to log hub subscription.
The required subscriptions are created in an other project (az-create-subscriptions).
The Log Analytics Workspace in log hub subscription is created in separate sub-project (az-log-hub).
