DevOpsMaturity
==============

 

 

 

 

 

 

 

 

This will be a combination of maturity models to be mapped against CMMI V2

 

 

 

 

 

 

 

 

 

| Area       | ID  | Initial level (1)                                                           | Repeatable level (2)                                                         | Defined level (3)                                                                           | Managed level (4)                                                                                    | Oprimised level (5)                                                                                           |
|------------|-----|-----------------------------------------------------------------------------|------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------|
| Technology | T1  | Environments are provisioned manually                                       | All environments configurations are externalised and versioned               | Virtualisation used if applicable (automated builds)                                        | All environments managed efficiently                                                                 | Environment provisioned fully automated                                                                       |
|            | T2  | Manual tests or minimal automation                                          | Funtional test automation                                                    | Triggered automated tests                                                                   | Smoked tests and dashboard shared with Operational Team                                              | Choas Monkey                                                                                                  |
|            | T3  | Data migration unversioned and performed manually                           | Changes to DB done with automated scripts versioned with application         | DB changes performed automatically as part of deployment process                            | DB upgrades and rollbacks tested with every deployment                                               | Feedback from DB performed after each release                                                                 |
|            | T4  | Manual deployment                                                           | Build automation                                                             | Non-production deployment automation                                                        | Production deployment automation                                                                     | Ops teams and Dev teams regularly collaborate to manage risks and reduce cycle time                           |
|            | T5  | Manual processes for building software/No artefact versioning               | Regular automated build and testing. Any builds can be recreated from source | Automated build and test cycle every time a change is committed                             | Build metrics gathered, made visible and taken into account                                          | Continuous work on process improvement, better visibility, faster feedback                                    |
|            | T6  | No collaboration tools                                                      | Project Planning Tool                                                        | Team / Toolset Integration                                                                  | Knowledge management tool                                                                            |                                                                                                               |
|            | T7  | No software configuration management (SCM)                                  | Standardised SCM                                                             | Configuration is delivered with code                                                        | Self-healing tools                                                                                   |                                                                                                               |
|            | T8  | No or minimal monitoring                                                    | Core monitoring                                                              | Integrated monitoring                                                                       | Analytics / Intelligence                                                                             |                                                                                                               |
|            | T9  | No tools or minimal tools used for issue tracking                           | All issues and bug reports are tracked                                       | Issue reporting automation and monitoring                                                   | Activities based on received feedback and data                                                       | Continuous delivery process                                                                                   |
| Process    | PR1 | Inconsistent delivery process                                               | Scheduled delivery process                                                   | Automated delivery process                                                                  | Frequent delivery process                                                                            | Development process integrated with Lean Six Sigma                                                            |
|            | PR2 | Ad-hoc development                                                          | Scrum Development                                                            | Agile Development                                                                           | Lean Development                                                                                     | Continuous Testing                                                                                            |
|            | PR3 | Ad-hoc testing                                                              | Requirements based testing                                                   | Integrated testing                                                                          | Quantitative testing                                                                                 | Organised performance management                                                                              |
|            | PR4 | Inconsistent project management                                             | Project & requirements management                                            | Integrated project management                                                               | Quantitative project management                                                                      |                                                                                                               |
|            | PR5 | Deployment and development documentation is not available or is out of date | Development documentation and relevant configuration files are up to date    | Regular validation of the documentation and related configuration descriptions are provided | Documentation process and structure update based on gathered experience and quality requirements     |                                                                                                               |
|            | PR6 | Uncontrolled or reactive processes (not applied management)                 | Processes are managed but not standardised                                   | Processes are standardised across the organisation                                          | Visibility and predictability of entire process & performance                                        | Highly optimised and integrated processes                                                                     |
| People     | P1  | Teams organised around skillsets                                            | Teams organised around deliveries                                            | Teams organised around projects                                                             | Teams organised around products/business lines                                                       | Interdisciplinary teams organised around KPis                                                                 |
|            | P2  | Ad-hoc learning                                                             | Team learning                                                                | Value stream learning                                                                       | X-process learning                                                                                   | External learning                                                                                             |
|            | P3  | Ad-hoc approach regarding competency development                            | Competences are developed with the help of training and development          | Analysis of existing competencies and future development                                    | Mentor usage                                                                                         | Continuous capability improvement                                                                             |
| Culture    | C1  | Restricted communication                                                    | Rapid intra-team (inside) communication                                      | Rapid communication between teams (inter teams)                                             | Frequent collaborative communication                                                                 | Rapid Feedback                                                                                                |
|            | C2  | Uncommunicated vision                                                       | Clear delivery requirements                                                  | Clear project requirements                                                                  | Clear product/business line requirements                                                             | Clear organisational requirements                                                                             |
|            | C3  | Lack of awareness as to how culture is impacting day-to-day business        | Aware of aspects in culture that may help or hinder day-to-day business      | Cultural traits that supported business strategies have been identified                     | Culture viewed as an asset to be managed                                                             | Desired elements of the culture are identified, ingrained and sustainable for creating “the way we work here" |
|            | C4  | Poor, ad-hoc communication                                                  | Managed communication                                                        | Active collaboration                                                                        | Collaboration based on process measurement, which allows to identify bottlenecks and insufficiencies |                                                                                                               |
|            | C5  | Sub-innovation / no innovation                                              |                                                                              |                                                                                             |                                                                                                      |                                                                                                               |
