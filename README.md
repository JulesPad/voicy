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
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![GNU Affero License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



![Project Logo](https://raw.githubusercontent.com/JulesPad/voicy/main/assets/voicy-logo.png)


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    
  <h3 align="center">Speak to AI</h3>

  <p align="center">
    Have a natural voice to voice conversation with ChatGPT anytime with a simple keyboard shortcut on Windows & MacOS
    <br />
    <a href="https://github.com/github_username/repo_name"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/JulesPad/voicy">View Demo</a>
    ·
    <a href="https://github.com/JulesPad/voicy/issues">Report Bug</a>
    ·
    <a href="https://github.com/JulesPad/voicy/issues">Request Feature</a>
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

What if you could access LLMs' huge power by using your voice with a simple shortcut? It is what Voicy allows you to do
  
As a huge multitasking power-user and of ChatGPT I found myself struggling to ask quick questions while doing something else, I also missed not having a simpler and more natural way to communicate.
  
If you are a multitasking power-user wanting to have access by voice to an AI assistant, an Iron Man fan wanting to reproduce Jarvis 🤖, or impress your friends with an actually smart voice assistant; Voicy is for you!

Here are some of the main features of Voicy 💡:
* Custom prompts, craft your entirely custom prompt to create whatever personality you want in ChatGPT. Or feel free to use the optimized Voicy prompt.
* Always-on shortcut, one you run the script Voicy will wait for the shortcut to be activated and will run in the background without you having to do anything
* Auto-install the required packages, no need to bother yourself with installing them; Voicy handles this for you. 
<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

Voicy's intallation is very simple and fast, you will only need to clone the repository and add your OpenAI and Elevenlabs API keys. Then simply choose the script that is made for your platfrom, and your are ready to go!

### Prerequisites

For Voicy to work you will need 2 API keys, one from OpenAI for ChatGPT and voice-to-text to work, and one from Elevenlabs for speech synthesis to work. 

For both APIs you get access to free credits:

* **OpenAI**: While creating an account with a never used phone number you have automatically $5 of free credit on your account. It is plenty enough to use Voicy for serval long months. 

* **Elevenlabs**: Once you created your Elevenlabs account you get 10K characters free that renew monthly. If you generate long answers regularly the free quota could become short for you. You can upgrade for $0.95 and then $5 monthly to get access to 30K characters. 

Here are some step by step tutorials to get your API key for [OpenAI](https://www.windowscentral.com/software-apps/how-to-get-an-openai-api-key) and  [Elevenlabs](https://docs.elevenlabs.io/authentication/01-xi-api-key)

### Installation

1. Get your free API keys
2. Clone the repo
   ```sh
   git clone https://github.com/JulesPad/voicy.git
   ```
3. Go to the installation path to find the scripts. Open the script that you want to use and move on to step 4
4. Once you have the Python script opened modify at the beginning of the script the 2 following variables:
   ```py
   openai.api_key = "YOUR_KEY"

   user = ElevenLabsUser("YOUR_KEY")
   ```
6. If you are on **MacOS** don't forget to allow input monitoring from your terminal in the system's settings. 
5. Feel free to modify the prompt and other parameters! Enjoy 😄


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

Voicy is made available with 2 keyboard shortcuts on each platfrom, feel free to modify them as you want ;)  

**Windows Shortcuts**
| Key Combination   | Action                                |
|-------------------|---------------------------------------|
| `Ctrl` + `Shift` + `C` | Start recording                  |
| `Ctrl` + `Shift` + `X` | Stop recording                   |

**MacOS Shortcuts**
| Key Combination   | Action                                |
|-------------------|---------------------------------------|
| `Ctrl` + `Option` + `Shift` + `C`| Start recording                  |
| `Ctrl` + `Option` + `Shift` + `X`| Stop recording                   |



<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap
  
Here is a non-exhaustive list of features that I would like to gradually add to Voicy

- [ ] Serval language support 
- [ ] Side pannel UX
- [ ] On-device operations for reduced latency 

See the [open issues](https://github.com/github_username/repo_name/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the AGPL-3.0 License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact
  
I would love to have a chat with you, feel free to contact me here:

Jules Padova - [@pad_jules](https://twitter.com/pad_jules) - julespadova5@gmail.com

Personnal Website / Portfolio : [julespadova.me](https://julespadova.me)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/JulesPad/voicy.svg?style=for-the-badge
[forks-shield]: https://img.shields.io/github/forks/JulesPad/voicy.svg?style=for-the-badge
[stars-shield]: https://img.shields.io/github/stars/JulesPad/voicy.svg?style=for-the-badge
[issues-shield]: https://img.shields.io/github/issues/JulesPad/voicy.svg?style=for-the-badge
[license-shield]: https://img.shields.io/github/license/JulesPad/voicy.svg?style=for-the-badge
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555

[contributors-url]: https://github.com/JulesPad/voicy/graphs/contributors
[forks-url]: https://github.com/JulesPad/voicy/forks
[stars-url]: https://github.com/JulesPad/voicy/stargazers
[issues-url]: https://github.com/JulesPad/voicy/issues
[license-url]: https://github.com/JulesPad/voicy/blob/main/LICENSE
[linkedin-url]: https://www.linkedin.com/in/jules-padova/


[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
