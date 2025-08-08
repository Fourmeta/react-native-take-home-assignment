# Pokédex Vibes + Step Power!

📘 Overview:
Create a small React Native Pokédex app that allows users to:
1. Browse a list of Pokémons (use any open API like [PokeAPI](https://pokeapi.co/))
2. View details of a selected Pokémon
3. Use a native module to track steps (pedometer) and “power up” your Pokémon based on steps taken.

🧠 Core Objectives:
- Display a list of Pokémon fetched from a remote API
- On Pokémon selection, show its details (name, image, type, etc.)
- Integrate a native module to track steps (e.g., using `CoreMotion` on iOS or `SensorManager` on Android)
- Based on step count, increase the "power level" of the Pokémon
  - For example: 100 steps = +1 power level
- Bonus: Add animation or fun UI to reflect the Pokémon powering up

🔧 Requirements:
1. Rect Native core skills:
  - List rendering
  - API integration
  - Navigation (stack or tabs)
2. Native Module Integration:
  - Must implement a simple custom native module OR integrate with a pedometer library like:
    - iOS: CMPedometer
    - Android: SensorManager
  - The module should expose a method like getStepCount() or startStepTracking() that returns step count since app launch or over a time period.
3. Optional Extras (for brownie points):
  - Persist Pokémon power level (e.g., AsyncStorage)
  - Unit test a component or the native module interface
  - Cool UI/UX interactions

🧪 Evaluation Criteria:
- Clean, readable code with good structure
- Proper state management (React state or libraries like Zustand, Redux, or Context)
- Proper usage of native module (can be minimal but should be real)
- Ability to create a fun, interactive UI
- Time-efficient implementation (don't over-engineer)

📦 Submission Instructions:
- Provide a GitHub repo (public or private with access)
- Include a short README:
  - How to run the app
  - Which native module strategy was used
  - Any limitations or assumptions

⚠️ Notes:
- The goal is not to build a full Pokédex but to show:
  - You can work with external APIs
  - You understand React Native principles
  - You know how to implement or integrate native functionality
