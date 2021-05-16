opencart liqpay extension
===============

LiqPay Checkout plugin for opencart CMS since Version 2.3.0.x

#### To install the module, copy the contents of the upload directory: ####
Files of this extension replace the files included in the standard opencart distribution

``,
<OpenCart> / admin /
<OpenCart> / catalog /
<OpenCart> / system /
``,

#### Then install and configure it in the admin panel: ####

``,
Extensions> Payments> Liqpay click [Install]
Extensions> Payments> Liqpay click [Edit] and fill in the required settings
``,
 * in the settings you can select the mode of operation of the extension in test mode -
   in this mode, funds are not debited from the payer's card.
   Also in the settings, statuses for orders are set in case of successful payment and in case of payment cancellation.
   All test payments will have the status set for payment cancellation.
   


#### To start accepting payments on your website, you need: ####
    - Register at https://www.liqpay.com
    - Create a store in your account using the installation wizard (https://www.liqpay.com/admin/business)
    - Get "Public Key" and "Private Key"

#### Для установки модуля скопируйте содержимое каталога upload: ####
Файлы данного расширение заменяют файлы идущие в стандартной поставке opencart

```
<OpenCart>/admin/
<OpenCart>/catalog/
<OpenCart>/system/


--------------------

#### Затем в панели администратора установите и настройте его: ####

```
Extensions > Payments > Liqpay нажать [Install]
Extensions > Payments > Liqpay нажать [Edit] и заполнить необходимые настройки
```
 * в настройках есть возможность выбора режима работы расширения в тестовом режиме - 
   в этом режиме средства с карты плательщика не списываются. 
   Также в настройках задаются статусы для заказов в случае успешной оплаты и в случае отмены платежа.
   Все тестовые платежи будут иметь статус установленный для отмены платежа.
   


#### Для начала приема платежей на Вашем сайте необходимо: ####
    - Зарегистрироваться на https://www.liqpay.com
    - Создать магазин в Вашем аккаунте используя мастер-установки (https://www.liqpay.com/admin/business)
    - Получите "Публичный ключ" и "Приватный ключ"
