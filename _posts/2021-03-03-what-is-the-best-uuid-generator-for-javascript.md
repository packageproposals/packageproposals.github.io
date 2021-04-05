---
layout: post
title: What is the best UUID generator for javascript
date: 2021-03-02
summary: |
 Did you ever wish you to generate uuids for your javascript project ? well here are the available options .
tags: techtips javascript vue react
categories:
  - Tech Tips
  - Vue
  - Javascript
---

In this post we'll take a look at a .  

## Problem
The problem is simple enough... how do you automatically generate a uuid without going into the math complexity.


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
