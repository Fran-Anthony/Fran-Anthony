# Hi 👋, I'm Fran Hancco Champi
Nice to meet you! :)

```python
class FranHanccoChampi:
    def __init__(self):
        self.pronouns = "he"
        self.nickName = "Fran"
        self.study = "Computer and Systems Engineering student at UNSAAC"
        
        self.focusAreas = [
            "Computer Vision",
            "Cloud & AI",
            "Deep Learning"
        ]
        
        self.languages = ["Python", "Java", "SQL"]
        self.frameworks = ["TensorFlow", "YOLOv8", "Spring Boot", "Angular"]
        
        self.cloud_experience = {
            "AWS": ["S3", "Bedrock", "Lambda Functions"],
            "Azure": ["Azure Search", "Azure OpenAI"],
            "Google Cloud": ["BigQuery", "Vertex AI", "Cloud Functions"]
        }
        
        self.projects = {
            "Computer Vision": "Quality control of alpaca fiber using AI (custom dataset + YOLOv8)",
            "Cloud & AI": "RAG pipelines with AWS, Azure, GCP",
            "Software Dev": [
                "Inventory Control System (UNSAAC)",
                "Loan Eligibility System (farmers and ranchers)"
            ]
        }
        
        self.databases = ["SQL Server"]
        self.other_tools = ["Git", "Docker"]
        
        self.message = "Passionate about applying AI in real-world scenarios, \
combining computer vision research with scalable cloud solutions."
        
    def say_hi(self):
        print("Thanks for visiting my profile! Let's connect 🚀")

me = FranHanccoChampi()
me.say_hi()
