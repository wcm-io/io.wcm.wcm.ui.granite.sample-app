<img src="https://wcm.io/images/favicon-16@2x.png"/> WCM Granite UI Extensions Sample Application
======
[![Build](https://github.com/wcm-io/io.wcm.wcm.ui.granite.sample-app/actions/workflows/maven-build.yml/badge.svg?branch=develop)](https://github.com/wcm-io/io.wcm.wcm.ui.granite.sample-app/actions?query=workflow%3ABuild+branch%3Adevelop)

Sample application / Test pad for Granite UI Components for AEM Touch UI.

Documentation: https://wcm.io/wcm/ui/granite/<br/>
Issues: https://github.com/wcm-io/io.wcm.wcm.ui.granite.sample-app/issues<br/>
Wiki: https://wcm-io.atlassian.net/wiki/<br/>
Continuous Integration: https://github.com/wcm-io/io.wcm.wcm.ui.granite.sample-app/actions<br/>
Commercial support: https://wcm.io/commercial-support.html


Deploy sample project
---------------------

You can use this scripts for a full deployment into local AEM instances.

Deploy to local AEMaaCS SDK instance:

* `build-deploy.sh` -> deploy to author on port 4502
* `build-deploy-publish.sh` -> deploy to publish on port 4503

Deploy to local AEM 6.5 instance:

* `build-deploy_aem65.sh` -> deploy to author on port 45025
* `build-deploy-publish_aem65.sh` -> deploy to publish on port 45035

Deploy to local AEM 6.6 (AEM 6.5 LTS) instance:

* `build-deploy_aem66.sh` -> deploy to author on port 45026
* `build-deploy-publish_aem66.sh` -> deploy to publish on port 45036


Authoring Sample Pages
----------------------

Open the authoring sample pages at<br/>
[http://localhost:4502/content/contextaware-config-sample/en/config.html](http://localhost:4502/editor.html/content/wcmio-graniteui-sample-app/en.html)


System requirements
-------------------

* AEM 6.5.17+, AEM 6.6 or AEMaaCS SDK
* Java 11
