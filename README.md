
# Password Strength Checker - OWASP  

`Password_Strenght_checker_OWASP` is a password-strength tester inspired by the [OWASP Guidelines for enforcing secure passwords][guidelines]. It is a lightweight and extensible solution that can be used both server-side (Node.js) and in-browser to evaluate the strength of user passwords based on multiple complexity rules.

This tool helps ensure that passwords meet security standards, providing real-time feedback to users about their password strength.


## Features

- **Required and Optional Tests**: Passwords are evaluated against essential and optional complexity requirements, offering flexibility for developers.
- **Passphrase Support**: Encourages using passphrases (longer than 20 characters) with less strict complexity checks.
- **Extensible**: Easily customizable by adding or modifying tests based on your security requirements.

## Installation

### Server-side (Node.js)

To install the module in your Node.js project, run:

```sh
npm install password-strength-checker-owasp
```

### In-browser

Include the script in your HTML file:

```html
<script src='password-strength-checker-owasp.js'></script>
```

## Usage

Once installed, this module can be used in your server-side application or on your website to evaluate password strength.

### Where to Integrate

- **Web Applications**: Integrate into user registration and login forms to enforce strong password requirements.
- **Backend Services**: Use it as part of your API to check password strength before storing them.
- **Real-time Feedback**: Display password strength to users as they type, helping them choose secure passwords.

## Configuration

You can configure the strength checker to adjust the complexity rules, such as minimum password length, passphrase handling, and more. This ensures that the tool fits your application's specific security policies.

## Testing

To run tests for the module, simply run the following command in the project directory:


```sh
npm install
```

```sh
npm test
```

Note : for demo open index.html

## Contributing

Feel free to contribute by forking the repository, making improvements, and submitting pull requests. We welcome new ideas and enhancements!

[guidelines]: https://www.owasp.org/index.php/Authentication_Cheat_Sheet#Implement_Proper_Password_Strength_Controls
