Laravel-PayPal-IPN
==================

Laravel 4.1 Laravel Paypal IPN Listener

Requirements / Requerimientos:
You need to have an account for testing on PayPal / Necesitas una cuenta para pruebas en PayPal
https://developer.paypal.com/

You need have installed Curl / Necesitas tener instalado Curl:
If you do not know how to install Curl you can search it on google /Si no sabes como instalar Curl puedes buscarlo en Google

You need a route like this / Necesitas una ruta como esta :
Route::post('pago/paypal', array('uses' => 'PayPalController@paypal'));
