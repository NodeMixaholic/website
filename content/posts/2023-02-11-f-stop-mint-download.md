---
title: 'F-Stop Mint Download *Sid Distro*'
author: sam_lord
type: post
date: 2023-02-11T16:59:15+00:00
url: /2023/02/11/f-stop-mint-download/
categories:
  - Uncategorized

---
A user-friendly, near-vanilla **Debian Sid** distro with AI and a new package manager front-end (**node-get**); has remote updates. Inspired by the thought (**_&#8220;What if Linux Mint was based on Debian Sid, had AI, a different package manager front-end, used XFCE and not Cinnamon, and the user had to connect to the WLAN via nmcli.&#8221;)_** from myself.

The username and password for the livecd are both **&#8220;live&#8221;** (no quotes)

Not to mention, built in Intel Wi-Fi support in the setup. Note: You must connect to Wi-Fi via **<a href="https://www.makeuseof.com/connect-to-wifi-with-nmcli/" target="_blank" rel="noreferrer noopener nofollow">&#8220;nmcli&#8221;.</a>** Ethernet should work out of the box.

## Help! Error that contains &#8220;&#8216;/lib/live/boot&#8217;: No such file or directory&#8221; when I install drivers/update intramfs/kernel!

Here&#8217;s a hacky fix to help you out:

<pre class="wp-block-code"><code>sudo mkdir /lib/live && sudo mkdir /lib/live/boot</code></pre>

Note that the latest &#8220;nvidia-easyinstall&#8221; does this by default to help the end-user. Install it along with all other updates by doing this:

<pre class="wp-block-code"><code>sudo node-get system-upgrade</code></pre>

<div class="is-layout-flex wp-block-buttons">
  <div class="wp-block-button">
    <a class="wp-block-button__link wp-element-button" href="https://www.sparksammy.com/iso/FStop_Mint.iso">Download it here</a>
  </div>
</div>