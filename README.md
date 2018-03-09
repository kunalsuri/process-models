# process-models
A repository for process models created for experimentation purposes.
The models can be downloaded and visualized using any BPMN 2.0 compatible process editor or simulation engine.

**Process Model Metrics**

*Naming: IoT_ProcessVariant_XX => iPVXX*

| Metrics                           | iPV01  | iPV02 | iPV03  | iPV04  |
|-----------------------------------|--------|-------|--------|--------|
| start_events                      | 1      | 1     | 1      | 1      |
| internal_events                   | 0      | 0     | 0      | 0      |
| end_events                        | 1      | 1     | 1      | 1      |
| events                            | 2      | 2     | 2      | 2      |
| functions                         | 6      | 8     | 9      | 7      |
| and_splits                        | 1      | 3     | 3      | 2      |
| and_joins                         | 1      | 3     | 3      | 2      |
| xor_splits                        | 1      | 1     | 1      | 1      |
| xor_joins                         | 1      | 1     | 1      | 1      |
| or_splits                         | 0      | 0     | 0      | 0      |
| or_joins                          | 0      | 0     | 0      | 0      |
| connectors                        | 4      | 8     | 8      | 6      |
| nodes                             | 12     | 18    | 19     | 15     |
| arcs                              | 13     | 21    | 23     | 17     |
| control_flow_complexity           | 3      | 5     | 5      | 4      |
| join_complexity                   | 3      | 5     | 5      | 4      |
| density_1                         | 0,098  | 0,069 | 0,067  | 0,081  |
| coefficient_of_connectivity       | 1,083  | 1,167 | 1,211  | 1,133  |
| coefficient_of_network_complexity | 14,083 | 24,5  | 27,842 | 19,267 |
| separability                      | 0,4    | 0,313 | 0,294  | 0,385  |
| sequentiality                     | 0,231  | 0,048 | 0,043  | 0,059  |
| cyclomatic_number                 | 2      | 4     | 5      | 3      |
| avg_connector_degree              | 3      | 3     | 3,25   | 3      |
| max_connector_degree              | 3      | 3     | 4      | 3      |
| depth                             | 2      | 3     | 3      | 2      |
| mismatch                          | 0      | 0     | 0      | 0      |
| heterogeneity                     | 0,631  | 0,512 | 0,512  | 0,579  |
| token_splits                      | 1      | 3     | 4      | 2      |
