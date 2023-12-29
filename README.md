<a name="readme-top"></a>

# greenhouse
Greenhouse Monitoring with Raspberry Pi and Prometheus

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
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>


<!-- ABOUT THE PROJECT -->
## About The Project

Greenhouse Monitoring with Raspberry Pi and Prometheus 

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

This section should list any major frameworks/libraries used to bootstrap your project. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.

* [![Kubernetes][Kubernetes.com]][Kubernetes-url]
* [![Prometheous][Prometheus]][Prometheus-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>




<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* Install Kubernetes
  ```sh

  ```
* Install Prometheus
  ```sh
  
  ```
* Install module random
  ```sh
  pip install random2
  ```
  



### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

1. Install miniforge on raspberry pi or your computer [https://github.com/conda-forge/miniforge](https://github.com/conda-forge/miniforge)
2. Go to desired workspace folder
   ```sh 
   cd ~/github/aquaponic_ws/source/greenhouse/
   ```
3. create new conda environment using miniforge
   For pc : 
   ```sh
   conda create -n env_pc_py38 python=3.8
   ```
   For raspi
   ```sh
   conda create -n env_raspi_py38 python=3.8
   ```
4. create new folder to indicate the env name
   ```sh
   mkdir env_pc_py38
   ```
5.activate miniforge conda environment
   ```sh
   source ~/mambaforge/bin/activate
   ```
7. Deactivate miniforge environment
   ```sh
   conda deactivate
   ```
8. Check your conda miniforge environment list
   ```sh
   conda env list
   ```
9. Activate newly conda environment
   ```sh
   conda activate env_pc_py38
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>
