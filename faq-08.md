## What information is collected by Freemius if I opt-in and why?
When opting into usage tracking, the only personal data collected includes first & last name, and email address of the opted-in WordPress user. Except for that, no other personal or business-critical data from you or your website’s users is tracked.

When opting-in by activating a license key, no personal data will be collected at all, as we already have the details of the license owner from the payment process.

The name and email address are stored to allow the product’s team to get in touch regarding potential security updates, feature announcements, promotions, etc.

The table below shows a comprehensive list of all the data we collect and why.

---

### **User information**

**Important:** The user information is **_not_** collected when activating a license key.

#### What data?
* Opted-in user’s first & last name
* Opted-in user’s email address

#### Why?
Let’s start with the most important reason - _Security_. 

Security issues are inevitable in the software world. Whether developers like it or not, one day they will release a version that will have a security issue. The issue can be directly in their code, a 3rd party library/framework used in the product, a WordPress core method that provides unexpected results, or many other scenarios.

If the plugin or theme developer has no way to communicate with their users, how will you know about the security vulnerability that is currently putting your site at risk of being hacked? The only way you might find out about the risk would be for the developer to release a public announcement or an update/patch and hope that you’ll notice it before any hackers do. That’s super risky since it raises awareness and creates an opportunity for hackers to exploit the situation. Therefore, the ability for the product developer to communicate with their users in a private manner is essential.

There are many more valid reasons to maintain a direct communication channel between you and the product developer. Here is a short list of possible use-cases (again, not exhaustive):
* Thank you for being a loyal user or for purchasing
* Ask for your feedback on the product or a new feature for ongoing product improvement
* Apologize for making some kind of mistake. Maybe a release accidentally contained a major bug and took your entire website down, or any other number of problems that can be caused by bugs or code conflicts. 
* Let you know about special promotions or discounts like Black Friday / Cyber Monday / Giving Tuesday
* Invite you to special events or conferences, e.g., “meet our team at WordCamp”
* Invite you to the product’s beta access so you can test releases before they are officially published in return for rewards
* Advise you about the ending of a trial period
* Send you general company news & updates
* Let you know about new feature releases
* Run user surveys to get your feedback on which new features you’d like to see in the product
* Invite you to join the product’s affiliates’ program
* Inform you about newly published educational content or a blog post/article

If the day comes – notify you on ceasing the plugin or theme’s support, updates, or maintenance 🙁

As you can see, some of the reasons are more valuable for you as a user/customer and others benefit the developer. 

At the end of the day, both sides rely on each other.  Product developers build products for YOU, the user, and if they rely on guesswork without actually knowing what their users need, the quality of the product, features, and service, will never meet their full potential. In order to create great products and offer support, the developer of the product need to understand their users’ needs and make money to sustain product development and support. 

**Customers & License Holders**
When you activate a paid product that is using the Freemius WordPress SDK, the first thing that you’ll be prompted with is a license activation screen. By activating the license, regardless of who is the logged-in user that activates it, the opt-in is triggered in behalf of the license owner. So no information about the logged-in user, or any other user, will be collected. The license owner’s information was already collected during the purchase process and will not be changed if a different user activates the license under a different email address than what was used for the original purchase.

### **Product information**

#### What data?
Product version

#### Why?
Knowing the plugin/theme version being used is super important for many reasons. Here are just two examples:

1. We mentioned security before, but if the developer finds that there’s a security vulnerability in a specific plugin version, they can easily identify which users need to be notified. Without knowing what version you have installed, the developer would normally have to reach out to all their users, unnecessarily bothering some portion of them with information they don’t need to know.

2. If the product’s team decides to stop supporting PHP versions that are older than 5.6 in the next release and your hosting provider is still using it (which can potentially break your site) wouldn’t you want to get notified before the new version is released and you hit the update button? I definitely would. This is not just an “edge-case” scenario to justify collecting the product version either - this is a real issue plugin and theme developers have to deal in the WordPress “data-less” ecosystem, which puts your website at risk.

#### What data?
Product state (active, inactive, uninstalled)

#### Why?
Remember, there are many valid reasons to maintain a direct communication channel between you and the product developer. For example, if you’ve opted-in to usage-tracking and then later uninstalled the product, the developer has no way to know the product is no longer in use, so you may continue receiving feature announcements and other direct email communications that most likely aren’t relevant to you any more.

When opting into during license activation for a paid product, the product state becomes even more important. For example, wouldn’t you want to reuse a license? If Freemius won’t be aware of a product’s deactivation/uninstall, the system would have on record that the license is still in use by the site, hence you wouldn’t be able to reuse the license on another website of yours.

Knowing the product’s state helps developers understand the status of the product on your site. This allows for transparency at all levels, including if there is a refund request or payment dispute, a log of activations, deactivations, and uninstallations keeps everyone honest about whether or not refunds are possible or justified given the circumstances.

### **Site information**

#### What data?
* WordPress version
* PHP version
* MySQL version

#### Why?

The environment versions are important data points for ongoing development of a plugin or theme. For example, let's say that a developer is considering to drop support for PHP 5.3 and maybe even require PHP 7.0 as the minimum required PHP version to be able to take advantage of the modern syntax of the programming language for better code maintenance. Without knowing how many sites are using older PHP versions and without having a way to contact those site owners in advance, the product will always get “stuck” at the oldest PHP version that WordPress core supports. The same reasoning applies to the WordPress and MySQL versions.

These data points are even more important for users of paid product(s) as part of the software update mechanism. For example, if a developer wants to introduce a new paid version that uses a core WordPress function that was only added in version 5.3, without knowing the WordPress version that is installed on user sites, an update like that can potentially generate fatal errors. On the other hand, when the installed WP version is known, if it is older than the minimum required version, the update won’t be served to avoid any issues up until the WP version on that site is updated.

#### What data?
WordPress locale (country + language)

#### Why?
WordPress is used all over the world and fully translated into dozens of languages. Plugin and theme developers have an interest in expanding their reach and making their products accessible to as many users as possible. With limited information and resources, one option is shooting in the dark and trying to get the product translated into the most widely used global languages. However, the better approach is to identify the top countries and languages (the locale) of the sites where the product is installed, and focus translation efforts on the actual languages and dialects that the users of the product need.

As an example, [Joe Dolson](https://www.youtube.com/watch?v=ztdxgcF2caE), WP accessibility expert and the developer of the WP to Twitter plugin, has [discovered that almost 30% of the sites using the plugin are in Japanese](https://www.joedolson.com/2016/04/learning-wp-twitter/):
> The first thing I learned is about internationalization. While the most common language group using this plug-in is English (not surprising), the second most common appears to be Japanese – by a significant margin. I wasn’t expecting that, and it’s very interesting. It’ll definitely be relevant in focusing my efforts on reaching out to translators to improve the internationalization of WP to Twitter.

#### What data?
Site URL

#### Why?
Knowing the site URL allows developers to learn about how users are using their product in the wild. Being able to see what types of websites are using their product helps in prioritizing the development of new capabilities while accommodating the needs of users based on real use-cases.

#### What data?
Site IP

#### Why?
The IP of the website server enables identification of the ISP (Internet Service Provider) and hosting company. Combined with the other collected data points, problematic patterns can be identified and solved in scale. For example, if a particular host consistently uses unsupported PHP versions and doesn’t have the PHP cURL extension enabled by default, we can contact the host directly and encourage them to enable cURL by default and upgrade the default PHP version.

#### What data?
List of installed plugins & themes (optional)

#### Why?
While sharing installed plugins and themes is super valuable, its collection is absolutely optional. You can control whether to share it or not when activating a license key or even when opting in. Simply click the “What permissions are being granted?” shown in the opt-in/license-activation screen, and turn off the plugins & themes tracking by clicking the switch next to the relevant permission: 

![Image of Opt-In Permissions](https://freemius.com/blog/wp-content/uploads/2020/03/freemius-wordpress-sdk-opt-in-permissions.png)

Knowing the plugins and themes that are most commonly used in parallel with a product can help developers in multiple ways:

**Testing & Compatibility**
WordPress.org has more than 50,000 plugins and 7,000 themes. It is literally impossible to test your product with all of those, and that’s not to mention the tens of thousands of plugins and themes hosted outside of the WordPress.org repository. By knowing the plugins and themes that are most commonly used alongside the product, developers can focus their testing efforts on compatibility with those plugins and themes. Basically, they are given more information to prevent unexpected conflicts.

**Collaborations & Partnerships**
If a product developer knows that their plugin/theme is typically used in combination with pluginX, they can collaborate with pluginX’s team to make sure both products are compatible and working smoothly. There are also opportunities for plugin and theme businesses to cooperate on content marketing and educational content, helping the users of both products get the most out of them.

---

All this data is collected with the intention of making plugins and themes better and more secure. We help plugin and theme businesses do that by tracking how their users are using the product, learning why they abandon it, what environments are needed to continue supporting, and much more. These valuable data points are key to making data-driven decisions and lead to better UX (user experience), new features, better documentation and other benefits for the customer.

## [Next →](faq-09.md)
