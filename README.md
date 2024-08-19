# podcaste_page

<!DOCTYPE html>
<html>

<head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
</head>

<body>
    <div id="sectionHome">
        <div class="podcast-1-top-container">
            <h1 class="podcast-1-top-heading">Podcasts</h1>

        </div>

        <div class="d-flex flex-row">
            <div class="podcast-1-card-container" onclick="display('sectionPuri')">
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/puri-jagannadh-img.png" class="podcast-1-card-image" />
                <h1 class="podcast-1-card-heading">Puri jagannadh</h1>
                <p class="podcast-1-card-para">24 Episodes</p>
            </div>

            <div class="podcast-1-card-container" onclick="display('sectionTedx')">
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tedx-img.png" class="podcast-1-card-image" />
                <h1 class="podcast-1-card-heading">Tedx talks</h1>
                <p class="podcast-1-card-para">12 Episodes</p>
            </div>
        </div>


        <div class="d-flex flex-row">
            <div class="podcast-1-card-container" onclick="display('sectionSadhguru')">
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/sadhguru-img.png" class="podcast-1-card-image" />
                <h1 class="podcast-1-card-heading">Sadhuguru</h1>
                <p class="podcast-1-card-para">49 Episodes</p>
            </div>

            <div class="podcast-1-card-container" onclick="display('sectionOnpurpose')">
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/on-purpose-img.png" class="podcast-1-card-image" />
                <h1 class="podcast-1-card-heading">On purpose</h1>
                <p class="podcast-1-card-para">49 Episodes</p>
            </div>
        </div>
    </div>


    <div id="sectionPuri">
        <div class="puri-page-container-selected d-flex flex-row">
            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/puri-jagannadh-img.png" class="puri-page-container-image" />
            <div class="puri-page-container-words">
                <p class="puri-page-container-selected-side-head">podcaste</p>
                <h1 class="puri-page-container-selected-heading">Puri Jaganadh podcaste</h1>
                <p class="puri-page-container-selected-discription">The puri Jagannadh Podcaste</p>
            </div>
        </div>



        <div class="puri-page-container d-flex flex-row">
            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/puri-jagannadh-img.png" class="puri-page-container-image" />
            <div class="puri-page-container-words">
                <h1 class="puri-page-container-heading">Molecular Gastronomy</h1>
                <p class="puri-page-container-discription"> Anything happens there it will not cook,...</p>
                <p class="puri-page-container-side-head">15 min</p>
            </div>
        </div>

        <div class="puri-page-container d-flex flex-row">
            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/puri-jagannadh-img.png" class="puri-page-container-image" />
            <div class="puri-page-container-words">
                <h1 class="puri-page-container-heading">Mysterious book</h1>
                <p class="puri-page-container-discription"> The voynich manuscript is the 15th century book...</p>
                <p class="puri-page-container-side-head">12 min</p>
            </div>
        </div>



        <div class="puri-page-container d-flex flex-row">
            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/puri-jagannadh-img.png" class="puri-page-container-image" />
            <div class="puri-page-container-words">

                <h1 class="puri-page-container-heading">Predator Drone</h1>
                <p class="puri-page-container-discription"> The most powerful drone it is 10 feet height....</p>
                <p class="puri-page-container-side-head">10 min</p>
            </div>
        </div>



        <div class="puri-page-container d-flex flex-row">
            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/puri-jagannadh-img.png" class="puri-page-container-image" />
            <div class="puri-page-container-words">

                <h1 class="puri-page-container-heading"> Paella</h1>
                <p class="puri-page-container-discription"> The national dish of spain. It was first star</p>
                <p class="puri-page-container-side-head">6 min</p>
            </div>
        </div>
        <div class="d-flex flex-row justify-content-end">
            <button class="puri-back-button-adjust" onclick="display('sectionHome')">Back</button>
        </div>
    </div>



    <div id="sectionTedx">

        <div class="puri-page-container-selected d-flex flex-row">
            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tedx-img.png " class="puri-page-container-image" />
            <div class="puri-page-container-words">
                <p class="puri-page-container-selected-side-head">podcaste</p>
                <h1 class="puri-page-container-selected-heading">The Tedx podcast</h1>
                <p class="puri-page-container-selected-discription"> The tedx podcaste</p>
            </div>
        </div>

        <div class="puri-page-container d-flex flex-row">
            <img src=" https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tedx-img.png" class="puri-page-container-image" />
            <div class="puri-page-container-words">
                <h1 class="puri-page-container-heading">The science of friction</h1>
                <p class="puri-page-container-discription"> Tribology:Its's a funny sounding word you might...</p>
                <p class="puri-page-container-side-head">12 min</p>
            </div>
        </div>

        <div class="puri-page-container d-flex flex-row">
            <img src=" https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tedx-img.png" class="puri-page-container-image" />
            <div class="puri-page-container-words">
                <h1 class="puri-page-container-heading">Unleash you</h1>
                <p class="puri-page-container-discription">What can we learn from the world's most enduringly...</p>
                <p class="puri-page-container-side-head">8 min</p>
            </div>
        </div>

        <div class="puri-page-container d-flex flex-row">
            <img src=" https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tedx-img.png" class="puri-page-container-image" />
            <div class="puri-page-container-words">

                <h1 class="puri-page-container-heading">3 psychological tricks </h1>
                <p class="puri-page-container-discription"> We all want to save more money- but overall,... </p>
                <p class="puri-page-container-side-head">10 min</p>
            </div>
        </div>

        <div class="puri-page-container d-flex flex-row">
            <img src=" https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tedx-img.png" class="puri-page-container-image" />
            <div class="puri-page-container-words">

                <h1 class="puri-page-container-heading">The caste for stubborn </h1>
                <p class="puri-page-container-discription"> This decade is a moment of choice unlike any we...</p>
                <p class="puri-page-container-side-head">12 min</p>
            </div>
        </div>
        <div class="d-flex flex-row justify-content-end">
            <button class="puri-back-button-adjust" onclick="display('sectionHome')">Back</button>
        </div>
    </div>


    <div id="sectionSadhguru">

        <div class="puri-page-container-selected d-flex flex-row">
            <img src=" https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/sadhguru-img.png " class="puri-page-container-image" />
            <div class="puri-page-container-words">
                <p class="puri-page-container-selected-side-head">podcaste</p>
                <h1 class="puri-page-container-selected-heading">The Sadhguru podcaste</h1>
                <p class="puri-page-container-selected-discription"> The Sadhguru podcaste</p>
            </div>
        </div>

        <div class="puri-page-container d-flex flex-row">
            <img src="  https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/sadhguru-img.png" class="puri-page-container-image" />
            <div class="puri-page-container-words">
                <h1 class="puri-page-container-heading"> Head or heart</h1>
                <p class="puri-page-container-discription"> Sadhguru shares his wisdome on how to make... </p>
                <p class="puri-page-container-side-head">16 min</p>
            </div>
        </div>

        <div class="puri-page-container d-flex flex-row">
            <img src=" https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/sadhguru-img.png" class="puri-page-container-image" />
            <div class="puri-page-container-words">
                <h1 class="puri-page-container-heading">How to equip yourself</h1>
                <p class="puri-page-container-discription"> Society and human interactions are going...</p>
                <p class="puri-page-container-side-head">13 min</p>
            </div>
        </div>

        <div class="puri-page-container d-flex flex-row">
            <img src="  https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/sadhguru-img.png" class="puri-page-container-image" />
            <div class="puri-page-container-words">

                <h1 class="puri-page-container-heading"> How not to get irritated</h1>
                <p class="puri-page-container-discription"> How do you see an unpleasent spouse the... </p>
                <p class="puri-page-container-side-head">15 min</p>
            </div>
        </div>

        <div class="puri-page-container d-flex flex-row">
            <img src="  https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/sadhguru-img.png" class="puri-page-container-image" />
            <div class="puri-page-container-words">

                <h1 class="puri-page-container-heading">Isha Kriya </h1>
                <p class="puri-page-container-discription"> Rooted in the timeless wisdom if the yougic...</p>
                <p class="puri-page-container-side-head">16 min</p>
            </div>
        </div>
        <div class="d-flex flex-row justify-content-end">
            <button class="puri-back-button-adjust" onclick="display('sectionHome')">Back</button>
        </div>
    </div>


    <div id="sectionOnpurpose">

        <div class="puri-page-container-selected d-flex flex-row">
            <img src="  https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/on-purpose-img.png " class="puri-page-container-image" />
            <div class="puri-page-container-words">
                <p class="puri-page-container-selected-side-head">podcaste</p>
                <h1 class="puri-page-container-selected-heading">On purpose with Jay</h1>
                <p class="puri-page-container-selected-discription"> The jay shetty podcaste </p>
            </div>
        </div>

        <div class="puri-page-container d-flex flex-row">
            <img src=" https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/on-purpose-img.png" class="puri-page-container-image" />
            <div class="puri-page-container-words">
                <h1 class="puri-page-container-heading"> Patrick Bet David</h1>
                <p class="puri-page-container-discription">Are you an entrepreneur or have dreams of mental... </p>
                <p class="puri-page-container-side-head">10 min</p>
            </div>
        </div>

        <div class="puri-page-container d-flex flex-row">
            <img src="  https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/on-purpose-img.png" class="puri-page-container-image" />
            <div class="puri-page-container-words">
                <h1 class="puri-page-container-heading"> 5 Techiques to cope </h1>
                <p class="puri-page-container-discription"> Does anxiety looms around every corner of yours</p>
                <p class="puri-page-container-side-head">4 min</p>
            </div>
        </div>

        <div class="puri-page-container d-flex flex-row">
            <img src=" https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/on-purpose-img.png" class="puri-page-container-image" />
            <div class="puri-page-container-words">

                <h1 class="puri-page-container-heading"> Radhanath swami ON</h1>
                <p class="puri-page-container-discription">World-renowned spritual leaders and philanthropist... </p>
                <p class="puri-page-container-side-head">12 min</p>
            </div>
        </div>

        <div class="puri-page-container d-flex flex-row">
            <img src=" https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/on-purpose-img.png" class="puri-page-container-image" />
            <div class="puri-page-container-words">

                <h1 class="puri-page-container-heading">3 ways to let go </h1>
                <p class="puri-page-container-discription">Do the opinions of others veer you from the core...
                <p class="puri-page-container-side-head">13 min</p>
            </div>
        </div>
        <div class="d-flex flex-row justify-content-end">
            <button class="puri-back-button-adjust" onclick="display('sectionHome')">Back</button>
        </div>
    </div>
    <script type="text/javascript" src="https://new-assets.ccbp.in/frontend/content/static-ccbp-ui-kit/static-ccbp-ui-kit.js"></script>
</body>

</html>

#CSS

@import url('https://fonts.googleapis.com/css2?family=Bree+Serif&family=Caveat:wght@400;700&family=Lobster&family=Monoton&family=Open+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Playfair+Display+SC:ital,wght@0,400;0,700;1,700&family=Playfair+Display:ital,wght@0,400;0,700;1,700&family=Roboto:ital,wght@0,400;0,700;1,400;1,700&family=Source+Sans+Pro:ital,wght@0,400;0,700;1,700&family=Work+Sans:ital,wght@0,400;0,700;1,700&display=swap');

.podcast-1-top-container {

    background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/podcasts-bg.png");
    height: 40vh;
    background-size: cover;
    margin-bottom: 20px;
}

.podcast-1-top-heading {

    color: white;
    font-weight: 400;
    padding: 20px;

}

.podcast-1-card-container {

    margin-left: 60px;


}

.podcast-1-card-image {

    height: 120px;
    margin: 5px;

}

.podcast-1-card-heading {

    font-size: 18px;
    color: #151765;
    margin-left: 15px;
    font-family: "Roboto";
    font-weight: bold;


}

.podcast-1-card-para {

    color: #5a7184;
    margin-left: 30px;

}




.puri-page-container-selected {

    background-color: #151765;
    padding: 25px;
    margin-bottom: 20px;
}

.puri-page-container-selected-side-head {

    color: white;
}

.puri-page-container-selected-heading {

    font-size: 30px;
    color: white;

}

.puri-page-container-selected-discription {

    color: white;

}


.puri-page-container {

    background-color: white;
    padding: 5px;
    margin-bottom: 20px;
}


.puri-page-container-words {

    padding: 10px;

}

.puri-page-container-image {

    height: 140px;
    margin: 10px;
}

.puri-page-container-side-head {

    color: white;
    color: #151765;

}

.puri-page-container-heading {

    font-size: 22px;
    color: #151765;

}

.puri-page-container-discription {

    color: #5a7184;
    font-size: 18px;

}

.puri-back-button-adjust {

    color: white;
    width: 100px;
    border-radius: 15px;
    background-color: #151765;
}
