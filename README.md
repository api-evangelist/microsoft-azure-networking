# Azure Networking (microsoft-azure-networking)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

A collection of Azure Networking APIs for managing virtual networks, load balancers, application gateways, and network security.

## Tags

- Azure
- Cloud
- Infrastructure
- Microsoft
- Networking

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-05-19

## APIs

### Azure Virtual Networks API

Manage Azure Virtual Networks (VNets) including subnets, peering, and network configurations.

- **Human URL:** [https://azure.microsoft.com/en-us/services/virtual-network/](https://azure.microsoft.com/en-us/services/virtual-network/)
- **Base URL:** `https://management.azure.com/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworks`

#### Tags

- Peering
- Subnets
- Virtual Networks
- Vnet

#### Properties

- [OpenAPI](openapi/microsoft-azure-networking-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-azure-networking.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-networking.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [X-documentation](https://docs.microsoft.com/en-us/rest/api/virtualnetwork/)
- [X-openapi](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/network/resource-manager/Microsoft.Network/stable/2023-05-01/virtualNetwork.json)
- [X-pricing](https://azure.microsoft.com/en-us/pricing/details/virtual-network/)
- [X-authentication](https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow)
- [Documentation](https://learn.microsoft.com/en-us/rest/api/virtualnetwork/)
- [Getting Started](https://learn.microsoft.com/en-us/azure/virtual-network/quickstart-create-virtual-network)

### Azure Load Balancer API

Distribute traffic across multiple virtual machines and services with Azure Load Balancer.

- **Human URL:** [https://azure.microsoft.com/en-us/services/load-balancer/](https://azure.microsoft.com/en-us/services/load-balancer/)
- **Base URL:** `https://management.azure.com/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/loadBalancers`

#### Tags

- High Availability
- Load Balancer
- Traffic Distribution

#### Properties

- [X-documentation](https://docs.microsoft.com/en-us/rest/api/load-balancer/)
- [X-openapi](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/network/resource-manager/Microsoft.Network/stable/2023-05-01/loadBalancer.json)
- [X-pricing](https://azure.microsoft.com/en-us/pricing/details/load-balancer/)
- [X-authentication](https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow)
- [Documentation](https://learn.microsoft.com/en-us/rest/api/load-balancer/)
- [Postman Collection](collections/azure-networking-load-balancer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-networking-load-balancer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/azure-networking-virtual-networks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-networking-virtual-networks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-azure-networking.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-networking.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Application Gateway API

Web traffic load balancer with application-level routing and SSL termination.

- **Human URL:** [https://azure.microsoft.com/en-us/services/application-gateway/](https://azure.microsoft.com/en-us/services/application-gateway/)
- **Base URL:** `https://management.azure.com/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/applicationGateways`

#### Tags

- Application Gateway
- Layer 7 Load Balancing
- Ssl Termination
- Web Application Firewall

#### Properties

- [X-documentation](https://docs.microsoft.com/en-us/rest/api/application-gateway/)
- [X-openapi](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/network/resource-manager/Microsoft.Network/stable/2023-05-01/applicationGateway.json)
- [X-pricing](https://azure.microsoft.com/en-us/pricing/details/application-gateway/)
- [X-authentication](https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow)
- [Documentation](https://learn.microsoft.com/en-us/rest/api/application-gateway/)
- [Postman Collection](collections/azure-networking-load-balancer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-networking-load-balancer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/azure-networking-virtual-networks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-networking-virtual-networks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-azure-networking.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-networking.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Network Security Groups API

Control network traffic to and from Azure resources with security rules.

- **Human URL:** [https://azure.microsoft.com/en-us/services/network-security-groups/](https://azure.microsoft.com/en-us/services/network-security-groups/)
- **Base URL:** `https://management.azure.com/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkSecurityGroups`

#### Tags

- Firewall
- Network Security Groups
- Nsg
- Security

#### Properties

- [X-documentation](https://docs.microsoft.com/en-us/rest/api/virtualnetwork/networksecuritygroups)
- [X-openapi](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/network/resource-manager/Microsoft.Network/stable/2023-05-01/networkSecurityGroup.json)
- [X-pricing](https://azure.microsoft.com/en-us/pricing/details/virtual-network/)
- [X-authentication](https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow)
- [Documentation](https://learn.microsoft.com/en-us/rest/api/virtualnetwork/networksecuritygroups)
- [Postman Collection](collections/azure-networking-load-balancer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-networking-load-balancer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/azure-networking-virtual-networks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-networking-virtual-networks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-azure-networking.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-networking.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure VPN Gateway API

Establish secure cross-premises connectivity between Azure and on-premises networks.

- **Human URL:** [https://azure.microsoft.com/en-us/services/vpn-gateway/](https://azure.microsoft.com/en-us/services/vpn-gateway/)
- **Base URL:** `https://management.azure.com/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualNetworkGateways`

#### Tags

- Gateway
- Hybrid Connectivity
- Site-To-Site
- Vpn

#### Properties

- [X-documentation](https://docs.microsoft.com/en-us/rest/api/network-gateway/)
- [X-openapi](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/network/resource-manager/Microsoft.Network/stable/2023-05-01/virtualNetworkGateway.json)
- [X-pricing](https://azure.microsoft.com/en-us/pricing/details/vpn-gateway/)
- [X-authentication](https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow)
- [Documentation](https://learn.microsoft.com/en-us/rest/api/network-gateway/)
- [Postman Collection](collections/azure-networking-load-balancer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-networking-load-balancer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/azure-networking-virtual-networks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-networking-virtual-networks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-azure-networking.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-networking.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Traffic Manager API

DNS-based traffic load balancer for distributing traffic globally.

- **Human URL:** [https://azure.microsoft.com/en-us/services/traffic-manager/](https://azure.microsoft.com/en-us/services/traffic-manager/)
- **Base URL:** `https://management.azure.com/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/trafficManagerProfiles`

#### Tags

- Dns
- Failover
- Global Load Balancing
- Traffic Manager

#### Properties

- [X-documentation](https://docs.microsoft.com/en-us/rest/api/trafficmanager/)
- [X-openapi](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/trafficmanager/resource-manager/Microsoft.Network/stable/2022-04-01/trafficmanager.json)
- [X-pricing](https://azure.microsoft.com/en-us/pricing/details/traffic-manager/)
- [X-authentication](https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow)
- [Documentation](https://learn.microsoft.com/en-us/rest/api/trafficmanager/)
- [Postman Collection](collections/azure-networking-load-balancer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-networking-load-balancer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/azure-networking-virtual-networks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-networking-virtual-networks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-azure-networking.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-networking.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure ExpressRoute API

Create private connections between Azure datacenters and on-premises infrastructure.

- **Human URL:** [https://azure.microsoft.com/en-us/services/expressroute/](https://azure.microsoft.com/en-us/services/expressroute/)
- **Base URL:** `https://management.azure.com/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/expressRouteCircuits`

#### Tags

- Dedicated Connection
- Expressroute
- Hybrid
- Private Connectivity

#### Properties

- [X-documentation](https://docs.microsoft.com/en-us/rest/api/expressroute/)
- [X-openapi](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/network/resource-manager/Microsoft.Network/stable/2023-05-01/expressRouteCircuit.json)
- [X-pricing](https://azure.microsoft.com/en-us/pricing/details/expressroute/)
- [X-authentication](https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow)
- [Documentation](https://learn.microsoft.com/en-us/rest/api/expressroute/)
- [Postman Collection](collections/azure-networking-load-balancer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-networking-load-balancer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/azure-networking-virtual-networks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-networking-virtual-networks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-azure-networking.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-networking.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Firewall API

Cloud-native network security service with built-in high availability.

- **Human URL:** [https://azure.microsoft.com/en-us/services/azure-firewall/](https://azure.microsoft.com/en-us/services/azure-firewall/)
- **Base URL:** `https://management.azure.com/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/azureFirewalls`

#### Tags

- Firewall
- Network Security
- Security
- Threat Protection

#### Properties

- [X-documentation](https://docs.microsoft.com/en-us/rest/api/firewall/)
- [X-openapi](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/network/resource-manager/Microsoft.Network/stable/2023-05-01/azureFirewall.json)
- [X-pricing](https://azure.microsoft.com/en-us/pricing/details/azure-firewall/)
- [X-authentication](https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow)
- [Documentation](https://learn.microsoft.com/en-us/rest/api/firewall/)
- [Postman Collection](collections/azure-networking-load-balancer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-networking-load-balancer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/azure-networking-virtual-networks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-networking-virtual-networks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-azure-networking.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-networking.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure DNS API

Host DNS zones and manage DNS records using the Azure DNS REST API. Supports creating, updating, and deleting public DNS zones and record sets for domain name resolution within Azure-managed infrastructure.

- **Human URL:** [https://learn.microsoft.com/en-us/azure/dns/](https://learn.microsoft.com/en-us/azure/dns/)
- **Base URL:** `https://management.azure.com/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/dnsZones`

#### Tags

- DNS
- Domain Name System
- Records
- Zones

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/dns/)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/dns/)
- [Authentication](https://learn.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow)
- [Postman Collection](collections/azure-networking-load-balancer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-networking-load-balancer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/azure-networking-virtual-networks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-networking-virtual-networks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-azure-networking.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-networking.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Private DNS API

Manage private DNS zones for name resolution within Azure virtual networks. Azure Private DNS provides a reliable and secure DNS service to manage and resolve domain names in a virtual network without needing a custom DNS solution.

- **Human URL:** [https://learn.microsoft.com/en-us/azure/dns/private-dns-overview](https://learn.microsoft.com/en-us/azure/dns/private-dns-overview)
- **Base URL:** `https://management.azure.com/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/privateDnsZones`

#### Tags

- DNS
- Name Resolution
- Private DNS
- Virtual Networks

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/dns/privatedns/private-zones)
- [Authentication](https://learn.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow)
- [Postman Collection](collections/azure-networking-load-balancer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-networking-load-balancer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/azure-networking-virtual-networks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-networking-virtual-networks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-azure-networking.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-networking.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Front Door API

Global load balancer and application delivery network that provides fast, reliable, and secure access to web applications. Azure Front Door offers layer 7 load balancing, SSL offload, URL-based routing, and Web Application Firewall integration.

- **Human URL:** [https://learn.microsoft.com/en-us/azure/frontdoor/](https://learn.microsoft.com/en-us/azure/frontdoor/)
- **Base URL:** `https://management.azure.com/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/frontDoors`

#### Tags

- CDN
- Front Door
- Global Load Balancing
- Web Application Firewall

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/frontdoor/)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/frontdoor/)
- [Authentication](https://learn.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow)
- [Postman Collection](collections/azure-networking-load-balancer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-networking-load-balancer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/azure-networking-virtual-networks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-networking-virtual-networks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-azure-networking.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-networking.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure DDoS Protection API

Manage DDoS protection plans that provide enhanced DDoS mitigation capabilities for Azure Virtual Network resources. Azure DDoS Protection provides countermeasures against sophisticated DDoS threats with adaptive tuning, attack analytics, and alerting.

- **Human URL:** [https://learn.microsoft.com/en-us/azure/ddos-protection/](https://learn.microsoft.com/en-us/azure/ddos-protection/)
- **Base URL:** `https://management.azure.com/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/ddosProtectionPlans`

#### Tags

- DDoS Protection
- Network Security
- Security
- Threat Mitigation

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/virtualnetwork/ddos-protection-plans)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/ddos-protection/)
- [Authentication](https://learn.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow)
- [Postman Collection](collections/azure-networking-load-balancer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-networking-load-balancer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/azure-networking-virtual-networks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-networking-virtual-networks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-azure-networking.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-networking.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Network Watcher API

Monitor, diagnose, and gain insights into network performance and health in Azure. Network Watcher provides tools for packet capture, connection troubleshooting, NSG flow logs, and network topology visualization.

- **Human URL:** [https://learn.microsoft.com/en-us/azure/network-watcher/](https://learn.microsoft.com/en-us/azure/network-watcher/)
- **Base URL:** `https://management.azure.com/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/networkWatchers`

#### Tags

- Diagnostics
- Flow Logs
- Network Monitoring
- Packet Capture

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/network-watcher/)
- [Authentication](https://learn.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow)
- [Postman Collection](collections/azure-networking-load-balancer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-networking-load-balancer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/azure-networking-virtual-networks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-networking-virtual-networks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-azure-networking.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-networking.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Bastion API

Fully managed PaaS service that provides secure and seamless RDP and SSH connectivity to virtual machines directly through the Azure portal over TLS. Azure Bastion is deployed inside a virtual network and does not require a public IP on the target VM.

- **Human URL:** [https://learn.microsoft.com/en-us/azure/bastion/](https://learn.microsoft.com/en-us/azure/bastion/)
- **Base URL:** `https://management.azure.com/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/bastionHosts`

#### Tags

- Bastion
- RDP
- Remote Access
- Secure Connectivity
- SSH

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/virtualnetwork/bastion-hosts)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/azure-bastion/)
- [Authentication](https://learn.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow)
- [Postman Collection](collections/azure-networking-load-balancer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-networking-load-balancer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/azure-networking-virtual-networks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-networking-virtual-networks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-azure-networking.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-networking.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure NAT Gateway API

Simplify outbound-only internet connectivity for virtual networks. When configured on a subnet, all outbound connectivity uses specified static public IP addresses. NAT Gateway provides on-demand SNAT port allocation without the need for a load balancer or directly attached public IPs.

- **Human URL:** [https://learn.microsoft.com/en-us/azure/nat-gateway/](https://learn.microsoft.com/en-us/azure/nat-gateway/)
- **Base URL:** `https://management.azure.com/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/natGateways`

#### Tags

- IP Address Management
- NAT Gateway
- Outbound Connectivity
- SNAT

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/virtualnetwork/nat-gateways)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/azure-nat-gateway/)
- [Authentication](https://learn.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow)
- [Postman Collection](collections/azure-networking-load-balancer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-networking-load-balancer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/azure-networking-virtual-networks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-networking-virtual-networks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-azure-networking.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-networking.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Private Link API

Access Azure PaaS services and customer-owned services over a private endpoint in your virtual network. Azure Private Link eliminates data exposure to the public internet by keeping traffic on the Microsoft global network.

- **Human URL:** [https://learn.microsoft.com/en-us/azure/private-link/](https://learn.microsoft.com/en-us/azure/private-link/)
- **Base URL:** `https://management.azure.com/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/privateLinkServices`

#### Tags

- Network Isolation
- Private Endpoint
- Private Link
- Security

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/virtualnetwork/private-link-services)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/private-link/)
- [Authentication](https://learn.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow)
- [Postman Collection](collections/azure-networking-load-balancer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-networking-load-balancer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/azure-networking-virtual-networks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-networking-virtual-networks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-azure-networking.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-networking.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Virtual WAN API

Networking service that provides optimized and automated branch-to-branch connectivity through Azure. Virtual WAN brings together networking, security, and routing functionalities into a single operational interface including VPN, ExpressRoute, and point-to-site connectivity.

- **Human URL:** [https://learn.microsoft.com/en-us/azure/virtual-wan/](https://learn.microsoft.com/en-us/azure/virtual-wan/)
- **Base URL:** `https://management.azure.com/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/virtualWans`

#### Tags

- Branch Connectivity
- Hybrid Networking
- SD-WAN
- Virtual WAN

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/virtualwan/)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/virtual-wan/)
- [Authentication](https://learn.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow)
- [Postman Collection](collections/azure-networking-load-balancer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-networking-load-balancer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/azure-networking-virtual-networks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-networking-virtual-networks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-azure-networking.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-networking.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Web Application Firewall API

Cloud-native web application firewall service that provides centralized protection for web applications from common exploits and vulnerabilities. Azure WAF can be deployed with Application Gateway, Front Door, and CDN for layer 7 protection.

- **Human URL:** [https://learn.microsoft.com/en-us/azure/web-application-firewall/](https://learn.microsoft.com/en-us/azure/web-application-firewall/)
- **Base URL:** `https://management.azure.com/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/ApplicationGatewayWebApplicationFirewallPolicies`

#### Tags

- Application Protection
- Security
- WAF
- Web Application Firewall

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/application-gateway/web-application-firewall-policies)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/web-application-firewall/)
- [Authentication](https://learn.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow)
- [Postman Collection](collections/azure-networking-load-balancer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-networking-load-balancer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/azure-networking-virtual-networks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-networking-virtual-networks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-azure-networking.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-networking.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [X-portal](https://portal.azure.com)
- [X-support](https://azure.microsoft.com/en-us/support/)
- [X-status](https://status.azure.com/)
- [X-blog](https://azure.microsoft.com/en-us/blog/topics/networking/)
- [X-terms-of-service](https://azure.microsoft.com/en-us/support/legal/)
- [Portal](https://portal.azure.com)
- [Documentation](https://learn.microsoft.com/en-us/azure/networking/)
- [Getting Started](https://learn.microsoft.com/en-us/azure/networking/fundamentals/networking-overview)
- [Privacy Policy](https://privacy.microsoft.com/en-us/privacystatement)
- [S D Ks](https://learn.microsoft.com/en-us/azure/developer/)
- [GitHub Organization](https://github.com/Azure)
- [GitHub Repository](https://github.com/Azure/azure-rest-api-specs)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/azure-virtual-network)
- [Changelog](https://azure.microsoft.com/en-us/updates/?query=networking)
- [Pricing](https://azure.microsoft.com/en-us/pricing/)
- [Sign Up](https://azure.microsoft.com/en-us/free/)
- [Login](https://portal.azure.com/#home)
- [Authentication](https://learn.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://azure.microsoft.com
