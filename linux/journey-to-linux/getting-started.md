---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Getting Started

If you aren't feeling underconfident with Linux give it a try in a VM first. This will give you an idea and feel of Linux. This article will guide you through a [VM installation](https://linuxhint.com/get-started-linux/).

{% hint style="warning" %}
This is my suggestion. Switch over to Linux completely. If you Dual Boot, this will not only mess up you Linux installation but you won't use Linux as your daily driver.
{% endhint %}

## **So here the quick guide on you getting started with Linux installation.**

1. Make sure windows Bit-locker Encryption is turned off or you have your Bitlocker Key. If not follow this article [here](https://www.manageengine.com/products/os-deployer/help/how-to-disable-bitlocker-encryption.html).
2. After Bit-locker is turned off, download your favorite ISO. If you don't know how to choose one watch this [video](https://www.youtube.com/watch?v=dL05DoJ0qsQ).&#x20;

{% hint style="info" %}
this [Video](https://www.youtube.com/watch?v=hCBs2qVuc0Q) by Brodie Roberston will help you clear you basic terminology.
{% endhint %}

3. Download [Balena Etcher](https://etcher.balena.io/). Open it, select the USB Drive which you want to make a bootable one, select the ISO and let the software do it work.&#x20;
4. Once you have your bootable ready, Go into BIOS turn off the Secure Boot and Boot form the USB.&#x20;
5. Follow the installation setup and if everything did right you should have a running Linux System within 20 minutes.

{% hint style="info" %}
Make sure to select the proper Drive when installing. I'm assuming that you are using your whole disk instead of a partition. If you want custom layout you need to manually partition you disk.
{% endhint %}
