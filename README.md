# Spleeter
**ONLY INTRODUCTION** to Spletter, an audio decomposition open-source work.


# What is Spleeter
page url: https://github.com/deezer/spleeter

download pretrained model: https://github.com/deezer/spleeter/releases/tag/v1.4.0
(cr: https://github.com/boy1dr/SpleeterGui/issues/188)


# Usage
spleeter separate -p spleeter:<pretrained_model> -o <destination_directory> <source_sound_file>

## Sample 
spleeter separate -p spleeter:2stems -o dst src/yanse_wanghaojue.mp3 
