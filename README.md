# Unhandled Promise Rejection in Next.js 15 API Route

This repository demonstrates a common error in Next.js 15 API routes where an unhandled promise rejection leads to application crashes.  The example showcases an API route that performs an asynchronous operation which may fail, causing a silent crash unless correctly handled. The solution provides the correct implementation for error handling.

## How to Reproduce

1. Clone this repository.
2. Run `npm install`
3. Run `npm run dev`
4. Make a request to `/api/data`.
5. Observe the error in your console. 

## Solution

The solution demonstrates how to properly handle promise rejections and return appropriate error responses to the client, preventing application crashes.