# Data Quality Library

This repository contains a data quality library designed to be used within Jupyter notebooks or Databricks environments. The library provides tools for generating reports about data quality.

## Installation

To install the data quality library, follow these steps:

1. Import the `_dq-library.ipynb` notebook into your Databricks workspace.
2. Run the notebook to make the library functions available in your environment.


## Usage

To utilize the library, execute the `_dq-library.ipynb` notebook in your Databricks workspace:

```bash
%run "/path/to/_dq-library"
```

Replace `"/path/to/_dq-library"` with the actual path to the `_dq-library.ipynb` notebook.

### Example Usage

Here is a basic example of how to use a function from the library after loading it:

```python
df_processed, dq_summary = calculate_data_quality(dataframe, config_json)
```

Substitute `validate_data` with the actual function you wish to use, and `dataframe` with your data frame object.

a complete example can be found under Main.ipynb

## Functions

Below are the functions provided by the data quality library. .

- `calculate_data_quality(df_policies, config_json)`: Use dataframe to be assessed, and DQ business rules [[to be further documented]] config as input and generate 2 dataframes df_processed, dq_summary.
- `df_processed`: Include additional columns logging the DQ result
- `dq_summary`: Include DQ KPIs for each field


## Configuration

No dependencies install requirement

## Testing

To test the functions of the library, follow these steps:

1. Navigate to the test notebook or scripts.
2. Execute the tests and review the results.

If there are specific commands or scripts to run the tests, provide them here.

## Contributing

Contributions to the library are welcome! Here's how you can contribute:

1. Fork the repository.
2. Create a new branch for your feature (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -am 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Create a new Pull Request.

## License

This library is licensed under the [License Name]. See the LICENSE file for details.

## Contact

For questions or feedback regarding this library, please reach out to the maintainers.

- Name: Mahmal Sami & xxx
- Email: [mahmalsami@gmail.com]