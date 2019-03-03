# Redact-On
Problem Statment: Redaction of sensitive personal information from unstructured text.

Solution: 
Name of the Web based service: Redact-on.
Services used to make Redact-on are IBM Natural Language understanding, IBM Watson Knowledge Studio and Node Js 
respectively.
This service basically hides or masks all the sensitive data present in data that you give as input,
you recieve the redacted or masked data as output, where all the sensitive data as per Personal Data Protection Bill is hidden.
The service is 50 % accurate according to IBM WKS.
We have used WKS and NLU to extract the entities followed by some algorithms to decide which data is sensitive and a function to mask them.
We finally made a web based application to take input from users and produce the redacted text.  

