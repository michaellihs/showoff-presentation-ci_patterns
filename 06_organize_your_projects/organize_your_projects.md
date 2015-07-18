!SLIDE section_slide
# Organize your Projects
## Preperation for Continuous Delivery

!SLIDE
# Keep everything in Version Control
* Configuration
* Testdata
* Continuous Integration Jobs
* Infrastructure Code
* Deployment Scripts
* *[SMELL]* Configuration in database (TS)

!SLIDE
# Environmental Awareness
* Development
* Integration
* Staging
* Production

!SLIDE
# Development Environment
* Maximize log output
* Disable all caching
* Provide production-like environment
  * OS, Packages, Versions...

!SLIDE
# Testing Environment
* Use separate database
  * Don't "override" development data
* Use production context (Flow)
  * Might make things a lot faster

!SLIDE
# Staging Environment
* For customer review
* Stick to production settings
* Remember access restrictions
* `robots.txt` might be a good idea!

!SLIDE
# Production
* Turn off logging
* Enable caches

!SLIDE
# Implementing Environments
* Use `TYPO3_CONTEXT`
* Use environment variables
  * Apache `set_env TYPO3_CONTEXT`
  * CLI `export TYPO3_CONTEXT`
* Include different `Settings` files


!SLIDE section_slide
# Reproducible Environments

!SLIDE
# Prepare for Update and Disaster Recovery
* Use Configuration Management if possible
* At least: Document setup very well

!SLIDE section_slide
# Tasks
## Automate all your Tasks

!SLIDE
# Build Tasks
* Composer
* CSS, JavaScript, Sprites
* Database migrations
* Database import / export

!SLIDE code_slide
# TYPO3 Console

    @@@
    typo3_project_root $ ./typo3cms
