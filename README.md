# sensu-files
Contains various files used by sensu server & clients, including
check scripts
handlers
etc...

These files get extract to /etc/sensu on the Sensu server and any Sensu clients. To implement them, you need to update the sensu check definitions in hiera.

##NOTES
Before adding anything to this repo, check the requirements and add them to the puppet manifests.
