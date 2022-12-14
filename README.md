# node-red-contrib-ffmpeg-iotcam

[node-red](https://flows.nodered.org/node/node-red-contrib-ffmpeg-iotcam)

Capture and save to image from iotcam using ffmpeg.
Based on node-red's **exec** node.
<br>

## Pre-requisites

-   node-red
-   ffmpeg

<br>

## Installation

    npm i node-red-contrib-ffmpeg-iotcam

<br>

## Usage

### Input

-   `SmartThings MNID`: Samsung smartthings developer MNID
-   `SmartThings PAT`: Samsung SmartThings developer Personal Access Token
-   `RTSP Stream URL`: Video Stream URL. If input msg has propertie `msg.rtspURL` this will be replaced that value
-   `Image save URL`: Location where image to be stored. If input msg has propertie `msg.saveURL` this will be replaced that value
-   `Total Frame`: Number of frames to save
-   `Timer`: How many seconds to capture
-   `Name`: Node's name

[How to use Bixby Nodes](https://sasm.developer.samsung.com/tutorials/article_2_4)  
[How to use SmartThings Nodes](https://sasm.developer.samsung.com/tutorials/article_2_3)

<br>

## Example flow

-   [Basic flow](https://flows.nodered.org/flow/79184eba802a9d2cf44885f0b5a94a66)
-   [Trained model with Smartthings and mediapipe](https://flows.nodered.org/flow/b44ca6dede78702d287c393bb922a8cb)

## Authors

[TeamWildWest in SSAFY(Samsung Software Academy for Youth)](https://github.com/TeamWildWest)

<br>

## Copyright and license

Copyright Samsung Automation Studio Team under [the Apache 2.0 license](https://www.apache.org/licenses/LICENSE-2.0).

<br>

## Reference

-   [Node-RED Creating Nodes](https://nodered.org/docs/creating-nodes/)
-   [SamsungAutomationStudio Github Repository](https://github.com/Samsung/SamsungAutomationStudio)
-   [ffmpeg](https://www.ffmpeg.org/)
