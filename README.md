<div align="center">
<img src="https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png" alt="Project Logo">


Welcome to Class Diagram Visualizer, a Python application designed to provide a clear visual representation of your Python application's structure. 

[Explore the Docs 📚](https://empress.eco/) | 
[Report a Bug 🐛](https://github.com/empress-eco/class_diagram_visualizer/issues) |
[Request a Feature 🌟](https://github.com/empress-eco/class_diagram_visualizer/issues)

</div>


## 📖 About The Project

Class Diagram Visualizer simplifies understanding your application's architecture, making it easier to navigate and modify the codebase. Whether you're a developer, project manager, or software architect, this tool will help you better comprehend the underlying structure of your Python applications.

### Key Features 🌟
- Visualize class diagrams of Python applications
- Output in various formats (txt, img, all)
- Usable as a command-line tool or a Python module

### Built With 🛠
Class Diagram Visualizer is built with Python and leverages the power of the PlantUML library for generating the diagrams.

## Getting Started

### Prerequisites
You'll need Python 3 and PlantUML installed on your system.

### Installation
1. Clone the repository using the following command:
```sh
git clone https://github.com/empress-eco/class_diagram_visualizer.git
```
2. Install the package via pip:
```sh
pip install Empressviz
```

## Usage

### Command Line
```sh
Empressviz [-h] [--output output-dir] [--format {txt,img,all}] Empress-app-directory
```

### Python Module
```python
from Empressviz import generate_uml
generate_uml('path/to/Empress/app/dir', '/path/to/output/dir', 'img')
```

## Contributing
We welcome contributions from the community! Here's how you can contribute:

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License and Acknowledgements

### License
This project is under the MIT License. Contributions are also licensed under the MIT License.

### Acknowledgements
Special thanks to the Empress Community and the PlantUML team for their essential tools and libraries that power this project. Their innovation and dedication have been instrumental in building the foundations and functionalities we rely on. We are profoundly grateful for their pioneering work and ongoing support.