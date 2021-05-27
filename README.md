# Checkout Transparente PayPal para OpenCart 2 e 3
![](https://raw.githubusercontent.com/wiki/paypal/PayPal-PHP-SDK/images/homepage.jpg)

The experience of a transparent checkout processed with PayPal security. Your client will pay directly on your site, without redirection and without the need to open a PayPal account, using only credit card data, which can be saved to Streamline the payment of future purchases.


## Requirements

For the correct solution of the solution, you need to check if your store and server support some features:
1. Your store needs to support CPF Custom Fields and Number (Address Type), so before activating the solution ensure that your store is properly configured to support these fields;
2. The server needs to support PHP 7.3 or higher;
3. The server needs to support TLS 1.2 or higher and HTTPS 1.1 [(official reference)] (https://www.paypal.com/sg/webapps/mpp/tls-http-upgrade).

## Transparent Checkout (Paypal Plus)

Transparent checkout is only available for paypal accounts registered with CNPJ (Company Account), if your account is from a physical person, you must open a Legal Personal account by this [link] (https://www.paypal.com / bizsignup /).

The solution requires commercial approval, contact by 0800 721 6959 and ask now.

*** Transparent checkout will only work if it has been approved by PayPal. **

## Compatibility

This module is compatible with OpenCart versions ** 2.0.1.1 up to 3.0.3.7 **.

## Installation

1. Download the module compatible with your version of Opencart, then access the administration of your store;
2. Go to the menu ** Extensions → Installer **, click the "** Upload **" button, locate the file you downloaded, and wait for the automatic installation completion;
3. Go to the menu ** Extensions → Modifications ** and click the "** update **" button;
4. In OpenCart 3, go to the menu ** Control panel **, on the right side of the screen below the "** Exit **" button, click the button in blue color with the drawing of a white gear on it, in the modal Click on both orange buttons that are inside the column "** Action **" to update the theme cache;
5. Go to the menu ** Extensions → Payments ** (in versions 2.3 or higher Go to the menu ** Extensions → Extensions ** and Filter by ** Payments **), locate the extension "** Paypal Plus **" Click the "** install **" button, then the "** edit **" button, fill in the fields and click the "** Save **" button.

## Settings
### - API credentials
To configure the PAYPAL PLUS solution, you must generate the REST API credentials in case the Client ID and Secret ID.

To obtain you follow this step-by-step:

1. Log in with your PayPal account at https://developer.paypal.com and click on the link at the top "** dashboard **";
2. Click "** MY Apps & Credentials **";
3. Beneath "** Rest API Apps **" Click "** Create App **";
4. Then enter the term "** ppplus **" in the "** app name **" field and click "** Create App **";
5. In the upper right corner of the screen, click "** Live **";
6. You must copy the codes that appear in "** Client ID **" and "** Secret **" (To view the "Secret" you need to click "** Show **") and paste these codes On the solution configuration page you use.

### - Custom Fields

For the transparent checkout to work correctly, your store will need to register the Custom CPF (Type Account) and Number (Address Type) fields.

To register them Go to the ** clients → Customize Register **.

To register the ** cpf ** field, click the ** new button **, fill out the form with the information below:

| Field | Value |
| -------- | ----- |
| Field Name | CPF |
| Location | Account |
| Field type | Text in a line |
| Type of customer | Mark the types of customers who will see the field during registration |
| Mandatory types | Mark the types of clients that will have the field as required |
| Situation | Enabled |

After filling out the form, click the ** Save ** button.

To register the field ** number **, click the ** new button **, fill out the form with the information below:

| Field | Value |
| -------- | ----- |
| Field Name | Number |
| Location | Address |
| Field type | Text in a line |
| Type of customer | Mark the types of customers who will see you during the registration |
| Mandatory types | Mark the types of clients that will have the field as required |
| Situation | Enabled |

After filling out the form, click the ** Save ** button.

## Questions / Support

If your doubt has not been answered here, please contact PayPal at 0800 047 4482.

And if you need some technical support and / or believe you have found some problem with this module, visit our [Technical Support Portal] (https://www.paypal-support.com/s/?Language=pt_Br) and open A ticket detailing your problem in the "Contact Us" section.
## Changelog

Para visulizar as últimas atualizações acesse o [**CHANGELOG.md**](CHANGELOG.md).
