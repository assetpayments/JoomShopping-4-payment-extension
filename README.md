# Joomla 3.5 & JoomShopping 4 payment extension
Payment extension for Joomla 3.5 JoomShopping 4 / Модуль оплаты для Joomla 3.5 JoomShopping 

### Installation

* Backup your webstore and database
* Open menu Components -> JoomShopping -> Installation & Update 
* Press Choose file button and select assetpayments.zip file
* Open menu Components -> JoomShopping -> Payment methods
* Find installed AssetPayments extension
* Configure the new module
* General settings:
  * Publication - On
  * Code - assetpayments
  * Name - Pay by card Visa/Mastercard (AssetPayments)
  * Alias - pm_assetpayments
  * Script name - pm_assetpayments
  * Price - 0.00
  * Image URL - /components/com_jshopping/payments/pm_assetpayments/pay_logo/asset.png
  * Type - Extended
  * Show description in the order - off
  * Show standard bank details - on
* Configuration:
  * Merchant Id
  * Secret key
  * Template ID (default = 19)
  * Successful payment status
  * Pending payment status
  * Failed payment status
  * Press Save & close button
  
### Notes
Tested and developed with Joomla 3.5.4 and JoomShopping 4.18.2.

## Модуль оплаты Joomla 3.5 & JoomShopping 4

### Установка

* Сделайте резервную копию сайта и базы данных
* Откройте раздел Компоненты -> JoomShopping -> Установка и обновление
* Укажите путь к файлу assetpayments.zip и нажмите кнопку Установить
* Откройте раздел Компоненты -> JoomShopping -> Платежные методы
* Нажмите на созданный метод AssetPayments 
* Настройте модуль
* Основные настройки:
  * Публикация -Вкл
  * Код - assetpayments
  * Название - Оплатить картой Visa/Mastercard (AssetPayments)
  * Алиас - pm_assetpayments
  * Имя скрипта - pm_assetpayments
  * Цена - 0.00
  * Изображение URL - /components/com_jshopping/payments/pm_assetpayments/pay_logo/asset.png
  * Тип - Расширенный
  * Показывать описание в заказе - Выкл
  * Показать стандартные банковские данные в счете - Вкл
* Конфигурация:
  * Id мерчанта
  * Секретный ключ
  * ID шаблона (по-умолчанию = 19)
  * Статус успешного платежа
  * Статус прерванного платежа
  * Статус НЕ успешного платежа
  
### Заметки
Протестировано с Joomla 3.5.4 и JoomShopping 4.18.2.
