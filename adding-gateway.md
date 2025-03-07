---

copyright:
  years: 2020, 2021
lastupdated: "2021-06-17"

keywords:

subcollection: transit-gateway

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:codeblock: .codeblock}
{:pre: .pre}
{:screen: .screen}
{:tip: .tip}
{:note: .note}
{:important: .important}
{:download: .download}
{:external: target="_blank" .external}
{:term: .term}

# Adding a connection
{: #adding-connections}

To add a connection to a transit gateway, follow these steps:
1. From your browser, open the [{{site.data.keyword.cloud_notm}} console](https://cloud.ibm.com){:external} and log in to your account.
1. Select the Menu icon ![Menu icon](../../icons/icon_hamburger.svg) from the upper left, then click **Interconnectivity**.
1. Click **Transit Gateway** from the left navigation pane.
1. Click the name of the transit gateway where you want to add a connection.

  If you are in the expanded view, click **View details**.
  {: tip}

1. Click **Add connection**.
1. Choose and configure the specific network connections that you want to add to your transit gateway.

  Choices include:

  * **Classic infrastructure** - Allows you to connect to IBM Cloud classic resources.
  * **VPC** - Allows you to connect to your account's VPC resources, or VPC resources from other accounts as well.
  * **GRE tunnel** - Allows a transit gateway to connect to overlay networks hosted on classic infrastructure resources in approved use cases. For prerequisites and detailed instructions, see [Creating a Generic Routing Encapsulation (GRE) tunnel connection](/docs/transit-gateway?topic=transit-gateway-GRE-connection).

1. Click **Add**.
