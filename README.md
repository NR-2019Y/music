# music

## folder: res

### res/snowdreams res/Childhood_Memory_bandari
简谱文件，处理后的简谱（相关的MATLAB、mathematica播放代码）

## folder: script
Karplus-Strong Algorithm 和 Extended Karplus-Strong Algorithm等（MATLAB实现，模拟钢琴音效）

实现主要见 genNote4SecDbEKS.m，先构建音源，以后直接调用该音源就可以生成音频文件了 （BasicMusNote*.m 中的函数不推荐使用）

此外 res/db 文件夹里面有从 mp3cutterpro.com 提取出来的音源

应用案例见：res/snowdreams_oriversion 等（README文件）

使用 README.md 中的 MATLAB 代码时，注意 将 您的script所在目录 addpath

## folder: mid_and_mp3_file
mid文件，mp3等格式的音频（可由前面的MATLAB、mathematica代码生成）
