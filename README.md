# wordpress-composer
This is the repository to try sample config on the web tutorial.
It may need to set values in wp-config.
At least, need to define follows two values before require_once(ABSPATH . 'wp-settings.php');

define('WP_CONTENT_DIR', dirname(__FILE__) . '/wp-content');
define('WP_PLUGIN_DIR', dirname(__FILE__).'/wp-content');
