# Crisis Hackers

GitHub repository for Call for Code submission.

## Contents

1. [Short description](#short-description)
1. [Demo video](#demo-video)
1. [The architecture](#the-architecture)
1. [Long description](#long-description)
1. [Project roadmap](#project-roadmap)
1. [Getting started](#getting-started
1. [Live demo](#live-demo)
1. [Built with](#built-with)
1. [Contributing](#contributing)

## Short description

### What's the problem?

Communication and awareness is the hour of the need, people can use this bot and embed in their existing application if they want. In times of crisis like Covid-19 pandemic, communications systems are often overwhelmed with people trying to find basic information about testing, symptoms, community response, and other resources. When communication lines get clogged, people who need real help can't get through.

### How can technology help?

Whether via text, phone, websites, or communication apps, conversing with chatbots and other AI-enabled resources can play a critical role in helping communities quickly understand crucial information and free up customer service resources to focus on higher-level issues.

### The idea

It's imperative that communications systems shouldn't be affected in times of crises, such as the COVID-19 pandemic. Providing a set of open source tools, backed by IBM Cloud and Watson Services, will enable everyone to more easily get statictics/help available about the COVID-19. We will have a AI-Voice Enabled Chatbot that will help answer many queries revolving around COVID-19. 

## Demo video

[![Watch the video](https://github.com/vs28031996/HackIt/blob/master/Video/demo.wmv)](https://github.com/vs28031996/HackIt/blob/master/Video/demo.wmv)

## The architecture

![Architecture](https://developer.ibm.com/developer/tutorials/cfc-starter-kit-speech-to-text-app-example/images/cfc-covid19-remote-education-diagram-2.png)

1. The user navigates to the site and uploads a video file.
2. Watson Speech to Text processes the audio and extracts the text.
3. Watson Translation (optionally) can translate the text to the desired language.
4. The app stores the translated text as a document within Object Storage.

## Long description

[More detail is available here](DESCRIPTION.md)

## Getting started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

## Built with

* [IBM Cloudant](https://cloud.ibm.com/catalog?search=cloudant#search_results) - The NoSQL database used
* [IBM Cloud Functions](https://cloud.ibm.com/catalog?search=cloud%20functions#search_results) - The compute platform for handing logic
* [IBM API Connect](https://cloud.ibm.com/catalog?search=api%20connect#search_results) - The web framework used
* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Authors

* **Vinay Sharma** - [Vinay](https://github.com/vs28031996)
