In this project, I created a weather dashboard that collects data from a weather API and stores it in an S3 bucket. Before starting the development, I needed to set up two things:

1. I signed up for an account on the OpenWeather API website.
2. I created an IAM user with administrative access in AWS and generated an access key and secret access key for that user.

Once these steps were completed, I loaded the environment variables containing the OpenWeather API key and the AWS Bucket name. Then, I created a `WeatherDashboard` class that sends API requests to OpenWeather, fetches the weather data, and transforms it into a structured format. This structured data is then stored as a JSON file in the S3 bucket.

