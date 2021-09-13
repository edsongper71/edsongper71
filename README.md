- 👋 Hi, I’m @edsongper71
Hello

I'm working to configure OTEL Collector for Splunk and Dynatrace. I'm trying to add the configuration on Config.YAML to retrieve the server hostname
using an ENV Variable like $HOSTNAME.

resource:
   attributes:
   - key: host.name
     action: insert
     value:  ${HOSTNAME}
     
     No errors to start the Agent.
     
     On Splunk side, the host is showing a blank: host:
     
     My idea is to have a generic configuration file to be distributed during the server provisioning.

<!---
edsongper71/edsongper71 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
