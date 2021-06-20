## - Introduction
分类存放语音技术、对抗算法和防御的文章（文章，代码，简介，链接，会议/期刊，年份），目前主要包括语音识别和声纹识别两大领域的论文。

---
## - Speech Recognition

### 【1】Survey
### 【2】Attack Papers
1. #### CommanderSong: A Systematic Approach for Practical Adversarial Voice Recognition [[paper](https://www.usenix.org/system/files/conference/usenixsecurity18/sec18-yuan.pdf)]  [[video](https://www.usenix.org/conference/usenixsecurity18/presentation/yuan-xuejing)] [[code]()] [[method]()] USENIX2018</br>
  方法简介：在歌曲中嵌入指令。对kaldi里的“ASpIRE Chain Model” 攻击，模型是HMM-DNN，指定command，载体声音向command的token序列定向移动。

2. #### 隐藏语音命令[[paper](https://security.cs.georgetown.edu/~tavish/hvc_usenix.pdf)] [[video] (https://www.usenix.org/conference/ usenixsecurity16 / technical-sessions / presentation / carlini)] USENIX2016 
remain to be introduced
### 【3】Defense Papers
### 【4】Related Techniques

---
## - Speaker Recognition/Verfication
### 【1】Survey
### 【2】Attack Papers
1. #### Learning to fool the speaker recognition. [Jiguo Li, ..] ([paper](https://arxiv.org/abs/2004.03434)、[code](https://github.com/smallflyingpig/learning-to-fool-the-speaker-recognition)、[Web](https://smallflyingpig.github.io/speaker-recognition-attacker/main))    ICASSP 2020 
2. #### Attack on Practical Speaker Verification Systerm Using Universal Adversarial Perturbations.([Paper](https://arxiv.org/pdf/2105.09022.pdf)) ICASSP 2021
### 【3】Defense Papers
1. #### Adversarial Defense for Deep Speaker Recognition Using Hybrid Dversarial Training. [Monisankha Pal, Arindam Jati..] ([paper](https://arxiv.org/abs/2010.16038))   ICASSP 2021
2. #### Adversarial Defense for Automatic Speaker Verification by Cascaded Self-Supervised Learning Models. [Haibin Wu;Xu Li..] ([paper](https://ieeexplore.ieee.org/document/9413737?denied=))  ICASSP2021
3. #### Voting for the right answer: Adversarial defense for speaker verification.([paper](https://arxiv.org/pdf/2106.07868.pdf))   InterSpeech 2021
### 【4】Related Techniques
