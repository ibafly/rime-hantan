# 韓단

recipe: ℞ **`hantan`**
schema_id: hantan

A [Rime](https://rime.im) input schema for Korean.

N.B. The key bindings are pretty random for QWERT users. Please let me know in Github issues that you need a QWERT version.

## Install and Get Ready

- Put all 3 files under your rime's user directory
- In `default.custom.yaml` Add hantan (the schema_id) to `schema_list`
- Use keyboard shortcut to call out rime input menu then Choose 韓단.

## Why made this?

I kind of get used to single vowel layout in G**gle's Korean keyboard. But that's on Android and no alternatives was found on PC. Then hantan comes to play...

## What are mixed in hantan?

- The romanization idea and Hanja dict are from another recipe repo [LiGhauNgyan/rime-korean](https://github.com/LiGhauNgyan/rime-korean/blob/master/README.md)
- Vocab dict is `ko__hangugeo_hakseubyong_eohwi` 국립국어연구원《한국어 학습용 어휘》

## Key features

- Double typing a single vowel goes to its y-start-diphthong.
  - eg. type ㅏㅏ(aa) -> ㅑ
- Double typing a consonant goes to its tense or pumping version.
  - eg. type ㄷㄷ(tt) -> ㅌ while (d) -> ㄸ
  - eg. type ㅅㅅ (ss) -> ㅆ

## LICENSE

MIT
