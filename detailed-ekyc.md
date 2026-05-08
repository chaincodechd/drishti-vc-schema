# Detailed EKYC Schema

This document describes the **DetailedEKYC** schema used for storing detailed eKYC fields.

---

## fullName

`fullName` is the full name of the user.

```json
"fullName": "Rahul Sharma"
```

## mobileNumber

`mobileNumber` is the mobile number of the user in E.164 format.

```json
"mobileNumber": "+919876543210"
```

## age

`age` is the age of the user.

```json
"age": 28
```

## gender

`gender` is the gender of the user.

```json
"gender": "Male"
```

## residentialAddress

`residentialAddress` is the residential address of the user.

```json
"residentialAddress": "221B Baker Street, Delhi"
```

## dataHash

`dataHash` is the SHA-256 hash of the complete detailed EKYC data in hex format.

```json
"dataHash": "0x9f86d081884c7d659a2feaa0c55ad015a3bf4f1b2b0b822cd15d6c15b0f00a08"
```
