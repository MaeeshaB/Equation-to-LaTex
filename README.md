<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

![MIT License][license-shield]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/ahmed22002">
    <img src="https://cdn.pixabay.com/photo/2022/07/24/05/18/background-7341011_1280.jpg" alt="Logo" width="300">
  </a>

  <h3 align="center">Equation To LaTeX</h3>

  <p align="center">
    Digital Image Recognition of Handwritten Mathematical Expressions
    <br />
    <a href="https://github.com/ahmed22002/Equation-to-LaTex/tree/main/docs"><strong>Explore the docs »</strong></a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#collaborators">Collaborators</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

Mathematics is relevant to every industry. As the world is becoming more technology-driven, it has become essential to automate the digitization of handwritten mathematical expressions to reduce the manual and redundant nature of this work.

The main goal of our project is to create a model that can take handwritten mathematical equations from an image upload or canvas and convert the equation to LATEXformat. The model takes the input and goes through a symbol segmentation process using OpenCV in Python. Then it uses a pre-trained model, which consists of architecture similar to Convolutional Neural Networks (CNN), and an Artificial Neural Network (ANN) classifier used for flattening. This allows the model to carry out feature extraction. Once each character of the equation is identified, the model recombines and outputs the equation in LATEXformat. The CNN model has a 93% testing accuracy. To demonstrate this model, a web application was built using the Python Flask web framework.


<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With
<img src="https://upload.wikimedia.org/wikipedia/commons/f/f8/Python_logo_and_wordmark.svg" style="height: 50px;"/>
</br>
<img src="https://upload.wikimedia.org/wikipedia/commons/c/c6/PyTorch_logo_black.svg" style="height: 50px;"/>
 </br>
<img src="https://upload.wikimedia.org/wikipedia/commons/3/3c/Flask_logo.svg" style="height: 50px;"/>
<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

### Installation

Clone the repo
   ```sh
   git clone https://github.com/ahmed22002/Equation-to-LaTex
   ```
Run the following shell command install dependencies
   ```sh
   $ pip install -r requirements.txt
   ```
Build & Run project so it's usable on a browser.
<p align="right">(<a href="#readme-top">back to top</a>)</p>




## Collaborators

| Team Member    | Email                           |
| -------------- | ------------------------------- |
| Muhammad Ahmed | mm.ahmed@mail.utoronto.ca       |
| Maeesha Biswas | maeesha.biswas@mail.utoronto.ca |
| Tracy Sun      | tracy.sun@mail.utoronto.ca      |



<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Your Name - mm.ahmed@mail.utoronto.ca

Project Link: [https://github.com/your_username/repo_name](https://github.com/ahmed22002/Equation-to-LaTex)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/mm-ahmed
[product-screenshot]: images/screenshot.png
