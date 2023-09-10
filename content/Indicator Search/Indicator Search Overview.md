![[Indicator Search/Images/logo.png]]

* Demo: [indicatorsearch.app](https://indicatorsearch.app) 
* Github Repo: [Indicator-Search](https://github.com/rc-austinoneil/Indicator-Search)
* Project Readme: [[Readme]]

Security incidents are a common occurrence. When these incidents happen, security analysts need a fast and reliable tool to enrich indicators (observables) across various open-source intelligence (OSINT) sites. That's where Indicator Search comes in.

Indicator Search is a project that I have been developing for the last few months. The original goal was to just learn the FastAPI framework as a weekend ordeal and it blossomed into a whole lot more. This project has taught me a lot about web app development which is new to me since I've been in a Detection Engineering / SOC role for the last few years.

One of the problems I've faced in my working career so far is the lack of enrichment in security telemetry from an analyst perspective and it requires the need to pivot to multiple tools to inquire additional details about an IP/Hash or domain.

It can be a massive time saver to the analysis process to add an enrichment source to your detection pipeline. Doing so gives the security analyst additional context about indicators found in the alert and saves the analyst from having to do all the leg work themselves.

Using enrichment also enables you to make security detection & response decisions in your SOAR platform based on indicators OSINT results.

I have built over 20 tools into the initial build of the application with plans to add more as time goes on.
I've also added the ability to search public threatfeed lists and the ability to IOC an indicator. IOCing an indicator in the app allows you to retrieve the IOC list over the API which in turn enables other tools to benefit from search results.    

If you are unable to add an enrichment source into your detection pipeline and if you don't have a SOAR platform, Indicator Search still provides analysts a web app to perform searches and view results in an aggregated view.

What started as a weekend learning project turned into a fun couple of months, I'm excited to continue building on this one.

Check out the [[Readme|readme]] to learn how to set it up!

![[home.png]]