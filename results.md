# Amazon m5.12xlarge

`Linux ip-10-0-0-55.ec2.internal 4.14.47-64.38.amzn2.x86_64 `

```
Architecture:        x86_64
CPU op-mode(s):      32-bit, 64-bit
Byte Order:          Little Endian
CPU(s):              48
On-line CPU(s) list: 0-47
Thread(s) per core:  2
Core(s) per socket:  24
Socket(s):           1
NUMA node(s):        1
Vendor ID:           GenuineIntel
CPU family:          6
Model:               85
Model name:          Intel(R) Xeon(R) Platinum 8175M CPU @ 2.50GHz
Stepping:            4
CPU MHz:             2140.140
BogoMIPS:            5000.00
Hypervisor vendor:   KVM
Virtualization type: full
L1d cache:           32K
L1i cache:           32K
L2 cache:            1024K
L3 cache:            33792K
NUMA node0 CPU(s):   0-47
Flags:               fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ss ht syscall nx pdpe1gb rdtscp lm constant_tsc arch_perfmon rep_good nopl xtopology nonstop_tsc cpuid aperfmperf pni pclmulqdq monitor ssse3 fma cx16 pcid sse4_1 sse4_2 x2apic movbe popcnt tsc_deadline_timer aes xsave avx f16c rdrand hypervisor lahf_lm abm 3dnowprefetch invpcid_single pti fsgsbase tsc_adjust bmi1 hle avx2 smep bmi2 erms invpcid rtm mpx avx512f avx512dq rdseed adx smap clflushopt clwb avx512cd avx512bw avx512vl xsaveopt xsavec xgetbv1 xsaves ida arat pku ospke
```

threads | throughput 
--------|-----------
1 | 1265.77
2 | 2395.03
4 | 4768.50
8 | 9338.83
12 | 13554.33
16 | 17018.47
20 | 19559.00
24 | 21570.36
30 | 23646.43
36 | 26074.58
42 | 32663.37
48 | 39095.84
56 | 38763.14
64 | 38307.01
72 | 38016.81
80 | 37990.24
90 | 38099.02
100 | 37805.40
128 | 37343.67
192 | 35976.13
256 | 34897.15
512 | 38466.43
1024 | 38416.31

# Amazon m5d.24xlarge

`Linux ip-10-0-0-135.ec2.internal 4.14.47-64.38.amzn2.x86_64`

```
Architecture:        x86_64
CPU op-mode(s):      32-bit, 64-bit
Byte Order:          Little Endian
CPU(s):              96
On-line CPU(s) list: 0-95
Thread(s) per core:  2
Core(s) per socket:  24
Socket(s):           2
NUMA node(s):        2
Vendor ID:           GenuineIntel
CPU family:          6
Model:               85
Model name:          Intel(R) Xeon(R) Platinum 8175M CPU @ 2.50GHz
Stepping:            4
CPU MHz:             1434.020
BogoMIPS:            5000.00
Hypervisor vendor:   KVM
Virtualization type: full
L1d cache:           32K
L1i cache:           32K
L2 cache:            1024K
L3 cache:            33792K
NUMA node0 CPU(s):   0-23,48-71
NUMA node1 CPU(s):   24-47,72-95
Flags:               fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ss ht syscall nx pdpe1gb rdtscp lm constant_tsc arch_perfmon rep_good nopl xtopology nonstop_tsc cpuid aperfmperf pni pclmulqdq monitor ssse3 fma cx16 pcid sse4_1 sse4_2 x2apic movbe popcnt tsc_deadline_timer aes xsave avx f16c rdrand hypervisor lahf_lm abm 3dnowprefetch invpcid_single pti fsgsbase tsc_adjust bmi1 hle avx2 smep bmi2 erms invpcid rtm mpx avx512f avx512dq rdseed adx smap clflushopt clwb avx512cd avx512bw avx512vl xsaveopt xsavec xgetbv1 xsaves ida arat pku ospke
```

threads | throughput 
--------|-----------
1 | 1262.06
2 | 2471.29
4 | 4691.86
8 | 9237.46
12 | 13603.88
16 | 17909.05
20 | 22185.41
24 | 25898.27
30 | 31011.24
36 | 34857.49
42 | 38141.69
48 | 40755.52
56 | 43423.67
64 | 45791.34
72 | 49338.21
80 | 57263.65
90 | 65448.18
100 | 71815.08
128 | 71134.12
192 | 69581.45
256 | 66604.79
512 | 62648.34
1024 | 68831.86

# Amazon c5d.18xlarge

`Linux ip-10-0-0-82.ec2.internal 4.14.47-64.38.amzn2.x86_64`

```
Architecture:        x86_64
CPU op-mode(s):      32-bit, 64-bit
Byte Order:          Little Endian
CPU(s):              72
On-line CPU(s) list: 0-71
Thread(s) per core:  2
Core(s) per socket:  18
Socket(s):           2
NUMA node(s):        2
Vendor ID:           GenuineIntel
CPU family:          6
Model:               85
Model name:          Intel(R) Xeon(R) Platinum 8124M CPU @ 3.00GHz
Stepping:            4
CPU MHz:             1672.009
BogoMIPS:            6000.00
Hypervisor vendor:   KVM
Virtualization type: full
L1d cache:           32K
L1i cache:           32K
L2 cache:            1024K
L3 cache:            25344K
NUMA node0 CPU(s):   0-17,36-53
NUMA node1 CPU(s):   18-35,54-71
Flags:               fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ss ht syscall nx pdpe1gb rdtscp lm constant_tsc arch_perfmon rep_good nopl xtopology nonstop_tsc cpuid aperfmperf pni pclmulqdq monitor ssse3 fma cx16 pcid sse4_1 sse4_2 x2apic movbe popcnt tsc_deadline_timer aes xsave avx f16c rdrand hypervisor lahf_lm abm 3dnowprefetch invpcid_single pti fsgsbase tsc_adjust bmi1 hle avx2 smep bmi2 erms invpcid rtm mpx avx512f avx512dq rdseed adx smap clflushopt clwb avx512cd avx512bw avx512vl xsaveopt xsavec xgetbv1 xsaves ida arat pku ospke
```

threads | throughput 
--------|-----------
1 | 1228.26
2 | 2401.11
4 | 4625.90
8 | 9107.63
12 | 13497.11
16 | 17745.19
20 | 21655.97
24 | 24830.36
30 | 28613.84
36 | 31931.37
42 | 33759.56
48 | 35596.92
56 | 41022.56
64 | 49056.68
72 | 58140.84
80 | 57414.28
90 | 56810.35
100 | 56025.96
128 | 55822.00
192 | 52944.75
256 | 51025.37
512 | 55792.19
1024 | 54902.98

# Amazon c5d.9xlarge

`Linux ip-10-0-0-254.ec2.internal 4.14.47-64.38.amzn2.x86_64`

```
Architecture:        x86_64
CPU op-mode(s):      32-bit, 64-bit
Byte Order:          Little Endian
CPU(s):              36
On-line CPU(s) list: 0-35
Thread(s) per core:  2
Core(s) per socket:  18
Socket(s):           1
NUMA node(s):        1
Vendor ID:           GenuineIntel
CPU family:          6
Model:               85
Model name:          Intel(R) Xeon(R) Platinum 8124M CPU @ 3.00GHz
Stepping:            4
CPU MHz:             2900.038
BogoMIPS:            6000.00
Hypervisor vendor:   KVM
Virtualization type: full
L1d cache:           32K
L1i cache:           32K
L2 cache:            1024K
L3 cache:            25344K
NUMA node0 CPU(s):   0-35
Flags:               fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ss ht syscall nx pdpe1gb rdtscp lm constant_tsc arch_perfmon rep_good nopl xtopology nonstop_tsc cpuid aperfmperf pni pclmulqdq monitor ssse3 fma cx16 pcid sse4_1 sse4_2 x2apic movbe popcnt tsc_deadline_timer aes xsave avx f16c rdrand hypervisor lahf_lm abm 3dnowprefetch invpcid_single pti fsgsbase tsc_adjust bmi1 hle avx2 smep bmi2 erms invpcid rtm mpx avx512f avx512dq rdseed adx smap clflushopt clwb avx512cd avx512bw avx512vl xsaveopt xsavec xgetbv1 xsaves ida arat pku ospke
```

threads | throughput 
--------|-----------
1 | 1227.80
2 | 2406.08
4 | 4773.12
8 | 9334.30
12 | 13112.17
16 | 15731.87
20 | 17755.95
24 | 18832.21
30 | 24285.73
36 | 31329.32
42 | 31171.16
48 | 30824.06
56 | 30567.31
64 | 30483.70
72 | 30504.17
80 | 30227.47
90 | 30058.98
100 | 29709.41
128 | 29021.73
192 | 27665.97
256 | 31003.29
512 | 30928.03
1024 | 30713.47

# Google n1-standard-96

`Linux ps-node-1 4.15.0-1009-gcp`
```
Architecture:        x86_64
CPU op-mode(s):      32-bit, 64-bit
Byte Order:          Little Endian
CPU(s):              96
On-line CPU(s) list: 0-95
Thread(s) per core:  2
Core(s) per socket:  24
Socket(s):           2
NUMA node(s):        2
Vendor ID:           GenuineIntel
CPU family:          6
Model:               85
Model name:          Intel(R) Xeon(R) CPU @ 2.00GHz
Stepping:            3
CPU MHz:             2000.182
BogoMIPS:            4000.36
Hypervisor vendor:   KVM
Virtualization type: full
L1d cache:           32K
L1i cache:           32K
L2 cache:            256K
L3 cache:            56320K
NUMA node0 CPU(s):   0-23,48-71
NUMA node1 CPU(s):   24-47,72-95
Flags:               fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ss ht syscall nx pdpe1gb rdtscp lm constant_tsc rep_good nopl xtopology nonstop_tsc cpuid pni pclmulqdq ssse3 fma cx16 pcid sse4_1 sse4_2 x2apic movbe popcnt aes xsave avx f16c rdrand hypervisor lahf_lm abm 3dnowprefetch invpcid_single pti fsgsbase tsc_adjust bmi1 hle avx2 smep bmi2 erms invpcid rtm mpx avx512f avx512dq rdseed adx smap clflushopt clwb avx512cd avx512bw avx512vl xsaveopt xsavec xgetbv1 xsaves
```

threads | throughput 
--------|-----------
1 | 904.75
2 | 1870.22
4 | 3513.63
8 | 6990.49
12 | 10121.54
16 | 12933.22
20 | 15631.41
24 | 18664.26
30 | 21455.37
36 | 23594.94
42 | 25061.66
48 | 26410.39
56 | 28277.60
64 | 30894.86
72 | 33913.95
80 | 40847.05
90 | 49595.22
100 | 56569.86
128 | 55012.86
192 | 54699.59
256 | 53364.88
512 | 49968.71
1024 | 45820.81
