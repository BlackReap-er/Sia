

<p align="center">

  <img align = "center" src="/icon.png">
  <h3 align="center">Sia</h3>

  <p align="center">
    A browser extension that not only makes your browsing experience safe but also optimized.
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
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
    <li><a href="#api-setup">API Setup</a></li>
    <li><a href="#api-usage">API Usage</a></li>
    <li><a href="#outputs">Outputs</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
The idea came to us from some previous projects about making a browser extension that could automate the stuff and make net-surfing an awesome experience. There are a lot of people that get scammed everyday due to opening malicious links or get cyberbullied online, and they don't even realize that it's actually happening. People with Dyslexia can't read things on browsers properly. Or some of us might actually feel the need to get things read to us instead of actually reading it by ourselves. As a solution to all these problems and more, Sia was built.

### Built With

* [Flask](https://flask.palletsprojects.com/en/2.0.x/)
* [PyTorch](https://pytorch.org/)
* [JavaScript](https://www.javascript.com/)
* [NumPy](https://numpy.org/)
* [Pandas](https://pandas.pydata.org/)




<!-- GETTING STARTED -->
## Getting Started

Follow the instructions to setup the project locally!



### Installation

1. Clone this repository.
   ```sh
   git clone https://github.com/arungovindm2001/Sia.git
   ```

2. Open `chrome://extensions` within your Chrome browser.

3. Enable Development Mode.

4. Click on `Load unpacked` and select the cloned repository.

5. Click on the extensions button next to your browser address bar and pin Sia.

## API Setup

### Prerequisites(Only if testing API)

Make sure to have virtualenv package from python installed before proceeding to installation.
  ```sh
  pip install virtualenv
  ```

### Installation

1. Activate the virtual environment
   ```sh
   cd Sia/PyTorch-NLP-API
   virtualenv venv
   . venv/bin/activate
   ```
2. Install the required packages using pip
   ```sh
   pip install -r requirements.txt
   ```
3. Run the app
   ```sh
   python app.py
   ```

## API Usage
We have also built an API during the hackathon.
1. Detect malicious URL
```
https://safe-api.azurewebsites.net/predict?url=https://www.google.com
```
2. Detect toxic comment
```
https://safe-api.azurewebsites.net/predict/toxic?text="you are so dumb"
```
3. Localhost
```
https://127.0.0.1/predict?url="https://www.google.com"
https://127.0.0.1/predict/toxic?text="you are so dumb"
```

## Outputs
Help dyslexic people see content

![img1](https://user-images.githubusercontent.com/53506835/128630908-3af84ccf-fd16-40a0-bad0-d3ce57598500.gif)

Convert browser text into American Sign Language

![img2](https://user-images.githubusercontent.com/53506835/128631080-ed251da5-9cf7-4f28-8097-2e080369152d.gif)

Use Image Veil to hide images, magnify images or highlight words

![img3](https://user-images.githubusercontent.com/53506835/128631137-5a01ec4d-635d-44a3-8cea-f65d4d616621.gif)

Change font color or magnify images

![img4](https://user-images.githubusercontent.com/53506835/128631246-87452d5e-7d0f-4c50-8f11-4e0570d3ca7d.gif)

Use Color blind mode to get color under the texts

![img5](https://user-images.githubusercontent.com/53506835/128631327-059de0fd-b78c-437a-afbe-239b7abc61e2.gif)


(View the video demo for more examples)

<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/arungovindm2001/Sia/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.


