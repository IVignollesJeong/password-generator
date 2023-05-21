# Password Generator

## Description

This project called for the development of a password generating web application. This application was required to provide a secure and unique password following the user's inputs for a series of prompts. The assignment's criteria were as follows: 

- Upon clicking the button to generate a password, the user must answer a series of prompts to generate a unique and secure password.
- When prompted for the length of the password, the user must choose a length between 8 and 128 characters.
- When prompted on selecting whether to include special, numerical, lowercase, or uppercase characters, the user must select at least one character type to proceed.
- Upon completing the series of prompts, the user is presented with a generated password within the page.

## Installation

N/A, the webpage can be reached through the URL found inside the "Usage" section.

Source code for the portfolio page can be found here: [HTML](https://github.com/IVignollesJeong/password-generator/blob/master/index.html) // [Assets: JavaScript + CSS](https://github.com/IVignollesJeong/password-generator/tree/master/assets).

## Usage

![PassGenGif](https://github.com/IVignollesJeong/password-generator/assets/131202032/02e17e16-0520-44db-abc9-d6a6281e7bd8)

The application functions as follows:

- User is presented with an empty text box and "Generate Password button" on page initialization.
- Upon clicking the "Generate Password Button", the user is then prompted with a series of password creation criteria.
- User inputs the desired password character length (between 8 and 128 characters), then confirms or denies if they would like special characters, numerical characters, lowercase characters, or uppercase characters in their generated password.
- Once these prompts are completed, the page will generate and present the password in the "Your Secure Password" text box to be selected and copied to the clipboard.

## Credits

[w3schools array help](https://www.w3schools.com/jsref/jsref_push.asp) </br>
[MP4 to GIF converter](https://cloudconvert.com/mp4-to-gif) </br>
Starter code - OSU Bootcamp Slack

## License

MIT License

Copyright (c) [2023] [Ian Vignolles-Jeong]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Features

The application allows for the choice of including or excluding any of the generation criteria. This includes:
- Special characters or no special characters
- Numerical characters or no numerical characters
- Lowercase characters or no lowercase characters
- Uppercase characters or no uppercase characters

Keep in mind that at least ONE of these choices must be selected for the password generator to function. The character length must also be between 8 and 128. </br> 
Failure to meet these two criteria will result in an error alert and abort the password generation process. </br>
If the password generation process is aborted, simply click the "Generate Password" button again to restart the criteria prompts.