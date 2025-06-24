# Usage settings

In your Group or Organization, select **Settings** > **Usage** to view Snyk usage details for your Group or Organization:

* **Test usage**: the number of tests used
* **Contributing developers**: the number of developers contributing to Projects

{% hint style="info" %}
For more information about test frequency settings, see [Project actions](../snyk-projects/#project-actions-on-the-project-listing-page) on the Project Listings page, where bulk actions are also explained.
{% endhint %}

## Test usage

The **Test Usage** section shows how many tests you are using over the current billing period:

<figure><img src="../../.gitbook/assets/usage_test_usage.png" alt=""><figcaption><p>Test usage data</p></figcaption></figure>

{% hint style="info" %}
Test limits vary for Snyk products and plans.

For the Free plan, the limits are: Open Source, 400 tests; Code, 100 tests; IaC, 300 tests; Container, 100 tests.

See the [Plans and pricing page](https://snyk.io/plans/) for more details. See [What counts as a test?](https://app.gitbook.com/o/-M4tdxG8qotLgGZnLpFR/s/-MdwVZ6HOZriajCf5nXH/~/changes/9427/working-with-snyk/what-counts-as-a-test/~/comments/aVG2sKbleunjnrD7uebf?node=VTVpQ2yD0cl4) for details of how Snyk counts tests.
{% endhint %}

## Contributing developers

Snyk defines contributing developers as developers having made a commit to a private repo monitored by Snyk in the last 90 days.

The **Contributing developers for SCM and CLI integrations** section shows contributing developer counts, both at the Organization level and the Group level.

The developer count is the number of developers who have contributed to the default branch of any private repository connected to an integration.

Snyk does not count contributions to public (open-source) repos because the pricing model is based on the number of contributing developers to private repositories.

The contributing developers count shows:

* **Total unique contributors across all integrations:** the number of contributors across all the integrations in your Snyk account. Contributing developers are only counted once, even if they have contributed to multiple integrations or multiple repositories.
* **Breakdown by integration**: the number of contributors, Organizations, and repos in that integration.

A contributor is recognized through the author email field, set in the local Git settings.

## Billing and Usage

{% hint style="info" %}
The **Billing and Usage** menu is available only for Tenant Admins on the Snyk Platform Access plan.

For more information on billable events and credits, see [Policies](https://snyk.io/policies/definition-of-snyk-platform-access/).
{% endhint %}

At the Tenant level, navigate to **Billing and Usage** to view credit consumption and usage patterns across all Groups and Organizations within the selected Tenant. The **Billing and Usage** dashboard also provides an overview of which Snyk products and Projects consume your credits.

<figure><img src="../../.gitbook/assets/billing_and_usage_dashboard.png" alt=""><figcaption><p>Billing and Usage dashboard</p></figcaption></figure>

The **Billing and Usage** dashboard provides the following information:

* **Billing period**
* **Platform Access:** the number of available credits per billing period, the number of contributing developers, and the Snyk products enabled. To see which Snyk products are enabled, hover over the information button.&#x20;

{% hint style="info" %}
By default, all Snyk products are enabled. Any Project that you import and test using one of the Snyk products can consume credits.&#x20;
{% endhint %}

* **Credit usage:** the number of credits used so far and the number of days left on your subscription.
* **Billable events log:** a detailed list of all events during a billing period.

You can also see a breakdown of your credit usage and filter the information by Group, Snyk product, or date range.&#x20;

<figure><img src="../../.gitbook/assets/billing_and_usage_dahsboard_credit_breakdown.png" alt=""><figcaption><p>Example of credit usage breakdown</p></figcaption></figure>
