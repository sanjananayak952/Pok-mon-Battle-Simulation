## Pokémon Battle Simulation 


🌟 Features

1]⚡ Real-time Pokémon battles with authentic game mechanics

2]🔍 Comprehensive Pokémon data from the official PokeAPI

3]🤖 MCP compliant for seamless AI integration

4]🚀 Blazing fast performance with LRU caching

5]📊 Interactive API documentation built-in

📹 Screenshot
![image](https://github.com/user-attachments/assets/a37452f8-76b0-4cb9-a9fb-7b31365460b0)
![image](https://github.com/user-attachments/assets/78f41859-ebcd-43fd-bdb8-a3ca91746de9)


🛠️ Installation

Prerequisites
--Python 3.11+
--pip package manager

Step-by-Step Setup
# 1. Clone the repository
git clone [https://github.com/sanjananayak952/Pok-mon-Battle-Simulation]
cd pokemon-battle-server

# 2. Create and activate virtual environment
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate    # Windows

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






## 📬 Contact

<div align="center" style="background:#f5f5f5;padding:20px;border-radius:10px;max-width:500px;margin:0 auto;">
  <h3>Sanjana Nayak</h3>
  
  
  <p>
    <a href="sanajananayak952@gmail.com">📧 sanjananayak952@gmail.com</a><br>
    <a href="8090812761">📞 8090812761</a>
  </p>
  
  <p>
    <a href="www.linkedin.com/in/sanjana-nayak-82a06025b"><img src="https://img.icons8.com/color/32/000000/linkedin.png" alt="LinkedIn"></a>
    <a href="[https://github.com/sanjananayak952]" target="_blank"><img src="https://img.icons8.com/fluent/32/000000/github.png" alt="GitHub"></a>
    
  </p>
</div>
