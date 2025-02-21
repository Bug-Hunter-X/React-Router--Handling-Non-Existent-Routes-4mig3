# React Router: Handling Non-Existent Routes

This repository demonstrates a common error in React Router v6 and its solution. The problem occurs when navigating to a route that is not defined in your `Routes` component.  Without proper handling, this can lead to unexpected behavior, such as crashes or unexpected content display.

## The Problem

The provided `App.js` demonstrates an incomplete route configuration.  It defines routes for `/` and `/about`, but lacks a catch-all route to handle any other URL. This omission results in an error when a user attempts to navigate to a path not explicitly defined.  This may manifest as a blank page, a crash, or some default behavior.