# Silk_v3_decoder

### 介绍

`silk-v3-decoder` 实现silk和pcm相互转码

`liblame` pcm编码成mp3

`libmad`  mp3解码成pcm

silk->pcm->mp3

mp3->pcm->silk


### 格式互换

```

 Silk.convertSilkToMp3(silkSrc,mp3Dst,rate);
 
 Silk.convertMp3ToSilk(mp3Src,silkDst,rate);
 
```
