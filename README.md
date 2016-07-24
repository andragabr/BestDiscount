# BestDiscount
IOT Instant Promo in your outlet - BestDiscount --- FUNDING NEEDED!!!

## What is BestDiscount?
You have your own small business, like a restaurant or you are the marketing responsible of a chain like KMart or Carrfour, and you want to have instant promotions in your outlet, every day a different promotion, and you may decide on the spot what products are subject of your promo and may start and stop anytime. If you ever dreamd about such a system and you payd already a fortune on existing promo campaigns then we suggest it is time to stop and have a look at our BestDiscount solution.  

Use case 1. Small business, one outlet
- you decide that you want to boost sales for a specific item, let's say fresh fruits - bananas, in your store today, and also want to associate that with a small guarenteed quick win instant loterry, let's say you give one chocolate free for each customer that buys 2kg (about 4 1/2 lb) of bananas. No printouts or leaflets, no agency involved, no extra personnel, just with your mobile phone.
- you enter the bar code of bananas, the instant promo bar code and chocolate bar code. Type in a text of 200 characters. It's like a tweet or a post on social media(Facebook, Google+ etc). You upload that on the device present in your store and here you are. You promo is a ctive starting as now!
- you want to stop the promo, just uncheck the "Active promo" box and the promo stop as now!

Use case 2. Medium-big business, several outlets distributed over a wide geographic area (city, county, state)
- you have a web application where you create the promo campaing. Here you may involve a 3rd party for creating visual or just your internal marketing department. Select items to be part of the promo, the start-end date and specific outlets where you want to push the promo.
- each store manager will receive a notification on their mobile phone about the promo. They will have to synchronize the promo with the device present in their store. You may allow them to modify the promo according to stock availability and other criteria.
- the promo is available to customers in the store

There is another part that was not described here - your customers may install an application on their phones allowing them to receive announcement about the newly created promos, only if they are willing to receive the push notification, no forced and undesired publicity. The application may be used directly in the store when they checkout.

How does the customer benefit from BestDiscount - 1st benefit is that they will get instant bonification just for being present in the store. One wise manager will stimulate customers to buy from its strore once she knows that the clients are there. The promo is displayed on a touch screen available in the store. The client may choose one the promos and get a bar code print from a thermal printer - that cupon will be used when chacking out. The same type of interaction may be available on customer's mobile phone application.

There are endless possiblities and variations for promotions: happy hour, instant loterry, flash mob game, pokemon hunt like promos inside the store etc.

##Technical solution
The system has a series of components and it depends on the store owner or the retail chain which combination to implement.
Hardware: 
- Thremal printer  
  - Pipsta with built in NFC: http://www.pipsta.co.uk/
  - Adafruit https://learn.adafruit.com/pi-thermal-printer;
- IOT board  
  - RaspberryPi Model3 B: https://www.raspberrypi.org/products/raspberry-pi-3-model-b/
  - NanoPi2 Fire http://www.nanopi.org/NanoPi-2-Fire_Feature.html
  - Linkit One http://labs.mediatek.com/site/global/developer_tools/mediatek_linkit/whatis_linkit_one/index.gsp
  - C.H.I.P https://getchip.com/
  - Nordic Semiconductor nRF52DK https://www.nordicsemi.com/eng/Products/Bluetooth-low-energy/nRF52-DK
  - Intel Edison http://www.intel.com/content/www/us/en/do-it-yourself/edison.html
- LCD touch screen (according to the board choosen above)
- Software running on the IOT board

Sofware platform:
- Web application for central management of promotions, Dashboard and Reporting modules
- Mobile application (iOS, Android and Windows) for store managers
- Client's mobile application - _OPTIONAL_

