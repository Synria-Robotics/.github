# Synria Robotics 玄雅科技 -  the Future of Humanity

[![English](https://img.shields.io/badge/EN-blue)](README_EN.md)
[![中文](https://img.shields.io/badge/中文-red)](README.md)

**深圳市玄雅科技有限公司**（Shenzhen Synria Robotics Co., Ltd.）成立于 2024 年，总部位于中国深圳，是一家专注于 **具身智能与远程交互机器人** 的创新型科技企业。核心业务涵盖 **遥操作机器人、一体化远程交互解决方案、先进控制系统** 及 **新一代多模态具身智能算法** 的深度融合。产品广泛适用于工业自动化、远程医疗、教育辅助等场景，具备跨域远程遥操能力、高响应性、精细化操作能力与多模态感知能力，能够满足复杂任务下的人机协同需求。

公司技术体系构建于以下五大核心支柱之上：

- **远程与无线遥操作**：支持低延迟、高精度的人机远程控制，适用于跨地域作业需求  
- **力反馈与触觉交互**：实现操作过程中的触觉同步与力感还原，提升任务执行的可控性与安全性  
- **人体工学驱动的设计理念**：结合人体工学设计示教装置，贴合人体动作习惯，提升操控舒适性与效率
- **共享与自适应控制机制**：支持人与机器人共享控制，控制权可动态调整，实现高效、安全、便捷的人机协作
- **多模态具身智能算法**：融合视觉、触觉、语义等多源感知信息，支撑真实环境下的智能行为生成  

---

更多信息详见:
[GitHub](https://github.com/Synria-Robotics) | [Gitee](https://gitee.com/Synria-Robotics) | [Taobao](https://m.tb.cn/h.h2cVdhu5JXDQvPu) | [Website](https://www.xuanyatech.com/) | [Sparkling 手册](https://docs.sparklingrobo.com/)

<table border="1" cellspacing="0" cellpadding="6" style="border-collapse: collapse; width: 100%; text-align: left;">
  <thead>
    <tr>
      <th style="width: 30%;">Product</th>
      <th style="width: 20%;">Repository</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="6"><strong>Alicia-D Series</strong><br/>6-DOF Servo Arm
        <img src="../imgs/Alicia-D.jpg" alt="Alicia-D Preview" style="margin-top: 6px;" /><br/>
        <img src="../imgs/Alicia_Duo_V5_4.png" alt="Alicia-D Preview" style="margin-top: 6px;" />
      </td>
      <td><a href="https://github.com/Synria-Robotics/Alicia-D-SDK">Alicia-D-SDK</a></td>
      <td>A Python SDK for controlling the Alicia-D 6-DOF robotic arm. Features include state reading, joint control, end-effector pose control, gripper control, forward/inverse kinematics, and more.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/Synria-Robotics/Alicia-D-ROS1">Alicia-D-ROS1</a></td>
      <td>ROS1 control package with drivers, MoveIt configuration, drag-teaching and grasping examples.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/Synria-Robotics/Alicia-D-ROS2">Alicia-D-ROS2</a></td>
      <td>ROS2 Humble compatible package with standard topic interfaces and a complete control pipeline.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/Synria-Robotics/Alicia-D-Leader-ROS">Alicia-D-Leader-ROS</a></td>
      <td>ROS driver for the leader arm (teaching arm), used to read joint states and publish custom messages.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/Synria-Robotics/Alicia-D-VLM-Grasp">Alicia-D-VLM-Grasp</a></td>
      <td>Vision-Language Model (VLM) based semantic grasping example, integrating Alibaba Cloud Bailian API.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/Synria-Robotics/lerobot">lerobot</a></td>
      <td>A robot learning and data collection framework, supporting imitation learning and teleoperation workflows.</td>
    </tr>
    <tr>
      <td rowspan="2"><strong>Bessica-D Series</strong><br/>Dual-arm Humanoid Robot
        <img src="../imgs/Bessica-D.png" alt="Bessica-D Preview" style="margin-top: 6px;" />
      </td>
      <td><a href="https://github.com/Synria-Robotics/Bessica-D-SDK">Bessica-D-SDK</a></td>
      <td>A Python SDK that supports dual-arm control, gripper operation, serial communication, and state feedback.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/Synria-Robotics/Bessica-D-ROS1">Bessica-D-ROS1</a></td>
      <td>ROS1 control package supporting synchronized dual-arm control, state reading, and MoveIt integration.</td>
    </tr>
  </tbody>
</table>