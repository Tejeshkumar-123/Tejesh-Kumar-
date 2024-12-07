<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Event Details</title> <!-- Title is placed correctly in the head -->
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
    </style> <!-- Style block placed correctly in the head -->
</head>
<body>
    <!-- Body content goes here -->
</body>
</html>

</head>
<body>
    <!-- Header Section -->
    <header class="header text-center py-4">
        <img src="PROJECT/BIT Durg College_files/bitdruglogo.png" alt="BIT Durg Logo" style="width: 150px;">
        <img src="PROJECT/BIT Durg College_files/tej.png" alt="IEEE Logo" style="width: 150px;">
        <img src="PROJECT/BIT Durg College_files/iee.png" alt="IEE Logo" style="width: 150px;">
        <h1>BIT DURG COLLEGE</h1>
    </header>
<!-- Events Section -->
<section class="events container my-5">
    <h2 class="text-center">Upcoming Events</h2>
    <div class="row">
        <!-- Event 1 -->
        <div class="col-md-4 mb-4">
            <div class="card shadow-lg" style="border-radius: 10px; background-color: #e9f7fb;">
                <img src="image1.jpg" class="card-img-top" alt="Event 1" style="border-radius: 10px 10px 0 0; height: 250px; object-fit: cover;">
                <div class="card-body">
                    <h5 class="card-title text-center" style="color: #007bff;">Event Title 1</h5>
                    <p class="card-text text-center" style="font-size: 16px; color: #555;">
                        <strong>Date:</strong> 25th December 2024<br>
                        <strong>Time:</strong> 10:00 AM<br>
                        <strong>Location:</strong> BIT Durg Auditorium
                    </p>
                    <div class="text-center">
                        <button class="btn btn-primary" data-toggle="modal" data-target="#eventModal1" style="background-color: #007bff; border-color: #007bff;">View Details</button>
                    </div>
                </div>
            </div>
        </div>
        <!-- Event 2 -->
        <div class="col-md-4 mb-4">
            <div class="card shadow-lg" style="border-radius: 10px; background-color: #f1f1f1;">
                <img src="image2.jpg" class="card-img-top" alt="Event 2" style="border-radius: 10px 10px 0 0; height: 250px; object-fit: cover;">
                <div class="card-body">
                    <h5 class="card-title text-center" style="color: #00447C;">Event Title 2</h5>
                    <p class="card-text text-center" style="font-size: 16px; color: #555;">
                        <strong>Date:</strong> 10th January 2025<br>
                        <strong>Time:</strong> 2:00 PM<br>
                        <strong>Location:</strong> BIT Durg Auditorium
                    </p>
                    <div class="text-center">
                        <button class="btn btn-primary" data-toggle="modal" data-target="#eventModal2" style="background-color: #00447C; border-color: #00447C;">View Details</button>
                    </div>
                </div>
            </div>
        </div>
        <!-- Event 3 -->
        <div class="col-md-4 mb-4">
            <div class="card shadow-lg" style="border-radius: 10px; background-color: #f9e2e2;">
                <img src="image3.jpg" class="card-img-top" alt="Event 3" style="border-radius: 10px 10px 0 0; height: 250px; object-fit: cover;">
                <div class="card-body">
                    <h5 class="card-title text-center" style="color: #d9534f;">Event Title 3</h5>
                    <p class="card-text text-center" style="font-size: 16px; color: #555;">
                        <strong>Date:</strong> 15th February 2025<br>
                        <strong>Time:</strong> 4:00 PM<br>
                        <strong>Location:</strong> BIT Durg Auditorium
                    </p>
                    <div class="text-center">
                        <button class="btn btn-primary" data-toggle="modal" data-target="#eventModal3" style="background-color: #d9534f; border-color: #d9534f;">View Details</button>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Modals for Event Details -->
    <!-- Modal for Event 1 -->
    <div class="modal fade" id="eventModal1" tabindex="-1" role="dialog" aria-labelledby="eventModalLabel1" aria-hidden="true">
        <div class="modal-dialog" role="document">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title" id="eventModalLabel1">Event Title 1 - Details</h5>
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                        <span aria-hidden="true">×</span>
                    </button>
                </div>
                <div class="modal-body">
                    <p><strong>Details:</strong> Description of Event 1...</p>
                </div>
            </div>
        </div>
    </div>

    <!-- Modal for Event 2 -->
    <div class="modal fade" id="eventModal2" tabindex="-1" role="dialog" aria-labelledby="eventModalLabel2" aria-hidden="true">
        <div class="modal-dialog" role="document">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title" id="eventModalLabel2">Event Title 2 - Details</h5>
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                        <span aria-hidden="true">×</span>
                    </button>
                </div>
                <div class="modal-body">
                    <p><strong>Details:</strong> Description of Event 2...</p>
                </div>
            </div>
        </div>
    </div>

    <!-- Modal for Event 3 -->
    <div class="modal fade" id="eventModal3" tabindex="-1" role="dialog" aria-labelledby="eventModalLabel3" aria-hidden="true">
        <div class="modal-dialog" role="document">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title" id="eventModalLabel3">Event Title 3 - Details</h5>
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                        <span aria-hidden="true">×</span>
                    </button>
                </div>
                <div class="modal-body">
                    <p><strong>Details:</strong> Description of Event 3...</p>
                </div>
            </div>
        </div>
    </div>
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

        <!-- Modals for Faculty Profiles -->
        <!-- Modal for Dr. John Doe -->
        <div class="modal fade" id="facultyModal1" tabindex="-1" role="dialog" aria-labelledby="facultyModalLabel1" aria-hidden="true">
            <div class="modal-dialog" role="document">
                <div class="modal-content">
                    <div class="modal-header">
                        <h5 class="modal-title" id="facultyModalLabel1">Dr. John Doe - Profile</h5>
                        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                            <span aria-hidden="true">×</span>
                        </button>
                    </div>
                    <div class="modal-body">
                        <img src="PROJECT/BIT Durg College_files/Dr. John Doe.png" alt="Dr. John Doe" class="img-fluid" style="max-height: 500px; object-fit: cover;">
                    </div>
                </div>
            </div>
        </div>

        <!-- Modal for Dr. Jane Smith -->
        <div class="modal fade" id="facultyModal2" tabindex="-1" role="dialog" aria-labelledby="facultyModalLabel2" aria-hidden="true">
            <div class="modal-dialog" role="document">
                <div class="modal-content">
                    <div class="modal-header">
                        <h5 class="modal-title" id="facultyModalLabel2">Dr. Jane Smith - Profile</h5>
                        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                            <span aria-hidden="true">×</span>
                        </button>
                    </div>
                    <div class="modal-body">
                        <img src="PROJECT/BIT Durg College_files/Dr. Jane Smith.png" alt="Dr. Jane Smith" class="img-fluid" style="max-height: 500px; object-fit: cover;">
                    </div>
                </div>
            </div>
        </div>

        <!-- Modal for Prof. Alice Green -->
        <div class="modal fade" id="facultyModal3" tabindex="-1" role="dialog" aria-labelledby="facultyModalLabel3" aria-hidden="true">
            <div class="modal-dialog" role="document">
                <div class="modal-content">
                    <div class="modal-header">
                        <h5 class="modal-title" id="facultyModalLabel3">Prof. Alice Green - Profile</h5>
                        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                            <span aria-hidden="true">×</span>
                        </button>
                    </div>
                    <div class="modal-body">
                        <img src="PROJECT/BIT Durg College_files/Prof. Alice Green.png" alt="Prof. Alice Green" class="img-fluid" style="max-height: 500px; object-fit: cover;">
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Events Section -->
    <section class="events container my-5">
        <h2 class="text
