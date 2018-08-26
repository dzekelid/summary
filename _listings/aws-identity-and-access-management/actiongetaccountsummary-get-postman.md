{
  "info": {
    "name": "AWS Identity and Access Management API Get Account Summary",
    "_postman_id": "f36b5f9d-75f0-4050-9911-7d31d8cbb6a1",
    "description": "Retrieves information about IAM entity usage and IAM quotas in the AWS\n      account.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "OpenID Connect Providers",
      "item": [
        {
          "id": "0fa3670f-6cbb-43f5-b027-3e6394a3a2e7",
          "name": "addClientIDToOpenIDConnectProvider",
          "request": {
            "url": "http://example.com/api/?Action=AddClientIDToOpenIDConnectProvider?ClientID=ClientID&OpenIDConnectProviderArn=OpenIDConnectProviderArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds a new client ID (also known as audience) to the list of client IDs already\n      registered for the specified IAM OpenID Connect (OIDC) provider resource."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d097b177-74d3-42c6-a70e-b18e73a44cfd"
            }
          ]
        },
        {
          "id": "455f7179-5d1b-4756-956e-b643aebf29dc",
          "name": "createOpenIDConnectProvider",
          "request": {
            "url": "http://example.com/api/?Action=CreateOpenIDConnectProvider?ClientIDList.member.N=ClientIDList.member.N&ThumbprintList.member.N=ThumbprintList.member.N&Url=Url",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an IAM entity to describe an identity provider (IdP) that supports."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2a27ee7b-8d4b-4623-95c8-e9c10bc5231f"
            }
          ]
        },
        {
          "id": "6bb0d715-4bf1-4459-a541-b1ccd74dd897",
          "name": "deleteOpenIDConnectProvider",
          "request": {
            "url": "http://example.com/api/?Action=DeleteOpenIDConnectProvider?OpenIDConnectProviderArn=OpenIDConnectProviderArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes an OpenID Connect identity provider (IdP) resource object in IAM."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f0f9cfea-3694-44c4-a76b-9a47ae8d3f5f"
            }
          ]
        }
      ]
    },
    {
      "name": "Role Instance",
      "item": [
        {
          "id": "90971765-057e-4226-bdd2-53d917a6505b",
          "name": "addRoleToInstanceProfile",
          "request": {
            "url": "http://example.com/api/?Action=AddRoleToInstanceProfile?InstanceProfileName=InstanceProfileName&RoleName=RoleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds the specified IAM role to the specified instance profile."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b71015d1-2652-4bf2-ab42-b634c758e3d3"
            }
          ]
        }
      ]
    },
    {
      "name": "User Groups",
      "item": [
        {
          "id": "c88d38d3-0c1f-453e-817b-5dcc39d3db29",
          "name": "addUserToGroup",
          "request": {
            "url": "http://example.com/api/?Action=AddUserToGroup?GroupName=GroupName&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds the specified user to the specified group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7ddf3fa3-2afd-46d5-a765-675ed093f809"
            }
          ]
        }
      ]
    },
    {
      "name": "Group Policies",
      "item": [
        {
          "id": "d16f76f3-19ff-4967-a3cb-aaa7840b02d6",
          "name": "attachGroupPolicy",
          "request": {
            "url": "http://example.com/api/?Action=AttachGroupPolicy?GroupName=GroupName&PolicyArn=PolicyArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Attaches the specified managed policy to the specified IAM group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "47594c18-01d3-49f4-88a4-3914e1279d17"
            }
          ]
        },
        {
          "id": "7e442371-9698-4514-bfed-fb79523ef721",
          "name": "deleteGroupPolicy",
          "request": {
            "url": "http://example.com/api/?Action=DeleteGroupPolicy?GroupName=GroupName&PolicyName=PolicyName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified inline policy that is embedded in the specified IAM\n      group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0e7d8348-0ef9-4113-bcc9-ba7e1acb8491"
            }
          ]
        },
        {
          "id": "53560df0-3700-47c9-817b-17cbb13bed0d",
          "name": "detachGroupPolicy",
          "request": {
            "url": "http://example.com/api/?Action=DetachGroupPolicy?GroupName=GroupName&PolicyArn=PolicyArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Removes the specified managed policy from the specified IAM group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1363df38-cdfb-42ab-96a6-5821431e04be"
            }
          ]
        }
      ]
    },
    {
      "name": "Role Policies",
      "item": [
        {
          "id": "a84d71f9-2985-424c-8de9-2b4884574385",
          "name": "attachRolePolicy",
          "request": {
            "url": "http://example.com/api/?Action=AttachRolePolicy?PolicyArn=PolicyArn&RoleName=RoleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Attaches the specified managed policy to the specified IAM role."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8afd35d6-b60c-4542-975a-975169323bb2"
            }
          ]
        },
        {
          "id": "c69d1d04-cb91-4e15-badd-db91c3e1b158",
          "name": "deleteRolePolicy",
          "request": {
            "url": "http://example.com/api/?Action=DeleteRolePolicy?PolicyName=PolicyName&RoleName=RoleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified inline policy that is embedded in the specified IAM\n      role."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8ba861b8-66bf-4ca2-b84a-f4fef492d344"
            }
          ]
        },
        {
          "id": "85a14227-a8da-49be-b520-d988a342d028",
          "name": "detachRolePolicy",
          "request": {
            "url": "http://example.com/api/?Action=DetachRolePolicy?PolicyArn=PolicyArn&RoleName=RoleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Removes the specified managed policy from the specified role."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "aebdbc27-10d2-433d-af0a-c7bfc4108246"
            }
          ]
        }
      ]
    },
    {
      "name": "User Policies",
      "item": [
        {
          "id": "e5681822-5ae2-4cee-b1ac-12814d7498bb",
          "name": "attachUserPolicy",
          "request": {
            "url": "http://example.com/api/?Action=AttachUserPolicy?PolicyArn=PolicyArn&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Attaches the specified managed policy to the specified user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f8e352e6-5280-4c9b-be1d-d4d78a45abdb"
            }
          ]
        },
        {
          "id": "fa87c5b2-bea3-48b8-b5a0-3427f34f0e01",
          "name": "deleteUserPolicy",
          "request": {
            "url": "http://example.com/api/?Action=DeleteUserPolicy?PolicyName=PolicyName&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified inline policy that is embedded in the specified IAM\n      user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e6ef1be3-4f78-4287-a3ee-e70eebb08b58"
            }
          ]
        },
        {
          "id": "cc073c27-2ea3-4613-bd7f-7227201ffc07",
          "name": "detachUserPolicy",
          "request": {
            "url": "http://example.com/api/?Action=DetachUserPolicy?PolicyArn=PolicyArn&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Removes the specified managed policy from the specified user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1df0634f-0423-4a32-9a93-03b496b99b5e"
            }
          ]
        }
      ]
    },
    {
      "name": "Passwords",
      "item": [
        {
          "id": "e328d622-d33e-47fb-9bce-00670d2a1bc4",
          "name": "changePassword",
          "request": {
            "url": "http://example.com/api/?Action=ChangePassword?NewPassword=NewPassword&OldPassword=OldPassword",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Changes the password of the IAM user who is calling this action."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5a48a9a7-3bf0-42d5-8074-bc7dbe72ac16"
            }
          ]
        }
      ]
    },
    {
      "name": "Access Keys",
      "item": [
        {
          "id": "2964d6ba-bf57-46f1-a7e9-93fc90a4ec91",
          "name": "createAccessKey",
          "request": {
            "url": "http://example.com/api/?Action=CreateAccessKey?UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new AWS secret access key and corresponding AWS access key ID for the\n      specified user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1d897d9a-a38c-4628-84a5-5e8eb4cf4a8d"
            }
          ]
        },
        {
          "id": "6b30d037-73ab-4579-a457-09c56f4302e2",
          "name": "deleteAccessKey",
          "request": {
            "url": "http://example.com/api/?Action=DeleteAccessKey?AccessKeyId=AccessKeyId&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the access key pair associated with the specified IAM user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "77a8a0cf-4a45-4749-b2bf-b63246fc91cb"
            }
          ]
        },
        {
          "id": "c1f98db6-e4de-4f4b-a832-e0ab88c43033",
          "name": "getAccessKeyLastUsed",
          "request": {
            "url": "http://example.com/api/?Action=GetAccessKeyLastUsed?AccessKeyId=AccessKeyId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about when the specified access key was last used."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0cdb3307-e40f-4e13-983f-851df1461bab"
            }
          ]
        }
      ]
    },
    {
      "name": "Account Alias",
      "item": [
        {
          "id": "01147e37-34c6-43bc-8396-493c9255aabf",
          "name": "createAccountAlias",
          "request": {
            "url": "http://example.com/api/?Action=CreateAccountAlias?AccountAlias=AccountAlias",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an alias for your AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8797feab-9cda-49c3-b35c-cc3687fba8bf"
            }
          ]
        },
        {
          "id": "8d5cfafa-fc81-4169-baf2-f7044bc6637a",
          "name": "deleteAccountAlias",
          "request": {
            "url": "http://example.com/api/?Action=DeleteAccountAlias?AccountAlias=AccountAlias",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified AWS account alias."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "eda77d64-0f93-4e29-b1b8-be128ddef292"
            }
          ]
        }
      ]
    },
    {
      "name": "Groups",
      "item": [
        {
          "id": "ffaff65b-1947-4457-a626-c9fb7e98c4ef",
          "name": "createGroup",
          "request": {
            "url": "http://example.com/api/?Action=CreateGroup?GroupName=GroupName&Path=Path",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a34032da-05ce-42d0-ab78-77bed75dfbfc"
            }
          ]
        },
        {
          "id": "128fd2c1-53ea-4ea9-b390-68721adc70bb",
          "name": "deleteGroup",
          "request": {
            "url": "http://example.com/api/?Action=DeleteGroup?GroupName=GroupName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified IAM group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7a87db8e-d029-43b2-9ef9-602553fc7843"
            }
          ]
        }
      ]
    },
    {
      "name": "Instance Profiles",
      "item": [
        {
          "id": "bcb83f1c-6abb-494b-a534-3943ad3b5d07",
          "name": "createInstanceProfile",
          "request": {
            "url": "http://example.com/api/?Action=CreateInstanceProfile?InstanceProfileName=InstanceProfileName&Path=Path",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new instance profile."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9a51adb3-0f6b-4a8f-92a2-83d4e4d3e155"
            }
          ]
        },
        {
          "id": "91c36dbe-7eda-421d-94ab-c63e12fca785",
          "name": "deleteInstanceProfile",
          "request": {
            "url": "http://example.com/api/?Action=DeleteInstanceProfile?InstanceProfileName=InstanceProfileName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified instance profile."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f148cf3e-071d-45c6-89c1-1d919b19ec32"
            }
          ]
        }
      ]
    },
    {
      "name": "Login Profiles",
      "item": [
        {
          "id": "3139f676-7d4b-43cf-935c-5ada403f7280",
          "name": "createLoginProfile",
          "request": {
            "url": "http://example.com/api/?Action=CreateLoginProfile?Password=Password&PasswordResetRequired=PasswordResetRequired&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a password for the specified user, giving the user the ability to access AWS\n      services through the AWS Management Console."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "83365e44-3453-4563-bfdf-d2911f727636"
            }
          ]
        },
        {
          "id": "c75389fd-3786-41fb-b415-50fdaf216cf1",
          "name": "deleteLoginProfile",
          "request": {
            "url": "http://example.com/api/?Action=DeleteLoginProfile?UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the password for the specified IAM user, which terminates the user's ability\n      to access AWS services through the AWS Management Console."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "34dbeb31-a9e4-462a-a8fc-ba554f2e3772"
            }
          ]
        }
      ]
    },
    {
      "name": "Policies",
      "item": [
        {
          "id": "5527be9e-4417-43bf-b198-20877eb71deb",
          "name": "createPolicy",
          "request": {
            "url": "http://example.com/api/?Action=CreatePolicy?Description=Description&Path=Path&PolicyDocument=PolicyDocument&PolicyName=PolicyName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new managed policy for your AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "70660768-d819-456a-9712-3858be17444f"
            }
          ]
        },
        {
          "id": "ea8e803c-a504-4b2e-8881-00c53f3ae2ac",
          "name": "createPolicyVersion",
          "request": {
            "url": "http://example.com/api/?Action=CreatePolicyVersion?PolicyArn=PolicyArn&PolicyDocument=PolicyDocument&SetAsDefault=SetAsDefault",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new version of the specified managed policy."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f56a6b04-50bd-4f7f-b1c1-2294295d27ff"
            }
          ]
        },
        {
          "id": "e78dc3d9-4c0f-4466-a17e-f51fb2db436f",
          "name": "deletePolicy",
          "request": {
            "url": "http://example.com/api/?Action=DeletePolicy?PolicyArn=PolicyArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified managed policy."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "848f4cea-e50f-49d4-abe4-ae7e354bb3f3"
            }
          ]
        },
        {
          "id": "2f915318-235d-46ef-a39d-5e87020c3528",
          "name": "deletePolicyVersion",
          "request": {
            "url": "http://example.com/api/?Action=DeletePolicyVersion?PolicyArn=PolicyArn&VersionId=VersionId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified version from the specified managed policy."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6baa755c-4f40-4d21-9574-1eadecf6f7ef"
            }
          ]
        }
      ]
    },
    {
      "name": "Roles",
      "item": [
        {
          "id": "10a10e23-9298-4971-888f-1c8fe004fddd",
          "name": "createRole",
          "request": {
            "url": "http://example.com/api/?Action=CreateRole?AssumeRolePolicyDocument=AssumeRolePolicyDocument&Path=Path&RoleName=RoleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new role for your AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "93d248b0-47d7-4be7-bafb-18058c3f2011"
            }
          ]
        },
        {
          "id": "0d2b523e-6475-4519-b708-26b46faf2925",
          "name": "deleteRole",
          "request": {
            "url": "http://example.com/api/?Action=DeleteRole?RoleName=RoleName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified role."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7849bdc8-7b7f-4599-bafb-5aac568db289"
            }
          ]
        }
      ]
    },
    {
      "name": "SAML Providers",
      "item": [
        {
          "id": "9d8a4dbd-808a-435f-86f9-0886d068ad48",
          "name": "createSAMLProvider",
          "request": {
            "url": "http://example.com/api/?Action=CreateSAMLProvider?Name=Name&SAMLMetadataDocument=SAMLMetadataDocument",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an IAM resource that describes an identity provider (IdP) that supports SAML\n      2."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d274f1ec-6fde-4568-a85f-9d2d4bc1f042"
            }
          ]
        },
        {
          "id": "ff97973a-8577-4b16-bc31-b4206149a09c",
          "name": "deleteSAMLProvider",
          "request": {
            "url": "http://example.com/api/?Action=DeleteSAMLProvider?SAMLProviderArn=SAMLProviderArn",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a SAML provider resource in IAM."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "422294de-70e9-4157-b055-8122fbd477ff"
            }
          ]
        }
      ]
    },
    {
      "name": "Service Specific Credentials",
      "item": [
        {
          "id": "715d7b56-d8cb-4af2-ba6a-0ff8642a65bd",
          "name": "createServiceSpecificCredential",
          "request": {
            "url": "http://example.com/api/?Action=CreateServiceSpecificCredential?ServiceName=ServiceName&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Generates a set of credentials consisting of a user name and password that can be used\n      to access the service specified in the request."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "39c6274e-904a-42c8-b35c-be444a654346"
            }
          ]
        },
        {
          "id": "901d9a97-aed6-4a6c-8e02-b465210356f1",
          "name": "deleteServiceSpecificCredential",
          "request": {
            "url": "http://example.com/api/?Action=DeleteServiceSpecificCredential?ServiceSpecificCredentialId=ServiceSpecificCredentialId&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified service-specific credential."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b1d3fd2d-3998-42ff-9cf0-48118b3b9fd1"
            }
          ]
        }
      ]
    },
    {
      "name": "Users",
      "item": [
        {
          "id": "ed896dae-8940-49fe-8a75-ef000b262bcc",
          "name": "createUser",
          "request": {
            "url": "http://example.com/api/?Action=CreateUser?Path=Path&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new IAM user for your AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b3e6ebe7-23eb-4a1d-bf32-9638656023c3"
            }
          ]
        },
        {
          "id": "d5833a22-fb80-4017-9506-1ad51d115eb6",
          "name": "deleteUser",
          "request": {
            "url": "http://example.com/api/?Action=DeleteUser?UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified IAM user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9c4bbd22-d710-4821-a14d-7f5bbe13790f"
            }
          ]
        }
      ]
    },
    {
      "name": "Virtual MFA Device",
      "item": [
        {
          "id": "ad5472f8-ae2d-4347-bad8-2a62cfb2c9f1",
          "name": "createVirtualMFADevice",
          "request": {
            "url": "http://example.com/api/?Action=CreateVirtualMFADevice?Path=Path&VirtualMFADeviceName=VirtualMFADeviceName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new virtual MFA device for the AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8dea1406-4f88-4a19-9b64-b5c2d926cf2b"
            }
          ]
        },
        {
          "id": "3a0ef56b-b08c-4a7a-ac27-96ba7c1cd9cd",
          "name": "deactivateMFADevice",
          "request": {
            "url": "http://example.com/api/?Action=DeactivateMFADevice?SerialNumber=SerialNumber&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deactivates the specified MFA device and removes it from association with the user name\n      for which it was originally enabled."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5c5a2327-3c18-4952-a6ee-eb66a90b405b"
            }
          ]
        }
      ]
    },
    {
      "name": "Account Password Policies",
      "item": [
        {
          "id": "71fa7c61-c8b4-4e2d-86e4-178a9e69ec67",
          "name": "deleteAccountPasswordPolicy",
          "request": {
            "url": "http://example.com/api/?Action=DeleteAccountPasswordPolicy?LimitExceeded=LimitExceeded&NoSuchEntity=NoSuchEntity&ServiceFailure=ServiceFailure",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the password policy for the AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e9ea8b2b-e1bd-4c29-9845-0698fd929aa5"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Certificates",
      "item": [
        {
          "id": "791a6db6-22e4-4494-9cda-69642107e0e8",
          "name": "deleteServerCertificate",
          "request": {
            "url": "http://example.com/api/?Action=DeleteServerCertificate?ServerCertificateName=ServerCertificateName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified server certificate."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "abccc132-89ba-451f-865d-ebcd22dbd94e"
            }
          ]
        }
      ]
    },
    {
      "name": "Signing Certificates",
      "item": [
        {
          "id": "f463a1b5-56a2-468f-8375-d77954267495",
          "name": "deleteSigningCertificate",
          "request": {
            "url": "http://example.com/api/?Action=DeleteSigningCertificate?CertificateId=CertificateId&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a signing certificate associated with the specified IAM user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ec798c39-34c8-47a5-823a-91370fcb824c"
            }
          ]
        }
      ]
    },
    {
      "name": "SSH Public Key",
      "item": [
        {
          "id": "614a0fb7-6068-458f-8056-1f1a4cf312fc",
          "name": "deleteSSHPublicKey",
          "request": {
            "url": "http://example.com/api/?Action=DeleteSSHPublicKey?SSHPublicKeyId=SSHPublicKeyId&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified SSH public key."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0801b073-b738-4e52-8259-318a8e0b5133"
            }
          ]
        }
      ]
    },
    {
      "name": "Virtual MFA Devices",
      "item": [
        {
          "id": "c5009a46-6dfe-408d-b02c-f6b34a46a5ef",
          "name": "deleteVirtualMFADevice",
          "request": {
            "url": "http://example.com/api/?Action=DeleteVirtualMFADevice?SerialNumber=SerialNumber",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a virtual MFA device."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8064c70e-38e8-448c-8723-527fd7c052be"
            }
          ]
        }
      ]
    },
    {
      "name": "MFA Devices",
      "item": [
        {
          "id": "22ffd8d1-0a27-4507-99f2-134171600f77",
          "name": "enableMFADevice",
          "request": {
            "url": "http://example.com/api/?Action=EnableMFADevice?AuthenticationCode1=AuthenticationCode1&AuthenticationCode2=AuthenticationCode2&SerialNumber=SerialNumber&UserName=UserName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Enables the specified MFA device and associates it with the specified IAM user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ae8b3256-d36f-485f-b282-522e65637b52"
            }
          ]
        }
      ]
    },
    {
      "name": "Credential Reports",
      "item": [
        {
          "id": "ac9511de-6ba5-4142-98f5-c08d08783539",
          "name": "generateCredentialReport",
          "request": {
            "url": "http://example.com/api/?Action=GenerateCredentialReport?Description=Description&State=State",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Generates a credential report for the AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "aa049564-5fc1-4529-8a69-a53cffb97423"
            }
          ]
        }
      ]
    },
    {
      "name": "Accounts",
      "item": [
        {
          "id": "488c1874-58ac-4b27-a2c8-d67efd62cbef",
          "name": "getAccountAuthorizationDetails",
          "request": {
            "url": "http://example.com/api/?Action=GetAccountAuthorizationDetails?Filter.member.N=Filter.member.N&Marker=Marker&MaxItems=MaxItems",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about all IAM users, groups, roles, and policies in your AWS\n      account, including their relationships to one another."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e6ad80ee-6530-420f-8b14-47247cfab9d9"
            }
          ]
        },
        {
          "id": "939ba51f-c74a-4c7d-8d28-ea04532ff744",
          "name": "getAccountPasswordPolicy",
          "request": {
            "url": "http://example.com/api/?Action=GetAccountPasswordPolicy?PasswordPolicy=PasswordPolicy",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves the password policy for the AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0c1a594c-f56b-469e-8819-a7abdbd8fe46"
            }
          ]
        },
        {
          "id": "eaab638c-ace4-4b4d-a5a6-73209170a43e",
          "name": "getAccountSummary",
          "request": {
            "url": "http://example.com/api/?Action=GetAccountSummary?SummaryMap\n            , SummaryMap.entry.N.key (key), SummaryMapentry.N.value (value)=SummaryMap%0A%20%20%20%20%20%20%20%20%20%20%20%20%2C%20SummaryMap.entry.N.key%20%28key%29%2C%20SummaryMapentry.N.value%20%28value%29",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves information about IAM entity usage and IAM quotas in the AWS\n      account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "92ab49b5-293b-4458-b45c-02872d6b9fba"
            }
          ]
        }
      ]
    }
  ]
}