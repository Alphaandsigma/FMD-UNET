
FMD-UNet:Fine-Grained Feature Squeeze and Multiscale Cascade Dilated Semantic Aggregation Dual-Decoder UNet for COVID-19 Lung Infection Segmentation from CT Images

The automated segmentation of COVID-19 infection areas, facilitated by computer-aided diagnosis, holds 
considerable promise for aiding in the timely diagnosis and recovery of patients in clinical settings. Currently, 
methods relying on U-Net are ineffective in leveraging fine-grained semantic information from input images and 
face challenges in addressing semantic gaps between the encoder and decoder. To address these problems, this paper 
proposes a dual decoder U-Net network called FMD-UNet, which integrates fine-grained feature squeeze (FGFS) 
and multiscale cascade dilated semantic aggregation. The FMD-UNet shares input information from a common 
encoder to both the FGFS decoder and the multiscale dilated semantic aggregation (MDSA) decoder, enabling 
decoding and predictive segmentation at different levels. The FGFS decoder produces a finely detailed feature map 
via compression of fine-grained features, thereby directing the network to acquire fine-grained semantic information.
To optimize loss output, we apply full-resolution depth supervision to the fine-grained fusion information of the 
FGFS decoder. Moreover, in order to further improve the accuracy of FMD-UNet, the MDSA decoder progressively 
aggregates shallow and deep semantic information from the encoder through the multiscale semantic aggregation 
module, multiscale dilated semantic aggregation module, and multiscale cascade dilated semantic aggregation 
module before outputting predictions. It is noteworthy that the MDSA decoder ingeniously employs progressively 
expanding dilation convolutions to capture an extensive amount of contextual information, while effectively curbing 
the increase in model parameters. Furthermore, FMD-UNet was evaluated on two public available datasets and 
achieved the Dice similarity coefficient (DSC) of 84.76%, 78.56%, respectively. Experimental results show that the 
proposed FMD-UNet not only exhibits robustness and generalizability but also achieves accurate segmentation with 
fewer parameters and lower computational expenses.
