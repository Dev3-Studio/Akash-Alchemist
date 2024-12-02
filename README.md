# Akash-Alchemist

## Overview
#### Akash Alchemist is an innovative image generation platform designed to transform text into stunning visuals. The process is simple yet powerful:
1. Enter a Prompt: Users provide a text description of the image they want to create.
2. Prompt Enhancement: The Akash Chat API, powered by advanced language models, refines the user-provided text prompt to maximize its potential and ensure optimal results.
3. Smart Settings Optimization: The Akash Chat API also determines the best generation settings based on the user's input, eliminating the guesswork and streamlining the process.
4. Image Generation: The enhanced prompt and settings are then used to create a high-quality image that matches the user's vision.

#### Akash Alchemist seamlessly integrates cutting-edge AI technology to make image creation intuitive, efficient, and enjoyable.

For more details on the project, please visit [Our Docs](https://dev3-studio.gitbook.io/akash-alchemist/)

## Services

### akash-alchemist-frontend
The `akash-alchemist-frontend` service is a web application that provides a user interface for controlling the `comfyui-wrapper-api` service. The frontend is built using React and is served through Next.js.

### comfyui-plus
The `comfyui-plus` service is a custom fork of ComfyUI with additional nodes for face detailing.

### comfyui-wrapper-api
The `comfyui-wrapper-api` service is a wrapper around the ComfyUI API that provides an easy-to-use interface for generating images based on text prompts.

## Deployment

### Akash Network
The `akash-sdl.yaml` file is used to define the deployment on the Akash Network.


### Docker Compose
The `docker-compose.yaml` file is used for local development / deployment to another service.

## Usage

### Local Development
To run the services locally using Docker Compose:
```sh
docker-compose up
```

## Deployment
For deployment instructions, please refer to the documentation on [gitbook](https://dev3-studio.gitbook.io/akash-alchemist/getting-started/quickstart)