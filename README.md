# DormMate 

# Main Purpose:

The app aims to solve the challenge of finding compatible roommates in dormitories. By collecting detailed lifestyle and preference data from students, the app uses clustering and similarity algorithms to match individuals with similar habits and needs. This leads to improved living experiences and reduces conflicts among roommates.


# Target Audience:

Particularly those living in dorms or shared housing who want to ensure they are paired with compatible roommates. Also the staff who oversee housing assignments and wish to streamline the process through data-driven matchings.


# Key Features:

# User Registration and Authentication:
  Secure sign-up and login features to protect user data.

# Test Submission:
  A detailed questionnaire where students provide information such as desired dorm size, daily room time, music disturbance tolerance, sports preferences, and cleanliness level.

# Data Processing and Matching:
# Clustering:
  Uses the K-Means algorithm to group students based on test results.
# Weighted Similarity:
  Calculates similarity scores between student responses to recommend the best possible roommate matches.

# Admin Panel:
  Admins can trigger the matching process and release the results after verifying data quality.
  
# User Interface:
  Engaging UI screens for registration, test submission, and displaying match results.


# Platform:
  This app is develeoped via Flutter.

# Data Storage:
  User Profiles
  Test Results
  Clustering Results
  Admin Settings

# Unique Selling Point:
  The app distinguishes itself by using advanced data-driven algorithms to ensure that roommate matches are not just random pairings. Its dual approach—clustering combined with a weighted similarity function—provides a more precise and personalized matching process.

# Challenges:
  
  # Algorithm Tuning and Performance:
    Ensuring the clustering and similarity calculations accurately reflect compatibility.
    Optimizing performance, especially as the dataset grows.
  # Data Security and Privacy:
    Protecting sensitive user information with robust authentication and secure storage practices.
  # Integration Between Flutter and Database:
    Typically, direct connections between a mobile app and MySQL are not recommended; implementing a secure backend API might be necessary.
  # User Experience:
    Designing an intuitive interface that accommodates the data collection and display of complex matching information.
  # Scalability:
    Maintaining performance and data integrity as the number of users increases.
