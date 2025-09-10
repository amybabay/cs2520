# Lab 1: TCP Congestion Control

## Objectives

In this lab, you will:

- Review the basic operation of TCP congestion control
- Run TCP flows with different congestion control algorithms and visualize the results
- Explore how different congestion control algorithms interact with each other

## Prerequisites

You must have your Fabric account and JupyterHub environment setup. Please see the [Fabric Setup](https://github.com/amybabay/cs2520/blob/main/Fabric_Setup.md) for instructions.

## Pre-Lab Preparation

- You should start by reviewing the background information on TCP Congestion Control: [here](https://github.com/amybabay/cs2520/blob/main/labs/Lab01_CongestionControl/1-congestion-control-bg.md)
- Then, you will reserve the Fabric resources needed to run the lab using the provided pre-lab Jupyter Notebook.

- To run the pre-lab:
   - Login to the FABRIC Portal and JupyterHub
    	- Login to the [FABRIC Portal](https://portal.fabric-testbed.net/) and click the "JupyterHub" link. Or, you can directly go to: [FABRIC JupyterHub](https://jupyter.fabric-testbed.net/)

   - Download the latest copy of the lab materials from GitHub
    	- Open a terminal in JupyterHub by clicking the "Terminal" tile under "Other" in the Launcher tab
    	- In the terminal window, type the following command to download (pull) the latest version of the set of tutorials from Github:
            ```
            git clone https://github.com/amybabay/cs2520.git
            ```

   - Run the pre-lab notebook
    	- In the left-hand column of JupyterHub, navigate to the `Lab01_CongestionControl` folder (cs2520 -> labs -> Lab01_CongestionControl)
    	- Open, read, and run all cells of the `2-pre-lab1.ipynb` notebook

## Acknowledgment

This lab is based on Fraida Fund's [TCP Congestion Control](https://witestlab.poly.edu/blog/tcp-congestion-control-basics/) lab.
