---
layout: post
title: Dashboard Kesehatan Ibu dan Anak
date: 2022-09-10 00:00:00 +0700
description: Dashboard developed for 'Project Lab BI I' course held by Pacmann.io. All copyright belongs to respective authors. # Add post description (optional)
img: Kesehatan_Dash.png # Add image post (optional)
tags: [data wrangling, data visualization, UI design, Tableau, Python] # add tag
---
>Dashboard Kesehatan Ibu dan Anak developed for 'Project Lab BI I' course held by Pacmann.io. All copyright belongs to respective authors.

Students are given the opportunity to demonstrate their programming skills during Project Lab BI I. For this project, we were given a list of various datasets which we could choose from. I formed a team of three with Andi Cahyono and Dewandra Bomantara. We decided to choose mother and child's health as our main issue.

We were tasked not only to develop a dashboard, but also to provide a solution to the issue that caught our eye. During the wrangling process, we saw how difficult it is to have a complete grasp of the data due to the incomplete data. There were long gap years and missing places. To answer the problem, we suggested to create a grass-root based data collection system to aid community-level health workers capture and report the data in real time.

Link for a <strong>Live Demo</strong> is provided the bottom of the page.

<hr>

<strong>Vision</strong>
* To create a grass-root based health dashboard to increase visibility on mother and child's haelth condition in West Java province.

<strong>Goals</strong>
* <strong>Dashboard Kesehatan Ibu dan Anak.</strong> Data visualization and analysis regarding mother and child's health report in West Java. Dashboard takes about 3 days to develop.
* <strong>Grass-Root Based Data Collection.</strong> Develop a simple data-gathering application for grassroot health workers. Gathered data will be used to renew Dashboard information.

<strong>User Persona</strong>
* <strong>Posyandu Workers</strong>. Access to Data Collection App to collect and upload data.
* <strong>Puskesmas Workers</strong>. Access to Data Collection App to collect and upload data.
* <strong>General Audience / Public</strong>. Access to dashboard only. 

<!-- separator -->
<img src="{{site.baseurl}}/assets/img/Separator.png" style="display: block; margin-left: auto; margin-right: auto;"/>
<!-- separator -->

### Dataset Refference
Data sourced from <a href="opendata.jabarprov.go.id">opendata.jabarprov.go.id</a    >
* Jumlah Anak Usia 0-23 Bulan dengan Panjang Pertumbuhan Terindikasi Stunting (Merah) Berdasarkan Desa/Kelurahan di Jawa Barat
* Jumlah Balita bergizi kurang berdasarkan kabupaten/kota di Jawa Barat
* Jumlah Bayi Bergizi Buruk Berdasarkan Kabupaten/Kota di Jawa Barat
* Jumlah Bayi yang Diimunisasi Campak Berdasarkan Kabupaten/Kota di Jawa Barat
* Jumlah Imunisasi BCG Pada Bayi Berdasarkan Jenis Kelamin di Jawa Barat
* Jumlah ibu hamil berdasarkan kabupaten/kota di Jawa Barat
* Jumlah Ibu Hamil yang Mengalami Kekurangan Energi Kronis (KEK) Berdasarkan Desa/Kelurahan di Jawa Barat
* Jumlah Ibu Hamil yang Mengalami Resiko Tinggi Kehamilan (RESTI) Berdasarkan Desa/Kelurahan di Jawa Barat
* Jumlah Kejadian Kematian Bayi (0-12 Bulan) Berdasarkan Desa/Kelurahan di Jawa Barat
* Jumlah Orang Tua/Pengasuh yang Mengikuti Parenting Bulanan (PAUD) Berdasarkan Desa/Kelurahan di Jawa Barat

<!-- separator -->
<img src="{{site.baseurl}}/assets/img/Separator.png" style="display: block; margin-left: auto; margin-right: auto;"/>
<!-- separator -->

### User-Flow
<img src="{{site.baseurl}}/assets/img/Kesehatan_UserFlow.png" width="450" height="auto" style="display: block; margin-left: auto; margin-right: auto;"/>
<p style="text-align:center"><strong> Dashboard User-Flow.</strong> Userflow applies to all pages across CVEWS Dashboard.</p>

<strong>Simple Usage</strong> -- Similar User-Flow for all departments.

<strong>Intuitive Filters</strong> -- Adjust step in choosing department page and filters. Data on dashboard adapts based on adjustments on the filter.

<strong>Open for Improvements</strong> -- Dashboard is always open for requests based on each department's need. Requests will be queued on B.I. Team's Pipeline.

<!-- separator -->
<img src="{{site.baseurl}}/assets/img/Separator.png" style="display: block; margin-left: auto; margin-right: auto;"/>
<!-- separator -->

### Dashboard Features
<img src="{{site.baseurl}}/assets/img/Kesehatan_Filter.png" width="200" height="auto" style="display: block; margin-left: auto; margin-right: auto;"/>
<p style="text-align:center"><strong>Control Panel</strong>. Main control to adjust information displayed on the dashboard.</p>

<img src="{{site.baseurl}}/assets/img/Kesehatan_Geo.png" width="200" height="auto" style="display: block; margin-left: auto; margin-right: auto;"/>
<p style="text-align:center"><strong>Geomap & Tooltip</strong>. Heatmap to aid visualization based on the selected data. Additional information shown as tooltip.</p>

<img src="{{site.baseurl}}/assets/img/Kesehatan_Bar.png" width="200" height="auto" style="display: block; margin-left: auto; margin-right: auto;"/>
<p style="text-align:center"><strong>Bar Chart & Dual-Axis Chart</strong>. Data visualization to represent selected information.</p>

<hr>

### Links:
* <a href="https://public.tableau.com/app/profile/andi.cahyono/viz/DashboardKesehatanIbudanAnak/MVP_Dashboard">Live Demo (INA)</a>
* <a href="https://drive.google.com/file/d/1wYKuQjAn6TaQ4lcQqBPs4lQx4YRrTs3p/view?usp=share_link">Product Requirement Document (INA)</a>
* <a href="https://drive.google.com/file/d/1imCOwTqPEscNlBzOm2P_gXArLv-1ciJK/view?usp=share_link">MVP Presentation (INA)</a>
* <a href="https://drive.google.com/file/d/16kAAU0jDa3P-cLlN_IyKoWto2sMsUoys/view?usp=share_link">Final Report (INA)</a>
* <a href="https://docs.google.com/forms/d/e/1FAIpQLSc-JeSiw0Inh0qm7kuc00b5Z0aAe7J4vMcjXYyLMyv37_zpzA/viewform">Grass-Root Data Collection App</a>