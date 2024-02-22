<div align="center">
![Project Logo](https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png
<h1 align="center">Empress Shipping: Streamlining Your Shipping Operations</h1>
<p align="center">
A comprehensive shipping integration tool for businesses, designed to simplify and optimize your shipping process.
<br />
<a href="https://empress.eco/">Explore the Docs</a>
·
<a href="https://github.com/empress-eco/shipping/issues">Report Bug</a>
·
<a href="https://github.com/empress-eco/shipping/issues/new">Request Feature</a>
</p>
</div>

## About The Project

### 📖 Overview
Empress Shipping is a robust shipping integration tool connecting various platforms such as Packlink, LetMeShip, and SendCloud to provide an all-inclusive solution for creating shipments, comparing rates, printing labels, and tracking shipments. Designed with businesses in mind, it streamlines your shipping operations, saving time and reducing complexity.

### 🌟 Unique Features
- Seamless integration with Packlink, LetMeShip, and SendCloud.
- Efficient creation of shipments to various carrier services.
- Comprehensive comparison of shipping rates for informed decisions.
- Convenient printing of shipping labels directly from the application.
- Handy parcel dimension templates for easy reference.
- Real-time shipment tracking to stay updated.

## Technical Stack and Setup Instructions

### Prerequisites
To get started with Empress Shipping, you need to have an API key from your service provider. Each service provider has their own specific doctypes similar to those from the `Integrations` and can be enabled or disabled depending on your needs.

### Installation
Setting up Empress Shipping on your server is straightforward. Follow the steps below:

```sh
cd ~/Empress-bench
bench get-app https://github.com/empress-eco/shipping.git --branch version-14
bench --site $MY_SITE install-app Empress_shipping
```

## Usage
Fetch shipping rates by clicking the `Fetch Shipping Rates` button. Once you've chosen a rate, the shipment will be created for you. The app also allows you to generate shipping labels by clicking on the `Print Shipping Label` on top of the doctype.

## Contribution Guidelines
We welcome and appreciate contributions! To contribute, follow these steps:

- Fork the Project
- Create your Feature Branch (git checkout -b feature/AmazingFeature)
- Commit your Changes (git commit -m 'Add some AmazingFeature')
- Push to the Branch (git push origin feature/AmazingFeature)
- Open a Pull Request

Your ideas and code contributions can help enhance this project and benefit many businesses.

## License and Acknowledgements

### License
This project is under the MIT License. Your contributions are also licensed under the same MIT License.

### Acknowledgements
We owe a debt of gratitude to the Empress Community, the architects behind the essential tools powering this project. Their innovation and dedication have laid the groundwork and functionalities we rely on. We are profoundly grateful for their pioneering work and ongoing support.