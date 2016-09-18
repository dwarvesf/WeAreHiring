# Technology

We believe that using technology in appropriate way will help to boost up productivity and make our life better in many aspects. We persue the path of modern technology where we invest a lot of time in new techs and how to apply them to our products.

Having a team of strong engineering culture and product mindset, we use the cutting edge technologies to maximize the product outcome. As a time of writing down, we have

- Go and Elixir for backend development. Where Go is the greatest for API development and Elixir still a potential candidate to replace Ruby on Rails. They're both concurrency language which implemented Actor Model and Reader-Writer Synchonized.
- Native mobile development with Functional Reactive Programming in Android and iOS using RxJava and RxSwift. Cross platfrom technology is still something good for startup but when you want to dig deeper in term of device components or sensors, application performance improvement and so on.
- All the codebase is well-tested. We want everything should be stable and good enough before release date.
- Automation Process with Docker Container-centric workflow
    + We apply Gitflow and Kanban for product development.
    + We apply CI/CD workflow in [DC/OS](dcos.io) platform. (mesos and marathon) Everytime when the feature is reviewed and approved, it will be tested automatically using Gitlab CI. Then that success version will be pushed into our private Docker Registry. When time comes and the branch master is ready to deploy, Gitlab CI will help to trigger marathon to pull and install the new version.

With those toolset, our development process is boosted up a lot and it's really interesting for developers. We gained some compliments from friends and customers.
