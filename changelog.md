### v3.3.2 [view commit logs](https://github.com/soomla/android-store/compare/v3.3.1...v3.3.2)

* New Features
  * Added purchaseToken to MarketPurchaseEvent.
  * Added isInitialized to StoreController.
  * Added the option to overwrite an object in StoreInfo and save it.
  * You can now save StoreInfo to DB if you made changes to it.
  * You can now change price of MarketItem.
  * You can now change amount of PurchaseWithVirtualItem.

* Fixes
  * Enforce providing a SOOM_SEC in obfuscator.
  * If the purchasable item is NonConsumableItem and it already exists then we don't fire any events.
  
  
### v3.3.1 [view commit logs](https://github.com/soomla/android-store/compare/v3.3.0...v3.3.1)

* Billing Services
  * Add interface for async consume.
  * Add onDestroy() to IabActivity.
  * Allowing empty signatures for test purchases only when you specifically ask for it in StoreConfig.

* New Features
  * android-store will now refresh details of market items on initialization.
  
* Optimizations
  * Fixed Names of objects and events so they match in all SOOMLA plugins.
  * Added the changed market items to the MarketItemsRefreshed event.
  
### v3.3.0 [view commit logs](https://github.com/soomla/android-store/compare/v3.2.1...v3.3.0)

* Billing Services
  * We've split out Google Play so we can add more billing services.
  * Google Play is the default billing services and it's in a different project: https://github.com/soomla/android-store-google-play

