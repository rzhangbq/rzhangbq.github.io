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

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Submitted (LA-UR-25-30797)</div><img src='images/s-mhd2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Structure-Preserving Transfer of Grad-Shafranov Equilibria to Magnetohydrodynamic Solvers**

[**Presentation**](https://mfem.org/pdf/workshop25/15_Zhang_Magnetohydrodynamic_Solvers.pdf) |
[**Code**](https://github.com/mfem/mfem/tree/tds-load)
- Magnetohydrodynamic (MHD) solvers used to study dynamic plasmas for magnetic confinement fusion typically rely on initial conditions that describe force balancing, which are provided by an equilibrium solver based on the Grad--Shafranov (GS) equation. Transferring such equilibria from the GS discretization to the MHD discretization often introduces errors that lead to unwanted perturbations to the equilibria on the level of the MHD discretization. In this work, we identify and analyze sources of such errors in the context of finite element methods, with a focus on the force balancing and divergence-free properties of the loaded equilibria. In particular, we reveal three main sources of errors: (1) the improper choice of finite element spaces in the MHD scheme relative to the poloidal flux and toroidal field function spaces in the GS scheme, (2) the misalignment of the meshes from two solvers, and (3) possibly under-resolved strong gradients near the separatrix. With this in mind, we study the impact of different choices of finite element spaces, including those based on compatible finite elements. In addition, we also investigate the impact of mesh misalignment and propose to conduct mesh refinement to resolve the strong gradients near the separatrix. Numerical experiments are conducted to demonstrate equilibria errors arising in the transferred initial conditions. Results show that force balancing is best preserved when structure-preserving finite element spaces are used and when the MHD and GS meshes are both aligned and refined. Given that the poloidal flux is computed in continuous Galerkin spaces, we further demonstrate that projecting the magnetic field into div-conforming spaces is optimal for preserving force balancing, while projection into curl-conforming spaces, although less optimal for force balance, weakly preserves the divergence-free property. %This highlights the need to develop GS solvers capable of directly providing the poloidal flux in discontinuous Galerkin spaces.


</div>
</div>

