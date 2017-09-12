# minemeld-analysis
Splunk application to check MineMeld logs sent via logstash connector

Splunk/MineMeld configuration is described in this post
 http://wp.me/p6LD4A-9f
 
Here a video of the app in action
 https://youtu.be/WJogETMlpcc

In order to have a working environment you need a custom TA to parse MineMeld JSON events 
 https://github.com/gmellini/TA-custom-minemeld_ioc

*IMPORTANT* Install the app in the Splunk Search Head (distributed environment) or Splunk single-istance
