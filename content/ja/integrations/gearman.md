---
title: Datadog-Gearman Integration
sidebar:
  nav:
    - header: Integrations
    - text: Back to Overview
      href: "/ja/integrations/"
---

<div id="int-overview">
<h3>Overview</h3>

Bring Gearman metrics to Datadog to:
<ul>
<li> Visualize Gearman performance.</li>
<li> Know how many tasks are queued or running.</li>
<li> Correlate the performance of Gearman with the rest of your applications.</li>
</ul>
</div>

From the open-source Agent:

* <a href="https://github.com/DataDog/dd-agent/blob/master/conf.d/gearmand.yaml.example">
Gearman YAML example</a>
* <a href="https://github.com/DataDog/dd-agent/blob/master/checks.d/gearmand.py">
Gearman checks.d</a>

The following metrics are collected by default with the Gearman integration:

    gearman.queued
    gearman.running
    gearman.unique_tasks
    gearman.workers
