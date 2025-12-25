# I Bought the "Framework Desktop"

![image](photos/desktop.png)

## Specs

| Component | Details |
|---------|---------|
| **CPU** | AMD Ryzen 8600G ($210) |
| **GPU** | AMD Radeon 760M (APU) |
| **RAM** | 16GB (2×8GB) ADATA DDR5 4800MHz ($73 **USED**) |
| **Motherboard** | Gigabyte A620I AX ($145) |
| **Case** | InWin Chopin MAX ($115) |
| **SSD** | ADATA Legend 860 ($70) |
| **Total Price** | **$613** |

---

## Benchmarks

Before starting with the benchmarks, it is important to mention that all benchmarks were recorded using a **capture card**, meaning there was no performance loss due to recording.

This section is divided into two parts:

- **General**: Benchmarks taken after the BIOS update, focusing on overall performance.
- **Before vs. After BIOS Update**: Benchmarks recorded before and after installing the newest BIOS update, which resulted in a surprising performance boost.

---

### General

In Cinebench, the biggest difference was in the multicore result.

<p align="center">
  <img src="photos/cinebench_single.png" width="48%">
  <img src="photos/cinebench_multi.png" width="48%">
</p>

I was a little disappointed by the results. I did not expect my system to perform this much worse compared to the average for the same CPU–GPU combination. Based on my findings, there are two main reasons for this:

- **Low Memory Frequency**: In my opinion, this is the biggest reason. Since I was not able to buy faster RAM, the limited memory bandwidth caused the GPU to be bottlenecked.
- **No Overclocking**: Due to the A620 chipset, which does not allow overclocking, I was not able to get the full performance out of the APU.

![image](photos/firestrike.png)

---

### Before vs. After BIOS Update

Before the BIOS update, the system was running BIOS version **F23**, first released in April 2024. I then downloaded and installed version **F38**, which resulted in the following difference in Fire Strike:

![image](photos/before_after_firestrike.png)

I also re-ran Cinebench, but the difference in results was basically zero, so I did not include it here. This indicates that the biggest improvement came from the GPU.

For gaming performance, I tested FPS at the same location at 1080p on Deathmatch Mirage in CS2. The difference is quite significant: performance increased from **89 FPS to 108 FPS**. However, the low and high FPS values stayed almost the same.

<p align="center">
  <img src="photos/cs_bef.png" width="48%">
  <img src="photos/cs_aft.png" width="48%">
</p>

In PUBG, the overall difference was not as significant. This may be due to the fact that the tests were performed on two different maps.

<p align="center">
  <img src="photos/pubg_bef.png" width="48%">
  <img src="photos/pubg_aft.png" width="48%">
</p>
