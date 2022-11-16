# amazonehomepage
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        section{
            display: grid;
            grid-template-columns: 3fr 3fr 3fr 3fr;
            margin-top: -300px;
        }
        section > div {
            height: 400px;
            background-color: white;
            margin: 20px;
            margin: 10px;
            box-shadow: 2px 2px 2px grey;
            padding: 10px;
            
        }
        .card {
            width: 380px;
            padding: 5px;
            margin: 5px;
            margin-top: -30px;

        }
        .card-header {
            font-family: Arial, Helvetica, sans-serif;
            font-size: 20px;
        
        }
        .row {
            display: grid;
            grid-template-columns: 6fr 6fr;
            margin-top: -15px;
        }
        .card-image {
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <img src="./images/amazonebanner.jpg" width="100%">
    </header>
    <section>
        <div>
            <div class="card">
                <div class="card-header">
                   <h2>Top picks for your home</h2>
                </div>
                <div class="row">
                    <div>
                       <img src="./images/refrigerator.jpg" class="card-img">
                       <p>Clothing</p>
                    </div>
                    <div>
                        <img src="./images/microwaves.jpg" class="card-img"> 
                        <p>Footwear</p>
                    </div>
                </div>
                <div class="row">
                    <div>
                       <img src="./images/washing machine.jpg" class="card-img">
                       <p>Watches</p>
                    </div>
                    <div>
                        <img src="./images/ac.jpg" class="card-img">
                        <p>Bags & Luggage</p>
                    </div>
                </div>
                <div class="card-footer">
                    <p>See all offers</p>
                </div>
            </div>
        </div>
        <div>
            <div class="card">
                <div class="card-header">
                   <h2>Up to 60% off | Styles for Men</h2>
                </div>
                <div class="row">
                    <div>
                       <img src="./images/officechair.jpg" class="card-img">
                       <p>Clothing</p>
                    </div>
                    <div>
                        <img src="./images/sofa.jpg" class="card-img">
                        <p>Footwear</p>
                    </div>
                </div>
                <div class="row">
                    <div>
                       <img src="./images/sofa.jpg" class="card-img">
                       <p>Watches</p>
                    </div>
                    <div>
                        <img src="./images/beanbag.jpg" class="card-img">
                        <p>Bags & Luggage</p>
                    </div>
                </div>
                <div class="card-footer">
                    <p>See all offers</p>
                </div>
            </div>
        </div>
        <div>
            <div class="card">
                <div class="card-header">
                   <h2>Top picks for your home</h2>
                </div>
                <div class="row">
                    <div>
                       <img src="./images/ac.jpg" class="card-img">
                       <p>Clothing</p>
                    </div>
                    <div>
                        <img src="./images/microwaves.jpg" class="card-img">
                        <p>Footwear</p>
                    </div>
                </div>
                <div class="row">
                    <div>
                       <img src="./images/washing machine.jpg" class="card-img">
                       <p>Watches</p>
                    </div>
                    <div>
                        <img src="./images/refrigerator.jpg" class="card-img">
                        <p>Bags & Luggage</p>
                    </div>
                </div>
                <div class="card-footer">
                    <p>See all offers</p>
                </div>
            </div>
        </div>
        <div>
            <div class="card">
                <div class="sign-card-header">
                    <h2>Sign in for your best experience</h2>
                    <button>Sign in securely</button>
                </div>
            </div>
        </div>
    </section>
</body>
</html>
