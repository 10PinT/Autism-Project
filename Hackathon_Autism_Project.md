## Autism Project - Biometric Analysis and Response - Hack-athon

### Problem Statement -

People who suffer from Autism want to have a normal quality of life, however what are normal daily tasks / environmental and other events to none autism sufferers are major issues for people who suffer from this invisible mental issue. A lack of investment in social care, means that many people have to try to self heal and handle their activities without supporting systems and intelligence. If technology could provide patients with a non-intrusive monitoring, awareness and alerting service based on information processed by sensors and biometrics, Autism suffers, carers and family can be informed ahead of an issue, and corrective measure could be applied. The volume, variety and veracity of the data to be processed and responded too for a single human is not achievable let alone for 10's 100's of sufferers.


### Overview of Consider Solutions

[Reference User stories](./Data%20Story%20-%20Improve%20Care.md)


### Hack-athon scope

The Hack-athon event will focus on the

##### In-Scope
    - Data Storage in the Cloud
    - Data Processing - Ability to apply a simple query through code
    - Simple Event Trigger based on correlation of data events
    - Event Response through AI (Alexa)

##### Out of scope
    - Connecting to live data streams from devices
    - Multiple AI interfaces
    - Complex analytics Analysis
    - Security


#### Overview

Teams will aim to provide a solution that triggers an Alexa event by the analysis of a set of data held in a cloud ecosystem. The event will be based on the correlation of certain biometric and environmental triggers. (Heart Rate + Room Temperature)

Following a successful pattern match, an Alexa response should be triggered with a

  <b>"Hello World, I believe you need some help"</b>


### Preparation

  - https://www.autism.org.uk/about/behaviour/meltdowns.aspx
  - https://www.bbc.co.uk/news/av/health-44680214/the-watch-that-could-help-manage-severe-autism?SThisFB=


### Tools

  - Code will reside on Public Github under and agreed DXC Repository.
    - Team 1 - https://partner-github.csc.com
    - Team 2 - https://partner-github.csc.com
  - Any AWS service can be used
  - Alexa will be the AI interface


### Data
  - Two Data sets are provided
    1: Biometric from Off the self Personal Device (Fitbit or Other)
    2: Home based Smart Thermo Stat

### Added Credit

If the teams find that they complete the task, they is options to improve, considerations include

  - Create addition a Alexa response, targeting different personas
    - Consider
        - Patient - "Hi Carl, you need to move location"
        - Carers - "Carl is in trouble you need to contact him, it's his Body "
        - Family - " Carl is fine, but could do with you calling him"
  - Consider increase the Data set
    - Noise, Light (this will require creating a simple data set)
      - Noise (db) level measured during the time period
      - Light (Lux) Level measured during the time period