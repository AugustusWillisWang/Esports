
```mermaid
graph TD;

subgraph content-provider

participants
game-providers
competition-organizers
league
club

end

subgraph spectators

spectators

end

participants-->competition
competition--benefit-->participants
game-providers-->competition
competition-organizers-->competition
league-->competition
club-->competition

competition-->TV
competition-->live-streaming

TV-->cast
live-streaming-->cast

cast-->spectators

competition--report-->spectators

spectators--become-->sponsers
spectators--benefit-->investers

sponsers--benefit-->content-provider
investers--benefit-->content-provider

regulator

```