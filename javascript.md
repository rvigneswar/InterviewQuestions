1. Explain the ```.reduce()``` method with an example
2. Implement a simple shopping cart system with features to add items, 
  remove items and calculate the total price. Use objects to represent items, 
  including properties for the item name, price and quantity. 
  Implement features to add items to the cart, remove items and calculate the total cost.
3. Debug the below code snippet
  ```javascript
              function fetchData(callback) {
                  fetch('https://api.example.com/data')
        	        .then(response => response.json())
        	        .then(data => callback(null, data))
        	        .catch(error => callback(error));
              }
              fetchData(function (error, data) {
              if (error) {
        	        console.log('Error:', error);
              } else {
        	        console.log('Data:', data);
              }
              });
  ```

4. ```javascript
      
              const passengers = [
                {
                  id: 1,
                  passengerName: "Freddie Mercury",
                  isVegetarianOrVegan: false,
                  connectedFlights: 2,
                },
                {
                  id: 2,
                  passengerName: "Amy Winehouse",
                  isVegetarianOrVegan: true,
                  connectedFlights: 4,
                },
                  {
                  id: 3,
                  passengerName: "Kurt Cobain",
                  isVegetarianOrVegan: true,
                  connectedFlights: 3,
                },
                   {
                  id: 3,
                  passengerName: "Michael Jackson",
                  isVegetarianOrVegan: true,
                  connectedFlights: 1,
                },
              ];
```

By using filter and map get the passenger names who are VegetarianorVegan
