# VatiDeck-serverless

## Overview

VatiDeck-serverless is a Go-based serverless architecture designed for the VatiDeck game. It utilizes AWS services such as API Gateway and Lambda to handle matchmaking, game state updates, and user actions in a scalable and cost-effective manner.

> [!NOTE]  
> Under development

## Usage

### Prerequisites

- ![Go version](https://img.shields.io/badge/Go-1.23-blue) **Go** 1.23
- ![Terraform version](https://img.shields.io/badge/Terraform-v1.10.4-purple) **Terraform** 1.10.4 or latest 

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/Atrolide/VatiDeck-serverless.git
   cd VatiDeck-serverless
   ```

2. Install dependencies:
   ```sh
   go mod download
   ```

3. Initialize the Terraform state:
    ```sh
    cd infrastructure
    terraform init
    ```
4. Apply the conifguration:
    ```sh
    terraform apply
    ```