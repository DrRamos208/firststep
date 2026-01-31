## Incident Summary
A TLS Authentication Failure occurred when the client was unable to establish a trusted encrypted session with the server.

## Indicators
-UNITYTLS_INTERNAL_ERROR
-Authentication terminated pre-session
-Secure channel not established

## Impact Assessment
-Confidentiality: Protected
-Integrity: Protected
-Availability: Temporarily impacted

##Resolution
Authentication was denied until a secure TLS handshake could be successfully established. 