```("feel dead") is used as a magic number in the Linux reboot system call.[33] Other magic numbers to reboot the machine are 672274793, 85072278, 369367448 and 537993216 which in hex translate respectively to 0x28121969, 0x5121996, 0x16041998 and 0x20112000, the birth dates of Linus Torvalds and his three daughters.[34]``` - Wikipedia  

---

Compile it with:

bash
```
gcc feeldead.c -o feeldead
```

Then run it as root:

bash
```
sudo ./feeldead
```
