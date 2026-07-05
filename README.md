ゲーセンにあるクリスタルが３つ揃ったら消えるパズルゲーム<br>
<br>
↓↓↓<br>
<a href="https://crystalorbs.netlify.app/" target="_blank">crystal orbs</a><br>

<img src="https://x.com/sirou445205/status/2073591132270043347/photo/1"><br>
<br>
<br>
## 音声差し替えれるようにした<br>
index.html <br>
// 後から音源ファイルを追加する場合は、ここに相対パスを入れる<br>
const AUDIO_SRC = {<br>
  shoot: 'sfx1.wav',<br>
  pop: 'sfx2.wav',<br>
  clear: 'sfx3.wav',<br>
  bgm: 'bgm.mp3',<br>
};<br>
