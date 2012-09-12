Amazon-Codeigniter-api
======================

Amazon Product Advertising API for product selection and discovery functionality so that developers can advertise Amazon products to your website.

Placing
======================

Amazon_api is library file place it inside application/library/ folder

Config Settings
======================

Edit Amazon_api is library file set config variables with your


Calling Method
======================

$this->load->library('amazon_api'); //load the library amazon_api

$this->amazon_api->searchProducts($search_keyword, $category, $searchType);

eg:$this->amazon_api->searchProducts('X-men','DVD','TITLE');

More categories can be found here:
            http://docs.amazonwebservices.com/AWSECommerceService/latest/DG/APPNDX_SearchIndexValues.html


More Help 
======================

http://www.crashcoder.com/codeigniter-php-amazon-product-advertising-api-apaa-library/
            
            


