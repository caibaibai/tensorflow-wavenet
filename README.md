Speech-to-Text-WaveNet : End-to-end sentence level Chinese speech recognition using DeepMind's WaveNet
=
A tensorflow implementation for Chinese speech recognition based on DeepMind's WaveNet: A Generative Model for Raw Audio. (Hereafter the Paper: https://arxiv.org/abs/1609.03499)

Version
---
Current Version : 0.0.1

Dependencies ( VERSION MUST BE MATCHED EXACTLY! )
---
1. python == 3.5
2. tensorflow == 1.0.0
3. librosa == 0.5.0

Dataset
---
清华30小时中文数据集：http://data.cslt.org/thchs30/standalone.html

Network Model
---
1. Data random shuffle per epoch
2. Xavier initialization
3. Adam optimization algorithms
4. Batch Normalization

Train the network
---
python3 train.py

Test the network
---
python3 test.py

Other resources
---
1. https://github.com/ibab/tensorflow-wavenet
2. https://github.com/buriburisuri/speech-to-text-wavenet#version
