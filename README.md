# Project Responsive Web Design using Bootstrap
## Date:

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
home page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tech Haven</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">Tech Haven</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link active" href="#home">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#about">About Us</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#products">Products</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="C:\Users\admin\Desktop\WEB\SIHPS\services-tech haven.html">Services</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="C:\Users\admin\Desktop\WEB\SIHPS\contact us.html">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Home Section -->
    <section id="home" class="py-5 text-center bg-light">
        <div class="container">
            <h1>Welcome to Tech Haven</h1>
            <p class="lead">Your one-stop shop for the latest gadgets and technology at unbeatable prices!</p>
            <a href="#products" class="btn btn-primary">Shop Now</a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-5">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-md-6">
                    <h2>About Tech Haven</h2>
                    <p>At Tech Haven, we offer a wide range of cutting-edge electronics and gadgets designed to enhance your digital experience. From the latest smartphones to high-performance laptops, we bring the best technology to your doorstep at competitive prices.</p>
                </div>
                <div class="col-md-6">
                    <img src="c:\Users\MAHALAKSHMI B\OneDrive\Pictures\Screenshots\Screenshot 2025-05-14 145829.png" class="img-fluid rounded" alt="About Us">
                </div>
            </div>
        </div>
    </section>

    <!-- Products Section -->
    <section id="products" class="py-5 bg-light">
        <div class="container">
            <h2 class="text-center">Featured Products</h2>
            <div class="row mt-4">
                <div class="col-md-4">
                    <div class="card">
                        <img src="https://i.pinimg.com/736x/84/a1/55/84a155b0d056fc6c78fa71808c7f9ad9.jpg" class="card-img-top" alt="iPhone 15 Pro Max">
                        <div class="card-body text-center">
                            <h5 class="card-title">iPhone 15 Pro Max</h5>
                            <p class="card-text">Up to 2000 nits (peak brightness), perfect for outdoor visibility.</p>
                            <p class="card-text"><strong>₹1,50,000</strong></p>
                            <a href="#" class="btn btn-primary">Buy Now</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <img src="https://i.pinimg.com/736x/4f/34/ad/4f34ad5978d2a681d270368c6705f28f.jpg" class="card-img-top" alt="boAt Stone 1200F">
                        <div class="card-body text-center">
                            <h5 class="card-title">boAt Stone 1200F</h5>
                            <p class="card-text">IPX7 water resistance, suitable for poolside or beach use.</p>
                            <p class="card-text"><strong>₹12,000</strong></p>
                            <a href="#" class="btn btn-primary">Buy Now</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <img src="https://i.pinimg.com/736x/35/8b/2e/358b2ec5c09b1119f2cbe917f8b38549.jpg"  width="525px" height="525px"  class="card-img-top" alt="Playstation Controller">
                        <div class="card-body text-center">
                            <h5 class="card-title">Playstation Controller</h5>
                            <p class="card-text">Designed to fit comfortably in most hands.</p>
                            <p class="card-text"><strong>₹16,000</strong></p>
                            <a href="#" class="btn btn-primary">Buy Now</a>
                        </div>
                    </div>
                </div>
            </div>
            <div class="row mt-4">
                <div class="col-md-4">
                    <div class="card">
                    <img src="https://i.pinimg.com/736x/c1/c9/9a/c1c99aa0d88b82bc32278592877ef831.jpg"  class="card-img-top" alt="boAt Rockerz">
                    <div class="card-body text-center">
                        <h5 class="card-title">boAt Rockerz</h5>
                        <p class="card-text">Ergonomic design with soft ear cushions for extended wear.</p>
                        <p class="card-text"><strong>₹8000</strong></p>
                        <a href="#" class="btn btn-primary">Buy Now</a>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="https://i.pinimg.com/736x/36/2f/4c/362f4ce560c8185b1516ff42bdb10023.jpg" width="467px" height="467px"  class="card-img-top" alt="MacBook Air (M2, 2023)">
                    <div class="card-body text-center">
                        <h5 class="card-title">MacBook Air (M2, 2023)</h5>
                        <p class="card-text">Lightweight and portable, perfect for on-the-go productivity.</p>
                        <p class="card-text"><strong>₹1,70,000</strong></p>
                        <a href="#" class="btn btn-primary">Buy Now</a>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="https://i.pinimg.com/736x/7b/8f/c2/7b8fc2879d842503cac1de15f9a1baf6.jpg" width="467px" height="467px"  class="card-img-top" alt="Samsung Galaxy Watch 6">
                    <div class="card-body text-center">
                        <h5 class="card-title">Samsung Galaxy Watch 6</h5>
                        <p class="card-text">Comprehensive tracking, including heart rate, SpO2, stress, and sleep.</p>
                        <p class="card-text"><strong>₹17,000</strong></p>
                        <a href="#" class="btn btn-primary">Buy Now</a>
                    </div>
                </div>
            </div>

        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-5">
        <div class="container">
            <h2 class="text-center">Why Shop With Us?</h2>
            <div class="row text-center mt-4">
                <div class="col-md-4">
                    <h4>Free Shipping</h4>
                    <p>On orders over $100</p>
                </div>
                <div class="col-md-4">
                    <h4>Easy Returns</h4>
                    <p>Hassle-free returns within 30 days</p>
                </div>
                <div class="col-md-4">
                    <h4>24/7 Support</h4>
                    <p>We’re here to help you anytime</p>
                </div>
            </div>
        </div>
    </section>


    <!-- Footer -->
    <footer class="bg-dark text-white text-center py-3">
        <div class="container">
            <p class="mb-0">&copy; 2025 Tech Haven | Your Gateway to Innovation</p>
        </div>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

service page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Services - Tech Haven</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">Tech Haven</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="C:\Users\admin\Desktop\WEB\SIHPS\project.html">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="C:\Users\admin\Desktop\WEB\SIHPS\project.html">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link active" href="#services">Services</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="C:\Users\admin\Desktop\WEB\SIHPS\contact us.html">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
    <!-- Services Section -->
    <section id="services" class="py-5 bg-light">
        <div class="container">
            <h2 class="text-center">Why Shop With Us?</h2>
            <p class="text-center lead">At Tech Haven, we strive to provide an exceptional shopping experience with top-notch services to make your tech purchases easier and more satisfying. Here's what you can expect from us:</p>

            <div class="row text-center mt-4">
                <!-- Free Shipping -->
                <div class="col-md-4 mb-4">
                    <div class="card shadow-sm">
                        <div class="card-body">
                            <h4 class="card-title">Free Shipping</h4>
                            <p class="card-text">Enjoy free shipping on all orders over $100. We ensure that your products are delivered swiftly and securely to your doorstep.</p>
                        </div>
                    </div>
                </div>
                <!-- Easy Returns -->
                <div class="col-md-4 mb-4">
                    <div class="card shadow-sm">
                        <div class="card-body">
                            <h4 class="card-title">Easy Returns</h4>
                            <p class="card-text">We offer hassle-free returns within 30 days of purchase. If you're not satisfied with your product, we make returning it simple and stress-free.</p>
                        </div>
                    </div>
                </div>
                <!-- 24/7 Customer Support -->
                <div class="col-md-4 mb-4">
                    <div class="card shadow-sm">
                        <div class="card-body">
                            <h4 class="card-title">24/7 Customer Support</h4>
                            <p class="card-text">Our dedicated customer support team is available 24/7 to assist you with any queries, product recommendations, or technical support you may need.</p>
                        </div>
                    </div>
                </div>
            </div>

            <div class="text-center mt-5">
                <a href="#contact" class="btn btn-primary btn-lg">Get in Touch</a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-white text-center py-3">
        <div class="container">
            <p class="mb-0">&copy; 2025 Tech Haven | Your Gateway to Innovation</p>
        </div>
    </footer>





    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

contact us page 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - Tech Haven</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">Tech Haven</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="C:\Users\admin\Desktop\WEB\SIHPS\project.html">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="C:\Users\admin\Desktop\WEB\SIHPS\project.html">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="C:\Users\admin\Desktop\WEB\SIHPS\project.html">Products</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="C:\Users\admin\Desktop\WEB\SIHPS\services-tech haven.html">Services</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link active" href="#contact">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Contact Us Section -->
    <section id="contact" class="py-5 bg-light">
        <div class="container">
            <h2 class="text-center">Contact Us</h2>
            <p class="text-center lead">We'd love to hear from you! Whether you have a question, need support, or want to provide feedback, fill out the form below or use the other contact methods provided. Our team is ready to assist you.</p>

            <div class="row justify-content-center">
                <div class="col-md-8">
                                        <!-- Contact Form -->
                                        <form>
                                            <div class="mb-3">
                                                <label for="name" class="form-label">Your Name</label>
                                                <input type="text" class="form-control" id="name" placeholder="Enter your name" required>
                                            </div>
                                            <div class="mb-3">
                                                <label for="email" class="form-label">Your Email</label>
                                                <input type="email" class="form-control" id="email" placeholder="Enter your email" required>
                                            </div>
                                            <div class="mb-3">
                                                <label for="message" class="form-label">Your Message</label>
                                                <textarea class="form-control" id="message" rows="4" placeholder="Enter your message" required></textarea>
                                            </div>
                                            <div class="d-grid gap-2">
                                                <button type="submit" class="btn btn-primary btn-lg">Send Message</button>
                                            </div>
                                        </form>
                                    </div>
                                </div>
                    

            <!-- Our Location Section -->
            <div class="row justify-content-center mt-5">
                <div class="col-md-8">
                    <h3 class="text-center">Our Location</h3>
                    <p class="text-center">Visit us at our physical store or reach out to us via the contact methods below.</p>
                    <div class="embed-responsive embed-responsive-16by9">
                        <!-- Google Maps Embed -->
                        <iframe class="embed-responsive-item" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3240.722399263858!2d-118.25507228405374!3d34.05223438060393!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x80c2c01aee3c0c3f%3A0x44d64b617660c1b6!2sLos%20Angeles%2C%20CA!5e0!3m2!1sen!2sus!4v1674768368553!5m2!1sen!2sus" width="100%" height="400" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
                    </div>
                </div>
            </div>

            <!-- Additional Contact Information Section -->
            <div class="row justify-content-center mt-5">
                <div class="col-md-8">
                    <h3 class="text-center">Other Ways to Reach Us</h3>
                    <ul class="list-unstyled">
                        <li><strong>Phone:</strong> +1 456 789 123</li>
                        <li><strong>Email:</strong> <a href="mailto:support@techhaven.com">support@techhaven.com</a></li>
                        <li><strong>Live Chat:</strong> Available on our website</li>
                        <li><strong>Social Media:</strong> Follow us on <a href="#">Facebook</a>, <a href="#">Twitter</a>, and <a href="#">Instagram</a></li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-white text-center py-3">
        <div class="container">
            <p class="mb-0">&copy; 2024 Tech Haven | Your Gateway to Innovation</p>
        </div>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/1b689efb-b2f4-437d-926b-80cd4c1f5f75)

![image](https://github.com/user-attachments/assets/387623a9-db54-4b59-bc58-ea1ba4b39857)

![image](https://github.com/user-attachments/assets/a0f0d31b-1c50-4804-9c34-ee388abab657)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
