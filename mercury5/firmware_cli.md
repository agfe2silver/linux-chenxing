# Main menu

```
List of CLI commands:
 help                               -- Print help message
 ls                                 -- Print help message
 ?                                  -- Print help message
 quit                               -- Quit CLI
 cd                                 -- Change the working space
 memdump                            -- dump memory
 memset                             -- set memory
 memcpy                             -- memory copy
 regset                             -- set register value
 regget                             -- get register value
 net                                -- perform NETWORK commands
 wifi                               -- perform WIFI commands
 v4l                                -- v4l debugging
 rwgss                              -- Access Gsensor
 test                               -- Input OS test case num (999 for all)
 [cache]                            -- Menu Cache
 [icache]                           -- Menu ICache
 mfe                                -- Mfe Menu
 ait                                -- AIT Menu
 fs                                 -- FSTest Menu
 dumpdcf                            -- DCFDump Menu
 checkfps                           -- checkFPS Menu
 ispbypass                          -- IspBypass Menu
 dumpraw                            -- dumprawdata Menu
 adas                               -- ADAS Test
 dump_adas                          -- dump ADAS para 
 uartoff                            -- UART_TURNOFF
 comp                               -- Component Tese Entry
 Jpeg                               -- Component Tese Entry
 Aud                                -- Component Tese Entry
 jpd                                -- JPD Menu
 vdec                               -- VDEC Menu
 pb                                 -- PB Menu
 saradc                             -- Sar ADC
 key                                -- Sar ADC
 ucm                                -- UART Cmd test template
 repkey                             -- Repeat key command
 setrtc                             -- hint : setrtc 2017 01 01 01 01 01
 getrtc                             -- getrtc
 ChkBin                             -- CheckBinTest
 usb                                -- USBH 123-Menu gogogo
 3dnr                               -- 3D NR
 miu                                -- miu analysis
 alloc                              -- alloc analysis
 apk                                -- apical test
 cpu                                -- cpu analysis
 sreset                             -- sensor reset test
 memusage                           -- memusage on -t 5000
 mprot                              -- miu protect
 ps                                 -- process status
 uuid                               -- process uuid
 sine-wave                          -- mic input bypass
 sea                                -- Set emergency action type
 dvfs                               -- Dynamic change CPU freq
 pd                                 -- Power Down
 sw                                 -- Sensor register write
 sr                                 -- Sensor register read
 [dip]                              -- Menu DIP
 [dipctl]                           -- Menu DIPCTL
 [comput]                           -- Menu Comp
 [rtc]                              -- Menu RTC
 [spinand]                          -- Menu SPINAND
 usbh                               -- USBH 123-Menu gogogo
 [jpe]                              -- Menu JPE
 [io]                               -- Menu IO
 [scl]                              -- Menu SCL
 [gop]                              -- Menu Gop
 [pnl]                              -- Menu Pnl
 [MVOP]                             -- Menu MVOP
 [spi]                              -- Menu SPI
 [i2c]                              -- Menu I2C
 [rtc]                              -- Menu RTC
 [audio]                            -- Menu Audio
 [uart]                             -- Menu UART
 [isp]                              -- Menu ISP
 [sensorIF]                         -- Menu Sensor IF
 [vif]                              -- Menu Vif
 [pnl]                              -- Menu Pnl
 [decscl]                           -- Dec SCL
 [mipi]                             -- Menu DISP
 ```
## dip menu

```
List of CLI commands:
 move0                              -- move 420sp
 move1                              -- move 420t16x32
 move2                              -- move 422
 s0                                 -- 420sp scale
 s1                                 -- 420t16x32 scale
 s2                                 -- 422 scale
 r0                                 -- 420sp r 90
 r1                                 -- 420t16x32 r 90
 r2                                 -- 422 r 90
 clip                               -- img clip
 cc0                                -- cc_420sp_2_420tile16x32
 cc1                                -- cc_420tile16x32_2_420sp
 cc2                                -- cc_420sp_2_420tile32x16
 cc3                                -- cc_420tile32x16_2_420sp
 cc4                                -- cc_420sp_2_420tile32x32
 cc5                                -- cc_420tile32x32_2_420sp
 cc6                                -- cc_422_2_420sp
 cc7                                -- cc_422_2_420tile16x32
 cc8                                -- cc_420tile16x32_2_422
 cc9                                -- cc_420sp_2_422
 osdb0                              -- osdb 420sp
 rreg                               -- read reg
 wreg                               -- write reg
 test                               -- test
 ```
## gop menu

```
List of CLI commands:
 Gen                                -- General Function
 gop0                               -- OSD Draw GOP0 Test Function
 gop1                               -- OSD Draw GOP1 Test Function
 goputest                           -- OSD Draw GOP1 Test Function
 PrintGOPBanks                      -- OSD Draw GOP1 Test Function
 ```

## i2c menu

```
List of CLI commands:
 bus                                -- I2c I2C
 tst                                -- I2c I2C
```

## isp

```
List of CLI commands:
 run                                -- Initialize ISP
 stop                               -- Initialize ISP
 patgen                             -- Initialize ISP
 raw_wdma                           -- Initialize ISP
 raw_wdma2                          -- Initialize ISP
 ae_stats                           -- Initialize ISP
 awb_stats                          -- Initialize ISP
 dbg                                -- Initialize ISP
 prt                                -- Initialize ISP
 iq_ut                              -- Initialize ISP
 ae_ut                              -- Initialize ISP
 awb_ut                             -- Initialize ISP
 rotate                             -- Initialize ISP
 ints                               -- Initialize ISP
 dbgbuf                             -- Initialize ISP
 csi                                -- Initialize ISP
 histo_stats                        -- Initialize ISP
 mload                              -- Initialize ISP
 mload_R                            -- Initialize ISP
 hdr_stats                          -- Initialize ISP
```

## vif

```
List of CLI commands:
 VIF_INIT                           -- VIF test0
 FS_TASK_CREATE                     -- VIF test1
 FE_TASK_CREATE                     -- VIF test2
 FS_TASK_END                        -- VIF test3
 FE_TASK_END                        -- VIF test4
 VIF_INTS_EVENT                     -- VIF test5
 VIF_DEINIT                         -- VIF test6
 VIF_AUTO_TEST                      -- VIF test7
```

## pnl

```
List of CLI commands:
 LCDRW                              -- LCD bank Reg Read/Write
 RGBCFG                             -- RGB Panel setting
 PLCFG                              -- RGB Panel setting
 ShowBank                           -- RGB Panel setting
```

## decscl

```
List of CLI commands:
 REG                                -- Register R/W
 HVSP                               -- Hvsp
 VIP                                -- VIP
 SRAMDUMP                           -- VIP
```

## mipi menu

```
List of CLI commands:
 PrintCmd                           -- Print cmd set 
 BankRead                           -- Read bank info
 RB                                 -- Read bank info
 regw                               -- Write  MIPI Digital/CMDQ Reg used 
 regwb                              -- General Function
 ws                                 -- General Function
 wp                                 -- Write packet by user defined 
 read                               -- Read reg from panel control
 clkon                              -- Set MIPI clock on
 clkoff                             -- Set MIPI clock off
 mode                               -- Change Video mode (HS) or Cmd mode (LP)
 phy                                -- Update PHY setting 
``
