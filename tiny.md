---
layout: default
---

<h3><a href="./"><img src="assets/images/back.png" style="width:20px;height:20px;"> back to home page</a></h3>
<br>
* * *

## TINY: A diagnostic tool powered by sunlight, a flame, or electricity

<a href="https://www.nature.com/articles/s41551-018-0286-y" target="blank">This work has been published in Nature BME.<img src="assets/images/external-link.png" style="width:20px;height:20px;"></a> You can also visit two news articles (<a href="http://news.cornell.edu/stories/2018/09/tiny-cancer-detection-device-proves-effective-uganda-testing" target="blank">Link 1<img src="assets/images/external-link.png" style="width:20px;height:20px;"></a>, <a href="http://news.cornell.edu/stories/2016/08/1m-nih-grant-helps-researchers-refine-quick-cancer-test" target="blank">Link 2<img src="assets/images/external-link.png" style="width:20px;height:20px;"></a>) that were published about TINY.

<a href="assets/img/uganda.jpg" data-lightbox="image-1" data-title="This picture was taken during TINY deployment outside a healthcare facility in Uganda, November 2017. I am heating up the system using sunlight - you may be able to see the acrylic Fresnel lens which is concentrating sunlight into the device. After heating, a human sample will be placed inside the device and analyzed for the presence of specific nucleic acids. The assay is monitored using the optical system that I designed and built."><img src="assets/img/uganda_small.jpg" style="border:1px solid black"></a>

I have designed, built, and deployed a portable, nucleic acid diagnostic tool for use in Africa. It is the first diagnostic device that can be powered by sunlight, flame, and/or electricity. This makes it particular useful in locations with unreliable access to electricity.

My colleagues and I traveled to Uganda (in East Africa) in 2016 and 2017 to deploy the device at multiple healthcare institutions. We took 5 TINY systems with us.

<a href="assets/img/tinyassembly.jpg" data-lightbox="image-1" data-title="I built 5 TINYs for our 2017 field trial in Uganda. I designed all the parts you see here. The two right-most parts hold the optical components: bandpass filters, LEDs, and photodiodes. I was initially fabricating all of these parts during our first experiments; however, we started outsourcing everything before deployment to Uganda."><img src="assets/img/tinyassembly_small.jpg" style="border:1px solid black"></a>

This project has been an amazing opportunity to build an intricate system from the ground-up. The interior of the system is designed to stay isothermal at 68°C for an extended period of time: temperature stability is imperative for the nucleic acid assay. Through careful thermal engineering and use of a phase change material, the device can continue to perform the assay isothermally for over an hour in the case of complete electricity outages. If electricity is completely unavailable, sunlight or a flame may be used to heat the device to 68°C.

We experienced many electricity outages mid-assay during our field deployment in Uganda. The system performed flawlessly through the power outages and continued to make its nucleic acid measurement without electrical heating.

<a href="assets/img/Heatprofile.png" data-lightbox="image-1" data-title="This data shows the temperature inside TINY. The dotted lines show the isothermal target range, which is important to maintain for the nucleic acid assay. The top graph shows that the system tends to stabilize around the target temperature even when over- or under-heated. The bottom graph shows the automated heating of TINY when electricity is available."><img src="assets/img/Heatprofile_small.png" style=""></a>

I designed the mechanical parts, the electronics, and the optics for TINY. TINY uses sensitive photodiodes to detect very small changes in light, which enables us to determine if a target nucleic acid is present in a sample.

I should note that this effort has been part of international collaboration. While I have led all the engineering work, my colleagues at Weill Cornell Medicine, UC San Francisco, and the Infectious Diseases Institute in Uganda have worked incredibly hard on the diagnostic and clinical side of this project. It has been a joy to work with such a devoted and talented team of scientists.

It's difficult to summarize such a large project in a couple of paragraphs. Please refer to our <a href="https://www.nature.com/articles/s41551-018-0286-y" target="blank">TINY publication<img src="assets/images/external-link.png" style="width:20px;height:20px;"></a> for more details.

<a href="assets/img/TINYhand.png" data-lightbox="image-1" data-title="Portability is very important when building a diagnostic tool for resource limited settings. TINY weighs 1.1 kg and is the size of a very small lunchbox."><img src="assets/img/TINYhand_small.png"></a> &nbsp;&nbsp;&nbsp;<a href="assets/img/insidepcb.jpg" data-lightbox="image-1" data-title="On the opposite side of this PCB are 6 photodiodes for measuring the progress of 6 separate nucleic acid assays. The IC on the right is a local temperature sensor. The Molex connector in the middle is used to send signals to a central PCB."><img src="assets/img/insidepcb_small.jpg" style="border:1px solid black"></a>
