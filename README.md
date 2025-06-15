# Customer Emotion Prediction

## Installation

1. Clone the repository:
```
git clone https://github.com/your-username/customer-emotion-prediction.git
```

2. Create a virtual environment and activate it:
```
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

3. Install the required dependencies:
```
pip install -r requirements.txt
```

## Usage

1. Run the Streamlit application:
```
streamlit run app.py
```

2. The application will open in your default web browser.

3. Select the model you want to use (e.g., "Nhà hàng" or "Khách sạn") from the sidebar.

4. Enter the text you want to analyze in the text area.

5. Click the "Phân tích" button to get the sentiment analysis results.

## API

The application uses the following API endpoints:

- `/`: The main page where users can input text and get sentiment analysis results.
- `/chart`: Displays charts and visualizations based on the analysis history.
- `/history`: Shows the history of previous analysis results.
- `/stats`: Provides overall statistics and model information.
- `/batch`: Allows users to analyze sentiment from a file.

## Contributing

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your branch to your forked repository.
5. Submit a pull request to the original repository.

## License

This project is licensed under the [MIT License](LICENSE).

## Testing

To run the tests, use the following command:

```
python -m unittest discover tests
```

This will run all the tests in the `tests` directory.
