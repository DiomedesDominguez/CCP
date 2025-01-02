# CCP
Core Control Performance is a simple repository I decided to create to track measures of performance and others KPIs for using third party controls in dotnet.
At the moment of writing, I’ll compare DevExpress, Syncfusion and Telerik.

## Metrics
To compare apples to apples, I will try to keep everything as simple as possible. I'm open to better suggestions.
- Bare Size: have a project for library with the same dependencies except for the ones particular needed for each company’s library. I don’t even know if what I said make sense. Sorry for any caused confusion. Basically, I’ll try to have a project folder for each library’s project and just measure its size to know if any particular library is bigger than other.
- Dev RAM/CPU Size: how much RAM and CPU is needed to run the project in a dev environment.
- RAM/CPU Size: how much RAM and CPU is needed to run the project in release mode.

