# React Router Dom v6 Nested Routes Issue

This repository demonstrates a common issue encountered when using nested routes in React Router Dom v6. The problem arises when routes are nested within other components, leading to unexpected rendering behavior.

## Problem

The main App component includes nested routes, but these routes fail to render correctly. The application displays a blank screen or doesn't navigate as expected.

## Solution

The issue is solved by restructuring the application to utilize the correct routing configuration. The solution involves ensuring that the Routes component is nested appropriately. This ensures that routes are handled correctly within the application's hierarchy.