<p align="center">
  <img src='images/harness.png?raw=true' width='70%'>
</p>

---

Harness CD is a modern self-service continuous delivery solution that allows developers to deploy, verify and automatically rollback Kubernetes and other cloud-native applications, all without the toil present in legacy CD tools like Jenkins and Spinnaker.

- [What is Harness CD Community Edition?](#what-is-harness-cd-community-edition)
- [Starting with Harness CD Community Edition](#starting-with-harness-cd-community-edition)
- [Starting with Harness CD SaaS Plans](#starting-with-harness-cd-saas-plans)
- [Docs](#docs)
- [Need Help?](#need-help)
- [Contributing](#contributing)
- [Design](#design)
- [See Also](#see-also)

## What is Harness CD Community Edition?

Harness CD Community Edition is a free and open edition of Harness CD that is designed for developers to deploy cloud-native services at the fastest velocity possible. Developers can self-host this edition on Docker or Kubernetes using a [docker-compose.yml](./docker-compose/harness/README.md) and a [helm-chart](./helm/README.md) respectively. This repo houses the docker-compose and helm-charts for Harness CD Community Edition while the `harness-core` and other public repos in this `harness` organization house the source code.

Harness CD is also available as a fully-managed SaaS solution in three different plans, namely Free, Team and Enterprise. For more details, see the [Harness CD Editions & Plans](https://harness.io/pricing/?module=cd) page.

<p align="center">
  <a href=''> <img src='' width='70%'> </a>
</p>


## Starting with Harness CD Community Edition

1. Install Harness CD Community Edition:  [using docker-compose](./docker-compose/harness/README.md) or [using helm chart](./helm/README.md).
2. Create a [Kubernetes CD pipeline](https://ngdocs.harness.io/article/ltvkgcwpum-harness-community-edition-quickstart#step_2_create_pipeline) and deploy a sample microservice into your local minikube or external Kubernetes cluster.
3. Explore core features, such as [canary rollout](https://ngdocs.harness.io/article/i5p4feil89-create-a-kubernetes-canary-deployment), [automated infrastructure/Terraform provisioning](https://ngdocs.harness.io/article/boug6e884h-terraform-provisioning-with-harness), [pipeline-as-code](https://ngdocs.harness.io/article/1eishcolt3-harness-yaml-quickstart), [Git Experience](https://ngdocs.harness.io/article/dm69dkv34g-harness-git-experience-quickstart) and [built-in approvals](https://ngdocs.harness.io/article/43pzzhrcbv-using-harness-approval-steps-in-cd-stages).

## Starting with Harness CD SaaS Plans

We can run Harness CD for you, so you don't have to host and manage your own instance. All you have to do is signup at [harness.io](https://app.harness.io/auth/#/signup/?module=cd).

## Docs

For guidance on installation, usage, and administration, see our [User Documentation](https://ngdocs.harness.io/article/ltvkgcwpum-harness-community-edition-quickstart).

## Need Help?

- [Harness Community Slack](https://join.slack.com/t/harnesscommunity/shared_invite/zt-y4hdqh7p-RVuEQyIl5Hcx4Ck8VCvzBw) - Join our slack channel`#cd-community` to connect with our engineers and other users running Harness CD.
- [Harness Community Forum](https://community.harness.io/) - Ask questions, find answers, and help other users.
- [Troubleshooting documentation](https://ngdocs.harness.io/article/jzklic4y2j-troubleshooting) - Learn how to troubleshoot common errors.
- For filing bugs, suggesting improvements, or requesting new features, help us out by [opening an issue](https://github.com/harness/harness-cd-community/issues/new).


## Contributing

We welcome your contributions! We will soon be publishing guidelines on how you can contribute to Harness CD.

## Licensing

Harness CD Community Edition code is released under the source available [PolyForm Shield 1.0.0](https://polyformproject.org/wp-content/uploads/2020/06/PolyForm-Shield-1.0.0.txt) license. The `harness-core` and other public repos in the `harness` organization also contain code that is licensed under [PolyForm Free Trial](https://polyformproject.org/wp-content/uploads/2020/05/PolyForm-Free-Trial-1.0.0.txt) license.

When contributing to a Harness CD feature, you can find the relevant license in the comments at the top of each file.

For more information, see the [Harness Loves Open Source page]().

## Comparison with Other CD Tools

To see how key features of Harness CD stack up against other CD tools,
check out [Harness CD in Comparison](https://harness.io/learn/comparison-guide/).

## See Also

- [Technical Resources](https://harness.io/learn/resource-center/) (by Harness engineers and customers!)
- [Harness User Documentation](https://ngdocs.harness.io/)
- [The Harness Blog](https://harness.io/blog/)