# ixradiocheckboxissue
Example project to demonstrate a bug in IX version 2.6.1

When an ix-radio or ix-checkbox is wrapped in a div tag, it does jump a few pixels vertical when clicked.
Outside div it works as expected.
Remark: in our case we wrap it in tst-ui-radio and tst-ui-checkbox, but it is the same effect when just using a div element as encapsulation

relevant coding to reproduce issue can be found in files
  - app.component.html

To start project open terminal and execute the following commands:
  - npm install
  - npm run start

then open in browser url http://127.0.0.1:4200/
