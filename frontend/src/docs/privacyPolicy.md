---
id: privacy-policy
title: Privacy Policy
---

<div>

# <a href="#/docs">Docs</a> <span>/</span> Privacy Policy

<img src="/static/img/main/privacy.svg" alt="Privacy">

Last updated November 27, 2020

Webserver logs are stored for **7 days** (or less if the log file gets too big) and are in the [Common Log Format](https://en.wikipedia.org/wiki/Common_Log_Format).

Anonymized counters from all DNS queries are stored for ever (or until they get too big) and are logged every 60 seconds. We use https://github.com/prometheus-community/bind_exporter if you would like to see the full list of metrics, but in short these logs include numbers only so nothing that's able to identify any particular user.  

Nothing else is *ever* logged other than what is listed above.
</div>

<style>
    div {
        margin: auto;
        width: 50%;
    }
    
    span {
        color: #d000ff;
    }
    
    a {
        color: white;
        text-decoration: none;
    }
    
    img {
        width: 350px;
        display: block;
        margin: auto auto 40px;
    }
</style>
