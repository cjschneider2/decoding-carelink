## do stuff with an insulin pump over RF
using ` Namespace(begin=None, bytesPerRecord=None, command='tweak', descr=None, dryrun=False, effectTime=None, end=None, init=False, maxRecords=None, name=None, no_postlude=False, no_prelude=False, no_rf_prelude=False, other='ReadGlucoseHistory', page=1, params=None, port='/dev/ttyUSB0', postfix=None, prefix=None, prefix_path='logs/20140501_225446-pg-1-', save=True, saveall=False, serial='584923', verbose=None) `
```
```
```
```
```
```
```
```
```javascript
{'radio': {'errors.crc': 0,
           'errors.naks': 0,
           'errors.sequence': 0,
           'errors.timeouts': 0,
           'packets.received': 106L,
           'packets.transmit': 110L},
 'usb': {'errors.crc': 0,
         'errors.naks': 0,
         'errors.sequence': 0,
         'errors.timeouts': 0,
         'packets.received': 154L,
         'packets.transmit': 154L}}
```
```
```
### PUMP MODEL: `ReadPumpModel:size[64]:data:'722'`
<class 'decocare.commands.ReadGlucoseHistory'> {'page': 1}
response: ReadGlucoseHistory:size[1024]:[page][0]:data[1024]:
hexdump:
```python
0000   0x2b 0x2a 0x28 0x27 0x27 0x29 0x2b 0x2e    +*('')+.
0008   0x31 0x35 0x39 0x3c 0x3f 0x8a 0x0e 0x0a    159<?...
0010   0xa8 0x09 0x0e 0x44 0x47 0x45 0xcb 0x0c    ...DGE..
0018   0x0e 0x0a 0xb6 0x09 0x0f 0x46 0x46 0x47    .....FFG
0020   0x48 0x48 0x49 0x4b 0x4b 0x4a 0x4b 0x4b    HHIKKJKK
0028   0x48 0x45 0x44 0x44 0x45 0x44 0x44 0x45    HEDDEDDE
0030   0x46 0x45 0x44 0x43 0x43 0x44 0x45 0x44    FEDCCDED
0038   0x43 0x42 0x43 0x44 0x46 0x48 0x4a 0x4c    CBCDFHJL
0040   0x4d 0x4e 0x4e 0x4e 0x4d 0x4c 0x4c 0x4b    MNNNMLLK
0048   0x49 0x46 0x43 0x42 0x42 0x41 0x3e 0x39    IFCBBA>9
0050   0x36 0x33 0x2f 0x2b 0x28 0x25 0x22 0x1f    63/+(%".
0058   0x1c 0x1a 0x18 0x3e 0x0e 0x0a 0x86 0x0f    ...>....
0060   0x0e 0x17 0x18 0x1a 0x66 0x0d 0x0e 0x0a    ....f...
0068   0x94 0x0f 0x0f 0x1c 0x20 0x24 0x28 0x2c    .... $(,
0070   0x2e 0x30 0x31 0x31 0x31 0x31 0x31 0x32    .0111112
0078   0x32 0x32 0x34 0x33 0x32 0x30 0x2e 0x2c    224320.,
0080   0x2b 0x2b 0x2e 0x2f 0x2e 0x2c 0x2b 0x2c    ++./.,+,
0088   0x2f 0x32 0x34 0x36 0x37 0x37 0x37 0x36    /2467776
0090   0x34 0x32 0x66 0x0e 0x0a 0xa3 0x12 0x0e    42f.....
0098   0x30 0x2f 0x2f 0x64 0x0e 0x0e 0x0a 0xb3    0//d....
00A0   0x12 0x0f 0x2e 0x2e 0x2d 0x2c 0x29 0x26    ....-,)&
00A8   0x23 0x21 0x22 0x23 0x25 0x26 0x27 0x28    #!"#%&'(
00B0   0x28 0x29 0x2b 0x2d 0x2e 0x2e 0x2d 0x2d    ()+-..--
00B8   0x2e 0x2f 0x30 0x2e 0x2d 0x2c 0x2c 0x2e    ./0.-,,.
00C0   0x34 0x3a 0x3e 0x43 0x47 0x48 0x4a 0x49    4:>CGHJI
00C8   0x47 0x44 0x41 0x87 0x0e 0x0a 0x91 0x16    GDA.....
00D0   0x0e 0x40 0x3f 0x41 0x1f 0x0f 0x0e 0x0a    .@?A....
00D8   0x9d 0x16 0x0f 0x3e 0x3a 0x36 0x32 0x2e    ...>:62.
00E0   0x2b 0x29 0x27 0x26 0x25 0x24 0x23 0x22    +)'&%$#"
00E8   0x23 0x24 0x25 0x25 0x25 0x25 0x24 0x24    #$%%%%$$
00F0   0x23 0x23 0x22 0x21 0x21 0x21 0x20 0x20    ##"!!!  
00F8   0x1f 0x1f 0x1f 0x1f 0x21 0x22 0x23 0x24    ....!"#$
0100   0x25 0x26 0x27 0x28 0x2a 0x2c 0x2e 0x30    %&'(*,.0
0108   0x32 0x33 0x34 0x34 0x35 0x36 0x37 0x37    23445677
0110   0x37 0x38 0x38 0x36 0x34 0x30 0x2e 0x2d    788640.-
0118   0x2f 0x30 0x31 0x32 0x33 0x33 0x34 0x35    /0123345
0120   0x39 0x3b 0x3a 0x3a 0x39 0x37 0x36 0x36    9;::9766
0128   0x36 0x36 0x36 0x35 0x34 0x33 0x32 0x32    66654322
0130   0x32 0x33 0x33 0x33 0x33 0x32 0x32 0x33    23333223
0138   0x34 0x13 0x35 0x13 0x35 0x13 0x35 0x35    4.5.5.55
0140   0x34 0x32 0x31 0x30 0x2f 0x13 0x2f 0x2f    4210/.//
0148   0x13 0x2f 0x2f 0x2f 0x30 0x32 0x32 0x33    .///0223
0150   0x35 0x37 0x38 0x38 0x39 0x3d 0x3f 0x3e    57889=?>
0158   0x3c 0x85 0x0e 0x0b 0xa8 0x08 0x0e 0x3a    <......:
0160   0x38 0x37 0x3f 0x78 0x11 0x0e 0x0b 0xb7    87?x....
0168   0x08 0x0f 0x3f 0x3d 0x3b 0x38 0x36 0x34    ..?=;864
0170   0x33 0x32 0x33 0x32 0x31 0x31 0x32 0x33    32321123
0178   0x36 0x38 0x3b 0x3c 0x3d 0x3e 0x3f 0x3e    68;<=>?>
0180   0x3f 0x3f 0x3f 0x3e 0x3d 0x3d 0x3c 0x3c    ???>==<<
0188   0x3c 0x3c 0x3b 0x3a 0x39 0x38 0x37 0x37    <<;:9877
0190   0x37 0x38 0x39 0x38 0x37 0x34 0x32 0x2f    7898742/
0198   0x2e 0x2e 0x2f 0x31 0x33 0x34 0x34 0x33    ../13443
01A0   0x33 0x32 0x32 0x33 0x33 0x32 0x30 0x31    32233201
01A8   0x32 0x31 0x30 0x2e 0x2b 0x28 0x26 0x24    210.+(&$
01B0   0x24 0x23 0x22 0x21 0x62 0x0e 0x0b 0x87    $#"!b...
01B8   0x0f 0x0e 0x21 0x20 0x25 0x56 0x14 0x0e    ..! %V..
01C0   0x0b 0x94 0x0f 0x0f 0x25 0x26 0x26 0x29    ....%&&)
01C8   0x2f 0x33 0x34 0x34 0x34 0x35 0x34 0x33    /3444543
01D0   0x32 0x30 0x2f 0x2e 0x2c 0x29 0x29 0x2b    20/.,))+
01D8   0x2c 0x2a 0x28 0x26 0x24 0x22 0x21 0x20    ,*(&$"! 
01E0   0x20 0x20 0x20 0x1f 0x1f 0x1e 0x1e 0x1f       .....
01E8   0x21 0x23 0x26 0x29 0x2d 0x2f 0x2f 0x33    !#&)-//3
01F0   0x3b 0x40 0x42 0x44 0x47 0x4c 0x50 0x52    ;@BDGLPR
01F8   0x53 0x52 0x52 0x7f 0x0e 0x0b 0xb9 0x13    SRR.....
0200   0x0e 0x53 0x54 0x45 0x03 0x10 0x0e 0x0b    .STE....
0208   0x8b 0x14 0x0f 0x48 0x4c 0x50 0x54 0x57    ...HLPTW
0210   0x5c 0x61 0xc1 0x0e 0x0b 0xad 0x14 0x0e    \a......
0218   0x66 0x69 0x64 0xd0 0x0e 0x0e 0x0b 0xbb    fid.....
0220   0x14 0x0f 0x66 0x66 0x60 0x59 0x53 0x4d    ..ff`YSM
0228   0x4c 0x4b 0x4b 0x4c 0x4e 0x51 0x51 0x53    LKKLNQQS
0230   0x54 0x54 0x52 0x4e 0x4b 0x47 0x44 0x41    TTRNKGDA
0238   0x3e 0xc5 0x0e 0x0b 0xba 0x16 0x0e 0x3d    >......=
0240   0x3e 0x4a 0xf6 0x10 0x0e 0x0b 0x89 0x17    >J......
0248   0x0f 0x4a 0x48 0x44 0x40 0x3c 0x38 0x35    .JHD@<85
0250   0x32 0x31 0x30 0x2f 0x2e 0x2d 0x2c 0x2b    210/.-,+
0258   0x2b 0x2a 0x29 0x29 0x28 0x28 0x28 0x2d    +*))(((-
0260   0x37 0x3c 0x3c 0x3b 0x39 0x38 0x36 0x36    7<<;9866
0268   0x35 0x35 0x35 0x35 0x33 0x31 0x2d 0x2b    555531-+
0270   0x29 0x28 0x28 0x28 0x29 0x29 0x29 0x2a    )((()))*
0278   0x2a 0x2b 0x2e 0x31 0x35 0x38 0x3b 0x3d    *+.158;=
0280   0x3e 0x3e 0x3f 0x40 0x41 0x41 0x3f 0x3f    >>?@AA??
0288   0x3f 0x3f 0x40 0x42 0x44 0x47 0x4d 0x5a    ??@BDGMZ
0290   0x62 0x65 0x65 0x61 0x5a 0x53 0x4f 0x4c    beeaZSOL
0298   0x4b 0x4b 0x4b 0x4c 0x4c 0x4c 0x4c 0x4c    KKKLLLLL
02A0   0x4c 0x4b 0x4b 0x4b 0x4b 0x47 0x47 0xe6    LKKKKGG.
02A8   0x0e 0x0c 0x83 0x07 0x0e 0x4d 0x13 0x58    .....M.X
02B0   0x6a 0x3b 0x13 0x0e 0x0c 0x8e 0x07 0x0f    j;......
02B8   0x6b 0x6a 0x69 0x6a 0x68 0x64 0x61 0x5d    kjijhda]
02C0   0x59 0x56 0x54 0x52 0x4f 0xaa 0x0e 0x0c    YVTRO...
02C8   0x97 0x08 0x0e 0x4c 0x49 0x49 0xaf 0x14    ...LII..
02D0   0x0e 0x0c 0xa2 0x08 0x0f 0x45 0x41 0x3f    .....EA?
02D8   0x3e 0x3e 0x3f 0x3f 0x40 0x40 0x40 0x3f    >>??@@@?
02E0   0x3e 0x3c 0x3b 0x3b 0x3b 0x3a 0x39 0x38    ><;;;:98
02E8   0x36 0x36 0x36 0x35 0x35 0x35 0x33 0x32    66655532
02F0   0x32 0x33 0x33 0x32 0x31 0x30 0x2d 0x2a    233210-*
02F8   0x27 0x24 0x21 0x1e 0x1c 0x19 0x18 0x1a    '$!.....
0300   0x1f 0x25 0x2c 0x32 0x37 0x3b 0x3f 0xb0    .%,27;?.
0308   0x0e 0x0c 0xb0 0x0c 0x0e 0x43 0x47 0x53    .....CGS
0310   0xd2 0x16 0x0e 0x0c 0xbb 0x0c 0x0f 0x01    ........
0318   0x05 0x0e 0x4c 0x84 0x0d 0x08 0x0e 0x4c    ..L....L
0320   0x84 0x0d 0x0b 0x0e 0x2c 0x91 0x0d 0x0d    ....,...
0328   0x00 0x03 0x00 0x03 0x00 0x03 0xb1 0x0e    ........
0330   0x0c 0xa0 0x0d 0x0e 0x01 0x03 0x01 0x03    ........
0338   0x58 0x75 0x16 0x0e 0x0c 0xac 0x0d 0x0f    Xu......
0340   0x57 0x55 0x53 0x52 0x4f 0x4d 0x4c 0x4c    WUSROMLL
0348   0x4e 0x50 0x52 0x54 0x55 0x56 0x56 0x58    NPRTUVVX
0350   0x59 0x5b 0x5d 0x5d 0x5e 0x5f 0x61 0x61    Y[]]^_aa
0358   0x62 0x63 0x61 0x5e 0x5a 0x57 0x54 0x52    bca^ZWTR
0360   0x4f 0x4d 0x4d 0x4c 0x4d 0x50 0x52 0x53    OMMLMPRS
0368   0x54 0x55 0x56 0x57 0x59 0x5a 0x5c 0x5b    TUVWYZ\[
0370   0x58 0x55 0x52 0x4f 0x4e 0x4d 0x4a 0x48    XURONMJH
0378   0x46 0x42 0x3d 0x38 0x35 0x35 0x36 0x38    FB=85568
0380   0x39 0x39 0x38 0x73 0x0e 0x0c 0x95 0x13    998s....
0388   0x0e 0x38 0x37 0x39 0x8c 0x16 0x0e 0x0c    .879....
0390   0xa3 0x13 0x0f 0x3a 0x3a 0x3a 0x3a 0x3c    ...::::<
0398   0x3d 0x40 0x44 0x48 0x4b 0x4f 0x55 0x5e    =@DHKOU^
03A0   0x64 0x67 0x6c 0x71 0x75 0x79 0xdd 0x0e    dglquy..
03A8   0x0c 0x8e 0x15 0x0e 0x7d 0x7e 0x72 0xb6    ....}~r.
03B0   0x14 0x0e 0x0c 0x99 0x15 0x0f 0x6e 0x6a    ......nj
03B8   0x65 0x5e 0x54 0x4b 0x41 0x38 0x32 0x2e    e^TKA82.
03C0   0x2c 0x13 0x2a 0x13 0x29 0x13 0x29 0x6b    ,.*.).)k
03C8   0x0e 0x0c 0xa6 0x16 0x0e 0x29 0x29 0x2b    .....))+
03D0   0x5c 0x15 0x0e 0x0c 0xb3 0x16 0x0f 0x2c    \......,
03D8   0x2c 0x2b 0x2a 0x2a 0x2a 0x28 0x26 0x23    ,+***(&#
03E0   0x20 0x1d 0x1b 0x32 0x0e 0x0c 0xb5 0x17     ..2....
03E8   0x0e 0x1a 0x1a 0x1b 0x22 0x15 0x0e 0x0d    ...."...
03F0   0x85 0x00 0x0f 0x1e 0x23 0x27 0x29 0x2b    ....#')+
03F8   0x2d 0x0e 0x2d 0xa2 0x00 0x08 0xd7 0x3e    -.-....>
```
#### decoded:
```python
'0000   0x2b 0x2a 0x28 0x27 0x27 0x29 0x2b 0x2e    +*(\'\')+.\n0008   0x31 0x35 0x39 0x3c 0x3f 0x8a 0x0e 0x0a    159<?...\n0010   0xa8 0x09 0x0e 0x44 0x47 0x45 0xcb 0x0c    ...DGE..\n0018   0x0e 0x0a 0xb6 0x09 0x0f 0x46 0x46 0x47    .....FFG\n0020   0x48 0x48 0x49 0x4b 0x4b 0x4a 0x4b 0x4b    HHIKKJKK\n0028   0x48 0x45 0x44 0x44 0x45 0x44 0x44 0x45    HEDDEDDE\n0030   0x46 0x45 0x44 0x43 0x43 0x44 0x45 0x44    FEDCCDED\n0038   0x43 0x42 0x43 0x44 0x46 0x48 0x4a 0x4c    CBCDFHJL\n0040   0x4d 0x4e 0x4e 0x4e 0x4d 0x4c 0x4c 0x4b    MNNNMLLK\n0048   0x49 0x46 0x43 0x42 0x42 0x41 0x3e 0x39    IFCBBA>9\n0050   0x36 0x33 0x2f 0x2b 0x28 0x25 0x22 0x1f    63/+(%".\n0058   0x1c 0x1a 0x18 0x3e 0x0e 0x0a 0x86 0x0f    ...>....\n0060   0x0e 0x17 0x18 0x1a 0x66 0x0d 0x0e 0x0a    ....f...\n0068   0x94 0x0f 0x0f 0x1c 0x20 0x24 0x28 0x2c    .... $(,\n0070   0x2e 0x30 0x31 0x31 0x31 0x31 0x31 0x32    .0111112\n0078   0x32 0x32 0x34 0x33 0x32 0x30 0x2e 0x2c    224320.,\n0080   0x2b 0x2b 0x2e 0x2f 0x2e 0x2c 0x2b 0x2c    ++./.,+,\n0088   0x2f 0x32 0x34 0x36 0x37 0x37 0x37 0x36    /2467776\n0090   0x34 0x32 0x66 0x0e 0x0a 0xa3 0x12 0x0e    42f.....\n0098   0x30 0x2f 0x2f 0x64 0x0e 0x0e 0x0a 0xb3    0//d....\n00A0   0x12 0x0f 0x2e 0x2e 0x2d 0x2c 0x29 0x26    ....-,)&\n00A8   0x23 0x21 0x22 0x23 0x25 0x26 0x27 0x28    #!"#%&\'(\n00B0   0x28 0x29 0x2b 0x2d 0x2e 0x2e 0x2d 0x2d    ()+-..--\n00B8   0x2e 0x2f 0x30 0x2e 0x2d 0x2c 0x2c 0x2e    ./0.-,,.\n00C0   0x34 0x3a 0x3e 0x43 0x47 0x48 0x4a 0x49    4:>CGHJI\n00C8   0x47 0x44 0x41 0x87 0x0e 0x0a 0x91 0x16    GDA.....\n00D0   0x0e 0x40 0x3f 0x41 0x1f 0x0f 0x0e 0x0a    .@?A....\n00D8   0x9d 0x16 0x0f 0x3e 0x3a 0x36 0x32 0x2e    ...>:62.\n00E0   0x2b 0x29 0x27 0x26 0x25 0x24 0x23 0x22    +)\'&%$#"\n00E8   0x23 0x24 0x25 0x25 0x25 0x25 0x24 0x24    #$%%%%$$\n00F0   0x23 0x23 0x22 0x21 0x21 0x21 0x20 0x20    ##"!!!  \n00F8   0x1f 0x1f 0x1f 0x1f 0x21 0x22 0x23 0x24    ....!"#$\n0100   0x25 0x26 0x27 0x28 0x2a 0x2c 0x2e 0x30    %&\'(*,.0\n0108   0x32 0x33 0x34 0x34 0x35 0x36 0x37 0x37    23445677\n0110   0x37 0x38 0x38 0x36 0x34 0x30 0x2e 0x2d    788640.-\n0118   0x2f 0x30 0x31 0x32 0x33 0x33 0x34 0x35    /0123345\n0120   0x39 0x3b 0x3a 0x3a 0x39 0x37 0x36 0x36    9;::9766\n0128   0x36 0x36 0x36 0x35 0x34 0x33 0x32 0x32    66654322\n0130   0x32 0x33 0x33 0x33 0x33 0x32 0x32 0x33    23333223\n0138   0x34 0x13 0x35 0x13 0x35 0x13 0x35 0x35    4.5.5.55\n0140   0x34 0x32 0x31 0x30 0x2f 0x13 0x2f 0x2f    4210/.//\n0148   0x13 0x2f 0x2f 0x2f 0x30 0x32 0x32 0x33    .///0223\n0150   0x35 0x37 0x38 0x38 0x39 0x3d 0x3f 0x3e    57889=?>\n0158   0x3c 0x85 0x0e 0x0b 0xa8 0x08 0x0e 0x3a    <......:\n0160   0x38 0x37 0x3f 0x78 0x11 0x0e 0x0b 0xb7    87?x....\n0168   0x08 0x0f 0x3f 0x3d 0x3b 0x38 0x36 0x34    ..?=;864\n0170   0x33 0x32 0x33 0x32 0x31 0x31 0x32 0x33    32321123\n0178   0x36 0x38 0x3b 0x3c 0x3d 0x3e 0x3f 0x3e    68;<=>?>\n0180   0x3f 0x3f 0x3f 0x3e 0x3d 0x3d 0x3c 0x3c    ???>==<<\n0188   0x3c 0x3c 0x3b 0x3a 0x39 0x38 0x37 0x37    <<;:9877\n0190   0x37 0x38 0x39 0x38 0x37 0x34 0x32 0x2f    7898742/\n0198   0x2e 0x2e 0x2f 0x31 0x33 0x34 0x34 0x33    ../13443\n01A0   0x33 0x32 0x32 0x33 0x33 0x32 0x30 0x31    32233201\n01A8   0x32 0x31 0x30 0x2e 0x2b 0x28 0x26 0x24    210.+(&$\n01B0   0x24 0x23 0x22 0x21 0x62 0x0e 0x0b 0x87    $#"!b...\n01B8   0x0f 0x0e 0x21 0x20 0x25 0x56 0x14 0x0e    ..! %V..\n01C0   0x0b 0x94 0x0f 0x0f 0x25 0x26 0x26 0x29    ....%&&)\n01C8   0x2f 0x33 0x34 0x34 0x34 0x35 0x34 0x33    /3444543\n01D0   0x32 0x30 0x2f 0x2e 0x2c 0x29 0x29 0x2b    20/.,))+\n01D8   0x2c 0x2a 0x28 0x26 0x24 0x22 0x21 0x20    ,*(&$"! \n01E0   0x20 0x20 0x20 0x1f 0x1f 0x1e 0x1e 0x1f       .....\n01E8   0x21 0x23 0x26 0x29 0x2d 0x2f 0x2f 0x33    !#&)-//3\n01F0   0x3b 0x40 0x42 0x44 0x47 0x4c 0x50 0x52    ;@BDGLPR\n01F8   0x53 0x52 0x52 0x7f 0x0e 0x0b 0xb9 0x13    SRR.....\n0200   0x0e 0x53 0x54 0x45 0x03 0x10 0x0e 0x0b    .STE....\n0208   0x8b 0x14 0x0f 0x48 0x4c 0x50 0x54 0x57    ...HLPTW\n0210   0x5c 0x61 0xc1 0x0e 0x0b 0xad 0x14 0x0e    \\a......\n0218   0x66 0x69 0x64 0xd0 0x0e 0x0e 0x0b 0xbb    fid.....\n0220   0x14 0x0f 0x66 0x66 0x60 0x59 0x53 0x4d    ..ff`YSM\n0228   0x4c 0x4b 0x4b 0x4c 0x4e 0x51 0x51 0x53    LKKLNQQS\n0230   0x54 0x54 0x52 0x4e 0x4b 0x47 0x44 0x41    TTRNKGDA\n0238   0x3e 0xc5 0x0e 0x0b 0xba 0x16 0x0e 0x3d    >......=\n0240   0x3e 0x4a 0xf6 0x10 0x0e 0x0b 0x89 0x17    >J......\n0248   0x0f 0x4a 0x48 0x44 0x40 0x3c 0x38 0x35    .JHD@<85\n0250   0x32 0x31 0x30 0x2f 0x2e 0x2d 0x2c 0x2b    210/.-,+\n0258   0x2b 0x2a 0x29 0x29 0x28 0x28 0x28 0x2d    +*))(((-\n0260   0x37 0x3c 0x3c 0x3b 0x39 0x38 0x36 0x36    7<<;9866\n0268   0x35 0x35 0x35 0x35 0x33 0x31 0x2d 0x2b    555531-+\n0270   0x29 0x28 0x28 0x28 0x29 0x29 0x29 0x2a    )((()))*\n0278   0x2a 0x2b 0x2e 0x31 0x35 0x38 0x3b 0x3d    *+.158;=\n0280   0x3e 0x3e 0x3f 0x40 0x41 0x41 0x3f 0x3f    >>?@AA??\n0288   0x3f 0x3f 0x40 0x42 0x44 0x47 0x4d 0x5a    ??@BDGMZ\n0290   0x62 0x65 0x65 0x61 0x5a 0x53 0x4f 0x4c    beeaZSOL\n0298   0x4b 0x4b 0x4b 0x4c 0x4c 0x4c 0x4c 0x4c    KKKLLLLL\n02A0   0x4c 0x4b 0x4b 0x4b 0x4b 0x47 0x47 0xe6    LKKKKGG.\n02A8   0x0e 0x0c 0x83 0x07 0x0e 0x4d 0x13 0x58    .....M.X\n02B0   0x6a 0x3b 0x13 0x0e 0x0c 0x8e 0x07 0x0f    j;......\n02B8   0x6b 0x6a 0x69 0x6a 0x68 0x64 0x61 0x5d    kjijhda]\n02C0   0x59 0x56 0x54 0x52 0x4f 0xaa 0x0e 0x0c    YVTRO...\n02C8   0x97 0x08 0x0e 0x4c 0x49 0x49 0xaf 0x14    ...LII..\n02D0   0x0e 0x0c 0xa2 0x08 0x0f 0x45 0x41 0x3f    .....EA?\n02D8   0x3e 0x3e 0x3f 0x3f 0x40 0x40 0x40 0x3f    >>??@@@?\n02E0   0x3e 0x3c 0x3b 0x3b 0x3b 0x3a 0x39 0x38    ><;;;:98\n02E8   0x36 0x36 0x36 0x35 0x35 0x35 0x33 0x32    66655532\n02F0   0x32 0x33 0x33 0x32 0x31 0x30 0x2d 0x2a    233210-*\n02F8   0x27 0x24 0x21 0x1e 0x1c 0x19 0x18 0x1a    \'$!.....\n0300   0x1f 0x25 0x2c 0x32 0x37 0x3b 0x3f 0xb0    .%,27;?.\n0308   0x0e 0x0c 0xb0 0x0c 0x0e 0x43 0x47 0x53    .....CGS\n0310   0xd2 0x16 0x0e 0x0c 0xbb 0x0c 0x0f 0x01    ........\n0318   0x05 0x0e 0x4c 0x84 0x0d 0x08 0x0e 0x4c    ..L....L\n0320   0x84 0x0d 0x0b 0x0e 0x2c 0x91 0x0d 0x0d    ....,...\n0328   0x00 0x03 0x00 0x03 0x00 0x03 0xb1 0x0e    ........\n0330   0x0c 0xa0 0x0d 0x0e 0x01 0x03 0x01 0x03    ........\n0338   0x58 0x75 0x16 0x0e 0x0c 0xac 0x0d 0x0f    Xu......\n0340   0x57 0x55 0x53 0x52 0x4f 0x4d 0x4c 0x4c    WUSROMLL\n0348   0x4e 0x50 0x52 0x54 0x55 0x56 0x56 0x58    NPRTUVVX\n0350   0x59 0x5b 0x5d 0x5d 0x5e 0x5f 0x61 0x61    Y[]]^_aa\n0358   0x62 0x63 0x61 0x5e 0x5a 0x57 0x54 0x52    bca^ZWTR\n0360   0x4f 0x4d 0x4d 0x4c 0x4d 0x50 0x52 0x53    OMMLMPRS\n0368   0x54 0x55 0x56 0x57 0x59 0x5a 0x5c 0x5b    TUVWYZ\\[\n0370   0x58 0x55 0x52 0x4f 0x4e 0x4d 0x4a 0x48    XURONMJH\n0378   0x46 0x42 0x3d 0x38 0x35 0x35 0x36 0x38    FB=85568\n0380   0x39 0x39 0x38 0x73 0x0e 0x0c 0x95 0x13    998s....\n0388   0x0e 0x38 0x37 0x39 0x8c 0x16 0x0e 0x0c    .879....\n0390   0xa3 0x13 0x0f 0x3a 0x3a 0x3a 0x3a 0x3c    ...::::<\n0398   0x3d 0x40 0x44 0x48 0x4b 0x4f 0x55 0x5e    =@DHKOU^\n03A0   0x64 0x67 0x6c 0x71 0x75 0x79 0xdd 0x0e    dglquy..\n03A8   0x0c 0x8e 0x15 0x0e 0x7d 0x7e 0x72 0xb6    ....}~r.\n03B0   0x14 0x0e 0x0c 0x99 0x15 0x0f 0x6e 0x6a    ......nj\n03B8   0x65 0x5e 0x54 0x4b 0x41 0x38 0x32 0x2e    e^TKA82.\n03C0   0x2c 0x13 0x2a 0x13 0x29 0x13 0x29 0x6b    ,.*.).)k\n03C8   0x0e 0x0c 0xa6 0x16 0x0e 0x29 0x29 0x2b    .....))+\n03D0   0x5c 0x15 0x0e 0x0c 0xb3 0x16 0x0f 0x2c    \\......,\n03D8   0x2c 0x2b 0x2a 0x2a 0x2a 0x28 0x26 0x23    ,+***(&#\n03E0   0x20 0x1d 0x1b 0x32 0x0e 0x0c 0xb5 0x17     ..2....\n03E8   0x0e 0x1a 0x1a 0x1b 0x22 0x15 0x0e 0x0d    ...."...\n03F0   0x85 0x00 0x0f 0x1e 0x23 0x27 0x29 0x2b    ....#\')+\n03F8   0x2d 0x0e 0x2d 0xa2 0x00 0x08 0xd7 0x3e    -.-....>'
```
### end stats
```
```
```javascript
{'radio': {'errors.crc': 0,
           'errors.naks': 0,
           'errors.sequence': 0,
           'errors.timeouts': 0,
           'packets.received': 124L,
           'packets.transmit': 129L},
 'usb': {'errors.crc': 0,
         'errors.naks': 0,
         'errors.sequence': 0,
         'errors.timeouts': 0,
         'packets.received': 178L,
         'packets.transmit': 178L}}
```
