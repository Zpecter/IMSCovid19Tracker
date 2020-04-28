# IMS COVID-19
This is a simple COVID-19 mobile app available for iOS and Android

![App Images](Assets/app.jpg)

# Installation

Open the following links from your phone to install the app:
- **iOS (from v12.4)**: https://install.appcenter.ms/orgs/imsmaxims/apps/ims-covid-19-tracker-ios/distribution_groups/allpublic
- **Android (from v5)**: https://install.appcenter.ms/orgs/imsmaxims/apps/ims-covid-19-tracker-android/distribution_groups/allpublic
[Click here to install the App](https://appcenter.ms/orgs/imsmaxims/applications)

You should now be able to download the app directly onto your mobile

# Release Notes
  - **1.0.0** - First Release
  - **1.0.1** 
    - Fix bug where query for U.S.A provinces were incomplete
    - Change Death icon to something more sensitive
  - **1.0.2** 
    - Added auto-complete on search page
    - Fix bug in country search
  - **2.0.0** 
    - Include dynamic versioning in About page
    - Make main page country panels as editable widgets
  - **2.0.1** 
    - Fix collection bug on refresh
  - **2.0.2** 
    - Fix bug where widget values do not update properly
  - **2.0.3** 
    - Swipe left in a widget to display it bigger in a second page
    - Reset search criteria when leaving Search Page
  - **2.0.4** 
    - Bug fix where search box would crash app sometimes
  - **2.0.5** 
    - Fix small flickering when poping a page (Android only)
  - **2.1.0** 
    - More data and statistics being displayed
    - Added Donut Chart and Bar Chart on Widget Detail view
    - Added small tutorial toast to explain widget usage
    - Add "help" button to display widget tutorial
    - Add Sources information in the About page
    - Get total population, population per country and new calculation on deaths per million
  - **2.1.1** 
    - Fix bug where the population for US is wrong
  - **2.1.2** 
    - Fix population bugs and improve population by country API.
  - **2.1.3** 
    - Change country population API.
  - **2.2.0** 
    - Overall UI clean up and performance improvements.
    - Small country widgets are bigger and now have slide indicators and the country flag.
    - Got rid of third party country info/covid APIs and created new web scraper APIs
    - Remove web scraping code from Mobile sources and move it to a Web API server deployed in Azure.


# License
IMS COVID-19 is MIT Licensed