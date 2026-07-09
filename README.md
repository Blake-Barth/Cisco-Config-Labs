# Cisco-Config-Labs (EVE-NG)

A collection of high-level Cisco networking labs. This repository showcases functional configurations and topologies for **ENCOR** and **ENARSI**, all built and validated in **EVE-NG**.

---

## 📂 Lab Collection

Each folder below contains a standalone project with all necessary assets for replication. 

> **Note:** A link to the virtual images is **not included** in this repository as they are proprietary and require valid licensing from the vendor.

---

## 🛠 What's in Each Lab?

Every lab folder provides a comprehensive package for technical analysis and replication:

1.  **Topology Diagram:** A clear map of the network architecture (`topology.png`).
2.  **Configuration:** A `configs.zip` file containing the initial setup applied to every node.
---

## 🚀 How to Use

1.  **Build:** Match your EVE-NG topology to the provided diagram.
2.  **Initial Setup:** * Access the EVE-NG console for each node.
    * Apply the `configs.zip` by importing it into the startup-configuration section in eve-ng.
3.  **Implementation:** * Open the node-specific configuration file (e.g., `R1.txt`).
    * **Audit the interface IDs:** Verify that the interfaces in the text file (e.g., `ge-0/0/0`) match your physical cabling in EVE-NG. 
    * Use the **Node-Specifc Configuration File** as a guide to apply the specific routing and switching logic to your nodes.
4.  **Verification:** Check the included README to see the expected convergence results, then run the corresponding `show` commands on your own nodes to verify the state. Check that full network connectivity exists using **Ping** and **Traceroute** to validate end-to-end reachability.
   
---

## 📝 Requirements

* **Platform:** EVE-NG (Community or Professional).
* **Images:** * **Routing:** vIOS (router).
    * **Switching:** vIOSL2 (switch).
