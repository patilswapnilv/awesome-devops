# awesome-devops
Awesome resources for DevOps

What is DevOps?
---------------

DevOps is a culture, movement, or practise that emphasises the collaboration and communication of both software developers and other information technology (IT) professionals while automating the process of software delivery and infrastructure changes. DevOps is a clipped compound of "development" and "operations." 
[Wikipedia](https://en.wikipedia.org/wiki/DevOps)

Index
-----

-	[Culture](#culture)
-	[Process](#process)
-	[Technology](#technology)
-	[Security](#security)
-	[Tools](#tools)
-	[Misc](#misc)

Culture
-------

-	[DevOps Culture](https://www.atlassian.com/devops/what-is-devops/devops-culture)
-	[Conway's Law](https://en.wikipedia.org/wiki/Conway%27s_law) - States that organisations will tend to produce systems that mirror their communication structures
-	[What security experts need to know about DevOps and continuous delivery](#) - Info and benefits for Security and DevOps teams working together
-	DevOps and the Myth of Efficiency [Part 1](http://blog.christianposta.com/devops/devops-and-the-myth-of-efficiency-part-i/) & [Part 2](http://blog.christianposta.com/devops/devops-and-the-myth-of-efficiency-part-ii/) - Complex vs Complicated and Efficiency - DevOps for Enterprise
-   [Who drives culture in DevOps?](https://opensource.com/article/17/12/who-drives-culture-devops)

Process
-------

-	[Choosing Design over Architecture](https://18f.gsa.gov/2015/11/17/choose-design-over-architecture/) - Starting from user stories and user experience
-	[Incident postmortem best pratices](https://www.datadoghq.com/blog/incident-postmortem-process-best-practices//)

### Project Management

-	[Organizing GitHub issues](https://robinpowered.com/blog/best-practice-system-for-organizing-and-tagging-github-issues/) - One (of many) approaches to managing and tagging Github issues
-	[Release Ready Teams](https://www.atlassian.com/agile/release-ready-agile-teams) - An infographic showing the how Atlassian's agile teams release early and often
-	[Using Kanban over Scrum](https://medium.com/cto-school/ditching-scrum-for-kanban-the-best-decision-we-ve-made-as-a-team-cd1167014a6f#.p8a1zicwm) - A useful post on the benefits of Kanban over Scrum (but not always relevant for every team)

### Mapping

-	[Wardley Mapping](http://blog.gardeviance.org/2015/02/an-introduction-to-wardley-value-chain.html) - An introduction to Value Chain Mapping to help understand the "Why" for organisations and Devops Teams.

### Automation

### Quality

### Open Source

-	[Making Your Open Source Project Newcomer-friendly](http://manishearth.github.io/blog/2016/01/03/making-your-open-source-project-newcomer-friendly/)

Technology
----------

-	[Basic Infrastructure Patterns](https://www.thoughtworks.com/talks/infrastructure-design-patterns-xconf-eu-2017) - Basic patterns seen while working on build/CI/deployment technology
-	[Infrastructure as Code](http://martinfowler.com/bliki/InfrastructureAsCode.html) - the approach to defining infrastructure through code that can then be treated just like any software

### Containers

-	[The Curious Case of Linux Containers](https://medium.com/@sumbry/the-curious-case-of-linux-containers-328e2adc12a2#.j1hbq72im) - A Blog Post discussing real issues of deploying containers across distributed systems.
-	[The Oncoming Train of Enterprise Container Deployments](http://www.juliandunn.net/2015/12/04/the-oncoming-train-of-enterprise-container-deployments/) - Blog summary of containers and a few antipatterns.
-	[DevOps, Containers & Microservices: Separating the hype from the reality](http://www.slideshare.net/dberkholz/devops-containers-microservices-separating-the-hype-from-the-reality) - A presentation outlining a future of how to build and deploy applications to generate business value.
-	[Tectonic Summit Videos](https://www.youtube.com/playlist?list=PLlh6TqkU8kg_Eydfk1Nyt6iK7wM8v9bRA) - A YouTube playlist of Container and DevOps presentationss from the Tectonic Summit in December 2015
- [A Practical Introduction to Container Terminology](https://developers.redhat.com/blog/2018/02/22/container-terminology-practical-introduction) - It's crucial to understand the terminology used while discussing a containerization design.

### Operating Systems

-	[The Art of Command Line](https://github.com/jlevy/the-art-of-command-line) - A guide on the Command Line for beginners and the experienced

### Cloud

-	[Infrastructure as Database](https://blog.solvaria.com/infrastructure-as-code) - Is infrastructure more like a DB than code?

### Microservices

### Security

-	[You Wouldn't Base64 a Password - Cryptography Decoded](https://paragonie.com/blog/2015/08/you-wouldnt-base64-a-password-cryptography-decoded) - A primer on Cryptography for Developers
-	[How to Protect Your Infrastructure Against the Basic Attacker](https://www.mailgun.com/blog/it-and-engineering/security-guide-basic-infrastructure-security/) - A good outline of important security configurations in Linux based systems

- [Network Infrastructure
Security Guide by National Security Agency
Cybersecurity USA ](https://media.defense.gov/2022/Jun/15/2003018261/-1/-1/0/CTR_NSA_NETWORK_INFRASTRUCTURE_SECURITY_GUIDE_20220615.PDF)


Tools
-----

### Containers

-	[Docker](https://www.docker.com/) - The tool that kickstarted the modern container movement
-	[rkt](https://coreos.com/rkt/docs/latest/) - An alternative container runtime and spec by the team at CoreOS

### Operating Systems

-	[RancherOS](https://rancher.com) - Another small container OS where the entire OS is containerized.


### Cluster Managers

-	[Kubernetes](https://kubernetes.io)
-	[Nomad](https://www.nomadproject.io/)
-	[Mesos](https://mesos.apache.org/)
-	[Swarm](https://docs.docker.com/swarm/)

### Source Control

-	[Git](https://git-scm.com/) - The most popular distributed version control system.
-	[Mercurial](https://www.mercurial-scm.org/)
-	[Github](https://github.com/) - Git repo hosting as a Service
-	[Gitlab](https://about.gitlab.com/) - Self-hosted Git repos

### Configuration Management

-	[Ansible](http://www.ansible.com/)
-	[Chef](https://www.chef.io/)
-	[Puppet](https://puppetlabs.com/)


### Continuous Integration & Deployment

-	[Jenkins](https://www.jenkins.io/)
-	[Buildkite](https://buildkite.com/)
-	[Drone](https://github.com/drone)
-	[Travis](https://www.travis-ci.com/)
-	[Gitlab CI](https://about.gitlab.com/)

### Incident Management

- [PagerTree](https://pagertree.com/)
- [OpsGenie](https://www.atlassian.com/software/opsgenie)
- [PagerDuty](https://www.pagerduty.com/)

### DevOps as a Service 

- [Cloud 66](https://www.cloud66.com/) - DevOps as a service that helps to build, deploy and manage any application on any cloud or server

Misc
----

-	[Awesome Lists](https://github.com/sindresorhus/awesome) - A list of Awesome lists (very meta!)
-	[DevOps Weekly](http://www.devopsweekly.com/) - A weekly mailing list with interesting DevOps related News and Tools
-	[The Phoenix Project](http://www.amazon.com/Phoenix-Project-DevOps-Helping-Business/dp/0988262509/ref=sr_1_1?ie=UTF8&qid=1451900824&sr=8-1&keywords=project+phoenix) - A Novel about IT, DevOps, and Helping Your Business Win
-   [DevOps'ish](https://devopsish.com/) - A newsletter focused on People, Process, and Tools in the DevOps, Cloud Native, and Open Source spaces.
-   [Last week in AWS](https://www.lastweekinaws.com/) Keep up with AWS announcements
-   [The New Stack](https://thenewstack.io/) Context and explanation of at-scale technologies to advance knowledge 
-   [Google Cloud Platfrom Blog](https://cloud.google.com/blog/products/gcp) This can be a reliable source of vendor-neutral information due to the fact that it is a product blog that covers "product updates, customer tales, and tips & techniques on Google Cloud Platform." If you use the GCP, it's a must-read; if not, it's a good idea to read.
-   The [DevOps Dispatch](https://devopsdispatch.com/) is a weekly, curated by fellow DevOps protagonist Matty Straton.

