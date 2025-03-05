# API Data Integration

This repository contains various projects that utilize different research and data science-relevant APIs to improve the efficiency of data science workflows, research coordination, and participant management. By integrating multiple services, it automates and streamlines tasks in ways that significantly enhance project efficiency.

## Key Features:
- **Google Sheets API**: Automates updates to Google Sheets databases based on RedCap data completion, facilitating seamless data synchronization across platforms.
- **RedCap API**: Allows for data analysis directly within RedCap, enabling efficient management of project data and participant information. Includes automated data imports at specific time points to initiate project legs and trigger notifications/alerts within RedCap.
- **Text Service APIs**: Automates participant communication, including sending reminders, project updates, and other important messages.

## Submodules

This repository includes several submodules. Each submodule is an independent repository that utilizes APIS -  linked to this main repository for modular integration.

- **[Age Cohort Check APIs](https://github.com/dzweben/age-cohort-check-apis)**: Provides APIs for checking age cohorts in various datasets.

To view or interact with any submodule, you can navigate to the respective submodule folder inside this repository or visit their respective GitHub repositories. To clone and initialize submodules locally, use the following commands:


# API Data Integration

This repository contains various projects that utilize different research and data science-relevant APIs to improve the efficiency of data science workflows, research coordination, and participant management. By integrating multiple services, it automates and streamlines tasks in ways that significantly enhance project efficiency.

## Key Features:
- **Google Sheets API**: Automates updates to Google Sheets databases based on RedCap data completion, facilitating seamless data synchronization across platforms.
- **RedCap API**: Allows for data analysis directly within RedCap, enabling efficient management of project data and participant information. Includes automated data imports at specific time points to initiate project legs and trigger notifications/alerts within RedCap.
- **Text Service APIs**: Automates participant communication, including sending reminders, project updates, and other important messages.

## Submodules

This repository includes several submodules. Each submodule is an independent repository that utilizes APIS. A directory to submodules is detailed below: 

- **[Age Cohort Check APIs](https://github.com/dzweben/age-cohort-check-apis)**: Uses the **RedCap API** and **Google Sheets API**, along with Python for CSV editing, to check if participants' assigned record IDs match their ages across the project cohorts. It outputs a CSV file showing any incorrectly assigned participants.

- (more submodules will be added soon...
