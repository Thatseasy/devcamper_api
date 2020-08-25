# Project: DevCamper API
## Description: Backend API for the DevCamper application to manage bootcamps, courses, reviews, users and authentication
# 📁 Collection: Bootcamps 


## End-point: Get All Bootcamps
### Description: Fetch all bootcamps from database. Includes pagination, filtering, etc
Method: GET
>```
>{{URL}}/api/v1/bootcamps
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|application/json|



⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃


## End-point: Get Single Bootcamp
### Description: Get single bootcamp by ID
Method: GET
>```
>{{URL}}/api/v1/bootcamps/1
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|application/json|



⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃


## End-point: Create new Bootcamp
### Description: Add new Bootcamp to database. Must be authenticated and must be publisher or admin.
Method: POST
>```
>{{URL}}/api/v1/bootcamps/
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|application/json|


### Headers

|Content-Type|Value|
|---|---|
|Authorization|eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjVmMmM4MjFlNmZhYzdjMzhmNGYyMzg2NyIsImlhdCI6MTU5NzkzNjAxNSwiZXhwIjoxNjAwNTI4MDE1fQ.4yPiVxuuZHw5KM0sCq4-QsXyb9a4gIFwD-97D8u_9JM|


### Body (**raw**)

```json
 {
    "name": "ModernTech Bootcamp<script>alert(1)</script>",
    "description": "ModernTech has one goal, and that is to make you a rockstar developer and/or designer with a six figure salary. We teach both development and UI/UX",
    "website": "https://moderntech.com",
    "phone": "(222) 222-2222",
    "email": "enroll@moderntech.com",
    "address": "220 Pawtucket St, Lowell, MA 01854",
    "careers": ["Web Development", "UI/UX", "Mobile Development"],
    "housing": false,
    "jobAssistance": true,
    "jobGuarantee": false,
    "acceptGi": true
  }
```

### 🔑 Authentication bearer

|Param|value|Type|
|---|---|---|
|token|{{TOKEN}}|string|



⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃


## End-point: Update Bootcamp
### Description: Update single bootcamp in database by ID
Method: PUT
>```
>{{URL}}/api/v1/bootcamps/1
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|application/json|


### 🔑 Authentication bearer

|Param|value|Type|
|---|---|---|
|token|{{TOKEN}}|string|



⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃


## End-point: Delete Bootcamp
### Description: Delete Bootcamp from database.
Method: DELETE
>```
>{{URL}}/api/v1/bootcamps/5f3643a0bd7e1b4a486ea192
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|application/json|


### Body (**raw**)

```json

```

### 🔑 Authentication bearer

|Param|value|Type|
|---|---|---|
|token|{{TOKEN}}|string|



⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃


## End-point: Get Bootcamps By Distance
### Description: Get bootcamps within a radius of a specific zipcode
Method: GET
>```
>{{URL}}/api/v1/bootcamps/radius/02118/100
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|application/json|



⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃


## End-point: Upload photo
### Description: Route to upload a bootcamp photo
Method: PUT
>```
>{{URL}}/api/v1/bootcamps/5d725a1b7b292f5f8ceff788/photo
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|application/json|


### 🔑 Authentication bearer

|Param|value|Type|
|---|---|---|
|token|{{TOKEN}}|string|



⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

# 📁 Collection: Courses 


## End-point: Get All courses
### Description: Get all courses in the database
Method: GET
>```
>{{URL}}/api/v1/courses
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|application/json|



⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃


## End-point: Get Courses For Bootcamp
### Description: Get the specific courses for a bootcamp
Method: GET
>```
>{{URL}}/api/v1/bootcamps/5d725a1b7b292f5f8ceff788/courses
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|application/json|



⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃


## End-point: Create New Course
### Description: Create new course for a bootcamp.
Method: POST
>```
>{{URL}}/api/v1/bootcamps/5d725a1b7b292f5f8ceff788/courses
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|application/json|


### Body (**raw**)

```json
{
    "title": "Front End Web Development",
		"description": "This course will provide you with all of the essentials to become a successful frontend web developer. You will learn to master HTML, CSS and front end JavaScript, along with tools like Git, VSCode and front end frameworks like Vue",
		"weeks": 8,
		"tuition": 8000,
		"minimumSkill": "beginner",
		"scholarhipsAvailable": true
}
```

### 🔑 Authentication bearer

|Param|value|Type|
|---|---|---|
|token|{{TOKEN}}|string|



⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃


## End-point: Update course
### Description: Update course in database
Method: PUT
>```
>{{URL}}/api/v1/courses/5d725a4a7b292f5f8ceff789
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|application/json|


### Body (**raw**)

```json
{        "tuition": "13000",
        "minimumSkill": "advanced"
        }
```

### 🔑 Authentication bearer

|Param|value|Type|
|---|---|---|
|token|{{TOKEN}}|string|



⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃


## End-point: Delete Course
### Description: Remove course from database
Method: DELETE
>```
>{{URL}}/api/v1/courses/5d725a4a7b292f5f8ceff789
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|application/json|


### Body (**raw**)

```json

```

### 🔑 Authentication bearer

|Param|value|Type|
|---|---|---|
|token|{{TOKEN}}|string|



⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

# 📁 Collection: Authentication 


## End-point: Register User
### Description: Add user to database with encrypted password
Method: POST
>```
>{{URL}}/api/v1/auth/register
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|application/json|


### Body (**raw**)

```json
{
    "name": "John Doe",
    "email": "john@gmail.com",
    "password": "123456",
    "role": "publisher"
}
```

### 🔑 Authentication bearer

|Param|value|Type|
|---|---|---|
|token|{{TOKEN}}|string|



⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃


## End-point: Login User
### Description: 
Method: POST
>```
>{{URL}}/api/v1/auth/login
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|application/json|


### Body (**raw**)

```json
{
    "email": "mary@gmail.com",
    "password": "123456"
}
```

### 🔑 Authentication bearer

|Param|value|Type|
|---|---|---|
|token|{{TOKEN}}|string|



⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃


## End-point: Get Logged In User via Token
### Description: 
Method: GET
>```
>{{URL}}/api/v1/auth/me
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|application/json|


### Body (**raw**)

```json

```

### 🔑 Authentication bearer

|Param|value|Type|
|---|---|---|
|token|{{TOKEN}}|string|



⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃


## End-point: Forgot Password
### Description: Generate password token and send email
Method: POST
>```
>{{URL}}/api/v1/auth/forgotpassword
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|application/json|


### Body (**raw**)

```json
{
    "email": "john@gmail.com"
}
```

### 🔑 Authentication bearer

|Param|value|Type|
|---|---|---|
|token|{{TOKEN}}|string|



⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃


## End-point: Reset Password
### Description: 
Method: PUT
>```
>{{URL}}/api/v1/auth/resetpassword/35ce2c39a76c04d547510e6d9ed75fab5d064174
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|application/json|


### Body (**raw**)

```json
{
    "password": "1234567"
}
```

### 🔑 Authentication bearer

|Param|value|Type|
|---|---|---|
|token|{{TOKEN}}|string|



⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃


## End-point: Reset Password
### Description: Reset User Password using token
Method: PUT
>```
>{{URL}}/api/v1/auth/resetpassword/7ca28958ca888c18d64696d8576f682331a06b95
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|application/json|


### Body (**raw**)

```json
{
    "password": "1234567"
}
```

### 🔑 Authentication bearer

|Param|value|Type|
|---|---|---|
|token|{{TOKEN}}|string|



⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃


## End-point: Update Password
### Description: Update logged in user password, send in the body currentPassword  and newPassword
Method: PUT
>```
>{{URL}}/api/v1/auth/updatepassword
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|application/json|


### Body (**raw**)

```json
{
    "currentPassword": "1234567",
    "newPassword": "123456"

}
```

### 🔑 Authentication bearer

|Param|value|Type|
|---|---|---|
|token|{{TOKEN}}|string|



⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃


## End-point: Update User Details
### Description: Update logged in user name and email
Method: PUT
>```
>{{URL}}/api/v1/auth/updatedetails
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|application/json|


### Body (**raw**)

```json
{
    "email": "john@gmail.com",
    "name": "John Doe",
    "role": "publisher"
}
```

### 🔑 Authentication bearer

|Param|value|Type|
|---|---|---|
|token|{{TOKEN}}|string|



⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃


## End-point: Logout User
### Description: Clear token cookie
Method: GET
>```
>{{URL}}/api/v1/auth/logout
>```

⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

# 📁 Collection: Reviews 


## End-point: Get All Reviews
### Description: Get all reviews from database and populate with bootcamp name and description
Method: GET
>```
>{{URL}}/api/v1/reviews
>```

⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃


## End-point: Get Reviews For Bootcamp
### Description: Fetch the reviews for a specific bootcamp
Method: GET
>```
>{{URL}}/api/v1/bootcamps/5d725a1b7b292f5f8ceff788/reviews
>```

⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃


## End-point: Get Single Review
### Description: Fetch a review from database by if and populate Bootcamp name and description
Method: GET
>```
>{{URL}}/api/v1/reviews/5d7a514b5d2c12c7449be026
>```

⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃


## End-point: Add Review For Bootcamp
### Description: Insert reveiw for a specific bootcamp   
Method: POST
>```
>{{URL}}/api/v1/bootcamps/5f440b02b422063ebcb6af6b/reviews
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|application/json|


### Body (**raw**)

```json
{
    "title": "fffff",
    "text": "I learned a lot",
    "rating": 2
}
```

### 🔑 Authentication bearer

|Param|value|Type|
|---|---|---|
|token|{{TOKEN}}|string|



⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃


## End-point: Update Review
### Description: Update review in database
Method: PUT
>```
>{{URL}}/api/v1/reviews/5f440c33150e711324186c94
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|application/json|


### Body (**raw**)

```json
{
    "title": "Had Fun"
}
```

### 🔑 Authentication bearer

|Param|value|Type|
|---|---|---|
|token|{{TOKEN}}|string|



⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃


## End-point: Delete Review
### Description: Remove review from database
Method: DELETE
>```
>{{URL}}/api/v1/reviews/5f440c33150e711324186c94
>```
### Body (**raw**)

```json

```

### 🔑 Authentication bearer

|Param|value|Type|
|---|---|---|
|token|{{TOKEN}}|string|



⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

# 📁 Collection: Users 


## End-point: Get All Users
### Description: Get all users (admin)
Method: GET
>```
>{{URL}}/api/v1/users
>```
### 🔑 Authentication bearer

|Param|value|Type|
|---|---|---|
|token|{{TOKEN}}|string|



⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃


## End-point: Get Single User
### Description: Get Single User by Id
Has to be admin
Method: GET
>```
>{{URL}}/api/v1/users/5c8a1d5b0190b214360dc038
>```
### 🔑 Authentication bearer

|Param|value|Type|
|---|---|---|
|token|{{TOKEN}}|string|



⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃


## End-point: Create User
### Description: Add User to database
Method: POST
>```
>{{URL}}/api/v1/users/
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|application/json|


### Body (**raw**)

```json
{
    "name": "Nate Smith",
    "email": "nate@gmail.com",
    "password": "123456"
}
```

### 🔑 Authentication bearer

|Param|value|Type|
|---|---|---|
|token|{{TOKEN}}|string|



⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃


## End-point: Update User
### Description: Update the user details
Method: PUT
>```
>{{URL}}/api/v1/users/5f43f839a1e22d4b6407451d
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|application/json|


### Body (**raw**)

```json
{
    "name": "Nate Johnson",
    "email": "nate@gmail.com",
    "password": "123456"
}
```

### 🔑 Authentication bearer

|Param|value|Type|
|---|---|---|
|token|{{TOKEN}}|string|



⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃


## End-point: Delete User
### Description: Delete user from database
Method: DELETE
>```
>{{URL}}/api/v1/users/5f43f839a1e22d4b6407451d
>```
### Headers

|Content-Type|Value|
|---|---|
|Content-Type|application/json|


### Body (**raw**)

```json

```

### 🔑 Authentication bearer

|Param|value|Type|
|---|---|---|
|token|{{TOKEN}}|string|



⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃ ⁃

_________________________________________________
Author: [bautistaj](https://github.com/bautistaj)

Package: [postman-to-markdown](https://github.com/bautistaj)
