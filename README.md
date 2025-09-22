# Hi there, I'm Fran Hancco Champi
Nice to meet you! :)

# ABOUT ME
```python
class FranHancco:
    def __init__(self) -> None:
        self.nickName: str = "Fran"
        self.code: list[str] = ["Python", "Java", "JavaScript"]
        self.languages: list[str] = ["Spanish (native)", "English", "Portuguese"]
        self.askMeAbout: list[str] = [
            "Computer Vision",
            "Artificial Intelligence",
            "Cloud Services",
            "Deep Learning",
            "Research"
        ]
        
        self.message: str = (
            "Bachelor in Computer Science, "
            "specialized in Computer Vision and "
            "Cloud-based AI solutions."
        )

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


if __name__ == "__main__":
    fran = FranHancco()
    print(fran.message)
```
