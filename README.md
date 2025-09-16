# Budget Tracker

A desktop application for budget tracking. Allows you to record spending by price and category. The amount of spending by category is conveniently displayed in a graph in the Graph menu.



## Technologies

**Tech Stack:**

- Python
- Pandas
- Plotly
- SQLite3
- tkinter
- ttkbootstrap

## Features

- Add records to the table (data is stored in a SQLite3 database)
- View all records
- Search for records by Title / Price / Category
- Delete one record or all records at once
- In the Graph menu you can see the amount of your expenses by category as a graph (implemented with Pandas and Plotly)
- Shows the error window when leaving blank fields, incorrect text length, etc.

## Run it locally (written for Windows)
1) Create a directory and clone the repo in it:
```sh
   git clone https://github.com/yash66699/-Personal-Budget-Tracker.git
   ```
2) Create your virtual environment:
```
python -m venv env
```
3) Activate your virtual environment:
```
env\Scripts\activate
```
4) Install the requirements.txt:
```
pip install -r requirements.txt
```

