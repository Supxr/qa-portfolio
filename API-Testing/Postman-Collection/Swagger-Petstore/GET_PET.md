# Test Suite: Retrieve pet by petId

## Scope
This test suite validates the behavior of the GET /pet/{petId} endpoint for valid, non-existent, and invalid petId inputs.


**Test Case ID:** SP_GET_PET_001 <br>
**Title:** Retrieve pet using valid petId.<br>
**Endpoint:** `Get /pet/{petId}`<br>
**Preconditions:** API key set via Swagger UI (api_key: special-key).


**Test Steps:**<br>
1. Submit `GET` request to `/pet/{petId}` using petId = `1`<br>
2. Capture response


**Expected Result(s):**
1. `Status code: 200` OK<br>
2. Response body contains a Pet object<br>
3. Fields `id`, `category`, `name`, `photoUrls`, `tags`, and `status` are present<br>
4. Data types match Pet schema


**Actual Result(s):**
1. HTTP status code: `200` returned.<br>
2. Response body contains a Pet object<br>
3. Reponse body contained all expected fields as defined in the Pet schema.<br>
4. Data types match Pet schema.<br>
5. No unexpected or undocumented fields are present in the response.


**Status:**
Pass


**Notes:** Response values conform to the Pet schema. Test data values appear valid for the demo environment.

---
**Test Case ID:** SP_GET_PET_002 <br>
**Title:** Retrieve pet using non-existent petId.<br>
**Endpoint:** `GET /pet/{petId}`<br>
**Preconditions:** API key set via Swagger UI (api_key: special-key).


**Test Steps:**<br>
1. Submit `GET` request to `/pet/{petId}` using petId = `999999`<br>
2. Capture response


**Expected Result(s):**
1. `Status code: 404` Not Found.<br>
2. Response body contains the fields: `code`, `type`, and `message`.<br>
3. Message indicates: `Pet not found`.<br>
3. Data types match Error Response schema.

**Actual Result(s):**
1. `Status code: 404` returned.<br>
3. Reponse body contained all expected fields as defined in the Error Response schema.<br>
4. Data types match Error Response schema.<br>
5. No unexpected or undocumented fields are present in the response.


**Status:**
Pass


**Notes:** Response values conform to the Error Response schema. Test data values appear valid for the demo environment.

---
**Test Case ID:** SP_GET_PET_003 <br>
**Title:** Retrieve pet using invalid petId.<br>
**Endpoint:** `GET /pet/{petId}`<br>
**Preconditions:** API key set via Swagger UI (api_key: special-key).


**Test Steps:**<br>
1. Submit `GET` request to `/pet/{petId}` using invalid petId = `-10` (other tested values: `!@#$%^`, `     `, `abc`).<br>
2. Capture response.


**Expected Result(s):**
1. `Status code: 400` Bad Request.<br>
2. Response body contains the fields: `code`, `type`, and `message`.<br>
3. Message indicates: `Invalid ID suppled`.<br>
3. Data types match Error Response schema (`400`).

**Actual Result(s):**
1. `Status code: 404` returned.<br>
2. Response body contains the fields: `code`, `type`, and `message`.<br>
3. Message indicates: `Pet not found`.<br>
4. Data types match Error Response schema (`404`).


**Status:**
Fail


**Notes:** 
1. Invalid petId formats returned `404 Not Found` instead of `400 Bad Request`.
2. This suggests missing or incorrect input validations where bad requests are treated as missing data.

