# Setting up developement environment for Joomla! dev

*These settings are being done in VS Code.*

#### 1. Installing PHP Code sniffer

- It is a linter checks the error of intendation and spaces

##### To install it

``` composer global require "squizlabs/php_codesniffer=*" ```

##### Install joomla standards

```composer global require joomla/coding-standards "~2.0@alpha"```

##### Add this to the path
```
C:\\xa\php
```

##### Add this to the VS code user settings
```
"php.executablePath": "C:\\xa\\php\\php.exe",
"php.validate.executablePath": "C:\\xa\\php\\php.exe",
```
> This would be parsing JSON data so please make sure that the response should be proper JSON.
