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
  
  [中文版](README_ZH.md)
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
    </li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<br/></br>
<!-- ABOUT THE PROJECT -->
## About The Project


This project provides trained models for `audio to audio` simulation using so-vits-4.1, as training the model is resource intensive, but not so much for infering an audio. Every model included has been trained for at least 20K steps

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

https://github.com/NAinfini/GTFO_Character_Voice_models_sovits4.0/assets/68311621/702f1842-637b-41ca-958c-702ab315e8e3

https://github.com/NAinfini/GTFO_Character_Voice_models_sovits4.0/assets/68311621/4b0a5e2d-3316-44bb-ae0b-fcf948341489

https://github.com/NAinfini/GTFO_Character_Voice_models_sovits4.0/assets/68311621/c3efd11d-5858-4599-8ee6-9d988bbf701e

https://github.com/NAinfini/GTFO_Character_Voice_models_sovits4.0/assets/68311621/75132ed8-61c3-4937-9453-a86d3fbb8c4e

https://github.com/NAinfini/GTFO_Character_Voice_models_sovits4.0/assets/68311621/02463b44-4efb-4bb6-a202-72a4c1929dc3



Trained with [so-vits-svc](https://github.com/svc-develop-team/so-vits-svc/tree/4.0)



<!-- GETTING STARTED -->
## Getting Started

To use the models, you need to follow the instructions on [so-vits-svc](https://github.com/svc-develop-team/so-vits-svc/tree/4.0) or [so-vits-svc-fork](https://github.com/voicepaw/so-vits-svc-fork) for a better GUI and easier inference as no training is required.


Dragging the folder into the so-vits-svc folder should work right away, otherwise, move models to designated folder based on description.
```
so-vits-svc-4.1
    └───logs
          └───44k
                ├───G_(name of character).pth - Default model
                ├───(name of character)Kmeans.pt - fusion model
                ├───config(name of character)json - config file for default training
                ├───diffusion(name of character).yaml - config file for diffusion training
                └───diffusion
                        └───(name of character).pt - difussion model for character

data_set - dataset used for training, audio cut to slices.
```

<!-- USAGE EXAMPLES -->
## Usage

Select Default model, diffusion model, fusion model and respective config for training.
Note: Update the speaker in the config file to avoid key errors.
"Hacket_data_set,Dauda_data_set,Bishop_data_set,Woods_data_set"
If that does not work, try using pre process a folder with such names, and preconfig to set all configs with the same voice name. 
* Fusion model = cluster model
* You might not see the option for diffusion as it is a new feature, it is only provided in some versions of so-vits-forks





<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.
If used, please attatch link to the repo.



<!-- CONTACT -->
## Contact

NAinfini - na.infini@gmail.com

NA infini#6457 -Discord

Project Link: [GTFO_Character_Voice_models](https://github.com/NAinfini/GTFO_Character_Voice_models_sovits4.0)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

