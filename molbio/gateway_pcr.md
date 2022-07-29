Gateway cloning protocol

https://www.protocols.io/view/preparing-gene-of-interest-for-gateway-cloning-2-s-5jvg4n6?step=1

https://www.embl.de/pepcore/pepcore_services/cloning/cloning_methods/gateway/2step/



Template primers:

(For 1 step PCR)

attB1

5' GGGG ACA AGT TTG TAC AAA AAA GCA GGC T TC GCCACC (start codon) gene 3’

 

attB2

5' GGGG AC CAC TTT GTA CAA GAA AGC TGG GT C CTA (gene) 3’

rev comp

gene (TAG stop codon) G ACCCAGCTTTCTTGTACAAAGTGGTCCCC

 

To keep ORF 'open' for addition of C-terminal V5 tag:

attB2_open

5' GGGG AC CAC TTT GTA CAA GAA AGC TGG GT C (gene) 3’

rev comp

(penultimate codon) G ACCCAGCTTTCTTGTACAAAGTGGTCCCC

 

 

(For 2 step PCR)

 

**Gene specific forward primer (PCR 1):** 

5'-AA AAA GCA GGC T*NN* -(20 bp template specific sequence)-3'

5'-AA AAA GCA GGC T *TC GCCACC ATG* -(20 bp template specific sequence)-3'


 **Gene specific reverse primer (PCR 1):** 

5'-A GAA AGC TGG GT*N* -(20 bp template specific sequence)-3'

5'-A GAA AGC TGG GT C [STOP] -(20 bp template specific sequence)-3'

gene [STOP] G AC CCA GCT TTC T
 

**attB1 adapter primer (PCR 2):** 5'-GGG GAC AAG TTT GTA CAA AAA AGC AGG CT-3'

**attB2 adapter primer (PCR 2):** 5'-GGG GAC CAC TTT GTA CAA GAA AGC TGG GT-3'

 

GGGGACAAGTTTGTACAAAAAAGCAGGCT

​       5'-AAAAAGCAGGCT *TC GCCACC ATG*

 

 

attB1_PCR2_F

GGGGACAAGTTTGTACAAAAAAGCAGGCT

 

attB2_PCR2_R

GGGGACCACTTTGTACAAGAAAGCTGGGT

 