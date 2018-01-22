# Kubernetes on AWS Users

If you are using Kubernetes on AWS, please [participate in our Kubernetes on AWS user survey](https://docs.google.com/a/zalando.de/forms/d/e/1FAIpQLScrZkcCP8lfAuxZcWOzEmAIP0XCO5PtnfJbU0lFLx8D2-EdNg/viewform)
to help us compile a public list of Kubernetes on AWS users.

The survey results (list of organizations) will be published in the next section.

## Form Responses

The following companies/organizations filled out [the Google form](https://docs.google.com/a/zalando.de/forms/d/e/1FAIpQLScrZkcCP8lfAuxZcWOzEmAIP0XCO5PtnfJbU0lFLx8D2-EdNg/viewform) so far (sorted alphabetically):

<!-- TABLE_START -->
| Organization | Workload (K8s on AWS) | Provisioning | More Info | Location |
|---|---|---|---|---|
| [AOE](https://aoe.com) | dev/test/staging | kops |  | Wiesbaden, Germany |
| [Applatix, Inc.](https://www.applatix.com) | dev/test/staging | kube-up | Yes. See [applatix.com/blog/](https://applatix.com/blog/) for various articles on our internal use | Sunnyvale, California. |
| [ArchDaily](http://www.archdaily.com) | critical business apps | kops |  | Santiago, Chile |
| [Athlinks](https://www.athlinks.com) | critical business apps | kubeadm, Terraform | [twitter.com/ryanckoch/status/768933690298609665](https://twitter.com/ryanckoch/status/768933690298609665) [prezi.com/goiqe5_2u7lg/not-all-who-wander-are-lost-our-journey-to-kubernetes/](https://prezi.com/goiqe5_2u7lg/not-all-who-wander-are-lost-our-journey-to-kubernetes/) | Louisville, CO |
| [Atlassian](http://www.atlassian.com) | internal/non-critical apps | Custom Terraform | [legacy-developer.atlassian.com/blog/2017/07/kubernetes-infra-on-aws/](https://legacy-developer.atlassian.com/blog/2017/07/kubernetes-infra-on-aws/) [legacy-developer.atlassian.com/blog/2017/07/kubetoken/](https://legacy-developer.atlassian.com/blog/2017/07/kubetoken/) [legacy-developer.atlassian.com/blog/2017/07/kubernetes-workflow/](https://legacy-developer.atlassian.com/blog/2017/07/kubernetes-workflow/) | Sydney, Australia |
| [Base CRM](https://lab.getbase.com/) | critical business apps | kops |  | Kraków, Poland |
| [Bitnami](https://bitnami.com/) | critical business apps | kops | [bitn.am/2p25cF3](http://bitn.am/2p25cF3) [bitnami.com/kubernetes](https://bitnami.com/kubernetes) [docs.bitnami.com/kubernetes/](https://docs.bitnami.com/kubernetes/) | San Francisco, CA |
| [Box](http://www.box.com) | proof of concept | kops |  | Redwood City, CA |
| [ChatWork](https://www.chatwork.com/) | critical business apps | kube-aws | // All the contents are written in Japanese [blog-ja.chatwork.com/2017/06/chatworkaws-dev-day.html](http://blog-ja.chatwork.com/2017/06/chatworkaws-dev-day.html) [www.slideshare.net/mumoshu/from-dev-to-prod-kubernetes-on-aws-short-ver](https://www.slideshare.net/mumoshu/from-dev-to-prod-kubernetes-on-aws-short-ver) [itpro.nikkeibp.co.jp/atcl/column/14/346926/092100643/](http://itpro.nikkeibp.co.jp/atcl/column/14/346926/092100643/) | Tokyo, Japan |
| [Checkr](http://checkr.com) | critical business apps | kube-aws | [github.com/checkr/codeflow](https://github.com/checkr/codeflow) | San Francisco, CA |
| [Clarifai, Inc.](https://clarifai.com) | critical business apps | Custom Ansible for GPUs + CoreOS | [blog.clarifai.com/how-to-scale-your-gpu-cloud-infrastructure-with-kubernetes/](http://blog.clarifai.com/how-to-scale-your-gpu-cloud-infrastructure-with-kubernetes/) | New York City (HQ), San Francisco |
| [cloudkite.io](https://cloudkite.io) | critical business apps | kops | We're building some tools which will be open source within 6 months. | Austin, TX |
| [CodeValue](http://www.codevalue.net) | critical business apps | kops |  | Israel |
| [Contentful](https://www.contentful.com) | critical business apps | kops | [www.slideshare.net/AnthonyStanton/aws-kubernetes](https://www.slideshare.net/AnthonyStanton/aws-kubernetes) | Berlin, Germany |
| [Crestle](https://www.crestle.com) | critical business apps | kops |  | San Francisco, USA |
| [Crowdfire Inc](https://crowdfireapp.com) | critical business apps | kops, Custom Terraform+Ansible |  | Mumbai, India |
| [Databricks](http://databricks.com) | critical business apps | Custom Cloud Formation + CoreOS | We are running a very large fraction of our production infrastructure, user- and customer- facing, on Kubernetes. We are currently split across multiple Kubernetes clusters running 50+ nodes Kubernetes nodes (totaling over 500 cores and 5TB of memory) with hundreds of services deployed (Kubernetes Deployments). We have done significant customization on the security front; setting up workers in different subnets behind distinct NATs, authorizing certain pods to assume particular AWS IAM roles, and a Google Groups-based ACL setup to give teams access only to their own namespaces. All new services are deployed in Kubernetes and we are currently in the process of migrating our remaining services over. Additionally, we hope to expand the reach of Kubernetes to tens more datacenters by the end of the year, and develop or use whatever tooling necessary to allow engineers to develop and deploy their software across these clusters. | San Fransisco |
| [DB Schenker](https://www.dbschenker.com/) | critical business apps | Terraform + Ansible | Not yet, sorry | Essen, Germany |
| [Descomplica](https://descomplica.com.br) | critical business apps | kube-aws | [danielfm.me/posts/five-months-of-kubernetes.html](http://danielfm.me/posts/five-months-of-kubernetes.html) | Rio de Janeiro, Brazil |
| [Deutsche Börse Group](http://deutsche-boerse.com) | proof of concept | kops |  | Prague, Czech Republic / Frankfurt, Germany |
| [Ekino](http://www.ekino.com) | dev/test/staging | kops, Cloudformation / Troposphere |  | France |
| [Encompass Corporation](https://www.encompasscorporation.com/) | proof of concept | kops | [icicimov.github.io/blog/virtualization/Kubernetes-Cluster-in-AWS-with-Kops/](https://icicimov.github.io/blog/virtualization/Kubernetes-Cluster-in-AWS-with-Kops/) | Sydney, Australia |
| [Engine Yard](http://engineyard.com) | critical business apps | new product | Coming soon | San Francisco, CA |
| [Exaring AG](http://waipu.tv) | critical business apps | kops, Home build solution |  | München, Karlsruhe, Berlin |
| [FarmLogs](http://farmlogs.com) | critical business apps | Custom Cloud Formation + CoreOS |  | Ann Arbor, Michigan |
| [Flixbus](https://www.flixbus.com) | critical business apps | Puppet |  | Berlin, Germany |
| [freee K.K.](https://corp.freee.co.jp/) | proof of concept | kube-aws |  | Tokyo, Japan |
| [HBO](https://play.hbogo.com/) | critical business apps | CoreOS + Custom Terraform | [www.youtube.com/watch?v=7skInj_vqN0](https://www.youtube.com/watch?v=7skInj_vqN0) |  |
| [Hiya, Inc.](https://hiya.com) | critical business apps | Custom Cloud Formation + CoreOS | high-level talk at KubeCon 2016: [www.youtube.com/watch?v=xkSYOtPxH_Q](https://www.youtube.com/watch?v=xkSYOtPxH_Q) | Seattle, USA |
| [Honestbee](https://honestbee.com) | critical business apps | tack (Terraform + CoreOS) | [speakerdeck.com/so0k/kubernetes-and-helm-tech-talk](https://speakerdeck.com/so0k/kubernetes-and-helm-tech-talk) | Singapore, Singapore |
| [immmr GmbH](http://www.immmr.com) | critical business apps | Custom terraform + Container Linux | [www.slideshare.net/Metatron31/kubernetes-at-immmr-coreos-fest-2016](https://www.slideshare.net/Metatron31/kubernetes-at-immmr-coreos-fest-2016) | Berlin, Germany |
| [Indix Corp](https://www.indix.com/) | critical business apps | Custom Terraform + Ansible + CoreOS | [manojlds.github.io/kubernetes-production/](https://manojlds.github.io/kubernetes-production/) | Chennai, India |
| [Luiza Labs](http://luizalabs.com) | critical business apps | kops | Our first Black Friday with critical apps on Kubernetes: [schd.ws/hosted_files/cloudnativeeu2017/10/KubeCon-BlackFriday.pdf](http://schd.ws/hosted_files/cloudnativeeu2017/10/KubeCon-BlackFriday.pdf) | São Paulo, Brazil |
| [Movio](https://movio.co/) | critical business apps | Custom Ubuntu AMIs | Older blog post: [movio.co/blog/6-months-kubernetes-production/](https://movio.co/blog/6-months-kubernetes-production/) Prometheus + Kubernetes: [movio.co/blog/prometheus-service-discovery-kubernetes/](https://movio.co/blog/prometheus-service-discovery-kubernetes/) | Auckland, New Zealand |
| [Mozilla](https://www.mozilla.org) | critical business apps | kops | [github.com/mozmar/infra](https://github.com/mozmar/infra) |  |
| [mytaxi](http://mytaxi.com) | proof of concept | kops, Terraform |  | Hamburg, Germany |
| [Netquest](https://www.netquest.com) | critical business apps | kube-aws | [www.camil.org/create-a-secure-kubernets-ha-cluster-in-aws-using-kube-aws/](https://www.camil.org/create-a-secure-kubernets-ha-cluster-in-aws-using-kube-aws/) | Barcelona, Spain |
| [notasquare](http://notasquare.vn) | dev/test/staging |  |  | Vietnam |
| [NUVI](http://www.nuvi.com) | critical business apps | Terraform + Ansible + CoreOS | No | Lehi, UT |
| [Oteemo](http://oteemo.com) | critical business apps | kops | Presentation to DC Continuous Delivery on running a CD stack on K8s: [docs.google.com/presentation/d/18r-u6S2r4LEV-0oTVL2iipfSyu6GRPYag3GsmafjRUU/edit?usp=sharing](https://docs.google.com/presentation/d/18r-u6S2r4LEV-0oTVL2iipfSyu6GRPYag3GsmafjRUU/edit?usp=sharing) | Reston, VA, United States |
| [Paytm](http://paytm.com) | critical business apps | kube-aws |  | Bangalore, India |
| [Pearson](http://www.pearson.com) | critical business apps | Terraform | www.devoperandi.com | London, UK and Denver, CO |
| [Photobox Ltd](http://group.photobox.com) | critical business apps | kops |  | London |
| [PlanGrid](http://www.plangrid.com) | critical business apps | CloudFormation + salt |  | San Francisco, CA, USA |
| [PlayCom](https://www.playcom.com) | critical business apps | kops | No (not yet) | Madrid, Barcelona (Spain) |
| [PornTube](https://porntube.com) | critical business apps | kube-aws | Not yet | Barcelona, Spain |
| [ReactiveOps](http://www.reactiveops.com) | critical business apps | kops, We also use our own internal framework for building clusters as we do it for many clients: [github.com/reactiveops/pentagon/](https://github.com/reactiveops/pentagon/) | [www.reactiveops.com/blog/introducing-pentagon](https://www.reactiveops.com/blog/introducing-pentagon) [github.com/reactiveops/pentagon/](https://github.com/reactiveops/pentagon/)  Lots more on our regular blog [www.reactiveops.com/blog/](https://www.reactiveops.com/blog/) | United States: Distributed |
| [Reddit](https://www.reddit.com/) | dev/test/staging | kubeadm, terraform |  | San Francisco, CA |
| [Restorando](http://www.restorando.com) | critical business apps | kops, kube-up |  | Buenos Aires, Argentina |
| [Rythm SAS](http://dreem.com) | critical business apps | kops, kops is wrapped into the karch Terraform module we wrote for the occasion: [github.com/elafarge/karch](https://github.com/elafarge/karch)  | [github.com/elafarge/karch](https://github.com/elafarge/karch) | Paris, France |
| [Schibsted](http://bytes.schibsted.com) | critical business apps | kube-aws |  | Barcelona |
| [SeamlessGov](http://seamlessgov.com/) | critical business apps | kops |  | New York, NY |
| [Simple](https://simple.com) | dev/test/staging | CoreOS Tectonic |  | Portland, Oregon |
| [Skuid Inc](https://www.skuid.com) | critical business apps | Terraform | [www.skuid.com/blog/reduce-administrative-toil-with-kubernetes-1-3/](https://www.skuid.com/blog/reduce-administrative-toil-with-kubernetes-1-3/) | Chattanooga, TN |
| [Spire Labs](http://spirelabs.co (also spire.me)) | critical business apps | kops | [medium.com/spire-labs/mitigating-an-aws-instance-failure-with-the-magic-of-kubernetes-128a44d44c14](https://medium.com/spire-labs/mitigating-an-aws-instance-failure-with-the-magic-of-kubernetes-128a44d44c14) [www.youtube.com/watch?v=xvXy2BiaWrQ](https://www.youtube.com/watch?v=xvXy2BiaWrQ) | Chattanooga, TN |
| [Spotahome](http://www.spotahome.com) | critical business apps | kops | Not yet | Madrid, Spain |
| [Spreaker](https://www.spreaker.com) | critical business apps | kops |  | Remote Team across Europe |
| [store2be GmbH](https://tech.store2be.com) | internal/non-critical apps | kops |  | Berlin, Germany |
| [Streema](http://streema.com) | critical business apps | kops, Terraform | Not yet |  |
| [Stylight GmbH](https://www.stylight.com) | critical business apps | Custom Cloud Formation + CoreOS | [github.com/stylight/etcd-bootstrap](https://github.com/stylight/etcd-bootstrap) | Munich |
| [Supership Inc.](https://supership.jp/en/) | dev/test/staging | kube-aws |  |  |
| [Ticketmaster](http://www.ticketmaster.com) | critical business apps | CoreOS Tectonic | See presentations from KubeCon & KubeCon EU. It's growing like mad. | Los Angeles, CA |
| [Tictrac](https://tictrac.com) | critical business apps | kops |  | London, UK |
| [UPMC Enterprises](http://enterprises.upmc.com) | critical business apps | [github.com/upmc-enterprises/kubernetes-on-aws](https://github.com/upmc-enterprises/kubernetes-on-aws) |  | Pittsburgh, PA |
| [uSwitch](http://www.uswitch.com) | critical business apps | kops and custom terraform | Not yet- we've started posting regularly to [labs.uswitch.com](https://labs.uswitch.com) and some posts on our Kubernetes work will appear soon. | London, UK |
| [Veritas Technologies LLC](http://veritas.com) | internal/non-critical apps | Terraform based on kube-aws with CoreOS | No | Minneapolis, MN; Hays, KS; Mtn View, CA |
| [Vonage](https://www.vonage.com) | proof of concept | kops, terraform |  | Holmdel, NJ |
| [Weaveworks](http://weave.works) | critical business apps | Terraform+Ansible ([github.com/weaveworks/ansible-kubernetes](https://github.com/weaveworks/ansible-kubernetes)) | [www.weave.works/provisioning-lifecycle-production-ready-kubernetes-cluster/](https://www.weave.works/provisioning-lifecycle-production-ready-kubernetes-cluster/) | Berlin, London & San Francisco |
| [Yahoo Inc](http://qc.yahoo.cm) | proof of concept | kops, Terraform |  | Barcelona, Sunnyvale |
| [Zalando SE](https://tech.zalando.com) | critical business apps | Custom Cloud Formation + CoreOS | [github.com/zalando-incubator/kubernetes-on-aws](https://github.com/zalando-incubator/kubernetes-on-aws) | Berlin, Germany |
<!-- TABLE_END -->


## Manually Compiled List

The following companies/organizations are known to run Kubernetes on AWS (sorted alphabetically), but haven't yet filled out [the Google form](https://docs.google.com/a/zalando.de/forms/d/e/1FAIpQLScrZkcCP8lfAuxZcWOzEmAIP0XCO5PtnfJbU0lFLx8D2-EdNg/viewform):

* [Buffer](https://buffer.com)
* Concur
* Disney
* [GolfNow](https://www.youtube.com/watch?v=MBDog4ivBHI&list=PLj6h78yzYM2PqgIGU1Qmi8nY7dqn9PCr4&index=74)
* [Hotels.com](https://hotels.com)
* [Nanit](https://www.nanit.com/) - [blog post](https://railsadventures.wordpress.com/2015/12/06/why-we-chose-kubernetes-over-ecs/)

## Contact

This is an initiative of [SIG-AWS](https://github.com/kubernetes/community/tree/master/sig-aws).
Please create GitHub issues for questions/concerns with this repo or [the Google form](https://docs.google.com/a/zalando.de/forms/d/e/1FAIpQLScrZkcCP8lfAuxZcWOzEmAIP0XCO5PtnfJbU0lFLx8D2-EdNg/viewform).

Please fill out [the Google form](https://docs.google.com/a/zalando.de/forms/d/e/1FAIpQLScrZkcCP8lfAuxZcWOzEmAIP0XCO5PtnfJbU0lFLx8D2-EdNg/viewform) to add your organization instead of opening a PR.

You can also [reach the maintainer on Twitter](https://twitter.com/try_except_).
