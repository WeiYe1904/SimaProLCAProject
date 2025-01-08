# SimaPro LCA Project

A data collection GUI for processing manual inputs and populating missing fields with validated baseline data. This tool outputs a SimaPro-compatible CSV file that can be imported into SimaPro for life cycle assessment. It is designed specifically for sand casting iron production.

> **Note:** This project requires the purchase of [SimaPro 9.6.0.1](https://simapro.com/).

---

## How to Use

1. Place the `input.csv` file in your project directory.  
2. Run the code to launch the GUI.  
3. Update the data in the GUI as needed.  
4. Click the **Save Data** button.  
5. The program will generate a SimaPro-compatible CSV file named `updated_simapro_file.CSV`.  

---

## How to Import into SimaPro

1. Open SimaPro and the project you want to import data into.  
2. Click **File** → **Import**.  
3. Select **SimaPro CSV** as the file format.  
4. Click **Add** and browse to the `updated_simapro_file.CSV` file.  
5. Click **Open**.  
6. Select the option: **Try to link imported objects to other imported objects first**.  
7. Set the **CSV format separator** to **Semicolon**.  
8. Click **OK** to view the Import overview.  
