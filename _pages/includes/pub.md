# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/donet_2023.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**DoNet: Deep De-Overlapping Network for Cytology Instance Segmentation**

Hao Jiang\*, **Rushan Zhang**\*, Yanning Zhou, Yumeng Wang, Hao Chen

[**Google Scholar**](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=72yDElgAAAAJ&citation_for_view=72yDElgAAAAJ:u5HHmVD_uO8C&inst=7707536466893209563) |
[**Paper**](https://openaccess.thecvf.com/content/CVPR2023/papers/Jiang_DoNet_Deep_De-Overlapping_Network_for_Cytology_Instance_Segmentation_CVPR_2023_paper.pdf) |
[**Code**](https://github.com/DeepDoNet/DoNet) |
<strong><span class='show_paper_citations' data='72yDElgAAAAJ:u5HHmVD_uO8C'></span></strong>
- In this work, we proposed a De-overlapping Network (DoNet) in a decompose-and-recombined strategy. A Dual-path Region Segmentation Module (DRM) explicitly decomposes the cell clusters into intersection and complement regions, followed by a Semantic Consistency-guided Recombination Module (CRM) for integration. To further introduce the containment relationship of the nucleus in the cytoplasm, we design a Mask-guided Region Proposal Strategy (MRP) that integrates the cell attention maps for inner-cell instance prediction. We validate the proposed approach on ISBI2014 and CPS datasets. Experiments show that our proposed DoNet significantly outperforms other state-of-the-art (SOTA) cell instance segmentation methods.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Submitted (LA-UR-25-30797)</div><img src='images/gs-mhd2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Structure-Preserving Transfer of Grad-Shafranov Equilibria to Magnetohydrodynamic Solvers**

[**Presentation**](https://mfem.org/pdf/workshop25/15_Zhang_Magnetohydrodynamic_Solvers.pdf) |
[**Code**](https://github.com/mfem/mfem/tree/tds-load)
Magnetohydrodynamic (MHD) simulations of magnetically confined plasmas require initial conditions that satisfy force balance, typically obtained from equilibria computed by Grad–Shafranov (GS) solvers. However, transferring these equilibria to MHD discretizations can introduce numerical errors that disturb the equilibrium. This work identifies and analyzes key error sources within finite element frameworks, focusing on the preservation of force balance and the divergence-free property of the magnetic field. We show that errors primarily arise from (1) incompatible finite element spaces between GS and MHD solvers, (2) mesh misalignment, and (3) under-resolved gradients near the separatrix. Using numerical experiments, we demonstrate that equilibria are best preserved when structure-preserving finite element spaces are employed, meshes are aligned and refined, and magnetic fields are projected into div-conforming spaces to maintain force balance. Projection into curl-conforming spaces, while less optimal for force balance, provides weak preservation of the divergence-free condition.


</div>
</div>

