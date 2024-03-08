# Vector Database Module
This module provides an efficient and scalable vector database for storing and retrieving high-dimensional vector data. It supports fast similarity search and nearest neighbor queries, making it suitable for various scenarios such as recommendation systems, image retrieval, natural language processing, and more.
Features
Support for inserting, deleting, and updating vector data
Efficient similarity search and nearest neighbor queries
Highly scalable, supporting massive data storage and retrieval
Multiple indexing algorithms, including Faiss, Annoy, HNSW, etc.
Python API and command-line tools for easy integration and usage
Comprehensive documentation and examples for quick start
## qdrant
### install
```
apt install build-essential libclang-dev protobuf-compiler
```
```
cd qdrant
cargo build --release --bin qdrant
```
### run 
```
./target/release/qdrant
```