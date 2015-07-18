!SLIDE section_slide
# Deployment
## Ship your Application

!SLIDE
# How to handle User Data
* Independent directory structure for user data
* Separate project files from user data
  * Templates
  * CSS
  * Sprites, Icons...

!SLIDE
# Where to build stuff
* Don't build things on (production) servers
* Use integration server
* Ship as package
* *[SMELL]* git on (production) servers

!SLIDE
# Rollback
* Rollback for files is easy
* Rollback for database is hard
* Prepare for disaster recovery

!SLIDE
# Handling of external services
* Solr needs configuration &amp; restart
* Cache clearing in
  * Varnish
  * Memcached / Redis

!SLIDE
# Recommended Tool
* TYPO3 Surf
* Many best-practices and pre-defined tools for
  * TYPO3
  * Neos
  * Flow

!SLIDE section_slide
# Basic Principles
* "If it hurts, do it more often!"
* *[SMELL]* Checklists are  no deployment strategy
* *[SMELL]* handing over source code to some ops guys: "We build it - you run it!"
