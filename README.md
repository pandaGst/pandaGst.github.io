<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Audio Samples</title>
  <style>
body {
  margin:0;
  padding:10px 30px;
  background: #fff;
  color: #111;
  font-size: 15px;
  font-family: sans-serif;
  font-weight: 400;
  line-height: 1.8;
  overflow-x: hidden;
  -webkit-font-smoothing: antialiased;
}
audio {
  width: 180px !important;
  margin-right: 10px;
}
.sample {
  font-size: 0.9em;
  font-style: italic;
  border: 1px solid #ddd;
  padding: 1em;
  margin-bottom: 1em;
}
</style>
</head>
<body>
    <h2>Audio samples for paper: Code-Switched Speech Synthesis using Bilingual Phonetic Posteriorgram with Only Monolingual Corpora. </h2>

  <div><b>Authors:</b> Yuewen Cao, Songxiang Liu, Xixin Wu, Shiyin Kang, Peng Liu, Zhiyong Wu, Xunying Liu, Dan Su, Dong Yu, Helen Meng</div>
<!--     <div><b>Abstract:</b> State-of-the-art text-to-speech (TTS) synthesis models can produce monolingual speech with high intelligibility and naturalness. However, when the models are applied to synthesize code-switched (CS) speech, the performance declines seriously. Conventionally, developing a CS TTS system requires multilingual data to incorporate language-specific and cross-lingual knowledge. Recently, end-to-end (E2E) architecture has achieved satisfactory results in monolingual TTS. The architecture enables the training from one end of alphabetic text input to the other end of acoustic feature output. In this paper, we explore the use of E2E framework for CS TTS, using a combination of Mandarin and English monolingual speech corpus uttered by two female speakers. To handle alphabetic input from different languages, we explore two kinds of encoders: (1) shared multilingual encoder with explicit language embedding (LDE); (2) separated monolingual encoder (SPE) for each language. The two systems use identical decoder architecture, where a discriminative code is incorporated to enable the model to generate speech in one speaker's voice consistently. Experiments confirm the effectiveness of the proposed modifications on the E2E TTS framework in terms of quality and speaker similarity of the generated speech. Moreover, our proposed systems can generate controllable foreign-accented speech at character-level using only mixture of monolingual training data. </div> -->
  <div><b>Corpora:</b> American English speech corpus from Blizzard challenge 2011 and Mandarin speech corpus from Data-baker's open-source website.</div> 
  <div><b>Notes:</b> All utterances below are unseen by the systems during training.</div> 


    <h3>System Comparison</h3>
    <div>
    <table>
    <tr><td> <strong>PY-AP</strong>: Tonal pinyin for mandarin and alphabet for English.</td></tr> 
    <tr><td> <strong>PY-UP</strong>: Tonal pinyin for mandarin and uppercase for English..</td></tr>         
    <tr><td> <strong>PY-PY</strong>: Tonal pinyin for both Mandarin and English. </td></tr>
    <tr><td> <strong>PY-PH</strong>: Tonal pinyin for mandarin and CMU-phonemes for English. </td></tr>
    <tr><td> <strong>*_AUG</strong>: Data augmentation by pure English data. </td></tr>
    </table>
    </div>

<br> 
<h3>Result</h3>
<p>1. "CDMA手机防窃听。（74）"</p>
<table style="width:100%">
</table>
      <table style="width:100%">
      <tbody><tr>
        <th>PY-AP</th>
        <th>PY-AP_AUG</th>
        <th>PY-UP</th>
        <th>PY-UP_AUG</th>
        <th>PY-PY</th>
        <th>PY-PY_AUG</th>
        <th>PY-PH</th>
        <th>PY-PH_AUG</th>
      </tr>
      <tr>
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-AP/wav-batch_74_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th> 
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-AP_AUG/wav-batch_74_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th>
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-UP/wav-batch_74_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th>
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-UP_AUG/wav-batch_74_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th>  
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-PY/wav-batch_74_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th> 
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-PY_AUG/wav-batch_74_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th>
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-PH/wav-batch_74_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th>
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-PH_AUG/wav-batch_74_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th>        
      </tr>
      </tbody></table>  



<p>2. "而他也在继二零一七年KPL春季赛MVP和二零一七年冠军杯MVP后第三次获MVP的荣耀。（129）"</p>
<table style="width:100%">
</table>
      <table style="width:100%">
      <tbody><tr>
        <th>PY-AP</th>
        <th>PY-AP_AUG</th>
        <th>PY-UP</th>
        <th>PY-UP_AUG</th>
        <th>PY-PY</th>
        <th>PY-PY_AUG</th>
        <th>PY-PH</th>
        <th>PY-PH_AUG</th>
      </tr>
      <tr>
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-AP/wav-batch_129_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th> 
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-AP_AUG/wav-batch_129_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th>
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-UP/wav-batch_129_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th>
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-UP_AUG/wav-batch_129_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th>  
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-PY/wav-batch_129_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th> 
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-PY_AUG/wav-batch_129_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th>
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-PH/wav-batch_129_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th>
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-PH_AUG/wav-batch_129_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th>        
      </tr>
      </tbody></table>  





<p>3. "华为nova四配置曝光。(138)"</p>
<table style="width:100%">
</table>
      <table style="width:100%">
      <tbody><tr>
        <th>PY-AP</th>
        <th>PY-AP_AUG</th>
        <th>PY-UP</th>
        <th>PY-UP_AUG</th>
        <th>PY-PY</th>
        <th>PY-PY_AUG</th>
        <th>PY-PH</th>
        <th>PY-PH_AUG</th>
      </tr>
      <tr>
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-AP/wav-batch_138_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th> 
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-AP_AUG/wav-batch_138_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th>
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-UP/wav-batch_138_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th>
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-UP_AUG/wav-batch_138_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th>  
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-PY/wav-batch_138_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th> 
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-PY_AUG/wav-batch_138_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th>
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-PH/wav-batch_138_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th>
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-PH_AUG/wav-batch_138_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th>        
      </tr>
      </tbody></table>  


 

<p>4. "黎贝卡office小程序。(53)"</p>
<table style="width:100%">
</table>
      <table style="width:100%">
      <tbody><tr>
        <th>PY-AP</th>
        <th>PY-AP_AUG</th>
        <th>PY-UP</th>
        <th>PY-UP_AUG</th>
        <th>PY-PY</th>
        <th>PY-PY_AUG</th>
        <th>PY-PH</th>
        <th>PY-PH_AUG</th>
      </tr>
      <tr>
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-AP/wav-batch_53_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th> 
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-AP_AUG/wav-batch_53_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th>
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-UP/wav-batch_53_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th>
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-UP_AUG/wav-batch_53_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th>  
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-PY/wav-batch_53_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th> 
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-PY_AUG/wav-batch_53_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th>
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-PH/wav-batch_53_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th>
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-PH_AUG/wav-batch_53_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th>        
      </tr>
      </tbody></table>  




<p>5. "橄榄球靠往地上趴,叫Touch down 。(104)"</p>
<table style="width:100%">
</table>
      <table style="width:100%">
      <tbody><tr>
        <th>PY-AP</th>
        <th>PY-AP_AUG</th>
        <th>PY-UP</th>
        <th>PY-UP_AUG</th>
        <th>PY-PY</th>
        <th>PY-PY_AUG</th>
        <th>PY-PH</th>
        <th>PY-PH_AUG</th>
      </tr>
      <tr>
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-AP/wav-batch_104_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th> 
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-AP_AUG/wav-batch_104_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th>
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-UP/wav-batch_104_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th>
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-UP_AUG/wav-batch_104_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th>  
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-PY/wav-batch_104_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th> 
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-PY_AUG/wav-batch_104_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th>
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-PH/wav-batch_104_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th>
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-PH_AUG/wav-batch_104_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th>        
      </tr>
      </tbody></table>  



<p>6. "You raise me up太好听了。(149)"</p>
<table style="width:100%">
</table>
      <table style="width:100%">
      <tbody><tr>
        <th>PY-AP</th>
        <th>PY-AP_AUG</th>
        <th>PY-UP</th>
        <th>PY-UP_AUG</th>
        <th>PY-PY</th>
        <th>PY-PY_AUG</th>
        <th>PY-PH</th>
        <th>PY-PH_AUG</th>
      </tr>
      <tr>
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-AP/wav-batch_149_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th> 
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-AP_AUG/wav-batch_149_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th>
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-UP/wav-batch_149_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th>
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-UP_AUG/wav-batch_149_sentence_0-linear.wavv" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th>  
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-PY/wav-batch_149_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th> 
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-PY_AUG/wav-batch_149_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th>
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-PH/wav-batch_149_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th>
        <th>
                <audio controls="" style="width: 100px;">
                  <source src="./PY-PH_AUG/wav-batch_149_sentence_0-linear.wav" type="audio/mpeg">
                Your browser does not support the audio element.
                </audio>
        </th>        
      </tr>
      </tbody></table>  



</body>
</html>



