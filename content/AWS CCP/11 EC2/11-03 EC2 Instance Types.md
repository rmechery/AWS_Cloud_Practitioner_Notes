---
title: 11-03 EC2 Instance Types
date: 08/10/23
---

An instance type is a particular **[instance size](11-03%20EC2%20Instance%20Types.md#ec2-instance-sizes) and [instance family](11-02%20EC2%20Instance%20Families.md#8eb238)**.

 > 
 > \[!example\] Example  
 > `t2.micro`
 > 
 > * `t2` is the instance family
 > * `micro` is the instance size  
 >   *together* they make up an instance type

# EC2 Instance Sizes

A common pattern for instance sizes:

* `nano`
* `micro`
* `small`
* `medium`
* `large`
* `xlarge`
* `2xlarge`
* `4xlarge`
* `8xlarge`
* ….

There are many exceptions to this pattern for sizes e.g.

* `c6g.metal` – is a bare metal machine.
* `C5.9xlarge` – Is not a power of 2 or even number size

EC2 Instance Sizes generally double in price and key attributes

<div>
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-c3ow{border-color:inherit;text-align:center;vertical-align:top}
.tg .tg-0pky{border-color:inherit;text-align:left;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-c3ow"><span style="font-weight:bold">Name</span></th>
    <th class="tg-c3ow"><span style="font-weight:bold">vCPU</span></th>
    <th class="tg-c3ow"><span style="font-weight:bold">RAM (GB)</span></th>
    <th class="tg-c3ow"><span style="font-weight:bold">On-Demand per hour</span></th>
    <th class="tg-c3ow"><span style="font-weight:bold">On-Demand per month</span></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0pky">t2.small</td>
    <td class="tg-0pky">1</td>
    <td class="tg-0pky">12</td>
    <td class="tg-0pky"> $0.023</td>
    <td class="tg-0pky"> $16.79</td>
  </tr>
  <tr>
    <td class="tg-0pky">t2.medium</td>
    <td class="tg-0pky">2</td>
    <td class="tg-0pky">24</td>
    <td class="tg-0pky"> $0.0464</td>
    <td class="tg-0pky"> $33.87</td>
  </tr>
  <tr>
    <td class="tg-0pky">t2.large</td>
    <td class="tg-0pky">2</td>
    <td class="tg-0pky">36</td>
    <td class="tg-0pky"> $0.0928</td>
    <td class="tg-0pky"> $67.74</td>
  </tr>
  <tr>
    <td class="tg-0pky">t2.xlarge</td>
    <td class="tg-0pky">4</td>
    <td class="tg-0pky">54</td>
    <td class="tg-0pky"> $0.1856</td>
    <td class="tg-0pky"> $135.48</td>
  </tr>
</tbody>
</table>
</div>
