---
icon: '2'
description: Last updated Feb 2, 2025
cover: >-
  https://images.unsplash.com/photo-1642222385655-8339a5b6033b?crop=entropy&cs=srgb&fm=jpg&ixid=M3wxOTcwMjR8MHwxfHNlYXJjaHw1fHxudW1iZXIlMjAyfGVufDB8fHx8MTczNzYwMzYyNnww&ixlib=rb-4.0.3&q=85
coverY: 159
layout:
  cover:
    visible: true
    size: full
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Introduction to Module 2

{% hint style="info" %}
You will have 1 week to complete Module 2
{% endhint %}

:exclamation:Homework is due 2/03/25 (Alaska local time) -  [https://courses.datatalks.club/de-zoomcamp-2025/](https://courses.datatalks.club/de-zoomcamp-2025/)

:warning: NOTE that because this module was new, there were a lot of changes/modifications to this week throughout the week. Some of my notes may not have caught all the changes. Two ISSUES were the docker-compose.yml and JSON key. In these notes, the docker-compose.yml by Bruno is great, up until the dbt module, when I used Will's, but better practice is Bruno's. The JSON private key comes into play for GCP connection. BE SURE to NOT git your key info. The video has up copy and paste it into a flow, so DO NOT git that flow. I put mine in a folder called 'private' and did not add it to my public github repo. You can find more info in slack here -&#x20;

{% embed url="https://datatalks-club.slack.com/archives/C01FABYF2RG/p1738520204522619" %}

:books: Module 2 Course Material from #zoomcamp:

{% @github-files/github-code-block url="https://github.com/DataTalksClub/data-engineering-zoomcamp/tree/main/02-workflow-orchestration" %}

<figure><img src="../.gitbook/assets/arch_v4_workshops (1).jpg" alt=""><figcaption><p><a href="https://github.com/DataTalksClub/data-engineering-zoomcamp/tree/main/images/architecture">https://github.com/DataTalksClub/data-engineering-zoomcamp/tree/main/images/architecture</a></p></figcaption></figure>

#### :writing\_hand: Summary

Module 2 will introduce us to Kestra, which is "an open-source, event-driven orchestration platform that simplifies building both scheduled and event-driven workflows. By adopting Infrastructure as Code practices for data and process orchestration, Kestra enables you to build reliable workflows with just a few lines of YAML."  - #dezoomcamp

{% @github-files/github-code-block url="https://github.com/kestra-io/kestra" %}

### :bookmark: FAQs videos

{% tabs %}
{% tab title="PostgresDB Setup and Installing pgAdmin" %}
{% embed url="https://youtu.be/ywAPYNYFaB4?si=5X9AD0nFAT2WLWgS" %}
{% endtab %}

{% tab title="Docker Setup" %}
{% embed url="https://youtu.be/l2M2mW76RIU?si=oqyZ7KUaI27vi90V" %}
{% endtab %}
{% endtabs %}

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td></td><td><a href="2.1-introduction-to-orchestration-and-kestra/">2.1 - Introduction to Orchestration and Kestra</a></td><td></td></tr><tr><td></td><td><a href="2.2-etl-pipelines-in-kestra-detailed-walkthrough/">2.2 - ETL Pipelines in Kestra: Detailed Walkthrough</a></td><td></td></tr><tr><td></td><td><a href="2.3-etl-pipelines-in-kestra-google-cloud-platform/">2.3 - ETL Pipelines in Kestra: Google Cloud Platform</a></td><td></td></tr><tr><td><a href="bonus-deploy-to-the-cloud.md">Bonus: Deploy to the Cloud</a></td><td></td><td></td></tr><tr><td><a href="broken-reference">Homework</a></td><td></td><td></td></tr></tbody></table>
