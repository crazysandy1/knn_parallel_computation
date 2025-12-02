KNN Parallel Computation

A high-performance implementation of the k-Nearest Neighbors (KNN) algorithm using parallel computation to significantly reduce execution time for large datasets.
This project demonstrates how parallelism (CPU multithreading / multiprocessing) can accelerate distance calculations and classification tasks in KNN.

✨ Features

⚡ Parallelized distance computation using multiprocessing / threading

📊 Supports classification & regression

🧮 Efficient handling of large datasets

🔁 Customizable k value, distance metric, and worker count

🏎 Measurable speedup over sequential KNN

📈 Benchmark Example
Dataset Size	Sequential	Parallel (4 cores)	Speedup
10k samples	3.2s	1.1s	2.9×
50k samples	18.4s	5.7s	3.2×
