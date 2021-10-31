# blog-transcode-for-youtube
Python sample application to transcode media to YouTube recommended settings.

## Getting Started

Here is how to set up and run this project locally.

### Prerequisites
* Install Python 3.8+
* Sign up for a free Dolby.io account [here](https://dashboard.dolby.io/).
* Create a new application and save the Media API key.

![How to Create Dolby.io App and Get API Key](https://imgur.com/VKvQRio.gif)

### Installation and Usage
1. Clone this repo and change directory.
    ```sh
    $ git clone https://github.com/dolbyio-samples/blog-transcode-for-youtube

    $ cd blog-transcode-for-youtube
    ```
    
2. Install required packages.
    ```sh
    $ pip3 install -r requirements.txt 
    ```
    
4. Create environment variable to store your Dolby.io Media API key.
    ```sh
    $ export DOLBYIO_API_KEY=$DOLBYIO_API_KEY
    ```
    OR

    ```sh
    $ echo "DOLBYIO_API_KEY=$DOLBYIO_API_KEY" > .env

    ```

3. Run the code to transcode the video file in [/videos/input/](/videos/input/).
    ```sh
    $ python3 ./src/main.py
    ```
