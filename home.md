---
layout: page
title: "DaD Analytics"
permalink: /DaD_Analytics
---
## Examples
![mysql_example](https://github.com/andjnewb/andjnewb.github.io/assets/71988305/9fb707cb-2b76-401d-98e4-f4af9d3e561e)
![Capture](https://github.com/andjnewb/andjnewb.github.io/assets/71988305/bce7abe3-1494-43e5-8fdb-408e7dc64853)

## Inspirations 
<p>I started this project because I identified a major issue with the player market for items in Dark and Darker. The vast majority of item prices were pure speculation.
  The only way you can know if you're overpaying is by playing the game a lot, way more than most people can. I wanted to help remedy this issue. The developers are planning on introducing an 
  auction house style system which may help mitigate this issue.
</p>

## Tech Used 

<p>
I ended up settling on Roboflow for annotation and inference, Tesseract OCR for scanning the image clips that Roboflow spits out, MySQL for data storage, and Python to tie it all together.
I had originally used MongoDB, but it didn't work out because I don't have any experience with it. 
</p>

## Major Issues 

<ol>
  <li>Inference isn't possible locally on my current machine, due to issues with Docker and WSL</li>
  <li>Rarity isn't factored into the average price.</li>
  <li>Time isn't considered, so projects accuracy will change over time and will likely be skewed.</li>
  <li>This project needs a frontend!</li>
</ol>  

## Goals  

<p>I hope to get this project to a state where it can accurately track the market of Dark and Darker and help players make informed decisions about their purchases. I'm also hoping to continue developing my knowledge of all the technologies I have used so far.</p>
