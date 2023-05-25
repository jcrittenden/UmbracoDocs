---
description: >-
  Learn the steps needed in order to install Vendr into your Umbraco CMS
  website.
---

# Installation

Learn how to install Umbraco Vendr into your Umbraco CMS implementation.

You can also find information about how to upgrade and how to install and activate your Umbraco Vendr license.

## NuGet Package Installation

Vendr is available via [NuGet.Org](https://www.nuget.org/packages/Vendr/).

To install Vendr via NuGet you can run the following command directly in the NuGet Manager Console window:

```bash
PM> dotnet add package Vendr
```

Alternatively, you can also find and install the NuGet package via the NuGet Package Manager in Visual Studio. You will see a number of packages available, however, you will want to install the main **Vendr** package.

![Installing Vendr via the NuGet Package Manager](../../payment-providers/media/nuget-package-manager-gui.png)

For most sites using a single solution, the above will be all you need to install Vendr into your project. When you have a more complex solution structure consisting of multiple projects, Vendr is available in multiple sub-packages with varying dependencies.

<table><thead><tr><th width="282">Sub-package</th><th>Description</th></tr></thead><tbody><tr><td><strong>Vendr.Common</strong></td><td>A shared project of common, non-Vendr-specific patterns and helpers.</td></tr><tr><td><strong>Vendr.Core</strong></td><td>Core Vendr functionality that doesn't require any infrastructure-specific dependencies.</td></tr><tr><td><strong>Vendr.Infrastructure</strong></td><td>Infrastructure-specific project containing implementations of core Vendr functionality.</td></tr><tr><td><strong>Vendr.Persistence</strong></td><td>Persistence-specific project containing implementations of core Vendr persistence functionality.</td></tr><tr><td><strong>Vendr.Persistence.SqlServer</strong></td><td>Persistence-specific project containing implementations of core Vendr persistence functionality for SQL Server.</td></tr><tr><td><strong>Vendr.Persistence.Sqllite</strong></td><td>Persistence-specific project containing implementations of core Vendr persistence functionality for SQLite.</td></tr><tr><td><strong>Vendr.Web</strong></td><td>Core Vendr functionality that requires a web context.</td></tr><tr><td><strong>Vendr.Umbraco</strong></td><td>Core Vendr functionality that requires an Umbraco dependency.</td></tr><tr><td><strong>Vendr.Umbraco.Web</strong></td><td>The Vendr functionality for the Umbraco presentation layer.</td></tr><tr><td><strong>Vendr.Umbraco.Web.UI</strong></td><td>The static Vendr assets for the Umbraco presentation layer.</td></tr><tr><td><strong>Vendr.Umbraco.Startup</strong></td><td>The Vendr functionality for registering Vendr with Umbraco.</td></tr><tr><td><strong>Vendr</strong></td><td>The main Vendr package entry point package.</td></tr></tbody></table>

## Upgrading

{% hint style="warning" %}
Before upgrading, it is always advisable to take a complete backup of your site and database.
{% endhint %}

Vendr uses Umbraco Migrations to install all of its features. Upgrades follow the same process as the installation processes detailed above, by installing the latest version over the top of the existing package installation. By using this process the installation will only install new features and features that are missing.

## Installing a License

Once you have purchased a license you can install it by dropping the license file directly into your sites `umbraco\Licenses` folder. Vendr will automatically scan this directory for any valid licenses.

When you need to store your licenses in an alternative directory, you can change where Vendr looks for licenses. This is done by setting a `Vendr.Licensing.LicensesDirectory` appSetting with a path to the alternative location.

{% hint style="info" %}
You only need to install your license when you are ready to go live.

Vendr is fully functional during development, and whilst it is hosted on a local server (`localhost` or `.local` domains).

You can also host a staging site on a `*.azurewebsite.net` or `*.umbraco.io` (Umbraco Cloud) domain without the need for a license.

Hosting on any other public domain without a license will be limited to a maximum of 20 orders.

If you require an unrestricted staging environment, all licenses support two methods of allowing this:

* `staging.client.com` - Licenses allow unlimited subdomains, meaning you can host the staging site on a subdomain of the licensed domain.
* `clientcom.agency.com` - Licenses allow a concatenation of the licensed domain as a subdomain of any other domain.

If you wish to host the site on any other URL, then an additional license file will be required for that domain.

Learn more about the licensing model in the [Licensing article](installation.md).
{% endhint %}