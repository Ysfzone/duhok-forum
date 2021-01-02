# Duhok Forum v3.0
Duhok Forum is a free forum script developed in PHP and MySQL. It can be installed in Linux servers or local servers by using Wamp, Xampp, etc...\
دهوك فوريوم هي نسخة منتديات مجانية مبرمجة بلغة&#x202b; PHP وقواعد بيانات MySQL. بإمكانك تثبيت على خوادم لينكس و خوادم المحلية مثل Wamp وXampp والى اخره...

[![GitHub Version](https://img.shields.io/github/v/tag/dilovanmatini/duhok-forum)](https://github.com/dilovanmatini/duhok-forum/releases)
[![editor](https://img.shields.io/badge/editor-vscode-blue)](https://code.visualstudio.com/)

![Preview](https://repository-images.githubusercontent.com/324770043/500d6e80-4c34-11eb-9563-967e32b1c16a)

## Download - تحميل
[Download](https://github.com/dilovanmatini/duhok-forum/releases)

## Installation - التثبيت
After you download the ZIP file, extract it, then put the script files into your server's runnable folder and do the below steps:
1. Create a `MySQL` database and open `includes/config.php` file, then put the database information into below variable:
```php
$df_config['database'] = [
    'host' => 'localhost',    // Server Host Name
    'name' => 'df_db',        // Database Name
    'user' => 'df_db',        // Database User Name
    'pass' => '',             // Database User's Password
    'prefix' => 'df_',        // Tables's Preix
    'port' => 3306            // MySQL Server Port
];
```
1. Go to `http://hostname/install`.
1. After reading license and agree it, click `Next`.
1. Check the database connection and click `Next`.
1. Type the nessesary forum's information, then create an `Admin`, and then click `Begin Setting Up`
1. Finally, you will see the congratulation message, then you can navigate your forum.

## Documentation - الدليل
<https://www.startimes.com/f.aspx?mode=f&f=211>

## Bugs and Issues - مشاكل
Have an issue or a bug? please feel free to [open a new issue](https://github.com/dilovanmatini/duhok-forum/issues/new).\
هل توجد مشكلة في النسخة؟ أرجوا ان لا تتردد في ذكرها بفتح [مشكلة جديدة&#x202b;](https://github.com/dilovanmatini/duhok-forum/issues/new).


## Contact - اتصل بنا
df@lelav.com

## Support - دعم
Is Duhok Forum fitted your requirements?  [Buy Me a Coffee ☕](https://www.paypal.me/DilovanMatini)\
&#x202b;هل نسخة منتديات دهوك يناسب متطلباتك؟  [اشتري لي فنجان قهوة ☕](https://www.paypal.me/DilovanMatini)
