Wrapper response library is a .NET Core Library that can be used on .NET Core Web API. The purpose of this library is to display api response in the format below:

Success Response:
{
   "code": 200,
   "result": [],
   "source": "identity.api.users"
}

Error Response:
{
   "code": 401,
   "message": "Unauthorized",
   "source": "identity.api.users"
}
