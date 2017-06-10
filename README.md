# Side-Projects
- Sched-Macbook
  - An automated Ebay API script I made to help purchase a Macbook Pro. Used Ebay, Twilio APIs to ping Ebay every 20 seconds to text me new listings based on set of criteria (sub $750, buy it now = true, and 15" 16gb Macbook Pro)
  - This experiment worked but ultimately failed (in a spectacular way). I'm currently using a souped up Macbook 2011
  - There is a corresponding Medium article about what happened:
    - https://medium.com/@xbno/self-selecting-a-scam-e24631a7852a
- pytrends-simple
  - Modification on the existing pytrends API for google trends. Layers multiple functions to provide ability to:
    - Avoid google trend's limitation of pulling only day resolution trend data for short time periods. It pulls multiple chunks in succession and scaled the chunks based on a 'low resolution' (weeks or months) of trends data
    - Allow Ability to search for rising/top keywords per location based on DMA/state/counry locations.
- Hue
  - Hue is a few functions I wrote based on the phue module.
  - Goal: to modify my Philips hue to change color according to the outside temperature using a weather API
