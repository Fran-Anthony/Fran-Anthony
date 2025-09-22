# Hi there, I'm Fran Anthony Hancco Champi
Nice to meet you! :)

# ABOUT ME
```python
class FranAHancco:
    def __init__(self) -> None:
        self.nickName: str = "Fran"
        self.code: list[str] = ["Python", "C++", "JavaScript" ]
        self.languages: list[str] = ["Spanish", "English", "Portuguese"]
        self.askMeAbout: list[str] = ["Computer Vision", "Artificial Intelligence", "Cloud Services", "Deep Learning", "Research"
        ]
        
        self.message: str = "Bachelor in Computer Science with specialization in Computer Vision, and Cloud-based AI solutions."


    def research(self) -> dict:
        return {
            "cloudAI": {
                "specialization": "Retrieval-Augmented Generation (RAG)",
                "providers": ["AWS", "Azure", "Google Cloud"],
                "tools": [
                    "Amazon S3", "Amazon Bedrock", "Lambda Functions",
                    "Azure Search", "Azure OpenAI",
                    "BigQuery", "Vertex AI", "Cloud Functions"
                ]
            }
        }

    def technologies(self) -> dict:
        return {
            "os": ["Windows", "Linux"],
            "deepLearning": ["TensorFlow", "PyTorch", "YOLO", "OpenCV"],
            "backEnd": ["Spring Boot", "Postman"],
            "frontEnd": ["Angular"],
            "databases": ["SQL Server"],
            "additional": ["Git", "Docker"],
            "methodologies": ["Scrum", "CRISP-DM"]
        }

```

## 🎮 Play Hunt the Wumpus
Want to play a classic game in Python? Copy this code into your terminal and run it!

```python
import random

class HuntTheWumpus:
    def __init__(self):
        self.rooms = {i: [((i-1) % 20)+1, ((i+1) % 20)+1, ((i+5) % 20)+1] for i in range(1, 21)}
        self.wumpus = random.randint(1, 20)
        self.player = random.randint(1, 20)

    def play(self):
        print("Welcome to Hunt the Wumpus! Try not to get eaten...")
        while True:
            print(f"\nYou are in room {self.player}. Tunnels lead to {self.rooms[self.player]}")
            if self.player == self.wumpus:
                print("Oh no! The Wumpus got you!")
                break

            move = input("Move or Shoot? (m/s) ").strip().lower()
            if move == "m":
                choice = int(input("Which room? "))
                if choice in self.rooms[self.player]:
                    self.player = choice
                else:
                    print("You can't go there!")
            elif move == "s":
                choice = int(input("Shoot into which room? "))
                if choice == self.wumpus:
                    print("🎉 You killed the Wumpus! Victory!")
                    break
                else:
                    print("Missed! The Wumpus is still alive...")
            else:
                print("Invalid command. Use m/s.")
                
if __name__ == "__main__":
    HuntTheWumpus().play()




```















# Contact
# 📫 How to reach me: fran.an15@proton.me


### Languages and Tools

<p align="left">
  <!-- Lenguajes -->
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" alt="C++" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript" width="40" height="40"/>

  <!-- Cloud & AWS específicos -->
  <!-- Otros Clouds -->
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/azure/azure-original.svg" alt="Azure" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/googlecloud/googlecloud-original.svg" alt="GCP" width="40" height="40"/>

  <!-- Deep Learning / IA -->
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tensorflow/tensorflow-original.svg" alt="TensorFlow" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" alt="PyTorch" width="40" height="40"/>
  <img src="https://cdn.simpleicons.org/ultralytics/042AFF" alt="Ultralytics" width="40" height="40"/>

  <!-- Herramientas / APIs -->
  <img src="https://cdn.simpleicons.org/postman/FF6C37" alt="Postman" width="40" height="40"/>

  <!-- Bases de datos -->
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" alt="MongoDB" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/microsoftsqlserver/microsoftsqlserver-plain.svg" alt="SQL Server" width="40" height="40"/>

  <!-- Extras -->
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="Git" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" alt="Docker" width="40" height="40"/>

  <!-- Sistemas Operativos -->
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/windows8/windows8-original.svg" alt="Windows" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" alt="Linux" width="40" height="40"/>

  <!-- Roboflow -->
  <img src="https://cdn.simpleicons.org/roboflow/00C4CC" alt="Roboflow" width="40" height="40"/>
</p>


