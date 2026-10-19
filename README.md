<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a id="readme-top"></a>

<!-- PROJECT SHIELDS -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT TITLE -->
<br />
<div align="center">
  <h3 align="center">JavaScript Interactivity Playground</h3>

  <p align="center">
    A small HTML/CSS/JavaScript exercise: an image preview gallery driven by mouse and keyboard
    events.
    <br />
    <a href="https://github.com/Elouahabi-Naoufal/javascript-interactivity-playground"><strong>Explore the repository »</strong></a>
    <br />
    <br />
    <a href="https://github.com/Elouahabi-Naoufal/javascript-interactivity-playground/issues">Report Bug</a>
    &middot;
    <a href="https://github.com/Elouahabi-Naoufal/javascript-interactivity-playground/issues">Request Feature</a>
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

This repository is a hands-on DOM exercise rather than a full application. It contains one page:
a photo gallery where hovering or focusing a thumbnail displays that image in a large preview box
and writes the image's `alt` text underneath it.

The JavaScript is intentionally small (`js/gallery.js`):

* `upDate(previewPic)` sets the preview box's background image and label.
* `unDo()` restores the placeholder background and prompt.
* `functionSet()` adds `tabindex="0"` to every `.preview` image on page load so the gallery can be
  driven with the keyboard as well as the mouse.

The six thumbnails are loaded from **external image URLs** (BlenderKit and other hosts), so the page
needs an internet connection to show them. There is no build step, package manager or test suite.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

* [![HTML5][html-shield]][html-url]
* [![CSS3][css-shield]][css-url]
* [![JavaScript][js-shield]][js-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

* A modern web browser.
* An internet connection for the externally hosted thumbnails.

### Installation

1. Clone the repository
   ```sh
   git clone https://github.com/Elouahabi-Naoufal/javascript-interactivity-playground.git
   cd javascript-interactivity-playground
   ```
2. Open `index.html` in a browser. No server or install step is required.
   ```sh
   xdg-open index.html   # Linux
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE -->
## Usage

* Hover over a thumbnail to show it in the large preview and display its caption.
* Move the pointer away to restore the prompt.
* Use `Tab` to move focus onto a thumbnail; focus triggers the same preview, and blur restores the
  prompt.
* Edit `index.html` to swap the image URLs and `js/gallery.js` to change the interaction.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->
## Roadmap

- [x] Hover preview with caption
- [x] Keyboard focus/blur support via `tabindex`
- [ ] Move image URLs to local assets so the gallery works offline
- [ ] Replace inline `onmouseover`/`onfocus` attributes with `addEventListener`
- [ ] Add more DOM exercises (tabs, accordion, form validation) under separate pages
- [ ] Add a basic HTML/CSS linting check

See the [open issues](https://github.com/Elouahabi-Naoufal/javascript-interactivity-playground/issues) for a full list of proposed features and known issues.

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

### Top contributors:

<a href="https://github.com/Elouahabi-Naoufal/javascript-interactivity-playground/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Elouahabi-Naoufal/javascript-interactivity-playground" alt="contrib.rocks image" />
</a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->
## License

No `LICENSE` file is bundled with this repository. This project is not licensed — all rights reserved.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

Naoufal Elouahabi
* LinkedIn: [https://www.linkedin.com/in/elouahabi-naoufal/](https://www.linkedin.com/in/elouahabi-naoufal/)
* Email: [elouahabi-naoufal1@gmail.com](mailto:elouahabi-naoufal1@gmail.com)

Project Link: [https://github.com/Elouahabi-Naoufal/javascript-interactivity-playground](https://github.com/Elouahabi-Naoufal/javascript-interactivity-playground)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [MDN Web Docs — DOM events](https://developer.mozilla.org/en-US/docs/Web/Events)
* [Best-README-Template](https://github.com/othneildrew/Best-README-Template)
* [Img Shields](https://shields.io)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/Elouahabi-Naoufal/javascript-interactivity-playground.svg?style=for-the-badge
[contributors-url]: https://github.com/Elouahabi-Naoufal/javascript-interactivity-playground/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Elouahabi-Naoufal/javascript-interactivity-playground.svg?style=for-the-badge
[forks-url]: https://github.com/Elouahabi-Naoufal/javascript-interactivity-playground/network/members
[stars-shield]: https://img.shields.io/github/stars/Elouahabi-Naoufal/javascript-interactivity-playground.svg?style=for-the-badge
[stars-url]: https://github.com/Elouahabi-Naoufal/javascript-interactivity-playground/stargazers
[issues-shield]: https://img.shields.io/github/issues/Elouahabi-Naoufal/javascript-interactivity-playground.svg?style=for-the-badge
[issues-url]: https://github.com/Elouahabi-Naoufal/javascript-interactivity-playground/issues
[license-shield]: https://img.shields.io/badge/License-All%20rights%20reserved-red.svg?style=for-the-badge
[license-url]: https://github.com/Elouahabi-Naoufal/javascript-interactivity-playground
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/elouahabi-naoufal/
[html-shield]: https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white
[html-url]: https://developer.mozilla.org/en-US/docs/Web/HTML
[css-shield]: https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white
[css-url]: https://developer.mozilla.org/en-US/docs/Web/CSS
[js-shield]: https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black
[js-url]: https://developer.mozilla.org/en-US/docs/Web/JavaScript
