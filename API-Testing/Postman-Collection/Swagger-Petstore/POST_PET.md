# Test Suite: Create/Update Pet

## Scope
Valid create, invalid payloads, schema/validation behaviour.


**Test Case ID:** SP_POST_PET_001

**Title:** Create Pet using valid payload.

**Endpoint:** `POST /pet`

**Preconditions:** API key set via Swagger UI (api_key: special-key).

**Test Steps:**
1. Submit `POST` request to `/pet` using valid pet JSON payload with ID: `10001`.
2. Capture response
3. Submit `GET`  request to `/pet/{petId}` used petId = `10001`.
4. Capture response


**Expected Result(s):**
1. `Status code: 200` OK for POST submission.
2. POST submission response body matches Pet schema: `id`, `category`, `name`, `photoUrls`, `tags`, `status`
3. Returned `ID` matches submitted `ID`
4. GET returns `Status code: 200` OK and the created Pet.


**Actual Result(s):**
1. `Status code: 200` OK for POST submission.
2. Response body contains a Pet object
3. Reponse body contained all expected fields as defined in the Pet schema.
4. Data types match Pet schema.
5. Returned `ID` matches submitted `ID`
6. GET returns `Status code: 200` OK and the created Pet.
7. No unexpected or undocumented fields are present in the response.


**Status:** ✅Pass

---
**Test Case ID:** SP_POST_PET_002

**Title:** Create Pet with missing required field.

**Endpoint:** `POST /pet`

**Preconditions:** API key set via Swagger UI (api_key: special-key).

**Test Steps:**
1. Remove top-level `name` field.
2. Submit `POST` request to `/pet` using ID = `10002`.
2. Capture response
3. Submit `GET`  request to `/pet/{petId}` used petId = `10002`.
4. Capture response


**Expected Result(s):**
1. `Status code: 405` Invalid input for POST submission.
2. POST submission is denied.
3. Error message indicates: `Invalid input`.
4. New Pet is not created.


**Actual Result(s):**
1. `Status code: 200` OK for POST submission.
2. Response body contains the fields: `id`, `category`, `photoUrls`, `tags`, `status` 
5. Returned `ID` matches submitted `ID`
6. GET returns `Status code: 200` OK and the created Pet.
7. No unexpected or undocumented fields are present in the response.


**Status:** ❌Fail

**Notes:** 
1. `POST /pet` request was successful (status code: 200 OK) even when `name` field was missing.
