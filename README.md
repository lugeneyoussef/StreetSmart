# StreetSmart "Paving The Way To Inclusivity"
![StreetSmartLogo](https://github.com/user-attachments/assets/ec2d0125-73a9-452f-85da-8a8b5ae51523)

## Overview:
StreetSmart is an AI-powered web app that improves sidewalk safety and accessibility, focusing on the needs of individuals with mobility challenges.

## Why StreetSmart?
My team and I identified a critical issue in our community: sidewalk hazards, such as damage and obstructions which create unsafe, difficult to navigate pathways with limited accessibility, especially for individuals with mobility challenges. Despite these issues, repairs are often delayed due to inefficient reporting and planning processes. To address this, we developed StreetSmart, a web app prototype featuring accessibility focused color-coded navigation maps, a user-friendly hazard reporting system, and tools for city officials to access current hazards and generate actionable proposals to streamline repair projects. By leveraging AI, StreetSmart empowers communities, improves accessibility, and accelerates urban infrastructure improvements. 

Residents should use StreetSmart because it addresses a critical need for safer and more accessible sidewalks, benefiting individuals with mobility challenges and the broader community. By providing AI-powered navigation with color coded accessibility maps, StreetSmart helps users identify the safest routes while avoiding hazards like uneven pavement or construction. Its easy to use hazard reporting feature allows community members to actively contribute to improving sidewalk conditions, creating a collaborative approach to urban safety. Additionally, StreetSmart streamlines repair processes for city officials by offering actionable project proposals, ensuring faster and more efficient infrastructure improvements. With its focus on inclusivity and safety StreetSmart makes cities more navigable and accessible for everyone.

## App Showcase:

My team and I developed StreetSmart, an app prototype designed to enhance sidewalk safety and accessibility through three key features. The first feature, powered by the Google Maps API, enables users to select starting and ending points and view color coded directions on a map based on route accessibility (Easily Accessible = Green, Moderately Accessible = Blue, Inaccessible = Red, Challenging = Purple). Since real sidewalk hazard data is unavailable, the color coding is based on synthetic data, with a clear legend provided for user reference. We also integrated text to speech step by step audio directions, offering support for visually impaired users and bicyclists. These audio guides explain why specific routes were selected, such as avoiding uneven pavements, flooding, or construction, along with written directions and estimated walking time.

The second feature allows users to report sidewalk hazards to city officials by uploading a description, severity level, accessibility level, location, and photo of the hazard. These reports are stored as new entries in a Pandas DataFrame, updated in our dataset, and saved to a CSV file for secure tracking and management. The third feature using OpenAI ChatGPT provides actionable proposals for resolving hazards, displayed in two tables: Completed Hazards and Current Hazards (categorized as “In Progress” or “Not Started”). City officials can update the status of reports and generate project plans, including descriptions, timelines, resources, budgets, and materials needed, through a dropdown selection. This feature helps city officials pinpoint the exact requirements needed to resolve each hazard efficiently.

Key challenges in designing and developing this prototype include API integration, ensuring data privacy, and accommodating diverse user needs, which were addressed through innovative problem-solving, teamwork, and ethical AI practices. This project offers a practical solution to urban accessibility issues, empowering communities and fostering safer, more inclusive environments. 

## Watch Our Demo Video For StreetSmart:
https://github.com/user-attachments/assets/d89484d9-4792-4abc-9849-f2aa1210691b










