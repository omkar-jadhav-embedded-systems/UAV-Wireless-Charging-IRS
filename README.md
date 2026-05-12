# Dynamic Charging of Unmanned Aerial Vehicles (UAVs) using Intelligent Reflecting Surfaces (IRS)

### M.Tech Thesis Project | Indian Institute of Technology (IIT), Guwahati

This repository contains the thesis, research poster, and simulation findings for my Master's project. The research investigates the feasibility of wirelessly charging UAVs using IRS to overcome range limitations and improve operational endurance.

---

## 🚀 Project Goal

The primary challenge with UAVs (drones) is their limited flight time due to battery constraints. This project models and analyzes a system where an **Intelligent Reflecting Surface (IRS)** is used to create a reliable, secondary line-of-sight path for wireless power transfer, especially in urban environments where direct line-of-sight is often blocked.

**The objective:** To determine the optimal system conditions (number of IRS elements, UAV elevation angle) that minimize power transfer outage probability.

---

## 🛠️ System Model & Key Concepts

The system consists of a Ground Base Station (BS), a UAV, and a planar IRS. The IRS intelligently reflects and focuses radio frequency (RF) signals from the BS toward the UAV, enabling it to harvest energy even in Non-Line-of-Sight (NLoS) conditions.

![System Model](<PATH_TO_YOUR_IMAGE>/system_model.png)
> *To get the image path: upload the image from your poster to your repo, click on it, right-click the image and select "Copy Image Address".*

---

## 📈 Key Findings & Results

The analysis and simulations demonstrated a clear relationship between system parameters and performance.

1.  **More IRS Elements = Better Performance:** Increasing the number of reflecting elements on the IRS significantly decreases the outage probability, allowing for more reliable power transfer.

    ![IRS Elements vs Outage](<PATH_TO_YOUR_IMAGE>/irs_vs_outage.png)

2.  **Higher Elevation Angle = Better Performance:** As the UAV's elevation angle increases, it moves into a more favorable Line-of-Sight (LoS) position, drastically improving energy transfer efficiency up to a certain point.

    ![Elevation vs Outage](<PATH_TO_YOUR_IMAGE>/elevation_vs_outage.png)

---

## 📂 Repository Contents

*   `OMKAR_JADHAV_MTP_II_204102021 (1) (1).pdf`: The complete M.Tech thesis document.
*   `FINAL_POSTER_MTP_PHASE_1 (1).pdf`: A visual summary and poster of the project.

---

## ©️ Copyright & Licensing

**Thesis & Poster:** © 2022 Omkar Amol Jadhav. All Rights Reserved. The documents herein are for portfolio and reading purposes only. No part of these documents may be reproduced or distributed without prior written permission.


