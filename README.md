# Hi there, I'm Fran Hancco Champi
Nice to meet you! :)

# ABOUT ME
```javascript
class FranHancco {
  constructor() {
    this.nickName = "Fran";
    this.code = ["Python", "Java", "JavaScript"];
    this.languages = ["Spanish (native)", "English", "Portuguese"];
    this.askMeAbout = [
      "Computer Vision",
      "Artificial Intelligence",
      "Cloud Services",
      "Deep Learning",
      "Research"
    ];
    
    this.message = "Bachelor in Computer Science, specialized in Computer Vision and Cloud-based AI solutions.";
  }

  research() {
    return {
      cloudAI: {
        specialization: "Retrieval-Augmented Generation (RAG)",
        providers: ["AWS", "Azure", "Google Cloud"],
        tools: [
          "Amazon S3", "Amazon Bedrock", "Lambda Functions",
          "Azure Search", "Azure OpenAI",
          "BigQuery", "Vertex AI", "Cloud Functions"
        ]
      }
    };
  }

  technologies() {
    return {
      os: ["Windows", "Linux"],
      deepLearning: ["TensorFlow", "PyTorch", "YOLO", "OpenCV"],
      backEnd: ["Spring Boot", "Postman"],
      frontEnd: ["Angular"],
      databases: ["SQL Server"],
      additional: ["Git", "Docker"],
      methodologies: ["Scrum", "CRISP-DM"]
    };
  }
}

const fran = new FranHancco();
console.log(fran.message);
