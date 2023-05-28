<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT LOGO -->
<br />
<div align="center">

  <h3 align="center">GTFO_Character_Voice_models</h3>

</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<br/></br>
<!-- ABOUT THE PROJECT -->
## About The Project


This project provides trained models for `audio to audio` simulation using so-vits-4.1, as training the model is resource intensive, but not so much for infering an audio.

This repo includes:
* All data sets used to train the models
* Default model
* Diffusion model
* Fusion model
* Sample of model



Dataset Source:
* [Hacket](https://youtu.be/eX5f9dVZP2A)
* [Woods](https://www.youtube.com/watch?v=UE5h4AowjoU)
* [Dauda](https://www.youtube.com/watch?v=kgdOFGUQMVA)
* [Bishop](https://www.youtube.com/watch?v=OJp-yALvqGU)

Examples:
* [Origional](so-vits-svc-4.1/Example_Audio/TestAudio_Origional.mp4)
* [Hacket](so-vits-svc-4.1/Example_Audio/TestAudio_Hacket.mp4)
* [Woods](so-vits-svc-4.1/Example_Audio/TestAudio_Woods.mp4)
* [Dauda](so-vits-svc-4.1/Example_Audio/TestAudio_Dauda.mp4)
* [Bishop](so-vits-svc-4.1/Example_Audio/TestAudio_Bishop.mp4)

Trained with [so-vits-svc](https://github.com/svc-develop-team/so-vits-svc/tree/4.0)



<!-- GETTING STARTED -->
## Getting Started

To use the models, you need to follow the instructions on [so-vits-svc](https://github.com/svc-develop-team/so-vits-svc/tree/4.0) or [so-vits-svc-fork](https://github.com/voicepaw/so-vits-svc-fork) for a better GUI and easier inference as no training is required.



### Installation
Dragging the folder into the so-vits-svc folder should work right away, otherwise, move models to designated folder based on description.
```
so-vits-svc-4.1
    │
    ├───configs
    │      ├───config.json - config file for default training
    │      └───diffusion.yaml - config file for diffusion training
    │   
    └───logs
          └───44k
                ├───D_(name of character).pth - file required for more training
                ├───(name of character)Kmeans.pt - fusion model
                └───diffusion
                        └───(name of character).pt - difussion model for character

data_set - dataset used for training, audio cut to slices.
```

<!-- USAGE EXAMPLES -->
## Usage

Select Default model, diffusion model, fusion model and respective config for training.

* Fusion model = cluster model
* You may not see the option for diffusion as it is a new feature, it is only provided in some versions of so-vits-forks





<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.




<!-- CONTACT -->
## Contact

NAinfini - na.infini@gmail.com

NA infini#6457 -Discord

Project Link: [GTFO_Character_Voice_models](https://github.com/NAinfini/GTFO_Character_Voice_models_sovits4.0)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

