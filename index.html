<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hypothetical University Food Menu</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        header {
            background-color: #4CAF50;
            width: 100%;
            text-align: center;
            padding: 1em 0;
            color: white;
            font-size: 2em;
        }

        main {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 20px;
        }

        .food-item {
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin: 15px;
            padding: 20px;
            text-align: center;
            width: 250px;
            transition: transform 0.2s;
        }

        .food-item img {
            width: 100%;
            height: 150px;
            border-radius: 10px;
            object-fit: cover;
        }

        .food-item h2 {
            font-size: 1.5em;
            margin: 10px 0;
        }

        .rating {
            color: #FFD700;
            font-size: 1.2em;
        }

        .stars {
            display: flex;
            justify-content: center;
            cursor: pointer;
        }

        .star {
            font-size: 1.5em;
            color: #ccc;
            transition: color 0.2s;
        }

        .star.active, .star:hover, .star:hover ~ .star {
            color: #FFD700;
        }

        .food-item:hover {
            transform: scale(1.05);
        }
    </style>
</head>
<body>
    <header>
        Hypothetical University Cafeteria Menu
    </header>
    <main id="food-list"></main>

    <script>
        const foodItems = [
            { name: "Zinger Shawarma", image: "sddefault.jpg" },
            { name: "Classic Margherita Pizza", image: "https://via.placeholder.com/250?text=Pizza" },
            { name: "Grilled Cheese Sandwich", image: "https://via.placeholder.com/250?text=Sandwich" },
            { name: "Pasta Alfredo", image: "https://via.placeholder.com/250?text=Pasta" },
            { name: "Chicken Biryani", image: "https://via.placeholder.com/250?text=Biryani" },
            { name: "Caesar Salad", image: "https://via.placeholder.com/250?text=Salad" },
            { name: "BBQ Chicken Wings", image: "https://via.placeholder.com/250?text=Wings" },
            { name: "Chocolate Brownie", image: "https://via.placeholder.com/250?text=Brownie" },
            { name: "Sushi Platter", image: "https://via.placeholder.com/250?text=Sushi" },
            { name: "Vegan Tacos", image: "https://via.placeholder.com/250?text=Tacos" },
            { name: "Fruit Smoothie", image: "https://via.placeholder.com/250?text=Smoothie" },
            { name: "Pancake Stack", image: "https://via.placeholder.com/250?text=Pancakes" },
            { name: "French Fries", image: "https://via.placeholder.com/250?text=Fries" },
            { name: "Ice Cream Sundae", image: "https://via.placeholder.com/250?text=Sundae" },
            { name: "Mushroom Risotto", image: "https://via.placeholder.com/250?text=Risotto" }
        ];

        // Load ratings from localStorage or set all to 0
        const ratings = JSON.parse(localStorage.getItem('foodRatings')) || Array(foodItems.length).fill(0);

        // Generate and display food items in HTML
        const foodList = document.getElementById("food-list");

        function renderFoodItems() {
            foodList.innerHTML = '';
            foodItems.forEach((item, index) => {
                const foodDiv = document.createElement("div");
                foodDiv.classList.add("food-item");

                foodDiv.innerHTML = `
                    <img src="${item.image}" alt="${item.name}">
                    <h2>${item.name}</h2>
                    <div class="stars" data-index="${index}">
                        ${[1, 2, 3, 4, 5].map(i => `
                            <span class="star ${i <= ratings[index] ? 'active' : ''}" data-value="${i}">★</span>
                        `).join('')}
                    </div>
                    <div class="rating" id="rating-${index}">Rating: ${ratings[index].toFixed(1)}</div>
                `;
                foodList.appendChild(foodDiv);
            });
        }

        foodList.addEventListener('click', (event) => {
            if (event.target.classList.contains('star')) {
                const star = event.target;
                const index = star.parentElement.getAttribute('data-index');
                const value = star.getAttribute('data-value');
                ratings[index] = parseInt(value); // Set new rating
                localStorage.setItem('foodRatings', JSON.stringify(ratings)); // Save to localStorage
                renderFoodItems(); // Re-render items to update stars
            }
        });

        renderFoodItems();
    </script>
</body>
</html>
            
