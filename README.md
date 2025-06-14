# Netflix Titles Analysis with Neo4j

This project explores the **Netflix Titles Dataset** using **Neo4j**, a graph database platform. It models relationships between titles, directors, actors, genres, and countries.

## 📁 Files Included
- `netflix_titles.csv` - Raw dataset used
- `ScalableDatabaseFinalProject.txt` - Cypher queries for creating nodes and relationships
- `ScalableDatabaseFinalProject.pdf` - Project overview and results
- `README.md` - Project documentation

## 🧠 Problem Statement
Analyze Netflix content to uncover patterns by modeling entities and their relationships.

## 🔗 Why Graph DB?
Graph databases like Neo4j are ideal for modeling complex relationships such as:
- `ACTED_IN`, `DIRECTED_BY`, `AVAILABLE_IN`, etc.

## 📊 Technologies Used
- Neo4j Desktop
- Cypher Query Language
- Python (optional for CSV preprocessing)

## 🚀 Usage
1. Import `netflix_titles.csv` into Neo4j
2. Run `graph_modeling.cypher` to create the schema
3. Use Neo4j Browser to query and visualize the graph
