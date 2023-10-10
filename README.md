
![image](https://github.com/magmodules/magento2-ekomi-hyva/assets/24823946/7e8e6a5c-ce6f-44e7-ada2-cb1c27a95e10)

# Ekomi Hyvä Compatibility plugin


The eKomi plugin for Magento is a powerful integration that seamlessly connects the popular review platform, eKomi, with Magento. This plugin offers extensive functionality to enhance your online store's reputation management and customer feedback process.

The Ekomi Compatibility plugin for the Magento Hyva theme has the following requirements:
- [Magento 2.4.+](https://github.com/magento/magento2)
- [Hyvä](https://github.com/hyva-themes)
- [Magmodules Ekomi Reviews](https://www.magmodules.eu/magento2-ekomi-reviews.html)    

<img width="1078" alt="Hyva-ekomi-magento-plugin" src="https://github.com/magmodules/magento2-ekomi-hyva-dev/assets/24823946/844e4615-d7f5-440a-aa0e-64a3597b12ef">


## About the Ekomi Plugin

This means that you can effortlessly integrate the eKomi review platform into your Magento store, even if you are using the Hyva theme. The plugin ensures a smooth and seamless user experience, maintaining the aesthetic and functionality of the Hyva theme while incorporating the eKomi review system.

By utilizing this plugin, you can effectively collect and showcase customer reviews, ratings, and testimonials on your Magento website. It empowers you to display social proof, build trust with potential customers, and improve your brand reputation. The integration allows customers to submit reviews, while also providing you with the necessary tools to moderate and manage the reviews within your Magento admin panel.

Additionally, the eKomi plugin offers advanced features such as automatic review requests, email notifications, customizable review widgets, and rich snippet integration for search engine optimization (SEO) benefits. These features enable you to actively engage with customers, gather valuable feedback, and improve the overall shopping experience on your Magento store.

Overall, the eKomi plugin for Magento, with its seamless compatibility with the Magento Hyva theme, provides an excellent solution for integrating the eKomi review platform into your online store. It helps you leverage customer reviews to boost credibility, enhance customer trust, and drive conversions.

## Installation

1. Install the module using composer: 

```bash
composer require magmodules/magento2-hyva-ekomi
```

2. Enable the module:

```bash
bin/magento module:enable Magmodules_HyvaEkomiSR
```

3. Upgrade the database:

```bash
bin/magento setup:upgrade
```

4. Let Hyvä know about the new module:

```bash
php bin/magento hyva:config:generate
```

5. Generate the CSS files:

```bash
npm --prefix vendor/hyva-themes/magento2-default-theme/web/tailwind/ run ci
npm --prefix vendor/hyva-themes/magento2-default-theme/web/tailwind/ run build-prod
```

Or from your theme:

```bash
npm --prefix app/design/frontend/<Vendor>/<Theme>/web/tailwind run ci
npm --prefix app/design/frontend/<Vendor>/<Theme>/web/tailwind run build-prod
```

## Ekomi Magento plugin features

- Seamless integration
- Review collection automation
- Customizable review widgets
- Rich snippet integration
- Review moderation and management
## Magento Support

If you have any questions, please fill out our secure contact form by clicking [here](https://www.magmodules.eu/support-form.html).

## Magmodules & Hyva

Magmodules and Hyva have established a strong partnership, working closely together to provide enhanced e-commerce solutions. As an official Hyva partner, we specializes in developing integrations for various platforms and services. 

We have created integrations for well-known providers such as Mollie, Sooqr, Paazl, and many more. This collaboration ensures seamless compatibility and optimized performance for online stores utilizing the Hyva theme. Through our partnership, Magmodules and Hyva strive to deliver comprehensive and tailored solutions to meet the diverse needs of e-commerce businesses.






## Checkout our other Hyva Plugins!

[- Magento 2 Hyvä Shopreview](#) 
 
[- Magento 2 Hyvä Product Review Reminder](#) 

[- Magento 2 Hyvä Mollie React Checkout](#) 

[- Magento 2 Hyvä Checkout](#) 

[- Magento 2 Hyvä Mollie React Checkout](#) 

[- Magento 2 Hyvä Paazl](#) 
