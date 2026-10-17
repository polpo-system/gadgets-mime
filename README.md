# gadgets-mime

MIME for the gadgets of [polpo](https://github.com/polpo-system/polpo): the headers of mail and of HTTP (fields, parameters, dates, e-mail addresses, content types) and MIME content, with the section MIME of Oberon.Text for the types. HTTPDocs uses it.

```
portia.Install gadgets-mime
```

## What is here

    src/OLR.MIME.Mod
    test/MIMETest.Mod

The source comes from ETH Linux Oberon (OLR, 2017-06-18), converted from an Oberon text to plain
text; the first commit has it unchanged. It compiles unchanged with all five of polpo's compilers
(x86, ARM, ARMv7, RISC-V, MIPS).

## Tests

    MIMETest.Run      1 check: the module loaded; it needs the desktop's display

The license is GPL-3 (`LICENSE`); the code comes from ETH Oberon, whose license (`LICENSE.ETH`)
asks to keep its copyright notice and conditions, which `LICENSE.ETH` does.
