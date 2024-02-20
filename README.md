# Academic Insight: Student Performance Forecast

Academic Insight is an end-to-end machine learning application developed using Python and Flask. It predicts student performance based on various factors and incorporates essential features for efficient development and deployment.

## Features

- **Logging and Exception Handling**: Ensures robustness by logging important events and handling exceptions gracefully.
- **Exploratory Data Analysis (EDA)**: Analyzes and visualizes the dataset to gain insights into the data's characteristics and distributions.
- **Model Training**: Trains machine learning models using the provided dataset.
- **Data Ingestion**: Fetches data from external sources for analysis and model training.
- **Data Transformation**: Preprocesses and transforms data using pipelines to prepare it for model training.
- **Model Evaluation**: Assesses the performance of trained models using appropriate evaluation metrics.

Moreover, the application includes a Prediction Pipeline seamlessly integrated with a Flask Web Application for making predictions based on new data inputs.

## Deployment

The application utilizes Continuous Integration/Continuous Deployment (CI/CD) Pipelines on the AWS Cloud platform for efficient deployment. Automation is facilitated by GitHub Actions, ensuring seamless integration with the development workflow.

To ensure portability and scalability, Docker containers are employed for packaging the application along with its dependencies. Additionally, AWS services such as Elastic Container Registry (ECR) and EC2 instances are utilized for deployment, providing a reliable and scalable infrastructure for hosting the application.

## Getting Started

To get started with the Student Performance Predictor application, follow these steps:

1. Clone the repository to your local machine.
2. Install the necessary dependencies using `pip install -r requirements.txt`.
3. Run the application locally for testing and development purposes.

## Contribution

Contributions to the Student Performance Predictor application are welcome! If you'd like to contribute, please follow these guidelines:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and ensure all tests pass.
4. Submit a pull request with a clear description of your changes.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify the code according to your needs.

