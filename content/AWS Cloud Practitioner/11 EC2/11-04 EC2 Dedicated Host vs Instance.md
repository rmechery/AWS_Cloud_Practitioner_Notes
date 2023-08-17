---
title: 11-04 EC2 Dedicated Host vs Instance
date: 08/10/23
---

**Dedicated Hosts** are single-tenant EC2 instances designed to let you Bring-Your-Own-License (BYOL) based on machine characteristics

<table>
<thead>
  <tr>
    <th></th>
    <th>Dedicated Instances</th>
    <th>Dedicated Hosts</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Isolation</td>
    <td>Instance Isolation</td>
    <td>Physical Server Isolation</td>
  </tr>
  <tr>
    <td>Billing</td>
    <td>Per instance billing (+$2 per region fee)</td>
    <td>Per host billing</td>
  </tr>
  <tr>
    <td>Visibility of Physical <br>characteristics</td>
    <td>No Visibilities</td>
    <td>Sockets, cores, host ID</td>
  </tr>
  <tr>
    <td>Affinity between a <br>host and instance</td>
    <td>No Affinity</td>
    <td>Consistency deploys to the same <br>instances to the same physical server</td>
  </tr>
  <tr>
    <td>Targeted instance <br>placement</td>
    <td>No control</td>
    <td>Additional control over instance <br>placement on physical server</td>
  </tr>
  <tr>
    <td>Automatic instance <br>placement</td>
    <td>Yes</td>
    <td>Yes</td>
  </tr>
  <tr>
    <td>Add capacity using <br>an allocation request</td>
    <td>No</td>
    <td>Yes</td>
  </tr>
</tbody>
</table>
