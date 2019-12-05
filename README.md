# Effects-of-Skip-Connections-in-CNN-based-Architectures-for-Speech-Enhancement
In this repository, we present some demos about the some speech enhancement based on CNN architectures with skip connection. In the feature, we will upload codes realted to this work.


#samples
        clean: 1 utterance       
        senn_noise: 16 noise types appared in training stage
        unseen_noise: 4 noise types didn't appared in training stage
        seen_nosiy:  mixed seen noise to clean, totall 16 utterances
        seen_enhanced:
                      CNN0: using CNN0 structure enhanced speech
                      CNN1: using CNN1 structure enhanced speech
                      CNN2: using CNN2 structure enhanced speech
                      wiener: using wiener filtering enhanced speech
        unseen_noisy: mixed unseen noise to clean, totall 4 utterances
        unseen_enhanced:
                        CNN0: using CNN0 structure enhanced speech
                        CNN1: using CNN1 structure enhanced speech
                        CNN2: using CNN2 structure enhanced speech
                        wiener: using wiener filtering enhanced speech
        
#speech spectrum.pdf
  In this file, we plot spectrumgram of one example audio, under seen noise condition with -6dB SNR. As we can clear see form pictures, 
