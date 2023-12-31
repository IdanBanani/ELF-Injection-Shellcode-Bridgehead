Pull requests are welcomed.

- [ ] Try to run the given injection techniques code.
- [ ] Understand how each technique works
- [ ] Understand the attack vector and the different parts (stages) of the chain    
  (i.e the bridgehead shellcode, injection to process memory,LPE, when to create a new process etc.)
- [ ] Describe the need for a custom statically PIC compiled elf (Shared object library) loader shellcode.  
- [ ] Injection vs patching at runtime?
- [ ] Implement / imporve it by yourself.

# Research Papers and Articles
- [Linkers & Loaders](https://www.wh0rd.org/books/linkers-and-loaders/linkers_and_loaders.pdf) by John R. Levine (1999)
- [Using procfs to execute ELF without touching the disk](https://blog.entysec.com/2023-04-02-remote-elf-loading/)
- [The Nexus between Static and Position Independent Code](https://tmpout.sh/1/10/)
- [Enabling SHELF Loading in Chrome for fun and profit](https://tmpout.sh/2/5.html)
- [General Linux Process injection techniques](https://github.com/itaymigdal/awesome-injection#linux-injection)
  
# Projects and Code Repositories

## 2023
- [Playstation5 ELF Manipulation](https://github.com/astrelsky/libhijacker/blob/msg/libhijacker/source/elf/elf.cpp)

## 2022
- [NASM Linux x86_64 Pure Shared Library](https://github.com/therealdreg/nasm_linux_x86_64_pure_sharedlib)

## 2018
- ARM: [SamyGOso Next-Gen](https://github.com/openlgtv/samyGOso_ng/blob/master/core/samyGOso.c)
  - Based on 2014 ARM: [HideAndroidEmulator ADBI Hook System Call](https://github.com/MindMac/HideAndroidEmulator/blob/master/HITCON/DemoCode/adbi_hook_systemcall/hijack/hijack.c)
- [Reflective Injection for Linux](https://github.com/haidragon/ReflectiveInjection/blob/master/linux%E7%89%88/inject/src/inject.c)

## 2017
- [DarkElf - Linux ELF Injector](https://github.com/jordan9001/darkelf/tree/master)

## 2016
- [XHook JNI Hijack](https://github.com/hello2mao/XHook/blob/master/ref/jni/hijack_ref/hijack.c)
- [ReflectiveSOInjection](https://github.com/infosecguerrilla/ReflectiveSOInjection/)

## 2014
- [Insecurity - Elves for Linux](https://github.com/nima/insecurity/blob/master/elvez/elves.c)

# Appendix / Somewhat Related / Need to organize

## 2018
- [Saruman ELF Virus](https://github.com/elfmaster/saruman/blob/master/launcher.c)

## Miscellaneous
- [ElfMaster - ELF Internals projects (Injection, Patching etc.)](https://github.com/elfmaster)
- [DEF CON 31 - Revolutionizing ELF binary patching w Shiva - ElfMaster](https://www.youtube.com/watch?v=TDMWejaucdg)
- [CVE-2022-34918 Shellcode Generation](https://github.com/jiayy/android_vuln_poc-exp/blob/master/linux/CVE-2022-34918/generate_shellcode/gen_shellcode.sh)
- [DDexec - Linux Binary Execution Technique](https://github.com/arget13/DDexec-)
- [bhook - Android PLT Hook Library](https://github.com/bytedance/bhook)

- [vfsfitvnm/intruducer](https://github.com/vfsfitvnm/intruducer)
- [arget13/memdlopen](https://github.com/arget13/memdlopen)
- [Shared Library Injection in Android](https://shunix.com/shared-library-injection-in-android/)
- [Shellcode Android Internals CTF ex4](https://dev.to/wireless90/shellcode-android-internals-ctf-ex4-4357)
- [Paper: 46043 - Android System Tracing: A Real-Life Story](https://www.exploit-db.com/papers/46043)
- [ELF Shared Library Injection Forensics](https://engineering.backtrace.io/2016-04-14-elf-shared-library-injection-forensics/)
