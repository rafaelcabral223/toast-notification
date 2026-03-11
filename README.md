# Toast Notification

![](https://github.com/user-attachments/assets/9692940d-bb38-4510-9d07-accb3d3ad5e7)

| :placard:  |                                       |
| --------------------- | ------------------------------------- |
| :sparkles: Name       | **Toast Notification**                |
| :label: Technologies  | html, css, javascript                 |
| :rocket: URL          | https://toastnoti.netlify.app        |

## About

This project is a simple implementation of Toast Notifications using JavaScript. Clicking the button generates a toast with a random message and type (`info`, `success`, or `error`), which automatically disappears after 3 seconds.

## Features

- Random toast messages and types on each button click
- Three notification styles: `info`, `success`, and `error`
- Toasts auto-dismiss after 3 seconds
- Supports custom message and type via function parameters

## How It Works

1. Clicking the button calls `createNotification()`.
2. A new `div` with the class `toast` and a random type is created and appended to the toasts container.
3. A random message from the `messages` array is displayed inside the toast.
4. After 3 seconds, the toast is automatically removed from the DOM.