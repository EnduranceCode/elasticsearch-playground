# Elasticsearch Masterclass For Java Spring Developers

This [folder](./) contains the code written while taking the course [Elasticsearch Masterclass For Java Spring Developers](https://www.udemy.com/course/elasticsearch-java/)
which is presented by [Vinoth Selvaraj](https://www.vinsguru.com/vinoth-selvaraj/). The official repository with this course code is available in [Github](https://github.com/vinsguru/elasticsearch-course).

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
