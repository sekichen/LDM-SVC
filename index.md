# <center> LDM-SVC: Latent Diffusion Model Based Zero-Shot Any-to-Any Singing Voice Conversion with Singer Guidance </center>
## Abstract
<div style="text-align: justify"> Any-to-any singing voice conversion is a novel audio editing technique, aiming to convert the singing voice of one singer into that of another, given only a few seconds of singing data. However, during the conversion process, the issue of timbre leakage is inevitable: the converted singing voice still sounds like the original singer's voice. To better address the issue of timbre leakage, we propose the LDM-SVC method, which attempts to perform singing voice conversion in the latent space using a latent diffusion model. We trained a Variational Autoencoder structure using the noted open-source So-VITS-SVC project based on the VITS framework, and used this for our latent diffusion model training. Furthermore, we proposed a singer guidance training method, using a classifier-free inference method to further suppress the timbre of the original singer. Experiments show that our proposed method outperforms previous methods in both subjective and objective evaluations of timbre similarity.
</div> 

![arch](images/pic1.png)

<body>

<br>
<!-- <div align="center"> -->
<h3>  <br>target singer: 
    <audio src="https://github.com/zzftts/zzftts.github.io/raw/main/voice_conversion/sample3/8630_305213_000011_000000.wav" controls="controls"></audio>  
    source singer: 
    <audio src="https://github.com/zzftts/zzftts.github.io/raw/main/voice_conversion/sample3/8630_305213_000011_000000.wav" controls="controls"></audio><br>
    <br> converted wav: <br>
    FastSVC: 
    <audio src="https://github.com/zzftts/zzftts.github.io/raw/main/voice_conversion/sample3/convert/LJ005-0218.wav" controls="controls"></audio>
    DiffSVC:
    <audio src="https://github.com/zzftts/zzftts.github.io/raw/main/voice_conversion/sample3/convert/LJ007-0143.wav" controls="controls"></audio><br>
    So-VITS-SVC: 
    <audio src="https://github.com/zzftts/zzftts.github.io/raw/main/voice_conversion/sample3/convert/LJ008-0295.wav" controls="controls"></audio>
    + LDM:
    <audio src="https://github.com/zzftts/zzftts.github.io/raw/main/voice_conversion/sample3/convert/LJ016-0027.wav" controls="controls"></audio><br>
    + Singer Guidance 
    <audio src="https://github.com/zzftts/zzftts.github.io/raw/main/voice_conversion/sample3/convert/LJ019-0057.wav" controls="controls"></audio> <br>
    <!-- <audio src="https://github.com/zzftts/zzftts.github.io/raw/main/voice_conversion/sample3/convert/LJ033-0170.wav" controls="controls"></audio> 
    <audio src="https://github.com/zzftts/zzftts.github.io/raw/main/voice_conversion/sample3/convert/LJ035-0157.wav" controls="controls"></audio> 
    <audio src="https://github.com/zzftts/zzftts.github.io/raw/main/voice_conversion/sample3/convert/LJ036-0163.wav" controls="controls"></audio> 
    <audio src="https://github.com/zzftts/zzftts.github.io/raw/main/voice_conversion/sample3/convert/LJ040-0175.wav" controls="controls"></audio> -->
</h3>
<!-- </div>  -->