# Streamlit App for Data Analysis

This project involves creating an interactive data analysis application using Streamlit. The application allows users to perform data analysis and visualization using pandas and pandas-profiling. The app is deployed using LocalTunnel to make it accessible over the web.

## Table of Contents
- [Setup Instructions](#setup-instructions)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Project Files](#project-files)
- [Author](#author)
- [License](#license)

## Setup Instructions

1. **Install Streamlit and other dependencies:**
   ```bash
   pip install streamlit pandas pandas-profiling streamlit-pandas-profiling
   ```

2. **Install LocalTunnel:**
   LocalTunnel is used to create a public URL for the Streamlit app.
   ```bash
   npm install -g localtunnel
   ```

3. **Download and Run the App:**
   Download the script for the Streamlit app and run it.
   ```bash
   wget -q -O - ipv4.icanhazip.com
   streamlit run /content/demo.py & npx localtunnel --port 8501
   streamlit run /content/app.py & npx localtunnel --port 8501
   ```

## Dependencies

- streamlit
- pandas
- pandas-profiling
- streamlit-pandas-profiling
- localtunnel

## Usage

1. **Install Required Packages:**
   Ensure you have all the necessary packages installed. You can install them using pip:
   ```bash
   pip install streamlit pandas pandas-profiling streamlit-pandas-profiling
   ```

2. **Run the Streamlit App:**
   You can run the Streamlit app using the following command:
   ```bash
   streamlit run /content/app.py
   ```

3. **Create a Public URL using LocalTunnel:**
   Use LocalTunnel to create a public URL for the Streamlit app:
   ```bash
   npx localtunnel --port 8501
   ```

4. **Access the App:**
   Once LocalTunnel is set up, it will provide a public URL. Open this URL in your web browser to access the Streamlit app.

## Project Files

- `demo.py`: Example Streamlit script for demonstration.
- `app.py`: Main Streamlit application script.

## Author

[Your Name]

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
