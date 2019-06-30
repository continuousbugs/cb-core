### What is Continuous Bugs ?
As the name itself depicts, continuous bug is finding software bugs in production enviornmint in realtime as soon as any one user faces.

Vision is to bring set of tools and solutions to achive this common goal.
### How is it related to Continous Integration and Continous Delivery?
We could consider it as next step after CI and CD like CI -> CD -> CB
### How does CB work?
One of the ways we tried(just for now but a lot is coming) to achive CB is by creating simple alerts(not Machine learning ones yet) from prodction application logs. Kind of sending alerts to the one who commited that peice of code. 
### Is it really possible to catch all bugs in production in realtime?
May be not 100%, but definitely possible to catch bugs before hundred's of users face the same bug and complain in social media.
### What are current available solutions?
Current solution is built using following technology stack. these are completely open source and free to use. This soultion can be built by any one by installing and integrating these tools as shown in sequence diagram.

[Apache Kafka](https://kafka.apache.org "Apache Kafka")

[Apache Samza](http://samza.apache.org "Apache Samza")

[Apache Druid](https://druid.apache.org "Apache Druid")

[Apache Superset](https://superset.apache.org "Apache Superset")

#### Sequence Diagram

![](https://github.com/vishmalipatil/cb-core/blob/master/cb_sequence_diagram.svg)

### Roadmap
- Simple one click installable and easily scalable solution using Kubernates.
- Machine Learning based Alerts


![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)

**Working on your first Pull Request?** You can learn how from this *free* series [How to Contribute to an Open Source Project on GitHub](https://egghead.io/series/how-to-contribute-to-an-open-source-project-on-github)
