ASxxxx Assembler V02.00 + NoICE + SDCC mods  (Zilog Z80 / Hitachi HD64180), page 1.
Hexadecimal [16-Bits]



                              1 ;; File 'src/assets/levels/level20.s' generated using cpct_pack
                              2 ;; Compresor used:   zx7b
                              3 ;; Files compressed: [ 'src/assets/tilemaps/level20.bin' ]
                              4 ;; Uncompressed:     2000 bytes
                              5 ;; Compressed:       360 bytes
                              6 ;; Space saved:      1640 bytes
                              7 ;;
                              8 
                              9 ;; Data array definition
   0EBD                      10 _level20::
   0EBD 58 55 5C 00 15 82    11    .db  0x58, 0x55, 0x5c, 0x00, 0x15, 0x82, 0x63, 0x5d, 0x27, 0x42, 0xbc, 0x32, 0x30, 0xbb, 0x12, 0xb8
        63 5D 27 42 BC 32
        30 BB 12 B8
   0ECD 0F AE 27 31 3B 02    12    .db  0x0f, 0xae, 0x27, 0x31, 0x3b, 0x02, 0x1c, 0xfa, 0x25, 0x01, 0x6b, 0x06, 0x4f, 0xfa, 0x10, 0x8e
        1C FA 25 01 6B 06
        4F FA 10 8E
   0EDD 0C 04 12 76 0B 4D    13    .db  0x0c, 0x04, 0x12, 0x76, 0x0b, 0x4d, 0x05, 0x09, 0x77, 0x11, 0x04, 0x11, 0x27, 0x6d, 0x40, 0x00
        05 09 77 11 04 11
        27 6D 40 00
   0EED 5C 27 C0 01 4D 4B    14    .db  0x5c, 0x27, 0xc0, 0x01, 0x4d, 0x4b, 0x27, 0xa5, 0x06, 0xae, 0x89, 0x27, 0x73, 0x01, 0x3a, 0x49
        27 A5 06 AE 89 27
        73 01 3A 49
   0EFD 4A 27 6E 06 00 75    15    .db  0x4a, 0x27, 0x6e, 0x06, 0x00, 0x75, 0x01, 0x02, 0x03, 0x89, 0x98, 0x4f, 0x57, 0x27, 0x57, 0x06
        01 02 03 89 98 4F
        57 27 57 06
   0F0D 0D 0E 0F 10 87 89    16    .db  0x0d, 0x0e, 0x0f, 0x10, 0x87, 0x89, 0x4f, 0x79, 0x28, 0x27, 0xf5, 0x1a, 0x55, 0x1b, 0x1c, 0x1d
        4F 79 28 27 F5 1A
        55 1B 1C 1D
   0F1D 4F 18 3E 3E 25 90    17    .db  0x4f, 0x18, 0x3e, 0x3e, 0x25, 0x90, 0x27, 0x55, 0x28, 0x29, 0x2a, 0x4f, 0x58, 0x34, 0x40, 0x35
        27 55 28 29 2A 4F
        58 34 40 35
   0F2D 36 37 27 08 4A 4B    18    .db  0x36, 0x37, 0x27, 0x08, 0x4a, 0x4b, 0x27, 0x24, 0x41, 0x50, 0x42, 0x43, 0x44, 0x27, 0x08, 0x57
        27 24 41 50 42 43
        44 27 08 57
   0F3D 58 00 64 22 15 57    19    .db  0x58, 0x00, 0x64, 0x22, 0x15, 0x57, 0x00, 0xb1, 0x05, 0x4e, 0x4f, 0x3a, 0x50, 0x51, 0xab, 0x40
        00 B1 05 4E 4F 3A
        50 51 AB 40
   0F4D 4F 3A 20 15 2E B7    20    .db  0x4f, 0x3a, 0x20, 0x15, 0x2e, 0xb7, 0xc6, 0x20, 0xd0, 0x25, 0xbf, 0x46, 0x15, 0xba, 0x18, 0xb7
        C6 20 D0 25 BF 46
        15 BA 18 B7
   0F5D 83 D0 94 58 9F 81    21    .db  0x83, 0xd0, 0x94, 0x58, 0x9f, 0x81, 0x27, 0x6e, 0x9f, 0x2d, 0x27, 0xba, 0x5a, 0x9f, 0xab, 0x27
        27 6E 9F 2D 27 BA
        5A 9F AB 27
   0F6D 6E 9F 2D 27 BA 5A    22    .db  0x6e, 0x9f, 0x2d, 0x27, 0xba, 0x5a, 0x9f, 0xab, 0x27, 0x6e, 0x9f, 0x8d, 0x38, 0xd6, 0xa3, 0xed
        9F AB 27 6E 9F 8D
        38 D6 A3 ED
   0F7D C6 4F 86 82 8F B2    23    .db  0xc6, 0x4f, 0x86, 0x82, 0x8f, 0xb2, 0x11, 0x9a, 0x01, 0x19, 0xb4, 0xa9, 0xcf, 0x94, 0x11, 0x60
        11 9A 01 19 B4 A9
        CF 94 11 60
   0F8D 01 66 B4 AC 8F CA    24    .db  0x01, 0x66, 0xb4, 0xac, 0x8f, 0xca, 0x20, 0xc7, 0x84, 0x2a, 0x8f, 0x8b, 0x27, 0x8b, 0x8f, 0xca
        20 C7 84 2A 8F 8B
        27 8B 8F CA
   0F9D 27 E2 A2 8F B2 27    25    .db  0x27, 0xe2, 0xa2, 0x8f, 0xb2, 0x27, 0xb8, 0xa8, 0x8f, 0xac, 0x27, 0xae, 0x28, 0x8f, 0xa9, 0x00
        B8 A8 8F AC 27 AE
        28 8F A9 00
ASxxxx Assembler V02.00 + NoICE + SDCC mods  (Zilog Z80 / Hitachi HD64180), page 2.
Hexadecimal [16-Bits]



   0FAD 3D 11 29 BC 61 C1    26    .db  0x3d, 0x11, 0x29, 0xbc, 0x61, 0xc1, 0xed, 0x4f, 0xd8, 0x44, 0x50, 0x8f, 0x02, 0x27, 0xcd, 0xb0
        ED 4F D8 44 50 8F
        02 27 CD B0
   0FBD 58 BF 8C 40 27 33    27    .db  0x58, 0xbf, 0x8c, 0x40, 0x27, 0x33, 0xb0, 0x16, 0xbf, 0x23, 0x21, 0x4d, 0x9f, 0x58, 0x1f, 0x20
        B0 16 BF 23 21 4D
        9F 58 1F 20
   0FCD 15 9F 21 C8 27 1D    28    .db  0x15, 0x9f, 0x21, 0xc8, 0x27, 0x1d, 0x16, 0x2c, 0x2d, 0x15, 0x16, 0x27, 0x21, 0x27, 0xde, 0x51
        16 2C 2D 15 16 27
        21 27 DE 51
   0FDD 23 39 3A 23 27 21    29    .db  0x23, 0x39, 0x3a, 0x23, 0x27, 0x21, 0xe1, 0x27, 0x1d, 0x30, 0x46, 0x47, 0x15, 0x30, 0x27, 0x21
        E1 27 1D 30 46 47
        15 30 27 21
   0FED 27 CE 55 53 54 27    30    .db  0x27, 0xce, 0x55, 0x53, 0x54, 0x27, 0x21, 0xc9, 0x10, 0x1d, 0x05, 0x06, 0x07, 0x00, 0x45, 0x45
        21 C9 10 1D 05 06
        07 00 45 45
   0FFD 60 28 61 45 4F 04    31    .db  0x60, 0x28, 0x61, 0x45, 0x4f, 0x04, 0x88, 0x4d, 0x05, 0x27, 0x01, 0xf6, 0x40, 0x03, 0x45, 0x01
        88 4D 05 27 01 F6
        40 03 45 01
   100D 0A 0B 37 33 4D 05    32    .db  0x0a, 0x0b, 0x37, 0x33, 0x4d, 0x05, 0x45, 0x45, 0x2c, 0x01, 0x81, 0x03, 0x45, 0x01, 0x17, 0x6e
        45 45 2C 01 81 03
        45 01 17 6E
   101D 18 33 52 00 08 5E    33    .db  0x18, 0x33, 0x52, 0x00, 0x08, 0x5e, 0x41, 0x5f
        41 5F
                             34 ;; Address of the latest byte of the compressed array (for unpacking purposes)
                     0167    35 _level20_end == . - 1
                             36 
