# Udacity FEND- Project #6:  FOODNESS - Restaurant Reviews App (stage 1)

This project consists of three stages, and the goal is to incrementally convert a static webpage to a mobile-ready web application.


## Running instructions

### Web live
Visit:

### Run locally
*   Download the repository: click download ZIP on the right of the screen and extract the zip file to your computer or clone the repository using Git.
*   Navigate to where you unzipped the file or cloned the repository.
*  In this folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer. However, if you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.


### Set up yor server with Python
* In a terminal, check the version of Python you have:

    ```python -V```

* If you have Python 2.x, spin up the server with

    ```python -m SimpleHTTPServer 8000```

    - This project uses port 8000.


* For Python 3.x, you can use
    ```python3 -m http.server 8000```
    or
    ```py -m http.server 8000```

### Visit the site
* With your server running, in your browser, navigate to the site: `http://localhost:8000`

* Check out the website! For bonus points: in Dev Tools,  disconnect the internet or set the throttling to a low Internet speed to check out the offline experience of the app!


## Tasks of stage 1 (akka what I did)

### Responsiveness and Accessibility
In **Stage One**, we took a static design that lacks accessibility and convert the design to be responsive on different sized displays and accessible for screen reader use.

I tried my best to follow best practices of A11Y

I redesigend a the page a bit - giving it a new UI. Here are the mockups:

![Foodness UI]()

![Foodness Mockups]()

However, under the hood, functionality is the same as the original.

### Embeding Google Maps

We had a choice to use Leaflet with Mapbox or Google Maps. I picked Google Maps because I have never worked with them before and wanted to learn it.  Google recently (June 11, 2018) changed their API policies so it was a bit of a challenge, but I made it! It works!

### Offline experience
The other important partof this task was to add a service worker to begin the process of creating a seamless offline experience for the users.

## References
*   Original repo: [MWS Restaurant Stage 1 by Udacity](https://github.com/udacity/mws-restaurant-stage-1)

## Author
* [**Ozana Buljan**](https://github.com/ozana-buljan)
* *Initial work* - [Udacity](https://github.com/udacity/mws-restaurant-stage-1)
* Codeowners: @forbiddenvoid @hbkwong

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments
Thanks to Udacity, my mentor and my classmates for this opportunity and all the support!
