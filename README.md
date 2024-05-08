![Logo](https://github.com/DeemaSWE/TechCare/assets/90179257/cf227e04-3d70-4f45-b261-f62519a8dff8)
# TechCare

_Welcome to TechCare!_

TechCare is your reliable destination for all your electronic repair needs. We connect you with skilled technicians who can  restore your malfunctioning devices. Our platform caters to three users: Customers, Technicians, and Trainees.

_For Customers_

- Find skilled, trusted technicians who can fix your devices .
- Our platform makes it simple to request a repair, track progress, and leave feedback.
- Browse technician profiles and ratings to make informed decisions.

_For Technicians_

- Reach more customers and gain visibility for your repair skills.
- Accept or decline requests, setting your own hours and workload.
- Train the next generation of technicians and leave a lasting impact.

_For Trainees_

- Learn from experienced technicians and get hands-on training.
- Build your experience and reputation as a repair technician.
- Connect with technicians dedicated to sharing their knowledge.

## Tools
- Intellij
- DataGrip
- Postman
- Xampp
- Figma
- Canva

## Dependencies
- Lombok
- Validation
- Spring Web
- Spring Security
- Spring Data JPA
- MySQL Driver
- JUnit tests
## Presentation
https://www.canva.com/design/DAGEkE6e5qk/PMreR9pmtzD674fN389cjw/edit?utm_content=DAGEkE6e5qk&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton
## API Documentation
https://documenter.getpostman.com/view/33389231/2sA3JJA441
## Figma
https://www.figma.com/file/Ifmivq19uWHkpAEAQG3IZ3/Figma-basics?type=design&node-id=1669%3A162202&mode=design&t=AVVffBJIKCgRwYn8-1
## Endpoints
_Ahmed's Endpoints_
| No. | Endpoint | Description |
| --- | --- | --- |
| 1 | POST /api/v1/trainer/register | Trainer register |
| 2 | GET /api/v1/trainer/get-all | Admin get all trainers |
| 3 | GET /api/v1/trainer/get-profile | Trainer get their profile |
| 4 | PUT /api/v1/trainer/update | Trainer update their profile |
| 5 | DELETE /api/v1/trainer/delete/{trainer_id} | Admin delete a trainer |
| 6 | PUT /api/v1/trainer/rate-tech/{techID}/{reqId}/{rate} | Trainer rate technician |
| 7 | GET /api/v1/services/get-by-category/{categoryId} | Get services by category |
| 8 | GET /api/v1/services/get-by-hours/{hours} | Get training services by hours |
| 9 | PUT /api/v1/request/trainer-rate-request/{reqId}/{rate} | Trainer Rate Request |
| 10 | GET /api/v1/technician/service-technician/{service_id} | Get technician by service |
| 11 | GET /api/v1/technician/get-by-id/{technicianId} | Get technician by id |
| 12 | GET /api/v1/technician/top-rated | Get top rated technicians |
| 13 | GET /api/v1/technician/get-trainer-level/{level} | Technician get trainer by level |
| 14 | GET /api/v1/technician/filter-by-experience/{years} | Filter technician by years of experience |
## Class Diagram
## Use Case Diagram
![Final_use_case_Diagram drawio](https://github.com/DeemaSWE/test/assets/90179257/68ee24a9-0153-4db3-b50f-3689ca525b07)
