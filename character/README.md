# GraphQuest: Exploring and Implementing GraphQL

## Objective

This project involves writing GraphQL queries to fetch specific characters' details from the [Rick and Morty GraphQL API](https://rickandmortyapi.com/graphql). Each query retrieves the following fields for a character by their ID: `id`, `name`, `status`, `species`, `type`, and `gender`.

## Files

### Queries
- **character-id-1.graphql**: GraphQL query for character ID 1.
- **character-id-2.graphql**: GraphQL query for character ID 2.
- **character-id-3.graphql**: GraphQL query for character ID 3.
- **character-id-4.graphql**: GraphQL query for character ID 4.

### Outputs
- **character-id-1-output.json**: Response for character ID 1.
- **character-id-2-output.json**: Response for character ID 2.
- **character-id-3-output.json**: Response for character ID 3.
- **character-id-4-output.json**: Response for character ID 4.

## Instructions

1. Execute each `.graphql` file using a GraphQL client (e.g., Postman, Insomnia, or Apollo Explorer) to fetch character details.
2. Save the API responses in the respective `.json` files.

## Example Query

```graphql
query GetCharacterByID {
  character(id: 1) {
    id
    name
    status
    species
    type
    gender
  }
}

## Task 2: Paginated Character List

### Objective

This project focuses on fetching a paginated list of characters from the [Rick and Morty GraphQL API](https://rickandmortyapi.com/graphql). Each query retrieves character details for a specific page, including the following fields: `id`, `name`, `status`, and `image`.

## Files

### Queries
- **characters-page-1.graphql**: GraphQL query for characters on page 1.
- **characters-page-2.graphql**: GraphQL query for characters on page 2.
- **characters-page-3.graphql**: GraphQL query for characters on page 3.
- **characters-page-4.graphql**: GraphQL query for characters on page 4.

### Outputs
- **characters-page-1-output.json**: Response for characters on page 1.
- **characters-page-2-output.json**: Response for characters on page 2.
- **characters-page-3-output.json**: Response for characters on page 3.
- **characters-page-4-output.json**: Response for characters on page 4.

## Instructions

1. Execute each `.graphql` file using a GraphQL client (e.g., Postman, Insomnia, or Apollo Explorer) to fetch character details.
2. Save the API responses in the respective `.json` files.

## Example Query

```graphql
query GetCharactersByPage {
  characters(page: 1) {
    results {
      id
      name
      status
      image
    }
  }
}
