---
bg: "20160525_201702082_iOS.jpg"
layout: page
title: "Tips"
crawlertitle: "Tips to help with everything that I found"
permalink: /tips/
summary: "Tips to help with everything that I found"
active: tips
---
<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [Great Tips](#great-tips)
  - [Python Tips for Astronomy](#python-tips-for-astronomy)
    - [Anaconda Python Enviromennt](#anaconda-python-enviromennt)
    - [Astroconda](#astroconda)
  - [Data reduction](#data-reduction)
    - [Iraf installation on Ubuntu 16.04 using astroconda](#iraf-installation-on-ubuntu-1604-using-astroconda)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Great Tips 

## Python Tips for Astronomy

### Anaconda Python Enviromennt

Install [Anaconda Python][anaconda]

### Astroconda

Install [astroconda][astroconda]

## Data reduction

### Iraf installation on Ubuntu 16.04 using astroconda

After installation of astroconda enviromennt on Ubuntu 16.04, you have to install some 32-libraries that don't came to OS:

{% highlight ruby %}
sudo apt install libc6:i386 libz1:i386 libncurses5:i386 libbz2-1.0:i386 libuuid1:i386 libxcb1:i386 libxmu6:i386
# 32 libraries to work astroconda IRAF enviromennt
{% endhighlight %}


<!-- references -->
[astroconda]:http://astroconda.readthedocs.io/en/latest/
[anaconda]: https://www.continuum.io/downloads