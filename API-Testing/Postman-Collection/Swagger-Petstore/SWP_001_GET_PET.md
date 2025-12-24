# Test Case: Retrieve pet by petId

**Test Case ID:** SWP_001 <br>
**Endpoint:** `Get /pet/{petId}`<br>
**Preconditions:** API key set via Swagger UI (api_key: special-key). <br><br>
---
**Test Steps:**<br>
1. Submit `GET` request to `/pet/{petId}` using petId = 1<br>
2. Capture response<br><br>
---
**Expected Result(s):**
1. `Status code: 200` OK<br>
2. Response body contains a Pet object<br>
3. Fields `id`, `category`, `name`, `photoUrls`, `tags`, and `status` are present<br>
4. Data types match Pet schema<br><br>
---
**Actual Result(s):**
1. HTTP status code: `200` returned.<br>
2. Response body contains a Pet object<br>
3. Reponse body contained all expected fields.<br>
4. Data types match Pet schema<br><br>
---
**Status:**
Pass
---
**Notes:** Response values confirm to the the Pet schema. Test data values appear valid for the demo environment.
