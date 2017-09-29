---
title: Platform.IAuthCodeHandler 
description: Provides a method for getting an authorization token.
keywords: microsoft, windows, project rome, android api reference
---

# Platform.IAuthCodeHandler interface
Provides a method for getting an authorization token, as part of the platform initialization process.

## Syntax
`public interface IAuthCodeHandler`

## Public methods

### onAuthCodeFetched
Called by the Remote Systems platform when it is initializing and has acquired a new authorization code.

`void onAuthCodeFetched(String authCode)`

#### Parameters  
*authCode* - the previous authorization code that the system will attempt to refresh