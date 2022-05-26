### ELK Stack based on file logs.

# Filebeat

- Filebeat collect all the logs from the log files which we declared and will send those to the elastic search.
- Elastic search will send the logs to kibana to display.
- Filebeat should be placed in the api server. While elastic search & kibana can be on different servers.
- On Filebeat.config.yml file we need to specify
    - path to log files
    - elastic search url
    - kibana url

