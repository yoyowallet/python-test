# Yoyo Python Engineering Test

As part of the Yoyo interview process we ask you to complete a small coding challenge to help us better understand your skills. We estimate this should take no longer than half a day but there is no limit.

## User Story

As an API user I want to get the minimum, maximum, average and median temperature for a given city and period of time.

## Requirements

- Create a Django application with RESTful API
- Django application must run locally
- API must be in the format /api/locations/{city}/?days={number_of_days}
- API must fetch weather data from some public API of your choice
- API must compute min, max, average, and median temperature
- Response format must be in the following structure:

```
{
    "maximum": value,
    "minimum": value,
    "average": value,
    "median": value,
}
```

Please publish your project via Github and send us a link to your repository.

## Marking Criteria

| Category      | Description                                                 |
| ------------- | ----------------------------------------------------------- |
| Functionality | All specified requirements are adequately met               |
| Architecture  | How well the application is designed and code is structured |
| Readability   | Simplicity, comments, style, documentation etc.             |
| Tests         | Various test cases and coverage                             |

## Tips

- django-rest-framework is recommended although not required
- https://www.weatherapi.com/ provides a free tier for querying weather forecasts
- Consider and observe best practices regarding implementation of public facing APIs (i.e. input validation, error handling, etc.)
- Keep your Github repo clean and easy to navigate code changes. Ensure to provide a well structured README
