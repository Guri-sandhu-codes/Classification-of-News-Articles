# News Article Classification App

This application classifies news articles into one of six categories: Business, Education, Entertainment, Politics, Sports, and Technology. The app is designed to help users quickly determine the main focus of a given news article by automatically categorizing it based on its content.

## Features

- **Multi-category Classification**: Classifies articles into six categories.
- **User-Friendly Interface**: Easy-to-use interface for submitting articles and receiving results.
- **Real-time Classification**: Provides instant classification results after the article is submitted.

## Installation

### Prerequisites

- Python 3.8+
- pip (Python package manager)
- [Optional] A virtual environment tool like `venv` or `virtualenv`

### Clone the Repository

```bash
git clone https://github.com/Guri-sandhu-codes/Classification-of-News-Articles.git
cd Classification-of-News-Articles
```

### Install Dependencies

It's recommended to use a virtual environment to manage dependencies. To create and activate a virtual environment:

```bash
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
```

Then, install the required Python packages:

```bash
pip install -r requirements.txt
```

## Usage

1. **Run the App**: To start the application, run the following command:

```bash
python app.py
```

2. **Input an Article**: Open your browser and navigate to `http://127.0.0.1:5000` (or the appropriate local server URL). You can paste or type your news article into the provided input field.

3. **Get Results**: After submitting the article, the app will display the predicted category (e.g., Business, Education, etc.).

## Model Details

The classification model used in this application was trained using a large dataset of news articles. It leverages natural language processing (NLP) techniques and machine learning algorithms to accurately categorize the content.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch-name`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch-name`).
5. Open a Pull Request.

## Contact

For any questions or issues, please open an issue on GitHub or reach out to `gurisandhu.codes@gmail.com`.

