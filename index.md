<!DOCTYPE html>
<html lang="en">
  <head>
    <meta
      name="viewport"
      content="width-device-width, initial-scale=1.0,maximum-scale=1"
    />
    <link rel="stylesheet" type="text/css" href="VENDORS/CSS/normalize.css" />
    <link
      rel="stylesheet"
      type="text/css"
      href="VENDORS/CSS/4%20COLUMN%20GRID.css"
    />
    <link rel="stylesheet" type="text/css" href="RESOURCES/CSS/Style.css" />
    <link
      href="https://fonts.googleapis.com/css2?fam<style> @import url('https://fonts.googleapis.com/css2?family=Lato:ital,wght@0,100;0,300;0,400;1,300&display=swap');
            </style>ily=Lato:ital,wght@0,100;0,300;0,400;1,300&display=swap"
      rel="stylesheet"
    />
    <link rel="stylesheet" type="text/css" href="RESOURCES/CSS/queries.css" />

    <body>
      <header>
        <nav>
          <div class="row">
            <img
              src="VENDORS/IMG/logo-white.png"
              alt="Omnifood Logo"
              class="logo"
            />

            <ul class="main-nav">
              <li><a href="#section-features">Food Delivery</a></li>
              <li><a href="#how-it-works">How it works</a></li>
              <li><a href="#cities">Our cities</a></li>
              <li><a href="#sign-up">Sign up </a></li>
            </ul>
          </div>
        </nav>
        <div class="hero-text-box">
          <h1>
            Goodbye junk food. <br />
            Hello super healthy meals.
          </h1>

          <a class="btn btn-full" href="#"> I'm hungry</a>

          <a class="btn btn-ghost" href="#"> Show me more</a>
        </div>
      </header>
      <div id="section-features">
        <section class="section-features">
          <div class="row">
            <h2>Get food fast &mdash; not fast food.</h2>
            <p class="long-copy">
              Hello, we're Omnifood, your new premium food delivery service. We
              know you're always busy. No time for cooking. So let us take care
              of that, we're really good at it, we promise!
            </p>
          </div>

          <div class="row">
            <div class="col span-1-of-4">
              <ion-icon class="icon-big" name="thumbs-up-outline"></ion-icon>
              <h3>Up to 365 days/year</h3>
              <p>
                Never cook again! We really mean that. Our subscription plans
                include up to 365 days/year coverage. You can also choose to
                order more flexibly if that's your style.
              </p>
            </div>

            <div class="col span-1-of-4">
              <ion-icon class="icon-big" name="stopwatch-outline"></ion-icon>
              <h3>Ready in 20 minutes</h3>
              <p>
                You're only twenty minutes away from your delicious and super
                healthy meals delivered right to your home. We work with the
                best chefs in each town to ensure that you're 100% happy.
              </p>
            </div>

            <div class="col span-1-of-4">
              <ion-icon class="icon-big" name="leaf-outline"></ion-icon>
              <h3>100% organic</h3>
              <p>
                All our vegetables are fresh, organic and local. Animals are
                raised without added hormones or antibiotics. Good for your
                health, the environment, and it also tastes better!
              </p>
            </div>

            <div class="col span-1-of-4">
              <ion-icon class="icon-big" name="color-wand-outline"></ion-icon>
              <h3>Order anything</h3>
              <p>
                We don't limit your creativity, which means you can order
                whatever you feel like. You can also choose from our menu
                containing over 100 delicious meals. It's up to you!
              </p>
            </div>
          </div>
        </section>
      </div>

      <section class="section-meals">
        <ul class="meals-showcase clearfix">
          <li>
            <figure class="meal-photo">
              <img
                src="VENDORS/IMG/1.jpg"
                alt="Korean bibimbap with egg and vegetables"
              />
            </figure>
          </li>

          <li>
            <figure class="meal-photo">
              <img
                src="VENDORS/IMG/2.jpg"
                alt="Simple italian pizza with cherry tomatoes"
              />
            </figure>
          </li>

          <li>
            <figure class="meal-photo">
              <img
                src="VENDORS/IMG/3.jpg"
                alt="Chicken breast steak with vegetables"
              />
            </figure>
          </li>

          <li>
            <figure class="meal-photo">
              <img src="VENDORS/IMG/4.jpg" alt="Autumn pumpkin soup" />
            </figure>
          </li>
        </ul>

        <ul class="meals-showcase clearfix">
          <li>
            <figure class="meal-photo">
              <img
                src="VENDORS/IMG/5.jpg"
                alt="Paleo beef steak with vegetables"
              />
            </figure>
          </li>

          <li>
            <figure class="meal-photo">
              <img
                src="VENDORS/IMG/6.jpg"
                alt="Healthy baguette with egg and vegetables"
              />
            </figure>
          </li>

          <li>
            <figure class="meal-photo">
              <img
                src="VENDORS/IMG/7.jpg"
                alt="Burger with cheddar and bacon"
              />
            </figure>
          </li>

          <li>
            <figure class="meal-photo">
              <img
                src="VENDORS/IMG/8.jpg"
                alt="Granola with cherries and strawberries"
              />
            </figure>
          </li>
        </ul>
      </section>
      <div id="how-it-works">
        <section class="section-steps">
          <div class="row">
            <h2>How it works &mdash; Simple as 1, 2, 3</h2>
          </div>

          <div class="row">
            <div class="col span-1-of-2">
              <img
                src="VENDORS/IMG/app-iPhone.png"
                alt="Omnifood app on iphone "
                class="app-screen"
              />
            </div>

            <div class="col span-1-of-2 steps-box">
              <div class="works-step">
                <div>1</div>
                <p>
                  Choose the subscription plan that best fits your needs and
                  sign up today.
                </p>
              </div>

              <div class="works-step">
                <div>2</div>
                <p>
                  Order your delicious meal using our mobile app or website. Or
                  you can even call us!
                </p>
              </div>

              <div class="works-step">
                <div>3</div>
                <p>
                  Enjoy your meal after less than 20 minutes. See you the next
                  time!
                </p>
              </div>
              <div class="row download-buttons">
                <a href="#" class="btn-app"
                  ><img
                    src="VENDORS/IMG/download-app.svg"
                    alt="app-store-button"
                /></a>

                <a href="#" class="btn-app"
                  ><img
                    src="VENDORS/IMG/download-app-android.png"
                    alt="play-store-button"
                /></a>
              </div>
            </div>
          </div>
        </section>
      </div>
      <div id="cities">
        <section class="section-cities">
          <div class="row">
            <h2>We're currently in these cities</h2>
          </div>

          <div class="row row-cities">
            <div class="col span-1-of-4 box">
              <img src="VENDORS/IMG/lisbon-3.jpg" alt="City of Lisbon" />
              <h4>Lisbon</h4>
              <ion-icon class="city-icons" name="person"></ion-icon>
              <p>1600+ happy eaters</p>
              <ion-icon class="city-icons" name="star"></ion-icon>
              <p>60+ top chefs</p>
              <ion-icon class="city-icons" name="logo-twitter"></ion-icon>

              <div>
                <a link href=" #">@omnifood_lx </a>
              </div>
            </div>

            <div class="col span-1-of-4 box">
              <img
                src="VENDORS/IMG/san-francisco.jpg"
                alt="City of San Francisco"
              />
              <h4>San Francisco</h4>
              <ion-icon class="city-icons" name="person"></ion-icon>
              <p>3700+ happy eaters</p>
              <ion-icon class="city-icons" name="star"></ion-icon>
              <p>160+ top chefs</p>
              <ion-icon class="city-icons" name="logo-twitter"></ion-icon>
              <div>
                <a link href="#">@omnifood_sf </a>
              </div>
            </div>

            <div class="col span-1-of-4 box">
              <img src="VENDORS/IMG/berlin.jpg" alt="City of Berlin" />
              <h4>Berlin</h4>
              <ion-icon class="city-icons" name="person"></ion-icon>
              <p>2300+ happy eaters</p>
              <ion-icon class="city-icons" name="star"></ion-icon>
              <p>110+ top chefs</p>
              <ion-icon class="city-icons" name="logo-twitter"></ion-icon>
              <div>
                <a link href="#">@omnifood_berlin </a>
              </div>
            </div>

            <div class="col span-1-of-4 box">
              <img src="VENDORS/IMG/london.jpg" alt="City of London" />
              <h4>London</h4>
              <ion-icon class="city-icons" name="person"></ion-icon>
              <p>1200+ happy eaters</p>
              <ion-icon class="city-icons" name="star"></ion-icon>
              <p>50+ top chefs</p>
              <ion-icon class="city-icons" name="logo-twitter"></ion-icon>
              <div>
                <a link href="#">@omnifood_london </a>
              </div>
            </div>
          </div>
        </section>
      </div>
      <section class="customer-testimonials">
        <div class="row">
          <h2>Our customers can't live without us</h2>
        </div>
        <div class="row">
          <div class="col span-1-of-3">
            <blockquote>
              Omnifood is just awesome! I just launched a startup which leaves
              me with no time for cooking, so Omnifood is a life-saver. Now that
              I got used to it, I couldn't live without my daily meals!
            </blockquote>
            <cite>
              <img
                src="VENDORS/IMG/customer-1.jpg"
                alt="Alberto Duncan's photo"
              />
              (Alberto Duncan)
            </cite>
          </div>

          <div class="col span-1-of-3">
            <blockquote>
              Inexpensive, healthy and great-tasting meals, delivered right to
              my home. We have lots of food delivery here in Lisbon, but no one
              comes even close to Omifood. Me and my family are so in love!
            </blockquote>
            <cite>
              <img src="VENDORS/IMG/customer-2.jpg" alt="Joana Silva's photo" />
              (Joana Silva)
            </cite>
          </div>

          <div class="col span-1-of-3">
            <blockquote>
              I was looking for a quick and easy food delivery service in San
              Franciso. I tried a lot of them and ended up with Omnifood. Best
              food delivery service in the Bay Area. Keep up the great work!
            </blockquote>
            <cite>
              <img
                src="VENDORS/IMG/customer-3.jpg"
                alt="Milton Chapman's photo"
              />
              (Milton Chapman)
            </cite>
          </div>
        </div>
      </section>
      <div id="sign-up">
        <section class="section-plans">
          <div class="row">
            <h2>Start eating healthy today</h2>
          </div>

          <div class="row">
            <div class="col span-1-of-3">
              <div class="plan-box premium">
                <div>
                  <h3>Premium</h3>
                  <p class="plan-price">$399 <span> / month </span></p>
                  <p class="price-per-meal">That's only $13.30 per meal</p>
                </div>

                <div>
                  <ul>
                    <li>
                      <ion-icon
                        name="checkmark-outline"
                        size="small"
                      ></ion-icon>
                      1 meal everday
                    </li>

                    <li>
                      <ion-icon
                        name="checkmark-outline"
                        size="small"
                      ></ion-icon>
                      Order 24/7
                    </li>

                    <li>
                      <ion-icon
                        name="checkmark-outline"
                        size="small"
                      ></ion-icon>
                      Access to newest creations
                    </li>

                    <li>
                      <ion-icon
                        name="checkmark-outline"
                        size="small"
                      ></ion-icon>
                      Free delivery
                    </li>
                  </ul>
                </div>

                <div>
                  <li>
                    <a href="#" class="btn btn-full">Sign Up Now</a>
                  </li>
                </div>
              </div>
            </div>

            <div class="col span-1-of-3">
              <div class="plan-box pro">
                <div>
                  <h3>Pro</h3>
                  <p class="plan-price">$149<span> / month </span></p>
                  <p class="price-per-meal">That's only $14.90 per meal</p>
                </div>

                <div>
                  <ul>
                    <li>
                      <ion-icon
                        name="checkmark-outline"
                        size="small"
                      ></ion-icon>
                      1 meal 10 days/month
                    </li>

                    <li>
                      <ion-icon
                        name="checkmark-outline"
                        size="small"
                      ></ion-icon>
                      Order 24/7
                    </li>

                    <li>
                      <ion-icon
                        name="checkmark-outline"
                        size="small"
                      ></ion-icon>
                      Access to newest creations
                    </li>

                    <li>
                      <ion-icon
                        name="checkmark-outline"
                        size="small"
                      ></ion-icon>
                      Free delivery
                    </li>
                  </ul>
                </div>

                <div>
                  <li>
                    <a href="#" class="btn btn-ghost">Sign Up Now</a>
                  </li>
                </div>
              </div>
            </div>

            <div class="col span-1-of-3">
              <div class="plan-box starter">
                <div>
                  <h3>Starter</h3>
                  <p class="plan-price">$19 <span> / month </span></p>
                  <p class="price-per-meal">&nbsp;</p>
                </div>

                <div>
                  <ul>
                    <li>
                      <ion-icon
                        name="checkmark-outline"
                        size="small"
                      ></ion-icon>
                      1 meal
                    </li>

                    <li>
                      <ion-icon
                        name="checkmark-outline"
                        size="small"
                      ></ion-icon>
                      Order from 8am to 12pm
                    </li>

                    <li>
                      <ion-icon name="close-outline" size="small"></ion-icon>
                      Access to newest creations
                    </li>

                    <li>
                      <ion-icon
                        name="checkmark-outline"
                        size="small"
                      ></ion-icon>
                      Free delivery
                    </li>
                  </ul>
                </div>

                <div>
                  <li>
                    <a href="#" class="btn btn-ghost">Sign Up Now</a>
                  </li>
                </div>
              </div>
            </div>
          </div>
        </section>
      </div>

      <section class="Section-Form">
        <div class="row">
          <h2>We're happy to hear from you</h2>
        </div>

        <div class="row">
          <form method="post" action="#" class="Contact-form">
            <div class="row">
              <div class="col span-1-of-3">
                <label for="name">Name</label>
              </div>

              <div class="col span-2-of-3">
                <input
                  type="text"
                  name="Name"
                  id="name"
                  placeholder="Your Name"
                  required
                />
              </div>
            </div>

            <div class="row">
              <div class="col span-1-of-3">
                <label for="E-mail">E-mail</label>
              </div>

              <div class="col span-2-of-3">
                <input
                  type="email"
                  name="E-mail"
                  id="E-mail"
                  placeholder="Your E-mail"
                  required
                />
              </div>
            </div>

            <div class="row">
              <div class="col span-1-of-3">
                <label for="find-us">How did you find us?</label>
              </div>

              <div class="col span--of-3">
                <select name="Find-us" id="find-us">
                  <option value="friends" selected>Friends</option>
                  <option value="Search Engine">Search Engine</option>
                  <option value="Google">Google</option>
                  <option value="Other">Other</option>
                </select>
              </div>
            </div>

            <div class="row">
              <div class="col span-1-of-3">
                <label>Newsletter?</label>
              </div>

              <div class="col span-2-of-3">
                <input type="checkbox" name="news" id="news" checked /> Yes,
                please
              </div>
            </div>

            <div class="row">
              <div class="col span-1-of-3">
                <label for="message">Drop us a line</label>
              </div>

              <div class="col span-2-of-3">
                <textarea
                  name="message"
                  id="message"
                  placeholder="Bleed your heart out ;)"
                ></textarea>
              </div>
            </div>

            <div class="row">
              <div class="col span-1-of-3">
                <label>&nbsp;</label>
              </div>

              <div class="col span-2-of-3">
                <input type="submit" value="Send It" />
              </div>
            </div>
          </form>
        </div>
      </section>

      <footer>
        <div class="row">
          <div class="col span-1-of-2">
            <ul class="footer-nav">
              <li><a href="#">About us</a></li>
              <li><a href="#">Blog</a></li>
              <li><a href="#">Press</a></li>
              <li><a href="#">iOS App</a></li>
              <li><a href="#">Android App</a></li>
            </ul>
          </div>

          <div class="col span-1-of-2">
            <ul class="social-icons">
              <li>
                <a href="#">
                  <ion-icon
                    class="logo-facebook"
                    name="logo-facebook"
                  ></ion-icon>
                </a>
              </li>

              <li>
                <a href="#">
                  <ion-icon class="logo-twitter" name="logo-twitter"></ion-icon>
                </a>
              </li>
              <li>
                <a href="#">
                  <ion-icon class="logo-google" name="logo-google"></ion-icon>
                </a>
              </li>
              <li>
                <a href="#">
                  <ion-icon
                    class="logo-instagram"
                    name="logo-instagram"
                  ></ion-icon>
                </a>
              </li>
            </ul>
          </div>
        </div>

        <div class="row">
          <p>Copyright &copy; 2015 by Omnifood. All rights reserved</p>
        </div>
      </footer>

      <script src="https://unpkg.com/ionicons@5.0.0/dist/ionicons.js"></script>
      <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
      <script src="//cdn.jsdelivr.net/respond/1.4.2/respond.min.js"></script>
      <script src="//cdn.jsdelivr.net/html5shiv/3.7.2/html5shiv.min.jsr"></script>

      <script src="js/jquery-2.1"></script>
    </body>
  </head>
</html>

<!--

-->
