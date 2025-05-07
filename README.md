# 3D-Model
3D Model Generator
A Python application that converts photos or text prompts into simple 3D models with Gemini AI-powered visualization and download capabilities.

3D Model Generator App

🚀 Features
Dual Input Options: Generate 3D models from either:
Text descriptions (e.g., "A toy car", "An office chair")
Image uploads (photos of single objects)
Gemini AI Integration:
Enhanced 3D model descriptions and analysis
Intelligent object recognition from images
Smart texture and color suggestions
Detailed visualization insights
Interactive 3D Visualization:
Rotate, zoom, and explore your generated 3D models directly in the browser
Clear axis indicators for better spatial understanding
Export Capabilities:
Download models as .OBJ files
Ready for import into 3D software or 3D printing workflows
🔧 Technologies Used
Streamlit: For the interactive web interface
Google Gemini AI: For enhanced descriptions and analysis
Trimesh: For 3D geometry processing
OpenCV: For image preprocessing
Plotly: For interactive 3D visualization
📋 Requirements
Python 3.11+
Libraries listed in dependencies.txt
🛠️ Installation
Clone this repository:

git clone https://github.com/yourusername/3d-model-generator.git
cd 3d-model-generator
Install dependencies:

pip install -r dependencies.txt
Set up a Google API Key for Gemini:

Visit Google AI Studio
Create an API key
Add to environment variables:
export GOOGLE_API_KEY="your-api-key-here"
Run the application:

streamlit run app.py
💡 How It Works
Text-to-3D:

The application parses keywords from your text description
Gemini AI enhances the description with detailed features
A 3D model is generated based on the analysis
Texture and color suggestions are provided
Image-to-3D:

Your uploaded image is preprocessed to isolate the object
Background removal is applied if selected
Gemini AI analyzes the image contents
A 3D representation is created based on the silhouette
Advanced features are determined by AI analysis
✨ Examples
Text Input: "A sports car with sleek design"
Generates a car-shaped 3D model with Gemini-enhanced details
Image Input: Photo of a chair
Creates a 3D model based on the chair silhouette
Provides AI analysis of chair features
🔮 Future Improvements
More sophisticated 3D model generation algorithms
Texture mapping capabilities
Additional export formats (STL, GLTF)
More detailed geometry based on Gemini Vision analysis
📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

🙏 Acknowledgements
Google for their Gemini API
The Streamlit team for their excellent framework
The open-source community for libraries used in this project
