# AI Web Scraper

An advanced AI-powered web scraping solution that enables efficient data extraction from websites through intelligent content analysis and automated code generation.

## Features

- **AI-Driven Extraction**: Leverages artificial intelligence to identify and extract relevant data points from complex webpages
- **Multi-Language Support**: Generate scraping code in Python, JavaScript, or C#
- **Multiple Library Options**: Compatible with popular automation libraries including Selenium, Playwright, and Puppeteer
- **Dynamic Content Handling**: Capable of scraping both static and dynamically loaded content
- **Intelligent DOM Processing**: Automatically identifies the most relevant sections of a webpage based on your query
- **Performance Optimization**: Configurable performance settings to balance between speed and thoroughness
- **User-Friendly Interface**: Intuitive setup with straightforward configuration options

## Technical Implementation

The system uses advanced natural language processing to analyze webpage structure and generate appropriate scraping code. It processes HTML content by:

1. Pruning unnecessary DOM elements
2. Extracting relevant sections based on similarity to the user's query
3. Chunking content for efficient processing
4. Generating optimized scraping code tailored to the specified language and library

## Installation

### Backend Setup

1. Clone this repository
   ```
   git clone https://github.com/yourusername/AI-Web-Scraper.git
   cd AI-Web-Scraper/backend
   ```

2. Set up a Python virtual environment (using UV for faster dependency resolution)
   ```
   # Install UV if you don't have it
   pip install uv

   # Create and activate virtual environment
   uv venv
   # On Windows
   .venv\Scripts\activate
   # On macOS/Linux
   source .venv/bin/activate
   ```

3. Install dependencies
   ```
   uv pip install -r requirements.txt
   ```

4. Configure environment variables
   ```
   # Create a .env file with necessary API keys and configuration
   cp .env.example .env
   # Edit the .env file with your preferred text editor
   ```

5. Start the backend server
   ```
   python main.py
   ```

### Frontend Setup

1. Navigate to the frontend directory
   ```
   cd ../frontend
   ```

2. Install dependencies
   ```
   npm install
   ```

3. Start the development server
   ```
   npm run dev
   ```

4. The application will be available at `http://localhost:5173` (or the port specified in your terminal)

## Usage

1. Access the web interface through your browser
2. Enter the target website URL
3. Select your preferred programming language (Python, JavaScript, or C#)
4. Choose the automation library (Selenium, Playwright, or Puppeteer)
5. Specify your scraping requirements
6. Generate and download your custom scraping code

## License

[Your license information here]


