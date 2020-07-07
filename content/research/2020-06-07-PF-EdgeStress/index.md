---
title: Crack propagation under lattice asymmetry in h-BN
author: Bo Ni
date: '2020-06-07'
categories: []
tags:
  - Lattice asymmetry
  - Polarized edge stress
  - Anisotropic fracture energy
  - 2D materials
  - Phase field
  - LEFM
subtitle: ''
summary: 'Recent experimental measurements have discovered the fracture toughness of monolayer h-BN is much large than its intrinsic surface energy and based on DFT calculations toughening mechanisms of <strong>crack tip bifurcation</strong> and <strong>edge swapping</strong> due to the lattice asymmetry have been proposed. In this study, combining <strong>theoretical analysis</strong> and <strong>phase field (PF) modeling</strong>, we study the effect of the polarized edge stress and anisotropic fracture energy on the fracture of h-BN. It is found that polarized edge stress can contribute a mode II stress intensity factor (SIF) travelling with the crack tip and the competing of local lattice asymmetry and gloabl extrenal loading can result in a zigzag crack path with swaping branches.'
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

##  **The tie between surface effect and fracture**

Fracture, as a process of creating new surfaces in materials, intrisically has a strong tie to the properties of surface. For example, in the begining of fracture mechanics, by considering the energy transformation between bulk deformation and creating new surfaces, Griffith formulated the energetic view of fracture and lay the very foundation of fracture mechanics. 

<div class="row">

  <!-- **__**   -->
</div>
<div class="row">
  <div class="col-12 col-lg-12">
    {{< figure src="loc-ima/SS-1.jpg" title="Figure 1. Griffith view of fracture as a process of creating new surfaces" >}}
  </div>
  <!-- <div class="col-12 col-lg-5">
    {{< video src="loc-video/brittle_graphene.mp4" >}}
  </div> -->
</div>

Because atoms near the surface/edge enjoy an enviroment different from that in the bulk, the mechanical properties of surface/edges are usually different from thoes of the bulk. Especially, in low-dimensional nano-materials or soft materials, surface stress can affect the behavior of the whole material systems (including inducing phase transformation, size-dependent elastic properties, buckling patterns and so on).

<div class="row">

  <!-- **__**   -->
</div>
<div class="row">
  <div class="col-12 col-lg-12">
    {{< figure src="loc-ima/SS-2.jpg" title="Figure 2. Surface effects in low-dimensional nano-materials (Diao, et al. Nature mat 2.10 (2003): 656. Lai, S. L., et al. APL 72.9 (1998): 1098-1100.  Cuenot, Stéphane, et al.  PRB 69.16 (2004): 165410. Shenoy, V. B., et al. PRL 101.24 (2008): 245501. Alred, John M., et al. Nano Research 8.6 (2015). Xie, Saien, et al. Science359.6380 (2018): 1131-1136. )" >}}
  </div>
  <!-- <div class="col-12 col-lg-5">
    {{< video src="loc-video/brittle_graphene.mp4" >}}
  </div> -->
</div>

The effect of surface elasticity on a crack tip has also been discussion previously. For example, tensile residual stress may reduce mode I SIF and increses mode II and surface elastic modulus can locally adjust the stress field at the crack tip at nano-scale. 

<div class="row">

  <!-- **__**   -->
</div>
<div class="row">
  <div class="col-12 col-lg-12">
    {{< figure src="loc-ima/SS-3.jpg" title="Figure 3. Effect of residual surface stress on a blunt Mode-I crack: Tensile residual stress reduces mode-I SIF and increases shear (Wang, G. F., and Y. Li.  EFM 109 (2013): 290-301. Fu, X. L., G. F. Wang, and X. Q. Feng.  EFM 77.7 (2010): 1048-1057.)" >}}
  </div>
  <!-- <div class="col-12 col-lg-5">
    {{< video src="loc-video/brittle_graphene.mp4" >}}
  </div> -->
</div>


##  **New challenge from h-BN: asymmetric surfaces**

Recently, experimental study of fracture of monolayer hexagonal-boron nitride (h-BN) discovered that the effective fracture toughness of h-BN is one-order of magnitude higher that its Griffith energy release rate. Further DFT calculations suggest that the asymmetric lattice structure of h-BN w.r.t the crack can result in intrinsic toughening mechanisms of crack tip bifurcation and edge swapping. 

However, limited by the model size, DFT calculations can not directly unveil crack evolution process under such lattice asymmetry. Also, in the contiuum level, h-BN represents a new senario of asymmetric surfaces, (i.e., B-edges and N-edges with different edge stress and edge elasticity), which is shared with other multicomponent 2D materials, such as TMDs. How can we understand these toughening mechanisms and the fracture process under the presence of lattice asymmetry?

<div class="row">

  <!-- **__**   -->
</div>
<div class="row">
  <div class="col-12 col-lg-12">
    {{< figure src="loc-ima/SS-4.jpg" title="Figure 4. Fracture test of h-BN and asymmetric surface properties of h-BN (Song, Z. G., et al. under review)" >}}
  </div>
  <!-- <div class="col-12 col-lg-5">
    {{< video src="loc-video/brittle_graphene.mp4" >}}
  </div> -->
</div>

Without the loss of generalitiy, in this study, we try to study this new challenge in the framework of fracture mechanics and surface effect by integrating theoretical analysis and numerical simulations.

##  **Crack initiation: effect of asymmetric surface stress**

By including surface layers with asymmetric surface stress and surface elastic modulus for the upper and lower crack surfaces, we can estimate the change of stress intensity factors (SIF) at the crack tip theoretically. We found that 
* symmetric surface stress can induce extra mode I SIF
* asymmetric surface stress can induce extra mode II SIF
* the effect of surface elastic modulus is relatively weaker than that of the surface stress.

<div class="row">

  <!-- **__**   -->
</div>
<div class="row">
  <div class="col-12 col-lg-12">
    {{< figure src="loc-ima/SS-5.jpg" title="Figure 5. SIF due to symmetric/asymmetric surface stress" >}}
  </div>
  <!-- <div class="col-12 col-lg-5">
    {{< video src="loc-video/brittle_graphene.mp4" >}}
  </div> -->
</div>

The nontrivial the mode II SIF under the presence of asymmetric surface stress indicate that the crack has a tendency to deflect away from its original direction, which is indeed predicted in DFT calculations. Also, this mode II SIF come from the crack surface right behind the crack tip and will always travel with the crack tip. Combining the asymmetry of h-BN lattices, as the crack deflects aways from the orignal path, the chemical components of the upper and lower crack surfaces will switch, correspondly the surface stress and sign of the extra mode II SIF. This automatic switch make the crack path swapping possible.

## **Crack in action: PF model with fracture anisotropy and asymmertic surface stress**

To study the crack propagation under such asymmetric lattice geometry, we adopt a Phase Field framework. For the specific lattice and surface stress in h-BN, we extend the PF model by including 
* an fracture energy/fracture driving force with hexagonal anisotropy
* an new surface phase tracing the crack and providing asymmeteric surface stress.

With an anisotropic fracture driving force and asymmertic surface stress, the crack can switches between different preferred orientation. And the leading crack tip will shield other slower crack branches.

<div class="row">

  <!-- **__**   -->
</div>
<div class="row">
  <div class="col-12 col-lg-6">
    <p>crack phase, d</p>
    {{< video src="loc-video/crack-d-fracture-aniso.mp4" >}}
  </div>
  <div class="col-12 col-lg-6">
    <p>sign of surface stress<p>
    {{< video src="loc-video/crack-surfaces-fracture-aniso.mp4" >}}
  </div>
</div>

As the amplitude of the asymmetric surface stress increase the overall crack path will be deflected towards one side and the periodicity of edge swapping is further affected. By analyzing the history of crack path as well as the surface stress, we can understand the zigzag crack paths as the consequence of the competition between the surface stress effect local to the crack tip and the influence of global external loading. Also, as the local mode II SIF tends to bend the crack path away from the preferred path of the extranl loading, the effective toughness of the material can be enhanced beyond the intrinsic energy release rate of Griffith prediciton, which explain the toughening mechanisms in h-BN. 

<div class="row">

  <!-- **__**   -->
</div>
<div class="row">
  <div class="col-12 col-lg-12">
    {{< figure src="loc-ima/SS-6.jpg" title="Figure 6. Zigzag crack paths under different amplitude of asymmetric surface stress" >}}
  </div>
  <!-- <div class="col-12 col-lg-5">
    {{< video src="loc-video/brittle_graphene.mp4" >}}
  </div> -->
</div>


More detailes can be found in the following publication.<br>

Yang Y, Song Z, Lu G, Zhang Q, **Ni B**, Wang Chao, Li X, Gu L, Xie X, Gao H and Lou J. Lattice asymmetry induced intrinsic toughening and stable crack propagation in monolayer h-BN. (Under review)

**Ni B**, Gao H. Phase field modeling of crack propagation under asymmetric surface stress. (Under working)

