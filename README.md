<p align="center">
  <a href="" rel="noopener">
 <img src="./public/images/brands/Brand.png" alt="ANA &bull; Assistant to Normalize Activities"></a>
</p>
<h3 align="center">ANA &bull; Assistant to Normalize Activities</h3>

<div align="center">

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

</div>

---

<p align="center"> Few lines describing your project.
    <br> 
</p>

## 📝 Table of Contents

- [Challenge](#challenge)
- [Problem Statement](#problem_statement)
- [Idea / Solution](#idea)
- [Roadmap](#future_scope)
- [Technology Stack](#tech_stack)
- [Authors](#authors)
- [Acknowledgments](#acknowledgments)

## 🧐 Challenge <a name = "challenge"></a>

Mitigate the impact of COVID-19 and climate change by creating sustainable solutions using open source technology. Get the details on the 2020 Call for Code Global Challenge, understand its two tracks, and start building today.

## 🧐 Problem Statement <a name = "problem_statement"></a>

According to psychoanalyst Maria Francisca Mauro, more than 100 days of quarantine, leaving to do the minimum necessary, brought us anguish, fear, uncertainty and many other feelings. However, now that the new measures to reopen commerce and other establishments are scheduled, the idea of ​​leaving home is not that simple. “Many feel fearful about the risk of contamination of themselves or someone in the family, since some share the home with people most vulnerable to COVID-19's clinical complications.

In order for people to return to their activities safely, several health protocols were created for each type of establishment. However, protocols are often long and tiring to read, which may not be effective in keeping people safe and reassured.

## 💡 Idea / Solution <a name = "idea"></a>

Thinking of helping everyone involved in this resumption of activities in a safe way, our team developed the Assistant to Normalize the Activities solution, ANA our assistant capable of analyzing the user's audio in a few seconds to check which procedure to take in relation to that information based on based on local, regional, national and global health protocols, informing and keeping the user safe quickly and easily.
ANA will also analyze the emotional traits of the user's audio which will allow their artificial intelligence to initiate a dialogue to calm the user in case he needs it, keeping him and the others in the same place safely.

## 🚀 Roadmap <a name = "future_scope"></a>

![Roadmap](./public/images/readme/Roadmap.png)

## ⛏️ Built With <a name = "tech_stack"></a>

- [Figma](https://figma.com/) &bull; Design/UI
- [NodeJs](https://nodejs.org/) &bull; Back-End
- [ReactJS](https://reactjs.org/) &bull; Front-End
- [Node-RED](https://nodered.org/) &bull; Back-End
- [Watson Assistant](https://www.ibm.com/cloud/watson-assistant/) &bull; IBM Cloud Service #2

## ✍️ Team <a name = "authors"></a>

- [Alberthy](https://www.linkedin.com/in/alberthycoelho/) &bull; UX Designer
- [Antonio Carlos](https://www.linkedin.com/in/antonio-carlos149376b8/) &bull; Back-End
- [Esaú Morais](https://linkedin.com/in/emmorais) &bull; Front-End
- [Felipe Candian](https://www.linkedin.com/in/felipecandian/) &bull; UI/Motion Designer
- [Rodrigo Temóteo](https://www.linkedin.com/in/rodrigo-de-ara%C3%BAjo-tem%C3%B3teo-42020317/) &bull; Business

## 🎉 Acknowledgments <a name = "acknowledgments"></a>

- [IBM](https://ibm.com)
  - [IBM Cloud](https://cloud.ibm.com) Services
  - [Sérgio Gama](https://www.linkedin.com/in/sergiogama) overview and helping
- [Shawee](https://shawee.io)

Node-RED IBM Cloud Starter Application
====================================


### Node-RED on IBM Cloud

This repository is an example Node-RED application that can be deployed into
IBM Cloud with only a couple clicks. Try it out for yourself right now by clicking:

[![Deploy to IBM Cloud](https://cloud.ibm.com/devops/setup/deploy/button.png)](https://bluemix.net/deploy?repository=https://github.com/ibm/node-red-app)

### How does this work?

When you click the button, you are taken to IBM Cloud where you get a pick a name
for your application at which point the platform takes over, grabs the code from
this repository and gets it deployed.

It will automatically create an instance of the Cloudant service and bind it to
your app. This is where your Node-RED instance will store its data.

When you first access the application, you'll be asked to set some security options
to ensure your flow editor remains secure from unauthorised access.

It includes a set of default flows that are automatically deployed the first time
Node-RED runs.

### Customising Node-RED

This repository is here to be cloned, modified and re-used to allow anyone create
their own Node-RED based application that can be quickly deployed to IBM Cloud.

The default flows are stored in the `defaults` directory in the file called `flow.json`.
When the application is first started, this flow is copied to the attached Cloudant
instance. When a change is deployed from the editor, the version in cloudant will
be updated - not this file.

The web content you get when you go to the application's URL is stored under the
`public` directory.

Additional nodes can be added to the `package.json` file and all other Node-RED
configuration settings can be set in `bluemix-settings.js`.

If you do clone this repository, make sure you update this `README.md` file to point
the `Deploy to IBM Cloud` button at your repository.

If you want to change the name of the Cloudant instance that gets created, the memory
allocated to the application or other deploy-time options, have a look in `manifest.yml`.

### Environment Variables

The following environment variables can be used to configure the application:

 - `NODE_RED_STORAGE_NAME` - the Cloudant service name as exposed in `VCAP_SERVICES`
 - `NODE_RED_STORAGE_DB_NAME` - the name of the database to use on Cloudant
 - `NODE_RED_STORAGE_APP_NAME` - the prefix used in document names, allowing multiple instances
    to share the same database.
 - `NODE_RED_USERNAME`, `NODE_RED_PASSWORD` - if set, used to secure the editor
 - `NODE_RED_GUEST_ACCESS` - if the editor is secured, this will allow anonymous,
    read-only access
 - `NODE_RED_USE_APPMETRICS` - enables the appmetrics dashboard
