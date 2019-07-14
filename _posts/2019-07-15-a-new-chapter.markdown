---
layout: post
title: Open source, or commercial?
date: 2019-07-15T15:00:00Z
description: Is open source always the best solution? # Add post description (optional)
img: workflow.jpg # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: []
---

## The dilema

Open-source has many benefits when trying to develop software. In effect, I'd go as far as to say that it is not possible to produce a piece of software these days without using open source.  But this article isn't about open source libraries or scripts, but about full fledge applications.

For example, [Jenkins](https://jenkins.io/) vs [Bamboo](https://www.atlassian.com/software/bamboo) or [Jira](https://www.atlassian.com/software/jira) vs [OpenProject](https://www.openproject.org) or even [KVM](https://www.linux-kvm.org/page/Main_Page) vs [vSphere](https://www.vmware.com/ca/products/vsphere.html).

Cost is usually the biggest driver when selecting an open source solution over a commercial offering but there are a few other reasons.

### Convenience

Deploying a licensed application, regardless of price means that you have to purchase the license.  In most companies, that means having to engage the purchasing department to secure the license.  Needless to say that many larger companies have very complicated and elaborate workflows for purchasing software and end-users might have to wait for days or weeks (if not months) before they have the license file in hand.  While trial or demo licenses can get you started, they often run out before your purchasing department was able to get it for you.  And this can be quite frustrating when one of the options is to simply provide a credit card number and you get the license minutes later.

### Liberty

But more than that, it becomes an issue when you need multiple instances of the application.  In the era of DevOps, applications can be deployed often and everywhere.  Spinning up hundreds of database containers per day is no longer an easy task when you have to worry about licensing.  Are you running more instances than you're allowed to?  Or the number of cores these databases running on exceed the allowed number?  Going open source resolves all these issues because nobody cares how many instances of MariaDB you're running.

### Free as in free beer

Transfer of ownership of those licenses is also problematic.  Most open source simply require you to ensure you properly identify that you are using their software and transfer the same license to your end customer.  With commerical software, licenses might not even be transferrable and new licenses might need to be purchased by the end user which is an added complexity they might not desire to inherit.

### Change it all

Being open source, you are free to augment and modify the software and add missing funtionality you need.  That said, unless these are small changes or your are willing to invest a lot of time and energy on that software, making massive changes to open source is a committment and often you are not allowed to make said changes during work hours (and in some cases outside of work hours either) because your company owns everything you do, and that isn't compatible with open source.

## On the other hand...

Open source software has many limitations.  Software is born and dies at a very rapid rate, but even more so in open source.  If the application is supported by only a few developers and they decide to stop supporting it, you are left to hoping that another group will fork that project and carry the torch forward. But that doesn't happen often.

Since most open source software is developed by people using their free time, you cannot expect much from the software.  How can you compare an application developed by people in their free time versus developed by dedicated staff paid a good salary where the only goal they have all day is to improve that software.  And if an open source application has many more contributors to compensate, coordinating a lot of people that are only part time providing support is quite a massive undertaking.

Finally, there's always the risk that is looming that an open source project is adopted by a large company (like Oracle) that ends up steering the project in the direction they want and begin to hide all the nice new features behind "enterprise" editions.

The decision to select open source vs commercial solutions I believe needs to be done on a per case basis.  Selection factors include how popular an open source solution is, how many contributors it has, how many quality alternatives exists and any available standards that would allow to switch from one solution to another without too much impact.

Open source is here to stay and I believe will become even more prevalent in the future.  It's up to each of us to contribute back when we can to keep it growing.