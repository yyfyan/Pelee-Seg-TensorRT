# Pelee-TensorRT

**Accelerate Pelee with TensorRT**
Pelee: A Real-Time Object Detection System on Mobile Devices (NeurIPS 2018) 

**TensorRT-Pelee can run over 70FPS(11ms) on Jetson TX2(FP32)**

---

**Performance:** <br>
Jetson TX2: 72 FPS, 13.2~11 ms (FP32) <br>
Titan V:  200FPS, 5 ms (FP32)<br>

**Requierments:**

1.TensorRT4 (Jetpack 3.3 on TX2)  <br>
2.CUDA 9.0 <br>
3.cudnn7 <br>

---

**Run:**

```shell
cmake .
make
./build/bin/pelee
```

---

**Reference:**

https://github.com/Ghustwb/MobileNet-SSD-TensorRT

---

**TODO:**
- [ ] FP16 Implementation 
- [ ] Change Custom layers IPlugin to IPluginExt




**The bug has been fixed**

![image](testPic/test.png)
