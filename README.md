# HadoopCsvToHbase
Otto-von-Guericke-University Magdeburg BigData Lesson Task3

## task description
Write a MR program (only Mapper, no Reducer!) that imports the file Locations.csv into an HBase table. You should create the HBase table before using hbase shell. The rowkey shall be composed of the first and the second element per file row (e.g., „DE_BEELITZ_14547_BALKAN_2520714254817579423“). Columns in Locations.csv are separated from each other using commas. Every other column shall be written to the same HBase row but into a different column.
