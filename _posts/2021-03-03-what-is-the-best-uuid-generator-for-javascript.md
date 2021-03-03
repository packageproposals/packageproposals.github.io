---
layout: post
title: What is the best UUID generator for javascript
date: 2021-03-02
summary: |
 Did you ever wish you could control when and who could get access to your Azure 
 VMs?  Well now you can using Azure Security Center's Just-In-Time access
 feature.
tags: techtips javascript vue
categories:
  - Tech Tips
  - Vue
  - Javascript
---

In this post we'll take a look at a feature of Azure Security Center called
Just-In-Time VM access.  This feature will allow you to timebox when and who has
access to your Azure VMs.  Black Hats will invariably look for open management
ports on your VMs.  RDP and SSH are often used by hackers as a possible entry
point for access to your environment.  Using JIT Access you can block access to
these ports and require users to submit a request in order to gain access during
a specific timeframe.  

## Problem
The problem is simple enough... how do you limit access to your VMs so that only
users you permit have access to your VMs and only during a time that you allow?
This is accomplished by configuring some rules on the NSG and/or Azure Firewall that
protect your VM's access until a request and a timeframe for access are approved.
The great thing about this is that Azure has wrapped this functionality up into
a service called [Just-In-Time
Access](https://docs.microsoft.com/en-us/azure/security-center/just-in-time-explained) and you can activate it today.



```php
/**
 *  Setup model event hooks
 */
public static function boot()
{
    parent::boot();
    self::creating(function ($model) {
        $model->uuid = (string) Uuid::generate(4);
    });
}
```
