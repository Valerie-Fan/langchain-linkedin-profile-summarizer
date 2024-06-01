# Ice Breaker Application

## Overview

The application is a Flask-based web application designed to help users generate conversation starters based on a person's LinkedIn profile. By providing a name, the application fetches LinkedIn data and processes it to produce summaries, topics of interest, and ice breakers.

## Result
<img width="1021" alt="截圖 2024-06-02 上午2 07 03" src="https://github.com/Valerie-Fan/langchain-linkedin-profile-summarizer/assets/164007751/15023c80-f32a-4515-b27b-c18b1a05c322">
<img width="1145" alt="未命名" src="https://github.com/Valerie-Fan/langchain-linkedin-profile-summarizer/assets/164007751/161a6527-7de9-4afe-8c33-57744ffb298c">

## Installation

### Prerequisites

- Python 3.11

### Steps

1. **Clone the repository**:
    ```bash
    git clone <repository-url>
    cd <repository-directory>
    ```

2. **Install dependencies**:
    Ensure you have `pipenv` installed. Then run:
    ```bash
    pipenv install
    ```

3. **Set up environment variables**:
    Create a `.env` file in the root directory and add necessary environment variables.
    ```bash
    OPENAI_API_KEY=
    TAVILY_API_KEY=
    PROXYCURL_API_KEY=
    ```

## Usage

1. **Run the Flask application**:
    ```bash
    pipenv run flask run
    ```

2. **Access the application**:
    Open your browser and go to `http://127.0.0.1:5000`.

3. **Enter a name**:
    Input the name in the provided field and submit to receive conversation starters.

## License

This project is licensed under the Apache License 2.0. See the [LICENSE](LICENSE) file for more details.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## Acknowledgments

Special thanks to instructor Eden Marco who provided a comprehensive tutorial of LangChain. This project is based on his lecture on Udemy: https://www.udemy.com/course/langchain/learn/lecture/37496242#overview
