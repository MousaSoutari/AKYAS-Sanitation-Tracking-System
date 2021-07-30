# AKYAS container base track and trace and verification system

[![License](https://img.shields.io/badge/License-Apache2-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0) [![Website](https://img.shields.io/badge/View-Website-blue)](https://www.akyas-sanitation.com/)

AKYAS [أكياس] is an Arabic word for bags.
One of our flagship innovations is a portable wastewater treatment plant in a bag!
What we could offer in addition is a urine-diverting toilet pan that enhances the performance of the bag.

[![Watch the video](https://github.com/MousaSoutari/AKYAS-container-base-track-and-trace-and-verification-system/blob/main/Youtube.PNG)](https://www.youtube.com/watch?v=xF3K4bmht9o)

## Contents

- [Akyas Sanitation Tracking System](#akyas-container-base-track-and-trace-and-verification-system)
  - [Contents](#contents)
  - [Short description](#short-description)
    - [What's the problem?](#whats-the-problem)
    - [How can technology help?](#how-can-technology-help)
    - [The idea](#the-idea)
    - [Flow](#flow)
  - [Demo video](#demo-video)
  - [The architecture](#the-architecture)
  - [Long description](#long-description)
  - [Project roadmap](#project-roadmap)
  - [Getting started](#getting-started)
  - [Live demo](#live-demo)
  - [Built with](#built-with)
  - [Contributing](#contributing)
  - [Authors](#authors)
  - [License](#license)

## Short description

### What's the problem?

Part of the World Health Organization's guidance on limiting further spread of COVID-19 is to practice social distancing. As a result, schools in most affected areas are taking precautionary measures by closing their facilities. With school-aged children at home for an indeterminate amount of time, keeping them engaged, entertained, and on top of their education is important.

### How can technology help?

Schools and teachers can continue to engage with their students through virtual classrooms, and even create interactive spaces for classes. As parents face a new situation where they may need to homeschool their children, finding appropriate online resources is important as well.

### The idea

AKYAS sanitation has developed a backend technology for container-based sanitation (CBS) solution: a breathable bag made 100% from compostable material, the bag acts as a membrane sheet, it remove water content from fecal excreta and neutralizes pathogens onsite through a proprietary powder-mix. This technology shows a revolutionary approach for CBS service providers, and a new approach for the treatment of human waste onsite.

AKYAS bag will have a printed QR code, upon collection the bag will be weighed and sent into the greenhouse, in order to accelerate the removal of water content in the fecal waste (75-80% of poop is water). The end product is a soil amendment. For quality purposes, random samples will be collected from bag and sent to lab to verify the nutrients content and ensure that the new byproduct is free of pathogens.

The aim of the developing AKYAS software application is to consolidated web and mobile enterprise resource planning platform that will be used by CBS operation team.
The software will have the capacity to monitor and manage the collection of container from toilets at scale. Digitalizing this aspect of operations can offer significant benefits, as managing this system using manual data collection is expensive, prone to errors, and overall doesn’t give the level of visibility needed across the organization for the logistics. 

The software will record data such as:

- Toilet booth being served: Date and time through a booth QR

-  Digital Money transaction from the client

-  Collect the bag QR#, Weight correlate it with toilet booth.

-  log the date when the container is being entered to the greenhouse

- after leaving the greenhouse, measure the weight

- Collect random sample and send it to the lab

- if product is sold


## Flow

![Flow](https://github.com/MousaSoutari/AKYAS-container-base-track-and-trace-and-verification-system/blob/main/Flow.png)

## Demo video

NA

## The architecture

![architecture](https://github.com/MousaSoutari/AKYAS-container-base-track-and-trace-and-verification-system/blob/main/architecture.png)

1. The user log the Bags movement in/out from WC.
2. Calling the AOI business layer.
3. Store data on Database and start data analysis.
4. Prepare the required reports and information.
5. User naviagte and check the reports

## Long description

[More detail is available here](./docs/DESCRIPTION.md)

## Project roadmap

The project currently does the following things.

- Feature 1
- Feature 2
- Feature 3

It's in a free tier IBM Cloud Kubernetes cluster. In the future we plan to run on Red Hat OpenShift, for example.

See below for our proposed schedule on next steps after Call for Code 2021 submission.

![Roadmap](./images/roadmap.jpg)

## Getting started

In this section you add the instructions to run your project on your local machine for development and testing purposes. You can also add instructions on how to deploy the project in production.

- [sample-react-app](./sample-react-app/)
- [sample-angular-app](./sample-angular-app/)
- [Explore other projects](https://github.com/upkarlidder/ibmhacks)

## Live demo

NA

## Built with

- [IBM Cloudant](https://cloud.ibm.com/catalog?search=cloudant#search_results) - The NoSQL database used
- [IBM Cloud Functions](https://cloud.ibm.com/catalog?search=cloud%20functions#search_results) - The compute platform for handing logic
- [IBM API Connect](https://cloud.ibm.com/catalog?search=api%20connect#search_results) - The web framework used
- [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
- [Maven](https://maven.apache.org/) - Dependency management

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Authors

<a href="https://github.com/MousaSoutari/AKYAS-container-base-track-and-trace-and-verification-system/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=MousaSoutari/AKYAS-container-base-track-and-trace-and-verification-system" />
</a>

## License

This project is licensed under the Apache 2 License - see the [LICENSE](LICENSE) file for details.

