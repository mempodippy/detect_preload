# detect_preload
Small C application designed to detect LD_PRELOAD malware via the libdl library functions.</br>
Most public LD_PRELOAD rootkits don't hook any of the libdl functions, so you can easily reveal any "hidden" malware on the system.</br>
<b>Usage:</b>
```
gcc detect_preload.c -o detect_preload
./detect_preload
```
