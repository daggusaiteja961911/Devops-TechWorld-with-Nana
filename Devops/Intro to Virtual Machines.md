### **Virtualization & VM – Interview Notes**

---

## **1. What is Virtualization & Virtual Machine?**

* **Virtualization:** Running multiple OS on one physical machine.
* **VM:** Software-based computer with its own OS.

---

## **2. Why Virtualization is Useful**

* Better hardware utilization.
* Isolation between applications.

---

## **3. How Virtualization Works (Core Concepts)**

* **Hypervisor** sits between hardware and OS.
* Allocates CPU, memory, storage to VMs.

---

## **4. Benefits of Virtual Machines**

* Cost saving.
* Easy backup and recovery.
* Scalability.

---

## **5. Type 1 vs Type 2 Hypervisor**

* **Type 1:** Runs on hardware (AWS, Azure).
* **Type 2:** Runs on OS (VirtualBox).

---

## **6. Why Companies Adopt Virtualization**

* Faster provisioning.
* Better resource usage.
* Cloud readiness.

---

## **Extra Concepts (Important)**

* **Host OS vs Guest OS**
* **Snapshot**
* **VM vs Physical Server**
* **Virtualization vs Containerization**

---

### **Interview Questions & Answers**

* **What is virtualization?**
  Running multiple OS on one machine.

* **What is a hypervisor?**
  Software that manages VMs.

* **Type 1 vs Type 2?**
  Bare-metal vs hosted.

* **VM vs container?**
  VM has full OS, container shares OS.

* **Why VMs in cloud?**
  Isolation, scaling, efficiency.

---

### **Ultra-Short Summary**

* **Virtualization** → Hardware abstraction
* **VM** → Isolated OS
* **Cloud = Type 1 Hypervisor**
---------------------------------------------------------------------------------
### **Added High-Value VM Notes (Interview Focused)**

* **Hardware Virtualization**

  * CPU support (Intel VT-x / AMD-V).

* **Resource Overcommitment**

  * Allocate more virtual resources than physical.

* **VM Lifecycle**

  * Create → Start → Pause → Snapshot → Stop → Delete.

* **Isolation**

  * VM crash does not affect other VMs.

* **Performance Overhead**

  * VMs are heavier than containers.

* **Use Cases**

  * Testing, staging, legacy apps, cloud servers.

* **VM Images**

  * Pre-configured OS templates.

---

### **Extra Interview Questions**

* **What is a snapshot?**
  Point-in-time VM state backup.

* **Why VM slower than container?**
  Full OS per VM.

* **What is bare-metal hypervisor?**
  Type 1 hypervisor.

* **Can VMs run different OS?**
  Yes.

---

### **Final One-Line Summary**

* **VMs = isolated, secure, cloud-ready systems built using hypervisors**
