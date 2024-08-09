# Plugin Repository

for PHPNuxBill Plugin Manager

It will list plugin available for PHPNuxBill

No need to download, just open **Plugin Manager** in Admin area

To add your plugin

* fork this repository
* add your plugin details    
  The ID of the plugin is from your URL, if URL https://github.com/username/**My-Plugin** then the Plugin id is **My-Plugin**
* save it, and do pull request

if you want to sell your Plugin, then just set ispaid to true, to sell the plugin, customer must have github, and after they paid, you add it to your private repository plugin

```json
{
    "id": "My-Plugin",
    "name": "My Plugin Name",
    "description": "information about plugin",
    "ispaid": false,
    "author": "You Name",
    "url": "https://github.com/username/My-Plugin",
    "github": "https://github.com/username/My-Plugin",
    "last_update": "2023-11-3"
}
```

