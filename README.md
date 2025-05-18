## Pokémon Battle Simulation 


🌟 Features

1]⚡ Real-time Pokémon battles with authentic game mechanics

2]🔍 Comprehensive Pokémon data from the official PokeAPI

3]🤖 MCP compliant for seamless AI integration

4]🚀 Blazing fast performance with LRU caching

5]📊 Interactive API documentation built-in

📹 Screenshot
![Screenshot 2025-05-18 202610-min](https://github.com/user-attachments/assets/2d95da12-fc56-4c6c-a478-504c4fad687c)
![Screenshot 2025-05-18 203018-min](https://github.com/user-attachments/assets/841809f9-48bc-4bd5-bafc-75443807e568)


🛠️ Installation

Prerequisites
1]Python 3.11+
2]pip package manager

Step-by-Step Setup
# 1. Clone the repository
1]git clone [https://github.com/sanjananayak952/Pok-mon-Battle-Simulation]
2]cd pokemon-battle-server

# 2. Create and activate virtual environment
1]python -m venv venv
2]source venv/bin/activate  # Linux/Mac
3]venv\Scripts\activate    # Windows

# 3. Install dependencies
pip install -r requirements.txt

🚀 Quick Start
# Run the development server
uvicorn main:app --reload

Access these endpoints in your browser:

1]API Docs: http://localhost:8000/docs

Example Response:
json
{
  "id": 25,
  "name": "pikachu",
  "types": ["electric"],
  "stats": {
    "hp": 35,
    "attack": 55,
    "defense": 40,
    "special_attack": 50,
    "special_defense": 50,
    "speed": 90
  }
}

Simulate a Battle
curl -X POST "http://localhost:8000/battle/simulate" \
-H "Content-Type: application/json" \
-d '{"pokemon1":"charizard","pokemon2":"blastoise"}'








## 📇 Contact

**Sanjana Nayak**  
📞 Phone: +91-8090812761 
📧 Email: sanjananayak952@gmail.com  
🌐 GitHub: [github.com/Sanjana Nayak](https://github.com/sanjananayak952) 
🔗 LinkedIn: [linkedin.com/in/Sanjana Nayak](www.linkedin.com/in/sanjana-nayak-82a06025b)

