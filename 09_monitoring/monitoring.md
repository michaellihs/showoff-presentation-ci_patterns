!SLIDE section_slide
# Monitoring TYPO3 Applications
## Check the Heartbeat of your Application

!SLIDE
# Profiling vs. Monitoring
* Profiling is analyzing single requests
  * Mostly during development
* Monitoring is an aggregated view on your application
  * Mostly during operations

!SLIDE
# Monitoring Task Examples
* Is the homepage showing
* Does the FE user login work
* Does the search work
* Is the tt_news ticker showing some news
* Are there any severe log entries

!SLIDE
# How to implement<br> Monitoring Tasks
* Use rock solid technology
  * Selenium is fragile!
* Use Jenkins as a task runner
* Send emails or IM messages to developers
* Set up dashboards

!SLIDE
# Third-party Applications
* gtmetrix for page speed
* NewRelic for full stack monitoring / profiling
* Gatling for performance testing

!SLIDE
# Logfile management
* Log files provide a valuable source of information
* Often scattered all over the system
* Use logfile management tools like
  * Logstash / Heka
  * ElasticSearch
  * Kibana
