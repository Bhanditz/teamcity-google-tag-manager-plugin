# TeamCity Google Tag Manager Plugin

The initial version of the plugin allowing to add Google Tag Manager to the TeamCity UI pages. 
It's not ready for public announcement and is used on https://teamcity.jetbrains.com

The plugin is compatible with TeamCity starting from 2017.2.2

## Configuration
 Put the following configuration in `<TeamCity Data Directory>/config/googleTagManager/settings.xml` file 
 replacing {id} with an actual GTM container id.

```xml
<?xml version="1.0" encoding="UTF-8"?>
<google-tag-manager container-id="{id}"/>
```