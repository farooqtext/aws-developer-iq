---
title: AWS IAM Roles
---
Documentation Link: <https://courses.datacumulus.com/downloads/certified-developer-k92/>

![](https://firebasestorage.googleapis.com/v0/b/swimmio.appspot.com/o/repositories%2FZ2l0aHViJTNBJTNBYXdzLWRldmVsb3Blci1pcSUzQSUzQWZhcm9vcXRleHQ%3D%2F9bfef483-0b33-4b38-9e49-da6634370334.png?alt=media&token=2d81ba75-36ed-4321-9c73-db67198b8908)

> ### In AWS we have least privilege principle. We provide the user only necessary privileges to work with AWS.

> IAM is a global service, so there is no option for the region to be selected.

![](https://firebasestorage.googleapis.com/v0/b/swimmio.appspot.com/o/repositories%2FZ2l0aHViJTNBJTNBYXdzLWRldmVsb3Blci1pcSUzQSUzQWZhcm9vcXRleHQ%3D%2F0788679a-b200-417a-90b8-c7a7530081d4.png?alt=media&token=fbb149ac-c2a2-4ab0-93f7-76b7501aad14)

### As part of policies Charles and David will have policy from Developers as well as from Audit Team.

![](https://firebasestorage.googleapis.com/v0/b/swimmio.appspot.com/o/repositories%2FZ2l0aHViJTNBJTNBYXdzLWRldmVsb3Blci1pcSUzQSUzQWZhcm9vcXRleHQ%3D%2F4b48fb05-8847-4af4-bcb4-f5e485c0053b.png?alt=media&token=4268d5fb-ad57-479d-9752-1d08dca9ce4e)

### As part of exam Effect, Principal, Action and Resource are important.

![](https://firebasestorage.googleapis.com/v0/b/swimmio.appspot.com/o/repositories%2FZ2l0aHViJTNBJTNBYXdzLWRldmVsb3Blci1pcSUzQSUzQWZhcm9vcXRleHQ%3D%2Fc4eb6f74-83d2-49cf-a570-dcd7b9adaa90.png?alt=media&token=64b6f485-8fce-4ce8-b711-9cc6b60644d9)

## AWS Console Login

\> aws configure

Access Key - AKIA4JYA7VX3PQREFZ45

Secret Key - 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

\> aws iam list-users

```json
{
    "Users": [
        {
            "Path": "/",
            "UserName": "farooq-user",
            "UserId": "AIDA4JYA7VX3IIJUIMOGI",
            "Arn": "arn:aws:iam::845573762550:user/farooq-user",
            "CreateDate": "2024-01-12T15:49:52+00:00",
            "PasswordLastUsed": "2024-01-12T15:52:54+00:00"
        }
    ]
}
```

&nbsp;

![](https://firebasestorage.googleapis.com/v0/b/swimmio.appspot.com/o/repositories%2FZ2l0aHViJTNBJTNBYXdzLWRldmVsb3Blci1pcSUzQSUzQWZhcm9vcXRleHQ%3D%2F7c934fdc-b5fc-4d25-b7b7-0d78bd31bd30.png?alt=media&token=a975c7ee-6a36-4774-b5c2-08cdd5cdb501)

![](https://firebasestorage.googleapis.com/v0/b/swimmio.appspot.com/o/repositories%2FZ2l0aHViJTNBJTNBYXdzLWRldmVsb3Blci1pcSUzQSUzQWZhcm9vcXRleHQ%3D%2F5ce233b3-2ab5-4aa3-8fa6-763b320ffdfb.png?alt=media&token=586e607c-011a-4e18-b192-6bff3bfeb1b2)

![](https://firebasestorage.googleapis.com/v0/b/swimmio.appspot.com/o/repositories%2FZ2l0aHViJTNBJTNBYXdzLWRldmVsb3Blci1pcSUzQSUzQWZhcm9vcXRleHQ%3D%2Fa5ee18b6-874b-4ec0-b1c1-0a76b6eacb4c.png?alt=media&token=95f38d1d-977a-4bdd-853f-2343424b5d82)

![](https://firebasestorage.googleapis.com/v0/b/swimmio.appspot.com/o/repositories%2FZ2l0aHViJTNBJTNBYXdzLWRldmVsb3Blci1pcSUzQSUzQWZhcm9vcXRleHQ%3D%2Fdc8b601e-c17e-40e4-a740-1f5369ef82fe.png?alt=media&token=c27ad01a-e03d-49a2-b888-756a001c85cd)

<SwmMeta version="3.0.0" repo-id="Z2l0aHViJTNBJTNBYXdzLWRldmVsb3Blci1pcSUzQSUzQWZhcm9vcXRleHQ=" repo-name="aws-developer-iq"><sup>Powered by [Swimm](https://app.swimm.io/)</sup></SwmMeta>
