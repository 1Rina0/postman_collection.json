 API Testing Project (PokeAPI & JSONPlaceholder)

This project demonstrates manual + automated API testing using **Postman**.

## ✅ Overview
The goal of this project is to validate multiple API endpoints by:
- Sending requests
- Verifying responses
- Adding automated Postman tests
- Logging test results
- Recording defects

This simulates real entry‑level QA work.

---

## ✅ Tools Used
- Postman
- JSON
- Public REST APIs
- (Optional) Newman CLI

---

## ✅ Endpoints Tested
| Method | Endpoint | Description |
|--------|----------|-------------|
| GET    | /pokemon/ditto | Retrieve details for Pokémon “ditto” |
| GET    | /pokemon?limit=10 | Retrieve list of Pokémon |
| POST   | /posts | Create a placeholder post |
| GET    | /pokemon/invalid | Negative test |

---

## ✅ Test Artifacts

| Artifact | Location | Description |
|----------|----------|-------------|
| Test Cases | /test-cases/api_test_cases.md | Requirements + expected results |
| Test Results | /test-results/api_test_results.md | Actual execution results |
| Defect Log | /defects/defect_log.md | Mock defects captured |
| Evidence | /evidence | Placeholder for screenshots |
| Postman Collection (optional) | — | Can be added here |

---

## ✅ Sample Highlights
✔ Validated success response codes  
✔ Used automated Postman test scripts  
✔ Negative testing included  
✔ Mock defects added for realism  

---

## ✅ Folder Structure
```
api_project/
├── README.md
├── test-cases/
│   └── api_test_cases.md
├── test-results/
│   └── api_test_results.md
├── defects/
│   └── defect_log.md
└── evidence/
    └── placeholder.txt
```

---

## ✅ How To Use

1) Open Postman  
2) Import the API requests or collection  
3) Run each API request  
4) Observe status code + body  
5) Check automated tests  
6) Update results + defects  

Optional:
Run via Newman for CLI automation.

---

## ✅ Next Improvements
- Add Newman report output
- Add CI integration
- Add schema validation
- Add more endpoints

---

## ✅ Author
QA Tester Portfolio Project
g README.md…]()

