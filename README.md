# Christmas Festivity Optimization Projects 🎄

This project showcases some innovative ideas to optimize one of the most festive and wholesome holidays, Christmas.

## I. Network Optimization: Optimal Tour Route of Santa Claus

In this part, we aimed to design an optimal tour route from Spain to Finland (the most distanced country from Spain) that connects various European capital cities. The challenge was to minimize the total distance traveled while considering the actual distances and connectivity between the cities.

### Project Highlights
- **Objective**: Minimize the total distance traveled by Santa Claus.
- **Nodes and Edges**: Cities and routes between cities defined as sets.
- **Decision Variables**: Binary variables indicating if a route between two cities is included in the tour.
- **Algorithm**: Minimum Cost Flow algorithm applied to the network of cities and routes.
- **Constraints**: 
  - **Flow Conservation**: Ensuring each city is visited exactly once.
  - **Subtour Elimination**: Using Miller-Tucker-Zemlin (MTZ) constraints to prevent cycles.
  
### Key Results
- Successfully determined the optimal path and costs, ensuring minimal travel distance between nodes like Madrid, Rome, Paris, Lisbon, Dublin, etc.

## II. Non-Linear Optimization: Christmas Tree Pricing

This part focuses on optimizing the pricing of Christmas trees, considering their elastic and inelastic demand characteristics. Given the cultural significance of Christmas trees, their general demand is quite inelastic, but variations in consumer preferences based on size, type (artificial or natural), and price significantly influence specific demand patterns.

### Project Highlights
- **Objective**: Determine optimal prices for three types of Christmas trees to maximize profitability.
- **Variables**: Prices of three different types of Christmas trees (x1, x2, x3).
- **Demand Functions**: Custom functions representing the relationship between price and demand for each tree type, incorporating price elasticity and cross-price effects.
- **Production and Cost Functions**: Reflect economic realities of tree production, emphasizing the inverse relationship between production volume and per-unit cost.

### Key Results
- Developed a model using demand curve formulation and optimization techniques.
- Formulated demand, production, and cost functions to realistically reflect the market scenario.
