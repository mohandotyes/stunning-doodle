# stunning-doodle
In this project am trying to build out-of-core analytics command-line application and gradually improve it to build web-based application. 

Goals

1. Convert CSV file to Parquet file(https://findingcoefficients.blogspot.com/2021/03/convert-csv-file-parquet-file.html)
2. Use Umap for memory mapping at userspace.
3. Use thrust vector_host for in-memory data structue.
4. Use thrust parallel algorithms to do analytics.

Development Stack

1. Apache arrow c++(https://github.com/apache/arrow).
2. Apache parquet-cpp(https://github.com/apache/parquet-cpp).
3. LLNL/umap(https://github.com/LLNL/umap).
4. NVIDIA/thrust(https://github.com/NVIDIA/thrust).
