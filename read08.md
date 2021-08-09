# [reading-note-301](https://mohammadsilwadi.github.io/reading-note-301/)


##  APIs

## What does REST stand for?

representational state transfer

## REST APIs are designed around a ____.
resources
## What is an identifer of a resource? Give an example.
International Standard Book Number (ISBN) system, ISBN 0-486-27557-4
## What are the most common HTTP verbs?
The primary or most-commonly-used HTTP verbs (or methods, as they are properly called) are POST, GET, PUT, PATCH, and DELETE.

## What should the URIs be based on?
on nouns (the resource) and not verbs (the operations on the resource).

## Give an example of a good URI.
https://adventure-works.com/orders // Good

## What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
good thing , Chatty API is one that requires consumer to make tremendous (subjective matter) amount of distinct API calls to get needed information about a resource.

## What status code does a successful GET request return?
2xx
## What status code does an unsuccessful  GET request return?
400
## What status code does a successful POST request return?
HTTP response code 200 (OK) if the response includes an entity describing the status, 202 (Accepted) if the action has been queued, or 204 (No Content) if the action has been performed but the response does not include an entity.