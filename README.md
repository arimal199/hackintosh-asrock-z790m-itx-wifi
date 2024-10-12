```
00:000 00:000 OCCPU: TSC Adjust 0
00:000 00:000 OCCPU: Queried Core Crystal Clock Frequency    38400000Hz
00:000 00:000 OCCPU: CPUFrequencyFromART  3417600000Hz  3417MHz = 38400000 * 178 / 2
00:000 00:000 OC: Starting OpenCore...
00:000 00:000 OC: Booter path - EFI\OC\OpenCore.efi
00:000 00:000 OCFS: Trying to locate filesystem on 61B9E618 62437F98
00:000 00:000 OCFS: Filesystem DP - EFI\OC\OpenCore.efi
00:000 00:000 OC: Absolute booter path - EFI\OC\OpenCore.efi
00:000 00:000 OC: Storage root EFI\OC\OpenCore.efi
00:000 00:000 OCST: Missing vault data, ignoring...
00:000 00:000 OC: OcMiscEarlyInit...
00:000 00:000 OC: Loaded configuration of 65508 bytes
00:000 00:000 OC: Got 6 drivers
00:000 00:000 OC: Watchdog status is 0
00:021 00:021 OC: OpenCore DBG-102-2024-10-08 is loading in Optional mode (0/0)...
00:027 00:006 OC: Boot timestamp - 2024.10.12 18:02:01
00:033 00:006 OCCPU: MP services threads 24 (enabled 24) - Success
00:040 00:006 OCCPU: MP services Pkg 1 Cores 40 Threads 2 - Success
00:046 00:006 OCCPU: Found 13th Gen Intel(R) Core(TM) i7-13700KF
00:053 00:007 OCCPU: Signature B0671 Stepping 1 Model B7 Family 6 Type 0 ExtModel B ExtFamily 0 uCode 12B CPUID MAX (20/80000008)
00:060 00:007 OCCPU: EIST CFG Lock 0
00:066 00:006 OCCPU: TSC Adjust 0
00:072 00:006 OCCPU: Queried Core Crystal Clock Frequency    38400000Hz
00:079 00:006 OCCPU: CPUFrequencyFromART  3417600000Hz  3417MHz = 38400000 * 178 / 2
00:089 00:009 OCCPU: Timer address is 0 from Unknown INTEL
00:098 00:009 OCCPU: Failed to get FSBFrequency data using Apple Platform Info - Not Found
00:108 00:009 OCCPU: Intel TSC:  3417600000Hz,  3417MHz; FSB:   100517647Hz,   100MHz; MaxBusRatio: 34
00:122 00:013 OCCPU: Detected Apple Processor Type: 07 -> 0709
00:132 00:009 OCCPU: CPUFrequencyFromTSC           0Hz     0MHz
00:141 00:009 OCCPU: CPUFrequency  3417600000Hz  3417MHz
00:151 00:009 OCCPU: FSBFrequency   100517647Hz   100MHz
00:161 00:009 OCCPU: Pkg 1 Cores 16 Threads 24
00:170 00:009 OC: OcLoadNvramSupport...
00:180 00:010 OCVAR: Locate emulated NVRAM protocol - Not Found
00:190 00:009 OC: Deleting NVRAM 4D1EDE05-38C7-4A6A-9CC6-4BCCA8B38C14:DefaultBackgroundColor - Not Found
00:204 00:013 OC: Not deleting NVRAM 4D1FDA02-38C7-4A6A-9CC6-4BCCA8B30102:rtc-blacklist, matches add
00:217 00:013 OC: Not deleting NVRAM 7C436110-AB2A-4BBB-A880-FE41995C9F82:boot-args, matches add
00:231 00:013 OC: Not deleting NVRAM 7C436110-AB2A-4BBB-A880-FE41995C9F82:ForceDisplayRotationInEFI, matches add
00:245 00:014 OCVAR: Setting NVRAM 4D1EDE05-38C7-4A6A-9CC6-4BCCA8B38C14:DefaultBackgroundColor - Success
00:259 00:013 OCVAR: Setting NVRAM 4D1FDA02-38C7-4A6A-9CC6-4BCCA8B30102:revcpu - ignored, exists
00:272 00:013 OCVAR: Setting NVRAM 4D1FDA02-38C7-4A6A-9CC6-4BCCA8B30102:revcpuname - ignored, exists
00:286 00:013 OCVAR: Setting NVRAM 4D1FDA02-38C7-4A6A-9CC6-4BCCA8B30102:rtc-blacklist - Not Found
00:299 00:013 OCVAR: Setting NVRAM 7C436110-AB2A-4BBB-A880-FE41995C9F82:ForceDisplayRotationInEFI - ignored, exists
00:313 00:013 OCVAR: Setting NVRAM 7C436110-AB2A-4BBB-A880-FE41995C9F82:SystemAudioVolume - ignored, exists
00:326 00:013 OCVAR: Setting NVRAM 7C436110-AB2A-4BBB-A880-FE41995C9F82:bluetoothExternalDongleFailed - ignored, exists
00:340 00:013 OCVAR: Setting NVRAM 7C436110-AB2A-4BBB-A880-FE41995C9F82:bluetoothInternalControllerInfo - ignored, exists
00:354 00:013 OCVAR: Setting NVRAM 7C436110-AB2A-4BBB-A880-FE41995C9F82:boot-args - ignored, exists
00:367 00:013 OCVAR: Setting NVRAM 7C436110-AB2A-4BBB-A880-FE41995C9F82:csr-active-config - ignored, exists
00:381 00:014 OCVAR: Setting NVRAM 7C436110-AB2A-4BBB-A880-FE41995C9F82:prev-lang:kbd - Not Found
00:395 00:013 OCVAR: Setting NVRAM 7C436110-AB2A-4BBB-A880-FE41995C9F82:run-efi-updater - ignored, exists
00:409 00:013 OC: Current version is DBG-102-2024-10-08
00:419 00:009 OC: OcMiscMiddleInit...
00:428 00:009 OC: StorageHandle 61B9E618 with Full LauncherOption pointing to Default
00:439 00:010 OCVAR: Missing compatible FW NVRAM, going on...
00:449 00:009 OCB: Have existing order of size 10 - Buffer Too Small
00:459 00:009 OCB: Have existing option at Boot0001, valid
00:468 00:009 OCB: Boot order has first option as the default option
00:478 00:009 OC: OcLoadUefiSupport...
00:488 00:009 OCAU: OcAudioInstallProtocols (0, 0)
00:498 00:009 OCAU: 4B228577-6274-4A48-82AE-0713A1171987 protocol - Not Found
00:507 00:009 OCAU: C32332DF-FC56-4FE1-9358-BA0D529B24CD protocol - Not Found
00:517 00:009 OCAU: F4CB0B78-243B-11E7-A524-B8E8562CBAFA protocol - Not Found
00:527 00:009 OCAU: 3224B169-EC34-46D2-B779-E1B1687F525F protocol - Not Found
00:537 00:010 OCAE: Builtin installed
00:548 00:010 OCRTC: Wake log is 0x00 0x00  164 0x22
00:557 00:009 OCEG: Discovered rotate NVRAM override to 0
00:567 00:009 OC: Loading Apple Secure Boot with Disabled (level 0)
00:577 00:010 OCII: AIFTimerBoostInit Current timer is 10000
00:587 00:009 OC: Installing KeySupport...
00:597 00:009 OCII: gST->ConIn 64F96250 vs found 64F96250
00:606 00:009 AIK: Using 5 (50ms)
00:616 00:009 OCABC: ALRBL 0 RTDFRG 0 DEVMMIO 1 NOSU 0 NOVRWR 0 NOSB 0 FBSIG 0 NOHBMAP 0 SMSLIDE 0 WRUNPROT 1
00:629 00:013 OCABC: FEXITBS 0 PRMRG 0 CSLIDE 0 MSLIDE 0 PRSRV 1 RBMAP 1 VMAP 1 APPLOS 0 RTPERMS 1 ARBAR 0 RBIO 0
00:642 00:013 OCABC: Firmware has 16700156 free pages (381692 in lower 4 GB)
00:652 00:009 OCABC: Awaiting rendezvous with OpenRuntime r12
00:662 00:009 OC: RequestBootVarRouting 1
00:672 00:009 OCDM: Found 0x20050/0x20050 UEFI version (376 bytes, 0 rebuilding to 376) gST 69F65018 gBS 5F7E8F20 gBS->CreateEventEx 5F7DB2B0 &gBS 5D09F440
00:686 00:013 OC: AVX enabled - 1
00:696 00:010 OC: Got 6 drivers
00:706 00:010 OC: Driver HfsPlus.efi at 0 (HfsPlus.efi) is being loaded...
00:718 00:011 OCABC: EfiBootRt candidate - <nil>
00:727 00:009 OCABC: IsEfiBootRt 0 (BP 1, Apple 0)
00:737 00:009 OCB: Arch filtering 0(37892)->5F6B4018(37892) caps 0 - Success
00:747 00:009 OCABC: Recovering trashed GetMemoryMap pointer
00:756 00:009 OC: Driver HfsPlus.efi at 0 is successfully loaded!
00:766 00:009 OC: Driver HfsPlus.efi at 0 needs connection.
00:776 00:009 OC: Driver OpenRuntime.efi at 1 (OpenRuntime.efi) is being loaded...
00:788 00:012 OCABC: EfiBootRt candidate - <nil>
00:798 00:009 OCABC: IsEfiBootRt 0 (BP 1, Apple 0)
00:807 00:009 OCB: Arch filtering 0(36864)->5F6B4018(36864) caps 0 - Success
00:817 00:009 OCABC: Recovering trashed GetMemoryMap pointer
00:827 00:009 OCABC: Got rendezvous with OpenRuntime r12
00:837 00:010 OCABC: MAT support is 1
00:847 00:010 OC: Driver OpenRuntime.efi at 1 is successfully loaded!
00:857 00:010 OC: Driver OpenCanopy.efi at 2 () is being loaded...
00:869 00:011 OCABC: EfiBootRt candidate - <nil>
00:879 00:009 OCABC: IsEfiBootRt 0 (BP 1, Apple 0)
00:889 00:009 OCB: Arch filtering 0(139264)->5F68C018(139264) caps 0 - Success
00:898 00:009 OCABC: Recovering trashed GetMemoryMap pointer
00:908 00:009 OCCPU: TSC Adjust 0
00:918 00:009 OCCPU: Queried Core Crystal Clock Frequency    38400000Hz
00:928 00:009 OCCPU: CPUFrequencyFromART  3417600000Hz  3417MHz = 38400000 * 178 / 2
00:938 00:009 OCUI: Registered custom GUI protocol
00:948 00:009 OC: Driver OpenCanopy.efi at 2 is successfully loaded!
00:957 00:009 OC: Driver ResetNvramEntry.efi at 3 () is being loaded...
00:970 00:012 OCABC: EfiBootRt candidate - <nil>
00:981 00:010 OCABC: IsEfiBootRt 0 (BP 1, Apple 0)
00:991 00:010 OCB: Arch filtering 0(57344)->5F6A0018(57344) caps 0 - Success
01:001 00:010 OCABC: Recovering trashed GetMemoryMap pointer
01:011 00:009 OCCPU: TSC Adjust 0
01:021 00:009 OCCPU: Queried Core Crystal Clock Frequency    38400000Hz
01:031 00:009 OCCPU: CPUFrequencyFromART  3417600000Hz  3417MHz = 38400000 * 178 / 2
01:041 00:009 OC: Driver ResetNvramEntry.efi at 3 is successfully loaded!
01:050 00:009 OC: Driver OpenLinuxBoot.efi at 4 () is being loaded...
01:062 00:011 OCABC: EfiBootRt candidate - <nil>
01:072 00:010 OCABC: IsEfiBootRt 0 (BP 1, Apple 0)
01:082 00:009 OCB: Arch filtering 0(102400)->5F695018(102400) caps 0 - Success
01:092 00:009 OCABC: Recovering trashed GetMemoryMap pointer
01:102 00:009 OCCPU: TSC Adjust 0
01:112 00:009 OCCPU: Queried Core Crystal Clock Frequency    38400000Hz
01:122 00:009 OCCPU: CPUFrequencyFromART  3417600000Hz  3417MHz = 38400000 * 178 / 2
01:132 00:009 OC: Driver OpenLinuxBoot.efi at 4 is successfully loaded!
01:142 00:010 OC: Driver Ext4Dxe.efi at 5 () is being loaded...
01:154 00:012 OCABC: EfiBootRt candidate - <nil>
01:165 00:010 OCABC: IsEfiBootRt 0 (BP 1, Apple 0)
01:175 00:009 OCB: Arch filtering 0(57344)->5F6A0018(57344) caps 0 - Success
01:185 00:009 OCABC: Recovering trashed GetMemoryMap pointer
01:194 00:009 OC: Driver Ext4Dxe.efi at 5 is successfully loaded!
01:204 00:009 OC: Driver Ext4Dxe.efi at 5 needs connection.
01:214 00:009 OC: Connecting drivers...
01:265 00:051 OC: Connecting drivers done...
01:275 00:009 OC: Found 3 pointer devices - Success
01:285 00:009 OCJS: PartitionInfo is Success
01:296 00:010 OCJS: Got APFS super block for 6D4BA0ED-D4B5-9344-A566-F62F01A7AAF9
01:306 00:010 OCJS: Block (P:1|F:0) read req 8F0F6E -> 4787B70 of 1000 (mask 0, mul 8) - Success
01:325 00:018 OCJS: APFS driver 2313001002000000/20240807 found for 6D4BA0ED-D4B5-9344-A566-F62F01A7AAF9, required >= 0/0, allow
01:339 00:013 OCABC: Recovering trashed GetMemoryMap pointer
01:349 00:010 OCJS: Connecting normally APFS driver on handle 61B87C98
01:587 00:237 OCC: GOP exists on ConsoleOutHandle and has 8 modes
01:597 00:009 OCC: Looking for GOP replacement due to blit-only GOP
01:607 00:009 OCC: Alternative GOP status is - Success
01:617 00:009 OCC: Checking alternative GOP mode 1 - Success
01:626 00:009 OC: Requested resolution is 0x0@0 (max: 1, force: 0) from Max
01:636 00:009 OCC: Requesting 0x0@0 (max: 1) resolution, curr 2, total 8
01:646 00:009 OCC: Current FB at 0x4000000000 (0x1E7800), format 1, res 800x600 scan 832
01:656 00:009 OCC: Mode 0 - 3440x1440:1
01:666 00:009 OCC: Mode 1 - 640x480:1
01:676 00:009 OCC: Mode 2 - 800x600:1
01:686 00:009 OCC: Mode 3 - 1024x768:1
01:695 00:009 OCC: Mode 4 - 1280x1024:1
01:705 00:009 OCC: Mode 5 - 1400x1050:1
01:715 00:010 OCC: Mode 6 - 1600x1200:1
01:726 00:010 OCC: Mode 7 - 1280x960:1
01:736 00:010 OCC: Setting mode 0 with 3440x1440 resolution
01:750 00:014 OCC: Changed resolution mode to 0
01:760 00:009 OC: Changed resolution to 0x0@0 (max: 1, force: 0) from Max - Success
01:770 00:010 OC: Selected UIScale 2 based on 3440x1440 resolution
01:780 00:010 OC: Setting UIScale to 2 - Success
01:790 00:009 OCC: Using builtin text renderer with 2 scale
01:800 00:009 OCC: Install console control (5D08CF18/5F7D2350/0), current - Success
01:819 00:018 OCC: Setup ASCII Output - Success
01:826 00:007 OC: Requested console mode is 0x0 (max: 0) from 
01:834 00:008 OC: Cannot locate audio decoder protocol - Not Found
01:843 00:008 OC: OcMiscLoadSystemReport...
01:850 00:007 OCCPU: MP services threads 24 (enabled 24) - Success
01:858 00:008 OCCPU: MP services Pkg 1 Cores 40 Threads 2 - Success
01:867 00:008 OCCPU: Found 13th Gen Intel(R) Core(TM) i7-13700KF
01:875 00:008 OCCPU: Signature B0671 Stepping 1 Model B7 Family 6 Type 0 ExtModel B ExtFamily 0 uCode 12B CPUID MAX (20/80000008)
01:886 00:010 OCCPU: EIST CFG Lock 0
01:893 00:006 OCCPU: TSC Adjust 0
01:900 00:006 OCCPU: Queried Core Crystal Clock Frequency    38400000Hz
01:908 00:008 OCCPU: CPUFrequencyFromART  3417600000Hz  3417MHz = 38400000 * 178 / 2
01:917 00:008 OCCPU: Timer address is 0 from Unknown INTEL
01:925 00:007 OCCPU: Failed to get FSBFrequency data using Apple Platform Info - Not Found
01:934 00:009 OCCPU: Intel TSC:  3417600000Hz,  3417MHz; FSB:   100517647Hz,   100MHz; MaxBusRatio: 34
01:943 00:009 OCCPU: Detected Apple Processor Type: 07 -> 0709
01:951 00:008 OCCPU: CPUFrequencyFromTSC           0Hz     0MHz
01:960 00:008 OCCPU: CPUFrequency  3417600000Hz  3417MHz
01:967 00:007 OCCPU: FSBFrequency   100517647Hz   100MHz
01:975 00:007 OCCPU: Pkg 1 Cores 16 Threads 24
01:983 00:007 OCFS: Trying to locate filesystem on 61B9E618 0
01:992 00:009 OC: Report is already created, skipping
02:002 00:009 OC: OcLoadAcpiSupport...
02:009 00:007 OCA: Found 26 ACPI tables
02:016 00:007 OCA: Detected table FACP (50434146) (OEM 00002049204D2041) at 68FCD000 of 276 bytes at index 0
02:026 00:009 OCA: Detected DSDT at 68F44000 of 560247 bytes at index 0
02:034 00:008 OCA: Detected table SSDT (54445353) (OEM 6C62615466747044) at 68FCE000 of 5932 bytes at index 1
02:044 00:009 OCA: Detected table FIDT (54444946) (OEM 00000049204D2041) at 68F43000 of 156 bytes at index 2
02:054 00:009 OCA: Detected table SSDT (54445353) (OEM 7665445F78616D50) at 68FD1000 of 908 bytes at index 3
02:063 00:009 OCA: Detected table SSDT (54445353) (OEM 0074647353757043) at 68F3D000 of 23860 bytes at index 4
02:073 00:009 OCA: Detected table AAFT (54464141) (OEM 20544641414D454F) at 68FD0000 of 965 bytes at index 5
02:083 00:009 OCA: Detected table SSDT (54445353) (OEM 0020746473536153) at 68F3A000 of 10881 bytes at index 6
02:093 00:010 OCA: Detected table SSDT (54445353) (OEM 7464735378666749) at 68F36000 of 13135 bytes at index 7
02:103 00:009 OCA: Detected table HPET (54455048) (OEM 00002049204D2041) at 68F35000 of 56 bytes at index 8
02:113 00:009 OCA: Detected table APIC (43495041) (OEM 00002049204D2041) at 68F34000 of 476 bytes at index 9
02:123 00:009 OCA: Detected table MCFG (4746434D) (OEM 00002049204D2041) at 68F33000 of 60 bytes at index 10
02:133 00:010 OCA: Detected table NHLT (544C484E) (OEM 00002049204D2041) at 68F32000 of 45 bytes at index 11
02:144 00:010 OCA: Detected table LPIT (5449504C) (OEM 00002049204D2041) at 68F31000 of 204 bytes at index 12
02:153 00:009 OCA: Detected table SSDT (54445353) (OEM 4365707954746254) at 68F26000 of 37620 bytes at index 13
02:163 00:009 OCA: Detected table DBGP (50474244) (OEM 00002049204D2041) at 68F25000 of 52 bytes at index 14
02:173 00:009 OCA: Detected table DBG2 (32474244) (OEM 00002049204D2041) at 68F24000 of 84 bytes at index 15
02:183 00:009 OCA: Detected table SSDT (54445353) (OEM 6C62615443627355) at 68F22000 of 6410 bytes at index 16
02:193 00:009 OCA: Detected table DMAR (52414D44) (OEM 20202020324B4445) at 68F21000 of 80 bytes at index 17
02:203 00:009 OCA: Detected table FPDT (54445046) (OEM 00002049204D2041) at 68F20000 of 68 bytes at index 18
02:213 00:009 OCA: Detected table SSDT (54445353) (OEM 34317370725F6878) at 68F1E000 of 4905 bytes at index 19
02:234 00:020 OCA: Detected table SSDT (54445353) (OEM 0020657047636F53) at 68F1A000 of 15082 bytes at index 20
02:254 00:020 OCA: Detected table SSDT (54445353) (OEM 00206E6D43636F53) at 68F16000 of 14810 bytes at index 21
02:275 00:020 OCA: Detected table VFCT (54434656) (OEM 00002049204D2041) at 68F0B000 of 44164 bytes at index 22
02:296 00:020 OCA: Detected table BGRT (54524742) (OEM 00002049204D2041) at 68F0A000 of 56 bytes at index 23
02:317 00:020 OCA: Detected table PHAT (54414850) (OEM 00002049204D2041) at 68F09000 of 2727 bytes at index 24
02:338 00:020 OCA: Detected table WSMT (544D5357) (OEM 00002049204D2041) at 68F30000 of 40 bytes at index 25
02:359 00:021 OCA: FACS signature is 0 (0)
02:379 00:019 OCA: Allocated new table SSDT at 69008000
02:397 00:018 OCA: Inserted table SSDT (54445353) (OEM 0043415741435452) of 78 bytes into ACPI at index 26
02:419 00:021 OCA: Allocated new table SSDT at 69006000
02:438 00:018 OCA: Inserted table SSDT (54445353) (OEM 4167756C50757043) of 4120 bytes into ACPI at index 27
02:460 00:021 OCA: Allocated new table SSDT at 69005000
02:479 00:018 OCA: Inserted table SSDT (54445353) (OEM 0000434574647353) of 377 bytes into ACPI at index 28
02:500 00:021 OCA: Allocated new table SSDT at 69004000
02:519 00:018 OCA: Inserted table SSDT (54445353) (OEM 000000004348434D) of 104 bytes into ACPI at index 29
02:540 00:020 OCA: Exposing XSDT table table FACP (50434146) (OEM 00002049204D2041) at 68FCD000 of 276 bytes at index 0
02:561 00:021 OCA: Exposing XSDT table table SSDT (54445353) (OEM 6C62615466747044) at 68FCE000 of 5932 bytes at index 1
02:582 00:021 OCA: Exposing XSDT table table FIDT (54444946) (OEM 00000049204D2041) at 68F43000 of 156 bytes at index 2
02:603 00:021 OCA: Exposing XSDT table table SSDT (54445353) (OEM 7665445F78616D50) at 68FD1000 of 908 bytes at index 3
02:625 00:021 OCA: Exposing XSDT table table SSDT (54445353) (OEM 0074647353757043) at 68F3D000 of 23860 bytes at index 4
02:646 00:021 OCA: Exposing XSDT table table AAFT (54464141) (OEM 20544641414D454F) at 68FD0000 of 965 bytes at index 5
02:668 00:021 OCA: Exposing XSDT table table SSDT (54445353) (OEM 0020746473536153) at 68F3A000 of 10881 bytes at index 6
02:689 00:021 OCA: Exposing XSDT table table SSDT (54445353) (OEM 7464735378666749) at 68F36000 of 13135 bytes at index 7
02:711 00:021 OCA: Exposing XSDT table table HPET (54455048) (OEM 00002049204D2041) at 68F35000 of 56 bytes at index 8
02:732 00:021 OCA: Exposing XSDT table table APIC (43495041) (OEM 00002049204D2041) at 68F34000 of 476 bytes at index 9
02:753 00:021 OCA: Exposing XSDT table table MCFG (4746434D) (OEM 00002049204D2041) at 68F33000 of 60 bytes at index 10
02:774 00:021 OCA: Exposing XSDT table table NHLT (544C484E) (OEM 00002049204D2041) at 68F32000 of 45 bytes at index 11
02:795 00:021 OCA: Exposing XSDT table table LPIT (5449504C) (OEM 00002049204D2041) at 68F31000 of 204 bytes at index 12
02:816 00:021 OCA: Exposing XSDT table table SSDT (54445353) (OEM 4365707954746254) at 68F26000 of 37620 bytes at index 13
02:837 00:021 OCA: Exposing XSDT table table DBGP (50474244) (OEM 00002049204D2041) at 68F25000 of 52 bytes at index 14
02:859 00:021 OCA: Exposing XSDT table table DBG2 (32474244) (OEM 00002049204D2041) at 68F24000 of 84 bytes at index 15
02:880 00:021 OCA: Exposing XSDT table table SSDT (54445353) (OEM 6C62615443627355) at 68F22000 of 6410 bytes at index 16
02:901 00:021 OCA: Exposing XSDT table table DMAR (52414D44) (OEM 20202020324B4445) at 68F21000 of 80 bytes at index 17
02:922 00:021 OCA: Exposing XSDT table table FPDT (54445046) (OEM 00002049204D2041) at 68F20000 of 68 bytes at index 18
02:943 00:021 OCA: Exposing XSDT table table SSDT (54445353) (OEM 34317370725F6878) at 68F1E000 of 4905 bytes at index 19
02:965 00:021 OCA: Exposing XSDT table table SSDT (54445353) (OEM 0020657047636F53) at 68F1A000 of 15082 bytes at index 20
02:987 00:021 OCA: Exposing XSDT table table SSDT (54445353) (OEM 00206E6D43636F53) at 68F16000 of 14810 bytes at index 21
03:008 00:021 OCA: Exposing XSDT table table VFCT (54434656) (OEM 00002049204D2041) at 68F0B000 of 44164 bytes at index 22
03:029 00:021 OCA: Exposing XSDT table table BGRT (54524742) (OEM 00002049204D2041) at 68F0A000 of 56 bytes at index 23
03:050 00:021 OCA: Exposing XSDT table table PHAT (54414850) (OEM 00002049204D2041) at 68F09000 of 2727 bytes at index 24
03:072 00:021 OCA: Exposing XSDT table table WSMT (544D5357) (OEM 00002049204D2041) at 68F30000 of 40 bytes at index 25
03:093 00:021 OCA: Exposing XSDT table table SSDT (54445353) (OEM 0043415741435452) at 69008000 of 78 bytes at index 26
03:114 00:021 OCA: Exposing XSDT table table SSDT (54445353) (OEM 4167756C50757043) at 69006000 of 4120 bytes at index 27
03:135 00:021 OCA: Exposing XSDT table table SSDT (54445353) (OEM 0000434574647353) at 69005000 of 377 bytes at index 28
03:156 00:021 OCA: Exposing XSDT table table SSDT (54445353) (OEM 000000004348434D) at 69004000 of 104 bytes at index 29
03:178 00:021 OCA: Exposing RSDT table table FACP (50434146) (OEM 00002049204D2041) at 68FCD000 of 276 bytes at index 0
03:199 00:021 OCA: Exposing RSDT table table SSDT (54445353) (OEM 6C62615466747044) at 68FCE000 of 5932 bytes at index 1
03:220 00:021 OCA: Exposing RSDT table table FIDT (54444946) (OEM 00000049204D2041) at 68F43000 of 156 bytes at index 2
03:241 00:021 OCA: Exposing RSDT table table SSDT (54445353) (OEM 7665445F78616D50) at 68FD1000 of 908 bytes at index 3
03:262 00:021 OCA: Exposing RSDT table table SSDT (54445353) (OEM 0074647353757043) at 68F3D000 of 23860 bytes at index 4
03:284 00:021 OCA: Exposing RSDT table table AAFT (54464141) (OEM 20544641414D454F) at 68FD0000 of 965 bytes at index 5
03:305 00:021 OCA: Exposing RSDT table table SSDT (54445353) (OEM 0020746473536153) at 68F3A000 of 10881 bytes at index 6
03:327 00:021 OCA: Exposing RSDT table table SSDT (54445353) (OEM 7464735378666749) at 68F36000 of 13135 bytes at index 7
03:348 00:021 OCA: Exposing RSDT table table HPET (54455048) (OEM 00002049204D2041) at 68F35000 of 56 bytes at index 8
03:369 00:021 OCA: Exposing RSDT table table APIC (43495041) (OEM 00002049204D2041) at 68F34000 of 476 bytes at index 9
03:390 00:021 OCA: Exposing RSDT table table MCFG (4746434D) (OEM 00002049204D2041) at 68F33000 of 60 bytes at index 10
03:411 00:021 OCA: Exposing RSDT table table NHLT (544C484E) (OEM 00002049204D2041) at 68F32000 of 45 bytes at index 11
03:432 00:021 OCA: Exposing RSDT table table LPIT (5449504C) (OEM 00002049204D2041) at 68F31000 of 204 bytes at index 12
03:454 00:021 OCA: Exposing RSDT table table SSDT (54445353) (OEM 4365707954746254) at 68F26000 of 37620 bytes at index 13
03:475 00:021 OCA: Exposing RSDT table table DBGP (50474244) (OEM 00002049204D2041) at 68F25000 of 52 bytes at index 14
03:496 00:021 OCA: Exposing RSDT table table DBG2 (32474244) (OEM 00002049204D2041) at 68F24000 of 84 bytes at index 15
03:517 00:021 OCA: Exposing RSDT table table SSDT (54445353) (OEM 6C62615443627355) at 68F22000 of 6410 bytes at index 16
03:538 00:021 OCA: Exposing RSDT table table DMAR (52414D44) (OEM 20202020324B4445) at 68F21000 of 80 bytes at index 17
03:559 00:021 OCA: Exposing RSDT table table FPDT (54445046) (OEM 00002049204D2041) at 68F20000 of 68 bytes at index 18
03:581 00:021 OCA: Exposing RSDT table table SSDT (54445353) (OEM 34317370725F6878) at 68F1E000 of 4905 bytes at index 19
03:602 00:021 OCA: Exposing RSDT table table SSDT (54445353) (OEM 0020657047636F53) at 68F1A000 of 15082 bytes at index 20
03:624 00:021 OCA: Exposing RSDT table table SSDT (54445353) (OEM 00206E6D43636F53) at 68F16000 of 14810 bytes at index 21
03:646 00:021 OCA: Exposing RSDT table table VFCT (54434656) (OEM 00002049204D2041) at 68F0B000 of 44164 bytes at index 22
03:667 00:021 OCA: Exposing RSDT table table BGRT (54524742) (OEM 00002049204D2041) at 68F0A000 of 56 bytes at index 23
03:688 00:021 OCA: Exposing RSDT table table PHAT (54414850) (OEM 00002049204D2041) at 68F09000 of 2727 bytes at index 24
03:709 00:021 OCA: Exposing RSDT table table WSMT (544D5357) (OEM 00002049204D2041) at 68F30000 of 40 bytes at index 25
03:730 00:021 OCA: Exposing RSDT table table SSDT (54445353) (OEM 0043415741435452) at 69008000 of 78 bytes at index 26
03:751 00:021 OCA: Exposing RSDT table table SSDT (54445353) (OEM 4167756C50757043) at 69006000 of 4120 bytes at index 27
03:773 00:021 OCA: Exposing RSDT table table SSDT (54445353) (OEM 0000434574647353) at 69005000 of 377 bytes at index 28
03:794 00:021 OCA: Exposing RSDT table table SSDT (54445353) (OEM 000000004348434D) at 69004000 of 104 bytes at index 29
03:815 00:021 OC: OcLoadPlatformSupport...
03:833 00:018 OCSMB: Found DMI Anchor 69A64000 v3.5 Table Address 69A61000 Length 0BBA
03:853 00:019 OCSMB: Found DMI Anchor 69A63000 v3.5 Table Address 69A61000 Length 0BBA
03:873 00:019 OCSMB: Current SMBIOS Z790M-ITX WiFi (Z790M-ITX WiFi made by ASRock)
03:893 00:020 OC: PlatformInfo auto 1 OEM SN 0 OEM UUID 0 OEM MLB 0 OEM ROM 0 - Success
03:913 00:020 OC: New SMBIOS: Acidanthera model iMacPro1,1
03:933 00:019 OCSMB: Post-override BIOS vendor Acidanthera 0
03:951 00:018 OCSMB: Number of CPU cache entries is 8
03:970 00:018 OCSMB: Number of CPU cache entries is 8
03:989 00:018 OCSMB: Number of CPU cache entries is 8
04:007 00:018 OCSMB: CPU1 display frequency is 3420MHz
04:026 00:018 OCSMB: Applying 1337 (3) prev 69A64000 (3002/31), 69A63000 (3002/24)
04:046 00:019 OCSMB: Patched 66F59000 v3.2 Table Address 66F5A000 Length 0539 1E E6
04:065 00:019 OCDH: Setting DataHub 64517CC8-6561-4051-B03C-5964B60F4C7A:name (9) - Success
04:086 00:020 OCDH: Setting DataHub 64517CC8-6561-4051-B03C-5964B60F4C7A:Model (22) - Success
04:106 00:020 OCDH: Setting DataHub 64517CC8-6561-4051-B03C-5964B60F4C7A:SystemSerialNumber (26) - Success
04:126 00:020 OCDH: Setting DataHub 64517CC8-6561-4051-B03C-5964B60F4C7A:board-id (21) - Success
04:147 00:020 OCDH: Setting DataHub 64517CC8-6561-4051-B03C-5964B60F4C7A:board-rev (1) - Success
04:167 00:020 OCDH: Setting DataHub 64517CC8-6561-4051-B03C-5964B60F4C7A:StartupPowerEvents (8) - Success
04:188 00:021 OCDH: Setting DataHub 64517CC8-6561-4051-B03C-5964B60F4C7A:InitialTSC (8) - Success
04:209 00:020 OCDH: Setting DataHub 64517CC8-6561-4051-B03C-5964B60F4C7A:FSBFrequency (8) - Success
04:229 00:020 OCDH: Setting DataHub 64517CC8-6561-4051-B03C-5964B60F4C7A:ARTFrequency (8) - Success
04:250 00:020 OCDH: Setting DataHub 64517CC8-6561-4051-B03C-5964B60F4C7A:DevicePathsSupported (4) - Success
04:271 00:020 OCDH: Setting DataHub 64517CC8-6561-4051-B03C-5964B60F4C7A:RPlt (8) - Success
04:291 00:020 OC: Setting HW_BID Mac-7BA5B2D9E42DDD94 - Success
04:310 00:019 OC: Setting HW_ROM 5D:75:D7:5D:75:D7 - Success
04:329 00:018 OC: Setting ROM 5D:75:D7:5D:75:D7 - Success
04:348 00:018 OC: Setting HW_MLB XXXXXXXXXXXXXXXXX - Success
04:367 00:018 OC: Setting MLB XXXXXXXXXXXXXXXXX - Success
04:386 00:018 OC: Setting HW_SSN XXXXXXXXXXXX - Success
04:405 00:018 OC: Setting SSN XXXXXXXXXXXX - Success
04:423 00:018 OC: Setting FirmwareFeatures FD8FF53E - Success
04:442 00:019 OC: Setting ExtendedFirmwareFeatures 00000008FD8FF53E - Success
04:462 00:019 OC: Setting FirmwareFeaturesMask FF9FFF3F - Success
04:482 00:019 OC: Setting ExtendedFirmwareFeaturesMask 00000008FF9FFF3F - Success
04:502 00:020 OC: OcLoadDevPropsSupport...
04:520 00:018 OC: Setting devprop PciRoot(0x0)/Pci(0x1F,0x3):layout-id - Success
04:540 00:019 OC: OcMiscLateInit...
04:557 00:017 OC: Translated HibernateMode None to 0
04:576 00:018 OC: Hibernation activation - Invalid Parameter, hibernation wake - no
04:596 00:019 OC: Panic log does not exist
04:614 00:018 OC: OcLoadKernelSupport...
04:632 00:018 OC: All green, starting boot management...
04:650 00:018 OC: Handing off to external boot controller
04:669 00:018 OC: Ready for takeoff in 0 us
04:694 00:024 OCUI: Failed to load image (1/1) Resources\Image\Acidanthera\GoldenGate\Background.icns prefix:Acidanthera\GoldenGate icon:0 - Not Found
04:761 00:067 OCUI: Failed to load image (1/2) Resources\Image\Acidanthera\GoldenGate\Apple.icns prefix:Acidanthera\GoldenGate icon:1 - Not Found
04:805 00:044 OCUI: Failed to load image (2/2) Resources\Image\Acidanthera\GoldenGate\ExtWindows.icns prefix:Acidanthera\GoldenGate icon:1 - Not Found
04:828 00:022 OCUI: Failed to load image (1/2) Resources\Image\Acidanthera\GoldenGate\Other.icns prefix:Acidanthera\GoldenGate icon:1 - Not Found
04:855 00:026 OCUI: Failed to load image (2/2) Resources\Image\Acidanthera\GoldenGate\ExtTool.icns prefix:Acidanthera\GoldenGate icon:1 - Not Found
04:878 00:023 OCUI: Failed to load image (1/2) Resources\Image\Acidanthera\GoldenGate\ResetNVRAM.icns prefix:Acidanthera\GoldenGate icon:1 - Not Found
04:904 00:026 OCUI: Failed to load image (2/2) Resources\Image\Acidanthera\GoldenGate\ExtShell.icns prefix:Acidanthera\GoldenGate icon:1 - Not Found
04:930 00:025 OCUI: Info->fontSize 20 Info->bitField 192 Info->charSet 0 Info->stretchH 100 Info->aa 1
04:950 00:020 OCUI: Info->paddingUp 0 Info->paddingRight 0 Info->paddingDown 0 Info->paddingLeft 0
04:970 00:020 OCUI: Info->spacingHoriz 1 Info->spacingVert 1 Info->outline 0 Info->fontName 
04:991 00:020 OCB: Adding fs 6204AF98 (E:0|L:0|P:Success) - PciRoot(0x0)/Pci(0x6,0x0)/Pci(0x0,0x0)/NVMe(0x1,EC-68-3F-4E-8B-44-1B-00)/HD(1,GPT,050AA326-9EE4-4F0F-9A75-A86031801B50,0x1000,0x96000)
05:015 00:024 OCB: Adding fs 61B9E618 (E:0|L:1|P:Success) - PciRoot(0x0)/Pci(0x17,0x0)/Sata(0x4,0xFFFF,0x0)/HD(1,GPT,3850C186-C2AB-4525-835E-B677625E099C,0x28,0x64000)
05:038 00:023 OCB: Adding fs 61B4BD98 (E:0|L:0|P:Success) - PciRoot(0x0)/Pci(0x1D,0x0)/Pci(0x0,0x0)/NVMe(0x1,00-00-00-00-00-00-00-00)/HD(2,GPT,3556F94A-EDAD-4473-AD7F-9D2D9ED43E25,0x8800,0x32000)
05:062 00:024 OCB: Adding fs 61B4BB18 (E:0|L:0|P:Success) - PciRoot(0x0)/Pci(0x1D,0x0)/Pci(0x0,0x0)/NVMe(0x1,00-00-00-00-00-00-00-00)/HD(3,GPT,7B09B032-88FA-4C05-92D9-AFB7A7982511,0x3A800,0x77382800)
05:086 00:024 OCB: Adding fs 5F981898 (E:0|L:0|P:Success) - PciRoot(0x0)/Pci(0x17,0x0)/Sata(0x4,0xFFFF,0x0)/HD(2,GPT,3D64AD05-0A01-4998-9F4F-F557CF44AFD4,0x64028,0x3A321FE0)/VenMedia(BE74FCF7-0B7C-49F3-9147-01F4042E6842,AB628DA0825801439A7845D15782DE97)
05:124 00:037 OCB: Adding fs 5F6BC118 (E:0|L:0|P:Success) - PciRoot(0x0)/Pci(0x17,0x0)/Sata(0x4,0xFFFF,0x0)/HD(2,GPT,3D64AD05-0A01-4998-9F4F-F557CF44AFD4,0x64028,0x3A321FE0)/VenMedia(BE74FCF7-0B7C-49F3-9147-01F4042E6842,BACCAE5B62B82947BD71DD6119A7451D)
05:161 00:037 OCB: Adding fs 5F6B2918 (E:0|L:0|P:Success) - PciRoot(0x0)/Pci(0x17,0x0)/Sata(0x4,0xFFFF,0x0)/HD(2,GPT,3D64AD05-0A01-4998-9F4F-F557CF44AFD4,0x64028,0x3A321FE0)/VenMedia(BE74FCF7-0B7C-49F3-9147-01F4042E6842,464EA4CFE500A14186C4A7B32F841A2A)
05:198 00:037 OCB: Adding fs 5CFB8D98 (E:0|L:0|P:Success) - PciRoot(0x0)/Pci(0x17,0x0)/Sata(0x4,0xFFFF,0x0)/HD(2,GPT,3D64AD05-0A01-4998-9F4F-F557CF44AFD4,0x64028,0x3A321FE0)/VenMedia(BE74FCF7-0B7C-49F3-9147-01F4042E6842,072BCF4F4E08AD4487A782541C7DC168)
05:236 00:037 OCB: Adding fs 5F605E18 (E:0|L:0|P:Success) - PciRoot(0x0)/Pci(0x17,0x0)/Sata(0x4,0xFFFF,0x0)/HD(2,GPT,3D64AD05-0A01-4998-9F4F-F557CF44AFD4,0x64028,0x3A321FE0)/VenMedia(BE74FCF7-0B7C-49F3-9147-01F4042E6842,AB47EE84A088F6489817D9AD9BC944D7)
05:274 00:037 OCB: Adding fs 5CFD4D98 (E:0|L:0|P:Success) - PciRoot(0x0)/Pci(0x17,0x0)/Sata(0x4,0xFFFF,0x0)/HD(2,GPT,3D64AD05-0A01-4998-9F4F-F557CF44AFD4,0x64028,0x3A321FE0)/VenMedia(BE74FCF7-0B7C-49F3-9147-01F4042E6842,3BD6217D599E06429D7BE5ACF1BE94B4)
05:312 00:037 OCB: Found 10 potentially bootable filesystems
05:331 00:018 OCB: Found 2 BootOrder entries with BootNext excluded
05:350 00:019 OCB: efi-boot-device-data - Not Found
05:368 00:018 OCB: efi-boot-next-data - Not Found
05:387 00:018 OCB: efi-backup-boot-device-data - Not Found
05:406 00:018 OCB: efi-apple-recovery-data - Not Found
05:424 00:018 OCB: Dumping BootOrder
05:442 00:017 OCB: 0 -> Boot0000 = HD(2,GPT,3556F94A-EDAD-4473-AD7F-9D2D9ED43E25,0x8800,0x32000)/\EFI\Microsoft\Boot\bootmgfw.efi
05:464 00:021 OCB: 1 -> Boot0080 = PciRoot(0x0)/Pci(0x17,0x0)/Sata(0x4,0xFFFF,0x0)/HD(2,GPT,3D64AD05-0A01-4998-9F4F-F557CF44AFD4,0x64028,0x3A321FE0)/VenMedia(BE74FCF7-0B7C-49F3-9147-01F4042E6842,AB628DA0825801439A7845D15782DE97)/\5BAECCBA-B862-4729-BD71-DD6119A7451D\System\Library\CoreServices\boot.efi
05:503 00:039 OCB: Parsing predefined list...
05:521 00:018 OCB: 0 -> Boot0080 = PciRoot(0x0)/Pci(0x17,0x0)/Sata(0x4,0xFFFF,0x0)/HD(2,GPT,3D64AD05-0A01-4998-9F4F-F557CF44AFD4,0x64028,0x3A321FE0)/VenMedia(BE74FCF7-0B7C-49F3-9147-01F4042E6842,AB628DA0825801439A7845D15782DE97)/\5BAECCBA-B862-4729-BD71-DD6119A7451D\System\Library\CoreServices\boot.efi
05:561 00:039 OCB: Adding fs 2007C5F5 for 1 custom entries and BEP (aux shown)
05:580 00:019 OCB: Building entry from Boot0000
05:599 00:018 OCB: Assuming DP is short-form (prefix)
05:618 00:018 OCB: Expanded DP - PciRoot(0x0)/Pci(0x1D,0x0)/Pci(0x0,0x0)/NVMe(0x1,00-00-00-00-00-00-00-00)/HD(2,GPT,3556F94A-EDAD-4473-AD7F-9D2D9ED43E25,0x8800,0x32000)/\EFI\Microsoft\Boot\bootmgfw.efi
05:642 00:024 OCB: Expanded DP remainder - \EFI\Microsoft\Boot\bootmgfw.efi
05:662 00:019 OCB: Matched fs 61B4BD98
05:682 00:019 OCB: Adding entry type (T:32|F:0|G:0) - PciRoot(0x0)/Pci(0x1D,0x0)/Pci(0x0,0x0)/NVMe(0x1,00-00-00-00-00-00-00-00)/HD(2,GPT,3556F94A-EDAD-4473-AD7F-9D2D9ED43E25,0x8800,0x32000)/\EFI\Microsoft\Boot\bootmgfw.efi
05:710 00:028 OCB: Get visibility for boot entry <null string> - Not Found
05:732 00:022 OCB: Registering entry Windows [Windows] (T:32|F:0|G:0|E:0|B:0) - PciRoot(0x0)/Pci(0x1D,0x0)/Pci(0x0,0x0)/NVMe(0x1,00-00-00-00-00-00-00-00)/HD(2,GPT,3556F94A-EDAD-4473-AD7F-9D2D9ED43E25,0x8800,0x32000)/\EFI\Microsoft\Boot\bootmgfw.efi
05:769 00:037 OCB: Adding bless entry on disk - PciRoot(0x0)/Pci(0x1D,0x0)/Pci(0x0,0x0)/NVMe(0x1,00-00-00-00-00-00-00-00)/HD(2,GPT,3556F94A-EDAD-4473-AD7F-9D2D9ED43E25,0x8800,0x32000)
05:793 00:024 OCBP: Blessed file is missing
05:812 00:018 OCBP: Blessed folder is missing
05:831 00:019 OCBP: Predefined <nil> \System\Library\CoreServices\boot.efi is missing - Not Found
05:852 00:021 OCBP: Predefined <nil> \EFI\Microsoft\Boot\bootmgfw.efi was found
05:872 00:019 OCB: Adding entry type (T:32|F:0|G:0) - PciRoot(0x0)/Pci(0x1D,0x0)/Pci(0x0,0x0)/NVMe(0x1,00-00-00-00-00-00-00-00)/HD(2,GPT,3556F94A-EDAD-4473-AD7F-9D2D9ED43E25,0x8800,0x32000)/\EFI\Microsoft\Boot\bootmgfw.efi
05:901 00:028 OCB: Get visibility for boot entry <null string> - Not Found
05:920 00:019 OCB: Discarding already present DP
05:939 00:018 OCBP: APFS recovery volume handle missing - \EFI\Microsoft\Boot\
05:959 00:020 OCB: APFS recovery is not present - Not Found
05:977 00:018 OCB: Building entry from Boot0080
05:996 00:018 OCB: Assuming DP is full-form or lacks suffix
06:015 00:018 OCB: Expanded DP - PciRoot(0x0)/Pci(0x17,0x0)/Sata(0x4,0xFFFF,0x0)/HD(2,GPT,3D64AD05-0A01-4998-9F4F-F557CF44AFD4,0x64028,0x3A321FE0)/VenMedia(BE74FCF7-0B7C-49F3-9147-01F4042E6842,AB628DA0825801439A7845D15782DE97)/\5BAECCBA-B862-4729-BD71-DD6119A7451D\System\Library\CoreServices\boot.efi
06:054 00:039 OCB: Expanded DP remainder - \5BAECCBA-B862-4729-BD71-DD6119A7451D\System\Library\CoreServices\boot.efi
06:075 00:020 OCB: Matched fs 5F981898
06:095 00:020 OCB: Adding entry type (T:2|F:0|G:0) - PciRoot(0x0)/Pci(0x17,0x0)/Sata(0x4,0xFFFF,0x0)/HD(2,GPT,3D64AD05-0A01-4998-9F4F-F557CF44AFD4,0x64028,0x3A321FE0)/VenMedia(BE74FCF7-0B7C-49F3-9147-01F4042E6842,AB628DA0825801439A7845D15782DE97)/\5BAECCBA-B862-4729-BD71-DD6119A7451D\System\Library\CoreServices\boot.efi
06:135 00:040 OCB: Get visibility for boot entry 5BAECCBA-B862-4729-BD71-DD6119A7451D\ - Not Found
06:157 00:021 OCB: Registering entry Macintosh HD [Apple] (T:2|F:0|G:0|E:0|B:0) - PciRoot(0x0)/Pci(0x17,0x0)/Sata(0x4,0xFFFF,0x0)/HD(2,GPT,3D64AD05-0A01-4998-9F4F-F557CF44AFD4,0x64028,0x3A321FE0)/VenMedia(BE74FCF7-0B7C-49F3-9147-01F4042E6842,AB628DA0825801439A7845D15782DE97)/\5BAECCBA-B862-4729-BD71-DD6119A7451D\System\Library\CoreServices\boot.efi
06:199 00:041 OCB: Adding bless entry on disk - PciRoot(0x0)/Pci(0x17,0x0)/Sata(0x4,0xFFFF,0x0)/HD(2,GPT,3D64AD05-0A01-4998-9F4F-F557CF44AFD4,0x64028,0x3A321FE0)/VenMedia(BE74FCF7-0B7C-49F3-9147-01F4042E6842,AB628DA0825801439A7845D15782DE97)
06:236 00:037 OCBP: APFS Volume Info - 5D130398 (131072, A08D62AB-5882-4301-9A78-45D15782DE97, 16)
06:256 00:020 OCBP: APFS Container Info - 5D131398 (1, EDA04B6D-B5D4-4493-A566-F62F01A7AAF9)
06:276 00:020 OCBP: BlessedFileHEX (1/5 264) - 02 01 0C 00 D0 41 03 0A 00 00 00 00 01 01 06 00 00 17 03 12 0A 00 04 00 FF FF 00 00 04 01 2A 00 02 00 00 00 28 40 06 00 00 00 00 00 E0 1F 32 3A 00 00 00 00 05 AD 64 3D 01 0A 98 49 9F 4F F5 57
06:313 00:036 OCBP: BlessedFileHEX (2/5 264) - CF 44 AF D4 02 02 04 03 24 00 F7 FC 74 BE 7C 0B F3 49 91 47 01 F4 04 2E 68 42 AB 62 8D A0 82 58 01 43 9A 78 45 D1 57 82 DE 97 04 04 9A 00 5C 00 35 00 42 00 41 00 45 00 43 00 43 00 42 00 41 00
06:350 00:037 OCBP: BlessedFileHEX (3/5 264) - 2D 00 42 00 38 00 36 00 32 00 2D 00 34 00 37 00 32 00 39 00 2D 00 42 00 44 00 37 00 31 00 2D 00 44 00 44 00 36 00 31 00 31 00 39 00 41 00 37 00 34 00 35 00 31 00 44 00 5C 00 53 00 79 00 73 00
06:387 00:037 OCBP: BlessedFileHEX (4/5 264) - 74 00 65 00 6D 00 5C 00 4C 00 69 00 62 00 72 00 61 00 72 00 79 00 5C 00 43 00 6F 00 72 00 65 00 53 00 65 00 72 00 76 00 69 00 63 00 65 00 73 00 5C 00 62 00 6F 00 6F 00 74 00 2E 00 65 00 66 00
06:424 00:036 OCBP: BlessedFileHEX (5/5 264) - 69 00 00 00 7F FF 04 00
06:443 00:019 OCBP: BlessedFileDP - PciRoot(0x0)/Pci(0x17,0x0)/Sata(0x4,0xFFFF,0x0)/HD(2,GPT,3D64AD05-0A01-4998-9F4F-F557CF44AFD4,0x64028,0x3A321FE0)/VenMedia(BE74FCF7-0B7C-49F3-9147-01F4042E6842,AB628DA0825801439A7845D15782DE97)/\5BAECCBA-B862-4729-BD71-DD6119A7451D\System\Library\CoreServices\boot.efi
06:482 00:039 OCBP: Blessed file is valid
06:500 00:018 OCBP: 10 filesystems for APFS - Success
06:529 00:028 OCBP: APFS Volume Info - 5D131F98 (131072, A08D62AB-5882-4301-9A78-45D15782DE97, 16)
06:549 00:020 OCBP: APFS Container Info - 5D130B18 (1, EDA04B6D-B5D4-4493-A566-F62F01A7AAF9)
06:569 00:020 OCBP: APFS match container EDA04B6D-B5D4-4493-A566-F62F01A7AAF9 vs EDA04B6D-B5D4-4493-A566-F62F01A7AAF9 for 5 of 10 - 1
06:591 00:021 OCBP: Missing partition A08D62AB-5882-4301-9A78-45D15782DE97 on preboot - Not Found
06:611 00:020 OCBP: No APFS booter 5 of 10 for A08D62AB-5882-4301-9A78-45D15782DE97 - Not Found
06:631 00:020 OCBP: APFS Volume Info - 5D139498 (131072, 5BAECCBA-B862-4729-BD71-DD6119A7451D, 64)
06:652 00:020 OCBP: APFS Container Info - 5D131F18 (1, EDA04B6D-B5D4-4493-A566-F62F01A7AAF9)
06:672 00:020 OCBP: APFS match container EDA04B6D-B5D4-4493-A566-F62F01A7AAF9 vs EDA04B6D-B5D4-4493-A566-F62F01A7AAF9 for 6 of 10 - 1
06:694 00:021 OCBP: Found partition 5BAECCBA-B862-4729-BD71-DD6119A7451D on preboot
06:714 00:020 OCBP: Want predefined list for APFS 16 at 5BAECCBA-B862-4729-BD71-DD6119A7451D
06:734 00:020 OCBP: Predefined 5BAECCBA-B862-4729-BD71-DD6119A7451D \System\Library\CoreServices\boot.efi was found
06:755 00:021 OCBP: Found APFS booter 6 of 10 for 5BAECCBA-B862-4729-BD71-DD6119A7451D (5F7D2310)
06:776 00:020 OCBP: APFS Volume Info - 5D131C18 (131072, CFA44E46-00E5-41A1-86C4-A7B32F841A2A, 4)
06:796 00:020 OCBP: APFS Container Info - 5D131C98 (1, EDA04B6D-B5D4-4493-A566-F62F01A7AAF9)
06:816 00:020 OCBP: APFS match container EDA04B6D-B5D4-4493-A566-F62F01A7AAF9 vs EDA04B6D-B5D4-4493-A566-F62F01A7AAF9 for 7 of 10 - 1
06:838 00:021 OCBP: Missing partition CFA44E46-00E5-41A1-86C4-A7B32F841A2A on preboot - Not Found
06:858 00:020 OCBP: No APFS booter 7 of 10 for CFA44E46-00E5-41A1-86C4-A7B32F841A2A - Not Found
06:878 00:020 OCBP: APFS Volume Info - 5D131C98 (131072, 4FCF2B07-084E-44AD-87A7-82541C7DC168, 1)
06:898 00:020 OCBP: APFS Container Info - 5D139498 (1, EDA04B6D-B5D4-4493-A566-F62F01A7AAF9)
06:918 00:020 OCBP: APFS match container EDA04B6D-B5D4-4493-A566-F62F01A7AAF9 vs EDA04B6D-B5D4-4493-A566-F62F01A7AAF9 for 8 of 10 - 1
06:940 00:021 OCBP: Missing partition 4FCF2B07-084E-44AD-87A7-82541C7DC168 on preboot - Not Found
06:960 00:020 OCBP: No APFS booter 8 of 10 for 4FCF2B07-084E-44AD-87A7-82541C7DC168 - Not Found
06:981 00:020 OCBP: APFS Volume Info - 5D131F18 (131072, 84EE47AB-88A0-48F6-9817-D9AD9BC944D7, 192)
07:001 00:020 OCBP: APFS Container Info - 5D118A98 (1, EDA04B6D-B5D4-4493-A566-F62F01A7AAF9)
07:022 00:020 OCBP: APFS match container EDA04B6D-B5D4-4493-A566-F62F01A7AAF9 vs EDA04B6D-B5D4-4493-A566-F62F01A7AAF9 for 9 of 10 - 1
07:043 00:021 OCBP: Missing partition 84EE47AB-88A0-48F6-9817-D9AD9BC944D7 on preboot - Not Found
07:064 00:020 OCBP: No APFS booter 9 of 10 for 84EE47AB-88A0-48F6-9817-D9AD9BC944D7 - Not Found
07:084 00:020 OCBP: APFS Volume Info - 5D118498 (131072, 7D21D63B-9E59-4206-9D7B-E5ACF1BE94B4, 8)
07:104 00:020 OCBP: APFS Container Info - 5D130D98 (1, EDA04B6D-B5D4-4493-A566-F62F01A7AAF9)
07:124 00:020 OCBP: APFS match container EDA04B6D-B5D4-4493-A566-F62F01A7AAF9 vs EDA04B6D-B5D4-4493-A566-F62F01A7AAF9 for 10 of 10 - 1
07:146 00:021 OCBP: Missing partition 7D21D63B-9E59-4206-9D7B-E5ACF1BE94B4 on preboot - Not Found
07:166 00:020 OCBP: No APFS booter 10 of 10 for 7D21D63B-9E59-4206-9D7B-E5ACF1BE94B4 - Not Found
07:187 00:020 OCBP: APFS bless for EDA04B6D-B5D4-4493-A566-F62F01A7AAF9:<null string> is Success
07:207 00:020 OCB: Adding entry type (T:2|F:0|G:0) - PciRoot(0x0)/Pci(0x17,0x0)/Sata(0x4,0xFFFF,0x0)/HD(2,GPT,3D64AD05-0A01-4998-9F4F-F557CF44AFD4,0x64028,0x3A321FE0)/VenMedia(BE74FCF7-0B7C-49F3-9147-01F4042E6842,AB628DA0825801439A7845D15782DE97)/\5BAECCBA-B862-4729-BD71-DD6119A7451D\System\Library\CoreServices\boot.efi
07:247 00:040 OCB: Get visibility for boot entry 5BAECCBA-B862-4729-BD71-DD6119A7451D\ - Not Found
07:267 00:020 OCB: Discarding already present DP
07:286 00:018 OCBP: APFS Container Info - 5D130D18 (1, EDA04B6D-B5D4-4493-A566-F62F01A7AAF9)
07:306 00:020 OCBP: 10 filesystems for APFS - Success
07:327 00:021 OCBP: APFS Volume Info - 5D130398 (131072, A08D62AB-5882-4301-9A78-45D15782DE97, 16)
07:348 00:020 OCBP: APFS Container Info - 5D118498 (1, EDA04B6D-B5D4-4493-A566-F62F01A7AAF9)
07:368 00:020 OCBP: APFS match container EDA04B6D-B5D4-4493-A566-F62F01A7AAF9 vs EDA04B6D-B5D4-4493-A566-F62F01A7AAF9 for 5 of 10 - 1
07:390 00:021 OCBP: Missing partition A08D62AB-5882-4301-9A78-45D15782DE97 on preboot - Not Found
07:410 00:020 OCBP: No APFS booter 5 of 10 for A08D62AB-5882-4301-9A78-45D15782DE97 - Not Found
07:430 00:020 OCBP: APFS Volume Info - 5D130398 (131072, 5BAECCBA-B862-4729-BD71-DD6119A7451D, 64)
07:450 00:020 OCBP: APFS Container Info - 5D118498 (1, EDA04B6D-B5D4-4493-A566-F62F01A7AAF9)
07:471 00:020 OCBP: APFS match container EDA04B6D-B5D4-4493-A566-F62F01A7AAF9 vs EDA04B6D-B5D4-4493-A566-F62F01A7AAF9 for 6 of 10 - 1
07:492 00:021 OCBP: Found partition 5BAECCBA-B862-4729-BD71-DD6119A7451D on preboot
07:512 00:019 OCBP: Want predefined list for APFS 16 at 5BAECCBA-B862-4729-BD71-DD6119A7451D
07:532 00:020 OCBP: Predefined 5BAECCBA-B862-4729-BD71-DD6119A7451D \System\Library\CoreServices\boot.efi was found
07:553 00:020 OCBP: Found APFS booter 6 of 10 for 5BAECCBA-B862-4729-BD71-DD6119A7451D (0)
07:573 00:019 OCBP: APFS Volume Info - 5D130618 (131072, CFA44E46-00E5-41A1-86C4-A7B32F841A2A, 4)
07:593 00:020 OCBP: APFS Container Info - 5D130998 (1, EDA04B6D-B5D4-4493-A566-F62F01A7AAF9)
07:613 00:020 OCBP: APFS match container EDA04B6D-B5D4-4493-A566-F62F01A7AAF9 vs EDA04B6D-B5D4-4493-A566-F62F01A7AAF9 for 7 of 10 - 1
07:636 00:022 OCBP: Missing partition CFA44E46-00E5-41A1-86C4-A7B32F841A2A on preboot - Not Found
07:657 00:020 OCBP: No APFS booter 7 of 10 for CFA44E46-00E5-41A1-86C4-A7B32F841A2A - Not Found
07:677 00:020 OCBP: APFS Volume Info - 5D130618 (131072, 4FCF2B07-084E-44AD-87A7-82541C7DC168, 1)
07:697 00:020 OCBP: APFS Container Info - 5D130998 (1, EDA04B6D-B5D4-4493-A566-F62F01A7AAF9)
07:717 00:020 OCBP: APFS match container EDA04B6D-B5D4-4493-A566-F62F01A7AAF9 vs EDA04B6D-B5D4-4493-A566-F62F01A7AAF9 for 8 of 10 - 1
07:739 00:021 OCBP: Missing partition 4FCF2B07-084E-44AD-87A7-82541C7DC168 on preboot - Not Found
07:759 00:020 OCBP: No APFS booter 8 of 10 for 4FCF2B07-084E-44AD-87A7-82541C7DC168 - Not Found
07:779 00:020 OCBP: APFS Volume Info - 5D130618 (131072, 84EE47AB-88A0-48F6-9817-D9AD9BC944D7, 192)
07:799 00:020 OCBP: APFS Container Info - 5D130998 (1, EDA04B6D-B5D4-4493-A566-F62F01A7AAF9)
07:819 00:020 OCBP: APFS match container EDA04B6D-B5D4-4493-A566-F62F01A7AAF9 vs EDA04B6D-B5D4-4493-A566-F62F01A7AAF9 for 9 of 10 - 1
07:841 00:021 OCBP: Missing partition 84EE47AB-88A0-48F6-9817-D9AD9BC944D7 on preboot - Not Found
07:862 00:020 OCBP: No APFS booter 9 of 10 for 84EE47AB-88A0-48F6-9817-D9AD9BC944D7 - Not Found
07:882 00:020 OCBP: APFS Volume Info - 5D130618 (131072, 7D21D63B-9E59-4206-9D7B-E5ACF1BE94B4, 8)
07:903 00:020 OCBP: APFS Container Info - 5D130998 (1, EDA04B6D-B5D4-4493-A566-F62F01A7AAF9)
07:923 00:020 OCBP: APFS match container EDA04B6D-B5D4-4493-A566-F62F01A7AAF9 vs EDA04B6D-B5D4-4493-A566-F62F01A7AAF9 for 10 of 10 - 1
07:945 00:022 OCBP: Missing partition 7D21D63B-9E59-4206-9D7B-E5ACF1BE94B4 on preboot - Not Found
07:966 00:020 OCBP: No APFS booter 10 of 10 for 7D21D63B-9E59-4206-9D7B-E5ACF1BE94B4 - Not Found
07:986 00:020 OCBP: APFS bless for EDA04B6D-B5D4-4493-A566-F62F01A7AAF9:5BAECCBA-B862-4729-BD71-DD6119A7451D\System\Library\CoreServices\ is Success
08:008 00:022 OCBP: APFS Volume Info - 5D130D18 (131072, 5BAECCBA-B862-4729-BD71-DD6119A7451D, 64)
08:029 00:020 OCBP: APFS Container Info - 5D131398 (1, EDA04B6D-B5D4-4493-A566-F62F01A7AAF9)
08:049 00:020 OCBP: APFS recovery info 0/10 due to 00000000-0000-0000-0000-000000000000/EDA04B6D-B5D4-4493-A566-F62F01A7AAF9/0 - Not Found
08:072 00:023 OCBP: APFS recovery info 1/10 due to 00000000-0000-0000-0000-000000000000/EDA04B6D-B5D4-4493-A566-F62F01A7AAF9/0 - Not Found
08:095 00:022 OCBP: APFS recovery info 2/10 due to 00000000-0000-0000-0000-000000000000/EDA04B6D-B5D4-4493-A566-F62F01A7AAF9/0 - Not Found
08:117 00:021 OCBP: APFS recovery info 3/10 due to 00000000-0000-0000-0000-000000000000/EDA04B6D-B5D4-4493-A566-F62F01A7AAF9/0 - Not Found
08:138 00:021 OCBP: APFS Volume Info - 5D130D18 (131072, A08D62AB-5882-4301-9A78-45D15782DE97, 16)
08:159 00:020 OCBP: APFS Container Info - 5D130618 (1, EDA04B6D-B5D4-4493-A566-F62F01A7AAF9)
08:179 00:020 OCBP: APFS recovery info 4/10 due to EDA04B6D-B5D4-4493-A566-F62F01A7AAF9/EDA04B6D-B5D4-4493-A566-F62F01A7AAF9/10 - Success
08:201 00:021 OCBP: APFS Volume Info - 5D130618 (131072, 5BAECCBA-B862-4729-BD71-DD6119A7451D, 64)
08:221 00:020 OCBP: APFS Container Info - 5D130D18 (1, EDA04B6D-B5D4-4493-A566-F62F01A7AAF9)
08:241 00:020 OCBP: APFS recovery info 5/10 due to EDA04B6D-B5D4-4493-A566-F62F01A7AAF9/EDA04B6D-B5D4-4493-A566-F62F01A7AAF9/40 - Success
08:264 00:022 OCBP: APFS Volume Info - 5D130D18 (131072, CFA44E46-00E5-41A1-86C4-A7B32F841A2A, 4)
08:285 00:020 OCBP: APFS Container Info - 5D130618 (1, EDA04B6D-B5D4-4493-A566-F62F01A7AAF9)
08:305 00:020 OCBP: APFS recovery info 6/10 due to EDA04B6D-B5D4-4493-A566-F62F01A7AAF9/EDA04B6D-B5D4-4493-A566-F62F01A7AAF9/4 - Success
08:327 00:021 OCFS: Filename \5BAECCBA-B862-4729-BD71-DD6119A7451D\ has trailing slash
08:346 00:019 OCFS: Filename \5BAECCBA-B862-4729-BD71-DD6119A7451D\ has trailing slash
08:366 00:019 OCB: Matched fs 5F6B2918
08:384 00:017 OCB: Adding entry type (T:1|F:1|G:0) - PciRoot(0x0)/Pci(0x17,0x0)/Sata(0x4,0xFFFF,0x0)/HD(2,GPT,3D64AD05-0A01-4998-9F4F-F557CF44AFD4,0x64028,0x3A321FE0)/VenMedia(BE74FCF7-0B7C-49F3-9147-01F4042E6842,464EA4CFE500A14186C4A7B32F841A2A)/\5BAECCBA-B862-4729-BD71-DD6119A7451D\
08:424 00:039 OCB: Get visibility for boot entry 5BAECCBA-B862-4729-BD71-DD6119A7451D\ - Not Found
08:446 00:022 OCB: Registering entry Recovery 15.0 [AppleRecv:Apple] (T:4|F:1|G:0|E:0|B:0) - PciRoot(0x0)/Pci(0x17,0x0)/Sata(0x4,0xFFFF,0x0)/HD(2,GPT,3D64AD05-0A01-4998-9F4F-F557CF44AFD4,0x64028,0x3A321FE0)/VenMedia(BE74FCF7-0B7C-49F3-9147-01F4042E6842,464EA4CFE500A14186C4A7B32F841A2A)/\5BAECCBA-B862-4729-BD71-DD6119A7451D\
08:486 00:040 OCB: Processing blessed list
08:505 00:018 OCB: Adding bless entry on disk - PciRoot(0x0)/Pci(0x6,0x0)/Pci(0x0,0x0)/NVMe(0x1,EC-68-3F-4E-8B-44-1B-00)/HD(1,GPT,050AA326-9EE4-4F0F-9A75-A86031801B50,0x1000,0x96000)
08:529 00:023 OCBP: Blessed file is missing
08:547 00:018 OCBP: Blessed folder is missing
08:565 00:018 OCBP: Predefined <nil> \System\Library\CoreServices\boot.efi is missing - Not Found
08:586 00:020 OCBP: Predefined <nil> \EFI\Microsoft\Boot\bootmgfw.efi is missing - Not Found
08:606 00:020 OCBP: Predefined <nil> \EFI\BOOT\BOOTX64.EFI was found
08:626 00:019 OCB: Adding entry type (T:1|F:0|G:1) - PciRoot(0x0)/Pci(0x6,0x0)/Pci(0x0,0x0)/NVMe(0x1,EC-68-3F-4E-8B-44-1B-00)/HD(1,GPT,050AA326-9EE4-4F0F-9A75-A86031801B50,0x1000,0x96000)/\EFI\BOOT\BOOTX64.EFI
08:651 00:025 OCB: Get visibility for boot entry <null string> - Not Found
08:670 00:019 OCB: Trying to detect Microsoft BCD
08:689 00:018 OCB: Registering entry NO NAME [Auto] (T:1|F:0|G:1|E:0|B:0) - PciRoot(0x0)/Pci(0x6,0x0)/Pci(0x0,0x0)/NVMe(0x1,EC-68-3F-4E-8B-44-1B-00)/HD(1,GPT,050AA326-9EE4-4F0F-9A75-A86031801B50,0x1000,0x96000)/\EFI\BOOT\BOOTX64.EFI
08:725 00:036 OCBP: APFS recovery volume handle missing - \EFI\BOOT\
08:745 00:019 OCB: APFS recovery is not present - Not Found
08:764 00:018 LNX: TypeGUID: C12A7328-F81F-11D2-BA4B-00A0C93EC93B (ESP) PARTUUID: 050AA326-9EE4-4F0F-9A75-A86031801B50
08:785 00:021 LNX: ScanLoaderEntries \ - Not Found
08:805 00:019 OCB: Adding bless entry on disk - PciRoot(0x0)/Pci(0x17,0x0)/Sata(0x4,0xFFFF,0x0)/HD(1,GPT,3850C186-C2AB-4525-835E-B677625E099C,0x28,0x64000)
08:828 00:023 OCBP: Blessed file is missing
08:846 00:018 OCBP: Blessed folder is missing
08:865 00:018 OCBP: Predefined <nil> \System\Library\CoreServices\boot.efi is missing - Not Found
08:886 00:020 OCBP: Predefined <nil> \EFI\Microsoft\Boot\bootmgfw.efi is missing - Not Found
08:908 00:021 OCBP: Predefined <nil> \EFI\BOOT\BOOTX64.EFI was found
08:928 00:020 OCB: Adding entry type (T:1|F:0|G:1) - PciRoot(0x0)/Pci(0x17,0x0)/Sata(0x4,0xFFFF,0x0)/HD(1,GPT,3850C186-C2AB-4525-835E-B677625E099C,0x28,0x64000)/\EFI\BOOT\BOOTX64.EFI
08:954 00:026 OCB: Get visibility for boot entry - Success
08:973 00:018 OCB: Discarding disabled entry by visibility
08:991 00:018 OCBP: APFS recovery volume handle missing - \EFI\BOOT\
09:011 00:019 OCB: APFS recovery is not present - Not Found
09:030 00:019 LNX: TypeGUID: C12A7328-F81F-11D2-BA4B-00A0C93EC93B (ESP) PARTUUID: 3850C186-C2AB-4525-835E-B677625E099C
09:052 00:021 LNX: ScanLoaderEntries \ - Not Found
09:074 00:022 LNX: TypeGUID: C12A7328-F81F-11D2-BA4B-00A0C93EC93B (ESP) PARTUUID: 3556F94A-EDAD-4473-AD7F-9D2D9ED43E25
09:096 00:021 LNX: ScanLoaderEntries \ - Not Found
09:116 00:019 LNX: ScanLoaderEntries \boot - Not Found
09:136 00:019 LNX: AutodetectLinux not root fs - Not Found
09:154 00:018 LNX: AutodetectLinux \boot - Not Found
09:175 00:020 OCB: Adding bless entry on disk - PciRoot(0x0)/Pci(0x1D,0x0)/Pci(0x0,0x0)/NVMe(0x1,00-00-00-00-00-00-00-00)/HD(3,GPT,7B09B032-88FA-4C05-92D9-AFB7A7982511,0x3A800,0x77382800)
09:199 00:023 OCBP: Blessed file is missing
09:218 00:018 OCBP: Blessed folder is missing
09:237 00:018 OCBP: Predefined <nil> \System\Library\CoreServices\boot.efi is missing - Not Found
09:257 00:020 OCBP: Predefined <nil> \EFI\Microsoft\Boot\bootmgfw.efi is missing - Not Found
09:277 00:020 OCBP: Predefined <nil> \EFI\BOOT\BOOTX64.EFI is missing - Not Found
09:297 00:019 LNX: TypeGUID: EBD0A0A2-B9E5-4433-87C0-68B6B72699C7 (NTFS/FAT) PARTUUID: 7B09B032-88FA-4C05-92D9-AFB7A7982511
09:318 00:021 LNX: ScanLoaderEntries \ - Not Found
09:336 00:018 LNX: APFS - not scanning
09:354 00:018 OCB: Adding bless entry on disk - PciRoot(0x0)/Pci(0x17,0x0)/Sata(0x4,0xFFFF,0x0)/HD(2,GPT,3D64AD05-0A01-4998-9F4F-F557CF44AFD4,0x64028,0x3A321FE0)/VenMedia(BE74FCF7-0B7C-49F3-9147-01F4042E6842,BACCAE5B62B82947BD71DD6119A7451D)
09:391 00:036 OCBP: APFS Volume Info - 5F6B2718 (131072, 5BAECCBA-B862-4729-BD71-DD6119A7451D, 64)
09:412 00:020 OCBP: APFS Container Info - 5D118418 (1, EDA04B6D-B5D4-4493-A566-F62F01A7AAF9)
09:432 00:020 LNX: APFS - not scanning
09:450 00:017 OCB: Adding bless entry on disk - PciRoot(0x0)/Pci(0x17,0x0)/Sata(0x4,0xFFFF,0x0)/HD(2,GPT,3D64AD05-0A01-4998-9F4F-F557CF44AFD4,0x64028,0x3A321FE0)/VenMedia(BE74FCF7-0B7C-49F3-9147-01F4042E6842,464EA4CFE500A14186C4A7B32F841A2A)
09:487 00:036 OCBP: APFS Volume Info - 5D118398 (131072, CFA44E46-00E5-41A1-86C4-A7B32F841A2A, 4)
09:507 00:020 OCBP: APFS Container Info - 5CF03A18 (1, EDA04B6D-B5D4-4493-A566-F62F01A7AAF9)
09:527 00:020 LNX: APFS - not scanning
09:546 00:018 OCB: Adding bless entry on disk - PciRoot(0x0)/Pci(0x17,0x0)/Sata(0x4,0xFFFF,0x0)/HD(2,GPT,3D64AD05-0A01-4998-9F4F-F557CF44AFD4,0x64028,0x3A321FE0)/VenMedia(BE74FCF7-0B7C-49F3-9147-01F4042E6842,072BCF4F4E08AD4487A782541C7DC168)
09:583 00:037 OCBP: APFS Volume Info - 62437498 (131072, 4FCF2B07-084E-44AD-87A7-82541C7DC168, 1)
09:604 00:020 OCBP: APFS Container Info - 5CF03B98 (1, EDA04B6D-B5D4-4493-A566-F62F01A7AAF9)
09:624 00:020 LNX: APFS - not scanning
09:642 00:017 OCB: Adding bless entry on disk - PciRoot(0x0)/Pci(0x17,0x0)/Sata(0x4,0xFFFF,0x0)/HD(2,GPT,3D64AD05-0A01-4998-9F4F-F557CF44AFD4,0x64028,0x3A321FE0)/VenMedia(BE74FCF7-0B7C-49F3-9147-01F4042E6842,AB47EE84A088F6489817D9AD9BC944D7)
09:679 00:036 OCBP: APFS Volume Info - 62437418 (131072, 84EE47AB-88A0-48F6-9817-D9AD9BC944D7, 192)
09:699 00:020 OCBP: APFS Container Info - 5CF03698 (1, EDA04B6D-B5D4-4493-A566-F62F01A7AAF9)
09:719 00:020 LNX: APFS - not scanning
09:737 00:017 OCB: Adding bless entry on disk - PciRoot(0x0)/Pci(0x17,0x0)/Sata(0x4,0xFFFF,0x0)/HD(2,GPT,3D64AD05-0A01-4998-9F4F-F557CF44AFD4,0x64028,0x3A321FE0)/VenMedia(BE74FCF7-0B7C-49F3-9147-01F4042E6842,3BD6217D599E06429D7BE5ACF1BE94B4)
09:774 00:036 OCBP: APFS Volume Info - 5CF03718 (131072, 7D21D63B-9E59-4206-9D7B-E5ACF1BE94B4, 8)
09:794 00:020 OCBP: APFS Container Info - 5CF03798 (1, EDA04B6D-B5D4-4493-A566-F62F01A7AAF9)
09:814 00:020 LNX: APFS - not scanning
09:832 00:017 OCB: Adding custom entry OpenShell.efi (tool|B:0) -> OpenShell.efi
09:851 00:019 OCB: Registering entry OpenShell.efi [Auto] (T:128|F:0|G:0|E:0|B:0) - <nil>
09:872 00:020 BEP: Reset NVRAM entry, preserve boot 0, apple 0
09:891 00:019 OCB: Adding custom entry Reset NVRAM (action|B:1) -> <null string>
09:911 00:019 OCB: Registering entry Reset NVRAM [ResetNVRAM:NVRAMTool] (T:256|F:0|G:0|E:0|B:1) - <nil>
09:931 00:020 OCB: Showing menu... 
09:949 00:017 OCAU: PlayFile has no AudioIo or provider is unconfigured
09:969 00:019 OCHK: InitHotKeys
09:986 00:017 OCKM: Allocated key repeat context 5CF03518 5CF03918 5CF03998
10:006 00:019 OCAE: Set screen resolution to 3440x1440 - Success
10:025 00:019 OCTY: Registered handler
10:043 00:017 OCAE: Set screen resolution to 3440x1440 - Success
10:062 00:019 OCUI: Console attributes: 0
10:068 00:005 OCUI: UseDiskLabel: 0, UseGenericLabel: 0
10:074 00:006 OCB: Get volume icon for NO NAME <null string> - Not Found
10:080 00:005 OCUI: Console attributes: 0
10:086 00:005 OCUI: UseDiskLabel: 0, UseGenericLabel: 0
10:094 00:007 OCB: Get volume icon for Windows <null string> - Not Found
10:101 00:006 OCUI: Using flavour icon, custom: 0
10:107 00:005 OCUI: Console attributes: 0
10:112 00:005 OCUI: UseDiskLabel: 0, UseGenericLabel: 0
10:118 00:005 OCB: Get volume icon for Macintosh HD 5BAECCBA-B862-4729-BD71-DD6119A7451D\ - Not Found
10:124 00:005 OCUI: Console attributes: 0
10:130 00:005 OCUI: UseDiskLabel: 0, UseGenericLabel: 0
10:136 00:005 OCB: Get volume icon for Recovery 15.0 5BAECCBA-B862-4729-BD71-DD6119A7451D\ - Not Found
10:142 00:005 OCUI: Using flavour icon, custom: 0
10:148 00:005 OCUI: Console attributes: 0
10:154 00:005 OCUI: UseDiskLabel: 0, UseGenericLabel: 0
10:160 00:005 OCUI: Console attributes: 0
10:166 00:005 OCUI: UseDiskLabel: 0, UseGenericLabel: 0
10:198 00:031 OCAU: PlayFile has no AudioIo or provider is unconfigured
10:204 00:005 OCAU: PlayFile has no AudioIo or provider is unconfigured
10:210 00:006 OCAU: PlayFile has no AudioIo or provider is unconfigured
10:217 00:006 OCAU: PlayFile has no AudioIo or provider is unconfigured
10:223 00:005 OCAU: PlayFile has no AudioIo or provider is unconfigured
10:229 00:005 OCAU: PlayFile has no AudioIo or provider is unconfigured
10:235 00:005 OCAU: PlayFile has no AudioIo or provider is unconfigured
10:240 00:005 OCAU: PlayFile has no AudioIo or provider is unconfigured
10:246 00:005 OCAU: PlayFile has no AudioIo or provider is unconfigured
10:252 00:005 OCAU: PlayFile has no AudioIo or provider is unconfigured
10:258 00:005 OCAU: PlayFile has no AudioIo or provider is unconfigured
10:264 00:005 OCAU: PlayFile has no AudioIo or provider is unconfigured
10:270 00:005 OCAU: PlayFile has no AudioIo or provider is unconfigured
10:276 00:005 OCAU: PlayFile has no AudioIo or provider is unconfigured
10:282 00:005 OCAU: PlayFile has no AudioIo or provider is unconfigured
10:288 00:005 OCAU: Beep 1 200/150
10:294 00:005 OCAU: Beep has AudioIo not configured
11:284 00:990 OCAU: PlayFile has no AudioIo or provider is unconfigured
12:018 00:733 OCAU: PlayFile has no AudioIo or provider is unconfigured
12:024 00:005 OCAU: PlayFile has no AudioIo or provider is unconfigured
12:030 00:005 OCAU: PlayFile has no AudioIo or provider is unconfigured
12:778 00:748 OCHK: FreeHotKeys
12:796 00:017 OCTY: Unregistered handler
12:814 00:018 OCKM: Freeing key repeat context 5CF03518 5CF03918 5CF03998
12:833 00:019 OCB: Should boot from 3. Macintosh HD (T:2|F:0|G:0|E:0|DEF:1)
12:853 00:019 OCAU: PlayFile has no AudioIo or provider is unconfigured
12:872 00:019 OCAU: PlayFile has no AudioIo or provider is unconfigured
12:891 00:019 OCAU: PlayFile has no AudioIo or provider is unconfigured
12:911 00:019 OCAU: PlayFile has no AudioIo or provider is unconfigured
12:930 00:019 OCB: Matched default entry in BootOrder
12:949 00:018 OCB: Adding default entry Boot0080 to BootOrder
12:969 00:020 OCVAR: Locate emulated NVRAM protocol - Not Found
12:988 00:019 OCB: Setting default - Success
13:006 00:018 OCAU: PlayFile has no AudioIo or provider is unconfigured
13:026 00:019 OCAU: PlayFile has no AudioIo or provider is unconfigured
13:045 00:019 OCAU: PlayFile has no AudioIo or provider is unconfigured
13:064 00:019 OCB: Saved mode 0/0/0 - Success
13:082 00:018 OCB: Perform boot Macintosh HD to dp PciRoot(0x0)/Pci(0x17,0x0)/Sata(0x4,0xFFFF,0x0)/HD(2,GPT,3D64AD05-0A01-4998-9F4F-F557CF44AFD4,0x64028,0x3A321FE0)/VenMedia(BE74FCF7-0B7C-49F3-9147-01F4042E6842,AB628DA0825801439A7845D15782DE97)/\5BAECCBA-B862-4729-BD71-DD6119A7451D\System\Library\CoreServices\boot.efi (0/0)
13:122 00:040 OCABC: EfiBootRt candidate - PciRoot(0x0)/Pci(0x17,0x0)/Sata(0x4,0xFFFF,0x0)/HD(2,GPT,3D64AD05-0A01-4998-9F4F-F557CF44AFD4,0x64028,0x3A321FE0)/VenMedia(BE74FCF7-0B7C-49F3-9147-01F4042E6842,AB628DA0825801439A7845D15782DE97)/\5BAECCBA-B862-4729-BD71-DD6119A7451D\System\Library\CoreServices\boot.efi
13:162 00:039 OCABC: IsEfiBootRt 0 (BP 1, Apple 0)
13:183 00:021 OCSB: Secure boot is disabled, skipping
13:202 00:018 OCB: Arch filtering 5B8CC018(723512)->5B8CC018(723512) caps 0 - Success
13:222 00:019 OCB: Matching <>/0[0] args on type 2
13:240 00:018 OCABC: Recovering trashed GetMemoryMap pointer
13:246 00:005 OCABC: VMware Mac installed on 5CF03418 - Success
13:252 00:006 OCDM: RBAR using PciIo
13:259 00:006 OCDM: Setting RBAR to 0 inc 0 on 5/25
13:265 00:006 OCDM: RBAR control is E40, total 2 - Success
13:271 00:005 OCDM: Old BAR 0000000C 00000040 0000000C 00000044 00003001 70300000 - Success
13:277 00:005 OCDM: RBAR 1/2 supports 0x7F00, sizing 0 inc 0 results setting from 14 to 8
13:283 00:005 OCDM: RBAR 2/2 supports 0x1FE, sizing 0 inc 0 results setting from 8 to 1
13:289 00:005 OCDM: New BAR 0000000C 00000000 0000000C 00000000 00003001 70300000 - Success
13:295 00:005 OCDM: Reprogrammed BARs to original - Success
13:301 00:006 AAPL: #[EB.H.IS|!] Err(0xE) <- RT.GV boot-signature 7C436110-AB2A-4BBB-A880-FE41995C9F82
13:307 00:005 AAPL: #[EB.H.IS|!] Err(0xE) <- RT.GV boot-image-key 7C436110-AB2A-4BBB-A880-FE41995C9F82
13:313 00:005 AAPL: #[EB|H:IS] 0
13:319 00:006 AAPL: #[EB|LOG:INIT] 2024-10-12T18:02:14
13:325 00:005 AAPL: #[EB|VERSION] <"boot.efi 582~1023 (Official), built 2024-08-03T14:34:42-0700">
13:331 00:005 AAPL: #[EB|BUILD] <"BUILD-INFO[394]:{"DisplayName":"boot.efi","DisplayVersion":"582~1023","RecordUuid":"FE597825-EF1D-486A-BE36-3D9854842EC2","BuildTime":"2024-08-03T14:34:42-0700","ProjectName":"efiboot","ProductName":"boot.efi","SourceVersion":"582","BuildVersion":"1023","BuildConfiguration":"Release","BuildType":"Official","Compiler":"clang-1600.0.25.3","SdkVersion":"15.0","SdkBuild":"24A314","TargetArchitectures":"x86_64"}">
13:337 00:005 AAPL: #[EB.CFG.DEV|!] Err(0xE) <- RT.GV booter-strict-xmlparser 7C436110-AB2A-4BBB-A880-FE41995C9F82
13:343 00:005 AAPL: #[EB|CFG:DEV] r5 0x0 0x0
13:350 00:006 AAPL: #[EB|H:IS] 0
13:356 00:006 AAPL: #[EB|WL:MODE] 0
13:362 00:005 AAPL: #[EB|CFG:ARG] boot-save-log 0x0000000000000002 (0x0000000000000002 < 0xFFFFFFFFFFFFFFFF) default
13:368 00:005 AAPL: #[EB|CFG:ARG] wake-save-log 0x0000000000000002 (0x0000000000000002 < 0x0000000000000002) default
13:374 00:005 AAPL: #[EB|CFG:ARG] console       0x0000000000000001 (0x0000000000000001 < 0x0000000000000001) default
13:380 00:005 AAPL: #[EB|CFG:ARG] serial        0x0000000000000001 (0x0000000000000001 < 0x0000000000000000) default
13:386 00:005 AAPL: #[EB|CFG:ARG] preoslog      0x0000000000000001 (0x0000000000000001 < 0xFFFFFFFFFFFFFFFF) default
13:392 00:005 AAPL: #[EB|CFG:ARG] timestamps    0x0000000000000000 (0x0000000000000000 < 0xFFFFFFFFFFFFFFFF) default
13:398 00:005 AAPL: #[EB|CFG:ARG] log-level     0x0000000000000001 (0x0000000000000001 & 0x0000000000000021) default
13:404 00:005 AAPL: #[EB|CFG:ARG] breakpoint    0x0000000000000000 (0x0000000000000000 & 0x0000000000000000) default
13:410 00:005 AAPL: #[EB|CFG:ARG] kc-read-size  0x0000000000100000 (0x0000000000100000 < 0xFFFFFFFFFFFFFFFF) default
13:416 00:005 AAPL: #[EB|CFG:ARG] force-error   0x0000000000000000 (0x0000000000000000 & 0x0000000000000000) default
13:421 00:005 AAPL: #[EB|H:IS] 0
13:427 00:005 AAPL: #[EB|WL] 0 0 0x01 0x01   0 0x00
13:433 00:005 AAPL: #[EB|BRD:NV] Mac-7BA5B2D9E42DDD94
13:440 00:006 OCOS: OS set: <null> macOS 11.0
13:446 00:006 OCOS: OS set: Apple Inc. macOS 11.0
13:452 00:005 AAPL: #[EB|B:VAw]
13:458 00:005 AAPL: #[EB|B:IAw]
13:464 00:005 AAPL: #[EB|WL] 0 0 0x01 0x01   2 0x00
13:470 00:006 AAPL: #[EB.BST.IDT|+]
13:477 00:006 AAPL: #[EB.BST.IDT|-]
13:483 00:005 AAPL: #[EB|WL] 0 0 0x01 0x01   3 0x00
13:489 00:005 AAPL: #[EB|WL] 0 0 0x01 0x01   4 0x00
13:495 00:005 AAPL: #[EB|BRD:NV] Mac-7BA5B2D9E42DDD94
13:501 00:005 AAPL: #[EB|WL] 0 0 0x01 0x01   5 0x00
13:507 00:005 AAPL: #[EB.H.CHK|BM] 0x0000000000000000
13:513 00:005 AAPL: #[EB.H.LV|!] Err(0xE) <- RT.GV boot-signature 7C436110-AB2A-4BBB-A880-FE41995C9F82
13:519 00:005 AAPL: #[EB|WL] 0 0 0x01 0x01  23 0x0E
13:525 00:006 AAPL: #[EB.H.LV|!] Err(0xE) <- RT.GV boot-image-key 7C436110-AB2A-4BBB-A880-FE41995C9F82
13:532 00:006 AAPL: #[EB|WL] 0 0 0x01 0x01  24 0x0E
13:538 00:006 AAPL: #[EB.H.LV|!] Err(0xE) <- RT.GV boot-image 7C436110-AB2A-4BBB-A880-FE41995C9F82
13:544 00:006 AAPL: #[EB.H.LV|!] Err(0xE) <- RT.SV- boot-signature 7C436110-AB2A-4BBB-A880-FE41995C9F82
13:550 00:006 AAPL: #[EB.H.LV|!] Err(0xE) <- RT.SV- boot-image-key 7C436110-AB2A-4BBB-A880-FE41995C9F82
13:556 00:006 AAPL: #[EB.H.LV|!] Err(0xE) <- RT.SV- boot-image 7C436110-AB2A-4BBB-A880-FE41995C9F82
13:562 00:005 AAPL: #[EB|H:NOT]
13:568 00:006 AAPL: #[EB|SB:P] 0x0
13:576 00:007 AAPL: #[EB|LIMG:DP] Acpi(PNP0A03,0)/Pci(17|0)/SATA(4,FFFF)/HD(Part2,Sig3D64AD05-0A01-4998-9F4F-F557CF44AFD4)/VenMedia(BE74FCF7-0B7C-49F3-9147-01F4042E6842)
13:582 00:005 AAPL: #[EB|LIMG:FP] \5BAECCBA-B862-4729-BD71-DD6119A7451D\System\Library\CoreServices\boot.efi
13:588 00:005 AAPL: #[EB|LIMG:OPT] 
13:594 00:006 AAPL: #[EB.OPT.LXF|F] <"\\5BAECCBA-B862-4729-BD71-DD6119A7451D\\System\\Library\\CoreServices\\com.apple.Boot.plist">
13:600 00:005 AAPL: #[EB.LD.LF|IN] 0 1 <"\\5BAECCBA-B862-4729-BD71-DD6119A7451D\\System\\Library\\CoreServices\\com.apple.Boot.plist"> <"0">
13:606 00:005 AAPL: #[EB.LD.OFS|OPEN!] Err(0xE) <"\\5BAECCBA-B862-4729-BD71-DD6119A7451D\\System\\Library\\CoreServices\\com.apple.Boot.plist">
13:630 00:024 AAPL: #[EB.OPT.LXF|LF!] Err(0xE)
13:637 00:006 AAPL: #[EB.OPT.LXF|F] <"Library\\Preferences\\SystemConfiguration\\com.apple.Boot.plist">
13:643 00:005 AAPL: #[EB.LD.LF|IN] 0 1 <"Library\\Preferences\\SystemConfiguration\\com.apple.Boot.plist"> <"0">
13:650 00:007 AAPL: #[EB|KF] <"">
13:656 00:005 AAPL: #[EB|MBA:CL] <"">
13:662 00:005 AAPL: #[EB|MBA:NV] <"agdpmod=pikera -ctrsmt debug=0x100 keepsyms=1 revpatch=cpuname,sbvmm amfi=0x80 itlwm_cc=IL swd_panic=1">
13:668 00:005 AAPL: #[EB|MBA:KF] <"">
13:674 00:005 AAPL: #[EB|MBA:OUT] <"agdpmod=pikera -ctrsmt debug=0x100 keepsyms=1 revpatch=cpuname,sbvmm amfi=0x80 itlwm_cc=IL swd_panic=1">
13:680 00:005 AAPL: #[EB|OPT:BM] 0x80180
13:686 00:005 AAPL: #[EB.OPT.LXF|F] <"\\5BAECCBA-B862-4729-BD71-DD6119A7451D\\System\\Library\\CoreServices\\PlatformSupport.plist">
13:692 00:005 AAPL: #[EB.LD.LF|IN] 0 1 <"\\5BAECCBA-B862-4729-BD71-DD6119A7451D\\System\\Library\\CoreServices\\PlatformSupport.plist"> <"0">
13:699 00:006 AAPL: #[EB|P:CPR] N
13:705 00:005 AAPL: #[EB|P:MPI] N
13:711 00:005 AAPL: #[EB|P:BPI] N
13:716 00:005 AAPL: #[EB.OPT.RKS|!] Err(0xE) <- BS.LocP EDB4A040-6D8A-11EC-8FAD-3E22FB93ADCF
13:723 00:006 OCABC: MMIO devirt start
13:729 00:006 OCABC: MMIO devirt 0xC0000000 (0x10000 pages, 0x8000000000000001) skip 0
13:735 00:005 OCABC: MMIO devirt 0xFE000000 (0x11 pages, 0x8000000000000001) skip 0
13:741 00:005 OCABC: MMIO devirt 0xFEC00000 (0x1 pages, 0x8000000000000001) skip 0
13:747 00:005 OCABC: MMIO devirt 0xFED00000 (0x1 pages, 0x8000000000000001) skip 0
13:753 00:005 OCABC: MMIO devirt 0xFEE00000 (0x1 pages, 0x8000000000000001) skip 0
13:759 00:005 OCABC: MMIO devirt 0xFF000000 (0x1000 pages, 0x800000000000100D) skip 0
13:765 00:005 OCABC: MMIO devirt end, saved 278608 KB
13:771 00:005 AAPL: #[EB|KMR] 218304512
13:777 00:005 AAPL: #[EB.CS.CSKSD|+]
13:783 00:005 AAPL: #[EB.CS.CSKSD|!] Err(0xE) <- RT.GV boot-info-payload 8D63D4FE-BD3C-4AAD-881D-86FD974BC1DF
13:789 00:005 AAPL: #[EB|WL] 0 0 0x01 0x01   6 0x0E
13:795 00:005 AAPL: #[EB.CS.LFC|+]
13:801 00:005 AAPL: #[EB.LD.LF|IN] 0 1 <"System\\Library\\Caches\\com.apple.corestorage\\EncryptedRoot.plist.wipekey"> <"0">
13:815 00:014 AAPL: #[EB.FS.AGSVH|PU] 5BAECCBA-B862-4729-BD71-DD6119A7451D
13:822 00:006 AAPL: #[EB.FS.AGSVH|!] Err(0xE) <- BS.LocHB 59D76AE4-37E3-55A7-B460-EF13D46E6020
13:828 00:006 AAPL: #[EB.G.CS|-?] Ok(0)
13:845 00:016 AAPL: #[EB.LD.LF|IN] 0 1 <"<null string>"> <"1">
13:853 00:008 AAPL: #[EB.B.SBS|SZ] 723512
13:862 00:008 AAPL: #[EB|B:SHA] <259e240945a35624fda414e83bc172238d5ceba9>
13:868 00:005 AAPL: #[EB.WL.PWLFNV|!] Err(0xE) <- RT.GV wake-failure 7C436110-AB2A-4BBB-A880-FE41995C9F82
13:874 00:005 AAPL: #[EB.WL.DT|!] Err(0xE) <- EB.WL.PWLFNV
13:880 00:006 AAPL: #[EB|WL:DT] 0x0000a422
13:886 00:005 AAPL: #[EB.LD.LKC|D] <"boot\System\Library\KernelCollections\BootKernelExtensions.kc.development">
13:893 00:007 AAPL: #[EB.LD.OFS|OPEN!] Err(0xE) <"boot\\System\\Library\\KernelCollections\\BootKernelExtensions.kc.development">
13:899 00:005 AAPL: #[EB.LD.LKC|R.2] <"boot\System\Library\KernelCollections\BootKernelExtensions.kc">
14:121 00:221 OC: Kext reservation size info 582000 exe 2977000
14:127 00:006 OC: Trying 64-bit XNU hook on boot\System\Library\KernelCollections\BootKernelExtensions.kc
14:271 00:143 OC: Result of 64-bit XNU hook on boot\System\Library\KernelCollections\BootKernelExtensions.kc (00000000) is Success
14:281 00:010 OCAK: Read kernel version 24.0.0 (240000)
14:298 00:017 OCAK: 64-bit PanicKextDump replace count - 1
14:304 00:005 OCAK: [OK] Patch success kext dump
14:311 00:006 OCAK: [OK] Patch success CPUID release
14:317 00:006 OCAK: 64-bit PowerStateTimeout replace count - 0
14:323 00:005 OCAK: No inline power state patch - Not Found, trying fallback
14:333 00:009 OCAK: 64-bit PowerStateTimeout replace count - 1
14:339 00:005 OCAK: [OK] Patch success power state
14:345 00:006 OCAK: [OK] Found jettisoning fileset
14:352 00:006 OCAK: 64-bit Set core count to thread count replace count - 2
14:358 00:006 OCAK: Patching MSR 35h to 00180018 - Success
14:392 00:033 OCAK: 64-bit Set core per package count to 128 V2 replace count - 0
14:399 00:007 OCAK: 64-bit Set core per package count to 128 V1_5 replace count - 1
14:405 00:005 OCAK: Patching core per package count - Success
14:415 00:009 OCAK: BusFreq = 100517647Hz, BusFCvtt2n = 42728490212, BusFCvtn2t = 431720006
14:421 00:006 OCAK: TscFreq = 3417600000Hz, TscFCvtt2n = 1256720299, TscFCvtn2t = 14678480238
14:428 00:006 OCAK: 64-bit ProvideCurrentCpuInfoZeroMsrThreadCoreCount replace count - 2
14:454 00:025 OCAK: Patching invalid size 2CFF8 with 15DC000 for com.apple.iokit.IOSkywalkFamily
14:460 00:005 OCAK: Excluding com.apple.iokit.IOSkywalkFamily - VirtualBase FFFFFF80028E4000, MaxSize 3E000
14:466 00:006 OCAK: Found kext com.apple.iokit.IOSkywalkFamily (50B5B018) from link 50B5B020 to drop
14:472 00:005 OCAK: Erasing com.apple.iokit.IOSkywalkFamily from prelinked kext under dict index 3, plist 51448998, plist index 166
14:478 00:005 OC: Prelinked blocker (Exclude) result 1 for com.apple.iokit.IOSkywalkFamily (Allow IOSkywalk Downgrade) - Success
14:494 00:015 OCAK: Local relocs 689 on FFFFFF8003EC6000
14:500 00:006 OC: Prelinked injection Lilu.kext (V1.6.9 | Lilu.kext) - Success
14:506 00:005 OC: Prelinked injection Lilu.kext v1.6.9
14:513 00:006 OCAK: Patching invalid size 2000 with 1B46000 for com.apple.iokit.IOACPIFamily
14:522 00:009 OCAK: Local relocs 515 on FFFFFF8003EF5000
14:529 00:006 OC: Prelinked injection VirtualSMC.kext (V1.3.4) - Success
14:535 00:005 OC: Prelinked injection VirtualSMC.kext v1.3.4
14:543 00:008 OCAK: Local relocs 325 on FFFFFF8003F0F000
14:550 00:006 OC: Prelinked injection SMCProcessor.kext (V1.3.4 | SMCProcessor.kext) - Success
14:556 00:006 OC: Prelinked injection SMCProcessor.kext v1.3.4
14:564 00:008 OCAK: Local relocs 2593 on FFFFFF8003F1E000
14:576 00:011 OC: Prelinked injection SMCSuperIO.kext (V1.3.4 | SMCSuperIO.kext) - Success
14:582 00:005 OC: Prelinked injection SMCSuperIO.kext v1.3.4
14:589 00:006 OCAK: Patching invalid size 33000 with 16CC000 for com.apple.iokit.IOPCIFamily
14:597 00:008 OCAK: Patching invalid size DFE0 with 10B0000 for com.apple.kec.Libm
14:606 00:008 OCAK: Local relocs 377 on FFFFFF8003F41000
14:612 00:006 OC: Prelinked injection SMCRadeonSensors.kext (V2.3.0) - Success
14:618 00:005 OC: Prelinked injection SMCRadeonSensors.kext v2.3.0
14:627 00:008 OCAK: Local relocs 1922 on FFFFFF8003F4D000
14:635 00:008 OC: Prelinked injection WhateverGreen.kext (V1.6.8 | WhateverGreen.kext) - Success
14:641 00:005 OC: Prelinked injection WhateverGreen.kext v1.6.8
14:648 00:006 OCAK: Patching invalid size 15FF4 with 192E000 for com.apple.iokit.IONetworkingFamily
14:659 00:011 OCAK: Local relocs 457 on FFFFFF8003FD0000
14:666 00:006 OC: Prelinked injection AppleIGC.kext (V1.4d1 | AppleIGC.kext) - Success
14:672 00:006 OC: Prelinked injection AppleIGC.kext v1.4d1
14:683 00:011 OCAK: Local relocs 5892 on FFFFFF8003FF0000
14:700 00:017 OC: Prelinked injection AppleALC.kext (V1.9.2 | AppleALC.kext) - Success
14:706 00:005 OC: Prelinked injection AppleALC.kext v1.9.2
14:714 00:007 OCAK: Symbol __ZN9IOService19_RESERVEDIOService0Ev has 0-value
14:720 00:005 OCAK: Symbol __ZN9IOService19_RESERVEDIOService1Ev has 0-value
14:726 00:005 OCAK: Local relocs 304 on FFFFFF80041B6000
14:732 00:006 OC: Prelinked injection CpuTopologyRebuild.kext (V1.1.0 | CpuTopologyRebuild.kext) - Success
14:738 00:005 OC: Prelinked injection CpuTopologyRebuild.kext v1.1.0
14:744 00:006 OC: Prelinked injection USBMap.kext (V1.1) - Success
14:750 00:005 OC: Prelinked injection USBMap.kext v1.1
14:759 00:008 OCAK: Local relocs 315 on FFFFFF80041BD000
14:765 00:006 OC: Prelinked injection RestrictEvents.kext (V1.1.5 | RestrictEvents.kext) - Success
14:771 00:006 OC: Prelinked injection RestrictEvents.kext v1.1.5
14:780 00:008 OCAK: Local relocs 314 on FFFFFF80041CA000
14:786 00:006 OC: Prelinked injection BlueToolFixup.kext (V2.6.9) - Success
14:792 00:005 OC: Prelinked injection BlueToolFixup.kext v2.6.9
14:800 00:007 OCAK: Patching invalid size 74FF4 with 12AE000 for com.apple.iokit.IOUSBHostFamily
14:806 00:006 OCAK: Patching invalid size 4000 with 2772000 for com.apple.driver.AppleBusPowerController
14:812 00:006 OCAK: Patching invalid size 19FFE with 2369000 for com.apple.driver.AppleSMC
14:819 00:007 OCAK: Patching invalid size 2FFF with CC3000 for com.apple.driver.watchdog
14:828 00:008 OCAK: Patching invalid size 39FF1 with 245B000 for com.apple.driver.AppleMobileFileIntegrity
14:834 00:006 OCAK: Patching invalid size 9FF7 with 203E000 for com.apple.iokit.CoreAnalyticsFamily
14:842 00:008 OCAK: Patching invalid size 82000 with D8A000 for com.apple.kec.corecrypto
14:849 00:006 OCAK: Patching invalid size AFF8 with 1F63000 for com.apple.kext.CoreTrust
14:855 00:006 OCAK: Patching invalid size 25000 with 25CF000 for com.apple.security.AppleImage4
14:863 00:008 OCAK: Patching invalid size 3FFC with 214A000 for com.apple.driver.usb.AppleUSBCommon
14:871 00:007 OCAK: Dependency com.apple.driver.usb.AppleUSBHostPlatformProperties was not found for kext com.apple.iokit.IOUSBHostFamily
14:895 00:024 OCAK: Local relocs 740 on FFFFFF80041D4000
14:903 00:007 OC: Prelinked injection IntelBluetoothFirmware.kext (V2.5.0) - Success
14:908 00:005 OC: Prelinked injection IntelBluetoothFirmware.kext v2.5.0
14:917 00:008 OCAK: Local relocs 324 on FFFFFF8004CD1000
14:923 00:006 OC: Prelinked injection IntelBTPatcher.kext (V2.5.0) - Success
14:929 00:005 OC: Prelinked injection IntelBTPatcher.kext v2.5.0
14:936 00:007 OCAK: Patching invalid size 5000 with 16D3000 for com.apple.driver.mDNSOffloadUserClient
14:973 00:037 OCAK: Local relocs 7087 on FFFFFF8004CE1000
14:989 00:015 OC: Prelinked injection IOSkywalkFamily.kext (V1.0) - Success
14:995 00:005 OC: Prelinked injection IOSkywalkFamily.kext v1.0
15:003 00:007 OCAK: Patching invalid size 22FF5 with DBB000 for com.apple.driver.corecapture
15:095 00:092 OCAK: Local relocs 8897 on FFFFFF8004DAF000
15:112 00:016 OC: Prelinked injection IO80211FamilyLegacy.kext (V1200.12.2b1) - Success
15:118 00:005 OC: Prelinked injection IO80211FamilyLegacy.kext v1200.12.2b1
15:160 00:042 OCAK: Local relocs 6983 on FFFFFF8004FB9000
15:173 00:012 OC: Prelinked injection IO80211FamilyLegacy.kext\Contents\PlugIns\AirPortBrcmNIC.kext (V1400.1.1) - Success
15:180 00:006 OC: Prelinked injection IO80211FamilyLegacy.kext\Contents\PlugIns\AirPortBrcmNIC.kext v1400.1.1
15:199 00:019 OCAK: Local relocs 2754 on FFFFFF800585C000
15:208 00:008 OC: Prelinked injection AirportItlwm.kext (V2.3.0) - Success
15:214 00:005 OC: Prelinked injection AirportItlwm.kext v2.3.0
15:222 00:008 OCAK: Local relocs 307 on FFFFFF80067F6000
15:228 00:006 OC: Prelinked injection DebugEnhancer.kext (V1.1.0) - Success
15:234 00:005 OC: Prelinked injection DebugEnhancer.kext v1.1.0
15:243 00:008 OCAK: Local relocs 625 on FFFFFF8006800000
15:250 00:006 OC: Prelinked injection NVMeFix.kext (V1.1.1) - Success
15:256 00:005 OC: Prelinked injection NVMeFix.kext v1.1.1
15:266 00:009 OCAK: Local relocs 676 on FFFFFF800680D000
15:272 00:006 OC: Prelinked injection IntelMausiEthernet.kext (V2.5.4) - Success
15:278 00:005 OC: Prelinked injection IntelMausiEthernet.kext v2.5.4
15:284 00:005 OC: Prelink size 108253184 kext offset 64774144 reserved 43479040
15:291 00:006 OCAK: KC TEXT is 65536 bytes with 61800 Mach-O headers need 1464
15:317 00:026 OCAK: 64-bit RemoveUsbLimitIoP1 part 1 replace count - 1
15:323 00:005 OCAK: [OK] Patch success port com.apple.iokit.IOUSBHostFamily part 1
15:329 00:006 OCAK: 64-bit RemoveUsbLimitIoP1 part 2 replace count - 1
15:335 00:005 OCAK: [OK] Patch success port com.apple.iokit.IOUSBHostFamily part 2
15:342 00:007 OCAK: Patching invalid size 3CFFC with 1189000 for com.apple.driver.usb.AppleUSBXHCI
15:348 00:005 OCAK: 64-bit RemoveUsbLimitV2 replace count - 1
15:354 00:005 OCAK: [OK] Patch success com.apple.driver.usb.AppleUSBXHCI
15:361 00:007 OCAK: Patching invalid size 22FF5 with 1141000 for com.apple.driver.usb.AppleUSBXHCIPCI
15:367 00:005 OCAK: [OK] Skipping legacy port patch AppleUSBXHCIPCI on 240000
15:373 00:006 OCAK: 64-bit AppleIoMapper replace count - 1
15:379 00:005 OCAK: [OK] Patch success com.apple.iokit.IOPCIFamily AppleIoMapper
15:386 00:006 OCAK: Patching invalid size 2FFE with 236E000 for com.apple.driver.AppleSMBIOS
15:392 00:005 OCAK: 64-bit CustomSmbiosGuid replace count - 1
15:398 00:006 OCAK: [OK] SMBIOS Patch success
15:405 00:006 OCAK: Patching invalid size 77FF1 with 2B2D000 for com.apple.driver.AppleACPIPlatform
15:411 00:006 OCAK: 64-bit CustomSmbiosGuid replace count - 1
15:418 00:006 OCAK: [OK] SMBIOS Patch success
15:448 00:030 OC: Prelinked status - Success
15:462 00:013 AAPL: #[EB.LD.LKFS|-?] Ok(0)
15:468 00:005 AAPL: #[EB.LD.LKC|-?] Ok(0)
15:475 00:006 AAPL: #[EB|BST:REV1]
15:481 00:005 AAPL: #[EB|CSR:IN] 0x00000803
15:487 00:005 AAPL: #[EB|CSR:OUT] 0x00000803
15:493 00:005 AAPL: #[EB.BST.FBS|+]
15:499 00:006 AAPL: #[EB.BST.FBS|ADSZ] 0
15:505 00:005 AAPL: #[EB.BST.FBS|KSSZ] 0
15:511 00:005 AAPL: #[EB|SB:SBGMFNS] x86legacyap.im4m
15:517 00:005 AAPL: #[EB|RH:PF] usr\standalone\OS.dmg.root_hash
15:524 00:006 AAPL: #[EB|RH:MF] <"usr\\standalone\\OS.dmg.root_hash.x86legacyap.im4m">
15:530 00:006 AAPL: #[EB.LD.LF|IN] 0 1 <"usr\\standalone\\OS.dmg.root_hash"> <"0">
15:537 00:007 AAPL: #[EB.LD.LF|IN] 0 1 <"usr\\standalone\\OS.dmg.root_hash.x86legacyap.im4m"> <"0">
15:544 00:006 AAPL: #[EB.BST.FBS|RHPSZ] 229
15:550 00:005 AAPL: #[EB.BST.FBS|RHMSZ] 3658
15:556 00:005 OCSMC: SmcReadValue Key 4D535463 Size 1
15:562 00:005 OCSMC: SmcReadValue Key 4D534163 Size 2
15:568 00:006 AAPL: #[EB|LOG:DT] 2024-10-12T18:02:16
15:574 00:006 AAPL: #[EB|LOG:EXITBS:START] 2024-10-12T18:02:16
```
