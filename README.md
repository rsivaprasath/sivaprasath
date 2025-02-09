<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Food Festival Menu</title>
    <style>
        body {
            background-color: #1b1b1b;
            color: #f5f5f5;
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            animation: fadeIn 2s ease-in-out;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        h1 {
            color: #ff5722;
            margin: 20px 0;
            animation: glow 1.5s infinite alternate;
            text-shadow: 0 0 10px #ff5722, 0 0 20px #ff5722, 0 0 30px #ff5722;
        }

        @keyframes glow {
            from { text-shadow: 0 0 5px #ff5722; }
            to { text-shadow: 0 0 20px #ff5722, 0 0 30px #ff5722; }
        }

        .menu {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            padding: 20px;
            max-width: 1200px;
            width: 100%;
        }

        .card {
            background: linear-gradient(145deg, #292929, #1f1f1f);
            border-radius: 20px;
            padding: 20px;
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.7);
            transition: transform 0.5s ease, box-shadow 0.5s ease;
            animation: zoomIn 1s ease forwards;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .card:hover {
            transform: scale(1.1) rotate(2deg);
            box-shadow: 0 15px 30px rgba(255, 87, 34, 0.6);
        }

        @keyframes zoomIn {
            from { opacity: 0; transform: scale(0.8); }
            to { opacity: 1; transform: scale(1); }
        }

        .card h2 {
            color: #ffab40;
        }

        .card p {
            color: #d7ccc8;
        }

        .card img {
            width: 100%;
            height: 150px;
            object-fit: cover;
            border-radius: 15px;
            margin-bottom: 15px;
            transition: transform 0.3s ease;
        }

        .card img:hover {
            transform: scale(1.05);
        }
    </style>
</head>
<body>
    <h1>🍽️ Fandango 🍽️</h1>
    <h1>The Food and Fun Fest 2025</h1>
    <div class="menu">
        <div class="card">
            <img src="https://i.postimg.cc/NMCdK7KC/smokybbq.jpg" alt="Dish 1">
            <h2>Smoky BBQ grilled skewers
            </h2>
            <p>Grilled chicken skewers and vegetables glazed with smoky </p>
        </div>
        <div class="card">
            <img src="https://i.postimg.cc/x8t5wG23/potato.jpg" alt="Dish 2">
            <h2>Potato canapes
            </h2>
            <p>Potato tart filled with buttery veggies.</p>
        </div>
        <div class="card">
            <img src="https://i.postimg.cc/6QXZh2sW/peri.jpg" alt="Dish 3">
            <h2>Peri peri spiced chicken wings
            </h2>
            <p>Juicy chicken wings coated with peri peri spice 
                .</p>
        </div>
        <div class="card">
            <img src="https://i.postimg.cc/DfMbMYVY/mushroom.jpg" alt="Dish 4">
            <h2> Creamy Mushroom stroganoff </h2>
            <p>Sliced mushroom in a savory cream sauce served over herbed rice
                .</p>
        </div>
        <div class="card">
            <img src="https://i.postimg.cc/VkBvmKTw/meatball.jpg" alt="Dish 5">
            <h2>Classic meatball marinara pasta
 
            </h2>
            <p>Tender meatballs in a rich tomato sauce served over al dante spaghetti
                .</p>
        </div>
        <div class="card">
            <img src="https://i.postimg.cc/sDKgvTy4/mac-cheese.jpg" alt="Dish 6">
            <h2>Mac and  cheese casserole 
            </h2>
            <p>Tender macaroni in a rich velvety cheese sauce 
            </p>
        </div>
        <div class="card">
            <img src="https://i.postimg.cc/L8wR17WL/glazedchicken.jpg" alt="Dish 7">
            <h2> Lemon pepper glazed chicken wings
            </h2>
            <p>Juicy chicken wings coated in flavourful lemon pepper sauce
                .</p>
        </div>
        <div class="card">
            <img src="https://i.postimg.cc/6QrSpmx9/fowl.jpg" alt="Dish 8">
            <h2>Crispy fowl petite bun
            </h2>
            <p>A Crispy fried chicken tucked in a soft sesame bun with a side of coleslaw
                .</p>
        </div>
        <div class="card">
            <img src="https://i.postimg.cc/B6dM550h/farewell.jpg" alt="Dish 9">
            <h2>Farfelle al rose'
            </h2>
            <p>Farfelle pasta tossed in a luscious tomato and cream sauce.</p>
        </div>
        <div class="card">
            <img src="https://i.postimg.cc/GhpHPWX5/crispy.jpg" alt="Dish 10">
            <h2>Crispy spud delight
            </h2>
            <p>Crispy potato patty tucked in a soft sesame bun with a side of coleslaw
            </p>
        </div>
        <div class="card">
            <img src="https://i.postimg.cc/qq5FD1Fy/chickenvg.jpg" alt="Dish 11">
            <h2>Chicken Galentine
            </h2>
            <p>Poached chicken roll with honey cocoa sauce
                .</p>
        </div>
        <div class="card">
            <img src="https://i.postimg.cc/s2sTmF2b/beef.jpg" alt="Dish 12">
            <h2>Beef stroganoff ala creme</h2>
            <p>Beef chunks in a savoury cream sauce served over herbed rice
            </p>
        </div>
    </div>
</body>
</html>
