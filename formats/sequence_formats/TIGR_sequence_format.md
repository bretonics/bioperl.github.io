---
title: TIGR sequence format
layout: default
---

Description
-----------

The TIGR sequence format format, referred to as `tigrxml` here.

There are a couple of variants of it for the Rice and *Arabidopsis* data versus some of the pre-release data.

Example
-------

```
<ASSEMBLY ASMBL_ID = "162" COORDS = "1-1178688">
<HEADER>
               <CLONE_NAME>`chr9`</CLONE_NAME>
               <ORGANISM>`Cryptococcus neoformans`</ORGANISM>
               <AUTHOR_LIST CONTACT = "">
               </AUTHOR_LIST>
</HEADER>
       <TU FEAT_NAME = "162.t00500" LOCUS = "" PUB_LOCUS = "" ALT_LOCUS = "" COM_NAME = "hypothetical protein" PUB_COMMENT = "" COORDS =  "185408-187155">
               <MODEL FEAT_NAME = "162.m02638" COMMENT = "" COORDS = "185794-187041">
                        <PROTEIN_SEQ>`MSAHSGSCIPSTSCPSSTVSINGTCVTCPLDCATCSTASTCSTCPSDRPILKNGRCIAYCATDTYYDTSTGTCQACDWTCKNCVGEGSAMCSSCSDGYMLKDGVCVDALCGDAGFANGFGMCFSSFVHKSQKRYLGLLALVGVAIIAGIASWWYVRRERRKTRQATKEFGKRLDERNVNDRLSALRLEKVFGFNRVTFGRGGDRSARTTQEDGGKKNKLRELLLPSKRRSGNEEMEMKKSNFAPDKERDCYDSWRTSNFGKDNWVAPPPYVPSQGVPTPVDVKHTFNKRDSLDSIPTPSHQTFAPSSSTSSFTITRPATPPRKLQNPYLGSTIIHSMSTPSPPPHSRSLMPPPRPGMGRRESGNSFSSGSLWTPMTGMTSITKITADKERDVRRYSGRQDRQMDVERRPTDYDLL*`</PROTEIN_SEQ>
                       <EXON FEAT_NAME = "162.e11999" COORDS = "185408-185433">
                       </EXON>
                       <EXON FEAT_NAME = "162.e12000" COORDS = "185487-187155">
                               <CDS FEAT_NAME = "162.c02494" COORDS = "185794-187041"/>
                       </EXON>
               </MODEL>
       </TU>
       <TU FEAT_NAME = "162.t00448" LOCUS = "" PUB_LOCUS = "" ALT_LOCUS = "" COM_NAME = "eukaryotic translation initiation factor 2 alpha subunit (eif-2- alpha). (fission yeast" PUB_COMMENT = "" COORDS = "61061-59343">
               <MODEL FEAT_NAME = "162.m02967" COMMENT = "" COORDS = "60833-59633">
                         <PROTEIN_SEQ>`MPRFYENKYPEVDQLVMVQVQSIEDMGAYVKLLEYDNIEGMILLSELSRRRIRSVQKLIRVGRNEVVVVMRVDPDKGYIDLSKRRVSAEEVVKCEEQYEKGKAVDSIITQVAKKRGVTPESLYEKIAWPLHRQYGHAYEAFKLSISEPEAVFGSLELDEETLADLRSGIARRLTPKPVKVRADIEVKCFSYAGIDAIKRALTAGEAVSTPDVPIKVRLVAPPLYVMSTTSTDKNAAIELMEKAVEVIGETVRKDKGDITIKMKPKVVSETEDAELKALMEQFEAANMDQAGDDESSEEDE*`</PROTEIN_SEQ>
                       <EXON FEAT_NAME = "162.e18653" COORDS = "61061-60801">
                               <CDS FEAT_NAME = "162.c05241" COORDS = "60833-60801"/>
                       </EXON>
                       <EXON FEAT_NAME = "162.e18654" COORDS = "60736-60674">
                               <CDS FEAT_NAME = "162.c05242" COORDS = "60736-60674"/>
                       </EXON>
                       <EXON FEAT_NAME = "162.e18655" COORDS = "60619-60487">
                               <CDS FEAT_NAME = "162.c05243" COORDS = "60619-60487"/>
                       </EXON>
                       <EXON FEAT_NAME = "162.e18656" COORDS = "60431-60224">
                               <CDS FEAT_NAME = "162.c05244" COORDS = "60431-60224"/>
                       </EXON>
                       <EXON FEAT_NAME = "162.e18657" COORDS = "60160-59809">
                               <CDS FEAT_NAME = "162.c05245" COORDS = "60160-59809"/>
                       </EXON>
                       <EXON FEAT_NAME = "162.e18658" COORDS = "59746-59343">
                               <CDS FEAT_NAME = "162.c05246" COORDS = "59746-59633"/>
                       </EXON>
               </MODEL>
       </TU>
</ASSEMBLY>
```
 
