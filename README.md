1. Pull ontop docker with : docker pull ontop/ontop
2. Build this docker with: docker compose up -d --build
3. Go into Docker Desktop, look up and check the ID of this Ontop container (for example: 471642afaa85d3d36c79375595000f9b8515cadf9b69f8da2aab4dfcc8b245c8)
4. Connect ontop to the same network with backend sql: docker network connect backend_network-1 <ontop_container_ID>
5. Get the results at http://localhost:9090/ and profit (endpoint: http://localhost:9090/sparql)
