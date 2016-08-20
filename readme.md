# OrbWeaver

A theoretical tool for viewing hidden connections between domains

## Tech

 + Neo4J Graph Database
 + Swagger API Spec
 + Node.js with Express 4.0
 + D3.js on a bootstrap based frontend
 + Docker using docker-compose for multi-container orchestration

## Docs

Development documentation [available here](https://github.com/dark12222000/orbweaver/blob/master/docs/index.md).

### Getting Started

```
docker-compose up
```

Open your favorite browser to your machine's port 80 when ready.

### Basic Usage

Enter a domain name (by default the script generates several thousand random ones) and click search or hit enter to see it's connected domains. By default it'll show you domains a single hop away, though you can increase the depth. *With the default data set, the list grows VERY quickly.*
