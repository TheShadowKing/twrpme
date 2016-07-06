---
layout: device
title:  "LG Volt 2"
codename: LS751
downloadfolder: LS751
oldurl: http://teamw.in/project/twrp2/300
supportstatus: Current
maintainer: None
oem: LG
ddof: /dev/block/platform/msm_sdcc.1/by-name/recovery
---
{% include disclaimer.html %}

{% include supportstatus.html %}
Note: You must be rooted and vulnerable to ??? to install TWRP on this device.

<div class='page-heading'>Download Links:</div>
<hr />
<p class="text">Boost Mobile:</p>
<ul>
{% for mirror in site.data.mirrors %}
  <li>
    <a href="{{ mirror.baseurl }}g2spr">
      {{ mirror.description }}
    </a>
  </li>
{% endfor %}
</ul>
{% include twrpinstall.html %}

{% include ddinstall.html %}
