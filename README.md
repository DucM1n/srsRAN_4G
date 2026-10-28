# srsRAN_4G – Security Research & eNodeB Modifications Fork

> **Notice:** This repository is a modified fork of the official [srsRAN_4G](https://github.com/srsran/srsRAN_4G) suite by [SRS](http://www.srs.io). It is used for academic research, RAN security evaluation, and custom eNodeB testbed experiments as part of our **Graduation Thesis (Đồ án Tốt nghiệp)** on **4G/5G Network Security**.

---

## 📌 Research Scope & Custom Modifications

This repository is maintained by our thesis group to evaluate Radio Access Network (RAN) security, simulate signaling attack vectors, and test custom implementations within LTE/4G radio protocols.

### Key Objectives & Custom eNodeB Work

* **eNodeB (`srsENB`) Customizations:** Modified core RAN protocol layers (RRC, PDCP, RLC, MAC, or PHY) within `srsENB` to simulate edge behaviors, custom test cases, or specific RAN-side security scenarios.
* **RAN-to-Core Security Testing:** Interfacing modified `srsENB` with core network testbeds (such as Open5GS or srsEPC) to test security under rogue or non-standard eNodeB behaviors.
* **Air Interface & Protocol Vulnerability Analysis:** Investigating RRC connection handling, ciphering/integrity protection mechanisms, and NAS signaling relaying over radio links.
* **Experimental Case Verification:** Running specific test branches (`case-*`) to validate attack vectors and proposed defense/mitigation strategies.

---

## 👥 Credits & Acknowledgments

We express our gratitude to **Software Radio Systems (SRS)** and the open-source community for developing and maintaining the srsRAN suite.

* **Original Repository:** [srsran/srsRAN_4G](https://github.com/srsran/srsRAN_4G)
* **Official Website:** [srsran.com](https://www.srsran.com)
* **5G RAN Solution:** [srsRAN Project (O-RAN CU/DU)](https://github.com/srsran/srsran_project)

---

## 🚀 Original srsRAN_4G Suite Components

The original srsRAN suite includes:
* **`srsUE`** – A full-stack SDR 4G UE application with prototype 5G features.
* **`srsENB`** – A full-stack SDR 4G eNodeB application *(modified in this fork)*.
* **`srsEPC`** – A light-weight 4G core network implementation with MME, HSS, and S/P-GW.

---

## 📚 Documentation & Support (Original Project)

* **Documentation:** [srsRAN 4G Documentation](https://docs.srsran.com/projects/4g/)
* **Mailing List:** [srsran-users](https://lists.srsran.com/mailman/listinfo/srsran-users)
* **License:** See the `LICENSE` file in the repository for full license details.