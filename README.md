# Gas Sensors Measurements Dataset
This dataset contains measurements from gas sensors. The data includes readings from various gas sensors (MQ2, MQ3, MQ5, MQ6, MQ7, MQ8, MQ135) along with a serial number and the type of gas detected.

## Dataset Information

- **File Name:** Gas_Sensors_Measurements.csv
- **Columns:**
  - Serial Number: Unique identifier for each measurement
  - MQ2, MQ3, MQ5, MQ6, MQ7, MQ8, MQ135: Sensor readings for different gas types
  - Gas: Type of gas detected (e.g., NoGas, Smoke, Perfume, Mixture)


Here is a visualization of the sensor readings for different gas types from the Gas Sensors Measurements dataset:![sensor reading](https://github.com/TakMashhido/Gas-Sensors-Measurements-Dataset/assets/48276165/ea64ff95-9d79-4cbf-a598-6a4b7a773683)

The plot shows the sensor readings (y-axis) for each gas sensor type (MQ2, MQ3, MQ5, MQ6, MQ7, MQ8, MQ135) over the serial numbers (x-axis). Each line represents a different gas sensor type.


## Correlation Matrix

The correlation matrix shows the relationships between sensor readings for different gas types. It helps in understanding the strength and direction of correlations between the sensors.![cor_heatmap](https://github.com/TakMashhido/Gas-Sensors-Measurements-Dataset/assets/48276165/806dce05-8133-4185-9cb2-a43b6cfefd38)

The values in the matrix range from -1 to 1, where:

  - Values close to 1 indicate a strong positive correlation.
  - Values close to -1 indicate a strong negative correlation.
  - Values close to 0 indicate no correlation.
You can analyze the correlation values to see if there are any significant relationships between the sensor readings and the type of gas detected.

## Histograms of Sensor Readings

The histograms visually represent the distribution of sensor readings for each gas type. They offer insights into the range and frequency of sensor readings.
![hist](https://github.com/TakMashhido/Gas-Sensors-Measurements-Dataset/assets/48276165/a91af28a-35e5-4daf-8d6f-49dab2ee9e51)


## License
This dataset is provided under the [MIT License](https://github.com/TakMashhido/Gas-Sensors-Measurements-Dataset/blob/main/LICENSE). Feel free to use and modify the dataset for your projects and research.

## Acknowledgements
This dataset was collected and made available for public use. If you use this dataset in your research or projects, please consider citing the source.
