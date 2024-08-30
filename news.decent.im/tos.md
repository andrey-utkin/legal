# Terms and Conditions

https://news.decent.im (the Service) is an instance of [FreshRSS](https://freshrss.org) open source feed reader software service.

I, [Andriy Utkin](https://autkin.net), self-employed UK resident, am the Operator of the Service.

Customer is a physical person.
Customer uses the Service in exchange for a recurring subscription payment, or per voluntary grant from the Operator.

As a policy, the Service uses compute resources in countries [recognized as having adequate data protection by European Union](https://commission.europa.eu/law/law-topic/data-protection/international-dimension-data-protection/adequacy-decisions_en).
This can be rented or own, bare metal or virtualized (cloud) resources, in professional data centers or on Operator's premises.

Both Operator and Customer must follow the laws of UK and EU in their actions related to the Service.

The Operator provides technical support to Customers over email at customer-support@autkin.net .
This includes support of Customer's migration to other similar services or to a self-hosted FreshRSS.

The Service necessarily deals with Customer Data. It consists of:

- "Service User Data", stored in FreshRSS deployment: personal details (username, email), settlings, Personal Readings (feeds list, fetched articles and their read status).
- "Customer Relationship Data": purchase records (name, email, payment country of origin), emails and associated personal details, all stored outside of the FreshRSS deployment and inaccessible to it.


## Data redundancy and erasure policy

Operator cares about continued health of the Service in the face of expected faults of hardware and third-party services.

Effort is spent to make backups and continuously improve the approach to it, but no guarantees are made at the moment.

Backups of the Service User Data happen at least weekly on automated schedule.

Backups are stored for up to 4 weeks.

No particular level of redundancy and geographic distribution is advertised or guaranteed at the moment.

Customers are encouraged to export their feeds list regularly.

## User account deletion procedure

Customer can terminate their subscription anytime via Stripe at https://billing.stripe.com/p/login/4gw8zd35Ga7dbFC7ss and automatically get a pro-rated refund.

Alternatively, Customer can request termination via email to Operator at customer-support@autkin.net .

Customer can remove their account themselves in FreshRSS settings.
(At the moment this is not integrated with the subscription payments so Operator or Customer have to reconcile the subscription status and the user account manually.)

## Privacy

The Operator respects Customers' privacy.

The Operator has a duty to protect Customer Data confidentiality, to the extent possible by the laws of UK and EU.

The Operator does not sell or share Customers' Data.

The Operator does not employ or hire other people for activities allowing access to Customers' Data.

The Operator strives to not observe or disclose the Personal Readings.

The Customer must understand that despite the security features used (TLS, hashed passwords etc) and despite the Terms of Service, the Service has no strong technical protection of Customer privacy against the actions of Operator (especially actions in breach of Terms of Service), law enforcement personell or third parties gaining unauthorised access to the Service or its parts.

The Customer must understand that the nature of the Service and the Operator's duties make it probable for the Operator to inadvertently see Personal Readings, for example, the URLs of the original articles being fetched, because these are written into the log.

The Customer must understand that if the Operator becomes aware of suspected abusive or illegal activity by Customer, it will be investigated, possibly involving law enforcement personell.

The Operator may:

* Measure, compare and rank per-Customer load by measuring CPU, RAM and network traffic consumption.
* See the time of last usage by each Customer.


## Usage limits

Currently there are no specific usage limits.

Particular limits may be introduced in order to avoid deterioration of quality of service for all the Customers.
(Another possibility is that the computing capacity will be increased.)

In making decisions on which amount of system load is reasonable, Operator's own usage will be considered.

## Source code and licenses

FreshRSS license is GNU AGPL v3, which makes it mandatory for the deployed source code to be disclosed.

The source code deployed is made available at https://github.com/decent-im :

* https://github.com/decent-im/FreshRSS
* https://github.com/decent-im/FreshRSS_Extensions


This document was authored by [Andriy Utkin](https://autkin.net) and is shared on terms of [CC0 (Public Domain, No Copyright)](https://creativecommons.org/publicdomain/zero/1.0/).
