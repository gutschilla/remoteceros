# Remoteceros

Monitor metrics from your app.

# Motivation

Something like a very basic datadog - the custom metrics part. 

# Status

Not even a plan, yet. Base architecture decisions to be made:

- metric gathering and storage   
  - [ ] database decision, where do I store all this
    - aggregates
    - performance vs. reliability vs. consitency
    - **we may lose data**
  - [ ] cluster model
  - [ ] API (bulk REST, single metric UDP)
- dashboards
  - [ ] charts
- events
  - [ ] triggers on metrics
  - [ ] notifications
  
