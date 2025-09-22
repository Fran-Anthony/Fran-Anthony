# Hi 👋, I'm Fran Hancco Champi
Nice to meet you! :)

# ABOUT ME
```python
class FranHancco:
    def __init__(self):
        self.nickName = "Fran"
        self.code = ["Python", "Java", "JavaScript"]
        self.languages = ["Spanish (native)", "English", "Portuguese"]
        self.askMeAbout = [
            "Computer Vision",
            "Artificial Intelligence",
            "Cloud Services",
            "Deep Learning",
            "Research",
            "Open Source"
        ]
        self.message = (
            "Computer and Systems Engineering bachelor at UNSAAC. "
            "Passionate about Computer Vision research and "
            "Cloud-based AI solutions. Focused on applied projects "
            "that connect academia with real-world impact."
        )

        self.research = {
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

        self.technologies = {
            "operatingSystems": ["Windows", "Linux"],
            "deepLearning": ["TensorFlow", "PyTorch", "YOLO", "OpenCV", "CNNs"],
            "backEnd": ["Spring Boot", "Postman"],
            "frontEnd": ["Angular"],
            "databases": ["SQL Server"],
            "additional": ["Git", "Docker"],
            "methodologies": ["Scrum"]
        }

    def contact(self):
        return {
            "email": "fran.an15@proton.me",
            "linkedin": "https://linkedin.com/in/your-profile"
        }


me = FranHancco()
print(me.message)
