## Force Plate Data Analysis

This project processes AMTI force plate data, calculates Center of Pressure (CoP) characteristics, and generates various charts and databases. The data is processed from raw .txt files and results are saved in .xls format, with outputs provided on three worksheets.

### Features
<ul>
    <li><b>Center of Pressure (CoP) calculation</b> from AMTI force plate data.</li>
    <li><b>Chart generation</b> for CoP movement and other metrics.</li>
    <li><b>Data export</b> to <b>Excel</b> with results on multiple worksheets.</li>
</ul>
    
    


### Project Structure

<ul>
    <li>
        <code>environment.yml</code>: Conda environment configuration.
    </li>
     <li>
        <code>Charts</code>: Output folder for visualizations.
    </li>
     <li>
        <code>Data</code>: Directory containing input <code>.txt</code> files from AMTI force plate. Its divided into two experiments, COP_Data consisting of 3 subject groups measurements, and LOS experiment. 
    </li>
     <li>
        <code>Database</code>: Output directory for databases generated.
    </li>
      <li>
        <code>01_COP_Data_Analysis.ipynb</code>: Python worksheet for processing force plate data.
    </li>
      <li>
        <code>02_Data Analysis and Visualization.ipynb</code>: Python worksheet for data analysis and visualisation.
    </li>
      <li>
        <code>03_LOS project.ipynb</code>: Python worksheet for data analysis and visualisation for limits of stability test.
    </li>
   
</ul>

### Prerequisites

Before running this project, make sure you have <b>Miniconda</b> installed and follow these steps to set up the environment.

#### Setting Up the Environment

<ol>
    <li>Clone this repository, create the Conda environment and use the provided environment.yml to install the required dependencies.</br>
    <code>conda env create -f environment.yml</code>
    </li>
    <li>Activate the environment:</br>
        <code>conda activate forcePlate</code>
    </li>
</ol>

### Running the Analysis
After setting the up the environment, you're should be ready to run all analyses. You don't need to follow the order of worksheets by their numbers. They are meant to work independently. Before first usage, scroll through the file and change '/' to '\\' in locations marked by comments if you're using a Windows operating system. Other than this, it should work!


