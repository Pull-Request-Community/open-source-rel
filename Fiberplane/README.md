# Fiberplane & Open Source 
[Fiberplane](https://fiberplane.com/) has a strong approach to [building open-source tools](https://fiberplane.com/opensource) and contributing to the wider open-source ecosystem. The company has started a fully Open Source project called Autometrics and also baked in open-source components in their SaaS products: Fiberplane notebooks. 

A [Discord](https://discord.gg/6eZyhxFBmC) space for community interaction, questions, and support regarding both projects is available. 

## Autometrics
 [Autometrics](https://autometrics.dev/) is an open-source micro framework for developer-first observability. Its goal is to make it easy to instrument your code base and get metrics out of the box based on the functions in your code. From there, it helps you to generate SLOs and alerts. 


It is build up on top of the open-source projects [Prometheus](https://prometheus.io/) and [OpenTelemetry](https://opentelemetry.io/).

The micro framework is available for multiple languages. Fiberplane officially supports four languages (Python, TS, Go, and Rust), and there are community contributions for two languages (Java and C#). The language packages, IDE extensions, and shared sources are available in a dedicated [Autometrics-Dev GitHub organisation](https://github.com/autometrics-dev). There are [discussions on GitHub](https://github.com/orgs/autometrics-dev/discussions) for future development.In general, the whole development happens in the open, and besides the GitHub discussions, more conversations are taking place in the mentioned Discord space above. 

### Why is Autometrics open source?
The tool aims to make observability developer friendly. Hence making open-source, developers can contribute to this approach. 

Autometrics provides a simple way to instrument your code and get metrics from the functions in your code base. Because it is an easy tool to get started with observability, open source supports this approach and lowers the barrier to adopting the solution.

Additionally, it is built on top of other open-source tools and uses those components. Therefore an exchange with existing communities is important to provide the best outcome and value to the users of the microframework.

## Fiberplane notebooks
Fiberplane Notebooks is a SaaS solution that allows you to debug your infrastructure, resolve incidents and create runbooks collaboratively.

Engineering teams can write queries within the notebooks and connect them to their observability data backends like Prometheus, Elastic Search, and Loki. Those are called Providers. The whole [provider stack is open-source](https://fiberplane.com/blog/opensourcing-providers). The open-source stack allows you to write own providers and create your own observability stack. Besides the providers, the [CLI tool fp](https://github.com/fiberplane/fp) and [Fiberplane template](https://github.com/fiberplane/templates) are open source too. All projects can be found in [Fiberplane's GitHub repo](https://github.com/fiberplane). 


### Why are parts of Fiberplane notebooks open source?
The main reason to provide open source components is to make Fiberplane notebooks exensible and flexible towards an integration with multiple tools and vendors. 

Further it benefits the community and generates a shared basis for example for useful Fiberplane templates. Further opening the provider stack allows people to understand how data is processed. It enables transparency and good quality when building Software.


## Fiberplane's contribution to Open Source

Besides building open-source software, Fiberplane contributes to other communities too. 

Within the OpenTelemetry community, Fiberplane developers engage in discussion towards further development and contribute code too.