![image](https://github.com/user-attachments/assets/dfd27e8d-e542-465c-9395-3e96fb6d9c72)
![image](https://github.com/user-attachments/assets/45c1b73a-bf04-4085-acea-8a331b77b4c9)
![image](https://github.com/user-attachments/assets/e31bdaf6-238f-4d50-af8e-16c66b4ce13f)
![image](https://github.com/user-attachments/assets/95cbecaa-367f-4135-a623-22a9b34cc52e)

{
    "documents": [
        {
            "id": "id__11793",
            "sentiment": "negative",
            "confidenceScores": {
                "positive": 0.16,
                "neutral": 0.14,
                "negative": 0.69
            },
            "sentences": [
                {
                    "sentiment": "negative",
                    "confidenceScores": {
                        "positive": 0.31,
                        "neutral": 0.28,
                        "negative": 0.41
                    },
                    "offset": 0,
                    "length": 55,
                    "text": "Eu acho que o anúncio no site poderia ter sido melhor. ",
                    "targets": [],
                    "assessments": []
                },
                {
                    "sentiment": "negative",
                    "confidenceScores": {
                        "positive": 0.02,
                        "neutral": 0,
                        "negative": 0.98
                    },
                    "offset": 55,
                    "length": 133,
                    "text": "As informações diziam ser perto de museu, mas eu tive que andar bastante O hotel está velho e precisa de melhorias Não foi agradável.",
                    "targets": [
                        {
                            "sentiment": "negative",
                            "confidenceScores": {
                                "positive": 0.02,
                                "negative": 0.98
                            },
                            "offset": 130,
                            "length": 5,
                            "text": "hotel",
                            "relations": [
                                {
                                    "relationType": "assessment",
                                    "ref": "#/documents/0/sentences/1/assessments/0"
                                },
                                {
                                    "relationType": "assessment",
                                    "ref": "#/documents/0/sentences/1/assessments/1"
                                },
                                {
                                    "relationType": "assessment",
                                    "ref": "#/documents/0/sentences/1/assessments/2"
                                }
                            ]
                        }
                    ],
                    "assessments": [
                        {
                            "sentiment": "negative",
                            "confidenceScores": {
                                "positive": 0.01,
                                "negative": 0.99
                            },
                            "offset": 141,
                            "length": 5,
                            "text": "velho",
                            "isNegated": false
                        },
                        {
                            "sentiment": "negative",
                            "confidenceScores": {
                                "positive": 0.05,
                                "negative": 0.95
                            },
                            "offset": 160,
                            "length": 9,
                            "text": "melhorias",
                            "isNegated": false
                        },
                        {
                            "sentiment": "negative",
                            "confidenceScores": {
                                "positive": 0.01,
                                "negative": 0.99
                            },
                            "offset": 149,
                            "length": 20,
                            "text": "precisa de melhorias",
                            "isNegated": false
                        }
                    ]
                }
            ],
            "warnings": []
        }
    ],
    "errors": [],
    "modelVersion": "2025-01-01"
}
