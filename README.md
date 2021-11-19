# ola-trigger-hue-api-v2-dmx
DMX-Hue API V2 - Open Lighting Architecture trigger config to control Philips Hue and other Zigbee lights with DMX (Art-Net, sACN or via DMX input)  
  
Coming soon....  
  
Working curl syntax for turning on:  

```curl --insecure --request PUT 'https://$HOSTNAME/clip/v2/resource/light/$LIGHT-ID' --header 'hue-application-key:$HUE-KEY' --header 'Content-Type: application/json' --data-raw '{"on":{"on":true}}'```  
  
  https://developers.meethue.com/new-hue-api/
