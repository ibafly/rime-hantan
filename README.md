# 韓단

recipe: ℞ **`hantan`**
schema_id: hantan

A [Rime](https://rime.im) input schema for Korean.

## Install and Get Ready

- Put all 3 files under your rime's user directory
- In `default.custom.yaml` add hantan (the schema_id) to `schema_list`
- Click deploy in rime menu to let rime know&do your new changes
- Use keyboard shortcut to call out rime schema select menu then Choose 韓단

## Keyboard Layout
```
    Qㅊ /W /Eㅓ /Rㄹ /Tㄷㅌ/Yㅣ /Uㅜ /Iㅣ /Oㅗ /Pㅍ
      Aㅏ /Sㅅㅆ/Dㄸ /Fㅇ /Gㄲ /Hㅎ /Jㅈㅉ/Kㄱㅋ /Lㄹ 
        Zㅔ /Xㅐ /Cㅡ /Vㅣ /Bㅂㅃ/Nㄴ /Mㅁ
```

## Key Features

- Double typing a single vowel goes to its y-start-diphthong.
  - eg. type ㅏㅏ(aa) -> ㅑ
- Double typing a consonant goes to its corresponding tense or pumping version.
  - eg. type ㄷㄷ(tt) -> ㅌ while (d) -> ㄸ
  - eg. type ㅅㅅ (ss) -> ㅆ

## Why made this?

I kind of get used to single vowel layout of G**gle's Korean keyboard. But that's on Android and no alternatives was found on PC. So hantan comes to play...

## What are mixed in hantan?

- The romanization idea and Hanja dict are from another recipe repo [LiGhauNgyan/rime-korean](https://github.com/LiGhauNgyan/rime-korean/blob/master/README.md)
- Vocab dict is `ko__hangugeo_hakseubyong_eohwi` 국립국어연구원《한국어 학습용 어휘》
- [This article (무이단모음 키보드)](https://story.pxd.co.kr/962) talks about redesigning single-vowel-keyboard on mobile, which also helps.

## LICENSE

MIT
