# CBT682
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 682 is from Bob Glover and contains his TSOESO ISPF-based *   FILE 682
//*           command processor to display all the ESOTERICS on     *   FILE 682
//*           your system.                                          *   FILE 682
//*                                                                 *   FILE 682
//*           email:  Bob.Glover@fnf.com                            *   FILE 682
//*                                                                 *   FILE 682
//*       TSOESO = DISPLAY System ESOTERICS                         *   FILE 682
//*                                                                 *   FILE 682
//*       > Members are :                                           *   FILE 682
//*        TSOESO     = Assembler program                           *   FILE 682
//*        ESOPAN2    = ISPF panel                                  *   FILE 682
//*        ESO        = REXX                                        *   FILE 682
//*        ASMESO     = JCL to ASMLK TSOESO                         *   FILE 682
//*                                                                 *   FILE 682
//*       Note:  The assembler program has the ability to           *   FILE 682
//*              incorporate STK silo macros if you have            *   FILE 682
//*              them, and to exclude them if you don't.            *   FILE 682
//*              There is a conditional assembly statement          *   FILE 682
//*              in the code which takes care of the two            *   FILE 682
//*              cases:                                             *   FILE 682
//*                                                                 *   FILE 682
//*              " &STK     SETC  'YES' <=== 'YES' OR 'NO' "        *   FILE 682
//*                                                                 *   FILE 682
//*       Note:  A load library in TSO XMIT format has been         *   FILE 682
//*              included.  This load module was assembled with     *   FILE 682
//*              the STK option on, but it appears to work fine,    *   FILE 682
//*              even if you don't have STK silos in your           *   FILE 682
//*              system.                                            *   FILE 682
//*                                                                 *   FILE 682
```
