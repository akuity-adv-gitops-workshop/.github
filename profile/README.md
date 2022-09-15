ArgoCon 2022 Workshop By [Akuity](https://akuity.io/)
----------------------------------------------

Welcome, everyone! This workshop is provided by [Akuity](https://akuity.io/) and focuses on best practices for automatic DevOps tasks using GitOps and Argo CD.

<a href="https://docs.google.com/presentation/d/1bH9tSlhQDBL0Phgp1F-dRt1eVMo6MryTEx1YsTJgTTI/edit?usp=sharing">
<img src="images/logo.png" alt="Logo"/>
</a>

[Presentation](https://docs.google.com/presentation/d/1bH9tSlhQDBL0Phgp1F-dRt1eVMo6MryTEx1YsTJgTTI/edit?usp=sharing)

During the webinar, we will cover the following topics:

* **GitOps As A Service** - How to setup and manage shared Argo CD instance that is used by multiple teams.
* **Automated Changes Promotion** - Save developers time by leveraging CI to automate image tags updates and leverage rendered manifests to improve tracability.
* **Improve Developers Quality of Life** - Make developers happy by providing them with notifications and secrets management.
* **Beyond Application Development** Application developers are not the only GitOps users. Let's learn how help operators who manage clusters at scale.

As you can see, this workshop assumes some basic knowledge of Argo CD, GitOps, and Kubernetes. So we are not going through the basic steps of Argo CD installation and configuration and will jump right into a bit more advanced topics.

However, we are still going to start from scratch and set up an Argo CD instance. To save time, I'm going to use https://akuity.cloud/. Let's
provision an instance and define the basic configuration. We just going to setup SSO integration and connect a single cluster.

The more advanced configuration such as RBAC and multi-tenancy we are going manage together using GitOps. Visit https://github.com/argocon2022-workshop/control-plane to get stared.