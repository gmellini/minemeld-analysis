# minemeld-analysis
Splunk application to check MineMeld logs sent via logstash connector

Splunk/MineMeld configuration is described in this post
 http://wp.me/p6LD4A-9f
 
Here a video of the app in action
 https://youtu.be/WJogETMlpcc

In order to have a working environment you need a custom TA (TA-custom-minemeld-ioc) to parse MineMeld JSON events 
 https://github.com/gmellini/TA-custom-minemeld_ioc
 
The application check MineMeld events on index *minemeld_ioc*. If you want to change index name you have to adjust TA-custom-minemeld-ioc TA.

*IMPORTANT* Install the app in the Splunk Search Head (distributed environment) or Splunk single-istance
