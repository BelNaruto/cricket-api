# Cricket API

The **Cricket API** provides comprehensive access to cricket match data, player statistics, team information, and more. Ideal for developers, sports analysts, and cricket fans, this API delivers real-time updates and historical data to enhance your cricket-related applications and services. This Free API can be found on [RapidAPI](https://rapidapi.com/belchiorarkad-FqvHs2EDOtP/api/cricket-api18)


## Key Features

- **Live Match Data**: Access real-time updates during cricket matches, including scores, overs, and key events.
- **Player Statistics**: Retrieve detailed statistics for cricket players, including batting and bowling performance.
- **Team Information**: Get information on cricket teams, including player rosters, rankings, and team performance metrics.
- **Match Schedules**: Get information on upcoming matches, including dates, venues, and fixtures.
- **Historical Data**: Access past match results and player statistics for comprehensive analysis.


## Getting Started

1. **Sign Up**: Create an account on RapidAPI.
2. **Subscribe**: Choose a subscription plan that suits your needs.
3. **API Key**: Obtain your unique API key to start making requests.
4. **Documentation**: For detailed usage instructions, visit the [Cricket API Documentation](https://rapidapi.com/belchiorarkad-FqvHs2EDOtP/api/cricket-api18).


### Player Stats
Retrieves statistics for a specific player.

**Query Parameters:**
- `playerId` (Required): The unique identifier for the player.

### Player Matches
Retrieves match history for a specific player.

**Query Parameters:**
- `playerId` (Required): The unique identifier for the player.

### Player Videos
Retrieves videos related to a specific player.

**Query Parameters:**
- `playerId` (Required): The unique identifier for the player.
- `page` (Optional): The page number of results.
- `perPage` (Optional): The number of results per page.

### Player News
Retrieves news related to a specific player.

**Query Parameters:**
- `playerId` (Required): The unique identifier for the player.
- `page` (Optional): The page number of results.

### Player Images
Retrieves images related to a specific player.

**Query Parameters:**
- `playerId` (Required): The unique identifier for the player.
- `page` (Optional): The page number of results.
- `perPage` (Optional): The number of results per page.

### Match Live Scores
Retrieves live scores for ongoing cricket matches.

### Match Schedules/Fixtures
Retrieves match schedules or fixtures for a specific date.

**Query Parameters:**
- `date` (Optional): The date in DD-MM-YYYY format.

### Match Results
Retrieves match results for a specific date.

**Query Parameters:**
- `date` (Optional): The date in DD-MM-YYYY format.

### Match Trending
Retrieves trending matches.

### Match Current
Retrieves information on the current match.

### Get Teams
Retrieves a list of all teams.

### Team Details
Retrieves details for a specific team.

**Query Parameters:**
- `teamId` (Required): The unique identifier for the team.

### Team Fixtures/Schedules
Retrieves fixtures or schedules for a specific team and month.

**Query Parameters:**
- `teamId` (Required): The unique identifier for the team.
- `yearMonth` (Required): The year and month in YYYYMM format.

### Team Videos
Retrieves videos related to a specific team.

**Query Parameters:**
- `teamId` (Required): The unique identifier for the team.
- `page` (Optional): The page number of results.
- `perPage` (Optional): The number of results per page.

### Team Squads
Retrieves squad information for a specific team.

**Query Parameters:**
- `teamId` (Required): The unique identifier for the team.

### Team Images
Retrieves images related to a specific team.

**Query Parameters:**
- `teamId` (Required): The unique identifier for the team.
- `page` (Optional): The page number of results.
- `perPage` (Optional): The number of results per page.

### Team Fan Ratings
Retrieves fan ratings for a specific team.

**Query Parameters:**
- `teamId` (Required): The unique identifier for the team.

### Team Gallery
Retrieves gallery images for a specific team.

**Query Parameters:**
- `teamId` (Required): The unique identifier for the team.
- `page` (Optional): The page number of results.
- `perPage` (Optional): The number of results per page.

### News
Retrieves news articles.

**Query Parameters:**
- `page` (Optional): The page number of results.

### Features
Retrieves featured content.

**Query Parameters:**
- `page` (Optional): The page number of results.

### Current Videos
Retrieves the latest videos.

### Get All Videos
Retrieves all videos without filtering by team.

**Query Parameters:**
- `page` (Optional): The page number of results.
- `perPage` (Optional): The number of results per page.


## Commonly Asked Questions

### 1. What kind of data can I access through the Cricket API?
You can access live match data, player statistics, team information, match schedules, and historical data.

### 2. How do I authenticate my API requests?
You must include your API key in the headers of your requests as specified in the API documentation.

### 3. Are there usage limits for the API?
Yes, usage limits vary based on the subscription plan you choose. Check the RapidAPI dashboard for details.

### 4. Can I filter data by specific matches, teams, or players?
Yes, the API allows filtering to retrieve data for specific matches, teams, or players.

### 5. Is historical data available for past matches?
Yes, the Cricket API includes historical data for past matches, allowing for detailed analysis and comparisons.

For more information and to start using the Cricket API, visit [Cricket API on RapidAPI](https://rapidapi.com/belchiorarkad-FqvHs2EDOtP/api/cricket-api18).
