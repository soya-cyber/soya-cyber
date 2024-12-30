<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profile Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f6f8fa;
        }
        .container {
            max-width: 900px;
            margin: 20px auto;
            background: #fff;
            border: 1px solid #ddd;
            border-radius: 8px;
            overflow: hidden;
            padding: 20px;
        }
        .profile-header {
            display: flex;
            align-items: center;
            gap: 20px;
            border-bottom: 1px solid #eaecef;
            padding-bottom: 20px;
        }
        .profile-header img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
        }
        .profile-info {
            flex-grow: 1;
        }
        .profile-info h1 {
            margin: 0;
            font-size: 1.8rem;
        }
        .profile-info p {
            margin: 5px 0;
            color: #555;
        }
        .repositories {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        .repository {
            background: #f6f8fa;
            padding: 15px;
            border: 1px solid #e1e4e8;
            border-radius: 6px;
        }
        .repository h3 {
            margin: 0 0 10px;
            font-size: 1.2rem;
        }
        .repository p {
            margin: 0;
            color: #586069;
        }
        .footer {
            text-align: center;
            padding: 10px;
            color: #586069;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="profile-header">
            <img src="https://via.placeholder.com/120" alt="Profile Picture">
            <div class="profile-info">
                <h1>Blake White</h1>
                <p>@blwhit</p>
                <p>Hello! This GitHub account is dedicated to the documentation of my technical projects. These repositories contain write-ups that showcase my practical work.</p>
            </div>
        </div>

        <h2>Popular Repositories</h2>
        <div class="repositories">
            <div class="repository">
                <h3>Remote-Keylogger</h3>
                <p>Creating a remote keylogger in Python and disguising the executable as a JPEG.</p>
            </div>
            <div class="repository">
                <h3>EDR-Attack-and-Defense</h3>
                <p>Cyber Attack/Defense home lab using Sliver, LimaCharlie [SIEM], & VMs.</p>
            </div>
            <div class="repository">
                <h3>SOC-Training</h3>
                <p>TryHackMe Cybersecurity Analyst Certificate.</p>
            </div>
            <div class="repository">
                <h3>Web-Application-Development</h3>
                <p>Develop Website, Teamwork, SCRUM Framework.</p>
            </div>
            <div class="repository">
                <h3>-naughty-file-on-their-server</h3>
                <p>A Naughty File On Their Server.</p>
            </div>
            <div class="repository">
                <h3>Network-Intrusion-and-Sniffing</h3>
                <p>Network Intrusion, Password Cracking, Packet Sniffing.</p>
            </div>
        </div>

        <div class="footer">
            <p>© 2024 Blake White | 4 contributions in the last year</p>
        </div>
    </div>
</body>
</html>
