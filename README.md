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
