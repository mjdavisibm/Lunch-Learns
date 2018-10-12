# Lunch & Learns
Collection of Lunch and Learns that customers can follow

Pizza Ordering over the phone to a chatbot

This L&L uses the following IBM Services

1. Watson Assistant
2. Watson Speech to Text
3. Watson Text to Speech
4. Watson Voice Gateway


[![Deploy to IBM Cloud](https://bluemix.net/deploy/button.png)](https://bluemix.net/deploy?repository=https://github.com/mjdavisibm/Lunch-Learns&branch=master)
> If you want to know what this button does it's a lot. Get started with [IBMCloud Docs](https://console.bluemix.net/docs/services/ContinuousDelivery/deploy_button.html#button-examples)


##Notes

Setting up the deployment pipeline to create the appropriate services
* This should be added to the manifest.yml file
* use `$ ibmcloud cf marketplace |more`
** Note 1: This takes a long time and dumps a lot of services out, hence the more. You also might want to output it to a file
** Note 2: You may have to set up the end-point using `$ ibmcloud target --cf`. This is a interactive way to set up the endpoint
