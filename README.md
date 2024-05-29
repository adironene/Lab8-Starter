# Lab8-Starter

Name: Phoebe Tang
> How are graceful degradation and service workers related?
Service workers help achieve graceful degradation by ensuring that a web application remains functional even during unexpected situations like network being down or slow connections. This ties closely with graceful degradation's concept of the software still working even when features are "stripped." When we cache resources, we reduce load times, which gives us a basic responsive experience. Also, when resources can't be fetched due to network, our application is still usable, just without fancy features. When we have the service workers set up, we are still able to use `fetch()`, even if there's no internet, which directly shows the principles of graceful degradation.

> Screenshot
> ![image](pwa.png)