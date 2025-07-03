# Fabric-Py-Spark-DAG

A repository for PySpark notebooks and utilities, designed to facilitate data engineering workflows, ETL processes, and DAG (Directed Acyclic Graph) orchestration on Apache Spark. This project is intended to be used with Python and PySpark, and may be run locally or on distributed cloud environments.

## Features

- Example PySpark notebooks for data analysis and transformation
- Modular code structure for reusable ETL components
- Utilities for managing DAGs, scheduling, and orchestration
- Support for local development and cloud execution

## Getting Started

### Prerequisites

- Python 3.7 or newer
- [Apache Spark](https://spark.apache.org/) 3.x
- [PySpark](https://pypi.org/project/pyspark/)
- (Optional) [Jupyter Notebook](https://jupyter.org/) or [Databricks](https://databricks.com/)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/malomaye/Fabric-Py-Spark-DAG.git
   cd Fabric-Py-Spark-DAG
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

   Or, if not using a requirements.txt, manually install:
   ```bash
   pip install pyspark jupyter
   ```

3. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```
   Open the notebooks under the `notebooks/` directory.

## Usage

- Browse example notebooks in the `notebooks/` directory.
- Update configuration and paths as required for your environment.
- Extend or modify notebooks to suit your data pipeline needs.

## Project Structure

```
Fabric-Py-Spark-DAG/
├── notebooks/         # Jupyter notebooks with PySpark examples
├── src/               # Python modules/utilities for DAG and ETL
├── data/              # Sample datasets (if any)
├── tests/             # Unit and integration tests
├── requirements.txt   # Python dependencies
└── README.md
```

## Contributing

Contributions are welcome! Please open issues and submit pull requests for new features, bug fixes, and suggestions.

## License

This project is licensed under the MIT License.

## Contact

For questions or support, please open an issue in the repository.
