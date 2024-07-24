# SCM, IDE, and CI/CD integrations

This section of the documentation provides information about [Snyk SCM](snyk-scm-integrations/), [IDE](snyk-ide-plugins-and-extensions/), and [CI/CD integrations](snyk-ci-cd-integrations/).

Snyk supports SCM, IDE, and CI/CD integration methods that allow you to implement security at each point in your workflow: importing a Project, writing your code, and building and deployment.

{% hint style="warning" %}
Enterprise plan users have access to all of the functionality. The API and Snyk AppRisk are not available to Free and Team plan users. See [Plans and pricing](https://snyk.io/plans/) for more information.
{% endhint %}

There are two ways of implementing SCM integrations in a Snyk environment:

* **Group level** - At the Group level, you can set up the SCM integrations for Snyk AppRisk.&#x20;
* **Organization level** - At the Organization level, you can set up the SCM integrations for all Snyk plans. See the [Manage your Integrations](../getting-started/snyk-web-ui.md) at the Organizational level page for more details.&#x20;

## Choose an Integration

If you are an Enterprise customer, see [Choose rollout integrations](../implement-snyk/team-implementation-guide/phase-1-discovery-and-planning/choose-rollout-integrations.md) in the Enterprise implementation guide for tips and considerations on import strategies, as well as context for which integrations suit your SDLC.

## Pull Requests for Snyk integrations

Snyk can automatically create pull requests (PRs) on your behalf to upgrade your dependencies based on scan results. This is compatible with a variety of Snyk integrations. For more information, see [View and understand Snyk upgrade pull requests for integrations](../integrate-with-snyk/git-repositories-scms-integrations-with-snyk/introduction-to-git-repository-integrations/view-and-understand-snyk-upgrade-pull-requests.md).