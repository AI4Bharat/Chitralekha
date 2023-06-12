
<p align="center">
  <a href="https://chitralekha.ai4bharat.org"><img src="https://github.com/AI4Bharat/Chitralekha-App/blob/master/docs/chitralekha/logos/chitralekha-logo.png?raw=true" alt="Chitralekha" width="500" height="110"></a>
</p>

<p align="center">
    <em>An open source video transcreation platform for Indic languages using ML models</em>
</p>

<p align="center">
    <a href="https://opensource.org/licenses/MIT" target="_blank">
        <img src="https://img.shields.io/badge/License-MIT-green.svg" alt="License: MIT">
    </a>
</p>

***

*[Chitralekha](http://chitralekha.ai4bharat.org/)* is an open source platform for video transcreation across various Indic languages, using ML model support (ASR for Transcription, NMT for Translation and TTS for Voice-over)

Chitralekha offers support for multiple input sources (Ex : Youtube, local), transcription generation process (Ex : Models, Source captions, Custom subtitle files, manually created), translation generation process (Models, manually created) and voice-over generation process (Models, manually created). Currently, Chitralekha supports voice-over for only single speaker videos. Support for multi-speaker videos is under development.  

<br>

## Qualities of a good Subtitling Ecosystem
<p align="center">
  <img src="https://github.com/AI4Bharat/Chitralekha-App/blob/master/docs/chitralekha/images/transcription-editing-ecosystem.png"  width="800" height="350">
</p>

## Challenges faced by Transcriptionists
<p align="center">
  <img src="https://github.com/AI4Bharat/Chitralekha-App/blob/master/docs/chitralekha/images/editor-challenges.png"  width="800" height="420">
</p>

## Why Chitralekha?
In current world, there are numerous informative videos available online. Mostly they are associated with very few languages. The usefulness of the content can be increased by creating the sub-titles and voice-over of these across various Indic languages. 
With millions of hours of video contents, it becomes harder to manually create the multi-lingual sub-titles. This is where Chitraleka comes to the rescue.

The existing state-of-the-art ASR, Translation ML and TTS models can power the Chitralekha tool, to provides the platform for the Transcriptionists/Translators to create the multi-lingual sub-titles at scale with high accuracy. 


## Goals
* Support all possible video sources and languages
* Build a reliable & scalable platform beneath Chitralekha
* Keep the UI simple and intuitive


## Features of Chitralekha
### `Import from YouTube` 
Chitralekha supports importing videos and optional subtitles from YouTube. It also enables export of the subtitles in standard formats which can be used to update videos on YouTube.

### `Translation Support` 
Chitralekha supports translating the transcription into English and 12 Indian languages supported by IndicTrans model. Eventually it would be a Plug & Play feature.

### `Transcription Support` 
Chitralekha supports transcribing the input video with IndicASR for English and 9 Indian languages. This automatically creates timestamped transcription cards which can be edited. Eventually it would be a Plug & Play feature.

### `Transliteration Support` 
Chitralekha supports editing the transcriptions both in the source and target languages in Roman characters with IndicXlit support.

### `Voice-over Support` 
Chitralekha supports voice-over generation for the translated subtitles of the input video with IndicTTS for Indian languages. This automatically creates timestamped voice-over audio files which can be edited by editing the subtitle text of that particular timestamp. 

## Overview and Demo Video
[![Chitralekha Overview & Demo](https://github.com/AI4Bharat/Chitralekha-App/blob/master/docs/chitralekha/images/chitralekha-demo.png)](https://www.youtube.com/watch?v=Jq3CcEb9pxQ) 


## Cloning this master repo

```
git clone --recurse-submodules https://github.com/AI4Bharat/Chitralekha
```

## Communication Forum
Any information/help/discussion required, can be taken up using the following link :
<br>
https://github.com/AI4Bharat/Chitralekha/discussions


## Code of Conduct
This project adheres to the Contributor Covenant [code of conduct](CODE_OF_CONDUCT.md).
By participating, you are expected to uphold this code. Please report unacceptable behavior to opensource@ai4bharat.org.

