# CountryFlagAndName
A small country research application with the help of pure javascript codes and xmlhttp

You can access and experience the website at => https://countryflagandname.onrender.com

## Api Consuming 
This is a JavaScript code that fetches country data from the "https://restcountries.com" API and displays it on a webpage.

The code listens for a click event on a search button and then calls the getCountry() function, passing the value of the search input field as a parameter.

The getCountry() function makes an XMLHttpRequest to the API endpoint for the specified country and, on receiving the response, parses the JSON data and calls two functions to render the country details and its neighboring countries.

The renderCountry() function takes the country data as a parameter and generates an HTML code snippet to display the country details such as name, population, capital, language, and currency. The function then updates the HTML of a specified element on the webpage with the generated HTML code.

The renderNeighbors() function takes an array of neighboring countries data as a parameter and generates an HTML code snippet to display each neighbor's flag and name in a bootstrap card. The function then updates the HTML of a specified element on the webpage with the generated HTML code.
![proje1](https://user-images.githubusercontent.com/46266620/222308422-3ce7c2de-5a7b-434e-aab9-b8c15ce45a12.png)
