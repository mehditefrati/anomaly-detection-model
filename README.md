# anomaly-detection-model
# OSM Data Processing and Normalization

This project processes and normalizes geographic data from OpenStreetMap (OSM) files. It extracts nodes and routes, performs normalization, and prepares the data for further analysis or machine learning.

## Features

- **OSM Data Parsing**: Extracts nodes (latitude and longitude) and ways (routes) from OSM XML files.
- **Data Normalization**: Normalizes geographic coordinates for machine learning tasks.
- **Sequence Padding**: Prepares routes as padded sequences.

## Requirements

- Python 3.8+
- Required libraries:
  - `xmltodict`
  - `numpy`
  - `tensorflow` (for padding sequences)
   ```

## Usage

1. Place your OSM file in the project directory.
2. Update the file path in the notebook:
   ```python
   osm_file = 'path_to_your_osm_file.osm'
   ```
3. Run the Jupyter notebook to process the data.

## Outputs

- Extracted nodes and routes.
- Normalized and padded route data, ready for further analysis.

## Example

Here is an example output after running the notebook:
```
Extracted 12210 routes and 67696 nodes.
```

## Future Work

- Integrate additional preprocessing steps.
- Train and evaluate machine learning models using the prepared data.
- Provide command-line support for data processing.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- OpenStreetMap contributors for the data.
- TensorFlow for providing robust tools for sequence padding and normalization.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.
