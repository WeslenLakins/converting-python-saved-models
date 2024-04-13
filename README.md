# Converting Python Saved Models to TensorFlow.js Format

Welcome to the `converting-python-saved-models` GitHub repository. This project provides a comprehensive guide and toolkit for converting machine learning models from Python (specifically TensorFlow Keras) into the TensorFlow.js format, making them ready for use in web environments.

For a hands-on demonstration, please refer to the [Jupyter Notebook](https://github.com/WeslenLakins/converting-python-saved-models/blob/main/Converting_Models_Made_From_Python_to_TensorFlow_js_Format_with_the_TensorFlow_js_Command_Line_Converter.ipynb) included in this repository. It offers step-by-step instructions on converting a MobileNetV2 model from Keras format to TensorFlow.js, which you can follow to understand and apply to your own models.

## Project Overview

The primary objective of this project is to help users convert their existing machine learning models, saved in Python's `.h5` or `.pb` formats, into TensorFlow.js compatible models. This enables the deployment of machine learning capabilities directly into web applications, improving accessibility and usability across various platforms.

## Features

- **Detailed Guide**: Step-by-step instructions on converting models from Keras to TensorFlow.js.
- **Example Notebook**: An interactive Jupyter Notebook that demonstrates the conversion process using a MobileNetV2 model.
- **Support for Multiple Model Formats**: Conversion support for both `.h5` (Keras) and `.pb` (TensorFlow SavedModel) formats.

## Usage

To get started with the conversion process, follow the instructions provided in the Jupyter Notebook titled `Converting_Models_Made_From_Python_to_TensorFlow_js_Format_with_the_TensorFlow_js_Command_Line_Converter.ipynb`. This notebook will guide you through the process of setting up your environment, loading the model, and performing the conversion.

### Quick Start

1. Clone the repository:
   
   ```
   git clone https://github.com/WeslenLakins/converting-python-saved-models.git
   ```
   
2. Navigate to the project directory and open the Jupyter Notebook:
   
   ```
   cd converting-python-saved-models
   jupyter notebook
   ```
   
3. Follow the notebook instructions to convert your model.

## Requirements

- Python 3.6+
- TensorFlow 2.x
- TensorFlow.js
- Other dependencies are listed in the `requirements.txt` file.

## License

This project is open-sourced under the GPL-3.0 license. See the [LICENSE.md](LICENSE.md) file for more details.

## Support

If you encounter any problems or have questions, feel free to open an issue on the repository's [issue tracker](https://github.com/WeslenLakins/converting-python-saved-models/issues).

Happy converting!
