
---

# Motor Vehicle Collisions in Canada - Streamlit Dashboard

This Streamlit dashboard is designed to analyze motor vehicle collisions in Canada using interactive visualizations. The dashboard provides insights into different aspects of motor vehicle collisions, including the number of cases of people injured or died, collisions by time of day, and the top dangerous streets by affected type (pedestrians, cyclists, motorists).

## Getting Started

To run this Streamlit application, follow these steps:

1. Install the required Python libraries by running:
   
   ```
   pip install streamlit pandas numpy pydeck plotly
   ```

2. Clone or download this repository.

3. Place the CSV data file named `data.csv` in the same directory as the script.

4. Open your terminal and navigate to the directory containing the script and the data file.

5. Run the Streamlit application using the following command:

   ```
   streamlit run your_script_name.py
   ```

   Replace `your_script_name.py` with the actual name of your Python script.

6. A new browser tab will open, displaying the Streamlit dashboard.

## Usage

The Streamlit dashboard provides several interactive components that allow you to explore the motor vehicle collision data.

### How many cases of people injured or died?

- Use the slider to specify the minimum number of cases in which people were injured or there was a fatality in vehicle collisions.

### How many collisions happen during a given time of day?

- Use the sidebar slider to choose an hour of the day to analyze.
- The dashboard will display the breakdown of collisions by minute within the selected hour.

### Show Raw Data

- Check this box to display the raw data used in the visualizations.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please feel free to open an issue or submit a pull request.

## Credits

This Streamlit application is based on the Motor Vehicle Collisions dataset from Canadian government.
 
 Collisions_Canada is a project of analyzing the road accident data from Canada using the skills I obtained from the project "Build a Data Science Web App with Streamlit and Python": https://coursera.org/share/f5b8e25417a8e617f2efe220a1bdfcfc
