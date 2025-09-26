Phase 5: Apex Programming (Developer)

🎯 Objective

Develop Apex classes for API integration and business logic.

📝 Steps

1. WeatherController.cls:



public with sharing class WeatherController {
    @AuraEnabled(cacheable=true)
    public static Map<String, Object> getWeather(String city) {
        // Call OpenWeatherMap API and return JSON data
    }
}

2. Create Test Class for coverage.


3. Optional: Queueable/Future classes for callouts.