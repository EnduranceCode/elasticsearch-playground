# Elasticsearch Masterclass for Java Spring Developers

This [folder](./) contains the code written while taking the course [Elasticsearch Masterclass For Java Spring Developers](https://www.udemy.com/course/elasticsearch-java/)
which is presented by [Vinoth Selvaraj](https://www.vinsguru.com/vinoth-selvaraj/). The official repository with this course code is available in [Github](https://github.com/vinsguru/elasticsearch-course).

## Course content & progress

1. Introduction
    - [x] Before you enroll
2. Elasticsearch setup
    - [x] Humble request & resource
    - [x] Elasticsearch setup using Docker Compose
    - [x] Kibana Dev Tools
3. Elasticsearch core concepts
    - [x] Terminologies
    - [x] Index - Create/Delete
    - [x] CRUD : Adding documents
    - [x] Source metadata fields
    - [x] CRUD : Adding documents with ID
    - [x] CRUD : Querying documents
    - [x] CRUD : Updating documents
    - [x] CRUD : Patch
    - [x] CRUD : Scripted Update
    - [x] CRUD : Delete
    - [x] Inverted index
    - [x] Term dictionary/Term frequency/Document frequency
    - [x] OPTIONAL : Segments
    - [x] OPTIONAL : Refresh API
    - [x] Summary
    - [x] Quiz 1
4. Clustering/Sharding/Replication
    - [x] Elasticsearch Cluster
    - [x] Sharding
    - [x] Routing
    - [x] Replica Shard
    - [x] Index Creation With Shard And Replica
    - [x] Node Roles
    - [x] Three Node Elasticsearch Cluster
    - [x] Master Election
    - [x] High Availability Demo
    - [x] Two Shards Demo
    - [x] Initial Master Demo
    - [x] Node Roles Demo
    - [x] Coordination Only Node
    - [x] Optimistic Concurrency Control
    - [x] Cluster Settings - Persistent / Transient
    - [x] FAQ : How Many Primary Shards Do I Need?
    - [x] FAQ : How To Change Shard Count?
    - [x] FAQ : How Many Replica Shards Do I Need?
    - [x] Summary
    - [x] Quiz 2
5. Bulk API
    - [x] Bulk API introduction
    - [x] Bulk API demo
    - [x] Granular error handling
    - [x] Optimistic concurrency control / Multiple indices
    - [x] File upload
    - [x] Reindex API
    - [x] Summary
6. Analyzer
    - [x] Analyzer introduction
    - [x] Analyzer components
    - [x] Analyzer clarification
    - [x] Character filters
    - [x] Tokenizers
    - [x] Token filters
    - [x] Synonym filter
    - [x] Stop word filter
    - [x] Stemming filter
    - [x] Analyzers
    - [x] Custom Analyzer
    - [x] FAQ : Is Elasticsearch insert slow?
    - [x] FAQ : How Elasticsearch fits in your architecture
    - [x] FAQ : Custom Analyzer in Java
    - [x] Summary
    - [x] Quiz 3
7. Data mapping
    - [x] Data mapping - Introduction
    - [x] Dynamic mapping
    - [x] Explicit mapping
    - [x] FAQ : Can I add new field?
    - [x] FAQ : Can I change existing field type?
    - [x] Field possible values
    - [x] Using custom Analyzer
    - [x] Custom Analyzer clarification
    - [x] Skipping a field
    - [x] 1 to 1 parent/child mapping
    - [x] 1 to many parent/child mapping
    - [x] Summary
    - [x] Quiz 4
8. Full text search
    - [ ] Introduction
    - [ ] Match all
    - [ ] Select by IDs
    - [ ] Term/Terms query
    - [ ] Range query
    - [ ] Prefix/Wildcard/Regexp
    - [ ] Exists query
    - [ ] Relevance
    - [ ] Match query with relevance score - Part 1
    - [ ] Match query with relevance score - Part 2
    - [ ] Fuzziness
    - [ ] Match phrase
    - [ ] Multi match
    - [ ] Highlight
    - [ ] Multi field mapping
    - [ ] Leaf vs Compound queries
    - [ ] Bool query - Part 1
    - [ ] Bool query - Part 2
    - [ ] Bool query - Should clause - Part 1
    - [ ] Bool query - Should clause - Part 2
    - [ ] OPTIONAL : Bool query guidelines
    - [ ] Bool query - Assignment 1
    - [ ] Bool query - Assignment 2
    - [ ] Minimum match for should clause
    - [ ] Personalized results using should clause
    - [ ] Boosting query
    - [ ] Disjunction max query
    - [ ] Query string
    - [ ] Geo spatial query
    - [ ] 1-to-1 parent child query
    - [ ] 1-to-Many parent child query
    - [ ] Inner hits
    - [ ] Date math
    - [ ] Summary
    - [ ] Quiz 5
9. Filed selection/Pagination/Sorting
    - [ ] Field selection
    - [ ] Pagination
    - [ ] Sorting
    - [ ] Array - Sort mode
    - [ ] FAQ : Sorting by ID
10. Aggregation/Facets
    - [ ] Aggregation - Introduction
    - [ ] Metric aggregation
    - [ ] Bucket terms Aggregation - Part 1
    - [ ] Bucket terms Aggregation - Part 2
    - [ ] Range/Histogram aggregation
    - [ ] OPTIONAL : Nested aggregation
    - [ ] Summary
11. Autocomplete/Suggestions
    - [ ] Introduction
    - [ ] Completion suggester - Part 1
    - [ ] Completion suggester - Part 2
    - [ ] Multiple suggestions
    - [ ] OPTIONAL : Search as you type
    - [ ] Best practices
12. Spring Boot/Elasticsearch integration
    - [ ] Project setup - Part 1
    - [ ] Resource: Test Container configuration
    - [ ] Project setup - Part 2
    - [ ] Index operations - Part 1
    - [ ] Index operations - Part 2
    - [ ] CRUD operations
    - [ ] Bulk CRUD operations
    - [ ] Query methods - Part 1
    - [ ] Resource: Test data & mapping
    - [ ] Query methods - Part 2
    - [ ] Query methods - Part 3
    - [ ] Sort
    - [ ] Pagination
    - [ ] Resource: Test data & mapping
    - [ ] Query
    - [ ] Highlight
    - [ ] Resource: Test data & mapping
    - [ ] Test setup for criteria/Native query
    - [ ] Criteria query
    - [ ] Resource: Bool query reference
    - [ ] Native bool query
    - [ ] Resource: Aggregation reference
    - [ ] Aggregations - Part 1
    - [ ] Aggregations - Part 2
    - [ ] Resource: Completion suggestion request
    - [ ] Autocomplete/Suggestions
    - [ ] Summary
13. Final project: Building search engine with 5 million records
    - [ ] Application overview
    - [ ] Resource
    - [ ] Data setup
    - [ ] Data setup clarification
    - [ ] Suggestions - API discussion
    - [ ] Project setup
    - [ ] Suggestions API implementation - Part 1
    - [ ] Suggestions API implementation - Part 2
    - [ ] Suggestions API implementation - Error handling
    - [ ] Suggestions API demo
    - [ ] Search API discussion
    - [ ] Search API - DTOs/Constants
    - [ ] Search API - Building queries
    - [ ] Query rules Clarification
    - [ ] Query rules
    - [ ] Search API - Native query
    - [ ] Search API - Response DTOs
    - [ ] Search API Implementation
    - [ ] Search API Implementation - Error handling
    - [ ] Resource: Test data & mapping
    - [ ] Integration test - Setup
    - [ ] Suggestions API - Integration test - Part 1
    - [ ] Resource: Suggestions API Test Cases
    - [ ] Suggestions API - Integration test - Part 2
    - [ ] Resource: Search API Test Cases
    - [ ] Search API - Integration test
    - [ ] Business search API demo
    - [ ] Resource: Final Demo
    - [ ] Business search UI demo
    - [ ] Business search UI demo - Clarification on pagination
    - [ ] Business search UI demo - Complex search terms
    - [ ] Feedback!?
    - [ ] What about "Good restaurants near me"?
    - [ ] Designing large scale projects
    - [ ] How Elasticsearch fits in your application architecture - End to end
14. Security
    - [ ] Introduction
    - [ ] Resource: Security
    - [ ] SSL/TLS & Credentials
    - [ ] Security with JKS
    - [ ] Resource: Security with Spring Boot
    - [ ] Spring Boot with secured Elasticsearch
    - [ ] OPTIONAL : Cluster security
15. What's next?
    - [ ] What's next?

## Folder Structure

### env1-single-node

The folder [`env1-single-node`](./env1-single-node/) contains the docker environment setup for a single node Elasticsearch cluster. To setup the environment, execute the following commands:

    cd env1-single-node
    docker compose up -d

When the environment is no longer needed, bring it down with the following command:

    cd env1-single-node
    docker compose down

### env2-multiple-node

The folder [`env2-multiple-node`](./env2-multiple-node/) contains the docker environment setup for a multiple node Elasticsearch cluster. To setup the environment, execute the following commands:

    cd env2-multiple-node
    docker compose up -d

When the environment is no longer needed, bring it down with the following command:

    cd env2-multiple-node
    docker compose down

### env3-master-node

The folder [`env3-master-node`](./env3-master-node/) contains the docker environment setup for a multiple node Elasticsearch cluster with a initial master node defined. To setup the environment, execute the following commands:

    cd env3-master-node
    docker compose up -d

When the environment is no longer needed, bring it down with the following command:

    cd env3-master-node
    docker compose down

### env4-node-roles

The folder [`env4-node-roles`](./env4-node-roles/) contains the docker environment setup for a multiple node Elasticsearch cluster with a initial master node and node roles defined. To setup the environment, execute the following commands:

    cd env4-node-roles
    docker compose up -d

When the environment is no longer needed, bring it down with the following command:

    cd env4-node-roles
    docker compose down
