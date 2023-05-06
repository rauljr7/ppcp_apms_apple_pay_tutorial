# Getting Started

Grab your PayPal CLIENT ID and SECRET and fill them in the following files:
* [.env-rename](https://github.com/rauljr7/ppcp_apms_apple_pay_tutorial/blob/main/.env-rename)
* [script.js](https://github.com/rauljr7/ppcp_apms_apple_pay_tutorial/blob/main/script.js#L58)
* Rename the .env-rename file to .env
* Add your server-side URL here:
    * [script.js#L36](https://github.com/rauljr7/ppcp_apms_apple_pay_tutorial/blob/main/script.js#L36), [script.js#L109](https://github.com/rauljr7/ppcp_apms_apple_pay_tutorial/blob/main/script.js#L109), [script.js#L120](https://github.com/rauljr7/ppcp_apms_apple_pay_tutorial/blob/main/script.js#L120), [script.js#L158](https://github.com/rauljr7/ppcp_apms_apple_pay_tutorial/blob/main/script.js#L158), [script.js#L224](https://github.com/rauljr7/ppcp_apms_apple_pay_tutorial/blob/main/script.js#L224), [script.js#L293](https://github.com/rauljr7/ppcp_apms_apple_pay_tutorial/blob/main/script.js#L293), [script.js#L307](https://github.com/rauljr7/ppcp_apms_apple_pay_tutorial/blob/main/script.js#L307)
* If you want to use SendGrid for sending emails, add your SendGrid API Key in the [index.js file here](https://github.com/rauljr7/ppcp_apms_apple_pay_tutorial/blob/main/index.js#L165) and you can edit the email HTML content in the [email_content_html variable here](https://github.com/rauljr7/ppcp_apms_apple_pay_tutorial/blob/main/index.js#L166)


Once you have configured your credentials, you can run `npm i` to install the packages and start your app with `node index`