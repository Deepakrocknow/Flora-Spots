https://flora-spots.vercel.app/

🌱 Bio-Tiger
Overview
Bio-Tiger is a web-based platform designed to analyze plant biodiversity in the Cape Floristic Region of South Africa, leveraging hyperspectral data from NASA's EMIT mission. The platform provides a map-based interface and detailed analysis tools to help discover biodiversity hotspots using spectral diversity indicators like NDVI, NDWI, and NDMI.

Key Features
Interactive Map: Visualize biodiversity hotspots on a map using Leaflet.js.
Hyperspectral Data Analysis: Analyze vegetation, water, and moisture indices (NDVI, NDWI, NDMI) for pre-processing plant biodiversity data.
Dynamic Web Interface: Built with HTML, Tailwind CSS, Bootstrap, and jQuery for an intuitive, responsive experience.
🛠️ Tech Stack
Frontend: HTML, Tailwind CSS, Bootstrap, JavaScript (jQuery)
Mapping: Leaflet.js for map visualizations
Data Sources: Hyperspectral data from NASA's EMIT mission
Version Control: Git and GitHub for collaboration and tracking
🗺️ Project Structure
python
Copy code
Bio-Tiger/
├── index.html              # Main page with the interactive map
├── pages/
│   ├── introduction.html   # Introduction page with project details
│   ├── analysis.html       # Analysis page showing spectral indices data
├── image/
│   ├── plants.png          # Icon image
│   ├── NDVI.jpg            # Image for NDVI description
│   ├── NDWI.jpg            # Image for NDWI description
│   ├── NDMI.jpg            # Image for NDMI description
├── modules/
│   ├── bootstrap.min.css    # Bootstrap styles
│   ├── bootstrap.min.js     # Bootstrap JavaScript
│   ├── jquery.min.js        # jQuery
│   ├── tailwind.css         # Tailwind CSS
├── index.css                # Custom styles
├── map.js                   # Leaflet.js map functionality
├── README.md                # Project documentation (this file)
🌍 How to Run Locally
Prerequisites
Make sure you have the following installed:

A web browser (Google Chrome, Firefox, etc.)
A local server like Live Server for VS Code (or any similar tool) to view the project.
Steps
Clone this repository:
bash
Copy code
git clone https://github.com/YourUsername/Bio-Tiger.git
Navigate into the project directory:
bash
Copy code
cd Bio-Tiger
Open the index.html file in a browser:
If you're using VS Code, right-click the file and choose "Open with Live Server".
Otherwise, open it manually in your browser after running a local server.
📊 Analysis Details
Normalized Difference Vegetation Index (NDVI): Formula: ((842nm - 665nm) / (842nm + 665nm)). Used to detect vegetation density.

Normalized Difference Water Index (NDWI): Formula: ((560nm - 842nm) / (560nm + 842nm)). Used to detect water bodies.

Normalized Difference Moisture Index (NDMI): Formula: ((1640nm - 842nm) / (1640nm + 842nm)). Used to detect soil moisture.

🎨 Screenshots
Main Map Interface

NDVI Analysis Example

👩‍💻 Contributing
Contributions are welcome! Please follow these steps:

Fork the repository.
Create a new branch for your feature or bugfix:
bash
Copy code
git checkout -b feature/my-feature
Commit your changes:
bash
Copy code
git commit -m "Add my feature"
Push to the branch:
bash
Copy code
git push origin feature/my-feature
Open a pull request on GitHub.
📝 License
This project is licensed under the MIT License - see the LICENSE file for details.

