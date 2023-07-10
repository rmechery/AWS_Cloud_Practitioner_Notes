---
title: 06-01 Shared Responsibility Model
date: 07/10/23
---

The Shared Responsibility Model is a ==cloud security framework== that defines the  
security obligations of the customer versa the Cloud Service Provider (CSP) e.g. AWS.

Each CSP has their own variant of the Shared Responsibility Model but they are all generally the same.

## AWS Shared Responsibility Model

### Customer

<table style="text-align: center">
    <tbody>
        <tr>
          <td rowspan=4>Customer<br>Responsibility for security 'in' the cloud.</td>
          <td colspan=4>Customer Data</td>
        </tr>
        <tr>
          <td colspan=4>Platform, Applications, IAM</td>
        </tr>
        <tr>
          <td colspan=4>OS, Network & Firewall Config.</td>
        </tr>
        <tr>
          <td colspan=2>Client-side Data Encryption & Data Integrity Authentication</td>
          <td>Server-side Encryption</td>
          <td>Network Traffic Protection</td>
        </tr>
        <tr>
          <td rowspan=4>AWS<br>Responsibility for security 'of' the cloud.</td>
          <td colspan = 4>Software</td>
        </tr>
        <tr>
          <td>Compute</td>
          <td>Storage</td>
          <td>Database</td>
          <td>Networking</td>
        </tr>
        <tr>
           <td colspan = 4>Hardware/AWS Global Infr.</td>
        </tr>
        <tr>
            <td>Hardware</td>
            <td colspan=2>Availability Zone</td>
            <td>Edge Locations</td>
        </tr>
    </tbody>
</table>

The *type* of cloud deployment model and/or the *scope* of cloud service category  
can result in specialized Shared Responsibility Models.

## tl;dr

* You are responsible for security *in* the cloud
* AWS is responsible for security *of* the cloud
