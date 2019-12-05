# Effects-of-Skip-Connections-in-CNN-based-Architectures-for-Speech-Enhancement
In this repository, we present some demos about the some speech enhancement based on CNN architectures with skip connection. In the feature, we will upload codes realted to this work.


# samples<br>
        clean: 1 utterance.<br>       
        senn_noise: 16 noise types appared in training stage.<br>
        unseen_noise: 4 noise types didn't appared in training stage <br>
        seen_nosiy:  mixed seen noise to clean, totall 16 utterances <br>
        seen_enhanced: <br>
                      CNN0: using CNN0 structure enhanced speech <br>
                      CNN1: using CNN1 structure enhanced speech <br>
                      CNN2: using CNN2 structure enhanced speech <br>
                      wiener: using wiener filtering enhanced speech <br>
        unseen_noisy: mixed unseen noise to clean, totall 4 utterances <br>
        unseen_enhanced: <br>
                        CNN0: using CNN0 structure enhanced speech <br>
                        CNN1: using CNN1 structure enhanced speech <br>
                        CNN2: using CNN2 structure enhanced speech <br>
                        wiener: using wiener filtering enhanced speech <br>
        
# speech spectrum.pdf <br>
  In this file, we plot spectrumgram of one example audio, under seen noise condition with -6dB SNR. From those pictures, we can clearly see that wiener filtering can slightly attenuate noise, but it's distortion is serious as the same time. The three CNN structures proposed  in this work can perfectly recover clean speech. <br>
