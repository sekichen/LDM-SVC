<!DOCTYPE html>
<!-- saved from url=(0033)https://QicongXie.github.io/end2endvc/ -->
<html lang="en-US">

<head>
  <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">


  <!-- Begin Jekyll SEO tag v2.7.1 -->
  <title>DualVC: Dual-mode Voice Conversion using Intra-model Knowledge Distillation and Hybrid Predictive Coding</title>
  <meta name="generator" content="Jekyll v3.9.0">
  <meta property="og:title" content="TODO: title">
  <meta property="og:locale" content="en_US">
  <meta name="twitter:card" content="summary">
  <!-- End Jekyll SEO tag -->

  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="theme-color" content="#157878">
  <link rel="stylesheet" href="style.css">
</head>

<body data-new-gr-c-s-check-loaded="14.1001.0" data-gr-ext-installed="">
  <section class="page-header">
    <!-- <h1 class="project-name">Demo PAGE</h1> -->
    <!-- <h2 class="project-tagline"></h2> -->


  </section>

  <section class="main-content">
    <h1 id="">
      <center>DualVC: Dual-mode Voice Conversion using Intra-model Knowledge Distillation and Hybrid Predictive Coding</center>
    </h1>

    <h3 id="">
    <center>Ziqian Ning<sup>1, 2</sup>, Yuepeng Jiang<sup>1</sup>, Pengcheng Zhu<sup>2</sup>, Jixun Yao<sup>1</sup>, Shuai Wang<sup>3</sup>, Lei Xie<sup>1</sup>, Mengxiao Bi<sup>2</sup></center>
    <center><sup>1</sup>Audio, Speech and Language Processing Group (ASLP@NPU), School of Computer Science, Northwestern Polytechnical University, Xi'an, China</center>
    <center><sup>2</sup>Fuxi AI Lab, NetEase Inc., Hangzhou, China</center>
    <center><sup>3</sup>Shanghai Jiao Tong University, Shanghai, China</center>
    </h3>
    <center>Accepted by INTERSPEECH 2023</center>


    <br><br>
    <h2 id="abstract">1. Abstract<a name="abstract"></a></h2>
    <p>Voice conversion is an increasingly popular technology, and the growing number of real-time applications requires models with streaming conversion capabilities. Unlike typical (non-streaming) voice conversion, which can leverage the entire utterance as full context, streaming voice conversion faces significant challenges due to the missing future information, resulting in degraded intelligibility, speaker similarity, and sound quality. To address this challenge, we propose <b>DualVC</b>, a dual-mode neural voice conversion approach that supports both streaming and non-streaming modes using jointly trained separate network parameters. Furthermore, we propose intra-model knowledge distillation and hybrid predictive coding (HPC) to enhance the performance of streaming conversion.
      Additionally, we incorporate data augmentation to train a noise-robust autoregressive decoder, improving the model's performance on long-form speech conversion. Experimental results demonstrate that the proposed model outperforms the baseline models in the context of streaming voice conversion, while maintaining comparable performance to the non-streaming topline system that leverages the complete context, albeit with a latency of only 252.8 ms.</p>

    <table frame=void rules=none>
      <tr>
        <center><img src='raw/fig/overall.png'></center>
      </tr>
      <tr>
      </tr>
    </table>
    <br><br>


    <h2>2. Demos -- Voice Conversion<a name="Comparison"></a></h2>
    <ul>
      <li>Bottomline: Replace all convolution layers in the backbone model [1] with the causal version to create a naïve streaming implementation.</li>
      <li>IBF-VC: Reinplement [2] using the backbone model.</li>
      <li>Topline: Use the unmodified Backbone model which leverage full-context, but input BNF is extracted from a streaming ASR encoder.</li>
      <li>DualVC-nonstreaming: Non-streaming mode of our proposed DualVC.</li>
      <li>DualVC-streaming: Streaming mode of our proposed DualVC.</li>
    </ul>

    <table>
      <tbody id="tbody">
      </tbody>
    </table> 
    </br>
    <cite>[1] X. Tian, Z. Wang, S. Yang, X. Zhou, H. Du, Y. Zhou, M. Zhang, K. Zhou, B. Sisman, L. Xie et al., “The nus & nwpu system for voice conversion challenge 2020,” in Proc. Joint Workshop for the Blizzard Challenge and Voice Conversion Challenge 2020, 2020, pp. 170–17</cite>
    </br>
    <cite>[2] Y. Chen, M. Tu, T. Li, X. Li, Q. Kong, J. Li, Z. Wang, Q. Tian, Y. Wang, and Y. Wang, “Streaming voice conversion via intermediate bottleneck features and non-streaming teacher guidance,” CoRR, vol. abs/2210.15158, 202</cite>
  </section>
</body>

</html>

<script type="" text/javascript>
  window.onload = function () {
    let scenes = ["Clean", "Noisy"]
    let speakers = ["db_1", "M2VoC_male", "SSB1956", "SSB0273"]
    //let speakers = ["db_1", "M2VoC_male"]
    //let genders = ["female", "male"]
    let genders = ["female", "male", "aishell female", "aishell male"]
    let models = ["Bottomline", "Baseline", "Topline", "DualVC-nonstreaming", "DualVC-streaming"]
    let all_samples = [["1.wav", "4.wav", "biaobei_8315010.wav", "TenXiaozhi_007_000472.wav"], 
                    ["Y0000019527_oMwYDEEBw0g_S00489.wav", "Y0000019576_oVD68qz-Rrw_S00095.wav", "Y0000019686_omXo90yMpGc_S00895.wav", "Y0000019687_omf0WUsolCc_S00328.wav"]]
    let sample_data = `
        <tr>
          <td style="text-align: center; width: 150px;" rowspan=2><strong>Scenario<strong></td>
          <td style="text-align: center; width: 150px;" rowspan=2><strong>Target Speaker<strong></td>
          <td style="text-align: center; width: 150px;" rowspan=2><strong>Source speech<strong></td>
          <td style="text-align: center; width: 150px;" colspan=5><strong>Method<strong></td>
        </tr>
        <tr>
        `
    for (const id in models) {
      model = models[id]
      if (model == 'Baseline') {
        model = 'IBF-VC'
      }
      sample_data += '<td style="text-align: center; width: 150px;" rowspan=1><strong>' + model + '<strong></td>'
    }
    sample_data += "</tr>"
    console.log(sample_data)
    
    for (let x in scenes) {
      let scene = scenes[x]
      let scene_data = ""
      scene_data += '<tr>'
      scene_data += '<td style="text-align: center; width: 150px;" rowspan=' + 16 + '><strong>' + scene + ' Source' + '<strong></td>'
      let samples = all_samples[x]
      console.log(scene, samples)
      for (let y in speakers) {
        speaker = speakers[y]
        gender = genders[y]
        scene_data += '<td style="text-align: center; width: 150px;" rowspan=4>' + gender + '<audio style="width: 150px;"controls="" src="raw/samples/speakers/' + speaker + '.wav"></td>'
        for (let z in samples) {
          if (z != 0) {
            scene_data += '<tr>'
          }
          let sample = samples[z]
          scene_data += '<td style="text-align: center"><audio style="width: 150px;" controls="" src="raw/samples/' + scene + '/source/' + sample + '"></audio></td>'
          for (let w in models) {
            let model = models[w]
            console.log(speaker + model)
            if ((speaker == "SSB1956" || speaker == "SSB0273") && (model != "DualVC-streaming" && model != "DualVC-nonstreaming")) {
              console.log("!!!")
              scene_data += '<td style="text-align: center"><p>N/A</p></td>'
            } else {
              scene_data += '<td style="text-align: center"><audio style="width: 150px;" controls="" src="raw/samples/' + scene + '/' + model + '/' + speaker + '/' + sample + '"></audio></td>'
            }
          }
          scene_data += '</tr>'
        }
      }
      sample_data += scene_data
    }
    document.getElementById('tbody').innerHTML = sample_data
  }
</script>