# portal-audit

Is a BASH script that will gather all JSON facts of physical and virtual systems
connected to the Red Hat Customer Portal.

The output generated has a system per file, name with the UUID of the system as
it is found in customer portal.

You'll need jq installed on the machine you're running the script on.

Simply edit the credentials file to your username, password and orgID (Found using subscription-manager identity)
