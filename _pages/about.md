---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

This is Haitao's academic personal site! I am currently a M.S. student at ETH Zurich, majoring in [Computational Science and Engineering(CSE)](https://rw.ethz.ch/). I obtained my bachelor degree in [South China University of Technology](https://www.scut.edu.cn/en/) in July, 2021, where I developed my interest in computational science, especially in fields of materials and physics. 

During my study in ETH Zurich since 2021, I gradually learned fundamentals of CSE, including numerical methods and high performance computing, together with mathematical and machine learning basis. Then, I decided to specialize in computaional Roboitcs and started to grow interest in visual computing and computer graphics.

**Research interest:** I am open to any exciting combination of computer graphics, 3D vision and machine learning! (including Neural rendering, differentiable physically-based simulation, digital humans...)

<font size="5"> <strong> News: </strong> </font> <br>

**09/2023:** Start a semester project at [Disney Research|Studios](https://studios.disneyresearch.com/), supervised by Xianyao Zhang and overseen by Dr. Marios Papas and Prof. Markus Gross

**08/2023:** Start a semester project at [Interactive Geometry Lab](https://igl.ethz.ch/), supervised by Dr. Jing Ren and overseen by Prof. Olga Sorkine-Hornung

**09/2022:** Dematriculate from M.Sc in Material Science and Engineering, enrolled in master programme of Computational Science and Engineering at ETH Zurich

**09/2021:** Enrolled in master programme of Material Science and Engineering at ETH Zurich

**07/2021:** Graduate from South China University of Technology (SCUT), achieving B.Eng. in Material Science and Engineering. Bachelor thesis: Constructing Vitrimer-like Materials from Coordinative Self-Assembly Structure   

<font size="5"> <strong> Personal/course projects: </strong> </font> <br>

<html>
  <head>
  <meta name="google-site-verification" content="xDNWUvx6Q5EWK5YYSyKvK8DZTmvXhKsGX203Ll-BFFE" >	
  <meta name=viewport content="width=800" >
  <meta name="generator" content="HTML Tidy for Linux/x86 (vers 11 February 2007), see www.w3.org">
  <meta http-equiv="Content-Type" content="text/html; charset=UTF-8" />
  <style type="text/css">
  @import url(https://fonts.googleapis.com/css?family=Roboto:400,400italic,500,500italic,700,700italic,900,900italic,300italic,300);
  /* @import url(https://fonts.googleapis.com/css?family=Roboto:300,400,500,700|Roboto+Slab:100,300,400,500,700|Material+Icons); */
    /* Color scheme stolen from Sergey Karayev */
    .one
    {
    position: relative;
    }
    .two
    {
    position: absolute;
    transition: opacity .2s ease-in-out;
    -moz-transition: opacity .2s ease-in-out;
    -webkit-transition: opacity .2s ease-in-out;
    }
    .fade {
     transition: opacity .2s ease-in-out;
     -moz-transition: opacity .2s ease-in-out;
     -webkit-transition: opacity .2s ease-in-out;
    }
    span.highlight {
        background-color: #ffffd0;
    }
  </style>


<heading><strong>Detail-Preserving Fluid Simulation by Advection-Reflection Solver in <a href="https://www.taichi-lang.org/">Taichi</a></strong> </heading>
<table width="100%" align="center" border="0" cellspacing="0" cellpadding="20">
  <tr onmouseout="nice_stop()" onmouseover="nice_start()"> 

    <td width="40%">
      <div class="one">
      <img src='/images/pbs.gif' width="100%" >
      </div>
      
      <script type="text/javascript">
      function nice_start() { 
      document.getElementById('nice_shape').style.opacity = "1";
      }
      function nice_stop() { 
      document.getElementById('nice_shape').style.opacity = "0"; 
      }
      nice_stop()
      </script>
    </td>
    
    <td valign="top" width="75%">
          <papertitle>
          <strong>
            Detail-Preserving Fluid Simulation
          </strong>
          </papertitle>
    <br>
        <strong>Haitao Yu*</strong>,
        <a href="https://github.com/ccetaw">Jingyu Wang*</a>,
        <a href="https://github.com/amomorning"> Yichen Mo*</a>
        (* means equal contribution)
      <br>
        <em>Course project of Physically-Based Simulation in Computer Graphics HS2022 at ETH Zurich</em>
      <br>
       <a href="https://github.com/amomorning/pbs-fluid">Github Repo</a>
      <br>
      In this project, we implement a fluid simulator with Taichi, which incroperates bunch of different numerical algorithms based on pervasive Advection-Projection methods. In specific, we compare the visual effect of a 2D plume among different algorithms, together with algorithm explanations. Especially, we also implement <a href="https://jzehnder.me/publications/advectionReflection/">advection-refelction</a> scheme according to this paper for better energy perservasion.
    </td>
  </tr>
</table>
<hr>

<heading><strong>Multi-Agent Reinforcement Learning Based Sample Consensus for Robust Estimation</strong> </heading>
  <table width="100%" align="center" border="0" cellspacing="0" cellpadding="20">  
    <tr onmouseout="holo_stop()" onmouseover="holo_start()">  
            <td width="40%">
              <div class="one">
                  <img src='/images/MARLSAC.png' width="100%"/>
                </div>

              <script type="text/javascript">
              function holo_start() { 
              document.getElementById('holo_shape').style.opacity = "1";
              }
              function holo_stop() { 
              document.getElementById('holo_shape').style.opacity = "0"; 
              }
              holo_stop()
              </script>
            </td>
      <td valign="top" width="75%">
            <papertitle>
            <strong>
            Multi-Agent Reinforcement Learning Based Sample Consensus for Robust Estimation
            </strong>
            </papertitle>
      <br>
          <strong>Haitao Yu*</strong>,
          Zhiyuan Huang*,
          Turlan Kuzhagaliyev*,
          Saurabh Vaishampayan*,
          David Feng*
          (* means equal contribution)
        <br>
          <em>Course project of 3D Vision 2023 in ETH Zürich</em>
        <br>
        <a href="https://drive.google.com/file/d/1fkOCVTuatSYTuB6-asWYeytRvmKydHlo/view?usp=drive_link"> Report </a> | 
        <a href="https://github.com/sputnik524">Github Repo </a>
        <br>
        In this project, we propose and implement a Multi-Agent extension of RLSAC, a single-agent reinforcement learning based pipeline to perform robust sample consensus estimation. Particularly, we implement two broad categories of MARL: Counterfactual Policy Gradients (COMA)and Multi-Agent Soft Actor Critic, under the customized RLSAC environment.</td>
    </tr>
  </table>
  <hr>

<heading><strong>Extension on Physically-based Renderer: <a href="https://cgl.ethz.ch/teaching/cg22/www-nori/index.html/">Nori</a></strong> </heading>
  <table width="100%" align="center" border="0" cellspacing="0" cellpadding="20">  
    <tr onmouseout="kombu_stop()" onmouseover="kombu_start()">  
            <td width="40%">
              <div class="one">
                  <img src='/images/FinalScene.png' width="100%"/>
              </div>

              <script type="text/javascript">
              function kombu_start() { 
              document.getElementById('kombu_shape').style.opacity = "1";
              }
              function kombu_stop() { 
              document.getElementById('kombu_shape').style.opacity = "0"; 
              }
              kombu_stop()
              </script>
            </td>
      <td valign="top" width="75%">
            <papertitle>
            <strong>
            Extension on Physically-based Renderer: Nori
            </strong>
            </papertitle>
      <br>
          <strong>Haitao Yu</strong>
        <br>
          <em>Course project of Computer Graphics 2022 in ETH Zürich</em>
        <br>
        <a href="https://github.com/sputnik524/CG_final_report">Github Repo </a>
        <br>
        In this project, I extend several advanced functionalities on Nori, a Physically-based Renderer developed during the course Computer graphics, including volumetric rendering in heterogenerous participating media, Disney BSDF, Image as Textures and Normal Mapping. I also manage to render a self-construct scene (right) and participate in the final round of the school-level Rendering Competition (2022 topic: Out of Place) .</td>
    </tr>
  </table>
  <hr>

<heading><strong>Instant-Sim</strong> </heading>
<table width="100%" align="center" border="0" cellspacing="0" cellpadding="20">  
    <td width="50%">
      <div class="one">
      <img src="/images/inst-sim.png" width="100%"> </div>
    </td>
    <td valign="top" width="75%">
          <papertitle>
          <strong>
            Data augmentation with Instant-NeRF 
          </strong>
          </papertitle>
    <br>
        <strong>Haitao Yu*</strong>,
        <a href="https://github.com/thisiszy">Zhiyuan Huang*</a>,
        Mingxuan Qin*
        (* means equal contribution)
      <br>
        <em>Course project of Deep Learning 2022 in ETH Zürich</em>
      <br>
      <a href="https://github.com/thisiszy/Instant-Sim/blob/master/report.pdf">Report</a> | 
      <a href="https://github.com/thisiszy/Instant-Sim">Github Repo</a>
      <br>
       Generally speaking, we integrate <a href="https://github.com/NVlabs/instant-ngp">Instant-NeRF</a> (followed this <a href="https://github.com/ashawkey/torch-ngp">pytorch implementaion</a>) in the original version of <a href="https://github.com/gyhandy/Neural-Sim-NeRF">Neural-Sim</a> to facilitate NeRF model training and evaluation step for downstream task. We ran the experiments on a self-generated dataset: hand gesture detection based on BlenderNeRF, to verify the successful integration.
    </td>
</table>
<hr>

<heading><strong>Point-Based Radiance Fields for Animatable Human Model</strong> </heading>
  <table width="100%" align="center" border="0" cellspacing="0" cellpadding="20">  
    <tr onmouseout="sava_stop()" onmouseover="sava_start()">  
            <td width="50%">
              <div class="one">
                <img src='/images/pointnerf.png' width="100%" />
                </div>

              <script type="text/javascript">
              function sava_start() { 
              document.getElementById('sava_shape').style.opacity = "1";
              }
              function sava_stop() { 
              document.getElementById('sava_shape').style.opacity = "0"; 
              }
              sava_stop()
              </script>
            </td>
      <td valign="top" width="75%">
            <papertitle>
            <strong>
            Point-Based Radiance Fields for Animatable Human Model
            </strong>
            </papertitle>
      <br>
          <strong>Haitao Yu*</strong>,
          <a href="https://github.com/dehezhang2">Deheng Zhang*</a>,
          <a href="https://github.com/TianyiZhang-arc"> Tianyi Zhang*</a>,
          Peiyuan Xie*
          (* means equal contribution)
        <br>
          <em>Course project of Digital Human 2023 in ETH Zürich</em>
        <br>
        <a href="https://drive.google.com/file/d/1hqf_ugm07J3xs9FFm125my0i948OArX_/view?usp=drive_link">Paper</a> | 
        Github Repo(Coming soon..)
        <br>
        In this project, we proposed a new method for learning animatable human avatar model with point-based primitives. In specific, our method exploits the explicit point cloud to train the static 3D scene based on Point-NeRF and apply the deformation by encoding the point cloud translation using a deformation MLP. We also guarantee the rendering consistency by perform rotation-only ray-bending. The final <a href= "https://www.youtube.com/watch?v=3iZ_89IwZUU">animating avatar </a> is comparable to other state-of-art animatable human models. </td>
    </tr>
  </table>
  <hr>
