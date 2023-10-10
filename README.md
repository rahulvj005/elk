# elk

$ProgressPreference = 'SilentlyContinue'
Invoke-WebRequest -Uri https://artifacts.elastic.co/downloads/beats/elastic-agent/elastic-agent-8.10.2-windows-x86_64.zip -OutFile elastic-agent-8.10.2-windows-x86_64.zip
Expand-Archive .\elastic-agent-8.10.2-windows-x86_64.zip -DestinationPath .
cd elastic-agent-8.10.2-windows-x86_64
.\elastic-agent.exe install --url=https://f4c7f6a9def947659e449a11a4648665.fleet.us-central1.gcp.cloud.es.io:443 --enrollment-token=a1llWEdJc0Jvd2N5cHZaaGVrcmc6UW1jay1wZnNSUEtaVVRSTUdmNXZ6dw==

deployment uname and pass - elastic and xoQBcmkBTdDkYrvI2MepbXaJ

Elastic account pass - YaM_MeR!@#$%^&*()

ELK link: https://attack-simulation.kb.us-central1.gcp.cloud.es.io:9243/app/home#/

CS link: https://falcon.us-2.crowdstrike.com/hosts/sensor-downloads

