

# Job Site Application

Welcome to the Job Site Application! This project is a platform where users can create profiles, upload resumes, browse job openings, and manage their job applications.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Database Schema](#database-schema)
- [Deployment](#deployment)
- [Additional Features](#additional-features)
- [Contributing](#contributing)
- [License](#license)

## Features

### Core Features
1. **User Profile Management**: 
   - Create a profile, upload resumes, and edit personal information.
   - Manage education, experience, and projects.
   
2. **Job Browsing and Filtering**: 
   - View all available jobs.
   - Filter jobs based on Location, Job Type (full-time, part-time, remote), Job Title, Years of Experience, and Compensation.
   
3. **Application Tracking**: 
   - View all the jobs you have applied to.
   - Manage your job applications.

### Optional Features (Above & Beyond)
1. **Employer Profile Management**:
   - Employers can create profiles and manage job postings.
   
2. **Applicant Tracking for Employers**:
   - Employers can view applicants and filter them based on various criteria.
   
3. **Enhanced Filtering Categories**:
   - Enhanced job filtering capabilities with more intuitive categories.

## Technologies Used

- **Frontend**: React
- **Backend**: Express.js,NODE.js,Cloudinary,Multer.
- **Database**: MongoDB
- **Deployment**: Netlify

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Mukulraj109/jobportal.git
   ```
2. Navigate to the project directory:
   ```bash
   cd your-repo-name
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Set up the environment variables:
   - Create a `.env` file in the root directory.
   - Add necessary environment variables as described in the `.env.example` file.
   
5. Run the application:
   ```bash
   npm start
   ```

## Usage

1. Register a new user or login with an existing account.
2. Create or update your profile, including uploading a resume.
3. Browse job openings and apply filters as needed.
4. Apply to jobs and track your applications in the dashboard.



## Deployment

The application is deployed on [Netlify]. You can access it at [https://jobquested.netlify.app/]
To deploy locally using Docker:
1. Build the Docker image:
   ```bash
   docker build -t job-site-app .
   ```
2. Run the Docker container:
   ```bash
   docker run -p 3000:3000 job-site-app
   ```


## Contributing

Contributions are welcome! Please follow the standard Git workflow:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

