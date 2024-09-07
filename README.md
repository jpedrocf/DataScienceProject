# DataScienceProject

# Manchester City's Dominance in the Premier League

Over the past five seasons, Manchester City has established itself as the dominant force in English football, winning four Premier League titles out of five. Under the guidance of manager Pep Guardiola, the team has consistently demonstrated tactical brilliance, a deep squad, and an unwavering level of consistency.

City's ability to maintain high performance levels throughout the long and challenging Premier League campaigns has been unmatched by their rivals. Key players like Éderson, Kevin De Bruyne, Bernardo Silva and Erling Haaland have been instrumental in turning matches in City’s favor, while the club's depth has allowed them to rotate players effectively, keeping the squad fresh.

Manchester City's dominance has not only been measured in terms of titles but also in points accumulation, goal difference, and defensive records. The club has set multiple records during this period, showcasing a level of football that has raised the bar for what is required to win the Premier League.

Despite stiff competition from traditional powerhouses like Liverpool, Chelsea, and Manchester United, City’s consistency and adaptability have allowed them to maintain their supremacy. Winning four Premier League titles in the last five seasons speaks volumes about their ongoing dominance, positioning Manchester City as one of the most successful English clubs in recent history.


# Data Catalog

| Column Name | Type | Description                                               |
|-------------|------|-----------------------------------------------------------|
| **team**    | str  | The name of the team being analyzed                       |
| **date**    | date | The date on which the match took place (YYYY-MM-DD format)                                     |
| **time**    | str  | The start time of the match                                    |
| **comp**    | str  | The competition in which the match was played                              |
| **round**   | str  | the round of the competition                                     |
| **day**     | str  | The day of the week when the match was held (e.g., Sun, Mon, Sat)                          |
| **venue**   | str  | The venue of the match, indicating whether the team played at home or away                      |
| **result**  | str  | The result of the match from the team's perspective: Win (W), Draw (D), or Loss (L)   |
| **gf**      | int  | The number of goals scored by the team in the match                      |
| **ga**      | int  | The number of goals conceded by the team (i.e., goals scored by the opponent)                               |
| **opponent**| str  | The name of the opposing team in the match                        |
| **xg**      | float| The expected goals (xG) for the team based on the quality of chances created                |
| **xga**     | float| The expected goals against (xGA) based on the quality of chances the opponent created                       |
| **poss**    | int  | The percentage of ball possession the team had during the match                      |
| **captain** | str  | The name of the team's captain during the match                         |
| **formation**| str | The formation used by the team during the match (e.g., 4-4-2, 3-5-2)                       |
| **referee** | str  | The name of the referee who officiated the match                                   |
| **sh**      | int  | The total number of shots taken by the team during the match                           |
| **sot**     | int  | The total number of shots on target taken by the team during the match                 |
| **dist**    | float| The average distance (in meters) from which the team's shots were taken   |
| **fk**      | int  | The number of free kicks awarded to the team                      |
| **pk**      | int  | The number of penalty kicks awarded to the team                   |
| **pkatt**   | int  | The number of penalty kick attempts made by the team         |
| **season**  | int  | The season year in which the match occurred (e.g., 2020, 2021)                              |



