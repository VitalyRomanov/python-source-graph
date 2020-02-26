All files in the repository are compressed `csv` files, reaadble by `pandas.read_csv`

- `00_sourcetrail_export` files exported directly from sourcetrail database
- `01_python_edges_disambiguation` contains disambiguation of edges. Some edges in python are ambiguous. The ids for all ambiguaos edges are stored in `00_sourcetrail_export/element_component.csv.bz2`
- `02_largest_component` stores the largest component as calculated by `graphframe`'s WCC functions.
- `03_variables_on_functions` stores edges that signify that a variable with id listed in `03_variables_on_functions/variable_name_ids.csv.bz2` is used in the body of the current function
- `04_api_sequence_calls` stores the sequences of API calls inside some functions. 
- `05_function_bodies` stores function bodies as extracted from sources

