<a name="readme-top"></a>

# ICT2101-2022-P4-1 - Ambulance Services Management System

## Member Roles

| Member         | Role(s)                                     |
| -------------- | ------------------------------------------- |
| Shaun Varghese | Team Lead / Backend Developer               |
| Chee Kang Chen | Tech Lead(Architect) / Full Stack Developer |
| Ling Sing Yu   | Front End Developer / UI/UX Designerr       |
| Lim Ryan       | Full Stack Developer / QA Engineer          |

<!-- ABOUT THE PROJECT -->

## About The Project

This project aims to create a reliable and robust web application for managing employee scheduling and workloads in an emergency response team at a large hospital. The application will benefit both managers and staff on the ambulance team by providing an all-in-one workload manager and a graphical user interface (GUI) visualiser. This system will improve the efficiency of shift scheduling for all team members.

As this project requires continuous development from production to maintenance, we will employ the use of Agile methodology for our project. Specifically, we will be using the Kanban methodology. Kanban allows the project team to easily visualise our tasks, manage our flow, and helps limit “Work in Progress” tasks. This is to ensure that we are moving at a high speed with accuracy, which helps with efficiency of the team.

<!-- <p align="right">(<a href="#readme-top">back to top</a>)</p> -->

## Built With

| Application                | Framework(s) |
| -------------------------- | ------------ |
| Frontend application       | React.js     |
| Backend application        | Express.js   |
| Database management system | MySQL        |

# Developed Protoype

The Figma Prototype has been developed in 3 parts and each part can be accessed via the links below

- []() Staff Pages - [figma-staff]
- []() Manager Pages - [figma-manager]
- []() IT admin Pages - [figma-IT]

## Prototype Flows

### Staff Pages

#### Dashboard

1. Login -> View Dashboard
2. Click on any colour coded day
   - Green - Job assigned on that day
   - Orange - Understaffed Day
   - Red - Rejection request pending attention
3. Click on ambulances in Daily overview to indicate availability/ review assigned job/ submit rejection request

#### Profile Details

1. View profile and details
2. Edit profile
3. Create new profile
   - Will override existing profile

### Manager Pages

#### Dashboard

1. Login -> View Dashboard
2. Click on green day to view daily overview
3. Click on ambulance to view detials of shift

#### Allocate Jobs

1. Click on red day to view daily overview and understaffed ambulances
2. Drag staff tile from right panel to ambulance to assign
3. Confirm asignment of staff

#### Rejections

1. View all pending rejections in a list
2. Click on individual rejection for details
3. Choose to accept/reject rejection and confirm

### IT Admin Pages

#### Staff Directory

1. View all staff members in a list
2. Click on any staff member to expand details
3. Choose to edit or remove staff member from database

#### Add Staff

1. Input new details of staff to be added
2. Confirm addition of staff to database

#### Vehicles

1. View all vehicles in a list
2. Click on any vehicle to expand details
3. Choose to edit or remove vehicle from database
4. Add vehicle via button on top right
   - Input details of vehicle to be added
   - Confirm addition of vehicle

<p align="right">(<a href="#readme-top">back to top</a>)</p>

# Acknowledgments

The team would like to thank all Professors for the knowledge they have imparted to us and for giving us their time during labtorials and consultations.

- []() Prof. Marcus Tan
- []() Prof. Eric Lam
- []() Prof. Alex Chen
- []() Prof. Oran Devilly

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[figma-staff]: https://www.figma.com/proto/4lI6XV0cZOifpHER3bquuG/WEEWOO?node-id=238%3A3574&scaling=min-zoom&page-id=5%3A765&starting-point-node-id=5%3A37025&show-proto-sidebar=1
[figma-manager]: https://www.figma.com/proto/4lI6XV0cZOifpHER3bquuG/WEEWOO?node-id=5%3A17869&scaling=min-zoom&page-id=0%3A1&starting-point-node-id=241%3A3068
[figma-it]: https://www.figma.com/proto/4lI6XV0cZOifpHER3bquuG/WEEWOO?node-id=30%3A6947&scaling=min-zoom&page-id=5%3A17270&starting-point-node-id=30%3A6947
