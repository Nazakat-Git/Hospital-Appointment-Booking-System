[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/M5rgUwZx)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=19673663)
# Data Visualization Dashboard

Template repository for project work in Fundamentals of Programming.

This is a simple Flask web application that demonstrates data visualization using Plotly. The project includes three types of charts: Bar Chart, Pie Chart, and Line Chart.

## Running the Application

1. Clone the repository:

```bash
git clone https://github.com/unberath/Template_Flask.git
cd Template_Flask
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the application:

```bash
python app.py
```

Visit [http://localhost:8000/](http://localhost:8000/) in your browser to view the data visualization dashboard.
Visit [http://localhost:8000/test](http://localhost:8000/test) for simple user input.

## Project Structure

- `app.py`: Flask application with sample data and chart creation.
- `templates`: Folder for all HTML templates.
	- `dashboard.html`: HTML template for rendering the charts.
	- `my_form.html`: HTML template for basic user input.
- `data`: Folder for csv or json data.
- `resources`: Folder for additional documents like the presentation.


## Charts

- **Bar Chart:** Demonstrates a simple bar chart using Plotly Express.
- **Pie Chart:** Shows a basic pie chart using Plotly.
- **Line Chart:** Displays a line chart with markers using Plotly Subplots.

Feel free to modify the `data` dictionary in `app.py` to use your own dataset.
