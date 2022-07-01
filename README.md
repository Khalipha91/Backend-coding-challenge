Backend-coding-challenge

Build a service in Node.js that exposes an API which can be consumed from any client.This service must check how many video streams a given user is watching and prevent a user from watching more than 3 video streams concurrently.

'''URL to check API in AWS Lamda

The api can be accessed at  https://na2vwv35d5.execute-api.us-east-1.amazonaws.com/dev/stream

'''Challenge

 To fix this problem was one of challenging but with scalability knowledge I have.It was easy to figure the code I will develop to prevent user to watch 3 more videos but the issue was with AWS Lamda function this time to trigger it to perfom this action but will basics on how to create API on AWS I am fully confident about it.

... Instructions

- Installed Node js.
- installed the dependencies npm install http-server -g
- The offline server details are as follows
- http-server version: 14.1.1

http-server settings:
CORS: disabled
Cache: 3600 seconds
Connection Timeout: 120 seconds
Directory Listings: visible
AutoIndex: visible
Serve GZIP Files: false
Serve Brotli Files: false
Default File Extension: none

Available on:
  http://192.168.43.146:8080
  http://127.0.0.1:8080 


''''Scabality

- API Gateway

This allows up to 10,000 requests per second,with a burst of 5000 requests.

Severless

The servers are not managed manually there flexible and I think that makes it best for API intergration.

Dynamo DB

Scabality is design to meet up with any requiremts in terms of Storage.


