# Signicat Interview Assignment Presentation
**By Ivan Lupaka**

## Assignment 1

**Goal 1 Expected Result:**

*1. Name of my organisation:* "Lupaka"

*2. My Organisation ID:* "o-p-w1B4fU8XEsedQAMOhkiC"

*3. The name of my sandbox account:* "Lupaka-Sandbox"

*4. My Account ID:* "a-spge-6U4w49jaW85sJLic7lYM"

*5. The name of my OIDC client:* "client_01"

*6. The redirect URL(s) that I added to the OIDC client:* "https://oauth.tools/callback/code"

**Goal 2 Expected Result:**

*1. Returned value of “EVENT_TYPE”:* "[srn:sue:1:authbroker:idin:auth]"

**Goal 3 Expected Result:**

*1. OIDC Authorisation URL:* 
```sh
https://lupaka.sandbox.signicat.com/auth/open/connect/authorize?client_id=sandbox-lively-school-353&response_type=code&redirect_uri=https://oauth.tools/callback/code&state=1705456736286-BGY&scope=openid%20profile%20nin&code_challenge=MtTXBIyJ5P1qkLEnl5pdb4-t-JU3jDtszZVnn2HKzDU&code_challenge_method=S256&prompt=login
```

*2. Access Token:*
```sh
eyJhbGciOiJSUzI1NiIsImtpZCI6InNhbmRib3gtc2lnbmluZy1rZXktZDIyNzQ5MDE0NGI3Y2Q0ZmJhMDcxMjViODlhZGUyODQiLCJ0eXAiOiJhdCtqd3QifQ.eyJpc3MiOiJodHRwczovL2x1cGFrYS5zYW5kYm94LnNpZ25pY2F0LmNvbS9hdXRoL29wZW4iLCJuYmYiOjE3MDU0NTc3MjIsImlhdCI6MTcwNTQ1NzcyMiwiZXhwIjoxNzA1NDU4MzIyLCJzY29wZSI6WyJvcGVuaWQiLCJwcm9maWxlIiwibmluIl0sImFtciI6WyJleHRlcm5hbCJdLCJjbGllbnRfaWQiOiJzYW5kYm94LWxpdmVseS1zY2hvb2wtMzUzIiwic3ViIjoiMW1rank3d3JuY1g4ODM3alhrTURTV1pNOHk5ZmVVRm5tVVoxVmZDWlpUUT0iLCJhdXRoX3RpbWUiOjE3MDU0NTc3MTUsImlkcCI6ImlkaW4iLCJpZHBfaWQiOiJGQU5UQVNZQkFOSzEyMzQ1Njc4OTAiLCJzaWQiOiI0QjhBMjZENzQ5MDMwMjYxMzEwOTBBNDY4NEU1MUI3MyIsImlkcF9pc3N1ZXIiOiJpZGluIiwic2FuZGJveCI6dHJ1ZSwianRpIjoiRDJERDhEMUJCMTkxN0E1OTY4MjAyQzk5Nzg4RUUyNkUifQ.lfdhDSpI0F2lkIq74LAzwC7XVg_IK8IY0h8kuAXBpLBUaHD2V1PI-Dwu8UnUgkqjIuCIoBTS762e4Xhh75zQlpi9Vb1BiASzFUORpbT9ccc43E8Iu4D7t2tHy8vXmlt5qGveY51JAR5kaljaBwWYmdw7RqmBkuj4RcG4sWu7zpeBDq4SnQr-Lzefmhb6Ci2ysxyUJh4c4SXJkNAHODZWhO4aVv-PMbKDRvGriPozcNLErFNZ4oWmFH6x3gPdpdEK6_Te6RnKEae3jGH7rxXzzCgk_uQ9E5AuUlS8pUq03dlP9yJbNGfw9YTF4Ddfj01lqFInpCceDBN14VjOJ3Xlrw
```
---

## Assignment 2

**Goal 4 Expected Result:**

*1. Response of the Request:* "https://id.signicat.com/definitions/wsdl/Document-v3"

*2. Value of the “request-id”:* "170120244vfamrjbeskylwdof7pe5kx7fj8ym3plqvnc3xmy7btx15btso"

**Goal 5 Expected Result:**

*1. Description of what happens after I pressed the OK button:* I was redirected to to "https://signicat.com"

*2. Why the observed behaviour occurred:* I can see in the request the value for `<on-task-complete>`, is the signicat site url, which means the signing was successful. I can also see the value for `<on-task-cancel>` is the google url which i can assume means if the signing was unsucessful, the user would be redirected to the google homepage.

**Goal 6 Expected Result:**

*1. Value of “result-uri” from the response of the getStatus request:* "https://preprod.signicat.com/doc/demo/order/170120244vfamrjbeskylwdof7pe5kx7fj8ym3plqvnc3xmy7btx15btso/1/1/sdo</result-uri"

*2. Values I needed to provide in the getStatus request:* I needed to provide the `<doc:service>` and `<doc:password>`.

**Goal 7 Expected Result:**
*1. SDO/XAdES I downloaded:* [Link to SDO/XAdES](https://drive.google.com/file/d/1PwOfSkrrsqm6ifahd4qGjhB1FrMrl-2A/view?usp=sharing)

**Goal 8 Expected Result:**
*1. Result of the “id” element from the response of the create-package request:* "170120242t2iq0vlr3mshodkr2gno3cm07vue3v7lvxqzo67b40ymr6utp"

**Goal 9 Expected Result:**
*1. Link to PDF file:* [PDF File](https://drive.google.com/file/d/17bPv2hxOv7euoWWiMj0lkUNMYy-DzN6l/view?usp=sharing)

*2. Content of the file that is attached to the PAdES:* In the file attached to the PDF, we see key data points for the user that signed the document, the text markup of the document, the long term validation authentication response and timestamps.

*3. Value of the “SignerUniqueId”:* "FANTASYBANK1234567890"

*4. What I noticed about attached file:* The attached file is essentially the XAdES document. The pdf is a packaged version of this, more suitable for end user viewing.

---
## Assignment 3

**Goal 10 Expected Result:**
*1. Response of 3d for the createRequest:* 
```sh
    <create-request-response xmlns="https://id.signicat.com/definitions/wsdl/Document-v3">
         <request-id>1701202451w0kxebq94r9g686pen4tvsyuj8of92ge920cohk7mr8jt11f</request-id>
    </create-request-response>
```

*2. What I needed to do to solve 3d:* I needed to paste the request as in goal 4, and add all the relevant data. I also needed to make sure the syntax for the header value was correct.

*3. The value of the “expires_in” access token that I created:* This value states how long the token is valid for. In this case it was 1800 seconds which is 30 minutes.

**Goal 11 Expected Result:**
*1. Screenshot of SOAP UI demonstrating that i used the access token that I created through Postman in combination with the “create-package” request:*
[Link to screenshot 1](https://drive.google.com/file/d/1U1EWE10mG6OQ0I6tlBIjDrbl87KXv0Uk/view?usp=sharing)
[Link to screenshot 2](https://drive.google.com/file/d/133XLboD3YcVdBk2zWtcrK3mU60zMFcSF/view?usp=sharing)

*2. Access token I used:* 
```sh
{
    "access_token": "eyJhbGciOiJSUzI1NiIsImtpZCI6InNhbmRib3gtc2lnbmluZy1rZXktZDIyNzQ5MDE0NGI3Y2Q0ZmJhMDcxMjViODlhZGUyODQiLCJ0eXAiOiJhdCtqd3QifQ.eyJpc3MiOiJodHRwczovL2FwaS5zaWduaWNhdC5jb20vYXV0aC9vcGVuIiwibmJmIjoxNzA1NDkzMDM5LCJpYXQiOjE3MDU0OTMwMzksImV4cCI6MTcwNTQ5NDgzOSwiYXVkIjoiaHR0cHM6Ly9hcGkuc2lnbmljYXQuY29tIiwic2NvcGUiOlsic2lnbmljYXQtYXBpIl0sImNsaWVudF9pZCI6InNhbmRib3gtcm91Z2gtY2lyY2xlLTUyMCIsImFjY291bnRfaWQiOiJhLXNwZ2UtQmZwTTF4UThCSDdoN3pEcWxrSjkiLCJzYW5kYm94Ijp0cnVlLCJqdGkiOiI5QTA3MTI2MEMxRUYwNzhEODhBQkVFQjc4REM0N0IyNyJ9.l7FmzqR3d9FZ8celzrGbf_ohnXy999FAraUfwCT3GEIAYL9RgcINS2T9lcYfh4deP4SuEwfmBDX5l-SAqqwlCYZgTOeaXSwKvm18LeJvD1o7sQZIf-BfWsxZWOWa4okfBa9tpkSvw2PG_LDwwTIVrh-mJFQRgv0JfZMlkHf69jfOxnTuS4VfMaBNbm3CmVyrWZ40aECzkfLfIgZa1gwPGhYTZji4R5ACRn01d_DDYtvHH8iyjFowlU5Ykz4DdH0mEjYwW6T-G7mLlTumTHNqGhXpOCdqrM97__7hN9TA3Yb5CjwUd-gB8oraREu8JikhJmzD7fFEiG5sWB4fGKs9ig",
    "expires_in": 1800,
    "token_type": "Bearer",
    "scope": "signicat-api"
}
```

## Thank you


