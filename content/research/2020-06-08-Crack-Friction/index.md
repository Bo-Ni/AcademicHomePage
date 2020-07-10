---
title: Fracture under interlayer sliding in multilayered 2D materials
author: Bo Ni
date: '2020-06-08'
categories: []
tags:
  - Interlayer friction
  - asynchronous crack
  - Multilayered system
  - 2D materials
  - Cohesive element
  - Phase field
  - LEFM
subtitle: ''
summary: '2D materials communicate with the environment through large area of surface. Recent experimental measurements have deepened our understanding of the <strong>friction</strong> between layers of 2D materials and suggested the interlayer properties, such as interlayer friction, can couple with intralayer properties and affect the overall behavior of multilayered 2D material systems. In this study, the effect of interlayer friction on <strong>asyncronous crack propogation</strong> and <strong>dissimilar crack paths</strong> is considered by integrating theoretical analysis and numerical simulation. It is found that the intact layer can <strong>postpone</strong> crack propogation in the neighbouring layer and cracks along dissimilar paths can <strong>communicate</strong> via interlayer sliding zone, resulting in a <strong>size-dependent</strong> fracture behavior.'
authors: []
featured: no
disable_jquery: no
image:
  caption: ''
  focal_point: ''
  preview_only: yes
projects: []
gallery_item:
 - album: 
   image: 
   caption: 
---

##  **Interlayer sliding in multilayered 2D materials**

As atomically thin layers, 2D materials have large area of surfaces and interact with surroundings, including other layers, substrate or matrix materials, via interfaces. Consistent efforts have been devoted into understanding the interlayer properties of multilayered 2D materials. For example, different experimental methods have been developed to measure the interlayer shear strength or interlayer sliding stress for 2D materials, including graphene, MoS2, h-BN and graphene oxide films.

<div class="row">

  <!-- **__**   -->
</div>
<div class="row">
  <div class="col-12 col-lg-12">
    {{< figure src="loc-ima/Friction-1.jpg" title="Figure 1. Measure interlayer shear strength/sliding stress ( Wang, Guorui, et al.  Physical review letters 119.3 (2017): 036101. Oviedo, Juan Pablo, et al.  ACS nano 9.2 (2014): 1543-1551.) Liu, Shu-Wei, et al.  Nature communications 8 (2017): 14029. Daly, Matthew, et al.  ACS nano 10.2 (2016): 1939-1947." >}}
  </div>
  <!-- <div class="col-12 col-lg-6">
    {{< figure src="loc-ima/Friction-2.jpg" title="Figure 2. Range of interlayer sliding stress(Liu, Shu-Wei, et al.  Nature communications 8 (2017): 14029. Daly, Matthew, et al.  ACS nano 10.2 (2016): 1939-1947.)" >}}
  </div> -->
</div>

##  **Low friction vs low fracture toughness**

Crystalline 2D materials often show relatively low friction as some of them are good solid lubriant. One contributing factor is the sharp constract between weak interlayer interaction and strong intralayer covalent bonding. At the same time, most 2D materials have low fracture toughness and are fragile to cracks. The coupling between interlayer friction and intralayer fracture remains a possibility. For example, carcks in a trilayered graphene sample is observed to propogate along dissimilar paths in an asynchronous manner. Crack blocking, the second layer fracture and crack branching are captured in bilayered MoS2 via experimental observation and atomistic simulations. 

<div class="row">

  <!-- **__**   -->
</div>
<div class="row">
  <div class="col-12 col-lg-12">
    {{< figure src="loc-ima/Friction-2.jpg" title="Figure 2. Crack propagation in a trilayered graphene system and a bilayered MoS2 systems (Jang, Bongkyun, et al. Nanoscale 9.44 (2017): 17325-17333. Jung, Gang Seob, et al.  ACS nano 12.4 (2018): 3600-3608.)" >}}
  </div>
  <!-- <div class="col-12 col-lg-6">
    {{< figure src="loc-ima/Friction-2.jpg" title="Figure 2. Range of interlayer sliding stress(Liu, Shu-Wei, et al.  Nature communications 8 (2017): 14029. Daly, Matthew, et al.  ACS nano 10.2 (2016): 1939-1947.)" >}}
  </div> -->
</div>

As the application of multilayered 2D materials keeps increasing, ranging from reinforcing phase in composites, protective coating, Van der Waals heterostructures to flexible electronic devices, a systematic understanding of the interaction between interlayer friction and intralyer fracture of multplayered 2D materials gain importances for not only advancing fundamental knowledge in fracture mechanics but also robust engineering performances.


<div class="row">

  <!-- **__**   -->
</div>
<div class="row">
  <div class="col-12 col-lg-12">
    {{< figure src="loc-ima/Friction-3.jpg" title="Figure 3. Multilayered 2D materials in various applications(Wang, Lidong, et al.  Scientific reports 7 (2017): 41896. b. Preston, Daniel J., et al. Nano letters 15.5 (2015): 2902-2909. c. Liu, Yuan, et al.  Nature Reviews Materials 1.9 (2016): 16042.)" >}}
  </div>
  <!-- <div class="col-12 col-lg-6">
    {{< figure src="loc-ima/Friction-2.jpg" title="Figure 2. Range of interlayer sliding stress(Liu, Shu-Wei, et al.  Nature communications 8 (2017): 14029. Daly, Matthew, et al.  ACS nano 10.2 (2016): 1939-1947.)" >}}
  </div> -->
</div>

In this study, we focus on the fundamentals of the interaction between interlayer friction and intralayer fracture and propose model problems of asynchronous crack propogation and dissimilar crack paths in the framework combining fracture mechanics and interface mechanics, in hope to unviel the universal feature of the effect of interlayer sliding on cracks in multilayered 2D materials.

##  **Model problems: asynchronous crack propogation and dissimilar crack paths**

Without the loss of generality, we construct model problems of a bilayered system of brittle elastic membranes. The interlayer shearing stress due to sliding is represented by a constant interlayer sliding strength, tau_0. As the possible geometery of cracks in the two layer can be quite complicated, we focus on two model problems describing the asynchronous crack propogation in time and the dissimilar crack paths in space.

* Asynchronous crack model: an edge crack sitting in the top layer while the bottom layer is intact.
* Dissimilar crack path model: Two parallel edge cracks in two layers respectively.

Via steady steady analysis, we obtain the driving froce on the crack tip and the critical loading for the failure of the bi-layer system. Cohesive element simulations are used to validate the theoretical prediction while phase field modelling is adopted to demonstrate the potential complexity of crack propagation.

As the work is still under development, only some selected results are previewed in the following.

<div class="row">

  <!-- **__**   -->
</div>
<div class="row">
  <div class="col-12 col-lg-12">
    {{< figure src="loc-ima/Friction-4.jpg" title="Figure 4. Model problems of crack propagation in a bi-layered system in the presence of interlayer sliding." >}}
  </div>
  <!-- <div class="col-12 col-lg-6">
    {{< figure src="loc-ima/Friction-2.jpg" title="Figure 2. Range of interlayer sliding stress(Liu, Shu-Wei, et al.  Nature communications 8 (2017): 14029. Daly, Matthew, et al.  ACS nano 10.2 (2016): 1939-1947.)" >}}
  </div> -->
</div>

##  **Smaller is stronger, Stiffer is better**
According the theoretical analysis, we find the critical load for the leading crack in the asynchronous crack model to propagate depends on not only the size of the sample but also the stiffness of the bottom layer. As the sample height increases, the critial loading strain will approach to a constant, which is very different from the case of crack propogation in a single layer. Also, choosing a stiff bottom lay can postpone the crack propogation in the top layer and toughen the system.

<div class="row">

  <!-- **__**   -->
</div>
<div class="row">
  <div class="col-12 col-lg-12">
    {{< figure src="loc-ima/Friction-5.jpg" title="Figure 5. Effect of sample size and bottom layer stiffness on the crack propogation in the top layer" >}}
  </div>
  <!-- <div class="col-12 col-lg-6">
    {{< figure src="loc-ima/Friction-2.jpg" title="Figure 2. Range of interlayer sliding stress(Liu, Shu-Wei, et al.  Nature communications 8 (2017): 14029. Daly, Matthew, et al.  ACS nano 10.2 (2016): 1939-1947.)" >}}
  </div> -->
</div>


##  **Leading crack propogation vs second layer failure**
For the asynchronous crack model, a competition exists between crack propogation in the 
top layer and the strength failure of the bottom layer as the two layers can "communicate" via the interlayer friction. By controlling the sample size and the fracture toughness of the material, the failure mode can switch between the two. We draw the phase diagram of this competition and find the good agreement with the numerical simulations. 

<div class="row">

  **Crack propogation in the top layer wins.**
</div>
<div class="row">
  <div class="col-12 col-lg-6">
    Top layer, sigma_22
    {{< video src="loc-video/s22_top.mp4" >}}
    Top layer, interlayer shear_22
    {{< video src="loc-video/t22_top.mp4" >}}
  </div>
  <div class="col-12 col-lg-6">
    Bottom layer, sigma_22
    {{< video src="loc-video/s22_bot.mp4" >}}
    Bottom layer, interlayer shear_22
    {{< video src="loc-video/t22_bot.mp4" >}}
  </div>
</div>

<div class="row">

  **Strength failure in the bottom layer wins.**
</div>
<div class="row">
  <div class="col-12 col-lg-6">
    Top layer, sigma_22
    {{< video src="loc-video/job_3_top_layer_s22.mp4" >}}
    Top layer, interlayer shear_22
    {{< video src="loc-video/job_3_top_layer_t2.mp4" >}}
  </div>
  <div class="col-12 col-lg-6">
    Bottom layer, sigma_22
    {{< video src="loc-video/job_3_bot_layer_s22.mp4" >}}
    Bottom layer, interlayer shear_22
    {{< video src="loc-video/job_3_bot_layer_t2.mp4" >}}
  </div>
</div>


<div class="row">

  **Phase diagram of the failure mode**  
</div>
<div class="row">
  <div class="col-12 col-lg-8">
    {{< figure src="loc-ima/Friction-6.jpg" title="Figure 6. The critial loading strain under the competition of crack propogation in the top layer and streng failure in the bot layer." >}}
  </div>
  <!-- <div class="col-12 col-lg-6">
    {{< figure src="loc-ima/Friction-2.jpg" title="Figure 2. Range of interlayer sliding stress(Liu, Shu-Wei, et al.  Nature communications 8 (2017): 14029. Daly, Matthew, et al.  ACS nano 10.2 (2016): 1939-1947.)" >}}
  </div> -->
</div>

##  **Leading crack propogation vs second layer failure**
For cracks with dissimilar paths, we find there exist critical distance determined by the fracture and friction properties of the layers, beyond which the two cracks will not "feel" each other and can propogate independently (Figure 7). This critical crack spacing make it possible to propogate multiple cracks in multilayered system (See the video below), which is in contract of the leading crack shielding effect in a monolayer case.


<div class="row">

  <!-- **Phase diagram of the failure mode**   -->
</div>
<div class="row">
  <div class="col-12 col-lg-12">
    {{< figure src="loc-ima/Friction-7.jpg" title="Figure 7. Two modes of interlayer sliding zones between parallel cracks." >}}
  </div>
  <!-- <div class="col-12 col-lg-6">
    {{< figure src="loc-ima/Friction-2.jpg" title="Figure 2. Range of interlayer sliding stress(Liu, Shu-Wei, et al.  Nature communications 8 (2017): 14029. Daly, Matthew, et al.  ACS nano 10.2 (2016): 1939-1947.)" >}}
  </div> -->
</div>

<div class="row">

  **Propogate two cracks beyond shielding effect.**
</div>
<div class="row">
  <div class="col-12 col-lg-6">
    Top layer, Sigam_22
    {{< video src="loc-video/s22_two_crack.mp4" >}}
  </div>
  <div class="col-12 col-lg-6">
    Top layer, interlayer shear_22
    {{< video src="loc-video/t22_two_crack.mp4" >}}
  </div>
</div>

More detailes and related discussion can be found in the following publication.<br>

**Ni B**, Gao H. Harness the Power of Fracture: Controlled Fragmentation of Graphene via Substrate Necking. Matter. 2020 Mar 4;2(3):521-4.

**Ni B**, Gao H. Crack propogation in multilayered 2D materials in the presence of interlayer sliding. (Under working)
