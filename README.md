# shopify_api_php
Created: phong.nguyen 20151022 
Project: Shopify API for php 

# usage inside CodeIgniter app: 
- Put ShopifyAPI inside folder **".../third_party/"**  
- Use classes by this LOC 
```php
require_once APPPATH."/third_party/ShopifyAPI/autoload.php";    
```
- Get token  
+ Please read docs: https://docs.shopify.com/api/authentication/oauth   
+ View a demo app by Haravan:  https://github.com/Haravan/haravan_php_api   
- Get 1 product by id 

```ruby
$proSH = new ProductSH( 'your_shopify_store.myshopify.com', 'your_shopify_token', 'your_shopify_api_key', 'your_shopify_api_secret'); 
$product = $proSH->get_one('123123');  
``` 
