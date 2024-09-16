<h3 align="center">
  LLM Inferencing and Optimization with OpenVINO
</h3>

<p align="center">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/AkhilAjithkumar473/Openvino_LLM_inferencing">
  
  <img alt="Views" src="https://img.shields.io/github/watchers/AkhilAjithkumar473/Openvino_LLM_inferencing">
</p>

<p align="center">
  <a href="#-about-the-project">About the Project</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-technologies">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-getting-started">Getting Started</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-how-to-contribute">How to Contribute</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
</p>

## 👨🏻‍💻 About the Project

# LLM Inferencing and Optimization with OpenVINO

## Objective
The objective of this project is to enable users to query content extracted from PDF files using a Large Language Model (LLM). We focus on optimizing and quantizing the LLM using Intel's OpenVINO toolkit along with advanced techniques such as LoRA (Low-Rank Adaptation) and QLoRA (Quantized LoRA) to enhance performance and efficiency. 

## Project Components

- **User Interface**: Developed using Gradio to facilitate user interaction with the LLM.
- **Query Processor**: Handles and interprets user queries based on the content of the uploaded PDF file.
- **PDF Parser**: Extracts and indexes content from PDF files for querying.
- **Vector Database**: Retrieves relevant information from the indexed PDF content based on query embeddings.
- **Inference Engine**: Executes optimized inferencing tasks on the CPU using ONNX Runtime with enhancements from OpenVINO.
- **Response Generator**: Formats and generates responses based on the processed query.

## Key Features

- **PDF Querying**: Users can upload PDF files and query the extracted content using natural language.
- **Optimization with OpenVINO**: Leverages OpenVINO for model optimization and performance improvements.
- **Quantization and Adaptation**: Implements LoRA and QLoRA techniques for efficient model adaptation and quantization.
- **User-Friendly Interface**: Gradio-based front-end for seamless interaction.

## 🚀 Technologies

Technologies used in this project:

- **Python**: Programming language for development.
- **Gradio**: Front-end library for creating user interfaces.
- **OpenVINO**: Toolkit for optimizing and accelerating deep learning models.
- **ONNX Runtime**: Runtime for executing models with OpenVINO optimizations.
- **LoRA**: Low-Rank Adaptation for efficient model tuning.
- **QLoRA**: Quantized LoRA for model quantization.
- **pandas**: Data manipulation and analysis.
- **scikit-learn**: Machine learning library.
- **numpy**: Numerical operations.

## 💻 Getting Started

**Clone the project and access the folder**

```bash
$ git clone https://github.com/yourusername/llm-inferencing-openvino.git && cd llm-inferencing-openvino
```

**Install dependencies**
```bash
$ pip install gradio openvino-toolkit onnxruntime pandas scikit-learn numpy
```

**Run the application**

```bash
# To generate the optimized model run all the cells in the notebook

# Start the Gradio interface
$ python inference.py
```

## 🤔 How to contribute

**Make a fork of this repository**

```bash
# Fork using GitHub official command line
# If you don't have the GitHub CLI, use the web site to do that.

$ gh repo fork AkhilAjithkumar473/Openvino_LLM_inferencing
```

**Follow the steps below**

```bash
# Clone your fork
$ git clone https://github.com/AkhilAjithkumar473/Openvino_LLM_inferencing.git && cd Openvino_LLM_inferencing

# Create a branch with your feature
$ git checkout -b my-feature

# Make the commit with your changes
$ git commit -m 'feat: My new feature'

# Send the code to your remote branch
$ git push origin my-feature
```

After your pull request is merged, you can delete your branch 

---

Made &nbsp;by Akhil Ajithkumar 👋 &nbsp;[See my linkedin](https://www.linkedin.com/in/akhil-ajithkumar-230b52220/)