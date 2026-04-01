# ACMMM20264623
# SAT: Supervisor Regularization and Animation Augmentation for Two-process Monocular Texture 3D Human Reconstruction

---

# Abstract

Monocular texture 3D human reconstruction aims to create a complete 3D digital avatar from just a single front-view human RGB image. However, the geometric ambiguity inherent in a single 2D image and the scarcity of 3D human training data are the main obstacles limiting progress in this field. To address these issues, current methods employ prior geometric estimation networks to derive various human geometric forms, such as the SMPL model and normal maps. However, they struggle to integrate these modalities effectively, leading to view inconsistencies, such as facial distortions. To this end, we propose a two-process 3D human reconstruction framework, SAT, which seamlessly learns various prior geometries in a unified manner and reconstructs high-quality textured 3D avatars as the final output. To further facilitate geometry learning, we introduce a Supervisor Feature Regularization module. By employing a multi-view network with the same structure to provide intermediate features as training supervision, these varied geometric priors can be better fused. To tackle data scarcity and further improve reconstruction quality, we also propose an Online Animation Augmentation module. By building a one-feed-forward animation network, we augment a massive number of samples from the original 3D human data online for model training. Extensive quantitative and qualitative experiments on two benchmarks show the superiority of our approach compared to state-of-the-art methods.

---

# Comparison with SOTA Methods

<center>
<table align="center" style="border-collapse: collapse; width: 100%;">
  <thead>
    <tr align="center">
      <th>Input Image</th>
      <th>Ours</th>
      <th>PSHuman</th>
      <th>GTA</th>
      <th>ICON</th>
    </tr>
  </thead>
  <tbody>
    <tr align="center">
      <td>
        <img src="data/ood_28/1095.jpg" alt="Input Image" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_2_gif/ours.gif" alt="Ours" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_2_gif/pshuman.gif" alt="PSHuman" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_2_gif/GTA.gif" alt="GTA" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_2_gif/ECON.gif" alt="ICON" width="250px" style="max-width: 100%;">
      </td>
    </tr>
    <tr align="center">
      <th>SiFU</th>
      <th>SiTH</th>
      <th>Human3diff</th>
      <th>PiFu</th>
      <th>ECON</th>
    </tr>
    <tr align="center">
      <td>
        <img src="data/texture/other_2_gif/SiFU.gif" alt="SiFU" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_2_gif/SiTH.gif" alt="SiTH" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_2_gif/Human3diff.gif" alt="Human3diff" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_2_gif/PiFU.gif" alt="PiFu" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_2_gif/ECON.gif" alt="ECON" width="250px" style="max-width: 100%;">
      </td>
    </tr>
  </tbody>
</table>
</center>


---

<center>
<table align="center" style="border-collapse: collapse; width: 100%;">
  <thead>
    <tr align="center">
      <th>Input Image</th>
      <th>Ours</th>
      <th>PSHuman</th>
      <th>GTA</th>
      <th>ICON</th>
    </tr>
  </thead>
  <tbody>
    <tr align="center">
      <td>
        <img src="data/ood_28/1703.jpg" alt="Input Image" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_10_gif/ours.gif" alt="Ours" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_10_gif/pshuman.gif" alt="PSHuman" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_10_gif/GTA.gif" alt="GTA" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_10_gif/ECON.gif" alt="ICON" width="250px" style="max-width: 100%;">
      </td>
    </tr>
    <tr align="center">
      <th>SiFU</th>
      <th>SiTH</th>
      <th>Human3diff</th>
      <th>PiFu</th>
      <th>ECON</th>
    </tr>
    <tr align="center">
      <td>
        <img src="data/texture/other_10_gif/SiFU.gif" alt="SiFU" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_10_gif/SiTH.gif" alt="SiTH" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_10_gif/Human3diff.gif" alt="Human3diff" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_10_gif/PiFU.gif" alt="PiFu" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_10_gif/ECON.gif" alt="ECON" width="250px" style="max-width: 100%;">
      </td>
    </tr>
  </tbody>
</table>


---

<center>
<table align="center" style="border-collapse: collapse; width: 100%;">
  <thead>
    <tr align="center">
      <th>Input Image</th>
      <th>Ours</th>
      <th>PSHuman</th>
      <th>GTA</th>
      <th>ICON</th>
    </tr>
  </thead>
  <tbody>
    <tr align="center">
      <td>
        <img src="data/ood_28/1793.jpg" alt="Input Image" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_12_gif/ours.gif" alt="Ours" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_12_gif/pshuman.gif" alt="PSHuman" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_12_gif/GTA.gif" alt="GTA" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_12_gif/ECON.gif" alt="ICON" width="250px" style="max-width: 100%;">
      </td>
    </tr>
    <tr align="center">
      <th>SiFU</th>
      <th>SiTH</th>
      <th>Human3diff</th>
      <th>PiFu</th>
      <th>ECON</th>
    </tr>
    <tr align="center">
      <td>
        <img src="data/texture/other_12_gif/SiFU.gif" alt="SiFU" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_12_gif/SiTH.gif" alt="SiTH" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_12_gif/Human3diff.gif" alt="Human3diff" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_12_gif/PiFU.gif" alt="PiFu" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_12_gif/ECON.gif" alt="ECON" width="250px" style="max-width: 100%;">
      </td>
    </tr>
  </tbody>
</table>



---

<center>
<table align="center" style="border-collapse: collapse; width: 100%;">
  <thead>
    <tr align="center">
      <th>Input Image</th>
      <th>Ours</th>
      <th>PSHuman</th>
      <th>GTA</th>
      <th>ICON</th>
    </tr>
  </thead>
  <tbody>
    <tr align="center">
      <td>
        <img src="data/ood_28/541.jpg" alt="Input Image" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_13_gif/ours.gif" alt="Ours" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_13_gif/pshuman.gif" alt="PSHuman" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_13_gif/GTA.gif" alt="GTA" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_13_gif/ECON.gif" alt="ICON" width="250px" style="max-width: 100%;">
      </td>
    </tr>
    <tr align="center">
      <th>SiFU</th>
      <th>SiTH</th>
      <th>Human3diff</th>
      <th>PiFu</th>
      <th>ECON</th>
    </tr>
    <tr align="center">
      <td>
        <img src="data/texture/other_13_gif/SiFU.gif" alt="SiFU" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_13_gif/SiTH.gif" alt="SiTH" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_13_gif/Human3diff.gif" alt="Human3diff" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_13_gif/PiFU.gif" alt="PiFu" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_13_gif/ECON.gif" alt="ECON" width="250px" style="max-width: 100%;">
      </td>
    </tr>
  </tbody>
</table>



---

<center>
<table align="center" style="border-collapse: collapse; width: 100%;">
  <thead>
    <tr align="center">
      <th>Input Image</th>
      <th>Ours</th>
      <th>PSHuman</th>
      <th>GTA</th>
      <th>ICON</th>
    </tr>
  </thead>
  <tbody>
    <tr align="center">
      <td>
        <img src="data/ood_28/1616.jpg" alt="Input Image" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_9_gif/ours.gif" alt="Ours" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_9_gif/pshuman.gif" alt="PSHuman" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_9_gif/GTA.gif" alt="GTA" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_9_gif/ECON.gif" alt="ICON" width="250px" style="max-width: 100%;">
      </td>
    </tr>
    <tr align="center">
      <th>SiFU</th>
      <th>SiTH</th>
      <th>Human3diff</th>
      <th>PiFu</th>
      <th>ECON</th>
    </tr>
    <tr align="center">
      <td>
        <img src="data/texture/other_9_gif/SiFU.gif" alt="SiFU" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_9_gif/SiTH.gif" alt="SiTH" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_9_gif/Human3diff.gif" alt="Human3diff" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_9_gif/PiFU.gif" alt="PiFu" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_9_gif/ECON.gif" alt="ECON" width="250px" style="max-width: 100%;">
      </td>
    </tr>
  </tbody>
</table>
</center>

---

<center>
<table align="center" style="border-collapse: collapse; width: 100%;">
  <thead>
    <tr align="center">
      <th>Input Image</th>
      <th>Ours</th>
      <th>PSHuman</th>
      <th>GTA</th>
      <th>ICON</th>
    </tr>
  </thead>
  <tbody>
    <tr align="center">
      <td>
        <img src="data/ood_28/cropped_istockphoto-1169130132-612x612.png" alt="Input Image" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_18_gif/ours.gif" alt="Ours" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_18_gif/pshuman.gif" alt="PSHuman" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_18_gif/GTA.gif" alt="GTA" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_18_gif/ECON.gif" alt="ICON" width="250px" style="max-width: 100%;">
      </td>
    </tr>
    <tr align="center">
      <th>SiFU</th>
      <th>SiTH</th>
      <th>Human3diff</th>
      <th>PiFu</th>
      <th>ECON</th>
    </tr>
    <tr align="center">
      <td>
        <img src="data/texture/other_18_gif/SiFU.gif" alt="SiFU" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_18_gif/SiTH.gif" alt="SiTH" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_18_gif/Human3diff.gif" alt="Human3diff" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_18_gif/PiFU.gif" alt="PiFu" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_18_gif/ECON.gif" alt="ECON" width="250px" style="max-width: 100%;">
      </td>
    </tr>
  </tbody>
</table>


---

<center>
<table align="center" style="border-collapse: collapse; width: 100%;">
  <thead>
    <tr align="center">
      <th>Input Image</th>
      <th>Ours</th>
      <th>PSHuman</th>
      <th>GTA</th>
      <th>ICON</th>
    </tr>
  </thead>
  <tbody>
    <tr align="center">
      <td>
        <img src="data/ood_28/cropped_istockphoto-1253466968-612x612.png" alt="Input Image" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_20_gif/ours.gif" alt="Ours" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_20_gif/pshuman.gif" alt="PSHuman" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_20_gif/GTA.gif" alt="GTA" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_20_gif/ECON.gif" alt="ICON" width="250px" style="max-width: 100%;">
      </td>
    </tr>
    <tr align="center">
      <th>SiFU</th>
      <th>SiTH</th>
      <th>Human3diff</th>
      <th>PiFu</th>
      <th>ECON</th>
    </tr>
    <tr align="center">
      <td>
        <img src="data/texture/other_20_gif/SiFU.gif" alt="SiFU" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_20_gif/SiTH.gif" alt="SiTH" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_20_gif/Human3diff.gif" alt="Human3diff" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_20_gif/PiFU.gif" alt="PiFu" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/texture/other_20_gif/ECON.gif" alt="ECON" width="250px" style="max-width: 100%;">
      </td>
    </tr>
  </tbody>
</table>



---

<center>
<table align="center" style="border-collapse: collapse; width: 100%;">
  <thead>
    <tr align="center">
      <th>Input Image</th>
      <th>Ours</th>
      <th>PSHuman</th>
      <th>SiTH</th>
      <th>GTA</th>
      <th>ICON</th>
    </tr>
  </thead>
  <tbody>
    <tr align="center">
      <td>
        <img src="data/geo_inp_crop/ood_input_images_0_9.jpg" alt="Input Image" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/geometry/thuman_10_gif/ours.gif" alt="Ours" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/geometry/thuman_10_gif/pshuman.gif" alt="PSHuman" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/geometry/thuman_10_gif/SiTH.gif" alt="SiTH" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/geometry/thuman_10_gif/GTA.gif" alt="GTA" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/geometry/thuman_10_gif/ECON.gif" alt="ICON" width="250px" style="max-width: 100%;">
      </td>
    </tr>
    <tr align="center">
      <th>SiFU</th>
      <th>VS</th>
      <th>HiLo</th>
      <th>Human3diff</th>
      <th>PiFu</th>
      <th>ECON</th>
    </tr>
    <tr align="center">
      <td>
        <img src="data/geometry/thuman_10_gif/SiFU.gif" alt="SiFU" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/geometry/thuman_10_gif/VS.gif" alt="PSHuman" width="250px" style="max-width: 100%;">
      </td>
        <td>
        <img src="data/geometry/thuman_10_gif/HILO.gif" alt="SiTH" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/geometry/thuman_10_gif/Human3diff.gif" alt="Human3diff" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/geometry/thuman_10_gif/PiFU.gif" alt="PiFu" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/geometry/thuman_10_gif/ECON.gif" alt="ECON" width="250px" style="max-width: 100%;">
      </td>
    </tr>
  </tbody>
</table>


---

<center>
<table align="center" style="border-collapse: collapse; width: 100%;">
  <thead>
    <tr align="center">
      <th>Input Image</th>
      <th>Ours</th>
      <th>PSHuman</th>
      <th>SiTH</th>
      <th>GTA</th>
      <th>ICON</th>
    </tr>
  </thead>
  <tbody>
    <tr align="center">
      <td>
        <img src="data/geo_inp_crop/ood_input_images_0_19.jpg" alt="Input Image" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/geometry/thuman_20_gif/ours.gif" alt="Ours" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/geometry/thuman_20_gif/pshuman.gif" alt="PSHuman" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/geometry/thuman_20_gif/SiTH.gif" alt="SiTH" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/geometry/thuman_20_gif/GTA.gif" alt="GTA" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/geometry/thuman_20_gif/ECON.gif" alt="ICON" width="250px" style="max-width: 100%;">
      </td>
    </tr>
    <tr align="center">
      <th>SiFU</th>
      <th>VS</th>
      <th>HiLo</th>
      <th>Human3diff</th>
      <th>PiFu</th>
      <th>ECON</th>
    </tr>
    <tr align="center">
      <td>
        <img src="data/geometry/thuman_20_gif/SiFU.gif" alt="SiFU" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/geometry/thuman_20_gif/VS.gif" alt="PSHuman" width="250px" style="max-width: 100%;">
      </td>
        <td>
        <img src="data/geometry/thuman_20_gif/HILO.gif" alt="SiTH" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/geometry/thuman_20_gif/Human3diff.gif" alt="Human3diff" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/geometry/thuman_20_gif/PiFU.gif" alt="PiFu" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/geometry/thuman_20_gif/ECON.gif" alt="ECON" width="250px" style="max-width: 100%;">
      </td>
    </tr>
  </tbody>
</table>


---

<center>
<table align="center" style="border-collapse: collapse; width: 100%;">
  <thead>
    <tr align="center">
      <th>Input Image</th>
      <th>Ours</th>
      <th>PSHuman</th>
      <th>SiTH</th>
      <th>GTA</th>
      <th>ICON</th>
    </tr>
  </thead>
  <tbody>
    <tr align="center">
      <td>
        <img src="data/geo_inp_crop/ood_input_images_0_49.jpg" alt="Input Image" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/geometry/custom_50_gif/ours.gif" alt="Ours" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/geometry/custom_50_gif/pshuman.gif" alt="PSHuman" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/geometry/custom_50_gif/SiTH.gif" alt="SiTH" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/geometry/custom_50_gif/GTA.gif" alt="GTA" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/geometry/custom_50_gif/ECON.gif" alt="ICON" width="250px" style="max-width: 100%;">
      </td>
    </tr>
    <tr align="center">
      <th>SiFU</th>
      <th>VS</th>
      <th>HiLo</th>
      <th>Human3diff</th>
      <th>PiFu</th>
      <th>ECON</th>
    </tr>
    <tr align="center">
      <td>
        <img src="data/geometry/custom_50_gif/SiFU.gif" alt="SiFU" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/geometry/custom_50_gif/VS.gif" alt="PSHuman" width="250px" style="max-width: 100%;">
      </td>
        <td>
        <img src="data/geometry/custom_50_gif/HILO.gif" alt="SiTH" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/geometry/custom_50_gif/Human3diff.gif" alt="Human3diff" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/geometry/custom_50_gif/PiFU.gif" alt="PiFu" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/geometry/custom_50_gif/ECON.gif" alt="ECON" width="250px" style="max-width: 100%;">
      </td>
    </tr>
  </tbody>
</table>

---

<center>
<table align="center" style="border-collapse: collapse; width: 100%;">
  <thead>
    <tr align="center">
      <th>Input Image</th>
      <th>Ours</th>
      <th>PSHuman</th>
      <th>SiTH</th>
      <th>GTA</th>
      <th>ICON</th>
    </tr>
  </thead>
  <tbody>
    <tr align="center">
      <td>
        <img src="data/geo_inp_crop/ood_input_images_0_15.jpg" alt="Input Image" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/geometry/custom_16_gif/ours.gif" alt="Ours" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/geometry/custom_16_gif/pshuman.gif" alt="PSHuman" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/geometry/custom_16_gif/SiTH.gif" alt="SiTH" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/geometry/custom_16_gif/GTA.gif" alt="GTA" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/geometry/custom_16_gif/ECON.gif" alt="ICON" width="250px" style="max-width: 100%;">
      </td>
    </tr>
    <tr align="center">
      <th>SiFU</th>
      <th>VS</th>
      <th>HiLo</th>
      <th>Human3diff</th>
      <th>PiFu</th>
      <th>ECON</th>
    </tr>
    <tr align="center">
      <td>
        <img src="data/geometry/custom_16_gif/SiFU.gif" alt="SiFU" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/geometry/custom_16_gif/VS.gif" alt="PSHuman" width="250px" style="max-width: 100%;">
      </td>
        <td>
        <img src="data/geometry/custom_16_gif/HILO.gif" alt="SiTH" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/geometry/custom_16_gif/Human3diff.gif" alt="Human3diff" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/geometry/custom_16_gif/PiFU.gif" alt="PiFu" width="250px" style="max-width: 100%;">
      </td>
      <td>
        <img src="data/geometry/custom_16_gif/ECON.gif" alt="ECON" width="250px" style="max-width: 100%;">
      </td>
    </tr>
  </tbody>
</table>


---

# More Examples





<center>
<table align="center">
  <tr align="center">
    <td align="center">
      <img src="data/texture/other_22_gif/ours.gif" alt="Input Image" width="250px">
    </td>
    <td align="center">
      <img src="data/texture/other_3_gif/ours.gif" alt="Ours" width="250px">
    </td>
    <td align="center">
      <img src="data/texture/other_21_gif/ours.gif" alt="SiTH" width="250px">
    </td>
  </tr>
</table>
</center>

---


<center>
<table align="center">
  <tr align="center">
    <td align="center">
      <img src="data/texture/other_8_gif/ours.gif" alt="Input Image" width="250px">
    </td>
    <td align="center">
      <img src="data/texture/other_19_gif/ours.gif" alt="Ours" width="250px">
    </td>
    <td align="center">
      <img src="data/texture/other_11_gif/ours.gif" alt="SiTH" width="250px">
    </td>
  </tr>
</table>
</center>

---


<center>
<table align="center">
  <tr align="center">
    <td align="center">
      <img src="data/texture/other_17_gif/ours.gif" alt="Input Image" width="250px">
    </td>
    <td align="center">
      <img src="data/texture/other_14_gif/ours.gif" alt="Ours" width="250px">
    </td>
    <td align="center">
      <img src="data/texture/other_16_gif/ours.gif" alt="SiTH" width="250px">
    </td>
  </tr>
</table>
</center>


---


<center>
<table align="center">
  <tr align="center">
    <td align="center">
      <img src="data/texture/other_6_gif/ours.gif" alt="Input Image" width="250px">
    </td>
    <td align="center">
      <img src="data/texture/other_5_gif/ours.gif" alt="Ours" width="250px">
    </td>
    <td align="center">
      <img src="data/texture/other_1_gif/ours.gif" alt="SiTH" width="250px">
    </td>
  </tr>
</table>
</center>

---


# Animation
<center>
<table align="center">
  <tr align="center">
    <td align="center">
      <img src="data/video_gif/0451_00073_03_00121_8views.gif" alt="Input Image" width="250px">
    </td>
    <td align="center">
      <img src="data/video_gif/0558_00080_01_00161_8views.gif" alt="Ours" width="250px">
    </td>
    <td align="center">
      <img src="data/video_gif/0210_00048_06_00041_8views.gif" alt="SiTH" width="250px">
    </td>
    <td align="center">
      <img src="data/video_gif/0129_00032_06_00041_8views.gif" alt="Ours" width="250px">
    </td>
    <td align="center">
      <img src="data/video_gif/0113_00029_05_00041_8views.gif" alt="SiTH" width="250px">
    </td>
  </tr>
</table>
</center>

---


# Method Overview
<center>
<img src="data/overview.jpg" width="900px">
</center>
We introduce a novel framework, SAT, for the task of monocular texture 3D human reconstruction, which comprises two key processes: United Geometry Learning (UGL) and Cascading Gaussian Texturing (CGT). Central to these processes are two innovative modules: Supervised Feature Regularization (SFR) and Online Animation Augmentation (OAA). In the UGL process, we extract different-modality geometric features from the input image using various prior models and integrate them into a united geometric learning network for reconstructing 3D human normal Gaussians. To enhance this process, the SFR module is employed. It involves training a multi-view supervisor model that generates multi-level supervisor feature maps, which serve as a regularizing force for monocular geometry learning. The CGT process aims to align with the output distribution of the UGL process while preventing cascading errors. It utilizes the 3D geometry human Gaussian derived from UGL, alongside the input image, to reconstruct the 3D texture Gaussian. To further boost reconstruction quality and address the limited availability of human 3D data, we introduce the OAA module. This module trains an animation model that dynamically generates more pose-varied 3D human samples, augmenting the existing dataset for enhanced model training.
