<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Event Details</title>
    <!-- Include Bootstrap CSS for styling -->
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
        }
        .event-box {
            margin: 20px;
            padding: 20px;
            border-radius: 10px;
            background-color: #fff;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .header img {
            width: 100px;
            margin: 10px;
        }
        .header h1 {
            text-align: center;
            color: #00447C;
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header class="header">
        <img src="PROJECT/BIT Durg College_files/bitdruglogo.png" alt="BIT Durg Logo">
        <img src="PROJECT/BIT Durg College_files/tej.png" alt="IEEE Logo">
        <!-- New IEE Logo -->
        <img src="PROJECT/BIT Durg College_files/iee.png" alt="IEE Logo">
        <h1>BIT DURG COLLEGE</h1>
    </header>

    <!-- About Section -->
    <section class="about container text-center">
        <h2>About BIT Durg</h2>
        <p>
            Established in 1986, BIT Durg (Bhilai Institute of Technology, Durg) is a premier institution dedicated to excellence in education, research, and innovation. Nestled in the heart of Chhattisgarh, BIT Durg offers state-of-the-art facilities, a dynamic curriculum, and a vibrant academic environment that fosters holistic development. It is recognized for producing industry-ready professionals and nurturing the next generation of leaders in technology and management.
        </p>
        <p>
            The college is affiliated with Chhattisgarh Swami Vivekanand Technical University (CSVTU) and is accredited by the National Board of Accreditation (NBA) and NAAC, ensuring the highest standards in education. BIT Durg is renowned for its academic rigor, vibrant cultural ecosystem, and commitment to innovation and social responsibility.
        </p>
        <h3>Achievements</h3>
        <ul class="list-unstyled">
            <li><strong>Top Engineering Institution:</strong> Ranked among the top engineering colleges in Central India.</li>
            <li><strong>Innovation Hub:</strong> Over 50 patents filed and several innovative projects recognized at the national level.</li>
            <li><strong>Placement Success:</strong> Consistent record of 90%+ placements in top companies like TCS, Infosys, Wipro, and Accenture.</li>
            <li><strong>Industry Collaboration:</strong> Partnerships with leading companies and institutions for research and training.</li>
            <li><strong>Active IEEE Chapter:</strong> The college hosts an active IEEE Student Branch and Computer Society, promoting technological advancements.</li>
            <li><strong>Extracurricular Excellence:</strong> Students excel in technical, cultural, and sports competitions at regional and national levels.</li>
            <li><strong>Community Impact:</strong> Initiatives like rural education programs and environmental drives positively impact society.</li>
        </ul>
        <!-- Updated IEEE Registration Button -->
        <a href="https://docs.google.com/forms/d/e/1FAIpQLSfmXcexHxCwYxz92vJwqkiWzTcUj0v3qRQRLhD6UnFvb6WusQ/viewform?usp=sf_link" class="btn btn-primary" target="_blank" rel="noopener noreferrer">
           Register for IEEE
        </a>
    </section>

    <!-- Office Bearers Section -->
    <section class="OFFICE-BEARERS container my-5">
        <h2 class="text-center">Office Bearers</h2>
        <div class="row">
            <!-- Faculty 1 -->
            <div class="col-md-4 mb-4">
                <div class="card shadow-lg" style="border-radius: 10px; background-color: #f1f1f1;">
                    <img src="PROJECT/BIT Durg College_files/Dr. John Doe.png" class="card-img-top" alt="Dr. John Doe" style="border-radius: 10px 10px 0 0; height: 250px; object-fit: cover;">
                    <div class="card-body">
                        <h5 class="card-title text-center" style="color: #00447C;">Dr. John Doe</h5>
                        <p class="card-text text-center" style="font-size: 16px; color: #555;">
                            <strong>Position:</strong> Dean, Faculty of Engineering<br>
                            <strong>Education:</strong> PhD in Computer Science from ABC University
                        </p>
                        <div class="text-center">
                            <button class="btn btn-primary" data-toggle="modal" data-target="#facultyModal1" style="background-color: #00447C; border-color: #00447C;">View Profile</button>
                        </div>
                    </div>
                </div>
            </div>
            <!-- Faculty 2 -->
            <div class="col-md-4 mb-4">
                <div class="card shadow-lg" style="border-radius: 10px; background-color: #e9f7fb;">
                    <img src="PROJECT/BIT Durg College_files/Dr. Jane Smith.png" class="card-img-top" alt="Dr. Jane Smith" style="border-radius: 10px 10px 0 0; height: 250px; object-fit: cover;">
                    <div class="card-body">
                        <h5 class="card-title text-center" style="color: #007bff;">Dr. Jane Smith</h5>
                        <p class="card-text text-center" style="font-size: 16px; color: #555;">
                            <strong>Position:</strong> Associate Professor, Department of Electronics<br>
                            <strong>Education:</strong> MTech in Electronics from XYZ University
                        </p>
                        <div class="text-center">
                            <button class="btn btn-primary" data-toggle="modal" data-target="#facultyModal2" style="background-color: #007bff; border-color: #007bff;">View Profile</button>
                        </div>
                    </div>
                </div>
            </div>
            <!-- Faculty 3 -->
            <div class="col-md-4 mb-4">
                <div class="card shadow-lg" style="border-radius: 10px; background-color: #f9e2e2;">
                    <img src="PROJECT/BIT Durg College_files/Prof. Alice Green.png" class="card-img-top" alt="Prof. Alice Green" style="border-radius: 10px 10px 0 0; height: 250px; object-fit: cover;">
                    <div class="card-body">
                        <h5 class="card-title text-center" style="color: #d9534f;">Prof. Alice Green</h5>
                        <p class="card-text text-center" style="font-size: 16px; color: #555;">
                            <strong>Position:</strong> Professor, Department of Civil Engineering<br>
                            <strong>Education:</strong> PhD in Structural Engineering from DEF University
                        </p>
                        <div class="text-center">
                            <button class="btn btn-primary" data-toggle="modal" data-target="#facultyModal3" style="background-color: #d9534f; border-color: #d9534f;">View Profile</button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Events Section -->
    <section class="events container my-5">
        <h2 class="text-center">Upcoming Events</h2>
        <div class="container mt-4">
            <!-- Event 1: Oath Taking Ceremony -->
            <div class="event-box mb-4 p-4 shadow-lg" style="background-color: #f9f9f9; border-radius: 10px;">
                <h3 class="text-center" style="color: #00447C;">Oath Taking Ceremony</h3>
                <p><strong>Description:</strong> The Oath Taking Ceremony was conducted successfully, marking the official beginning of the new academic year. Students, faculty, and staff took part in this ceremony to reaffirm their commitment to academic excellence and ethical conduct.</p>
            </div>
            <!-- Event 2: Company in Focus -->
            <div class="event-box mb-4 p-4 shadow-lg" style="background-color: #e9f7fb; border-radius: 10px;">
                <h3 class="text-center" style="color: #007bff;">Company in Focus</h3>
                <p><strong>Description:</strong> In this session, students were introduced to the top industry players in various fields, providing valuable insights into the current trends, job opportunities, and career growth. Industry leaders shared their experiences, offering practical knowledge to all attendees.</p>
            </div>
            <!-- Event 3: Event Posters -->
            <div class="event-box mb-4 p-4 shadow-lg" style="background-color: #fef9e7; border-radius: 10px;">
                <h3 class="text-center" style="color: #ff9900;">Event Posters</h3>
                <p><strong>Description:</strong> Vibrant posters highlighting the themes of various events were displayed across the campus, adding a touch of excitement and visual appeal to the atmosphere.</p>
            </div>
        </div>
    </section>

    <!-- Footer Section -->
    <footer class="text-center py-3 bg-dark text-light">
        © 2024 BIT Durg College. All rights reserved.
    </footer>

    <!-- Include Bootstrap JS, Popper.js, and jQuery for other functionalities -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.2/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>

</body>
</html>
