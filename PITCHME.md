# Elastic Search

---

## Descriptions

![Press Down Key](assets/down-arrow.png)
+++
#### What is Elastic Search?

Elasticsearch is a search engine based on <strong>Lucene</strong>. It provides a distributed, multitenant-capable full-text search engine with an HTTP web interface and <strong>schema-free JSON</strong> documents. 

So what is <strong>Lucene</strong>?

+++
#### Not a complex detailed explanation

Apache Lucene is a free and open-source information retrieval software library. (Initial release 1999)

+++
#### But a good simple and flexible architecture

At the core of Lucene's logical architecture is the idea of a <strong>document</strong> containing <strong>fields</strong> of text. This flexibility allows Lucene's API to be independent of the file format. Text from PDFs, HTML, Microsoft Word, Mind Maps, and OpenDocument documents, as well as many others (except images), can all be indexed as long as their textual information can be extracted.

+++
#### Elastic Search Technological Details
Elasticsearch is developed in <strong>Java</strong> and is released as open source under the terms of the Apache License. Official clients are available in Java, .NET (C#), PHP, Python, Groovy and many other languages. 

---

## History

![Press Down Key](assets/down-arrow.png)

+++

#### First release (0.4	2010-02-08) 

<strong>Shay Banon</strong> created the precursor to Elasticsearch, called Compass, in 2004. While thinking about the third version of Compass he realized that it would be necessary to rewrite big parts of Compass to <strong>"create a scalable search solution"</strong>. So he created <strong>"a solution built from the ground up to be distributed"</strong> and used a common interface, <strong>JSON over HTTP</strong>, <strong>suitable for programming languages other than Java</strong> as well. Shay Banon released the first version of Elasticsearch in <strong>February 2010</strong>.

+++

#### Latest release (6.5.3 2018-12-11) 

* Simple scalable searh solution to modularized and extensible product compatible to companies

---
## Market and Users

![Press Down Key](assets/down-arrow.png)

+++

#### Popularity
Elasticsearch is the most popular enterprise search engine followed by Apache Solr, also based on Lucene.

+++
#### Users
* CERN
* Netflix
* Github
* Facebook
* Goldman Sachs (https://www.informationweek.com/software/enterprise-applications/goldman-sachs-puts-elasticsearch-to-work/d/d-id/1321778)

---
## ELK Stack

![Press Down Key](assets/down-arrow.png)

+++

#### Elastic Search
The heart of the Elastic Stack

+++

#### Log Stash
Logstash is an open source, server-side data processing pipeline that ingests data from a multitude of sources simultaneously, transforms it, and then sends it to your favorite “stash.” (Ours is Elasticsearch, naturally.)

+++
#### Kibana
Kibana lets you visualize your Elasticsearch data and navigate the Elastic Stack, so you can do anything from learning why you're getting paged at 2:00 a.m. to understanding the impact rain might have on your quarterly numbers.

---
## Stack Features
![Press Down Key](assets/down-arrow.png)

<span>From enterprise-grade security and developer-friendly APIs to machine learning, and graph analytics, the Elastic Stack ships with features (formerly packaged as X-Pack) made and maintained by us to be enjoyed by you.
</span>

+++

@snap[west span-75 text-06]
@ul[spaced]
- Authenticate with Active Directory, LDAP, or the Elasticsearch native realm. Use single sign-on (SSO) options like certificates, Kerberos, and SAML — or build a custom realm that supports your home-grown identity management system.
- Grant the IT/Ops team the ability to monitor Elasticsearch cluster health without being able to see or modify the data. Or give the marketing team read-only access to marketing-specific data, but deny access to other indices. User privileges extend to Kibana, too. Group dashboards, visualizations, and saved searches into spaces by team, function, or any way you choose — and control who can access which space.
- With SSL/TLS encryption, you can secure node-to-node, HTTP, and transport client traffic across your Elastic Stack. IP filtering also prevents unapproved hosts from joining or communicating with your cluster.
- Layered Security - Cluster, Indexes, Document, Fields
- Audit Logging
- Compliance : Whether it's compliance from our end (FIPS 140-2 and Section 508) or standards on your side (HIPAA, PCI DSS, FISMA, ISO, or GDPR), the security features of the Elastic Stack help you become and stay compliant.
@ulend
@snapend

@snap[east span-25]
@img[shadow](assets/elasticfeatures_security.PNG)
@snapend

+++

![Logo](assets/elasticfeatures_alerting.PNG)
---
## Workshop
