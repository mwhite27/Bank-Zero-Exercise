# Auth0 - Bank Zero, Java Script Log-In

This sample demonstrates a PoC application for Bank Zero based on their requirements, using the Auth0 Java Script sample app. The sample makes use of Auth0's hosted login page which provides centralized authentication. The application demonstrates the following requirements:

1. Ability to log in or sign up for an account, using the Auth0 Universal log-in page.
2. The ability to log in with one of two social site settings: Google or LinkedIn.
3. During authentication of the user, captures the role of the user, applying the appropriate permissions based on the role.
	a. The role is being captured via a custom claim on the ID token, applied to a rule in the Auth0 Dashboard.
4. Though not a specific requirement, the authentication process includes requesting the user's profile, demonstrating how Bank Zero can collect data on the user for their own purposes.


## Run the Application

The `serve` module provided with this sample can be run with the `start` command.

```bash
npm start
```

The application will be served at `http://localhost:3000`.


## What is Auth0?

Auth0 helps you to:

* Add authentication with [multiple authentication sources](https://docs.auth0.com/identityproviders), either social like **Google, Facebook, Microsoft Account, LinkedIn, GitHub, Twitter, Box, Salesforce, among others**, or enterprise identity systems like **Windows Azure AD, Google Apps, Active Directory, ADFS or any SAML Identity Provider**.
* Add authentication through more traditional **[username/password databases](https://docs.auth0.com/mysql-connection-tutorial)**.
* Add support for **[linking different user accounts](https://docs.auth0.com/link-accounts)** with the same user.
* Support for generating signed [Json Web Tokens](https://docs.auth0.com/jwt) to call your APIs and **flow the user identity** securely.
* Analytics of how, when and where users are logging in.
* Pull data from other sources and add it to the user profile, through [JavaScript rules](https://docs.auth0.com/rules).


## Issue Reporting

If you have found a bug or if you have a feature request, please report them at this repository issues section. Please do not report security vulnerabilities on the public GitHub issue tracker. The [Responsible Disclosure Program](https://auth0.com/whitehat) details the procedure for disclosing security issues.

## Author

[Auth0](https://auth0.com)

## License

This project is licensed under the MIT license. See the [LICENSE](LICENSE.txt) file for more info.








