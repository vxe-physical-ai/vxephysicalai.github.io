# 👟 Dual-Arm Shoe Inspection Dataset & Hardware

[![Hugging Face Dataset](https://img.shields.io/badge/Hugging%20Face-Dataset-yellow?logo=huggingface)](https://huggingface.co/datasets/vxe-physical-ai/dataset)
[![GitHub CAD](https://img.shields.io/badge/GitHub-CAD%20Files-blue?logo=github)](https://github.com/vxe-physical-ai/end-effector-CAD-models)

<p align="center">
  <img src="assets/demo.gif" width="800px" alt="Demo Animation">
</p>

---

## Abstract
This project provides an open-source dataset and hardware design platform for automated shoe inspection tasks using a dual-arm robot.

---

## ⚠️ Terms of Use & Licensing

Both the VXE-PHYSICAL-AI Dataset and its Hardware (CAD designs) are released under custom non-commercial licenses for academic research only.

* ❌ **No Commercial Use**: Direct or indirect commercial use is strictly prohibited for both dataset and hardware.
* ❌ **No Redistribution**: You may not redistribute, host, or share the dataset or hardware design files.
* 🎓 **Academic Use Only**: Allowed for academic research, publications, and presentations with proper attribution (XXXX).

Please review the full license terms before downloading or using them:
* **Dataset License**: Read the full terms on [Hugging Face Repository (LICENSE)](https://huggingface.co/datasets/vxe-physical-ai/dataset/blob/main/LICENSE)
* **Hardware License**: Read the full terms on [GitHub CAD Repository (LICENSE)](https://github.com/vxe-physical-ai/end-effector-CAD-models/blob/main/LICENSE)

---

## Dataset
This dataset contains demonstration data for shoe inspection tasks collected using Trossen Robotics hardware and the LeRobot framework.
It includes fine-grained, timestamp-based subtask annotations to facilitate advanced imitation learning and policy training.
We release two versions of the dataset: a 67.2-hour dataset utilizing standard end-effectors, and a 42.25-hour dataset incorporating tactile and force/torque (F/T) sensing data.

---

## Hardware / CAD
3D models of the custom end-effectors for the dual-arm robot.
Each gripper is designed to integrate a GelSight Mini sensor and an MMS101 6-axis F/T sensor.
The repository includes data for mounting onto the WidowX AI Follower arms as well as for UMI (Universal Manipulation Interface) setups.

<div align="center">
  <table style="border: none; background: transparent;">
    <tr>
      <td align="center" style="border: none; padding: 10px;">
        <img src="assets/WIDOWX.png" height="380px" alt="Gripper CAD View 1"><br>
      </td>
      <td align="center" style="border: none; padding: 10px;">
        <img src="assets/UMI.png" height="380px" alt="Gripper CAD View 2"><br>
      </td>
    </tr>
  </table>
</div>

---

## Download
All related files can be accessed via the links below:
* 📊 **Dataset**: [Hugging Face](https://huggingface.co/datasets/vxe-physical-ai/dataset)
* ⚙️ **CAD**: [GitHub](https://github.com/vxe-physical-ai/end-effector-CAD-models)
