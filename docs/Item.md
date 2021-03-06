# ai.thirdwatch.Model.Item
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**itemId** | **string** | The item&#39;s unique identifier according to your systems. Use the same ID that you would use to look up items on your website&#39;s database. | [optional] 
**productTitle** | **string** | The item&#39;s name, e.g., \&quot;WD 2 TB External Hard Drive\&quot;. | [optional] 
**price** | **string** | The item unit price in numbers, in the base unit of the currency_code.e.g. \&quot;2500\&quot; | [optional] 
**currencyCode** | **string** | The [ISO-4217](http://en.wikipedia.org/wiki/ISO_4217) currency code for the amount. e.g., USD, INR alternative currencies, like bitcoin or points systems. | [optional] 
**upc** | **string** | If the item has a Universal Product Code (UPC), provide it here. | [optional] 
**sku** | **string** | If the item has a Stock-keeping Unit ID (SKU), provide it here. | [optional] 
**isbn** | **string** | If the item is a book with an International Standard Book Number (ISBN), provide it here. | [optional] 
**brand** | **string** | The brand name of the item. | [optional] 
**manufacturer** | **string** | Name of the item&#39;s manufacturer. | [optional] 
**category** | **string** | The category this item is listed under in your business. e.g., \&quot;travel\&quot;, \&quot;man &gt; bags\&quot;. | [optional] 
**tags** | **string** | The tags used to describe this item in your business. e.g., \&quot;man\&quot;, \&quot;summer\&quot;. | [optional] 
**color** | **string** | The color of the item. | [optional] 
**quantity** | **long?** | The quantity of the item. | [optional] 
**isOnSale** | **bool?** | Is item on sale or running offers on this item . | [optional] 
**maxQuantity** | **long?** | The max quantity per user for this item. | [optional] 
**discountPrice** | **string** | Price of the product after discount. | [optional] 
**productWeight** | **string** | Weight of the product in Kilo Gram, e.g. \&quot;3\&quot; , \&quot;0.5\&quot; | [optional] 
**country** | **string** | The [ISO-3166](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2) country code of the item, e.g., \&quot;IN\&quot; in case of India. | [optional] 
**descriptionShort** | **string** | Short description of the item. | [optional] 
**description** | **string** | Detail description of the item. | [optional] 
**seller** | [**Seller**](Seller.md) |  | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

