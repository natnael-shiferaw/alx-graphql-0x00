# GraphQuest: Fetching Specific Episodes by ID

## Objective

This project demonstrates how to fetch specific episode details using the [Rick and Morty GraphQL API](https://rickandmortyapi.com/graphql). Each query retrieves episode details for a specific ID, including the following fields: `id`, `name`, `air_date`, and `episode`.

## Files

### Queries
- **episode-id-1.graphql**: GraphQL query for episode with ID 1.
- **episode-id-2.graphql**: GraphQL query for episode with ID 2.
- **episode-id-3.graphql**: GraphQL query for episode with ID 3.
- **episode-id-4.graphql**: GraphQL query for episode with ID 4.

### Outputs
- **episode-id-1-output.json**: Response for episode with ID 1.
- **episode-id-2-output.json**: Response for episode with ID 2.
- **episode-id-3-output.json**: Response for episode with ID 3.
- **episode-id-4-output.json**: Response for episode with ID 4.

## Instructions

1. Use a GraphQL client (e.g., Postman, Insomnia, or Apollo Explorer) to execute each `.graphql` query file.
2. Save the API responses into their respective `.json` files.

## Example Query

```graphql
query GetEpisodeById {
  episode(id: 1) {
    id
    name
    air_date
    episode
  }
}
