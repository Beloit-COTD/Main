## Introduction
This document provides an overview of the codebase for the "COTD: Color of the day" web application developed for the hackathon. The project aims to assist color-blind individuals in identifying colors within images using a Google Teachable Machine AI model.

## Table of Contents
1. [Prerequisites](#prerequisites)
2. [Project Structure](#project-structure)
3. [Frontend](#frontend)
4. [AI Model (Google Teachable Machine)](#ai-model-google-teachable-machine)
5. [Usage](#usage)
6. [Contributing](#contributing)
7. [Limitations and FutureImprovements](#Limitations-and-FutureImprovements)

## Prerequisites
- Data Crawling(Python 3, Selenium 4)
- HTML/CSS/JavaScript knowledge
- A web server for deployment (e.g., Netlify)

## Project Structure
The project is divided into the following main components:

- `frontend/` : Frontend code for the web application.
- `model/` : Python code for web scraping and training the AI model.
- `static/` : Static assets like images and styles.
- `templates/` : HTML templates for rendering the web pages.

## Frontend
The frontend is built using HTML, CSS, and JavaScript. It allows users to upload an image and see the AI model's predictions for the most probable color. The key files in the frontend are:
- `index.html`: The main HTML file for the web application.
- `style.css`: CSS styles for the user interface.
- `main.js`: JavaScript code for handling image uploads and displaying results.

## AI Model (Google Teachable Machine)
The color prediction AI model used in this project was trained using Google Teachable Machine, an online platform for creating and training custom machine learning models. The model was trained to identify colors in images, and it's based on machine learning and deep learning techniques. The training process involved collecting and labeling images of various shades of 14 different colors from online sources. The trained model was then exported and integrated into the web application.

## Usage
To use the Color Blind Friendly web application, follow these steps:

1. Access the web application by visiting [https://main--bespoke-queijadas-1f410e.netlify.app/].
2. On the website, you can upload an image.
3. The Google Teachable Machine AI model will predict the most probable color within the image and display the results.

## Contributing
We welcome contributions to improve and expand this project. If you want to contribute, please follow these guidelines:
- Fork the repository.
- Create a new branch for your feature or bug fix.
- Make your changes and submit a pull request.

## Limitations and Future Improvements
The AI model has some limitations, including:
- A larger training dataset could lead to better accuracy.
- The dataset underwent some manual data cleaning, but better image quality data could significantly improve the model.
- Adding more categories of colors increases the difficulty for the model to identify colors.

If more time is available, potential future improvements may include:
- Enhancing the aesthetic design of the web application.
- Using more color-friendly designs for color-blind individuals.