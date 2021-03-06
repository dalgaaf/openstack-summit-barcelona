<!-- .slide: data-background-image="images/suse_logo_full_epsexport.svg" data-background-size="90% auto" -->
Note: SUSE start


<!-- Slide -->
# 1
### OpenStack


<!-- Slide -->
###### SUSE 
###### OpenStack Cloud 7
with

<img src="images/openstack/newton-logo.png" style="width:15%;">

based on

`SLES 12 SP2`


<!-- Slide -->
### Kernel
4.4-based

<br> 
### Hypervisor <!-- .element class="fragment" data-fragment-index="1"-->
KVM, Xen<!-- .element class="fragment" data-fragment-index="1"--> 

Hyper-V, VMWare vSphere<!-- .element class="fragment" data-fragment-index="1"-->

IBM z/VM <!-- .element class="fragment" data-fragment-index="1"-->

Docker <!-- .element class="fragment" data-fragment-index="1"-->

Note: Kernel API/ABI compatibility


<!-- Slide -->
Deployment
 
## Crowbar 
(`v4.0`)

and 

## Chef
(`v10`)


<!-- Slide -->
### Openstack Support

All Core Services plus

<table>
<tr>
    <td><img src="images/openstack/barbican-techpreview.svg"></td>
    <td><img src="images/openstack/ceilometer.svg"></td>
    <td><img src="images/openstack/designate-techpreview.svg"></td>
    <td><img src="images/openstack/fuel-notsupported.svg"></td>
</tr>
<tr>
    <td><img src="images/openstack/heat.svg"></td>
    <td><img src="images/openstack/horizon.svg"></td>
    <td><img src="images/openstack/ironic-techpreview.svg"></td>
    <td><img src="images/openstack/magnum.svg"></td>
</tr>
<tr>
    <td><img src="images/openstack/manila.svg"></td>
    <td><img src="images/openstack/mistral-notsupported.svg"></td>
    <td><img src="images/openstack/murano-notsupported.svg"></td>
    <td><img src="images/openstack/sahara-techpreview.svg"></td>
</tr>
<tr>
    <td><img src="images/openstack/tempest-techpreview.svg"></td>
    <td><img src="images/openstack/trove-techpreview.svg"></td>
    <td></td>
    <td><img src="images/openstack/legend.svg"></td>
</tr>
</table>


<!-- Slide -->
### Life Cycle 
New downstream version with 
 
###### every 2nd upstream release

Next: 
 
P-release
Note: every 2nd may no issue in enterprise setups, you don't switch that easily production.


<!-- Slide -->
Additionally recommended
 
### SUSE Studio
### SUSE Manager
### SLES HA extension 
(for KVM/Xen compute nodes)


<!-- Slide -->
### Support

at least
###### 27 months
after GA


<!-- Slide -->
### Pricing
 
control node

admin node

compute node, per-socket-pair (SLES)

<br>
##### depending on:
 
12x5 or 24x7

special SLAs
Note: like `scheduled standby`, Support engineer (ASE/PSE/DSE)


<!-- Slide -->
# 2
## Ceph


<!-- Slide -->
###### SUSE Enterprise Storage 3

based on

### Jewel

with 

`Calamari`


<!-- Slide -->
Deployment via
### Crowbar
or
### Salt
(tech preview)


<!-- Slide -->
## Features
###### CephFS
Tech preview in v3
###### iSCSI
to connect Windows and VMWare
Note: SES4 - CephFS Use Cases and NFS-Ganesha tech preview


<!-- Slide -->
## Pricing

per node

Basis subscription:

with 4 OSDs, 3/5 MONs, Admin/Deploy node

priority support included
Note: release every 6 months, support for N and N-1, longer cycles on request


<!-- Slide -->
# 3
## More


<!-- Slide -->
You should know:

##SUSE

Is the only distro

which does `not` charge for

development of `upstream features`

if you agree on it!

All included in the subscription!

