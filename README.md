# Thai Nation Exam Corpus - Onet Corpus in JSON Format
This repository contains a collection of thai nation exam in JSON format for the purpose of being an AI resource for the O-net (Ordinary National Education Test) exam corpus. The O-net exam corpus is a copyrighted material, but this collection is intended to be used as a resource for AI research and development.

# Background
The O-net exam corpus is a collection of Thai language texts used in the Ordinary National Education Test in Thailand. It contains a wide variety of text genres, including news articles, academic papers, literary works, and more. The corpus is a valuable resource for language research and development, but its use is limited by copyright restrictions.

This repository aims to provide a useful resource for AI researchers and developers working with Thai language text data. By collecting a subset of the O-net exam corpus in JSON format, we hope to facilitate the development of natural language processing (NLP) models and other AI applications that can benefit Thai people.

# Contents
The corpus in this repository contains a subset of the O-net exam corpus, including text passages from a variety of genres. The corpus is organized into folders by genre, with each text passage stored as a separate JSON file. Each JSON file contains the following fields:

- `id`: a unique identifier for the text passage
- `question`: the exam question in Thai language
- `materials`: the supporting materials for the question, such as tables, images, or other relevant information (optional)
- `choice`: a list of possible answer choices for the question
- `answer`: the index of the correct answer choice, starting from 1

example:
```json
{
   "id":1,
   "question":"ข้อใดต่อไปนี้ถูกต้อง",
   "materials":[
      {
         "type":"table",
         "message:":"<table><th><tr>หัวข้อ</tr></th></table>"
      },
      {
         "type":"list",
         "message":[ "ก. ปลาเดินได้",  "ข.ปลาบินได้"     ]
      }
   ],
   "choice":[ "ก ถูก",  "ข ถูก",  "ผิดทั้งคู่", "ถูกทั้งคู่"   ],
   "answer":4
}
```

# Usage
The corpus in this repository can be used as a resource for AI research and development involving Thai language text data. However, please note that the O-net exam corpus is copyrighted, and any commercial use or distribution of this corpus may be subject to legal restrictions.

To use the corpus, simply clone or download this repository and extract the JSON files you need. The corpus can be used for a variety of tasks, including language modeling, text classification, and more.

# License
The corpus in this repository is provided under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) license. However, please note that the O-net exam is copyrighted, and any commercial use or distribution of this corpus may be subject to legal restrictions.

# Disclaimer
The corpus is provided as-is and without any warranty or guarantee of accuracy or completeness. The creators of the corpus are not responsible for any errors, omissions, or inaccuracies in the corpus, nor for any consequences that may arise from the use of the corpus. Users of the corpus are solely responsible for ensuring that their use of the corpus complies with all applicable laws and regulations.
