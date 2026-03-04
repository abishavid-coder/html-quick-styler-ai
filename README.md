[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/abishavid-coder/html-quick-styler-ai/blob/main/html_quick_styler.ipynb)

# HTML Quick Styler – AI Webpage Generator

## Overview

HTML Quick Styler is an AI-assisted tool that generates professional, responsive HTML/CSS webpages from simple natural-language descriptions. Users provide a website title, a short description of sections they want, and a preferred color theme. The system then generates structured HTML and modern CSS styling, producing a ready-to-use webpage layout.

The project demonstrates how AI-assisted workflows can accelerate web development using Python and an interactive UI.

---

## Key Features

* Generate complete HTML webpages from natural language descriptions
* Multiple predefined color themes (modern, vibrant, ocean, forest, sunset, luxury, creative, minimal)
* Automatic webpage section detection
* Responsive CSS layout for desktop, tablet, and mobile
* Interactive interface built with Gradio
* Instant preview of generated HTML code
* Download generated HTML output

---

## Technologies Used

* Python
* HTML5
* CSS3
* Gradio (UI framework)
* Google Colab (development environment)
* GitHub (project repository)

---

## Project Architecture

### 1. ColorPaletteGenerator

Generates predefined color palettes used to style webpages.

### 2. HTMLPageBuilder

Analyzes user input and determines which sections should appear in the webpage.

### 3. CSSGenerator

Creates responsive CSS styles based on the selected theme.

### 4. SectionTemplates

Provides reusable templates for webpage sections such as hero, features, portfolio, testimonials, and contact forms.

### 5. Gradio Interface

Provides the interactive UI where users input information and generate webpages.

---

## How the System Works

1. User enters a website title and description.
2. User selects a preferred color theme.
3. The application analyzes the description to identify sections.
4. HTML and CSS are automatically generated.
5. The user can preview or download the generated webpage.

---

## Project Workflow

1. Environment setup using Google Colab
2. Installation of required Python libraries
3. Development of HTML generation logic
4. Creation of CSS styling system
5. Building interactive interface using Gradio
6. Deploying the application using a public share link
7. Testing and validation of generated webpages

---

## Demo

A live interactive demo of the application is available via a public Gradio link.

Example format:

Demo Link:
https://cce3e4821900b589fa.gradio.live/


---

## GitHub Repository

Repository URL:
https://github.com/abishavid-coder/html-quick-styler-ai

---

## How to Run the Project

### Option 1 – Run in Google Colab

1. Click the **Open in Colab** button at the top of this README.
2. Run all notebook cells.
3. Launch the Gradio interface.
4. Use the generated public link to interact with the application.

### Option 2 – Run Locally

1. Clone the repository:
   git clone https://github.com/abishavid-coder/html-quick-styler-ai

2. Install required libraries:
   pip install gradio

3. Run the notebook or convert it to a Python script.

---

## Example Use Case

Input:
Title: Modern Portfolio Website
Description: Hero section, features list, portfolio gallery, testimonials, contact form and footer
Theme: Modern

Output:
A complete responsive HTML webpage with styling and structured sections.

---

## Future Enhancements

* Custom color picker support
* Integration with advanced AI models
* Drag-and-drop layout editing
* Component library for reusable UI blocks
* Export generated webpages as full project templates

---


---

## License

This project is created for educational purposes as part of the Agentic AI Application Development program.
