0% Hunger & Waste-Free India — Smart Community Dashboard
Overview

The 0% Hunger Community Dashboard is a data-driven visualization and financial simulation tool that demonstrates how urban waste can be transformed into valuable resources while supporting large-scale social welfare programs. It models a sustainable ecosystem where waste recycling funds food, shelter, and employment for underprivileged citizens.

This project is built using HTML, CSS, JavaScript, Chart.js, and GSAP for animation. It operates fully on the client side.

Objectives

Eliminate hunger by providing food and shelter to homeless and jobless individuals.

Create employment through organized waste collection and recycling.

Establish a circular economy model that converts city waste into usable resources.

Enable transparent monitoring of social and environmental impact through a live dashboard.

Features
City Simulation

Interactive visualization showing shelters, buses, and recycling factories.

Animated workflow of waste collection, transport, and resource recovery.

Real-time counters displaying people fed, buses active, and waste processed.

Resource Recovery Calculator

Calculates recoverable resources from municipal solid waste (MSW):

Compost, Paper, Plastic, Glass, Metal, RDF (Refuse Derived Fuel).

Includes realistic assumptions and yield rates based on industry averages.

Supports multiple scales: small town, medium city, large metro.

Financial and ROI Calculator

Input fields for market prices, operational costs, and shelter capacities.

Computes daily, monthly, and annual revenues and costs.

Displays net profit, payback period, and return on investment (ROI).

Optional CSV export for financial data.

Data Visualization

Integrated Chart.js bar charts for material recovery visualization.

GSAP-based animated flow from city to factory and back.

Clean and responsive layout suitable for presentations.

Tech Stack

Frontend: HTML5, CSS3, JavaScript (Vanilla)

Libraries: GSAP, Chart.js

Visualization: SVG-based map simulation and animated transitions

Data Export: CSV (client-side)

How to Use

Open index.html in any modern browser (Chrome, Edge, Firefox).

Set the daily waste quantity or choose a preset (50 / 500 / 5000 tonnes per day).

Click Apply to compute material outputs.

Enter market prices and cost parameters, then click Calculate to view ROI results.

Use the Export button to download daily output data.

Data Assumptions
Material	Share of MSW	Recovery Rate	Output per tonne (kg)
Organic	50%	35% compost yield	175
Paper	12%	80%	96
Plastic	8%	70%	56
Glass	4%	80%	32
Metal	3%	90%	27
RDF	~15%	-	150

Approx. 53–55% of total mixed waste mass becomes usable product.

Project Goals

Support government and NGO initiatives in urban waste management.

Demonstrate a scalable model for self-sustained community development.

Provide transparent, real-time monitoring of waste-to-resource conversion and social impact.

Future Enhancements

Integration with live city waste data sources (e.g., Swachh Bharat dashboards).

Geolocated shelters and bus routes using Leaflet.js.

Revenue prediction based on commodity price APIs.

User authentication and local data storage.

Export to PDF and data visualization reports.

License

This project is open source and distributed under the MIT License.
