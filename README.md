<p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="https://i.imgur.com/6wj0hh6.jpg" alt="Hydrafacial AWS IOT"></a>
</p>

<h3 align="center">Hydrafacial AWS IOT Infrastructure</h3>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![GitHub Issues](https://img.shields.io/github/issues/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/pulls)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center"> 
    <br> 

    HydraFacial is connecting the data from its facial treatment systems to the AWS cloud.
</p>

## 📝 Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Deployment](#deployment)
- [Usage](#usage)
- [Built Using](#built_using)
- [TODO](../TODO.md)
- [Contributing](../CONTRIBUTING.md)
- [Authors](#authors)
- [Acknowledgments](#acknowledgement)

## 🧐 About <a name = "about"></a>

This project will develop the IoT cloud connection and required infrastructure for AWS IOT services.

Collected data from IOT devices will then be utilized to support key metrics and use cases for its business, providers, and end users.



## 🏁 Getting Started <a name = "getting_started"></a>

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See [deployment](#deployment) for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them.

```
Node Package Manager NPM
AWS Credentials
@onica/Runway
```

### Installing

A step by step series that tell you how to get a development env running.

Installing Runway can be offered with different options but here it will be available as dev dependency in the package.json , so you will just need to run this command:

```
npm install
```

## 🔧 Running the tests <a name = "tests"></a>

Explain how to run the automated tests for this system.

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## 🎈 Usage <a name="usage"></a>

Add notes about how to use the system.

## 🚀 Deployment <a name = "deployment"></a>

This project use runway to manage deployment of Cloudformation stacks on different environments as follows:

```
npx runway deploy --debug --deploy-environment dev

npx runway deploy --debug --deploy-environment stage
```

And for generating sample Cloudformation module :
```
npx runway gen-sample cfn
```
## ⛏️ Built Using <a name = "built_using"></a>

- [Runway](https://docs.onica.com/projects/runway/en/release/index.html) - IAC Deployment Tool
- [NPM](https://docs.npmjs.com/about-npm) - Node Package Manager

## ✍️ Authors <a name = "authors"></a>

- [@Rackspace](https://www.rackspace.com/) - Architecture & Implementation


## 🎉 Acknowledgements <a name = "acknowledgement"></a>

- Hat tip to anyone whose code was used
- Inspiration
- References
