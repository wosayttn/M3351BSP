# Software Composition Analysis (SCA) Report: NuMicro-M3351BSP

This Software Composition Analysis (SCA) report details the third-party components, licensing, and security posture of the **NuMicro-M3351BSP** (v3.0.2) firmware distribution.

## 📊 Summary Dashboard

| Attribute | Value |
| :--- | :--- |
| **Project Name** | NuMicro-M3351BSP |
| **Firmware Version** | v3.0.2 |
| **Release Date** | 2026-06-01 |
| **Supplier / Vendor** | Nuvoton Technology |
| **Total Tracked Components** | 39 |
| **Vulnerability Status** | 🔴 Action Required |

---

## 🛡️ Security Vulnerability Summary

Vulnerabilities detected by the SCA scanning engine (Grype) on the complete firmware SBOM:

*   🔴 **Critical**: `5`
*   🟠 **High**: `9`
*   🟡 **Medium**: `9`
*   🟢 **Low**: `0`
*   🔵 **Negligible**: `0`
*   ⚪ **Unknown**: `0`

---

## 📦 Component Composition List

The following third-party components and local software libraries are tracked in the firmware package:

| Name | Version | Type | License | Vulnerabilities | Package URL (purl) |
| :--- | :--- | :--- | :--- | :---: | :--- |
| **ARM-software/cmsis-actions/armlm** | `v1` | library | Unknown | `0` | `pkg:github/ARM-software/cmsis-actions@v1#armlm` |
| **ARM-software/cmsis-actions/vcpkg** | `v1` | library | Unknown | `0` | `pkg:github/ARM-software/cmsis-actions@v1#vcpkg` |
| **HID Transfer Test Tool** | `1.1.0.0` | application | Unknown | `0` | `None` |
| **NuvPos58 Driver** | `1.0` | application | Unknown | `0` | `None` |
| **NuvPos58 Driver** | `1.0` | application | Unknown | `0` | `None` |
| **WDF Coinstaller** | `1.11.9200.16384` | application | Unknown | `0` | `None` |
| **WDF Coinstaller** | `1.11.9200.16384` | application | Unknown | `0` | `None` |
| **Windows Driver Foundation - User-mode Platform Device Update Co-Installer** | `6.1.7600.16385` | application | Unknown | `0` | `None` |
| **actions/checkout** | `v4` | library | Unknown | `0` | `pkg:github/actions/checkout@v4` |
| **actions/checkout** | `v4` | library | Unknown | `0` | `pkg:github/actions/checkout@v4` |
| **actions/upload-artifact** | `v4` | library | Unknown | `0` | `pkg:github/actions/upload-artifact@v4` |
| **libusb-win32 - DLL** | `1.2.6.0` | application | Unknown | `0` | `None` |
| **libusb-win32 - DLL** | `1.2.6.0` | application | Unknown | `0` | `None` |
| **libusb-win32 - Install-Filter** | `1.2.6.0` | application | Unknown | `0` | `None` |
| **libusb-win32 - Install-Filter** | `1.2.6.0` | application | Unknown | `0` | `None` |
| **libusb-win32 - Install-Filter** | `1.2.6.0` | application | Unknown | `0` | `None` |
| **libusbK.dll** | `3.0.7.0` | application | Unknown | `0` | `None` |
| **libusbK.dll** | `3.0.7.0` | application | Unknown | `0` | `None` |
| **libusbK.dll** | `3.0.7.0` | application | Unknown | `0` | `None` |
| **/mnt/tank/M3351BSP/.github/workflows/SBOM_CVE.yml** | `None` | file | Unknown | `0` | `None` |
| **/mnt/tank/M3351BSP/.github/workflows/VSCode.yml** | `None` | file | Unknown | `0` | `None` |
| **/mnt/tank/M3351BSP/SampleCode/ISP/ISP_DFU/WindowsDriver/amd64/WdfCoInstaller01011.dll** | `None` | file | Unknown | `0` | `None` |
| **/mnt/tank/M3351BSP/SampleCode/ISP/ISP_DFU/WindowsDriver/amd64/libusb0.dll** | `None` | file | Unknown | `0` | `None` |
| **/mnt/tank/M3351BSP/SampleCode/ISP/ISP_DFU/WindowsDriver/amd64/libusb0_x86.dll** | `None` | file | Unknown | `0` | `None` |
| **/mnt/tank/M3351BSP/SampleCode/ISP/ISP_DFU/WindowsDriver/amd64/libusbK.dll** | `None` | file | Unknown | `0` | `None` |
| **/mnt/tank/M3351BSP/SampleCode/ISP/ISP_DFU/WindowsDriver/amd64/libusbK_x86.dll** | `None` | file | Unknown | `0` | `None` |
| **/mnt/tank/M3351BSP/SampleCode/ISP/ISP_DFU/WindowsDriver/x86/WdfCoInstaller01011.dll** | `None` | file | Unknown | `0` | `None` |
| **/mnt/tank/M3351BSP/SampleCode/ISP/ISP_DFU/WindowsDriver/x86/install-filter.exe** | `None` | file | Unknown | `0` | `None` |
| **/mnt/tank/M3351BSP/SampleCode/ISP/ISP_DFU/WindowsDriver/x86/libusb0.dll** | `None` | file | Unknown | `0` | `None` |
| **/mnt/tank/M3351BSP/SampleCode/ISP/ISP_DFU/WindowsDriver/x86/libusb0_x86.dll** | `None` | file | Unknown | `0` | `None` |
| **/mnt/tank/M3351BSP/SampleCode/ISP/ISP_DFU/WindowsDriver/x86/libusbK.dll** | `None` | file | Unknown | `0` | `None` |
| **/mnt/tank/M3351BSP/SampleCode/ISP/ISP_DFU/WindowsDriver/x86/winusbcoinstaller2.dll** | `None` | file | Unknown | `0` | `None` |
| **/mnt/tank/M3351BSP/SampleCode/StdDriver/USBD_MicroPrinter/Windows driver/NuvPos58_Driver.exe** | `None` | file | Unknown | `0` | `None` |
| **/mnt/tank/M3351BSP/SampleCode/StdDriver/USBD_Printer_And_HID_Transfer/Windows driver/NuvPos58_Driver.exe** | `None` | file | Unknown | `0` | `None` |
| **/mnt/tank/M3351BSP/Tool/HIDTransferTest/Debug/HIDTransferTest.exe** | `None` | file | Unknown | `0` | `None` |
| **cmsis-core** | `5.9.0` | library | Apache-2.0 | `0` | `pkg:github/ARM-software/CMSIS_5@5.9.0` |
| **FatFs** | `0.15` | library | ChaN License | `0` | `pkg:generic/FatFs@0.15` |
| **FreeRTOS** | `10.5.1` | library | MIT | `1` | `pkg:github/FreeRTOS/FreeRTOS-Kernel@10.5.1` |
| **mbedtls** | `3.1.0` | library | Apache-2.0 | `22` | `pkg:github/Mbed-TLS/mbedtls@3.1.0` |

---

## 📝 Detailed Vulnerabilities List

Below is the list of identified vulnerabilities mapped to components:

| Severity | Vulnerability ID | Component | Version | Fix Status | Description |
| :---: | :--- | :--- | :--- | :---: | :--- |
| 🔴 Critical | `CVE-2025-47917` | **mbedtls** | `3.1.0` | `unknown` | Mbed TLS before 3.6.4 allows a use-after-free in certain situations of applications that are developed in accordance with the documentation. The funct... |
| 🔴 Critical | `CVE-2022-35409` | **mbedtls** | `3.1.0` | `unknown` | An issue was discovered in Mbed TLS before 2.28.1 and 3.x before 3.2.0. In some configurations, an unauthenticated attacker can send an invalid Client... |
| 🔴 Critical | `CVE-2022-46393` | **mbedtls** | `3.1.0` | `unknown` | An issue was discovered in Mbed TLS before 2.28.2 and 3.x before 3.3.0. There is a potential heap-based buffer overflow and heap-based buffer over-rea... |
| 🔴 Critical | `CVE-2026-34877` | **mbedtls** | `3.1.0` | `unknown` | An issue was discovered in Mbed TLS versions from 2.19.0 up to 3.6.5, Mbed TLS 4.0.0. Insufficient protection of serialized SSL context or session str... |
| 🔴 Critical | `CVE-2026-34872` | **mbedtls** | `3.1.0` | `unknown` | An issue was discovered in Mbed TLS 3.5.x and 3.6.x through 3.6.5 and TF-PSA-Crypto 1.0. There is a lack of contributory behavior in FFDH due to impro... |
| 🟠 High | `CVE-2024-23775` | **mbedtls** | `3.1.0` | `unknown` | Integer Overflow vulnerability in Mbed TLS 2.x before 2.28.7 and 3.x before 3.5.2, allows attackers to cause a denial of service (DoS) via mbedtls_x50... |
| 🟠 High | `CVE-2023-43615` | **mbedtls** | `3.1.0` | `unknown` | Mbed TLS 2.x before 2.28.5 and 3.x before 3.5.0 has a Buffer Overflow.... |
| 🟠 High | `CVE-2025-48965` | **mbedtls** | `3.1.0` | `unknown` | Mbed TLS before 3.6.4 has a NULL pointer dereference because mbedtls_asn1_store_named_data can trigger conflicting data with val.p of NULL but val.len... |
| 🟠 High | `CVE-2024-28960` | **mbedtls** | `3.1.0` | `unknown` | An issue was discovered in Mbed TLS 2.18.0 through 2.28.x before 2.28.8 and 3.x before 3.6.0, and Mbed Crypto. The PSA Crypto API mishandles shared me... |
| 🟠 High | `CVE-2025-52496` | **mbedtls** | `3.1.0` | `unknown` | Mbed TLS before 3.6.4 has a race condition in AESNI detection if certain compiler optimizations occur. An attacker may be able to extract an AES key f... |
| 🟠 High | `CVE-2023-52353` | **mbedtls** | `3.1.0` | `unknown` | An issue was discovered in Mbed TLS through 3.5.1. In mbedtls_ssl_session_reset, the maximum negotiable TLS version is mishandled. For example, if the... |
| 🟠 High | `CVE-2024-28115` | **FreeRTOS** | `10.5.1` | `unknown` | FreeRTOS is a real-time operating system for microcontrollers. FreeRTOS Kernel versions through 10.6.1 do not sufficiently protect against local privi... |
| 🟠 High | `CVE-2026-34876` | **mbedtls** | `3.1.0` | `unknown` | An issue was discovered in Mbed TLS 3.x before 3.6.6. An out-of-bounds read vulnerability in mbedtls_ccm_finish() in library/ccm.c allows attackers to... |
| 🟠 High | `CVE-2026-25835` | **mbedtls** | `3.1.0` | `unknown` | Mbed TLS before 3.6.6 and TF-PSA-Crypto before 1.1.0 misuse seeds in a Pseudo-Random Number Generator (PRNG).... |
| 🟡 Medium | `CVE-2025-52497` | **mbedtls** | `3.1.0` | `unknown` | Mbed TLS before 3.6.4 has a PEM parsing one-byte heap-based buffer underflow, in mbedtls_pem_read_buffer and two mbedtls_pk_parse functions, via untru... |
| 🟡 Medium | `CVE-2022-46392` | **mbedtls** | `3.1.0` | `unknown` | An issue was discovered in Mbed TLS before 2.28.2 and 3.x before 3.3.0. An adversary with access to precise enough information about memory accesses (... |
| 🟡 Medium | `CVE-2024-23170` | **mbedtls** | `3.1.0` | `unknown` | An issue was discovered in Mbed TLS 2.x before 2.28.7 and 3.x before 3.5.2. There was a timing side channel in RSA private operations. This side chann... |
| 🟡 Medium | `CVE-2025-27810` | **mbedtls** | `3.1.0` | `unknown` | Mbed TLS before 2.28.10 and 3.x before 3.6.3, in some cases of failed memory allocation or hardware errors, uses uninitialized stack memory to compose... |
| 🟡 Medium | `CVE-2025-27809` | **mbedtls** | `3.1.0` | `unknown` | Mbed TLS before 2.28.10 and 3.x before 3.6.3, on the client side, accepts servers that have trusted certificates for arbitrary hostnames unless the TL... |
| 🟡 Medium | `CVE-2025-59438` | **mbedtls** | `3.1.0` | `unknown` | Mbed TLS through 3.6.4 has an Observable Timing Discrepancy.... |
| 🟡 Medium | `CVE-2025-54764` | **mbedtls** | `3.1.0` | `unknown` | Mbed TLS before 3.6.5 allows a local timing attack against certain RSA operations, and direct calls to mbedtls_mpi_mod_inv or mbedtls_mpi_gcd.... |
| 🟡 Medium | `CVE-2025-66442` | **mbedtls** | `3.1.0` | `unknown` | In Mbed TLS through 4.0.0, there is a compiler-induced timing side channel (in RSA and CBC/ECB decryption) that only occurs with LLVM's select-optimiz... |
| 🟡 Medium | `CVE-2026-34871` | **mbedtls** | `3.1.0` | `unknown` | An issue was discovered in Mbed TLS before 3.6.6 and 4.x before 4.1.0 and TF-PSA-Crypto before 1.1.0. There is a Predictable Seed in a Pseudo-Random N... |
