# CakePHPStaticGoogleMapHelper
Cakephp Helper to generate Static google map images or URL

# Installing

1) Just Copy the GoogleHelper file and paste it under  app/View/Helper
2) Load the helper in  helpers array 

/**
 * Helpers
 *
 * @var array
 */
	public $helpers = ['Google'];
  
Then call it in the view:

echo  $this->Google->image(43.556677, 32.123456);
