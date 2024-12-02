<h1>Public Transportation Transaction Transjakarta Analysis</h1>

## 1. Project Overview
Transjakarta management wants to know the corridors and travel times most frequently used by passengers, as well as how they are distributed based on the direction of travel (Go/Back) and passenger demographics such as age and gender. This information will help Transjakarta to:

- Allocate the fleet more effectively on certain corridors and times.
- Improve user experience by customizing services based on passenger needs.
- Plan infrastructure development on the busiest corridors.

Key Objectives:
- Identify corridors with the highest frequency of use.
- Analysis of passenger travel time patterns.
- Profiling the demographics of Transjakarta users.
- Analyze the relationship between tap-in and tap-out data to understand travel patterns.

## 2. Data Sources
- [Dataset 1](https://drive.google.com/drive/folders/1S04hk5uHfHYe6J1S6fVqDunuja1Lk1Lo) - This dataset represents the details of Transjakarta trips in April 2023. There are 37900 rows and 22 columns. Each row represents one transaction.

## 3. Technologies Used
- Programming Language: Python,Pandas
- Visualization: Matplotlib, Seaborn, Plotly
- Interactive Dashboard: Tableau
- Version Control: Git

## 4. Project Structure

```
├── README.md          <- The top-level README for developers using this project.
|
├── data
│   ├── raw            <- Data from third party sources.
│   └── cleaned        <- The data that has been cleaned.
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── reports            <- Generated analysis as PowerPoint, PDF, LaTeX, etc.
|   ├── slide          <- Generated PowerPoint
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
└── src                <- Source code for use in this project.

```

## 5. Summary of Finding
### 5.1 Business Insight
* The Cibubur-Balai Kota and Ciputat-CSW corridors are the routes with the highest trip frequency, with 384 and 376 trips respectively, followed by the Kapuk Muara - Penjaringan flat. To optimize the service, it is recommended to increase the fleet on these corridors, especially during peak hours, as well as periodically evaluate high-volume routes to ensure the fleet capacity is sufficient.

* Peak travel activity occurred at 6am and 5pm, reflecting morning and evening commuting patterns. Bus Passenger was higher on weekdays than weekends, confirming Transjakarta's role as the primary transportation for workers. It is recommended to increase bus frequency at weekday peak times and reduce frequency on low-volume routes at weekends, or promote weekend services to increase usage.

* The distribution of passenger for the Go and Back travel directions is relatively balanced across all corridors, indicating stable demand in both directions. Transjakarta can maintain an equal fleet allocation for go and back trips, and identify volume differences that may arise at certain times to make dynamic adjustments.

* Demographic analysis shows different patterns of Transjakarta usage. Corridors such as Pasar Minggu-Tanah Abang and Ciputat-CSW are more popular with women, while Cibubur-Balai Kota is used more by men. The adult age group dominates all corridors, while the elderly prefer the Kampung Rambutan-Pondok Gede route, and teenagers are more often seen on the Pondok Bambu-Walikota East Jakarta Flat corridor. To improve services, female-friendly facilities in female-dominant corridors, elderly-friendly facilities in corridors with significant senior users, and special programs for teenagers in relevant corridors are suggested.

* Most trips using Transjakarta are for short distances (<5 km), with peaks in the 1-2 km range, while long distance trips (>10 km) are made by a handful of users. This suggests that Transjakarta services are mainly used for local trips. Therefore, service priority should be given to short-distance routes by increasing bus frequency, while promotion of long-distance trips can be done through incentives such as fare discounts.

* Points such as Rusun Kapuk Muara, Garuda Taman Mini, and Cibubur Junction are popular locations for both tap-in and tap-out. Transjakarta could improve facilities at these locations, for example by adding seating, digital information boards, and more comfortable waiting areas. In addition, traffic management at these points needs to be improved to reduce congestion and support travel efficiency.

### 5.2 Actionable Recommendation
* Add bus fleets on popular corridors during peak hours (06:00-09:00 and 16:00-19:00).
* Provide gender- and age-friendly services to improve user convenience.
* Focus on managing and promoting short-distance routes, while encouraging long-distance travel through fare discounts.
* Upgrade infrastructure at popular tap-in and tap-out points to support high travel volumes.

## 6. Contact
- Name: Elia Samuel
- Email: samuelelia0907@gmail.com
- Linkedin: https://www.linkedin.com/in/elia-samuel-992475324/