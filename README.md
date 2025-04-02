# .NET Web API Core using AKKA.Net

This repository contains a .NET application developed using Web API Core, featuring two services: **Order Service** and **Payment Service**. These services communicate with each other using **Akka.NET** for both asynchronous and synchronous operations, providing messages in response without utilizing a database.

## Features
- **Order Service**: Handles order-related operations and provides appropriate responses.
- **Payment Service**: Manages payment operations and responds with relevant messages.
- **Communication**: Implements asynchronous and synchronous communication using **Akka.NET**.

## Tech Stack
- **.NET Core**: Framework for building scalable and high-performance APIs.
- **Web API Core**: Enables the creation of RESTful APIs.
- **Akka.NET**: Provides an actor-based model for distributed communication.

## Getting Started

### Prerequisites
- Install [.NET SDK](https://dotnet.microsoft.com/download).
- Install package AKKA
- Install package Akka.Remote

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
