---
title: accord
description: testing accord
tags: [tutorial>advanced, tutorial>www, tutorial>lll, agreements>Service-Descriptions, tutorial>gateway, semaphore-rejected>SAP-Simple-Finance, tutorial>product>sap-ui5, tutorial>Java-Connector-API-(JCo), agreements>maintenance-/-support-agreements, tutorial>Servlets-/-JSP, tutorial>product>mobile, language>Serbian---Latin, solution>security, agreements>aaa, agreements>general-Terms-&-Conditions, tutorial>ttt, tutorial>new-tag, tutorial>test, tutorial:technology/maven, redirect>types]
qrcode: true
---

## Prerequisites  
 - **Proficiency:** Beginner 
 - **Web IDE** If you don't have the Web IDE open, follow these steps: [Enable and open the HANA Cloud Platform Web IDE](https://go.sap.com/developer/tutorials/sapui5-webide-open-webide.html)
 - **Tutorials:** This tutorial is part of a series.  The previous tutorial is [Set up the Northwind Destination](https://go.sap.com/developer/tutorials/hcp-create-destination.html)

### Time to Complete
bxcvbvlcbjkcvjjbklcvbjcv

## Next Steps
 - This tutorial is part of a series.  The next tutorial is part 4: [Add a list to the current view](https://go.sap.com/developer/tutorials/sapui5-webide-add-list.html)

## Details
### You will learn  
Now that you have set up a Destination in the HANA Cloud Platform (HCP) cockpit, you will connect that destination to your local application.  


## Prerequisites  
- [Access your first data in a SAP HANA XSC Application](http://go.sap.com/developer/tutorials/hana-data-access-authorizations.html)

#### Using the SAP HANA Developer Edition or SAP HANA Cloud Platform
The workbench allows you to develop on HANA without the need to set up a local development environment.
 ## Script Examples
 simle text
## Script 45646564
### Script Examples
#### Script Examples
 
>### Warning
>This is a Warning.

&nbsp;

>### Caution
>This is a Caution.

&nbsp;

>### Note

>This is a note.


```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

Here's an example that uses [cmdlet names)] to [task]. It includes commands that:

- [short verb, uses, has, is, etc]
- [next short verb] 

<!--include this statement if it uses variables that weren't introduced earlier--> It includes the following variables:

- [variable 1]
- [variable 2]

Sometimes you want numbered lists:

1. One
2. Two 
3. Three

Sometimes you want bullet points:

* Start a line with a star
* Profit!

You can create nested lists: 

* item1
    * one_one
    * two



 [ACCORDION-BEGIN [STEP 1](The workbench allows you to develop on HANA without the need to set up a local development environment The workbench allows you to develop on HANA without the need to set up a local development environment)] 
 
 ***Task Lists*** (Please note, this requires empty line before task list):

  **Example:** 
  
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item
 [ACCORDION-END]
 [ACCORDION-BEGIN [STEP 2](#step1)] 
 ![Image1] (tags.png)
 [ACCORDION-END]
  [ACCORDION-BEGIN [](kjhjkhjhkjhjkj)] 
 First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

and

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |

 [ACCORDION-END]
 
  [ACCORDION-BEGIN [STEP 2](Bulleted lists)] 
 ![Image1] (tags.png)
 ## Script Examples

Here's an example that uses [cmdlet names)] to [task]. It includes commands that:

- [short verb, uses, has, is, etc]
- [next short verb] 

<!--include this statement if it uses variables that weren't introduced earlier--> It includes the following variables:

- [variable 1]
- [variable 2]

<!--This shows you how a recent example was presented as well as how it was formatted. Preceding each line with one tab or four spaces to format in a code block-->

Sometimes you want numbered lists:

1. One
2. Two 
3. Three

Sometimes you want bullet points:

* Start a line with a star
* Profit!

You can create nested lists: 

* item1
    * one_one
    * two
 [ACCORDION-END]
 
  [ACCORDION-BEGIN []()] 
simle text
## Script 45646564
### Script Examples
#### Script Examples
 190 lines_
```javascript
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username –Password
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username –Password
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
``` 
 [ACCORDION-END]
 
Login to the [HANA Cloud Cockpit](https://account.hanatrial.ondemand.com/cockpit) with your free developer edition account.


 [ACCORDION-BEGIN [STEP 1](#step1)] 
 test
 test1
 [ACCORDION-END]
 [ACCORDION-BEGIN [STEP 2](#step1)] 
 ![Image1] (tags.png)
 [ACCORDION-END]
  [ACCORDION-BEGIN [](kjhjkhjhkjhjkj)] 
 First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

and

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |

 [ACCORDION-END]
   [ACCORDION-BEGIN [STEP 2](#step1)] 
 ![Image1] (tags.png)
 [ACCORDION-END]
   [ACCORDION-BEGIN [ ]( )] 
 >### Warning
>This is a Warning.

&nbsp;

>### Caution
>This is a Caution.

&nbsp;

>### Note

>This is a note.

 [ACCORDION-END]
 [ACCORDION-BEGIN [STEP test](test)] 
 <http://tut.by>
<address@example.com>

```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

```js
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

 [ACCORDION-END]
 
