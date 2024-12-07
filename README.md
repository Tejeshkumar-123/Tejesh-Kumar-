<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BIT Durg College</title>
    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
        }
        .header {
            background: #00447C;
            color: white;
            text-align: center;
            padding: 20px 10px;
        }
        .header img {
            max-height: 80px;
            margin-right: 20px;
        }
        .about {
            background: #f9f9f9;
            padding: 30px;
        }
        .office-bearers .card {
            margin: 15px 0;
        }
        .grievances form {
            background: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <header class="header">
        <img src="bitdruglogo.png" alt="BIT Durg Logo">
        <img src="iee.png" alt="IEEE Logo">
        <h1>BIT DURG COLLEGE</h1>
    </header>

    <!-- About Section -->
    <section class="about container text-center">
        <h2>About BIT Durg</h2>
        <p>
            Established in 1986, BIT Durg (Bhilai Institute of Technology, Durg) is a premier institution dedicated to excellence in education, research, and innovation. It is recognized for producing industry-ready professionals and nurturing leaders in technology and management.
        </p>
        <h3>Achievements</h3>
        <ul class="list-unstyled">
            <li><strong>Top Engineering Institution:</strong> Ranked among the top engineering colleges in Central India.</li>
            <li><strong>Innovation Hub:</strong> Over 50 patents filed and several innovative projects recognized at the national level.</li>
            <li><strong>Placement Success:</strong> Consistent record of 90%+ placements in top companies like TCS, Infosys, Wipro, and Accenture.</li>
        </ul>
        <a href="https://docs.google.com/forms/d/e/1FAIpQLSfmXcexHxCwYxz92vJwqkiWzTcUj0v3qRQRLhD6UnFvb6WusQ/viewform?usp=sf_link" class="btn btn-primary" target="_blank">Register for IEEE</a>
    </section>

    <!-- Office Bearers Section -->
    <section class="office-bearers container my-5">
        <h2 class="text-center">Office Bearers</h2>
        <div class="row">
            <div class="col-md-4 mb-4">
                <div class="card shadow-lg">
                    <img src="DrJohnDoe.png" class="card-img-top" alt="Dr. John Doe">
                    <div class="card-body">
                        <h5 class="card-title">Dr. John Doe</h5>
                        <p class="card-text">Dean, Faculty of Engineering</p>
                        <button class="btn btn-primary" data-toggle="modal" data-target="#facultyModal1">View Profile</button>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Modals -->
    <div class="modal fade" id="facultyModal1" tabindex="-1" role="dialog">
        <div class="modal-dialog" role="document">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title">Dr. John Doe - Profile</h5>
                    <button type="button" class="close" data-dismiss="modal">
                        <span>&times;</span>
                    </button>
                </div>
                <div class="modal-body">
                    <img src="DrJohnDoe.png" alt="Dr. John Doe" class="img-fluid">
                </div>
            </div>
        </div>
    </div>

    <!-- Grievances Section -->
    <section class="grievances container my-5">
        <h2 class="text-center">Grievances & Feedback</h2>
        <form>
            <label for="feedback">Your Feedback</label>
            <textarea id="feedback" class="form-control" rows="4"></textarea>
            <button type="submit" class="btn btn-success mt-3">Submit</button>
        </form>
    </section>

    <!-- Footer -->
    <footer class="text-center py-3 bg-dark text-light">
        © 2024 BIT Durg College. All rights reserved.
    </footer>

    <!-- Bootstrap JS and jQuery -->
    <script src="https://code.jquery.com/jquery-3.6.4.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
