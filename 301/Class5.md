# Thinking in React

## Start mocking

We should always start with a mock, either provided by a designer/design team in those big projects or made by ourselves if it's a small personal project. So let's say we want the classic login experience:

![image](https://res.cloudinary.com/practicaldev/image/fetch/s--cpZbF37j--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://dev-to-uploads.s3.amazonaws.com/i/0d9t0taa1auflw6wey22.png)

## Break mock into components

![image](https://res.cloudinary.com/practicaldev/image/fetch/s--1pxUtPXv--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://dev-to-uploads.s3.amazonaws.com/i/1gr7arw4ccr6jfs84dzb.png)

Once identified, we should use clear names for every "component" (PascalCase by React convention):

- LoginForm (red): The whole login form.

- SubmitButton (green): The button to submit the "form".

- Label (pink): The form labels.

- Input (orange): The form inputs.

- PasswordInput (light blue): The form input with type password.

## Early optimizations

While working on the components, we might detect optimizations such as every time we use an Input or PasswordInput component, we add a Label to it, so in order to keep DRY.

## Higher-order functions

Functions that operate on other functions, either by taking them as arguments or by returning them, are called higher-order functions. Since we have already seen that functions are regular values, there is nothing particularly remarkable about the fact that such functions exist. The term comes from mathematics, where the distinction between functions and other values is taken more seriously.

Higher-order functions allow us to abstract over actions, not just values. They come in several forms.
