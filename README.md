# 多线程定时器，防止浏览器页面被切换后，自带定时器被降频，导致定时器变慢，开了线程后切换标签就不会降频了。

Momentum
========

Patches `setInterval`, `clearInterval`, `setTimeout` and `clearTimeout` to avoid browser throttling
these functions when tab is inactive. 


Usage
=====

Just add the script before using `setInterval`, `clearInterval`, `setTimeout` and `clearTimeout`.
For example you can add it with a `<script>` tag in the head before loading other javascript files.

