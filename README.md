*This activity has been created as part of the 42 curriculum by maeverqu.*

# **NetPractice**

## **Description**

* **Goal:** **NetPractice** is a system administration project designed to teach the fundamentals of computer networking. The primary objective is to configure virtual network interfaces, routing tables, and IP addressing schemes to enable communication between various hosts, routers, and the Internet across **10 distinct levels**.
* **Overview:** Through an interactive web-based simulator, this activity covers standard IPv4 addressing, subnetting, default gateways, and inter-router communication under strict configuration constraints (such as read-only fields and fixed interfaces).

---

## **Instructions**

* **Running the Simulator:**
  * Execute the local web server script from your terminal:
    ```bash
    ./run.sh
    ```
  * Open your web browser and navigate to the local address provided by the script (e.g., `http://localhost:8080`).

* **Exporting Configurations:**
  * Complete each level from **Level 1** to **Level 10**.
  * Once a level is validated, click the **Export config** button to download the corresponding configuration file.
  * Ensure the exported files are named appropriately (`level1`, `level2`, ..., `level10`).

* **Submission Details:**
  * Place all **10 exported configuration files** directly at the **root** of your Git repository.
  * Your repository root must contain:
    * `README.md`
    * `level1`
    * `level2`
    * `level3`
    * `level4`
    * `level5`
    * `level6`
    * `level7`
    * `level8`
    * `level9`
    * `level10`

---

## **Resources**

* **Networking Concepts Studied:**
  * **TCP/IP Addressing:** IPv4 structure, public vs. private IP address ranges (RFC 1918).
  * **Subnet Masks & Subnetting:** CIDR notation (`/24`, `/25`, `/26`, `/30`), calculating network/broadcast addresses, and valid host ranges.
  * **Default Gateways:** Configuring gateway IPs for hosts to forward traffic outside local subnets.
  * **Routers & Switches:** Packet switching at Layer 2 (Switch) and packet routing at Layer 3 (Router).
  * **Routing Tables:** Static routing, next-hop resolution, and default routes (`0.0.0.0/0`).
  * **OSI Model:** Understanding physical, data-link, and network layer interactions.

* **Documentation & References:**
  * *Subnetting Guide:* [RFC 1878 - Variable Length Subnet Table For IPv4](https://datatracker.ietf.org/doc/html/rfc1878)
  * *Networking Basics:* Cisco CCNA Networking Essentials Documentation

* **Use of Artificial Intelligence (AI):**
  * **Tasks & Scope:** AI was utilized as a peer-learning assistant to analyze network trace logs (`Reverse way`, `loop detected`, `private subnets not routed over internet`), debug subnet mask overlapping issues on inter-router links, and structure project documentation.
  * **Implementation:** All network configurations were manually calculated, implemented, and verified in the NetPractice simulator.