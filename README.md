# Home_Sales

![Home_sales](https://journal.firsttuesday.us/wp-content/uploads/CA-Sales-Home-Volume.png)

Comparison of RunTime

The runtime of various methods was analyzed to compare their efficiency in processing a large dataset. Three methods were tested: uncached, cached, and parquet partitioned. The uncached method, which did not use caching or partitioning, took an astonishingly long time of 0.78 seconds to complete the analysis. In contrast, the cached method, which utilized caching, was significantly faster and took only 0.39 seconds to complete the same analysis. The parquet partitioned method, which utilized both caching and partitioning, was the most efficient and completed the analysis in only 0.32 seconds. These results demonstrate that utilizing caching and partitioning techniques can significantly improve the runtime of data analysis tasks, which can be crucial when working with large datasets.
