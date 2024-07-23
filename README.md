# Autoregressive Jazz Piano Music Generation from MIDI Tokens

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <img title="(C) https://www.analyticsvidhya.com/blog/2020/01/how-to-perform-automatic-music-generation/" alt="music robot" src="https://cdn.analyticsvidhya.com/wp-content/uploads/2020/01/auto-music-.jpg" >

  <h4 align="center">
    Bachelor Thesis in Artificial Intelligence <br> Johannes Kepler University Linz <br>
    

  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">Abstract</a>
    </li>
    <li>
      <a href="#getting-started">Usage</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## Abstract


The aim of this Bachelor Thesis is to test the generative abilities of GPT-2 style Autoregressive Transformer models, trained on MIDI-playalongs from the Jazz genre. It builds on my previous work in the Practical Project, where I extracted piano sources from the Aebersold dataset and converted them to
MIDI. I tested and evaluated three different models with the same model architecture but trained on
differently pre-processed data. When tasked to continue from jazz-style inputs, all three models exhibited basic structural understanding, but only limited rhythmic and harmonic coherence, especially when generating sequences longer than those they were trained on. 

You can read the complete thesis in <code> thesis.pdf </code> .
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Usage

To train your own models use <code> main.ipynb </code>, to test your models use <code> test.ipynb </code>.
Further instructions inside the respective notebooks.


### Installation


1. Clone the repo:
   ```sh
   git clone https://github.com/seb-son/bac-thesis.git
   ```
2. Create environment with python3.11 (conda) and activate:
   ```sh
   conda create --name <env-name> python=3.11
   ```
   ```sh
   conda activate <env-name>
   ```
3. 1. Install packages(conda):
   ```sh
   conda install --file requirements.txt
   ```
   2. Install packages(mamba - much faster):
   ```sh
   conda install mamba
   ```
   ```sh
   mamba install --file requirements.txt
   ```
4. Train a model with your own data and test it.

<p align="right">(<a href="#readme-top">back to top</a>)</p>




<!-- LICENSE -->
## License
This project is licensed under the GNU General Public License v3.0 (GPL-3.0). By using, modifying, or distributing this software, you agree to comply with the terms of the GPL-3.0. This license guarantees end users the freedom to run, study, share, and modify the software. Any distributed version, whether it is the original or a derivative work, must also be licensed under the GPL-3.0 to ensure that these freedoms are preserved. For more details, refer to the LICENSE file included in this repository or visit https://www.gnu.org/licenses/gpl-3.0.html.<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Due to copyright restrictions I can not publicly share the training data. 
For further information how to get training data, contact me.

Sebastian Sonderegger - K1246236 - K01246236@students.jku.at


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* Supervisor: Francesco Foscarin - ICP
* Institute: JKU - ICP 
* Readme-template: adapted from https://github.com/othneildrew/Best-README-Template

<p align="right">(<a href="#readme-top">back to top</a>)</p>




