#phpSecurityClass v0.1

Php regular expression for all html-input tag

## How to Install

1) Copy src/phpSecurityClass.php file on your website

2) Add class after `<body>`:
```php
<php 
 include("phpSecurityClass.php"); 
 $security = new phpSecurityClass();
?>
```

2) Choose the appropriate function:
```php
if($security->name("John Titor"){
	echo "Correct Input";
}else{
	echo "Error";
}
?>
```

## Support

You can find us on this web source:

WebSite: http://www.ptkdev.it/

Source: https://github.com/PTKDev/

IRC: chat.freenode.net at #ptkdev
