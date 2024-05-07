<p align="center"><img src="https://www.notadd.com/src/micrograte_logo.svg" alt="MicroGrate Logo"></p>

# Overview

MicroGrate is a microservice development architecture based on the MicroGrate framework. It allows you to build tailored microservices systems using the right modules and add-ons for various business needs. MicroGrate provides a standardized public service layer, with each module offering a gRPC interface for seamless integration with the main program.

# Features

- **[Microservice]** Supports standalone deployment and microservices.
- **[High Performance]** Asynchronous, high-performance applications capable of handling tens of thousands of concurrent requests.
- **[Ease of Maintenance]** Developed with TypeScript for intelligent code hints and compile-time checking.
- **[Modular]** Modular development system for selecting appropriate modules based on business requirements.

## Technology Stack

- TypeScript
- MicroGrate
- GraphQL
- TypeORM
- gRPC
- Redis

# Quick Start

1. Clone the Rpc sample service locally from [mg-rpc-demo](https://github.com/notadd/mg-rpc-demo).
2. Clone the user service locally from [mg-module-user](https://github.com/notadd/mg-module-user).
3. Follow the instructions in `mg-rpc-demo` and `mg-module-user` to start the microservice.
4. Clone this project locally.
5. Install dependencies with `yarn install`.
6. Start with `yarn start`.
7. Open a browser and go to `localhost:5000/graphql` to test GraphQL API.
