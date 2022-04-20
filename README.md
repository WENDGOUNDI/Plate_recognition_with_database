# Plate Recognition with Information Retrieval through a database
This project is a combination of optical character recognition and database information retrieval. A vehicle plate image is loaded into the model. The model will extract the plate number by using paddleOCR library and then the extracted plate number wil  be used to query with a database already containing some registered plate numbers. If the queried plate number exist in the database, we output the person first name, last name and telephone number otherwise we ask the user to register the unknown plate.

# Dependencies
 - CV2
 - Sqlite3
 - Matplotlib
 - OS
 - Paddleocr
 - Glob

# Inference
- Application of OCR for plate info extraction
![OCR_1](https://user-images.githubusercontent.com/48753146/164192887-6fd9f1ca-e090-4bb0-82af-10ddaca455ee.png)

- Inference with plate registered in the database
 
![query_1](https://user-images.githubusercontent.com/48753146/164192868-feecdc52-53f1-48a6-a55f-466318deda66.png)

- Inference with plate not register in the database
 
![query_2](https://user-images.githubusercontent.com/48753146/164192881-12b724e0-aa79-49c1-b84f-763d913c0b64.png)
