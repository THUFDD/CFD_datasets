# Compound fault diagnosis dataset of rotating machinery

**Description**: The experimental data is collected from a realistic large-scale rotating machinery fault diagnosis experimental platform. The test rig is utilized in Guangdong Province Key Laboratory for petrochemical equipment fault diagnosis. Initial vibration signals are obtained by sensors installed on the gearbox with a US CTC accelerometer mounted vertically on the gearbox. In detail, it is a centrifugal multi-stage impeller blower with crucial components such as a three-phase induction motor, gearbox, bearing, load, and shaft. In addition, gear wheels and pinions are engaged and abrade mutually inside the gearbox.

**The details of data folds:**

- F0: Normal bearing; Normal gearwheel

- F1: Normal bearing; Defective gearwheel 

- F2: Defective inner-ring of bearing; Normal gearwheel

- F3: Defective inner-ring of bearing; Defective gearwheel 

- F4: Defective outer-ring of bearing; Normal gearwheel

- F5: Defective outer-ring of bearing; Defective gearwheel 

- F6: Bearing with the absence of balls; Normal gearwheel

- F7: Bearing with the absence of balls; Defective gearwheel 

**The photograph of the utilized test rig:**

<img width="383" alt="photo" src="https://user-images.githubusercontent.com/115722686/195637306-ac88470b-9b61-45de-89aa-a94cfed8cfa8.png">

**The schematic diagram of the utilized test rig:**

<img width="530" alt="platform" src="https://user-images.githubusercontent.com/115722686/195636988-4477e226-16f5-4215-8601-febda5109235.png">

**The description of parameters:**

- *chip*: Data collection channel 
- *wave*: Collected vibration signal

The equipment is supported by *Guangdong Province Key Laboratory for petrochemical equipment fault diagnosis*.

## Citation
**Please consider citing the following work if you use the datasets:**
```
@ARTICLE{9869794,
  author={Liu, Zeyi and Zhang, Jingfei and He, Xiao and Zhang, Qinghua and Sun, Guoxi and Zhou, Donghua},
  journal={IEEE Transactions on Control Systems Technology}, 
  title={Fault Diagnosis of Rotating Machinery With Limited Expert Interaction: A Multicriteria Active Learning Approach Based on Broad Learning System}, 
  year={2023},
  volume={31},
  number={2},
  pages={953-960},
  doi={10.1109/TCST.2022.3200214}}
```
