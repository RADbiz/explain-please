# explain-please
My “life” has been hacked and need some help. Sick of being set up. Please explain the following code to me. 
{"share_with_app_devs":1,"app_version":"","bug_type":"145","timestamp":"2022-07-21 09:03:52.00 +1000","os_version":"iPhone OS 15.5 (19F77)","slice_uuid":"120FE649-6EC3-3637-9E32-105B4A6BBC3D","is_first_party":1,"build_version":"","incident_id":"D9E391AF-F4CB-4DAB-9B8F-99905BC47BFC","app_name":"aggregated","name":"aggregated"}
Date/Time:        2022-07-21 01:14:32.090 +1000
End time:         2022-07-21 09:03:50.914 +1000
OS Version:       iPhone OS 15.5 (Build 19F77)
Architecture:     arm64e
Report Version:   35.1
Incident Identifier: D9E391AF-F4CB-4DAB-9B8F-99905BC47BFC
Share With Devs:  Yes

Data Source:      Microstackshots
Shared Cache:     D3BF9328-5873-39B5-86EB-DDA04C31F0D3 slid base address 0x1dfa2c000, slide 0x5fa2c000

Command:          aggregated
Path:             /System/Library/PrivateFrameworks/AggregateDictionary.framework/Support/aggregated
Architecture:     arm64
PID:              417

Event:            disk writes
Action taken:     none
Writes:           1073.75 MB of file backed memory dirtied over 28159 seconds (38.13 KB per second average), exceeding limit of 12.43 KB per second over 86400 seconds
Writes limit:     1073.74 MB
Limit duration:   86400s
Writes caused:    1073.75 MB
Writes duration:  28159s
Duration:         28158.82s
Duration Sampled: 28054.23s
Steps:            685 ( (10.49 MB/step))

Hardware model:   iPhone14,2
Active cpus:      6
HW page size:     16384
VM page size:     16384

Advisory levels:  Battery -> 1, User -> 3, ThermalPressure -> 0, Combined -> 1
Free disk space:  398.31 GB/476.72 GB, low space threshold 150 MB

Heaviest stack for the target process:
  57  ??? (libsystem_pthread.dylib + 3676) [0x2516dbe5c]
  44  ??? (libsystem_pthread.dylib + 4284) [0x2516dc0bc]
  44  ??? (libdispatch.dylib + 91392) [0x1dfa93500]
  24  ??? (libdispatch.dylib + 48308) [0x1dfa88cb4]
  24  ??? (libdispatch.dylib + 45348) [0x1dfa88124]
  24  ??? (libdispatch.dylib + 14896) [0x1dfa80a30]
  24  ??? (libdispatch.dylib + 7788) [0x1dfa7ee6c]
  12  ??? (PowerlogCore + 56240) [0x20405abb0]
  12  ??? (PowerlogCore + 74952) [0x20405f4c8]
  12  ??? (PowerlogCore + 147400) [0x204070fc8]
  12  ??? (PowerlogCore + 22080) [0x204052640]
  12  ??? (PowerlogCore + 73828) [0x20405f064]
  12  ??? (libdispatch.dylib + 76944) [0x1dfa8fc90]
  12  ??? (libdispatch.dylib + 14896) [0x1dfa80a30]
  12  ??? (PowerlogCore + 121092) [0x20406a904]
  12  ??? (PowerlogCore + 17800) [0x204051588]
  6   ??? (libsqlite3.dylib + 280164) [0x1fece0664]
  6   ??? (libsqlite3.dylib + 450148) [0x1fed09e64]
  6   ??? (libsqlite3.dylib + 668344) [0x1fed3f2b8]
  6   ??? (libsqlite3.dylib + 668780) [0x1fed3f46c]
  6   ??? (libsqlite3.dylib + 535260) [0x1fed1eadc]
  6   ??? (libsqlite3.dylib + 449148) [0x1fed09a7c]
  6   ??? (libsystem_kernel.dylib + 12732) [0x2179aa1bc]


Powerstats for:   aggregated [417]
UUID:             120FE649-6EC3-3637-9E32-105B4A6BBC3D
Path:             /System/Library/PrivateFrameworks/AggregateDictionary.framework/Support/aggregated
Architecture:     arm64
Footprint:        11.08 MB -> 13.42 MB (+2400 KB)
Pageins:          76 pages
Start time:       2022-07-21 02:03:05.312 +1000
End time:         2022-07-21 09:03:33.102 +1000
Num samples:      57 (8%)
Primary state:    44 samples Non-Frontmost App, Non-Suppressed, Kernel mode, Effective Thread QoS Background, Requested Thread QoS Background, Override Thread QoS Unspecified
User Activity:    45 samples Idle, 12 samples Active
Power Source:     50 samples on Battery, 7 samples on AC
  57  ??? (libsystem_pthread.dylib + 3676) [0x2516dbe5c]
    44  ??? (libsystem_pthread.dylib + 4284) [0x2516dc0bc]
      44  ??? (libdispatch.dylib + 91392) [0x1dfa93500]
        24  ??? (libdispatch.dylib + 48308) [0x1dfa88cb4]
          24  ??? (libdispatch.dylib + 45348) [0x1dfa88124]
            24  ??? (libdispatch.dylib + 14896) [0x1dfa80a30]
              24  ??? (libdispatch.dylib + 7788) [0x1dfa7ee6c]
                12  ??? (PowerlogCore + 56240) [0x20405abb0]
                  12  ??? (PowerlogCore + 74952) [0x20405f4c8]
                    12  ??? (PowerlogCore + 147400) [0x204070fc8]
                      12  ??? (PowerlogCore + 22080) [0x204052640]
                        12  ??? (PowerlogCore + 73828) [0x20405f064]
                          12  ??? (libdispatch.dylib + 76944) [0x1dfa8fc90]
                            12  ??? (libdispatch.dylib + 14896) [0x1dfa80a30]
                              12  ??? (PowerlogCore + 121092) [0x20406a904]
                                12  ??? (PowerlogCore + 17800) [0x204051588]
                                  6   ??? (libsqlite3.dylib + 280164) [0x1fece0664]
                                    6   ??? (libsqlite3.dylib + 450148) [0x1fed09e64]
                                      6   ??? (libsqlite3.dylib + 668344) [0x1fed3f2b8]
                                        6   ??? (libsqlite3.dylib + 668780) [0x1fed3f46c]
                                          6   ??? (libsqlite3.dylib + 535260) [0x1fed1eadc]
                                            6   ??? (libsqlite3.dylib + 449148) [0x1fed09a7c]
                                              6   ??? (libsystem_kernel.dylib + 12732) [0x2179aa1bc]
                                  6   ??? (libsqlite3.dylib + 279112) [0x1fece0248]
                                    6   ??? (libsqlite3.dylib + 338988) [0x1feceec2c]
                                      6   ??? (libsqlite3.dylib + 149920) [0x1fecc09a0]
                                        6   ??? (libsqlite3.dylib + 364512) [0x1fecf4fe0]
                                          6   ??? (libsqlite3.dylib + 447216) [0x1fed092f0]
                                            6   ??? (libsqlite3.dylib + 784408) [0x1fed5b818]
                                              6   ??? (libsqlite3.dylib + 449148) [0x1fed09a7c]
                                                6   ??? (libsystem_kernel.dylib + 12732) [0x2179aa1bc]
                12  ??? (PowerlogCore + 56152) [0x20405ab58]
                  12  ??? (PowerlogCore + 118104) [0x204069d58]
                    12  ??? (CoreFoundation + 360908) [0x1dfdd81cc]
                      12  ??? (CoreFoundation + 262584) [0x1dfdc01b8]
                        12  ??? (PowerlogCore + 506984) [0x2040c8c68]
                          12  ??? (PowerlogCore + 137936) [0x20406ead0]
                            12  ??? (PowerlogCore + 510816) [0x2040c9b60]
                              12  ??? (PowerlogCore + 115432) [0x2040692e8]
                                12  ??? (PowerlogCore + 22080) [0x204052640]
                                  12  ??? (PowerlogCore + 73828) [0x20405f064]
                                    12  ??? (libdispatch.dylib + 76944) [0x1dfa8fc90]
                                      12  ??? (libdispatch.dylib + 14896) [0x1dfa80a30]
                                        12  ??? (PowerlogCore + 121092) [0x20406a904]
                                          12  ??? (PowerlogCore + 17800) [0x204051588]
                                            12  ??? (libsqlite3.dylib + 279112) [0x1fece0248]
                                              12  ??? (libsqlite3.dylib + 338920) [0x1feceebe8]
                                                12  ??? (libsqlite3.dylib + 149920) [0x1fecc09a0]
                                                  12  ??? (libsqlite3.dylib + 364512) [0x1fecf4fe0]
                                                    12  ??? (libsqlite3.dylib + 447216) [0x1fed092f0]
                                                      12  ??? (libsqlite3.dylib + 784408) [0x1fed5b818]
                                                        12  ??? (libsqlite3.dylib + 449148) [0x1fed09a7c]
                                                          12  ??? (libsystem_kernel.dylib + 12732) [0x2179aa1bc]
        20  ??? (libdispatch.dylib + 48256) [0x1dfa88c80]
          20  ??? (libdispatch.dylib + 45056) [0x1dfa88000]
            17  ??? (libdispatch.dylib + 133196) [0x1dfa9d84c]
              17  ??? (libdispatch.dylib + 45056) [0x1dfa88000]
                17  ??? (libdispatch.dylib + 129836) [0x1dfa9cb2c]
                  17  ??? (libdispatch.dylib + 15088) [0x1dfa80af0]
                    17  ??? (libxpc.dylib + 64616) [0x251705c68]
                      17  ??? (libxpc.dylib + 63544) [0x251705838]
                        12  ??? (aggregated + 20560) [0x1007f5050]
                          10  ??? (aggregated + 24408) [0x1007f5f58]
                            4   ??? (aggregated + 18968) [0x1007f4a18]
                              4   ??? (aggregated + 27792) [0x1007f6c90]
                                4   ??? (libsqlite3.dylib + 663084) [0x1fed3de2c]
                                  4   ??? (libsqlite3.dylib + 621844) [0x1fed33d14]
                                    4   ??? (libsqlite3.dylib + 475592) [0x1fed101c8]
                                      4   ??? (libsqlite3.dylib + 477016) [0x1fed10758]
                                        4   ??? (libsqlite3.dylib + 477832) [0x1fed10a88]
                                          4   ??? (libsqlite3.dylib + 535260) [0x1fed1eadc]
                                            4   ??? (libsqlite3.dylib + 449148) [0x1fed09a7c]
                                              4   ??? (libsystem_kernel.dylib + 12732) [0x2179aa1bc]
                            3   ??? (aggregated + 18928) [0x1007f49f0]
                              3   ??? (aggregated + 28468) [0x1007f6f34]
                                3   ??? (libsqlite3.dylib + 40196) [0x1feca5d04]
                                  3   ??? (libsqlite3.dylib + 279112) [0x1fece0248]
                                    3   ??? (libsqlite3.dylib + 338988) [0x1feceec2c]
                                      3   ??? (libsqlite3.dylib + 149920) [0x1fecc09a0]
                                        3   ??? (libsqlite3.dylib + 364512) [0x1fecf4fe0]
                                          3   ??? (libsqlite3.dylib + 447216) [0x1fed092f0]
                                            2   ??? (libsqlite3.dylib + 784844) [0x1fed5b9cc]
                                              2   ??? (libsqlite3.dylib + 449564) [0x1fed09c1c]
                                                2   ??? (libsystem_kernel.dylib + 14796) [0x2179aa9cc]
                                            1   ??? (libsqlite3.dylib + 784408) [0x1fed5b818]
                                              1   ??? (libsqlite3.dylib + 449148) [0x1fed09a7c]
                                                1   ??? (libsystem_kernel.dylib + 12732) [0x2179aa1bc]
                            2   ??? (aggregated + 18748) [0x1007f493c]
                              2   ??? (aggregated + 27928) [0x1007f6d18]
                                2   ??? (aggregated + 28100) [0x1007f6dc4]
                                  2   ??? (aggregated + 28228) [0x1007f6e44]
                                    2   ??? (aggregated + 28468) [0x1007f6f34]
                                      2   ??? (libsqlite3.dylib + 40164) [0x1feca5ce4]
                                        2   ??? (libsqlite3.dylib + 42212) [0x1feca64e4]
                                          2   ??? (libsqlite3.dylib + 43072) [0x1feca6840]
                                            2   ??? (libsqlite3.dylib + 45704) [0x1feca7288]
                                              2   ??? (libsqlite3.dylib + 60872) [0x1fecaadc8]
                                                2   ??? (libsqlite3.dylib + 101412) [0x1fecb4c24]
                                                  2   ??? (libsqlite3.dylib + 127088) [0x1fecbb070]
                                                    2   ??? (libsqlite3.dylib + 128072) [0x1fecbb448]
                                                      2   ??? (libsqlite3.dylib + 154464) [0x1fecc1b60]
                                                        2   ??? (libsqlite3.dylib + 156296) [0x1fecc2288]
                                                          2   ??? (libsqlite3.dylib + 163304) [0x1fecc3de8]
                                                            2   ??? (libsqlite3.dylib + 165416) [0x1fecc4628]
                                                              2   ??? (libsqlite3.dylib + 787192) [0x1fed5c2f8]
                                                                2   ??? (libsystem_kernel.dylib + 12732) [0x2179aa1bc]
                            1   ??? (aggregated + 18776) [0x1007f4958]
                              1   ??? (libsystem_c.dylib + 90248) [0x1eaf15088]
                                1   ??? (libsystem_c.dylib + 39820) [0x1eaf08b8c]
                                  1   ??? (libsystem_c.dylib + 35940) [0x1eaf07c64]
                                    1   ??? (libsystem_kernel.dylib + 13592) [0x2179aa518]
                          2   ??? (aggregated + 24208) [0x1007f5e90]
                            2   ??? (aggregated + 13820) [0x1007f35fc]
                              2   ??? (libsystem_c.dylib + 38336) [0x1eaf085c0]
                                2   ??? (libsystem_c.dylib + 71824) [0x1eaf10890]
                                  2   ??? (libsystem_c.dylib + 17380) [0x1eaf033e4]
                                    2   ??? (libsystem_c.dylib + 40912) [0x1eaf08fd0]
                                      2   ??? (libsystem_c.dylib + 39820) [0x1eaf08b8c]
                                        2   ??? (libsystem_c.dylib + 35940) [0x1eaf07c64]
                                          2   ??? (libsystem_kernel.dylib + 13592) [0x2179aa518]
                        5   ??? (aggregated + 20896) [0x1007f51a0]
                          5   ??? (libxpc.dylib + 81988) [0x25170a044]
                            5   ??? (libxpc.dylib + 77660) [0x251708f5c]
                              5   ??? (libxpc.dylib + 82088) [0x25170a0a8]
                                5   ??? (aggregated + 22312) [0x1007f5728]
                                  5   ??? (aggregated + 24208) [0x1007f5e90]
                                    5   ??? (aggregated + 13820) [0x1007f35fc]
                                      5   ??? (libsystem_c.dylib + 38336) [0x1eaf085c0]
                                        5   ??? (libsystem_c.dylib + 71824) [0x1eaf10890]
                                          5   ??? (libsystem_c.dylib + 17380) [0x1eaf033e4]
                                            5   ??? (libsystem_c.dylib + 40912) [0x1eaf08fd0]
                                              5   ??? (libsystem_c.dylib + 39820) [0x1eaf08b8c]
                                                5   ??? (libsystem_c.dylib + 35940) [0x1eaf07c64]
                                                  5   ??? (libsystem_kernel.dylib + 13592) [0x2179aa518]
            3   ??? (libdispatch.dylib + 135700) [0x1dfa9e214]
              3   ??? (libdispatch.dylib + 15024) [0x1dfa80ab0]
                3   ??? (libxpc.dylib + 60364) [0x251704bcc]
                  3   ??? (libxpc.dylib + 112300) [0x2517116ac]
                    3   ??? (libxpc.dylib + 181380) [0x251722484]
                      3   ??? (libxpc.dylib + 181756) [0x2517225fc]
                        3   ??? (libxpc.dylib + 180284) [0x25172203c]
                          3   ??? (PowerlogCore + 681540) [0x2040f3644]
                            3   ??? (PowerlogCore + 681724) [0x2040f36fc]
                              3   ??? (PowerlogCore + 680996) [0x2040f3424]
                                3   ??? (PowerlogCore + 679556) [0x2040f2e84]
                                  3   ??? (PowerlogCore + 423308) [0x2040b458c]
                                    3   ??? (libsqlite3.dylib + 40196) [0x1feca5d04]
                                      2   ??? (libsqlite3.dylib + 280164) [0x1fece0664]
                                        2   ??? (libsqlite3.dylib + 450148) [0x1fed09e64]
                                          2   ??? (libsqlite3.dylib + 668344) [0x1fed3f2b8]
                                            2   ??? (libsqlite3.dylib + 668780) [0x1fed3f46c]
                                              2   ??? (libsqlite3.dylib + 535260) [0x1fed1eadc]
                                                2   ??? (libsqlite3.dylib + 449148) [0x1fed09a7c]
                                                  2   ??? (libsystem_kernel.dylib + 12732) [0x2179aa1bc]
                                      1   ??? (libsqlite3.dylib + 279112) [0x1fece0248]
                                        1   ??? (libsqlite3.dylib + 338920) [0x1feceebe8]
                                          1   ??? (libsqlite3.dylib + 149920) [0x1fecc09a0]
                                            1   ??? (libsqlite3.dylib + 364512) [0x1fecf4fe0]
                                              1   ??? (libsqlite3.dylib + 447216) [0x1fed092f0]
                                                1   ??? (libsqlite3.dylib + 784408) [0x1fed5b818]
                                                  1   ??? (libsqlite3.dylib + 449148) [0x1fed09a7c]
                                                    1   ??? (libsystem_kernel.dylib + 12732) [0x2179aa1bc]
    13  ??? (libsystem_pthread.dylib + 4224) [0x2516dc080]
      13  ??? (libdispatch.dylib + 88428) [0x1dfa9296c]
        13  ??? (libdispatch.dylib + 86656) [0x1dfa92280]
          13  ??? (libdispatch.dylib + 14896) [0x1dfa80a30]
            13  ??? (libdispatch.dylib + 7788) [0x1dfa7ee6c]
              13  ??? (PowerlogCore + 588168) [0x2040dc988]
                13  ??? (PowerlogCore + 840312) [0x20411a278]
                  13  ??? (PowerlogCore + 391616) [0x2040ac9c0]
                    13  ??? (PowerlogCore + 367056) [0x2040a69d0]
                      13  ??? (PowerlogCore + 245472) [0x204088ee0]
                        7   ??? (PowerlogCore + 56240) [0x20405abb0]
                          7   ??? (PowerlogCore + 74952) [0x20405f4c8]
                            7   ??? (PowerlogCore + 147400) [0x204070fc8]
                              7   ??? (PowerlogCore + 22080) [0x204052640]
                                7   ??? (PowerlogCore + 73828) [0x20405f064]
                                  7   ??? (libdispatch.dylib + 76944) [0x1dfa8fc90]
                                    7   ??? (libdispatch.dylib + 14896) [0x1dfa80a30]
                                      7   ??? (PowerlogCore + 121092) [0x20406a904]
                                        7   ??? (PowerlogCore + 17800) [0x204051588]
                                          5   ??? (libsqlite3.dylib + 280164) [0x1fece0664]
                                            5   ??? (libsqlite3.dylib + 450148) [0x1fed09e64]
                                              5   ??? (libsqlite3.dylib + 668344) [0x1fed3f2b8]
                                                5   ??? (libsqlite3.dylib + 668780) [0x1fed3f46c]
                                                  5   ??? (libsqlite3.dylib + 535260) [0x1fed1eadc]
                                                    5   ??? (libsqlite3.dylib + 449148) [0x1fed09a7c]
                                                      5   ??? (libsystem_kernel.dylib + 12732) [0x2179aa1bc]
                                                        5   <Requested Thread QoS User Initiated>
                                          2   ??? (libsqlite3.dylib + 279112) [0x1fece0248]
                                            2   ??? (libsqlite3.dylib + 338988) [0x1feceec2c]
                                              2   ??? (libsqlite3.dylib + 149920) [0x1fecc09a0]
                                                2   ??? (libsqlite3.dylib + 364512) [0x1fecf4fe0]
                                                  2   ??? (libsqlite3.dylib + 447216) [0x1fed092f0]
                                                    2   ??? (libsqlite3.dylib + 784408) [0x1fed5b818]
                                                      2   ??? (libsqlite3.dylib + 449148) [0x1fed09a7c]
                                                        2   ??? (libsystem_kernel.dylib + 12732) [0x2179aa1bc]
                                                          2   <Requested Thread QoS User Initiated>
                        6   ??? (PowerlogCore + 56152) [0x20405ab58]
                          6   ??? (PowerlogCore + 118104) [0x204069d58]
                            6   ??? (CoreFoundation + 360908) [0x1dfdd81cc]
                              6   ??? (CoreFoundation + 262584) [0x1dfdc01b8]
                                6   ??? (PowerlogCore + 506984) [0x2040c8c68]
                                  6   ??? (PowerlogCore + 137936) [0x20406ead0]
                                    6   ??? (PowerlogCore + 510816) [0x2040c9b60]
                                      6   ??? (PowerlogCore + 115432) [0x2040692e8]
                                        6   ??? (PowerlogCore + 22080) [0x204052640]
                                          6   ??? (PowerlogCore + 73828) [0x20405f064]
                                            6   ??? (libdispatch.dylib + 76944) [0x1dfa8fc90]
                                              6   ??? (libdispatch.dylib + 14896) [0x1dfa80a30]
                                                6   ??? (PowerlogCore + 121092) [0x20406a904]
                                                  6   ??? (PowerlogCore + 17800) [0x204051588]
                                                    6   ??? (libsqlite3.dylib + 279112) [0x1fece0248]
                                                      6   ??? (libsqlite3.dylib + 338920) [0x1feceebe8]
                                                        6   ??? (libsqlite3.dylib + 149920) [0x1fecc09a0]
                                                          6   ??? (libsqlite3.dylib + 364512) [0x1fecf4fe0]
                                                            6   ??? (libsqlite3.dylib + 447216) [0x1fed092f0]
                                                              6   ??? (libsqlite3.dylib + 784408) [0x1fed5b818]
                                                                6   ??? (libsqlite3.dylib + 449148) [0x1fed09a7c]
                                                                  6   ??? (libsystem_kernel.dylib + 12732) [0x2179aa1bc]
                                                                    6   <Requested Thread QoS User Initiated>

  Binary Images:
           0x1007f0000 -                ???  aggregated              <120FE649-6EC3-3637-9E32-105B4A6BBC3D>  /System/Library/PrivateFrameworks/AggregateDictionary.framework/Support/aggregated
           0x1dfa7d000 -        0x1dfac2fff  libdispatch.dylib       <355ACCF4-3917-3730-BC55-EF7003887ABE>  /usr/lib/system/libdispatch.dylib
           0x1dfd80000 -        0x1e01d5fff  CoreFoundation          <5198FB57-5645-3B34-A49F-F32B52256CF3>  /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
           0x1eaeff000 -        0x1eaf7efff  libsystem_c.dylib       <9BD1E199-40A3-3E4A-8A78-271281C0CF0D>  /usr/lib/system/libsystem_c.dylib
           0x1fec9c000 -        0x1fee34fff  libsqlite3.dylib        <3AB8BB52-9CB7-36DB-B2C7-26F16E3319D4>  /usr/lib/libsqlite3.dylib
           0x20404d000 -        0x204188fff  PowerlogCore            <353C9C93-2828-3DE0-878F-0C7EA0312B5D>  /System/Library/PrivateFrameworks/PowerlogCore.framework/PowerlogCore
           0x2179a7000 -        0x2179dcfff  libsystem_kernel.dylib  <1DB00C91-6AD8-3840-8503-0C6FBFFA8E0B>  /usr/lib/system/libsystem_kernel.dylib
           0x2516db000 -        0x2516e6fff  libsystem_pthread.dylib <1026E3A4-D3C0-3B0D-A552-F185D6772A29>  /usr/lib/system/libsystem_pthread.dylib
           0x2516f6000 -        0x251732fff  libxpc.dylib            <267DA60E-B413-307F-BF47-C71B78244A25>  /usr/lib/system/libxpc.dylib


Powerstats for:   mediaserverd
UUID:             9CD5A11F-B6B5-32E7-9BF8-202A77EBA87A
Path:             /usr/sbin/mediaserverd
Architecture:     arm64
Start time:       2022-07-21 03:05:02.511 +1000
End time:         2022-07-21 08:52:53.601 +1000
Num samples:      87 (13%)
Primary state:    65 samples Non-Frontmost App, Non-Suppressed, Kernel mode, Effective Thread QoS Utility, Requested Thread QoS Utility, Override Thread QoS Unspecified
User Activity:    83 samples Idle, 4 samples Active
Power Source:     21 samples on Battery, 66 samples on AC
  55  ??? (libsystem_pthread.dylib + 3676) [0x2516dbe5c]
    55  ??? (libsystem_pthread.dylib + 4284) [0x2516dc0bc]
      55  ??? (libdispatch.dylib + 91392) [0x1dfa93500]
        55  ??? (libdispatch.dylib + 48256) [0x1dfa88c80]
          49  ??? (libdispatch.dylib + 45348) [0x1dfa88124]
            49  ??? (libdispatch.dylib + 14896) [0x1dfa80a30]
              35  ??? (CoreMedia + 132600) [0x1ea9565f8]
                35  ??? (CoreMedia + 131796) [0x1ea9562d4]
                  35  ??? (CoreMedia + 131928) [0x1ea956358]
                    35  ??? (MediaToolbox + 2584420) [0x1ea384f64]
                      35  ??? (MediaToolbox + 2635596) [0x1ea39174c]
                        35  ??? (CoreMedia + 232252) [0x1ea96eb3c]
                          35  ??? (CoreMedia + 43880) [0x1ea940b68]
                            35  ??? (CoreMedia + 350100) [0x1ea98b794]
                              35  ??? (libsystem_kernel.dylib + 13640) [0x2179aa548]
              14  ??? (MediaToolbox + 6604060) [0x1ea75a51c]
                14  ??? (MediaToolbox + 3120864) [0x1ea407ee0]
                  14  ??? (MediaToolbox + 3124184) [0x1ea408bd8]
                    14  ??? (CoreMedia + 231780) [0x1ea96e964]
                      14  ??? (CoreMedia + 43880) [0x1ea940b68]
                        14  ??? (CoreMedia + 350100) [0x1ea98b794]
                          14  ??? (libsystem_kernel.dylib + 13640) [0x2179aa548]
                            14  <Effective Thread QoS Default, Requested Thread QoS Default>
          6   ??? (libdispatch.dylib + 45572) [0x1dfa88204]
            6   ??? (libdispatch.dylib + 14896) [0x1dfa80a30]
              6   ??? (MediaToolbox + 5323184) [0x1ea6219b0]
                6   ??? (MediaToolbox + 2555716) [0x1ea37df44]
                  6   ??? (MediaToolbox + 209232) [0x1ea141150]
                    6   ??? (MediaToolbox + 210748) [0x1ea14173c]
                      6   ??? (MediaToolbox + 241576) [0x1ea148fa8]
                        6   ??? (MediaToolbox + 237704) [0x1ea148088]
                          6   ??? (libsystem_kernel.dylib + 13640) [0x2179aa548]
                            6   <Effective Thread QoS Default, Requested Thread QoS Default>
  32  ??? (libsystem_pthread.dylib + 3688) [0x2516dbe68]
    32  ??? (libsystem_pthread.dylib + 6572) [0x2516dc9ac]
      30  ??? (CoreMedia + 394384) [0x1ea996490]
        30  ??? (MediaToolbox + 375944) [0x1ea169c88]
          30  ??? (MediaToolbox + 379268) [0x1ea16a984]
            30  ??? (MediaToolbox + 2934296) [0x1ea3da618]
              30  ??? (MediaToolbox + 380420) [0x1ea16ae04]
                30  ??? (MediaToolbox + 534632) [0x1ea190868]
                  30  ??? (MediaToolbox + 5190056) [0x1ea6011a8]
                    30  ??? (MediaToolbox + 5192672) [0x1ea601be0]
                      30  ??? (CoreMedia + 232252) [0x1ea96eb3c]
                        30  ??? (CoreMedia + 43880) [0x1ea940b68]
                          30  ??? (CoreMedia + 350100) [0x1ea98b794]
                            30  ??? (libsystem_kernel.dylib + 13640) [0x2179aa548]
      2   ??? (libdispatch.dylib + 85748) [0x1dfa91ef4]
        2   ??? (libdispatch.dylib + 86372) [0x1dfa92164]
          2   ??? (libdispatch.dylib + 48308) [0x1dfa88cb4]
            2   ??? (libdispatch.dylib + 45348) [0x1dfa88124]
              2   ??? (libdispatch.dylib + 14896) [0x1dfa80a30]
                2   ??? (libdispatch.dylib + 75824) [0x1dfa8f830]
                  2   ??? (Foundation + 388624) [0x1e15d2e10]
                    2   ??? (Foundation + 330856) [0x1e15c4c68]
                      2   ??? (Foundation + 316892) [0x1e15c15dc]
                        2   ??? (Foundation + 246292) [0x1e15b0214]
                          2   ??? (Foundation + 409492) [0x1e15d7f94]
                            2   ??? (Foundation + 334876) [0x1e15c5c1c]
                              2   ??? (CFNetwork + 556900) [0x1e0626f64]
                                2   ??? (MediaToolbox + 3833236) [0x1ea4b5d94]
                                  2   ??? (MediaToolbox + 3839848) [0x1ea4b7768]
                                    2   ??? (MediaToolbox + 3832216) [0x1ea4b5998]
                                      2   ??? (MediaToolbox + 222532) [0x1ea144544]
                                        2   ??? (MediaToolbox + 227484) [0x1ea14589c]
                                          2   ??? (MediaToolbox + 235936) [0x1ea1479a0]
                                            2   ??? (MediaToolbox + 241576) [0x1ea148fa8]
                                              2   ??? (MediaToolbox + 237704) [0x1ea148088]
                                                2   ??? (libsystem_kernel.dylib + 13640) [0x2179aa548]
                                                  2   <Effective Thread QoS Unspecified, Requested Thread QoS Unspecified>

  Binary Images:
           0x102244000 -                ???  mediaserverd            <9CD5A11F-B6B5-32E7-9BF8-202A77EBA87A>  /usr/sbin/mediaserverd
           0x1dfa7d000 -        0x1dfac2fff  libdispatch.dylib       <355ACCF4-3917-3730-BC55-EF7003887ABE>  /usr/lib/system/libdispatch.dylib
           0x1e059f000 -        0x1e0a60fff  CFNetwork               <7072273C-58D2-3DC2-9E98-A6ED768544D8>  /System/Library/Frameworks/CFNetwork.framework/CFNetwork
           0x1e1574000 -        0x1e187efff  Foundation              <AC6AD2F3-C7B1-38AA-8588-57036A663180>  /System/Library/Frameworks/Foundation.framework/Foundation
           0x1ea10e000 -        0x1ea935fff  MediaToolbox            <28B942C5-5048-3031-9F28-AE8D02196091>  /System/Library/Frameworks/MediaToolbox.framework/MediaToolbox
           0x1ea936000 -        0x1eaa56fff  CoreMedia               <7A16874C-AFE1-399B-A195-167F832C5925>  /System/Library/Frameworks/CoreMedia.framework/CoreMedia
           0x2179a7000 -        0x2179dcfff  libsystem_kernel.dylib  <1DB00C91-6AD8-3840-8503-0C6FBFFA8E0B>  /usr/lib/system/libsystem_kernel.dylib
           0x2516db000 -        0x2516e6fff  libsystem_pthread.dylib <1026E3A4-D3C0-3B0D-A552-F185D6772A29>  /usr/lib/system/libsystem_pthread.dylib


Powerstats for:   com.apple.StreamingUnzipService
UUID:             3BF66FB1-38B7-373D-997A-B7B02A39F1C1
Path:             /System/Library/PrivateFrameworks/StreamingZip.framework/XPCServices/com.apple.StreamingUnzipService.xpc/com.apple.StreamingUnzipService
Identifier:       com.apple.StreamingUnzipService
Version:          1.0 (1)
Architecture:     arm64
Start time:       2022-07-21 03:57:32.384 +1000
End time:         2022-07-21 04:34:42.674 +1000
Num samples:      52 (8%)
Primary state:    38 samples Non-Frontmost App, Non-Suppressed, Kernel mode, Effective Thread QoS User Initiated, Requested Thread QoS User Initiated, Override Thread QoS Unspecified
User Activity:    14 samples Idle, 38 samples Active
Power Source:     38 samples on Battery, 14 samples on AC
  52  ??? (libsystem_pthread.dylib + 3676) [0x2516dbe5c]
    52  ??? (libsystem_pthread.dylib + 4284) [0x2516dc0bc]
      52  ??? (libdispatch.dylib + 91392) [0x1dfa93500]
        52  ??? (libdispatch.dylib + 48308) [0x1dfa88cb4]
          52  ??? (libdispatch.dylib + 45056) [0x1dfa88000]
            52  ??? (libdispatch.dylib + 133196) [0x1dfa9d84c]
              52  ??? (libdispatch.dylib + 45056) [0x1dfa88000]
                52  ??? (libdispatch.dylib + 129836) [0x1dfa9cb2c]
                  52  ??? (libdispatch.dylib + 15088) [0x1dfa80af0]
                    52  ??? (libxpc.dylib + 64616) [0x251705c68]
                      52  ??? (libxpc.dylib + 63544) [0x251705838]
                        52  ??? (Foundation + 128692) [0x1e15936b4]
                          52  ??? (Foundation + 193084) [0x1e15a323c]
                            52  ??? (Foundation + 271996) [0x1e15b667c]
                              52  ??? (com.apple.StreamingUnzipService + 114836) [0x100388094]
                                52  ??? (Foundation + 234400) [0x1e15ad3a0]
                                  52  ??? (com.apple.StreamingUnzipService + 115420) [0x1003882dc]
                                    51  ??? (libsystem_kernel.dylib + 11956) [0x2179a9eb4]
                                      13  <Effective Thread QoS Default, Requested Thread QoS Default>
                                      1   <Effective Thread QoS Utility, Requested Thread QoS Utility>
                                    1   ??? (com.apple.StreamingUnzipService + 93456) [0x100382d10]
                                      1   ??? (com.apple.StreamingUnzipService + 61232) [0x10037af30]
                                        1   ??? (libsystem_kernel.dylib + 11564) [0x2179a9d2c]

  Binary Images:
           0x10036c000 -                ???  com.apple.StreamingUnzipService 1.0 (1) <3BF66FB1-38B7-373D-997A-B7B02A39F1C1>  /System/Library/PrivateFrameworks/StreamingZip.framework/XPCServices/com.apple.StreamingUnzipService.xpc/com.apple.StreamingUnzipService
           0x1dfa7d000 -        0x1dfac2fff  libdispatch.dylib                       <355ACCF4-3917-3730-BC55-EF7003887ABE>  /usr/lib/system/libdispatch.dylib
           0x1e1574000 -        0x1e187efff  Foundation                              <AC6AD2F3-C7B1-38AA-8588-57036A663180>  /System/Library/Frameworks/Foundation.framework/Foundation
           0x2179a7000 -        0x2179dcfff  libsystem_kernel.dylib                  <1DB00C91-6AD8-3840-8503-0C6FBFFA8E0B>  /usr/lib/system/libsystem_kernel.dylib
           0x2516db000 -        0x2516e6fff  libsystem_pthread.dylib                 <1026E3A4-D3C0-3B0D-A552-F185D6772A29>  /usr/lib/system/libsystem_pthread.dylib
           0x2516f6000 -        0x251732fff  libxpc.dylib                            <267DA60E-B413-307F-BF47-C71B78244A25>  /usr/lib/system/libxpc.dylib


Powerstats for:   Music
UUID:             6F3D0F8A-8EEF-3D36-8293-EA330A7D117C
Path:             /private/var/containers/Bundle/Application/4A553F2E-E936-4860-B77F-DFBF3345E35A/Music.app/Music
Architecture:     arm64
Start time:       2022-07-21 02:46:32.473 +1000
End time:         2022-07-21 09:00:26.285 +1000
Num samples:      45 (7%)
Primary state:    15 samples Non-Frontmost App, Non-Suppressed, Kernel mode, Effective Thread QoS Default, Requested Thread QoS User Initiated, Override Thread QoS Unspecified
User Activity:    22 samples Idle, 23 samples Active
Power Source:     44 samples on Battery, 1 samples on AC
  44  ??? (libsystem_pthread.dylib + 3676) [0x2516dbe5c]
    34  ??? (libsystem_pthread.dylib + 4284) [0x2516dc0bc]
      34  ??? (libdispatch.dylib + 91392) [0x1dfa93500]
        26  ??? (libdispatch.dylib + 48308) [0x1dfa88cb4]
          26  ??? (libdispatch.dylib + 45348) [0x1dfa88124]
            26  ??? (libdispatch.dylib + 14896) [0x1dfa80a30]
              14  ??? (libdispatch.dylib + 7788) [0x1dfa7ee6c]
                8   ??? (MediaPlaybackCore + 1855252) [0x20bb83f14]
                  8   ??? (MediaPlaybackCore + 1648916) [0x20bb51914]
                    5   ??? (MediaServices + 65092) [0x1f87bae44]
                      4   ??? (MediaPlaybackCore + 1644116) [0x20bb50654]
                        4   ??? (MediaServices + 68640) [0x1f87bbc20]
                          4   ??? (CoreFoundation + 360908) [0x1dfdd81cc]
                            4   ??? (CoreFoundation + 262584) [0x1dfdc01b8]
                              4   ??? (MediaServices + 69188) [0x1f87bbe44]
                                4   ??? (Foundation + 251592) [0x1e15b16c8]
                                  4   ??? (Foundation + 234400) [0x1e15ad3a0]
                                    4   ??? (Foundation + 266932) [0x1e15b52b4]
                                      4   ??? (libsystem_kernel.dylib + 11956) [0x2179a9eb4]
                      1   ??? (MediaPlaybackCore + 1644544) [0x20bb50800]
                        1   ??? (Foundation + 251592) [0x1e15b16c8]
                          1   ??? (Foundation + 234400) [0x1e15ad3a0]
                            1   ??? (Foundation + 266932) [0x1e15b52b4]
                              1   ??? (libsystem_kernel.dylib + 11956) [0x2179a9eb4]
                                1   <Frontmost App, Effective Thread QoS User Initiated>
                    3   ??? (MediaServices + 65324) [0x1f87baf2c]
                      3   ??? (Foundation + 251592) [0x1e15b16c8]
                        3   ??? (Foundation + 234400) [0x1e15ad3a0]
                          3   ??? (Foundation + 266932) [0x1e15b52b4]
                            3   ??? (libsystem_kernel.dylib + 11956) [0x2179a9eb4]
                5   ??? (MediaPlaybackCore + 1856532) [0x20bb84414]
                  5   ??? (MediaPlaybackCore + 1851368) [0x20bb82fe8]
                    5   ??? (Foundation + 774188) [0x1e163102c]
                      5   ??? (Foundation + 251592) [0x1e15b16c8]
                        5   ??? (Foundation + 234400) [0x1e15ad3a0]
                          5   ??? (Foundation + 266932) [0x1e15b52b4]
                            5   ??? (libsystem_kernel.dylib + 11956) [0x2179a9eb4]
                1   ??? (MediaPlayer + 309068) [0x1e8f9774c]
                  1   ??? (MediaPlayer + 381644) [0x1e8fa92cc]
                    1   ??? (Foundation + 301804) [0x1e15bdaec]
                      1   ??? (Foundation + 316892) [0x1e15c15dc]
                        1   ??? (Foundation + 246292) [0x1e15b0214]
                          1   ??? (Foundation + 647192) [0x1e1612018]
                            1   ??? (libremovefile.dylib + 6692) [0x251655a24]
                              1   ??? (libremovefile.dylib + 5864) [0x2516556e8]
                                1   ??? (libsystem_kernel.dylib + 21476) [0x2179ac3e4]
                                  1   <Frontmost App, Effective Thread QoS User Initiated>
              12  ??? (libdispatch.dylib + 75824) [0x1dfa8f830]
                7   ??? (CFNetwork + 909640) [0x1e067d148]
                  5   ??? (libsystem_kernel.dylib + 11956) [0x2179a9eb4]
                    4   <Frontmost App, Effective Thread QoS Utility, Requested Thread QoS Utility>
                    1   <Effective Thread QoS Utility, Requested Thread QoS Utility>
                  1   ??? (CFNetwork + 2687468) [0x1e082f1ec]
                    1   ??? (libsystem_kernel.dylib + 19188) [0x2179abaf4]
                      1   <Frontmost App, Effective Thread QoS Utility, Requested Thread QoS Utility>
                  1   ??? (CFNetwork + 2687104) [0x1e082f080]
                    1   ??? (libsystem_kernel.dylib + 11564) [0x2179a9d2c]
                      1   <Frontmost App, Effective Thread QoS Utility, Requested Thread QoS Utility>
                4   ??? (CFNetwork + 911888) [0x1e067da10]
                  4   ??? (CFNetwork + 300556) [0x1e05e860c]
                    4   ??? (libsqlite3.dylib + 40196) [0x1feca5d04]
                      4   ??? (libsqlite3.dylib + 279112) [0x1fece0248]
                        4   ??? (libsqlite3.dylib + 338988) [0x1feceec2c]
                          4   ??? (libsqlite3.dylib + 149920) [0x1fecc09a0]
                            4   ??? (libsqlite3.dylib + 364512) [0x1fecf4fe0]
                              4   ??? (libsqlite3.dylib + 447216) [0x1fed092f0]
                                4   ??? (libsqlite3.dylib + 784408) [0x1fed5b818]
                                  4   ??? (libsqlite3.dylib + 449148) [0x1fed09a7c]
                                    4   ??? (libsystem_kernel.dylib + 12732) [0x2179aa1bc]
                                      3   <Frontmost App, Effective Thread QoS Utility, Requested Thread QoS Utility>
                                      1   <Effective Thread QoS Utility, Requested Thread QoS Utility>
                1   ??? (CFNetwork + 911152) [0x1e067d730]
                  1   ??? (libsystem_kernel.dylib + 11956) [0x2179a9eb4]
                    1   <Effective Thread QoS Utility, Requested Thread QoS Utility>
        8   ??? (libdispatch.dylib + 48256) [0x1dfa88c80]
          8   ??? (libdispatch.dylib + 45348) [0x1dfa88124]
            8   ??? (libdispatch.dylib + 14896) [0x1dfa80a30]
              8   ??? (libdispatch.dylib + 7788) [0x1dfa7ee6c]
                5   ??? (MediaPlayer + 1391240) [0x1e909fa88]
                  5   ??? (MediaPlayer + 2582036) [0x1e91c2614]
                    4   ??? (libdispatch.dylib + 76612) [0x1dfa8fb44]
                      4   ??? (libdispatch.dylib + 78008) [0x1dfa900b8]
                        4   ??? (libdispatch.dylib + 14896) [0x1dfa80a30]
                          4   ??? (MediaPlayer + 2582560) [0x1e91c2820]
                            4   ??? (MediaPlayer + 2571228) [0x1e91bfbdc]
                              4   ??? (MediaServices + 200984) [0x1f87dc118]
                                4   ??? (MediaServices + 199192) [0x1f87dba18]
                                  4   ??? (MediaServices + 25756) [0x1f87b149c]
                                    2   ??? (libsqlite3.dylib + 280164) [0x1fece0664]
                                      2   ??? (libsqlite3.dylib + 450148) [0x1fed09e64]
                                        2   ??? (libsqlite3.dylib + 668344) [0x1fed3f2b8]
                                          2   ??? (libsqlite3.dylib + 668780) [0x1fed3f46c]
                                            2   ??? (libsqlite3.dylib + 535260) [0x1fed1eadc]
                                              2   ??? (libsqlite3.dylib + 449148) [0x1fed09a7c]
                                                2   ??? (libsystem_kernel.dylib + 12732) [0x2179aa1bc]
                                                  2   <Frontmost App, Effective Thread QoS User Initiated>
                                    2   ??? (libsqlite3.dylib + 279112) [0x1fece0248]
                                      2   ??? (libsqlite3.dylib + 338988) [0x1feceec2c]
                                        2   ??? (libsqlite3.dylib + 149920) [0x1fecc09a0]
                                          2   ??? (libsqlite3.dylib + 364512) [0x1fecf4fe0]
                                            2   ??? (libsqlite3.dylib + 447216) [0x1fed092f0]
                                              2   ??? (libsqlite3.dylib + 784408) [0x1fed5b818]
                                                2   ??? (libsqlite3.dylib + 449148) [0x1fed09a7c]
                                                  2   ??? (libsystem_kernel.dylib + 12732) [0x2179aa1bc]
                                                    2   <Frontmost App, Effective Thread QoS User Initiated>
                    1   ??? (libdispatch.dylib + 76944) [0x1dfa8fc90]
                      1   ??? (libdispatch.dylib + 14896) [0x1dfa80a30]
                        1   ??? (MediaPlayer + 2582560) [0x1e91c2820]
                          1   ??? (MediaPlayer + 2571228) [0x1e91bfbdc]
                            1   ??? (MediaServices + 200984) [0x1f87dc118]
                              1   ??? (MediaServices + 199192) [0x1f87dba18]
                                1   ??? (MediaServices + 25756) [0x1f87b149c]
                                  1   ??? (libsqlite3.dylib + 279112) [0x1fece0248]
                                    1   ??? (libsqlite3.dylib + 338988) [0x1feceec2c]
                                      1   ??? (libsqlite3.dylib + 149920) [0x1fecc09a0]
                                        1   ??? (libsqlite3.dylib + 364512) [0x1fecf4fe0]
                                          1   ??? (libsqlite3.dylib + 447216) [0x1fed092f0]
                                            1   ??? (libsqlite3.dylib + 784408) [0x1fed5b818]
                                              1   ??? (libsqlite3.dylib + 449148) [0x1fed09a7c]
                                                1   ??? (libsystem_kernel.dylib + 12732) [0x2179aa1bc]
                                                  1   <Frontmost App, Effective Thread QoS User Initiated>
                3   ??? (MediaPlaybackCore + 139960) [0x20b9e12b8]
                  3   ??? (MediaServices + 25756) [0x1f87b149c]
                    2   ??? (libsqlite3.dylib + 279112) [0x1fece0248]
                      2   ??? (libsqlite3.dylib + 338920) [0x1feceebe8]
                        2   ??? (libsqlite3.dylib + 149920) [0x1fecc09a0]
                          2   ??? (libsqlite3.dylib + 364512) [0x1fecf4fe0]
                            2   ??? (libsqlite3.dylib + 447216) [0x1fed092f0]
                              2   ??? (libsqlite3.dylib + 784408) [0x1fed5b818]
                                2   ??? (libsqlite3.dylib + 449148) [0x1fed09a7c]
                                  2   ??? (libsystem_kernel.dylib + 12732) [0x2179aa1bc]
                                    1   <Frontmost App, Effective Thread QoS User Initiated>
                    1   ??? (libsqlite3.dylib + 280164) [0x1fece0664]
                      1   ??? (libsqlite3.dylib + 450148) [0x1fed09e64]
                        1   ??? (libsqlite3.dylib + 668344) [0x1fed3f2b8]
                          1   ??? (libsqlite3.dylib + 668780) [0x1fed3f46c]
                            1   ??? (libsqlite3.dylib + 535260) [0x1fed1eadc]
                              1   ??? (libsqlite3.dylib + 449148) [0x1fed09a7c]
                                1   ??? (libsystem_kernel.dylib + 12732) [0x2179aa1bc]
    10  ??? (libsystem_pthread.dylib + 4224) [0x2516dc080]
      10  ??? (libdispatch.dylib + 88428) [0x1dfa9296c]
        10  ??? (libdispatch.dylib + 86372) [0x1dfa92164]
          7   ??? (libswift_Concurrency.dylib + 246248) [0x261a881e8]
            7   ??? (libswift_Concurrency.dylib + 243660) [0x261a877cc]
              4   ??? (<213E3EB4-BFF0-3B7E-8458-6F91200130D0> + 6984284) [0x106b3125c]
                4   ??? (<213E3EB4-BFF0-3B7E-8458-6F91200130D0> + 2783984) [0x10672faf0]
                  4   ??? (<213E3EB4-BFF0-3B7E-8458-6F91200130D0> + 2796292) [0x106732b04]
                    4   ??? (libswiftFoundation.dylib + 146804) [0x1e44f9d74]
                      4   ??? (libswiftFoundation.dylib + 1138060) [0x1e45ebd8c]
                        4   ??? (libswiftFoundation.dylib + 1103660) [0x1e45e372c]
                          4   ??? (libswiftFoundation.dylib + 1151016) [0x1e45ef028]
                            4   ??? (Foundation + 251592) [0x1e15b16c8]
                              4   ??? (Foundation + 234400) [0x1e15ad3a0]
                                4   ??? (Foundation + 266932) [0x1e15b52b4]
                                  4   ??? (libsystem_kernel.dylib + 11956) [0x2179a9eb4]
                                    4   <Requested Thread QoS Default>
              3   ??? (<213E3EB4-BFF0-3B7E-8458-6F91200130D0> + 6983752) [0x106b31048]
                3   ??? (<213E3EB4-BFF0-3B7E-8458-6F91200130D0> + 2783364) [0x10672f884]
                  3   ??? (<213E3EB4-BFF0-3B7E-8458-6F91200130D0> + 2794424) [0x1067323b8]
                    3   ??? (libswiftFoundation.dylib + 146804) [0x1e44f9d74]
                      3   ??? (libswiftFoundation.dylib + 1138060) [0x1e45ebd8c]
                        3   ??? (libswiftFoundation.dylib + 1103660) [0x1e45e372c]
                          3   ??? (libswiftFoundation.dylib + 1151016) [0x1e45ef028]
                            3   ??? (Foundation + 251592) [0x1e15b16c8]
                              3   ??? (Foundation + 234400) [0x1e15ad3a0]
                                3   ??? (Foundation + 266932) [0x1e15b52b4]
                                  3   ??? (libsystem_kernel.dylib + 11956) [0x2179a9eb4]
                                    3   <Requested Thread QoS Default>
          3   ??? (libdispatch.dylib + 25944) [0x1dfa83558]
            3   ??? (libdispatch.dylib + 28396) [0x1dfa83eec]
              3   ??? (libdispatch.dylib + 14896) [0x1dfa80a30]
                3   ??? (libdispatch.dylib + 7788) [0x1dfa7ee6c]
                  2   ??? (iTunesCloud + 83212) [0x1f77e750c]
                    1   ??? (MediaPlayer + 2785504) [0x1e91f40e0]
                      1   ??? (MediaPlayer + 2692904) [0x1e91dd728]
                        1   ??? (MediaPlayer + 2786400) [0x1e91f4460]
                          1   ??? (MediaPlayer + 2787468) [0x1e91f488c]
                            1   ??? (<213E3EB4-BFF0-3B7E-8458-6F91200130D0> + 2807380) [0x106735654]
                              1   ??? (<213E3EB4-BFF0-3B7E-8458-6F91200130D0> + 2807252) [0x1067355d4]
                                1   ??? (<213E3EB4-BFF0-3B7E-8458-6F91200130D0> + 2820464) [0x106738970]
                                  1   ??? (<213E3EB4-BFF0-3B7E-8458-6F91200130D0> + 2784808) [0x10672fe28]
                                    1   ??? (<213E3EB4-BFF0-3B7E-8458-6F91200130D0> + 2798200) [0x106733278]
                                      1   ??? (libswiftFoundation.dylib + 146804) [0x1e44f9d74]
                                        1   ??? (libswiftFoundation.dylib + 1138060) [0x1e45ebd8c]
                                          1   ??? (libswiftFoundation.dylib + 1103660) [0x1e45e372c]
                                            1   ??? (libswiftFoundation.dylib + 1151016) [0x1e45ef028]
                                              1   ??? (Foundation + 251592) [0x1e15b16c8]
                                                1   ??? (Foundation + 234400) [0x1e15ad3a0]
                                                  1   ??? (Foundation + 266932) [0x1e15b52b4]
                                                    1   ??? (libsystem_kernel.dylib + 11956) [0x2179a9eb4]
                                                      1   <Frontmost App, Effective Thread QoS User Interactive, Requested Thread QoS User Interactive>
                    1   ??? (<213E3EB4-BFF0-3B7E-8458-6F91200130D0> + 8767272) [0x106ce4728]
                      1   ??? (<213E3EB4-BFF0-3B7E-8458-6F91200130D0> + 9519460) [0x106d9c164]
                        1   ??? (<213E3EB4-BFF0-3B7E-8458-6F91200130D0> + 9569424) [0x106da8490]
                          1   ??? (MediaPlayer + 2582036) [0x1e91c2614]
                            1   ??? (libdispatch.dylib + 76612) [0x1dfa8fb44]
                              1   ??? (libdispatch.dylib + 78008) [0x1dfa900b8]
                                1   ??? (libdispatch.dylib + 14896) [0x1dfa80a30]
                                  1   ??? (MediaPlayer + 2582560) [0x1e91c2820]
                                    1   ??? (MediaPlayer + 2571228) [0x1e91bfbdc]
                                      1   ??? (MediaServices + 200984) [0x1f87dc118]
                                        1   ??? (MediaServices + 199192) [0x1f87dba18]
                                          1   ??? (MediaServices + 25756) [0x1f87b149c]
                                            1   ??? (libsqlite3.dylib + 279112) [0x1fece0248]
                                              1   ??? (libsqlite3.dylib + 338988) [0x1feceec2c]
                                                1   ??? (libsqlite3.dylib + 149920) [0x1fecc09a0]
                                                  1   ??? (libsqlite3.dylib + 364512) [0x1fecf4fe0]
                                                    1   ??? (libsqlite3.dylib + 447216) [0x1fed092f0]
                                                      1   ??? (libsqlite3.dylib + 785752) [0x1fed5bd58]
                                                        1   ??? (libsystem_kernel.dylib + 18140) [0x2179ab6dc]
                                                          1   <Frontmost App, Effective Thread QoS User Interactive, Requested Thread QoS User Interactive>
                  1   ??? (iTunesCloud + 2007136) [0x1f79bd060]
                    1   ??? (MediaPlaybackCore + 936564) [0x20baa3a74]
                      1   ??? (MediaPlaybackCore + 925708) [0x20baa100c]
                        1   ??? (MediaPlayer + 2544020) [0x1e91b9194]
                          1   ??? (libdispatch.dylib + 76944) [0x1dfa8fc90]
                            1   ??? (libdispatch.dylib + 14896) [0x1dfa80a30]
                              1   ??? (MediaPlayer + 2544224) [0x1e91b9260]
                                1   ??? (MediaPlayer + 2571228) [0x1e91bfbdc]
                                  1   ??? (MediaServices + 200984) [0x1f87dc118]
                                    1   ??? (MediaServices + 199192) [0x1f87dba18]
                                      1   ??? (MediaServices + 25756) [0x1f87b149c]
                                        1   ??? (libsqlite3.dylib + 280164) [0x1fece0664]
                                          1   ??? (libsqlite3.dylib + 450148) [0x1fed09e64]
                                            1   ??? (libsqlite3.dylib + 668344) [0x1fed3f2b8]
                                              1   ??? (libsqlite3.dylib + 668780) [0x1fed3f46c]
                                                1   ??? (libsqlite3.dylib + 535260) [0x1fed1eadc]
                                                  1   ??? (libsqlite3.dylib + 449148) [0x1fed09a7c]
                                                    1   ??? (libsystem_kernel.dylib + 12732) [0x2179aa1bc]
  1   ??? (libsystem_pthread.dylib + 3688) [0x2516dbe68]
    1   ??? (libsystem_pthread.dylib + 6572) [0x2516dc9ac]
      1   ??? (Foundation + 431164) [0x1e15dd43c]
        1   ??? (<213E3EB4-BFF0-3B7E-8458-6F91200130D0> + 11180020) [0x106f317f4]
          1   ??? (<213E3EB4-BFF0-3B7E-8458-6F91200130D0> + 11179548) [0x106f3161c]
            1   ??? (CoreFoundation + 654760) [0x1dfe1fda8]
              1   ??? (CoreFoundation + 125896) [0x1dfd9ebc8]
                1   ??? (CoreFoundation + 45148) [0x1dfd8b05c]
                  1   ??? (CoreFoundation + 22164) [0x1dfd85694]
                    1   ??? (CoreFoundation + 836000) [0x1dfe4c1a0]
                      1   ??? (CoreFoundation + 766996) [0x1dfe3b414]
                        1   ??? (<213E3EB4-BFF0-3B7E-8458-6F91200130D0> + 11179956) [0x106f317b4]
                          1   ??? (<213E3EB4-BFF0-3B7E-8458-6F91200130D0> + 11178568) [0x106f31248]
                            1   ??? (libswiftObjectiveC.dylib + 6672) [0x20ea54a10]
                              1   ??? (<213E3EB4-BFF0-3B7E-8458-6F91200130D0> + 11183396) [0x106f32524]
                                1   ??? (<213E3EB4-BFF0-3B7E-8458-6F91200130D0> + 11183356) [0x106f324fc]
                                  1   ??? (<213E3EB4-BFF0-3B7E-8458-6F91200130D0> + 11183316) [0x106f324d4]
                                    1   ??? (<213E3EB4-BFF0-3B7E-8458-6F91200130D0> + 1079832) [0x10658fa18]
                                      1   ??? (<213E3EB4-BFF0-3B7E-8458-6F91200130D0> + 10877420) [0x106ee79ec]
                                        1   ??? (<213E3EB4-BFF0-3B7E-8458-6F91200130D0> + 10878432) [0x106ee7de0]
                                          1   ??? (<213E3EB4-BFF0-3B7E-8458-6F91200130D0> + 10881152) [0x106ee8880]
                                            1   ??? (JavaScriptCore + 4400320) [0x1eb4094c0]
                                              1   ??? (JavaScriptCore + 4403524) [0x1eb40a144]
                                                1   ??? (JavaScriptCore + 15291764) [0x1ebe6c574]
                                                  1   ??? (JavaScriptCore + 15073676) [0x1ebe3718c]
                                                    1   ??? (JavaScriptCore + 15044100) [0x1ebe2fe04]
                                                      1   ??? (libsystem_kernel.dylib + 11956) [0x2179a9eb4]
                                                        1   <Frontmost App, Effective Thread QoS User Initiated>

  Binary Images:
           0x104f78000 -                ???  Music                      <6F3D0F8A-8EEF-3D36-8293-EA330A7D117C>  /private/var/containers/Bundle/Application/4A553F2E-E936-4860-B77F-DFBF3345E35A/Music.app/Music
           0x106488000 -                ???  ???                        <213E3EB4-BFF0-3B7E-8458-6F91200130D0>
           0x1dfa7d000 -        0x1dfac2fff  libdispatch.dylib          <355ACCF4-3917-3730-BC55-EF7003887ABE>  /usr/lib/system/libdispatch.dylib
           0x1dfd80000 -        0x1e01d5fff  CoreFoundation             <5198FB57-5645-3B34-A49F-F32B52256CF3>  /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
           0x1e059f000 -        0x1e0a60fff  CFNetwork                  <7072273C-58D2-3DC2-9E98-A6ED768544D8>  /System/Library/Frameworks/CFNetwork.framework/CFNetwork
           0x1e1574000 -        0x1e187efff  Foundation                 <AC6AD2F3-C7B1-38AA-8588-57036A663180>  /System/Library/Frameworks/Foundation.framework/Foundation
           0x1e44d6000 -        0x1e4848fff  libswiftFoundation.dylib   <64D4CA49-54AE-3767-9305-B1E7C6AF4B24>  /usr/lib/swift/libswiftFoundation.dylib
           0x1e8f4c000 -        0x1e93a3fff  MediaPlayer                <24B8A5D8-81B2-3632-A794-9B443FB78F99>  /System/Library/Frameworks/MediaPlayer.framework/MediaPlayer
           0x1eafd7000 -        0x1ec456fff  JavaScriptCore             <62EB08D2-3EC0-33A3-9789-1FC94458F203>  /System/Library/Frameworks/JavaScriptCore.framework/JavaScriptCore
           0x1f77d3000 -        0x1f7adafff  iTunesCloud                <ACAAC4DC-EFFA-39A0-94EC-6C652F736DA4>  /System/Library/PrivateFrameworks/iTunesCloud.framework/iTunesCloud
           0x1f87ab000 -        0x1f880bfff  MediaServices              <03E54A16-55BD-3B53-AC00-44B1E777EF9E>  /System/Library/PrivateFrameworks/MediaServices.framework/MediaServices
           0x1fec9c000 -        0x1fee34fff  libsqlite3.dylib           <3AB8BB52-9CB7-36DB-B2C7-26F16E3319D4>  /usr/lib/libsqlite3.dylib
           0x20b9bf000 -        0x20bc0afff  MediaPlaybackCore          <F07A64E9-6D97-3C1A-AA28-9873BE1C98D7>  /System/Library/PrivateFrameworks/MediaPlaybackCore.framework/MediaPlaybackCore
           0x20ea53000 -        0x20ea55fff  libswiftObjectiveC.dylib   <BC4A9AC6-E66F-3CA7-8131-69A713EDAA78>  /usr/lib/swift/libswiftObjectiveC.dylib
           0x2179a7000 -        0x2179dcfff  libsystem_kernel.dylib     <1DB00C91-6AD8-3840-8503-0C6FBFFA8E0B>  /usr/lib/system/libsystem_kernel.dylib
           0x251654000 -        0x251656fff  libremovefile.dylib        <C741EA0B-44AD-32DD-BABC-2955D9B316DD>  /usr/lib/system/libremovefile.dylib
           0x2516db000 -        0x2516e6fff  libsystem_pthread.dylib    <1026E3A4-D3C0-3B0D-A552-F185D6772A29>  /usr/lib/system/libsystem_pthread.dylib
           0x261a4c000 -        0x261a9cfff  libswift_Concurrency.dylib <BD6E56A6-5AE1-31F3-BD05-2AD834FFAB43>  /usr/lib/swift/libswift_Concurrency.dylib
