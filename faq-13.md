## How can I hide sensitive information from the Account page?
To simplify the management of your account, one of the features included with the Freemius SDK is an Account section that is automatically added to the product’s settings in the WP Admin dashboard. This allows you and other users to manage their account right within the comfort of the developer’s website, without ever leaving the WP Admin. This feature is great, but can be a bit problematic when you are installing a product on a client’s site and not on yours, as the Account page may reveal your email address, license key, and billing information. It will allow any admin of that site to trigger different actions that are related to your account. To overcome that tricky situation, we introduced a special option to flag a license for “White-labeling”, which will hide all sensitive information related to you and the product from the WP Admin, including:
* User information
* Billing details and invoices
* License key
* Pricing page
* Add-on prices (if the product sells add-ons)
* Contact Us page

Flagging a license for “White-labeling” can be done easily from the _User Dashboard_. Simply locate the relevant license in the Licenses section, click the license to open the license options, and then check the relevant box in the _LICENSE SECURITY_ section:

![Image License Security](https://lh4.googleusercontent.com/_pzaXxYpqEIHGL2-cZcSjo4XDccCF-SXowEyCdnStmQzvP94RpwIx4sw8_KPqrhSgruOcjTI3iXVn2rUXyVx=w1085-h920)

**Notices:**
* This feature only works with with SDK 2.3.1 and higher.
* It can take up to 24 hours until the license “White-labeling” mode is synced into the WP Admin dashboard. If you’d like to expedite the process, navigate to the Account page within the WP Admin dashboard of the product and click the “Sync” link.

## [Next →](faq-14.md)
